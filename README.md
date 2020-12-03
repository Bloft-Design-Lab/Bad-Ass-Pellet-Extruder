<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, twitter_handle, email, project_title, project_description
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/">
    <img src="images/Bloft_Logo_Blue.png" alt="Logo" width="204" height="134">
  </a>

  <h3 align="center">Bad Ass Pellet Extruder</h3>

  <p align="center">
    A Hangprinter compatible pellet extruder for large scale FGF-printing.
    <br />
    <a href="https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/">View Demo</a>
    ·
    <a href="https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/issues">Report Bug</a>
    ·
    <a href="https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#design-drivers">Design Drivers</a>
      <ul>
        <li><a href="#the-compression-screw">The Compression Screw</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![The Bad Ass Pellet Extruder](/images/Bad-Ass-Pellet-Extruder.jpg)

The Hangprinter project by Torbjørn Ludvigsen has developed a promising and affordable concept for a large scale cable-driven 3D-printer, that has the potential to serve as the framework for an entirely new class of 3D-printers, enabling distributed local manufacturing of large end use products like furniture, vehicles, buildings etc. Up until now the Hangprinter has relied on regular FDM-extruders leaving the project far behind its true potential. Being great for desktop printers, those extruders are not suitable for printers beyond the 1 cubic meter class. Filament extrusion hits the wall in terms of speed, cost and sustainability.

We decided to circumvent this obstacle by developing an affordable pellet extruder, that enables you to print not only with industry standard plastic pellets, but also and mainly with re-granlute plastic made from your plastic waste.


<!-- DESIGN DRIVERS -->
## Design Drivers

* Throughput 1-2 kg/hr depending on polymer
* As light as possible
* Nozzle sizes up to 10 mm, easy to swap
* Sturdy base for attachment
* Enough heating power to cover as many polymers as possible
* Tolerance for potential foreign objects (dirt, sand, etc.) within the granulate
* Automatic material transport and dispensing
* High flow cooling for the print area

### The compression screw

The compression screw is the key element of a pellet extruder. It differs from a regular auger bit by having a flute depth that decreases top the tip. The compression screw is disected into three different zones: the feed zone, the compression zone and the metering zone. The screw adds shear to the plastic granulate and accelerates the melting process. These compression screws are difficult to manufacture, so we are going to cut corners and we will use the [RobotDigg 16 mm extruder screw, barrel and nozzle](https://www.robotdigg.com/product/1691/16mm-or-20mm-extruder-screw,-barrel-n-nozzle) for now.

The RobotDigg barrel has already a flange with standard Nema 23 attachment holes and it comes with an exchangeable nozzle.

## Pre-requisites

Certain set of tools is needed to start your own project. Both software and hardware tools.
We are designing the pellet extruder in Autodesk Fusion 360. Although not open source, you can obtain a [personal, non-commercial, license](https://www.autodesk.com/products/fusion-360/personal) for free from Autodesk. We will provide also exchange file formats if you prefer to use other CAD software.

Among other things you should be prepared to have access to following tools:
* Drill bench
* Soldering iron
* 3D-printer
* CNC-machine
* Handtools like allen keys, wrenches, screw drivers, metal saw etc.

## A word of warning

The barrel is heated by powerful mica band heaters. This leads to two serious hazards.
1. The heaters are powered by grid voltage which poses a danger of a lethal electric shock! If you are not trained in connecting electric circuitry, please ask someone with experience.
2. The heater bands can generate heat up to 450 degree Celcius, which can lead to serious burn injuries or a fire hazard.

Please keep this always in mind. Ask always, if in doubt.

<!-- ROADMAP -->
## Roadmap

* 09/2019 - 11/2019 Design, component selection
* 11/2019 - 12/2020 Manufacturing, assembly
* 01/2020 - 06/2020 Extrusion testing, iteration
* 01/2021 - 02/2021 Print testing

See the [open issues](https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/issues) for a list of proposed features (and known issues).

<!-- SOURCE FILES -->
## Source Files

The Bad Ass Pellet Extruder source files are maintained in the [Autodesk360 cloud]

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->
## License

Distributed under the Creative Commons Attribution-ShareAlike 4.0 International Public License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Atte Linna - [@twitter_handle](https://twitter.com/velmukelmu)

Project Link: [https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder](https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder.svg?style=for-the-badge
[contributors-url]: https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder.svg?style=for-the-badge
[forks-url]: https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/network/members
[stars-shield]: https://img.shields.io/github/stars/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder.svg?style=for-the-badge
[stars-url]: https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/stargazers
[issues-shield]: https://img.shields.io/github/issues/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder.svg?style=for-the-badge
[issues-url]: https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/issues
[license-shield]: https://img.shields.io/github/license/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder.svg?style=for-the-badge
[license-url]: https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/blob/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/company/bloft-design-lab
[Product Name Screen Shot]: https://github.com/Bloft-Design-Lab/Bad-Ass-Pellet-Extruder/images/Bad-Ass-Pellet-Extruder.jpg
