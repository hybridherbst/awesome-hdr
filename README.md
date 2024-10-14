# Awesome HDR
HDR resources for web dev and beyond

## Try it out

AVIF-based pages should have pretty wide availability by now.  
Canvas-based pages (WebGPU, realtime 3D) are Chrome 129+ and equivalent.  

- AVIF HDR Test Page: https://alexfry.github.io/ACES_ODT_Candidates_Examples/diagnostic.html

- PlayCanvas HDR Demo: https://engine-hlvhm84x4-playcanvas.vercel.app/#/graphics/clustered-lighting
  - Source Code: https://github.com/playcanvas/engine/blob/d50705d85e8f018c60ff0f521f3e440c0d4040c9/src/platform/graphics/webgpu/webgpu-graphics-device.js#L324
- Bright Pixel Page: https://ccameron-chromium.github.io/webgpu-hdr/example.html
- Bright Pixel Page, WebGL: https://ccameron-chromium.github.io/webgl-hdr/example.html (**not** working in Chrome as of 20241014)
- Greg Benz' Instagram Page with HDR images: https://www.instagram.com/gregbenzphotography/

## Some Experimental Findings
- JPEGs with Gainmaps work in Mac Preview, but don't work in Mac Finder
- YouTube does not support H.265/HEVC in HDR, but supports H.264 HDR10 Rec202 HLG and PQ

## More resources

- WebGPU Explainer: https://github.com/ccameron-chromium/webgpu-hdr/blob/main/EXPLAINER.md
- https://github.com/cmahnke/awesome-browser-hdr

- Test page with code, image, and video support: https://gregbenzphotography.com/hdr/#tests
  - Information on Instagram/Threads HDR Support: https://gregbenzphotography.com/hdr-photos/instagram-now-supports-hdr-photos/
  - Info about Camera Raw: https://gregbenzphotography.com/hdr-photos/jpg-hdr-gain-maps-in-adobe-camera-raw/

- Rant Tweet about iPhone HDR Video Editing: https://x.com/hybridherbst/status/1844493871998550447

- Test Image for brightness response (adjust your monitor's brightness settings if it supports HDR to see what it does)
   ![img](https://scontent-fra5-2.cdninstagram.com/v/t51.29350-15/456601983_821166773463295_1912801064159365898_n.jpg?stp=dst-jpegr_e15&efg=eyJ2ZW5jb2RlX3RhZyI6ImltYWdlX3VybGdlbi42MTJ4NDQzLmhkci5mMjkzNTAuZGVmYXVsdF9pbWFnZSJ9&_nc_ht=scontent-fra5-2.cdninstagram.com&_nc_cat=107&_nc_ohc=ueSs6LZryLEQ7kNvgHiNXeU&_nc_gid=c6b3c9ee93aa4150b336175397ca8ac7&edm=APoiHPcBAAAA&ccb=7-5&ig_cache_key=MzQ0MTI1NDkyMjczNjQ5OTYwNw%3D%3D.3-ccb7-5&oh=00_AYAr5CIEZBGlSU1pQvmuMb2N3ZHbwHsuaaR33gaVPnHKrg&oe=6713424B&_nc_sid=22de04)
