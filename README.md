# ShapeNet-Room-Generation
Generating synthetic 3D Point Cloud Rooms with ShapeNet dataset

> [!IMPORTANT]
> You must install the ShapeNetCore in order to get ShapeNet's object for creating rooms. Download [here](https://drive.google.com/file/d/1N-hPfbb3GOJy541hKW4lMu9A7W6btY_y/view?usp=sharing)
> This project is under my working so The Code for this Project is Hidden by me

## Introduction about ShapeNet
Shapenet is a widely used Synthetic object based 3D Point Cloud dataset. it contains 55 categories / classes like table, chair, sofa,..... More information about ShapeNet, read [HERE](https://paperswithcode.com/paper/shapenet-an-information-rich-3d-model)

<img src="https://cseweb.ucsd.edu/~shz338/images/shapenet.jpg" width="500" alt="Screenshot of My Project">

## The Purpose of this Project
Many works so far on 3D Point Cloud tasks have used ShapeNet and archieved good results. However, this is just only single object field.
In real life task, we should often work with large scenes like rooms, streets, .... with many objects.
The demain is clear, so now I'm trying to create a Multiple ShapeNet Object scene, only based on ShapeNet and applied real life rules.

<img src="https://i.ytimg.com/vi/RHHFC2UaZtQ/maxresdefault.jpg" width="600" alt="Scene">

## Progress
So far, i'm able to retrieve object from ShapeNet out and put it into a room. Currently, i only make simple rooms with chairs, tables, bookstores, sofas and beds. See my demo below

![image](https://github.com/WinerDeCoder/ShapeNet-Room-Generation/assets/136697023/9cb284ef-98c0-43ee-9018-5689e67e9169)

![image](https://github.com/WinerDeCoder/ShapeNet-Room-Generation/assets/136697023/8ff8ddb6-d7a5-4d3f-ae75-d5830c6d15b5)


You could see i can create a Synthetic Room with Walls, Ceiling, Floor, Beams, Columns and Objects. However, the objects are not in good arrangement.


**In my next step, we will apply learning rules to make it more realistic.**

## To be Continued
