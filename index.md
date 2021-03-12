<div style="text-align: center">
<img alt="YanuX Logo" src="images/yanux-logo.svg" 
     width="128px" style="border-radius: 8px">
</div>

This is the homepage of YanuX Framework, a novel framework for developing multi-device applications.
<iframe width="1903" height="772" src="https://www.youtube.com/embed/0q4qtyWWCpM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The framework is comprised of the following components:
- [__YanuX Auth__](https://github.com/YanuX-Framework/YanuX-Auth)
- [__YanuX Broker__](https://github.com/YanuX-Framework/YanuX-Broker)
     - [REST API Documentation](YanuX-Broker)
- [__YanuX Coordinator__](https://github.com/YanuX-Framework/YanuX-Broker) 
     - [TypeScript API Documentation](YanuX-Coordinator)
     - [JSON Schema of the Domain Specific Language for Specifying Restrictions on the Placement of UI Components](https://github.com/YanuX-Framework/YanuX-Coordinator/blob/release/extras/components-restriction-language/components-restriction-schema.json)
- [__YanuX IPS Bridge__](https://github.com/YanuX-Framework/YanuX-IPSBridge)
- __YanuX Orchestrator__
     - [__Android__](https://github.com/YanuX-Framework/YanuX-Scavenger)
          - Requires [Android](https://www.android.com/) 6.0 (tested up to Android 10)
          - It also includes some early indoor positioning experiments
     - [__Desktop__](https://github.com/YanuX-Framework/YanuX-DesktopClient)
          - Tested on GNU/Linux but it should also work on Windows and macOS.
          - Currently this CLI application also incorporates the desktop version of the __Indoor Positioning Client__.

Besides the framework itself, we have developed an indoor positioning solution comprised of:
- [__Indoor Positioning Server__](https://github.com/YanuX-Framework/YanuX-IPSServer)
- __Indoor Positioning Clients__:
     - [__Android__](https://github.com/YanuX-Framework/YanuX-AndroidIPSApp)
          - Requires [Android](https://www.android.com/) 6.0 (tested up to Android 10)
     - [__Desktop__](https://github.com/YanuX-Framework/YanuX-DesktopClient)
          - Tested on GNU/Linux but it should also work on Windows and macOS.
          - Currently this CLI application also incorporates the desktop version of the __YanuX Orchestrator__ component.

You can also find the following demo applications and prototypes:
- [__YanuX Demo__](https://github.com/YanuX-Framework/YanuX-Demo)
- [__YanuX YouTube Viewer__](https://github.com/YanuX-Framework/YanuX-YouTubeViewer)
- [__YanuX Calculator__](https://github.com/YanuX-Framework/YanuX-Calculator)
- [__JuxtBoard__](https://github.com/YanuX-Framework/YanuX-JuxtBoard)

You may also find all these repositories (and more) at the [YanuX Framework GitHub Organization](https://github.com/YanuX-Framework).

The existing documentation is also being improved and additional documentation will be made available in the future. 

## Publications
- Pedro Albuquerque Santos, Rui Neves Madeira, and Nuno Correia. 2019. YanuX: pervasive distribution of the user interface by co-located devices. In Proceedings of the 16th EAI International Conference on Mobile and Ubiquitous Systems: Computing, Networking and Services (MobiQuitous '19). Association for Computing Machinery, New York, NY, USA, 368–377. DOI: [https://doi.org/10.1145/3360774.3360832](https://doi.org/10.1145/3360774.3360832)
- Pedro Albuquerque Santos, Rui Neves Madeira, and Nuno Correia. 2018. Designing a Framework to Support the Development of Smart Cross-device Applications. In Proceedings of the 17th International Conference on Mobile and Ubiquitous Multimedia (MUM 2018). Association for Computing Machinery, New York, NY, USA, 367–374. DOI: [https://doi.org/10.1145/3282894.3289727](https://doi.org/10.1145/3282894.3289727)
- Pedro Albuquerque Santos. 2017. Enabling the development of pervasive multi-device applications. In Proceedings of the ACM SIGCHI Symposium on Engineering Interactive Computing Systems (EICS '17). Association for Computing Machinery, New York, NY, USA, 153–156. DOI: [https://doi.org/10.1145/3102113.3102156](https://doi.org/10.1145/3102113.3102156)

## Contact
Feel free to [__contact us__](https://mailhide.io/e/FyNhQ64a) if you have any questions.

## License
This website, and any original content created for it, is licensed under the 
[__Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)__](LICENSE). 

Other assets are property of their respective owners and licensed under their own terms.

The code repositories are licensed under the [__GNU Affero General Public License Version 3__](https://www.gnu.org/licenses/agpl-3.0.en.html), the [__GNU General Public License Version 3__](https://www.gnu.org/licenses/gpl-3.0.en.html) or the [__Apache License 2.0__](https://www.apache.org/licenses/LICENSE-2.0), depending on the case.