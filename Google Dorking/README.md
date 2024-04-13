# Google Dorking

## What is Google Dorking?

**Google Dorking**, also known as **Google hacking** - is a technique used by security researchers, hackers, and penetration testers to discover sensitive information indexed by Google's search engine. 

It involves using advanced search operators to refine search queries and uncover information that might not be easily accessible through conventional searches.


## Google dorks includes:

1. [intitle](#intitle)
2. [allintitle](#allintitle)
3. [inurl](#inurl)
4. [allinurl](#allinurl)
5. [filetype:env](#filetypeenv)
6. [intext](#intext)
7. [allintext](#allintext)
8. [site](#site)
9. [link](#link)
10. [inanchor](#inanchor)
11. [numrange](#numrange)
12. [daterange](#daterange)
13. [author](#author)
14. [group](#group)
15. [insubject](#insubject)
16. [msgid](#msgid)

These operators can be combined and used creatively to discover information indexed by Google.

## intitle

`intitle:` Find pages with a specific word or phrase in the title.

Example: 
``` 
intitle:Google Dorks 
```

## allintitle

`allintitle:` Find pages where all specified words or phrases appear in the title.

Example: 
```
allintitle:Google Dorks Tutorial
```

## inurl

`inurl:` Find pages with a specific word or phrase in the URL.

Example: 
```
inurl:admin
```

## allinurl

`allinurl:` Find pages where all specified words or phrases appear in the URL.

Example: 
```
allinurl:admin login
```

## filetype:env

`filetype:env:` Find environmental files.

Example: 
```
filetype:env DB_PASSWORD
```

## intext

`intext:` Find pages containing a specific word or phrase in the text.

Example: 
```
intext:password filetype:txt
```

## allintext

`allintext:` Find pages where all specified words or phrases appear in the text.

Example: 
```
allintext:password admin login
```

## site

`site:` Limit search results to a specific website or domain.

Example: 
```
site:wikipedia.org Google Dorks
```

## link

`link:` Find pages that link to a specific URL.

Example: 
```
link:example.com
```

## inanchor

`inanchor:` Find pages with a specific word or phrase in the anchor text of links.

Example: 
```
inanchor:"best SEO tools"
```

## numrange

`numrange:` Find pages containing numbers within a specific range.

Example: 
```
numrange:10-100 password
```

## daterange

`daterange:` Limit search results to pages published within a specific date range.

Example: 
```
daterange:2023-2024 cybersecurity
```

## author

`author:` Find pages written by a specific author.

Example: 
```
author:"Jon Erickson"
```

## group

`group:` Find pages related to a specific newsgroup.

Example: 
```
group:sci.math
```

## insubject

`insubject:` Find pages with a specific word or phrase in the subject line.

Example: 
```
insubject:"Assembly programming"
```

## msgid

`msgid:` Find pages containing a specific message ID.

Example: 
```
msgid:ABC123456789
```