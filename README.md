![Rezeptsammlung Familie Stumpp](github-readme.png)

[![Netlify Status](https://api.netlify.com/api/v1/badges/85a94c4b-0517-41ae-aee6-a03e8c1e0618/deploy-status)](https://app.netlify.com/sites/rezepte-stumpp-name/deploys)

# Recipe Collector

The recipe collector is a collection blog for cooking recipes for my family. It is based on the [Eleventy](https://11ty.io) template ["My Online Cookbook"](https://github.com/maeligg/my-online-cookbook) by @maeligg. I translated the whole thing into German, adapted the colours and made a few minimal changes in the templates.

## Changes:
  * added variable sourceCaption(site.json)
  * uses variable sourceCaption|default("Quelle") as label (recipe.njk)
  * added div to limit max size of pictures (recipes-list.njk)
  * removed *authorintitle* from home page 
  * changed primary color from **#ffdb70** to **#70dbff**
  * unchanged secondary color  **#32816e**
  * Initial deploy to [Netlify](https://app.netlify.com/start/deploy?repository=https://github.com/m-e-st/recipe-collector&stack=cms)

## Wichtiger Hinweis an die Familie

Der Deploy der Rezepte funktioniert nicht, wenn einfach die **.md**-Datei in das Repository geladen wird. Man muß vielmehr das Rezept einmal lokal mit Eleventy generieren ( *npm run dev* ), damit das Rezeptbild richtig generiert wird. Es ist sowieso eine gute Idee, nur Rezepte hochzuladen, die getestet sind.

Wem das zu kompliziert ist, der kann die Rezepte gerne in der Familien-Cloud ablegen und ich lade sie dann gelegentlich ins [Rezeptbuch](https://rezepte.stumpp.name) hoch.

## Information from the creator.

"My Online Cookbook" is a starter kit to create your own website of recipes, using [Eleventy](https://11ty.io) and [Netlify CMS](https://www.netlifycms.org/). It is meant to be both highly accessible (including to non-developers), as well as fully customisable should you want to use it as a starting off point.

Original README doc : <https://github.com/maeligg/my-online-cookbook#readme>  
Set-up instructions : <https://myonlinecookbook.xyz/>
