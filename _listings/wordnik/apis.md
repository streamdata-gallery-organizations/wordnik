---
name: Wordnik
x-slug: wordnik
description: Wordnik is an online English dictionary and language resource that provides
  dictionary and thesaurus content, some of it based on print dictionaries such as
  the Century Dictionary, the American Heritage Dictionary, WordNet, and GCIDE. Wordnik
  has collected a corpus of billions of words which it uses to display example sentences,
  allowing it to provide information on a much larger set of words than a typical
  dictionary.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
x-kinRank: "8"
x-alexaRank: "46540"
tags: Wordnik
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/apis.md
specificationVersion: "0.14"
apis:
- name: Wordnik Returns usage statistics for the API account.
  x-api-slug: wordnik
  description: Returns usage statistics for the api account..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//account.json/apiTokenStatus
  tags: Account,ApiTokenStatus
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/account-jsonapitokenstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/account-jsonapitokenstatus-get-openapi.md
- name: Wordnik Authenticates a User
  x-api-slug: wordnik
  description: Authenticates a user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//account.json/authenticate/{username}
  tags: Account,Authenticate,Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/account-jsonauthenticateusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/account-jsonauthenticateusername-get-openapi.md
- name: Wordnik Authenticates a user
  x-api-slug: wordnik
  description: Authenticates a user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//account.json/authenticate/{username}
  tags: Account,Authenticate,Username
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/account-jsonauthenticateusername-post-openapi.md
- name: Wordnik Returns the logged-in User
  x-api-slug: wordnik
  description: Requires a valid auth_token to be set.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//account.json/user
  tags: Account,User
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/account-jsonuser-get-openapi.md
- name: Wordnik Fetches WordList objects for the logged-in user.
  x-api-slug: wordnik
  description: Fetches wordlist objects for the logged-in user..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//account.json/wordLists
  tags: Account,Words,Lists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/account-jsonwordlists-get-openapi.md
- name: Wordnik Given a word as a string, returns the WordObject that represents it
  x-api-slug: wordnik
  description: Given a word as a string, returns the wordobject that represents it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//word.json/{word}
  tags: Words
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonword-get-openapi.md
- name: Wordnik Fetches audio metadata for a word.
  x-api-slug: wordnik
  description: The metadata includes a time-expiring fileUrl which allows reading
    the audio file directly from the API.  Currently only audio pronunciations from
    the American Heritage Dictionary in mp3 format are supported.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//word.json/{word}/audio
  tags: Words,Audio
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonwordaudio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonwordaudio-get-openapi.md
- name: Wordnik Return definitions for a word
  x-api-slug: wordnik
  description: Return definitions for a word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//word.json/{word}/definitions
  tags: Words,Definitions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonworddefinitions-get-openapi.md
- name: Wordnik Fetches etymology data
  x-api-slug: wordnik
  description: Fetches etymology data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//word.json/{word}/etymologies
  tags: Words,Etymologies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonwordetymologies-get-openapi.md
- name: Wordnik Returns examples for a word
  x-api-slug: wordnik
  description: Returns examples for a word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//word.json/{word}/examples
  tags: Words,Examples
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonwordexamples-get-openapi.md
- name: Wordnik Returns word usage over time
  x-api-slug: wordnik
  description: Returns word usage over time.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//word.json/{word}/frequency
  tags: Words,Frequency
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonwordfrequency-get-openapi.md
- name: Wordnik Returns syllable information for a word
  x-api-slug: wordnik
  description: Returns syllable information for a word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//word.json/{word}/hyphenation
  tags: Words,Hyphenation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonwordhyphenation-get-openapi.md
- name: Wordnik Fetches bi-gram phrases for a word
  x-api-slug: wordnik
  description: Fetches bi-gram phrases for a word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//word.json/{word}/phrases
  tags: Words,Phrases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonwordphrases-get-openapi.md
- name: Wordnik Returns text pronunciations for a given word
  x-api-slug: wordnik
  description: Returns text pronunciations for a given word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//word.json/{word}/pronunciations
  tags: Words,Pronunciations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonwordpronunciations-get-openapi.md
