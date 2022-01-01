# Menhera
A working MyAnimeList redirect URI.

## What is Menhera?
Menhera allows your [MyAnimeList](https://myanimelist.net) OAuth2 app to receive auth codes without hosting your own server. 

## How do I use Menhera?
**First of all please please please fork this repo first. Using my repo as a redirect uri is a gaping security hole because you don't control it.**
I also might change my username, breaking all existing redirect URIs.

Add the following redirect URI to your application: https://YOUR_USERNAME.github.io/menhera/auth.html

The page will provide a code and state that are provided in this format: `code:state`.

The user can then paste the code into your application.

## Can I use this project?
Sure, it's licensed under the MIT license so do whatever the license allows. 

## This looks boring
You can check out [Taiga's](https://taiga.moe/api/myanimelist/auth/?code=change_this). They may not allow copying it though. Check their license.
