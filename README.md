# Frontend

## Description

This is the frontend part of the distributed system DENTISTIMO, a web application that offers a geolocalisation based dental care booking system.
Dentistimo GUI provides a graphical user interface of the system using dentistry data from the clinic handler component. More details can be found below in this README.md file.

## System Architecture - Component Diagram

> ![Component Diagram](Assets/System_Component_Diagram_v2.0.png)


## Components Responsibilities

- Display interactive map allowing users to navigate to dentist practices
- Display info about clinics 
- Allow user to book an appointment 
- Publish booking (date + time) to MQTT broker 

## Data Input 

The client subscribes to a topic in the clinic handler and expects to recieve dentist data via MQTT.   
This data is then displayed on the map in line with the requirements. 


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
