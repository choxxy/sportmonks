# Sportmonks
Custom library to access sportmonks API

## Table of contents
* [Usage](#usage)
* [Sportmonks API support](#sportmonks-api-support)
* [Add library in your project](#add-library-in-your-project)

## Usage
You only need obtain the SportmonksAPI instance and invoke requested method.

Example: Request all leagues
`SportMonksAPI.getInstance(SPORTMONKS_API_KEY).getLeagues();`

## Sportmonks API support
The available methods are:
* getTodayMatches
* getLiveMatches
* getMatchesByDate
* getMatchesByDateRange
* getMatchesByDateRangeForTeam
* getMatchesByMultipleIDs
* getMatchDetail
* getSeasons
* getSeasonData
* getMatchOdds
* getMatchOddsByMarket
* getTopScores
* getAggregatedTopScores
* getStandings
* getCupStandings
* getVenues
* getTeams
* getLeagues
* getStages

## Add library in your project
### Add jcenter repository
You should add jcenter repository in your project like:
```xml
<repositories>
  <repository>
    <id>central</id>
    <name>bintray</name>
    <url>http://jcenter.bintray.com</url>
  </repository>
</repositories>
```

### Add dependency
```xml
<dependency>
  <groupId>com.kete</groupId>
  <artifactId>sportmonks.library</artifactId>
  <version>1.0.0</version>
  <type>pom</type>
</dependency>
```

## Authors
Iván Morales