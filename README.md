# Reminisce: A Batocera EmulationStation Theme
**Created by:** RetroNinja  
**Version:** v1.0. 
**First release:** 2023  
**Last Updated:** 2024  

## Introduction
Welcome to **Reminisce**, a theme designed for EmulationStation as an homage to the golden age of gaming. Created by RetroNinja, this theme brings together vintage video game artwork and modern UI design for a nostalgic yet sleek user experience. Whether you're a retro gaming aficionado or simply enjoy beautiful artwork, Reminisce offers something for everyone.

**Reminisce** combines two of my greatest passions: vintage video game artwork and retro-gaming. Sometimes the game art can be more fascinating than the games themselves! With Reminisce, you don't need games to enjoy the experience. Simply enable "Show Empty Systems" by navigating into 'Game Collection Settings' in the 'Main Menu,' and upon exiting to the system view, you'll be greeted by a gallery of striking artwork. It's visual nirvana for any retro enthusiast.

## Examples
Here's a preview of what you can expect from Reminisce.  
(*Screenshots coming soon!*)  

![Main Menu](./_inc/art/samples/001.png "Main Menu")

- System overview showcasing vibrant retro console logos
- Game lists adorned with authentic box art
- Full-screen visual experiences for each system

## Supported Systems
(*See [SYSTEMS.md](SYSTEMS.md)*.)

## Included Features
- **Splash Video**: A custom splash video is included to complete the retro gaming experience from the moment you boot up. Simply copy it into 'share > splash' and viola! (*[described here](https://wiki.batocera.org/splash_boot)*)
- Splash Image: A custom splash image to use in place of the default boot splash and EmulationStation’s loading splash as described [here](https://wiki.batocera.org/splash_boot).
  
## Scraping for Reminisce
Reminisce relies on the following assets:
* Image (*screenshot*)
* Marquee (*logos*)
* Thumbnail (*boxart*)
* Video (*optional—worth it if you have the disk space.*)

To get the most out of Reminisce, make sure your games are scraped properly. For optimal results:
- Use the built-in Batocera scraper to download game box art, logos, and screenshots (*as indicated above*.)
- ***NOTE:** do NOT scrape image ‘mixes!’ These will destroy the experience **Reminisce** was meant to impart, not to mention will just look horrible*.

## Theme Settings
(*Found under Main Menu > User Interface Settings >  Theme Configuration*)

| ![Theme Configuration eg. #1](./_inc/art/samples/900.png) | ![Theme Configuration eg. #2](./_inc/art/samples/901.png) |
|:---------------------------------------------------------:|:---------------------------------------------------------:|
|    Theme Config Example    |    Example Cont.    |

### Gamelist view styles to choose from:
Reminisce supports several game list view styles to customize how your collection is displayed:
- **Tiles** (*default*): This is the default layout. Similar to a Netflix or Amazon Prime experience, but for retro games! Each game title pulls in an image of the boxart with logo, and plays a video clip of the selected game in the background (*if enabled*). If no video is scraped (*or is disabled*), only the boxart will be displayed.
- **Detailed**: A nice balance of speed and visual niceties. This view plays the selected game title video in the background, along with the game logo and an overview of the game. A list of game titles to scroll through will be positioned on the left side of the screen.
- **Detailed Boxart**: As above, but with a slightly tweaked layout to to accommodate box art in the view.
- **Grid**: Displays boxes automatically in a two row configuration. Will be refined in a later update.
- **Boxes**: Game box art configured for each system, which is nice if you love box art / Japanese variations like me. The grids have been auto-configured for the format of each system's box art, so it's recommended to keep the grid set to AUTO.

Try each style and see which one best fits your collection and aesthetic preferences!

### Main Menu / System views video delay:
If you've scraped for game videos, Reminisce, after a short delay will display these as backgrounds across the system and gamelist views. With this setting, you can determine if and when they display.

- **2 Seconds (default):** The scraped image will be replaced by the scraped video after 2 seconds.
- **3 Seconds:** The scraped image will be replaced by the scraped video after 3 seconds.
- **5 Seconds:** The scraped image will be replaced by the scraped video after 5 seconds.
- **Video off:** Only the scraped image will show.

### Main Menu System logos:
- **mix:** Uses the theme default (my preferred mix). This is the theme default.
- **eu:** Uses European logos if available.z
- **jp:** Uses Japanese logos if available.
- **us:** Uses US logos if available.

### Animations:
To users of lower-powered devices such as the Raspberry Pi, you may want to turn off animations for a speedier experience.

- **Animations on:** Turn on the animations (theme default).
- **Animations off:** Turn off the animations.

### Scanlines on System Views / Main Menu:
Display a scanline-effect overlay over the screenshots and videos displayed in the main system view and individual system gamelist views.

- **No scanlines:** Don't show scanlines (theme default).
- **Light scanlines:** Show light scanlines over images and videos in individual system views / main menu.
- **Dark scanlines:** Show darker scanlines over images and videos in individual system views / main menu.

### Button set:
Here you can choose what button style you want to see throughout Retrofix. By default, where available, it will display the button styles for each system selected, including a supporting colour palette.

- **Unique (default):** Uses a button style specific to the system (default, recommended)
- **Red/Blue/Black/Cyan/Green/Yellow buttons:** Uses a generic button style in your chosen colour across Retrofix.
- **<system name>:** When selected Retrofix will use that button style across all of your systems.

### Primary / Secondary button graphic:

Retrofix uses a custom help system (english at v2 launch) that allows you to set the theme to the specific buttons you set when you configured your controller. That way, the button graphics in Retrofix match your configuation (either A, B, X or Y).

### UI modes:

- **Grey mode (default):** Uses a dark grey system-wide colour setting.
- **Darker mode:** Uses a darker system-wide colour setting.

## Thanks and Credits
(*See [CREDITS.md](CREDITS.md).*)

## Notice
All logos, artwork, screenshots, and trademarks within this theme are the property of their respective owners. The use of these materials within Reminisce is solely for the purposes of enhancing the retro gaming experience and does not imply ownership by the theme creator.

## License
This theme is licensed under the **Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)**.
(*See [LICENSE.md](LICENSE.md).*)
