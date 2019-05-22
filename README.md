# Homeydash V1.0.0.3 with light blue theme

homeydash is an open-source project for wall-mounted Homey dashboards.
This project is forked from daneedk/homeydash.com and is primarily aimed at usage on a tablet, smart phone or web browser

![Homey.ink on web](http://hjemmefest.ddns.net/Sider/shared/web.png)

To run this locally:

```
npm i -g serve
git clone https://github.com/daneedk/homey.ink
cd homey.ink
serve -p 5000 app
```

Then visit `http://localhost:5000/?theme=web&lang=en&token=<TOKEN>`

or `http://localhost:5000/?theme=iphone&lang=en&token=<TOKEN>`
Themes are awailable as web, iphone and ipad

Homey.ink is available in German (de), English (en), French (fr), Dutch (nl), Norwegian (nb), Swedish (sv) and Danish (da)

> Your token can be acquired by visiting https://homey.ink and looking in the console after logging in.
This is done by right clicking in browser with eks Chrome, then -> inspect and hit the console tab. 
Now you can copy your <token> token=xxxxxxxxxxxxxxxxxx
