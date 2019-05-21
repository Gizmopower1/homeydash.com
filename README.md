# homeydash.com

homeydash.com is an open-source project for wall-mounted Homey dashboards.
This project is forked from Homey.ink and is primarily aimed at usage on an iPad or iPhone


![Homey.ink on iPad](https://hjemmefest.ddns.net/Sider/homeydash3/assets/devices/web/web1.png)


To run this locally:

```
npm i -g serve
git clone https://github.com/daneedk/homey.ink
cd homey.ink
serve -p 5000 app
```

Then visit `http://localhost:5000/?theme=web&lang=en&token=<TOKEN>`

or `http://localhost:5000/?theme=iphone&lang=en&token=<TOKEN>`

Homey.ink is available in German (de), English (en), French (fr), Dutch (nl), Norwegian (nb), Swedish (sv) and Danish (da)

> Your token can be acquired by visiting https://homey.ink and looking in the console after logging in.
