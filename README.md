<h1 align="center">
  <a href="https://datacountry.io" target="_blank"><img src="./assets/logo.jpg" width="175"/></a>
  <br>
  datacountry.io
</h1>

<p align="center">
    <code>datacountry.io</code> is a website to discover the world in figures.
    <br>
    You will find on this repo all the data that powers the site in <b>json format</b>.
</p>

<br>
<br>

# **Introduction**

> All the data described bellow is available in the form of a monolithic json file named using 2 letters country code (_ISO 3166-1 alpha-2_) like so: **nz.json**. In the future I might split the file using the different categories described bellow. <br><br>
> The scraping process can take quite some time (even being fully automated) but I will make sure to update the repo with newest countries as soon as it's ready. <br><br>
> **Note:** Some data may not be available for some countries in which case the value will be set to **-** (dash) as a way to signify it's not available.

<br>
<br>

# **Available countries**

Oceania
--
* 🇻🇺 [Vanuatu](./datasets/oceania/vu.json)
* 🇸🇧 [Solomon Islands](./datasets/oceania/sb.json)
* 🇵🇬 [Papua New Guinea](./datasets/oceania/pg.json)
* 🇳🇿 [New Zealand](./datasets/oceania/nz.json)
* 🇫🇯 [Fiji](./datasets/oceania/fj.json)
* 🇦🇺 [Australia](./datasets/oceania/au.json)


Northern America
--
* 🇨🇦 [Canada](./datasets/northern-america/ca.json)
* 🇺🇸 [United States](./datasets/northern-america/us.json)

Central America
--
* 🇲🇽 [Mexico](./datasets/central-america/mx.json)
* 🇭🇳 [Honduras](./datasets/central-america/hn.json)
* 🇬🇹 [Guatemala](./datasets/central-america/gt.json)
* 🇸🇻 [El Salvador](./datasets/central-america/sv.json)
* 🇨🇷 [Costa Rica](./datasets/central-america/cr.json)
* 🇧🇿 [Belize](./datasets/central-america/bz.json)
* 🇵🇦 [Panama](./datasets/central-america/pa.json)
* 🇳🇮 [Nicaragua](./datasets/central-america/ni.json)

South America
--
* 🇻🇪 [Venezuela](./datasets/south-america/ve.json)
* 🇧🇴 [Bolivia](./datasets/south-america/bo.json)
* 🇺🇾 [Uruguay](./datasets/south-america/uy.json)
* 🇸🇷 [Suriname](./datasets/south-america/sr.json)
* 🇵🇪 [Peru](./datasets/south-america/pe.json)
* 🇵🇾 [Paraguay](./datasets/south-america/py.json)
* 🇬🇾 [Guyana](./datasets/south-america/gy.json)
* 🇪🇨 [Ecuador](./datasets/south-america/ce.json)
* 🇨🇴 [Colombia](./datasets/south-america/co.json)
* 🇨🇱 [Chile](./datasets/south-america/cl.json)
* 🇧🇷 [Brazil](./datasets/south-america/br.json)

