# UD_ReAgent_ABM
Reactive Agent-based Tangible simulation for decision making in urban studies

The EU-funded ReAgent project focuses on co-constructed pluridisciplinary approaches of modelling and participatory simulation to improve decision making and urban planning strategies. The project studies the impacts of urban policies using Agent Based-Models (ABM) to handle real-time visualization tasks applied both to data and simulation outputs. These models are then displayed on a physical 3D model of the city, called Tangible User Interface (TUI). ABM coupled with TUI represents a radically new decision support tool which can be used to explore and assess new urban planning strategies that meet citizens and stakeholders needs. The Marie Curie fellowship is carried out at Université Claude Bernard Lyon 1 (UCBL), in collaboration with LABEX IMU and Lyon Urban School. 

This project has received funding from the European Union’s Horizon 2020 research and innovation programme under the Marie
Sklodowska-Curie grant agreement No 101028036

See the [wiki](https://github.com/VCityTeam/UD_ReAgent_ABM/wiki) for more information about this project

Contact: [Arnaud Grignard](https://github.com/agrignard) 

----------------------------------------------------------------------------------------------------------




## [UD-Viz](https://github.com/VCityTeam/UD-Viz) Version using a client/server architecture where UD_Viz is the client and Gama (in headless) the server

### Start the server (GAMA headless) 

- If not yet installed, download the last Gama 1.9 release version [here](https://github.com/gama-platform/gama/releases/tag/1.9.0) 
- ``` cd /Applications/Gama.app/Contents/headless ``` (Mac OS) or ```cd C:\Program Files\Gama\headless``` (Windows) or ```/opt/gama-platform/headless```(linux)
- ``` bash gama-headless.sh -socket 6868 ```(Mac OS)   or ```gama-headless.bat -socket 6868``` (Windows) or ./gama-headless.sh -socket 6868```

### Start your client

- ``` cd UD-Viz-GCCV ```
- ``` npm i ```
- ```npm run start ``` or ```npm run debug``` (For Developpers):
- Open a browser at this adress ```http://localhost:8000/```


NB: - To reload the keystoning in the Javacript console of your browser run  ``` localStorage.clear() ```



----------------------------------------------------------------------------------------------------------
## [GAMA](https://gama-platform.org/) version (compatible with version 1.9.1)
ABM model developped using [Gama Platform](https://gama-platform.org/). As a standalone can be used directly to be displayed on a physical table. 

- In Gama Import the project ```ReAgent```
- Open ```models/Gratte_Ciel_demo.gaml```
- Run ```Demo```

----------------------------------------------------------------------------------------------------------

