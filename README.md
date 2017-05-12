# RedWire

a school project !

##Installation and launch

- clone repository
- install with npm : `npm install`
- build with npm : `npm run build`
- launch app with npm : `npm start`

##Faker

Faker is used to populate DB with fake users.
It handles Mysql and Mongo databases.
- duplicate `config/config_sample.json` to `config/config.json` and set your db connections and defaults params
- create fake users with npm : `npm run faker`

You can use arguments to override defaults params just for one time :
- `-t` or `--type` to change db (`mongobd` or `mysql` values allowed)
- `-q` or `--quantity` to change quantity (integer values allowed)

example : `npm run faker -- -t mongodb -q 50`

