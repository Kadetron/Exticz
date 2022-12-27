
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
Enter the URL: [domain].[TLD]
```
```bash
$ exticz
Enter the URL: [domain].[TLD]/directory
```
```bash
$ exticz
Enter the URL: [domain].[TLD]/directory?key=value
```
![exticz example](https://i.imgur.com/F92fFxQ.png)


## Installation
```bash
  git clone https://github.com/Kadetron/exticz  
  cd exticz
  sudo mv exticz /usr/local/bin
  rm ./exticz
```
    
## Features

- Highlight the base urls to have a consistent format. The sub urls come under the highlighted base urls
- Accepts any kind of valid links
- Prints the number of base urls at the end
- Removes successive repeated urls from the result
## Dependencies
- awk
- curl
- grep
- sed
- uniq
