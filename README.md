# unity-friends
Quality tools for Unity 3D

- https://github.com/SlightlyMad/VolumetricLights/
- https://assetstore.unity.com/packages/tools/camera/rts-camera-43321
- ProBuilder & ProGrids (integrated with Unity)
- https://assetstore.unity.com/packages/essentials/asset-packs/unity-particle-pack-5-x-73777?aid=1101lPGj&cid=1011l7EPFAyN&utm_source=aff


## Tips
- While playing and tweaking values on a component :
  - right click and copy component values
  - exit play mode
  - right click and paste component values
- Hold down Alt while tweaking a value to fine tune
- Mathf.Clamp for clamping values
  - Sometimes used as Mathf.Clamp(value, 0, int.MaxValue);
- Add multiple elements to an array with inspector locking and multi-drag
- Align with view : Select the camera and hit Ctrl + Shift + F
- F : focus on object, F F : focus on object continuously
- Alt + Click on hierarchy : expand all
- Undock preview : Double click on the bar above the preview
- Persists data : PlayerPrefs.Set<...>
- Coroutines : StartCoroutine(Foo()); IEnumerator Foo() { return new WaitForSeconds(delay); }
