# CabinProject  

## Table of Contents
- [Description](#description)
  - [Background](#background)   
  - [Implementation](#implementation)   
  - [Result](#result)   
- [Built with](#built-with)
- [Showcase](#showcase)
  - [Cafe Configuration](#cafe-configuration)
  - [Cabin Configurator](#cabin-configurator)
  - [360° Cabin Tour](#360-cabin-tour)
- [Author](#author)

## Description  
### Background  
The project is part of an Interdisciplinary Team Project module, where teams of students from various computing schools worked for real clients and provided a prototype within two months.

Our client, Beohus, a modular custom‐cabins company, wanted an accessible way to showcase their cabins’ modularity and uses. They needed an interactive tool to help clients visualise each cabin’s potential.

### Implementation
As the solo programmer, I used their existing 3D cabin model to create a web prototype in Three.js, GSAP, and JavaScript, allowing cabin elements to be manipulated.

To allow for fast iterations of different animations, I wrote a small framework that reads a JSON file specifying element names and animates them sequentially or concurrently. This simplified testing of animation configurations and ensures reuse if the 3D model changes.

Using the same framework, I integrated a second setup in which a coffee-shop model created by my teammate replaces the cabin layout.

Finally, I added a simple configurator for spawning walls to create custom layouts. This prototype demonstrates how users might build their own layouts, with plans to add furniture placement and a screenshot feature in the future to help users visualise a complete cabin design.

### Result  
The prototype was very well received for its implementation and solutions, leading to a contract offer to continue development and finalise the project’s vision.

## Built with
- **JavaScript**
  - **Three.js** – 3D graphics library 
  - **GSAP** – animation library 
  - **jQuery**
- **HTML** and **CSS**

## Showcase  

### Cafe configuration
Hiding the current layout and displaying a cafe configuration instead.   

https://github.com/user-attachments/assets/948b32f4-6678-4de1-a994-33a5d7d6ade2  

Reversing the cafe configuration, displaying the normal cabin layout.  

https://github.com/user-attachments/assets/df7c7656-cba8-4b64-94aa-4e55eccd5d13

### Cabin Configurator
Revealing the cabin configurator, where walls can be dynamically spawned.  

https://github.com/user-attachments/assets/946cb5f3-1949-4923-8e25-d1dbc4758e4b

### 360 Cabin Tour
Showing a 360° tour of the cabin.  

https://github.com/user-attachments/assets/2e77996f-6d0b-419f-800b-550208792d1e

## Author  
**Programming:** Tiberiu Rociu  
**Cafe 3D model:** Aardarsha Bhatta



