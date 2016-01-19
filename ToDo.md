# Introduction #

  * Importe XLS
  * Exporte XLS, PDF
  * Les secteurs économiques
  * GWT UI
  * Android UI

# Get stock informations #
API Url Formatting
The API from what I can tell is very simple. It only has a single parameter that accepts a stock ticker.
Here’s an example:
http://www.google.com/ig/api?stock=AAPL (described here: http://jarloo.com/tutorials/google-stock-api/)

But for now, because Google's API does not provide historical prices, Yahoo's API is used instead:

- http://finance.yahoo.com/d/quotes.csv?s=GE&f=nkqwxyr1l9t5p4 (described here http://www.gummy-stuff.org/Yahoo-data.htm)



# Industry Sectors #
(the list is in french at this point...)
  * http://biz.yahoo.com/ic/ind_index.html


  * Pétrole & Gaz - 100
    * Producteurs de Pétrole et de Gaz - 101
    * Matériaux de base - 102
  * Industries - 200
    * Bâtiment et matériaux de construction - 201
    * Aérospatiale et Défense - 202
    * Electronique et équipements électriques - 203
    * Ingénierie industrielle - 203
    * Transport industriel - 204
    * Services supports - 205
  * Biens de consommation - 300
    * Automobiles et équipementiers - 301
    * Boissons - 302
    * Agro-alimentaire - 303
    * Produits ménagers - 304
    * Equipements de loisirs - 305
    * Articles personnels - 306
  * Santé - 400
    * Hygiène Santé Cosmétiques - 401
    * Équipements et services de santé - 402
  * Services aux consommateurs - 500
    * Distribution spécialisée - 501
    * Distributeurs généralistes - 502
    * Médias et publicité - 503
    * Voyages et loisirs - 504
  * Télécommunications - 600
    * Télécommunications - 601
  * Services aux collectivités - 700
    * Gaz, eau et services multiples aux collectivités - 701
  * Société Financières - 800
    * Banques - 801
    * Assurances - non vie - 802
    * Immobilier - 803
    * Finances - Général - 804
  * Technologie - 900
    * Logiciels et services informatiques - 901
    * Matériel et équipements informatiques - 902