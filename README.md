# Node Demo


## Start Server
`node server.js 8888`

or

`node server 8888`

## Start Server in Background

```
touch log
node server.js 8888 > log 2>&1 &
```

## Start Server in Background with Only One Command

```
touch start
echo node server.js 8888 > log 2>&1 &' >> ./start
chmod +x start
```
Then you can use either `./start` or `sh ./start` to start the server.

## See the Website

Type `47.254.81.220:8888` in the address bar.
