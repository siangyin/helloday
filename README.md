# React-Project 2 : Focus Diary

[Demo Link](https://github.com/facebook/create-react-app).

## Pre-Project Planning

### Problem

Even on a good day, life can be overwhelming. Buzzing phones, work obligations, family needs, to-do lists, email overload, expectations, illness, invitations and the list goes on for the things that occupy our time. On top of that we have food choices, clothing choices, money worries, and mental and physical health issues that can weigh us down.

Personally, I always get stressed out pretty easily and having alot of inner thought in mind fighting with each other. Some day, I feel energetic and positive but some other day I maybe feeling down and begin to self doubting. By jot down all the thoughts reminding myself are helpful to free the mind and can be like a walk through or reflections from things that happened around me.

### Solution

Focus Diaries as like a place where one can record events, experience and even throw anything you want to declutter out from your mind. This digital journal app help to simplfy your life by empty what's on your mind at the same time understand ownself better.

## Project Development

### User Story

A user should be able to

- sign/ sign out
- create new diary input
- access to all his/her diaries for
- viewing
- editing
- deleting

### Ideas & App Structures:

Data needed:

- each personal user account
- Diary entry array object
  - date
  - mood
  - title
  - diary input
  - tagging option
- All diaries entry array object, each day entry in one main array to be access by unique date.
- Tagging list
- Mood list
- Daily quote

### Wireframe

Landing and routes
![Landing and routes](https://github.com/siangyin/focus-diary/blob/main/images/mapping.png?raw=true)

Create New Diary
![Create New Diary](https://github.com/siangyin/focus-diary/blob/master/images/NewDiary.png)

Accessing Personal Diaries
![Accessing Personal Diaries](https://github.com/siangyin/focus-diary/blob/master/images/AllDiaries.png)

## Project Implementation

### Technologies & Dependencies Used

- HTML
- CSS
- React (React-DOM & React-Router-DOM)
- Axios (for API)
- Firebase (for Auth login)
- Font Awesome
- API for [quote]: (https://type.fit/api/quotes)
