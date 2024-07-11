# Sponsor

You can use https://kayoanimetv.com that specializes in solving various types of captchas automatically.

# How to launch pupflare
1. Install NodeJS
2. `npm install`
3. `npm start`

# How to use
Send your request to the server with the port 3000 and add your URL to the "url" query string like this:
`http://localhost:3000/?url=https://example.org`

This script has been configured to wait for the cloudflare challenge to pass but, you can configure the "match" for anything else using the environment variable `CHALLENGE_MATCH`.  
If the website that you are targeting have a protection page with "please wait" in the HTML code then launch the script like this:
```
CHALLENGE_MATCH="please wait" npm start
```

To show the browser window, set the environment variable `PUPPETEER_HEADFUL=1`.

To use a proxy,
set the `PUPPETEER_PROXY` environment variable, for example `PUPPETEER_PROXY=localhost:8080`.

To specify user data directory, set `PUPPETEER_USERDATADIR=/path/to/dir`.

To enable debugging: `DEBUG=true` and debugging with body in the logs: `DEBUG_BODY=true`

# Docker
Available as a Docker image here: https://quay.io/repository/unixfox/pupflare (linux/amd64,linux/arm64)<br>
https://game8.jp/users/228577<br>
https://tabelog.com/rvwr/kayoanime/prof/<br>
https://kayoanime.mypixieset.com/<br>
https://www.pixiv.net/en/users/106315176<br>
https://www.pinterest.de/kayoanimetv/
https://www.pinterest.de/pin/996562223796792133/<br>
https://archive.org/details/@kayoanime<br>
https://solo.to/kayoanime
https://bio.link/kayoanimetv
https://hashnode.com/@Kayoanime
https://kayoanime.hashnode.dev
https://kayoanime.hashnode.dev/anime-is-my-favorite-why-anime-is-loved-by-many-people<br>
https://www.upwork.com/freelancers/~01a374356eb6769163?p=1805892988626501632<br>
https://www.evernote.com/shard/s365/client/snv?isnewsnv=true&noteGuid=fb697d61-c9d0-1280-017e-b42893c0471d&noteKey=d7agljzqW4PQHwn4XkjdWKefsJbjJDg8zXEadvqJKxBUx8lxLH9bWDL7QQ&sn=https%3A%2F%2Fwww.evernote.com%2Fshard%2Fs365%2Fsh%2Ffb697d61-c9d0-1280-017e-b42893c0471d%2Fd7agljzqW4PQHwn4XkjdWKefsJbjJDg8zXEadvqJKxBUx8lxLH9bWDL7QQ&title=my%2Bnotes<br>
https://www.kickstarter.com/profile/kayoanime/about<br>
https://www.twitch.tv/animixplayfun/about<br>
https://issuu.com/animixplay_kayoanime<br>
https://www.scam-detector.com/validator/animixplay-fun-review/<br>
https://about.me/animixplay_fun<br>
https://www.sitelike.org/similar/kayoanimetv.com/


```
docker run -d -p 3000:3000 quay.io/unixfox/pupflare
```