Europe
--
* 🇦🇱 [Albania](./datasets/europe/al.json)
* 🇦🇲 [Armenia](./datasets/europe/am.json)
* 🇦🇹 [Austria](./datasets/europe/at.json)
* 🇦🇿 [Azerbaijan](./datasets/europe/az.json)
* 🇧🇾 [Belarus](./datasets/europe/by.json)
* 🇧🇪 [Belgium](./datasets/europe/be.json)
* 🇧🇦 [Bosnia and Herzegovina](./datasets/europe/ba.json)
* 🇧🇬 [Bulgaria](./datasets/europe/bg.json)
* 🇭🇷 [Croatia](./datasets/europe/hr.json)
* 🇨🇾 [Cyprus](./datasets/europe/cy.json)
* 🇨🇿 [Czech Republic](./datasets/europe/cz.json)
* 🇩🇰 [Denmark](./datasets/europe/dk.json)
* 🇪🇪 [Estonia](./datasets/europe/ee.json)
* 🇫🇮 [Finland](./datasets/europe/fi.json)
* 🇫🇷 [France](./datasets/europe/fr.json)
* 🇬🇪 [Georgia](./datasets/europe/ge.json)
* 🇩🇪 [Germany](./datasets/europe/de.json)
* 🇬🇷 [Greece](./datasets/europe/gr.json)
* 🇭🇺 [Hungary](./datasets/europe/hu.json)
* 🇮🇸 [Iceland](./datasets/europe/is.json)
* 🇮🇪 [Ireland](./datasets/europe/ie.json)
* 🇮🇹 [Italy](./datasets/europe/it.json)
* 🇰🇿 [Kazakhstan](./datasets/europe/kz.json)
* 🇱🇻 [Latvia](./datasets/europe/lv.json)
* 🇱🇹 [Lithuania](./datasets/europe/lt.json)
* 🇱🇺 [Luxembourg](./datasets/europe/lu.json)
* 🇲🇰 [Macedonia](./datasets/europe/mk.json)
* 🇲🇩 [Moldova](./datasets/europe/md.json)
* 🇳🇱 [Netherlands](./datasets/europe/nl.json)
* 🇳🇴 [Norway](./datasets/europe/no.json)
* 🇵🇱 [Poland](./datasets/europe/pl.json)
* 🇵🇹 [Portugal](./datasets/europe/pt.json)
* 🇷🇴 [Romania](./datasets/europe/ro.json)
* 🇷🇺 [Russia](./datasets/europe/ru.json)
* 🇷🇸 [Serbia](./datasets/europe/rs.json)
* 🇸🇰 [Slovakia](./datasets/europe/sk.json)
* 🇸🇮 [Slovenia](./datasets/europe/si.json)
* 🇪🇸 [Spain](./datasets/europe/es.json)
* 🇸🇪 [Sweden](./datasets/europe/se.json)
* 🇨🇭 [Switzerland](./datasets/europe/ch.json)
* 🇹🇷 [Turkey](./datasets/europe/tr.json)
* 🇺🇦 [Ukraine](./datasets/europe/ua.json)
* 🇬🇧 [United Kingdom](./datasets/europe/gb.json)

# **Table of Contents**
* [General](#general)
* [Geography](#geography)
* [Environment](#environment)
* [Social](#social)
* [Food](#food)
* [Technology](#technology)

<br>

General
-----------

* **Name**
* **Population** (total, male, female and percentages)
* **Currency** (code, symbol & label)
* **Capital** (name, population & type - some countries can have multiple capitals like judicial, legislative...)

<br>

Geography
-----------

* **Surface area** (year, value & unit)
* **Forest area** (year, value & unit, percentage of country surface)
* **Agricultural area** (year, value & unit, percentage of country surface)
* **Water area** (year, value & unit, percentage of country surface)
* **Largest cities** (top 3 largest cities in the country)
* **Natural resource** (list of natural resources available in the country)
* **Coastline** (total coastline for the country)
* **Elevation highest point** (name and altitude of the highest point in the country in meter)
* **Elevation lowest point** (name and altitude of the lowest point in the country in meter)
* **Highest city** (name and altitude of the highest city in the country in meter)

<br>

Environment
-----------

* **Endangered species** (number of endangered species by type - mammals, birds, reptiles, amphibians, fishes, molluscs & inverts)
* **Plant threatened** (number of threatened plants)
* **Carbon dioxide emissions** (total carbon dioxide emission in Mt)
* **Percent of world emissions** (world emission percentage of carbon dioxide)
* **Electricity production renewable sources** (percentage of electricity produced via natural source(s))
* **Nuclear power plants operation** (total number of nuclear power plant(s) in the country)
* **Nuclear power plants in construction** (total number of nuclear power plant(s) in construction in the country)

<br>

Social
-----------

* **Life expectancy** (life expectancy for male/female in the country)
* **Unemployment rate** (unemployment rate in the country)
* **Growth rate** (growth rate in the country)
* **Sex ratio** (number of men per women in the country)
* **Infant mortality** (infant mortality in the country)
* **Median age** (median age for male/female/total)
* **Fertility rate** (fertility rate)
* **Billionaires** (number of billionaires in the country)
* **Prison population total** (number of prisoners and percentage of the total population)
* **Suffrage**

<br>

Food
-----------

* **Alcohol consumption** (beer/wine/spirits/others and total in litres per capita)
* **McDonalds restaurants** (total of McDonalds restaurants in the country)

<br>

Technology
-----------

* **Internet users** (total Internet users in the country)
* **Internet rank**
* **Internet country code**
* **browsers** (browser repartition for the last year between ie/edge/chrome/safari/firefox/others)
* **Average download** (average download speed for the country in Mpbs)
* **Average upload** (average upload speed for the country in Mpbs)
* **Mobile subscribers** (total number of mobile subscribers and percentage of total population)
* **Social media users** (total number of users in the country for Facebook/Instagram/Messenger)

<br>

<img src="./assets/soon.jpg" width="40" /> Economy
-----------

<img src="./assets/soon.jpg" width="40" /> Military
-----------