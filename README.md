Copy of Traccar with minor changes for our needs in the decoders. 

## Changed Files for Our System: 

Decoders: <BR>
-UlbotecProtocolDecoder, <BR>
-DmtDecoder, <BR>
-TeltonikaDecoder<BR>
-MictrackProtocolDecoder
<BR>
Helpers: <BR>
-ObdDecoder<BR>
<BR>

## End of changes from original 

## Process to update:
-Compile latest copy of Traccar with updated files into JAR file. 
<BR>
-Extract all compiled files from the new JAR file (jar -xvf filename.jar)
<BR>
-Download a copy of the compiled server JAR file from our server into a new folder
<BR>
-From the folder of that JAR file, create the folder structure matching the updated files (org/traccar/protocol/), etc. And, copy those files into their applicable places
<BR>
-Replace the files in our server JAR file with these compiled ones using jar uf jar-file org/traccar/....../file.class
    
## End Updates
    
   
    
    
    






# [Traccar](https://www.traccar.org)

## Overview

Traccar is an open source GPS tracking system. This repository contains Java-based back-end service. It supports more than 170 GPS protocols and more than 1500 models of GPS tracking devices. Traccar can be used with any major SQL database system. It also provides easy to use [REST API](https://www.traccar.org/traccar-api/).

Other parts of Traccar solution include:

- [Traccar web app](https://github.com/traccar/traccar-web)
- [Traccar Manager Android app](https://github.com/traccar/traccar-manager-android)
- [Traccar Manager iOS app](https://github.com/traccar/traccar-manager-ios)

There is also a set of mobile apps that you can use for tracking mobile devices:

- [Traccar Client Android app](https://github.com/traccar/traccar-client-android)
- [Traccar Client iOS app](https://github.com/traccar/traccar-client-ios)

## Features

Some of the available features include:

- Real-time GPS tracking
- Driver behaviour monitoring
- Detailed and summary reports
- Geofencing functionality
- Alarms and notifications
- Account and device management
- Email and SMS support

## Build

Please read [build from source documentation](https://www.traccar.org/build/) on the official website.

## Team

- Anton Tananaev ([anton@traccar.org](mailto:anton@traccar.org))
- Andrey Kunitsyn ([andrey@traccar.org](mailto:andrey@traccar.org))

## License

    Apache License, Version 2.0

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
