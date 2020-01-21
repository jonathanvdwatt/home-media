# Home Media Solution

This application consists of 3 docker containers that spin up Plex, Sonarr and SABNZBD.

**Plex**

A media player and library that supports chromecast and loads of plugins.

**Sonarr**

A tool to automatically download and manage your library of TV Series. Do not use this for downloading copyright material!

**SABNZBD**

A binary newsgroup download tool for NZBs.

## Getting Started

To clone this repo, simple run the following command:

```
git clone https://github.com/dankritz/home-media.git
```

## Installation

**Note:** Be sure to configure the .env file accordingly! Also, make sure all your media is mounted to /external.

To build the application and lauch the containers:

```
cd home-media/docker
docker-compose up -d
```

After the containers are up, setup the Sonarr->SABNZBD API integration and your indexer.
