Follow these steps to contribute to the project (instructions are with Eclipse only, though you can certainly setup yourself with Netbeans or Intellij)

(1) Generate Google password here: https://code.google.com/hosting/settings

(2) Download and install Eclipse: http://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/keplersr2

(2) Install mercurialeclipse plugin:
  * https://code.google.com/a/eclipselabs.org/p/mercurialeclipse/
  * https://bitbucket.org/mercurialeclipse/main/wiki/Home
  * http://mercurial.selenic.com/
  * http://mercurialeclipse.eclipselabs.org.codespot.com/hg.wiki/update_site/stable

(3) Import 4 projects:
  * https://code.google.com/p/stock-portfolio-manager/source/checkout?repo=bo (project name stock-portfolio-manager.bo)
  * https://code.google.com/p/stock-portfolio-manager/source/checkout?repo=bp  (project name stock-portfolio-manager.bp)
  * https://code.google.com/p/stock-portfolio-manager/source/checkout?repo=ui  (project name stock-portfolio-manager.ui)
  * https://code.google.com/p/stock-portfolio-manager/source/checkout?repo=parent  (project name stock-portfolio-manager.parent)

(4) Install Maven eclipse plugin: http://download.eclipse.org/technology/m2e/releases/1.4/1.4.1.20140328-1905

(5) Make sure you are running Eclipse with a JDK java (not just JRE). This is only to enable Maven command from Eclipse. Get JDK 7 here: http://www.oracle.com/technetwork/java/javase/downloads/index.html

(6) To build:
  * In eclipse, right click on 'stock-portfolio-manager.parent' project and do a Maven-Clean + Maven-Install.
OR
  * Open a terminal prompt
  * Go to your 'stock-portfolio-manager.parent' folder.
  * Type 'mvn clean install'

(7) You'll find the zip/tar.gz packaging in 'stock-portfolio-manager.parent/package/target'

(8) Pick an issue to fix and start coding :)

(9) Drop me an email to let me know, I'll add you as a contributer.