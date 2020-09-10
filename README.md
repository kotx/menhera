# Menhera
A working MyAnimeList redirect URI.

## What is Menhera?
Menhera allows your [MyAnimeList](https://myanimelist.net) OAuth2 app to receive auth codes without hosting your own server. 

## How do I use Menhera?
Add the following redirect URL to your application: https://kotx.github.io/menhera/auth.

The page will provide a code and state that are provided in this format: `code:state`.

The user can then paste the code into your application.

## What's the catch?
States can't be verified accurately. I've yet to think of a workaround for this.

## Can I use this project?
Sure, it's licensed under the MIT license so do whatever the license allows. 
