# Troubleshooting

## FAQ
### - My demo scene doesn't work correctly
Double-check that you followed the [Open Demo Scene](/OpenDemoScene) guide carefully, step by step. If something still is not working please contact me on email.
### - I tried changing Windshield Rain parameters via script or animation, but nothing happens
Make sure to call the UpdateShaderValues() method on the [Windshield Rain](/WindshieldRain) component after every parameter change.
### - My windows are black or gray
- Built-In RP - make sure you have [Command Buffer Blur](/RenderingWindshieldAndBlur#built-in-command-buffer-blur) component on your main camera.
- URP - make sure you have [Windshield Render Features](/RenderingWindshieldAndBlur#urp-renderer-features) in pipeline renderer data and that you've replaced all your windows mesh renderers with the [Windshield Mesh Renderer](/WindshieldMeshRenderer).
- HDRP - make sure you have **Custom Pass Volume** with [Windshield Passes](/RenderingWindshieldAndBlur#hdrp-custom-pass-volume) and that you've replaced all your windows mesh renderers with the [Windshield Mesh Renderer](/WindshieldMeshRenderer).

## Report a bug
If you’d like to report a bug, request a feature, or have any issues with this asset, you can reach me at:

📧 shaded.technology@gmail.com

In case I don’t reply within a week, please send a follow-up email, as messages can occasionally get lost in my inbox.


<div class="page-nav">
  <a href="#/RenderingWindshieldAndBlur" class="prev">
    <div class="title">Rendering Windshield And Blur</div>
    <div class="subtitle">⬅ Previous Page</div>
  </a>
</div>
