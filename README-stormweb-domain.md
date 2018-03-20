# Stormweb Domain Handling


## Adding a subdomain

- go to stormweb.ca ==> login to CPANEL
- click `domains`  ==>
- click dropdown menu for `energyexplorer.ca` ==>
- under `manage` click `zone editor` ==>


## tileserver // A 
```
name: tiles.energyexplorer.ca
IP Address: ###.###.##.###
```


## beta // CNAME
```
name: beta.energyexplorer.ca
CNAME: <link to heroku url>
```

## latest // CNAME
```
name: latest.energyexplorer.ca
CNAME: <link to heroku url>
```

Currently `energyexplorer.ca` redirects to `latest.energyexplorer.ca`