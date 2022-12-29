
# Exticz
<p align="center">
  <img src="https://i.imgur.com/MR3iQ0k.jpg" alt="Eye"/>
</p>
<br>
<h3 align="center">Exticz is a scrapping tool which is used to extract href links from a website and is written in shell scripting, can be used for examining websites for redirection and finding sub domains </h3>
<br>

>This is the initial build and can crawl up to a depth of 2.
## Usage
```bash
$ exticz
```
![exticz banner example](https://i.imgur.com/GpkaWhn.png)
<br>

```bash
$ exticz
Enter the URL: <[domain].[TLD]> | <[domain].[TLD]/directory> | <[domain].[TLD]/directory?key=value>
```
![exticz example](https://i.imgur.com/UNoaQnT.png)
<br>

```bash
$ exticz <[domain].[TLD]> | <[domain].[TLD]/directory> | <[domain].[TLD]/directory?key=value>
```
![exticz commandLine](https://i.imgur.com/sxH4Vfr.png)

> While using arguments as input it is recommended to enclose the url in quotes
## Installation
```bash
  git clone https://github.com/Kadetron/Exticz  
  cd Exticz
  sudo mv exticz /usr/local/bin
  cd ..
  rm -r ./Exticz
```
    
## Features

- Uses https scheme by default when no scheme is specified in input
- Highlight the base urls to have a consistent format. The sub urls come under the highlighted base urls
- Accepts any kind of valid links
- Can be used in a command chain
- Removes successive repeated urls from the result

## Dependencies
- awk
- curl
- grep
- sed
- uniq
