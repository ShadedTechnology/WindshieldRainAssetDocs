# Opening Demo Scene

First we have to import assets from the package. Select `Common` folder, `Readme` files and folder with the name of the pipeline you use (`Built-in RP`, `URP` or `HDRP`). Make sure to uncheck folders for other pipelines.


> <img src="_media/import_built_in.png" alt="Importing assets for Built-in Pipeline" width="800" /><br/>
> Importing assets for Built-in Pipeline

> <img src="_media/import_urp.png" alt="Importing assets for URP Pipeline" width="800" /><br/>
> Importing assets for URP Pipeline

> <img src="_media/import_hdrp.png" alt="Importing assets for HDRP Pipeline" width="800" /><br/>
> Importing assets for HDRP Pipeline

Then navigate to directory "Assets/WindshieldRainAsset/&lt;YourPipeline&gt;/Demo/Scenes" and open "DemoScene" scene.<br/>
Next before you run the scene click first on the GameObject named "--- !!! OPEN ME FIRST !!! ---" in the scene hierarchy.

> <img src="_media/demo_scene_hierarchy.png" alt="First open this GameObject" width="800" /><br/>
> First open this GameObject

In the Inspector you should see something like this:

> <img src="_media/package_installer_inspector.png" alt="You should see this component" width="800" /><br/>
> You should see this component

If you have newer Unity Editor you will see that TextMeshPro is already installed because its now built into the Unity Editor.

> <img src="_media/package_installer_inspector_tmp.png" alt="In the newer Unity Editors TextMeshPro is already installed" width="800" /><br/>
> In the newer Unity Editors TextMeshPro is already installed

Now install all missing packages by clicking on the buttons **one at a time!** This may take a while so you have to be patient.

If you are using URP Pipeline, you should see also warning to add renderer features. Click "Add Render Features" to enable widshield blur and glass rendering.

> <img src="_media/package_installer_urp.png" alt="In URP Pipeline you can see also warning to add renderer features" width="800" /><br/>
> In URP Pipeline you can see also warning to add renderer features

After installing all packages, the "PackageCheckerBehaviour" component should look like this:

> <img src="_media/package_installer_complete.png" alt="After installing all packages you should see this" width="800" /><br/>
> After installing all packages you should see this



Now you can start the Demo Scene!

Sometimes when starting the scene just after you've installed TextMeshPro Essentials the UI text doesn't load.
If your text is missing like below, stop and restart the game one more time.

> <img src="_media/missing_ui.png" alt="Missing UI Text" width="800" /><br/>
> If you don't see UI text in your Demo Scene, stop and start the scene one more time.

Now everything should work. You can play around and test the Windshield Rain Asset!

> <img src="_media/working_demo_scene.png" alt="Working demo scene" width="800" /><br/>
> Now you can enjoy the demo scene :D

<div class="page-nav">
    <span></span>
    <a href="#/PrepareCar" class="next">
        <div class="title">Prepare Your Car</div>
        <div class="subtitle">Next Page ➡</div>
    </a>
</div>