- name: Wordnik Given a word as a string, returns relationships from the Word Graph
  x-api-slug: wordnik
  description: Given a word as a string, returns relationships from the word graph.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//word.json/{word}/relatedWords
  tags: Words,RelatedWords
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonwordrelatedwords-get-openapi.md
- name: Wordnik Returns a top example for a word
  x-api-slug: wordnik
  description: Returns a top example for a word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//word.json/{word}/topExample
  tags: Words,TopExample
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/word-jsonwordtopexample-get-openapi.md
- name: Wordnik Deletes an existing WordList
  x-api-slug: wordnik
  description: Deletes an existing wordlist.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//wordList.json/{permalink}
  tags: WordList,Permalink
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/wordlist-jsonpermalink-delete-openapi.md
- name: Wordnik Fetches a WordList by ID
  x-api-slug: wordnik
  description: Fetches a wordlist by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//wordList.json/{permalink}
  tags: WordList,Permalink
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/wordlist-jsonpermalink-get-openapi.md
- name: Wordnik Updates an existing WordList
  x-api-slug: wordnik
  description: Updates an existing wordlist.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//wordList.json/{permalink}
  tags: WordList,Permalink
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/wordlist-jsonpermalink-put-openapi.md
- name: Wordnik Removes words from a WordList
  x-api-slug: wordnik
  description: Removes words from a wordlist.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//wordList.json/{permalink}/deleteWords
  tags: WordList,Permalink,DeleteWords
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/wordlist-jsonpermalinkdeletewords-post-openapi.md
- name: Wordnik Fetches words in a WordList
  x-api-slug: wordnik
  description: Fetches words in a wordlist.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//wordList.json/{permalink}/words
  tags: WordList,Permalink,Words
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/wordlist-jsonpermalinkwords-get-openapi.md
- name: Wordnik Adds words to a WordList
  x-api-slug: wordnik
  description: Adds words to a wordlist.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//wordList.json/{permalink}/words
  tags: WordList,Permalink,Words
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/wordlist-jsonpermalinkwords-post-openapi.md
- name: Wordnik Creates a WordList.
  x-api-slug: wordnik
  description: Creates a wordlist..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//wordLists.json
  tags: Words,Lists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/wordlists-json-post-openapi.md
- name: Wordnik Returns a single random WordObject
  x-api-slug: wordnik
  description: Returns a single random wordobject.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//words.json/randomWord
  tags: Words,RandomWord
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/words-jsonrandomword-get-openapi.md
- name: Wordnik Returns an array of random WordObjects
  x-api-slug: wordnik
  description: Returns an array of random wordobjects.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//words.json/randomWords
  tags: Words,RandomWords
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/words-jsonrandomwords-get-openapi.md
- name: Wordnik Reverse dictionary search
  x-api-slug: wordnik
  description: Reverse dictionary search.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//words.json/reverseDictionary
  tags: Words,ReverseDictionary
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/words-jsonreversedictionary-get-openapi.md
- name: Wordnik Searches words
  x-api-slug: wordnik
  description: Searches words.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//words.json/search/{query}
  tags: Words,Search,Query
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/words-jsonsearchquery-get-openapi.md
- name: Wordnik Returns a specific WordOfTheDay
  x-api-slug: wordnik
  description: Returns a specific wordoftheday.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4//words.json/wordOfTheDay
  tags: Words,WordOfTheDay
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/words-jsonwordoftheday-get-openapi.md
- name: Wordnik
  x-api-slug: wordnik
  description: The Wordnik API lets you request definitions, example sentences, spelling
    suggestions, related words like synonyms and antonyms, phrases containing a given
    word, word autocompletion, random words, words of the day, and much more.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Wordnik
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/wordnik/master/_listings/wordnik/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/wordnik
- type: x-developer
  url: http://developer.wordnik.com/
- type: x-documentation
  url: http://developer.wordnik.com/docs.html
- type: x-email
  url: feedback@wordnik.com
- type: x-email
  url: support@wordnik.com
- type: x-email
  url: privacy@wordnik.com
- type: x-email
  url: dmca@wordnik.com
- type: x-github
  url: https://github.com/wordnik
- type: x-twitter
  url: https://twitter.com/wordnik
- type: x-website
  url: http://wordnik.com
- type: x-website
  url: https://www.wordnik.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---