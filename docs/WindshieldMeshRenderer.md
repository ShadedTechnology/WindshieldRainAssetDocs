# Windshield Mesh Renderer

This component makes sure that your car windows meshes are rendered after the Windshield Blur Textures Pass. It is used only in the URP and HDRP pipelines. This makes rendering transparent objects like rain drops and other behind the windshield possible.

To replace your **MeshRenderer** component just add **WindshieldMeshRenderer** compoenent to your object.
> <img src="_media/add_windshield_mesh_renderer.png" alt="Add Windshield Mesh Renderer component" width="400" /><br/>
> Add **WindshieldMeshRenderer** component to your car window object.

Then mesh and material will be automatically assigned and you should see warning to remove **MeshRenderer**. Click "Remove Mesh Renderer component" button and its done.

> <img src="_media/windshield_mesh_renderer.png" alt="Windshield Mesh Renderer component" width="800" /><br/>
> Click "Remove Mesh Renderer component" button to remove **MeshRenderer**.

<div class="page-nav">
  <a href="#/RainMaterial" class="prev">
    <div class="title">Rain Material</div>
    <div class="subtitle">⬅ Previous Page</div>
  </a>
  <a href="#/RainPostProcess" class="next">
    <div class="title">Rain Post Process Profile</div>
    <div class="subtitle">Next Page ➡</div>
  </a>
</div>