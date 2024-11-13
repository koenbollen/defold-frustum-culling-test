# defold-frustum-culling-test

Just a small isolated test project to see if frustum culling on the near/far plane is working.

[**Launch Web Build**](https://koenbollen.github.io/defold-frustum-culling-test/)

## Screenshots

| No Near Plane Culling:                                                                                      | Near Plane Culling enabled:                                                                          |
|-------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| ![No Near Plane Culling](/.github/screenshots/screenshot-no-near-plane-culling.png "No Near Plane Culling") | ![Near Plane Culling](/.github/screenshots/screenshot-near-plane-culling.png "Near Plane Culling")   |
| ![Drawcalls](/.github/screenshots/drawcalls-no-near-plane-culling.png "Drawcalls - No Near Plane Culling")  | ![Drawcalls](/.github/screenshots/drawcalls-near-plane-culling.png "Drawcalls - Near Plane Culling") |
| 4 render calls, 3 logos and 1 label                                                                         | 4 render calls, 3 logos and 1 label (expect only 2 logos)                                            |

