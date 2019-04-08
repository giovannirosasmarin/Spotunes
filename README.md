Group Project - README Template
===
# Team Members:
1. Hector Aguirre
2. Giovanni Rosas-Marin
3. Teodoro Calvario


# SpotTunes

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
This app shows the user and gives the option to
play the current top100 billboard songs.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category: Music and Social Media**
- **Mobile: Iphone/Ipad(maybe)**
- **Story:**
- **Market: Music lovers**
- **Habit:**
- **Scope:**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* [Sign up, login]
* [Users main library(songs he likes)]
* [Profile page with name, password, and email    help]
* [tab to view top 100 songs at any given time]
* [search songs]
* 
* ...

**Optional Nice-to-have Stories**

* [quiz to reccomend songs to user]
* [reccomend top friends]
* [play songs, download]
* ...

### 2. Screen Archetypes

* [sign in]
    * user can sign in
* [register]
    * user can register
* [profiel]
    * page with name, password, and emailhelp
* [charts]
    * top 100 songs at any given time
* [search]
    * users can search new songs
    

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* [charts]
* [Profile]
* [search]

**Flow Navigation** (Screen to Screen)

* [login]
   * [user can connect to their profile page]
   * ...
* [profile page]
   * [user can go to charts and search]
   * ...

## Wireframes
## Hand Sketch of project

<img width="925" alt="Screen Shot 2019-04-02 at 1 32 39 PM" src="https://user-images.githubusercontent.com/36067708/55434170-cb1b8f80-554b-11e9-8809-762cd40a087f.png">

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
|Property|Type|Description|
|---|---|---|
|objectId|String|ID for all users|
|image|File|Album cover image|
|Label1|String|Name of the song|
|Label2|String|Name of the artist|
|Favorited|File|Determined if song is liked or not|

### Networking
- [Add list of network requests by screen ]

- Home Feed Screen

(Read/GET) Query all posts where user is author

(Create) Create a new Favorite

(Delete) Delete existing Favorite

- Create Post Screen

(Create/POST) Create a new post object
- Profile Screen

(Read/GET) Query logged in user object

(Update/PUT) Update user profile image

- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
