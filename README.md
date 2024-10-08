# Reminisce: a Batocera EmulationStation Theme

![Static Badge](https://img.shields.io/badge/platform-batocera-%23BB2222)
![GitHub Release(latest by date)](https://img.shields.io/github/v/release/cdaters/es7-theme-reminisce)
![GitHub License](https://img.shields.io/github/license/cdaters/es7-theme-reminisce)
![GitHub last commit](https://img.shields.io/github/last-commit/cdaters/es7-theme-reminisce)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/cdaters/es7-theme-reminisce)

**Created by:** PixelWizard (aka Craig Daters, cdaters)  
**Version:** v0.1.0 (Beta)  
**First release:** 2023  

## Introduction
Welcome to **Reminisce**, a theme designed for EmulationStation as an homage to the golden age of gaming. Created by RetroNinja, this theme brings together vintage video game artwork and modern UI design for a nostalgic yet sleek user experience. Whether you're a retro gaming aficionado or simply enjoy beautiful artwork, Reminisce offers something for everyone.

**Reminisce** combines two of my greatest passions: vintage video game artwork and retro-gaming. Sometimes the game art can be more fascinating than the games themselves! With Reminisce, you don't need games to enjoy the experience. Simply enable "Show Empty Systems" by navigating into 'Game Collection Settings' in the 'Main Menu,' and upon exiting to the system view, you'll be greeted by a gallery of striking artwork. It's visual nirvana for any retro enthusiast.

## Examples
Here's a preview of what you can expect from Reminisce. 

- Main Menu - System Overview

![Main Menu - System Overview](./_inc/art/samples/ssMain.png "Main Menu")

- Gamelist View - Modern (Default)

![Modern Gamelist View - Playstation Portable](./_inc/art/samples/ssModern.png "Modern Gamelist View - Playstation Portable")

- Gamelist View - Detailed

![Detailed Gamelist View - Commodore 64](./_inc/art/samples/ssDetailed.png "Detailed Gamelist View - Commodore 64")

- Gamelist View - Grid

![Grid Gamelist View - Bally Arcade](./_inc/art/samples/ssGrid.png "Grid Gamelist View - Bally Arcade")

- Gamelist View - Carousel

![Carousel Gamelist View - TurboGrafx 16](./_inc/art/samples/ssCarousel.png "Carousel Gamelist View - TurboGrafx 16")

## Supported Systems
(*See [SYSTEMS.md](SYSTEMS.md) for more information*)

## Included Features
- **Splash Video**: A custom splash video is included to complete the retro gaming experience from the moment you boot up. Simply copy it into `./share/splash` or `./userdata/splash` and viola! (*[described here](https://wiki.batocera.org/splash_boot)*)
- Splash Image: A custom splash image to use in place of the default boot splash and EmulationStation’s loading splash as described [here](https://wiki.batocera.org/splash_boot).
  
## Scraping for Reminisce
Reminisce relies on the following assets to work as expected and comes with some default content that it will display if any of this is missing or is omitted:
* Image (*screenshot*)
* Marquee (*logos*)
* Thumbnail (*boxart*)
* Video (*optional—worth it if you have the disk space.*)

To get the most out of Reminisce, make sure your games are scraped properly. For optimal results:
- Use the built-in Batocera scraper to download game box art, logos, and screenshots (*as indicated above*.)
- ***NOTE:** do NOT scrape image ‘mixes!’ These will destroy the experience **Reminisce** was meant to impart, not to mention will just look horrible*.

## Theme Settings
(*Found under `> Main Menu > User Interface Settings >  Theme Configuration`*)

| ![Theme Configuration eg. #1](./_inc/art/samples/themeGamelist.png) | ![Theme Configuration eg. #2](./_inc/art/samples/themeReset.png) |
|:---------------------------------------------------------:|:---------------------------------------------------------:|
|    Theme Config Example    |    Example Cont.    |

### Gamelist View Styles to choose from:
Reminisce supports several game list view styles to customize how your collection is displayed:
- **Modern** (*default*): This is the default layout. Similar to a Netflix or Amazon Prime experience, but for retro games! Each game title pulls in an image of the boxart with logo, and plays a video clip of the selected game in the background (*if enabled*). If no video is scraped (*or is disabled*), only the boxart will be displayed.
- **Detailed**: A nice balance of speed and visual niceties. This view displays a screenshot of gameplay for a few seconds and then fades to a video of gameplay of the selected title in the background (*if enabled*), along with displaying the game's boxart, logo, and an overview of the game. If no video is scraped (*or is disabled*), only the screenshot will be displayed.
- **Grid**: Displays boxes automatically in a two row configuration. Will be refined in a later update.
- **Carousel**: A carousel of game boxart, configured for each system, which is nice if you love box art like me. The carousels have been auto-configured for the format of each system's box art, so it's recommended to keep the grid set to AUTO.

Try each style and see which one best fits your collection and aesthetic preferences!

### Color Scheme:
Here you can select the color accents that you would prefer to see throughout the theme. The default is blue, but you can select violet, yellow, red, green, etc.

### Your Controller Type :video_game::
This will confiure the controller button style and labeling you'll see throughout Reminisce based on the controller you'll be using. This should be self-explanitory, or...  

... **this is why I have problems when video games ask me to press, "X"** ...

| ![XBOX](./_inc/art/samples/controller_xbox.jpg) | ![NES](./_inc/art/samples/controller_snes.jpg) | ![Playstation](./_inc/art/samples/controller_ps.jpg) |
|:-----------------------------------------------:|:----------------------------------------------:|:----------------------------------------------------:|
|    XBOX Style    |    Nintendo Style    |    Playstation Style    |

- **XBOX:** (*default*) The Y, B, A, X buttons are reversed compared to Nintendo controllers.
- **Nintendo:** The X, A, B, Y buttons are reversed compared to XBOX controllers.
- **PlayStation:** This controller uses symbols (△, ○, X, □) instead of lettered buttons.

Regardless of the chosen controller type, EmulationStation generally maps buttons using a North ![North](./_inc/art/samples/dirNorth.png), East ![East](./_inc/art/samples/dirEast.png), South ![South](./_inc/art/samples/dirSouth.png), and West ![West](./_inc/art/samples/dirWest.png) directional layout. This setting ensures that Reminisce properly reflects your controller’s layout and displays the correct contextual help imagery for navigating both Reminisce and EmulationStation.

### Theme / Gamelist Video Delay:
If you’ve scraped game videos, Reminisce will display them as backgrounds in the system overview and game list views after a brief delay. With this setting, you can control when, or if, the videos appear.

- **2 Seconds:** (*default*) The scraped image will be replaced by the video after 2 seconds.
- **3 Seconds:** The scraped image will be replaced by the video after 3 seconds.
- **5 Seconds:** The scraped image will be replaced by the video after 5 seconds.
- **Video off:** Only the scraped image will be displayed, without any video.

### System Logos:
- **Mix:** (*default*) This is the theme default and uses a prefered mix of the three other options.
- **EU:** Uses European logos if available.
- **JP:** Uses Japanese logos if available.
- **US:** Uses US logos if available.

### Theme Overlay:
Display a scanline-effect overlay effect over the images and videos displayed in the main system overview and gamelist views.

- **No scanlines:** Don't show scanlines (theme default).
- **Light scanlines:** Show light scanlines over images and videos in individual system views / main menu.
- **Dark scanlines:** Show darker scanlines over images and videos in individual system views / main menu.

### Animations:
Reminisce utilizes subtle animations to provide a more polished user experience. However this could be anoying to some and for users of lower-powered devices, such as earlier versions of the Raspberry Pi, etc., you may want to turn off animations for a speedier experience.

- **Animations on:** Turn on the animations (theme default).
- **Animations off:** Turn off the animations.

### UI modes: (*disabled for now*)
Change the accent color of the theme interface and EmulationStation menus.

- **Grey Mode (default):** Uses a dark grey system-wide color setting.
- **Darker Mode:** Uses a darker system-wide color setting.
- **Purple Mode:** A royal purple color setting.
- **Blue Mode:** A dark blue color setting.
- **Red Mode:** A blood red color setting.

## Thanks and Credits
(*See [CREDITS.md](CREDITS.md) for more information*)

## Notice
All logos, artwork, screenshots, and trademarks within this theme are the property of their respective owners. The use of these materials within Reminisce is solely for the purposes of enhancing the retro gaming experience and does not imply ownership by the theme creator.

## License

[Reminisce: a Batocera EmulationStation Theme](https://github.com/cdaters/es7-theme-reminisce) by [PixelWizard](https://daters.net) is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1) <img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt="CC Icon" style="height:24px; vertical-align:text-bottom;"> <img src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt="BY Icon" style="height:24px; vertical-align:text-bottom;"> <img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt="SA Icon" style="height:24px; vertical-align:text-bottom;">

**Summary:**
This license enables reusers to distribute, remix, adapt, and build upon the material in any medium or format, so long as attribution is given to the creator. The license allows for commercial use. If you remix, adapt, or build upon the material, you must license the modified material under identical terms.


(*See [LICENSE](LICENSE) for more information*)
