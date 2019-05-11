<h1 align="center">
  <img src="https://github.com/NivM1/StremioPodcust/blob/master/resources/images/addon_logo.png" alt="Podcast For All" width="150"></a>
  <br>
  Podcasts For All
  <br>
</h1>

<h4 align="center">Stream the best podcasts to <a href="https://www.stremio.com/" target="_blank">StremIO</a></h4> and much more

<p align="center">
  <a href="paypal.me/NivM1">
    <img src="https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&amp;style=flat">
  </a>
</p>

<p align="center">
  <a href="https://www.stremio.com/addon-sdk">Stremio add-on SDK</a> •
  <a href="https://www.stremio.com/competition">Add-On Master</a> •
  <a href="#Setup">Setup</a> 
  </a> •
  <a href="#Key-Features">Key Features</a> 
</p>

> *Podcasts For All* - `have fun`, `be smart`.

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/check-it-out.svg)](https://forthebadge.com)

> **We are making our best efforts** to bring you the best podcasts resources.<br/>
> If you like our addon, you can help us by <a href=" paypal.me/NivM1"> donate</a>.

## Key Features

* Best podcasts worldwide (smart filters and ordering) :trophy:
  * All types
  * All languages & regions :european_castle: :tokyo_tower:
* Podcast catalogs: :file_folder:
  * Top Podcasts
  * By Genres
  * By Country
  * Felling Luckey - Random podcast
* Search for podcasts :mag:
* Extra details :bookmark:
  * Podcast length
  * Podcast website
  * Social Platforms refrences (Facebook, Spotify and more)
* Stream HQ audio right to your device :headphones:
  * Cast the podcast to available devices

#### Screenshot - Main Podcasts Catalog:
![Podcasts Catalog](https://github.com/NivM1/podcasts-for-all/blob/master/resources/images/podcast_for_all_screen.jpg)

#### Screenshot - Select Episode:
![Podcasts Epidsodes](https://github.com/NivM1/podcasts-for-all/blob/master/resources/images/podcast_for_all_screen2.jpg)

## Setup

* Go to <a href="https://www.listennotes.com/api/">Listen Notes API</a> :page_facing_up:
* Create new **_account_** and save your **_API_KEY_** :memo:
* Now it's time for some preperation
```bash
# Clone this repository
$ https://github.com/NivM1/podcasts-for-all.git

# Go into the repository
$ cd podcasts-for-all

# Install dependencies
$ npm install
```
* Set your `.env` file like that:
```diff
+# PODCASTS_API_KEY= [Listen Notes API KEY]
+# LOG_LEVEL= [Logger level- such as: trace, debug, error...]
```

* Run your addon server using `npm start`
* Install it on your StreamIO app (web / desktop) :computer:
  * The addon available here: <http://127.0.0.1:56960/manifest.json>
* Now go to <https://staging.strem.io/#/discover/Podcasts> and **enjoy your podcasts!** :trumpet:


Thanks
------

**Podcast For All** © 2019+, DE, NM Released under the [MIT License].<br>
Authored and maintained by DE, NM. with help from [contributors].


> GitHub [Niv M](https://github.com/nivm1) <br/>
> GitHub [Doron Eli](https://github.com/doron050)

[MIT License]: http://mit-license.org/
[contributors]: http://github.com/contributors
