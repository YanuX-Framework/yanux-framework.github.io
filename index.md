<div style="text-align: center">
<img alt="YanuX Logo" src="images/yanux-logo.svg" 
     width="128px" style="border-radius: 8px">
</div>

This is the homepage of YanuX Framework, a novel framework for developing multi-device applications.

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
          - Requires Android 6.0 (tested up to Android 10)
          - It also includes some early indoor positioning experiments
     - [__Desktop__](https://github.com/YanuX-Framework/YanuX-DesktopClient)
          - Tested on GNU/Linux but it should also work on Windows and macOS.
          - Currently this CLI application also incorporates the desktop version of the __Indoor Positioning Client__.

Basides the framework itself, we have developed an indoor positioning solution comprised of:
- [__Indoor Positioning Server__](https://github.com/YanuX-Framework/YanuX-IPSServer)
- __Indoor Positioning Clients__:
     - [__Android__](https://github.com/YanuX-Framework/YanuX-AndroidIPSApp)
          - Requires Android 6.0 (tested up to Android 10)
     - [__Desktop__](https://github.com/YanuX-Framework/YanuX-DesktopClient)
          - Tested on GNU/Linux but it should also work on Windows and macOS.
          - Currently this CLI application also incorporates the desktop version of the __YanuX Orchestrator__ component.

You can also find the following demo applications and prototypes:
- [__YanuX Demo__](https://github.com/YanuX-Framework/YanuX-Demo)
- [__YanuX YouTube Viewer__](https://github.com/YanuX-Framework/YanuX-YouTubeViewer)
- [__YanuX Calculator__](https://github.com/YanuX-Framework/YanuX-Calculator)
- [__JuxtBoard__](https://github.com/YanuX-Framework/YanuX-JuxtBoard)

The existing documentation is being imrpoved and additional documentation will be made available in the future.

### License
Different parts of this work are either licensed under the [__GNU Affero General Public License Version 3__](https://www.gnu.org/licenses/agpl-3.0.en.html), the [__GNU General Public License Version 3__](https://www.gnu.org/licenses/gpl-3.0.en.html) or the [__Apache License 2.0__](https://www.apache.org/licenses/LICENSE-2.0)
