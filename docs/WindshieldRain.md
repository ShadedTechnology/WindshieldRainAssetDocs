# Windshield Rain

**WindshieldRain** component simulates rain drops on your windshield using ComputeShader. You can configure here how your rain drops should look and behave. When you add **WindshieldRain** component to your gameObject it should look like this:

> ![WindshieldRain empty](_media/windshield_rain_empty_no_command_buffer.png)<br/>
> Empty **WindshieldRain** component

If you see warning to add [CommandBufferBlur](/CommandBufferBlur) to your main camera, click `Add CommandBufferBlur to main camera` button for the warning to disappear and for the blur texture to work properely for your windshield shader.

> <img src="_media/windshield_rain_component/add_command_buffer.png" alt="Add CommandBufferBlur" width="640" /><br/>
> Add [CommandBufferBlur](/CommandBufferBlur) component to your main camera for the blur texture to work

At the top of the **WindshieldRain** component you should see info box to add [DropletsAcceleration](/DropletsAcceleration) component to make your trops react to car acceleration and gravity. When you click `Add DropletsAcceleration component` button the component will be added automatically to your gameObject. You can read more about this component [here](/DropletsAcceleration).

> <img src="_media/windshield_rain_component/add_droplets_acceleration.png" alt="Add DropletsAcceleration" width="640" /><br/>
> Add [DropletsAcceleration](/DropletsAcceleration) component to your gameObject

## Windshield Plane

## Texture Settings

## Rain Turbulance

## Rain Drops Settings

## Wipers Settings

## Rain Material

## Rain Post Prcess


<div class="page-nav">
  <a href="#/PrepareCar" class="prev">
    <div class="title">Prepare Your Car</div>
    <div class="subtitle">⬅ Previous Page</div>
  </a>
  <a href="#/DropletsAcceleration" class="next">
    <div class="title">Droplets Acceleration</div>
    <div class="subtitle">Next Page ➡</div>
  </a>
</div>
