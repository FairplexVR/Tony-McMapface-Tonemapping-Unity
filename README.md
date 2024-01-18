## Tony McMapface Tonemapping for Unity

Only compatible with Unity BIRP and HDRP, unity URP dosn't seems to understand external HDR tonemapping

Based on the original [Tony McMapface by Tomasz Stachowiak](https://github.com/h3r2tic/tony-mc-mapface)

![Screenshot_2](https://github.com/FairplexVR/AgX-Tonemapping-Unity/assets/31825109/77b5c477-06d3-485c-becd-2db7d94214a5)

### Installation

If you're not familiar with external LUTs in Unity, follow these steps to set it up. Assuming your project is configured in Linear Color Space with a working Post-Process, here's how to add the external LUTs:

1. Download the Unitypackage from from [the release page](https://github.com/FairplexVR/Tony-McMapface-Tonemapping-Unity/releases/tag/1.0.0) and import it your Unity project.
2. In your global Post-Process Volume Component, add a Color Grading effect by clicking on Add Effect... > Unity > Color Grading.
3. Change the Mode to External.
4. In the Lookup Texture field, drag and drop a LUT of your choice.

Enjoy!
