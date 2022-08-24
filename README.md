# expresssample

```
cd expresssample/
npm i
pm2 start app.js  --log-date-format 'DD-MM HH:mm:ss.SSS' --name expresssample
pm2 save
```

```
pm2 restart app.js  --log-date-format 'DD-MM HH:mm:ss.SSS' --name expresssample

```

### check logs

```
//realtime
pm2 monit

//tail
pm2 logs

```
