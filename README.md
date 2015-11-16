
# office-quake

i've, obviously, **not** included `pak0.pk3` in this repository.

##### installing

* clone the repository
* extract the baseq3 folder with `cat baseq3.tar.gz.* > baseq3.tar.gz && tar -zxf baseq3.tar.gz && rm baseq3.tar.gz`
* move your copy of `pak0.pk3` into `baseq3/`

##### playing

* simply run `ioquake3.app`

##### dedicated server

* first, open `bin/dedicated` in your preferred text editor
* edit line 3 to reflect the correct path to your `ioquake3.app` file
* edit line 4 to reflect your ip address on the lan
* edit line 16 to reflect the path to your quake folder in which the `ioquake3.app` resides
* run the script from your terminal with `./bin/dedicated`
* finally, run `map q3dm6` to change the level hosted on the server

##### known issues

* no config file has been written to have the dedicated server automatically start a server with an auto-determined map. you **have** to do something like `map q3dm6` to get started.
* `com_hunkmegs` can sometimes cause the dedicated server to crash or simply not start. if this happens, try doubling the value.

##### license

please see [here](https://github.com/id-Software/Quake-III-Arena/blob/master/README.txt)
