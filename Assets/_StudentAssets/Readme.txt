Instructions for your asset:

1. GitKraken - Clone the repository. Make sure to Pull all changes before doing any work. Make sure your are working in your own branch and NOT the main branch.

2. GitKraken - Right-click the Local branch named 'main'. 

3. GitKraken - Click on 'Create branch here'. The name of the branch should be 'firstname_lastname'

4. GitKraken - Push the current changes to ensure these changes are saved on the remote.

5. Unity - In the directory: '\DLC_Shared_Project_2022\Assets\_StudentAssets' you will need to create a folder. The folder name should be named 'Firstname_Lastname'

6. Unity  -The folder should contain:

	- Your model - 'Assetname_StaticMesh.fbx'. Make sure to 'Generative Lightmap UVs and assign your own material in the Material slot(s). Note that the asset prepared for this project should be scaled relative to the Base Human Male found in the Content Browser from Maya.

	- Your textures - Exported from Substance Painter as Targa (.tga) files. 1024 pixel is the standard size we will be using. Make sure to use 'Unity HD Render Pipeline (Metallic Standard)' Export settings. The file names should be:
'Assetname_BaseMap.tga'
'Assetname_MaskMap.tga'
'Assetname_Normal.tga'
'Assetname_Emissive.tga

	- Your material(s) - 'Assetname_mat'. Note that you should only have more than 1 material if you have a special need, such as a custom shader that utilizes opacity, emission, or some other special attributes.

	- Any other necessary assets, such as shaders created through Shadergraph.

3. Unity - Create a Unity scene. It should be named: 'Firstname_Lastname_scene.scene'

4. Unity - Import your asset into the scene. Make sure the asset sits at the origin of the scene (0,0,0). Create an Empty Game Object and nest the objects if necessary. Drag the asset from the Hierarchy windown down to the Project window in order to create a Prefab of your entire asset.

5. Unity - Save your Unity scene.

6. GitKraken - Verify that all of the changes are accurate and only changes you have made. Stage only the assets and meta files.

7. GitKraken - Commit the staged changes.

8. GitKraken - Push the current changes to ensure these changes are saved on the remote.