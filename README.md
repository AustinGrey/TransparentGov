# ClearGov
Work with the University of Alberta to enable more transparent governance. The University's governing bodies meet in GFC Commitiees (see project glossary) who debate on issues affecting topics such as tuition and program availability. The minutes of these meetings are available to the public, but there is no available way to search and categorize them for research or study. This project seeks to provide a search and visualizations tool for the public to use.

# Resulting Product
Although unfinished, after the 2 months of development time our team was able to develop a search engine and display system that would serve as a strong base for guiding future development. The following images are from the app:

*Desktop Interface Landing Page*
![Capture 0](/design/promotional_images/Capture.PNG?raw=true "The desktop interface, landing page.")

*Search result page, showing the results of searching for the word 'Liturgical'*
![Capture 1](/design/promotional_images/Capture1.PNG?raw=true "Search result page, showing the results of searching for the word 'Liturgical'")

*Search results can have sub items that are separated and navigable*
![Capture 2](/design/promotional_images/Capture2.PNG?raw=true "Showing the nested tabs interface that allows the user to quickly see what items were discussed.")

*An integrated Timeline helps find the right document amoung many results*
![Capture 3](/design/promotional_images/Capture3.PNG?raw=true "The timeline interface for search results")

*An advanced search area that both shows all the capabilities of the search language, while at the same time teaching users how to directly type their queries. The goal is to help every user become a power user over time.*
![Capture 4](/design/promotional_images/Capture4.PNG?raw=true "Advanced search interface")

*The system handles multiple screen sizes gracefully. This is the mobile version of the advanced search page*
![Capture 5](/design/promotional_images/Capture5.PNG?raw=true "Advanced search page, mobile interface")

*Mobile interface - landing page*
![Capture 6](/design/promotional_images/Capture6.PNG?raw=true "Mobile interface landing page")

*Mobile interface - example search page*
![Capture 7](/design/promotional_images/Capture7.PNG?raw=true "Mobile Interface search page")

# Development
[![Build Status](https://travis-ci.org/TransparentGovernanceUofA/TransparentGov.svg?branch=dev)](https://travis-ci.org/TransparentGovernanceUofA/TransparentGov) [![codecov](https://codecov.io/gh/TransparentGovernanceUofA/TransparentGov/branch/django_dev/graph/badge.svg)](https://codecov.io/gh/TransparentGovernanceUofA/TransparentGov)

## Branches
This project uses a branching pattern as follows:
* Branches are created to work on features, issues, or optimizations
* Pull requests are issued to the 'dev' branch, which are then automatically tested by Travis CI (which includes tests that we write)
* When the 'dev' branch is at a releasable stage, it will be pushed to the 'master' branch

Therefore you may pull master and it should work on your system if you have the right prerequisites.

## Project Boards
The project is divided into 4 Sprints, each Sprint has a project board here on github and you may view them to see what issues we are working on at any given time.
