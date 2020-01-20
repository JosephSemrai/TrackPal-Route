## TrackPal Route

TrackPal's ultimate goal is to provide commuters in Sri Lanka with information regarding the current positions of various transportation mediums. While this may be helpful for a daily route, the application still requires users to find particular busses, trains, etc. and tap on them to view their location. This dynamic nature of a moving target makes routing very complex.

With this, an application, **TrackPal Route** that automatically manages the routing through a pathfinding algorithm that makes use of these dynamic locations (or a maps API with updating sub-destination points) would be extremely helpful for users, as they would not have to scroll and monitor these locations themselves. They would simply be able to enter their destination and rely on the data being collected by TrackPal.

Ultimately, the goal for this application would be to leverage the different transportation mediums (for example, combining walking, train, and bus) and their locations provided by the data TrackPal is collecting to make an application that provides people with a route that incorporates all of this without the user needing to do anything with regard to monitoring data.

## Concept UI

| Live Navigation with Tracking From TrackPal                  | Route Overview View                                          | Plan Route Using Multiple Mediums                            |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ![ApplicationFrameHost_1omUuRcu5E](https://user-images.githubusercontent.com/29003194/72751506-ca60f200-3b8d-11ea-91f3-701f36ce3f13.png) | ![ApplicationFrameHost_b4TkEA3L0l](https://user-images.githubusercontent.com/29003194/72750756-aef4e780-3b8b-11ea-808e-faa5d043bd66.png) | ![ApplicationFrameHost_V1SPM8nxSr](https://user-images.githubusercontent.com/29003194/72751136-c08abf00-3b8c-11ea-9493-b8e3af42b58b.png) |

## Potential Stack
* React Native + React (if needed for a web dashboard) <- Plays nicely with the TrackPal stack
* Firebase or Express Backend
