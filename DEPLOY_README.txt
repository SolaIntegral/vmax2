
Deployment Steps (GitHub Pages, production)

1) Put these files in your repository root:
   - view_vmax_ar_production.html
   - vmax_bike_only_v2_black_fixed.glb
   - vmax_bike_only_v2_black_fixed.usdz   (iOS Quick Look; create via Reality Converter or Blender)

2) Ensure GitHub Pages is enabled for the repo (Settings → Pages → “Deploy from a branch”, main / root).

3) Access your page:
   https://<username>.github.io/<repo>/view_vmax_ar_production.html

Notes:
- Android: AR works with the GLB (Scene Viewer / WebXR).
- iOS: AR requires USDZ. If the USDZ is missing, iOS still shows the 3D viewer but AR won’t start.
- Real scale is enforced with ar-scale="fixed". If you prefer room-fit, change to ar-scale="auto".
- poster.png is a lightweight “loading” image with a birthday theme.
