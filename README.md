# Cinnamon-Flutter-Projects
Descriptions of projects that I worked on as a Flutter developer at Cinnamon Agency


## Return Valets
#### [Return Valets, LLC](https://www.returnvalets.com/)

This mobile application facilitates the return of purchased products in certain states of the USA. It allows users to schedule pickup returns from delivery agencies at their addresses and ensures the safe delivery of products to the desired destination.

Link to App Store: [here](https://apps.apple.com/us/app/return-valets/id1627509692)  
Total size of Flutter team: 2  
Phases of my involvement: joined a colleague in early development stages and participated until completion  
State management: GetX  

**My contributions:**

- replication of UI from provided design in Figma
- REST API integration, 
- phone number authentication & OTP SMS verification
- logic and UI for scanning package barcodes
- integration of Google API methods for address selection
- display of address on Google Maps
- significant code quality improvements (code refactoring)
- suggested and added animations for better user experience
- deployment of Android and iOS applications


____

 
## Alpine CSP AutoEQ
#### [Alpine Web Page](https://www.alpine-usa.com/)

Among its products, Alpine offers special [PXE-C80-88 amplifiers](https://www.alpine-usa.com/product/pxe-c80-88-optim8-sound-processor). The mobile and desktop applications are designed and implemented as a complement to these amplifiers, serving as a means for easy and precise manual or automatic EQ adjustment by interacting with a plotted graph to enhance audio experience or sound characteristics.

Platforms: iOS Mobile and Desktop  
Link to App Store: [here](https://apps.apple.com/us/app/pxe-c80-c60/id6444423958)  
Phases of my involvement: from start to finish  
Total size of Flutter team: 2  
State management: GetX  

**My contributions:**

- precise implementation of planned design for all parts of the application, including the challenging part with the graph
- smart clean-code solution to support 3 different variants of UI design for corresponding screen state and availability: portrait mode on mobile device, landscape mode on mobile device, and the desktop application itself
- complete implementation of an interactive graph for manually designing EQ curve on all platforms using the fl_chart package:
    - ability to move EQ curve at anchor points using drag and drop method
    - definition, execution, and implementation of all mathematical formulas constituting the logic of g(raph control
    - optimization through iterative improvement of prototypes until achieving a solution that responds most quickly and effectively to user demands
    - implementation of pinch to zoom feature
    - navigation on zoomed-in graph plane with pan action (finger movement)
    - adding anchor points to the graph on double-tap command
    - deleting anchor points on long-press command
    - resolving conflicts and other touchpad-level difficulties
    - fixing problematic outcomes during dynamic window resizing in the desktop application

____  

## Smart Fishing Spots
#### [Salt Strong LLC](https://smartfishingspots.com/)

Salt Strong improves fishing experie)nces by giving its subscribers helpful fishing insights and recommending the best nearby fishing spots based on the fishing-related metrics.

Link to App Store: [here](https://apps.apple.com/us/app/smart-fishing-spots/id6459022829)  
Total size of Flutter team: 3  
Phases of my involvement: I joined the team later, in the second half of the development process, to help in meeting the agreed deadline for delivery  
State management: Riverpod  

**My contributions:**
- search bar for finding addresses using Google API and locating them on the map
- authentication flow (login, registration, password recovery), specially designed validator methods for input data
- bug fixes before deployment
- In-App purchase


____  


## Vision Anchor
#### [Vision Anchor Web Page](https://www.visionanchor.net/)

The MVP application, still in its early development stages. It's a part of a smart anchoring system that provides users with insights into the anchor's location via the buoy it's attached to. The mobile application communicates with the device, establishing a BLE connection, and receives real-time GPS locations of the buoy. The current buoy location is displayed on Google Maps, along with other received data such as signal strength and battery status. Users receive alerts through notifications and sound signals when a deviation from an acceptable geographic boundary is detected in the buoy's location.


Total size of Flutter team: 2  
Phases of my involvement: At the beginning of our collaboration, the clients already had an MVP application with basic features. My responsibility was to implement fixes based on their requests  
State management: stateful widget  

**My contributions:**
- researching, testing, and debugging BLE connection  
- fixing the algorithm that collects and encodes data from the base device  
- implementing sound alarms and local notifications for critical deviations  
- researching and addressing cases of consecutive disconnections  

____  


## WIC PAY, Worldcom Finance
#### [Worldcom Finance Web Page](https://worldcomfinance.com/)

An application suitable for sending money to people abroad, as well as other ways of managing personal finances.

Link to App Store: [here](https://apps.apple.com/us/app/worldcom-finance/id1557852337)  
Total size of Flutter team: 3 (I joined a team organized by the client. I was the only one from my company on this project.)  
Phases of my involvement: From start to finish (with a colleague starting a week before me)  
State management: GetX  

**My contributions:**

- improving project structure, proposing rules for higher-quality and sustainable code
- implementing functionalities as per client's vision, UI based on specific designs from Figma
- REST API integration
- code refactoring
