# GPU-Animation-Baker-Basic

![image](https://github.com/swordmaster003/GPU-Animation-Baker-Basic/blob/master/Screenshots/Cover.png)

## Compare

By default,when we animate a large number of skinned mesh at the same time in screen,the frame rate is very low and the preformance is very bad.

![image](https://github.com/swordmaster003/GPU-Animation-Baker-Basic/blob/master/Screenshots/Compare1.png)

By using this GPU Animation Baker Basic package,you can play a large number animation at the same time on screen,with great performance and better frame rate.

![image](https://github.com/swordmaster003/GPU-Animation-Baker-Basic/blob/master/Screenshots/Compare2.png)

## Support Unity Versions

5.6.6 or higher

## Download

You can download this asset from Unity Asset Store:

[GPU Animation Baker Basic](https://assetstore.unity.com/packages/tools/animation/gpu-animation-baker-basic-135791)

## Online Documents:

[GPU Animation Baker Basic Manual](https://www.swordmaster.info/documents/unity-assets-documents/gpu-animation-baker-basic-manual-document/)

## Features:

- 1.By using compute shader,we sample the animaion data for corresponding model to textures,then use the customized shader to read the animation data from these texture in rendering stage.

- 2.In the GPU Animation basic package,we customized the Standard (Metallic Setup) shader,the Standard(Specular Setup) Shader,and the Simple Shader.These customized shaders could get the animation data from the baked animation texture.

- 3.Shadow effect support

- 4.GPU instancing support.

- 5.Crowd generator support.

- 6.There are three demo scenes in this package:the audience cheer demo,the bird fly demo,and the whale swim demo.

- 7.Full Source Code Support.

- 8.Only support DX10 (shader model 4.0) and GLCore / OpenGL ES 3 or Above.

- 9.The basic version can only bake the genetic or legcy animaion,not support the type of Humanoid animation.

- So if you want to bake all types of skeleton animation,including the Legacy, the Generic, and the Humanoid,please buy the pro version.

- What's more,use the pro version,the baked gpu animation can run on mobile device.

- The pro version link is here: 
[ GPU Animation Pro](https://assetstore.unity.com/packages/tools/animation/gpu-animation-baker-153503)
or [ GPU Animation Pro](https://assetstore.unity.com/packages/tools/animation/gpu-animation-baker-pro-136591/)
 
