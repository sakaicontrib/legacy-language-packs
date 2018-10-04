# Sakai Legacy Language Packs
Some language packs that have been marked as unmantained by the community have been moved to this repository before releasing Sakai 19.

|Locale|Archived|Version|
|---|---|---|
|es_MX|2018-10-03|Sakai 19|
|de|2018-10-04|Sakai 19|
|pl_PL|2018-10-04|Sakai 19|
|it|2018-10-04|Sakai 19|
|fr_CA|2018-10-04|Sakai 19|
|nl|2018-10-04|Sakai 19|
|ar|2018-10-04|Sakai 19|
|ru|2018-10-04|Sakai 19|
|pt_PT|2018-10-04|Sakai 19|
|ko|2018-10-04|Sakai 19|
|zh_TW|2018-10-04|Sakai 19|
|vi|2018-10-04|Sakai 19|
|en_GB|2018-10-04|Sakai 19|

# Legacy Language Pack installation guide

Clone the language packs into your local:

```git clone https://github.com/sakaicontrib/legacy-language-packs```

Copy the language pack that you want to install into your Sakai source (Example for es_MX and Unix OS):

```cp -R sakai_es_MX/* /path/to/your/source```

Install Sakai as usual using maven:

```mvn clean install sakai:deploy```

Enable the locale in your **sakai.properties** adding it at the end of the property: 

```locales = en_US, en_GB, en_AU, en_NZ, es_MX```