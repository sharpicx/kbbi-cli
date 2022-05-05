```sh
██     ██ ██████  ██████  ██
 ██   ██   ██   ██ ██   ██ ██
  █████     ██████  ██████  ██
   ██  ██    ██   ██ ██   ██ ██
    ██   ██   ██████  ██████  ██
    
made by me, a personal tool to dig more stuff about indonesia linguistic
```
## Prologue:
 * personally i love how linguistic looks like, and i learn it by myself doing self-taught on hip hop scene to make myself satisfied, ecstasy on writing lyrics. i been doing this too much LOL. i dont have enough setup to compose a music because i dont wanna make a career on it, nothing more than just a hobby, yass that's what i just said. built for indonesian only, and this project getting inspired by the precursor of [kbbi-cli](https://github.com/jhagas/kbbi-cli/), i be shoutouting for that guy who had made the previous one and have been inspiring me by his project, thanks bro love you, doesnt mean that i'm a LGBTQ.

* kbbi-cli (the better version of the previous one), is a personal tool that i wrote by myself using shell script to scrape synonyms, antonyms, rhymes, meaning of the picked words from the target site i have listed on.


## Features:
* ### Synonyms
   scrapping from <https://sinonim.lektur.id/>
* ### Antonyms 
   same as above.
* ### Rhymes
   scrapping from <https://kuncitts.com/rima-kata/>
* ### Meaning of the literals 
   scrapping from <https://kbbi.web.id>. <br/>
   why dont i scrape from the offical one? because if i did sending too much GET request, then the site's response might be crashed so i'm lazy to deal with.
* ### Interactive shell
  because i love interactive shell. <br/>
  i know it'll be tricky so dont judge me please.

## Installation
first of all you need to install the requirements.
the requirements installation based on your distribution.
```sh
pacman -S html-xml-utils html2text
```
after that. <br/>
make sure you have `~/.local/bin` path set down as `$PATH` on your `.bashrc` or `.zshrc`.
```sh
choose one:
1. export PATH=~/.local/bin:$PATH
2. export PATH=$HOME/.local/bin:$PATH
```
move the script to `$PATH`.
```sh
[~] $ git clone https://github.com/sharpicx/kbbi-cli
[~] $ cd kbbi-cli
[~/kbbi-cli] $ mv kbbi ~/.local/bin/.
```
Now, you have installed the script! congrats!.

## preview:
* [asciinema](https://asciinema.org/a/OQ4NGqTMAaNDtDQxQPhUZSrQz)

* GIF:
![demo](demo.gif)

* Appearance:<br/>
![lmfao](https://i.ibb.co/5W1wrwL/image.png)

## Acknowledgement
* <https://github.com/jhagas/kbbi-cli/> for inspiring me up to build this project.
* [Bashid.org](https://t.me/bashidorg) for `sed` references / cheatsheets.
* [Belajar Ngoding](https://t.me/belajarngodingbareng) Indonesia community that helped me on learning regex.
* [Belajar Linux](https://t.me/belajarlinuxbareng) same as above.
