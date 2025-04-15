# Welcome To My ePortfolio

## Informal Code Review
[![Code Review](https://img.youtube.com/vi/yvcHImLN97k/maxresdefault.jpg)](https://www.youtube.com/watch?v=yvcHImLN97k)


***
## C++ with Visual Studio IDE - 3D Scene Enhancement One

<video width="420" height="340" controls loop="" muted = "" autoplay="">
  <source src="https://github.com/melcian404/melcian404.github.io/raw/refs/heads/main/docs/assets/3Dvid.mp4">
</video>

[Github Repository](https://github.com/melcian404/CPP-3D-Scene)


<details>
	<summary>Project Descritpion</summary>
	This artifact utilizes an OpenGL graphics processing unit (GPU) and C++ to create a 3D model using texture, lighting, and object rendering and controls the virtual environment with hotkeys and camera positions. This includes zooming in and out, panning up and down, left and right, as well as tracking mouse movement. The scene required a combination of simple and complex objects. It depicts a scene of children's toys on a table and was initially created on July 20, 2024.
</details>

<details>
  <summary>Project Enhancements</summary>

  -  Refined inline comments to be concise and descriptive for detailing each function of code.
  -  Adding block comments to detail portions of code completed.
  -  Adding three complex objects of varying shapes, colors, sizes, and characteristics.
  -  Refined and combined object methods to reduce code redundancies.

</details>

<details>
  <summary>Created Object Example</summary>

  ```C++
	void SceneManager::RenderTrees(){

		// declare the variables for the transformations
		glm::vec3 scaleXYZ;
		float XrotationDegrees = 0.0f;
		float YrotationDegrees = 0.0f;
		float ZrotationDegrees = 0.0f;
		glm::vec3 positionXYZ;

	// LEFT TREE TOP
		// Set object scale
		scaleXYZ = glm::vec3(3.0f, 8.0f, 3.0f);

		// set the XYZ rotation for the mesh
		XrotationDegrees = 0.0f;
		YrotationDegrees = 0.0f;
		ZrotationDegrees = 0.0f;

		// set object position   L-R     U-D    F-B
		positionXYZ = glm::vec3(-15.5f, 2.53f, -9.5f);

		// set the transformations into memory to be used on the drawn meshes
		SetTransformations(
			scaleXYZ,
			XrotationDegrees,
			YrotationDegrees,
			ZrotationDegrees,
			positionXYZ);
	
		// set texture and material
		SetShaderTexture("Treetop");
		SetTextureUVScale(2.0, 4.0);
		SetShaderMaterial("wood");
	
		// draw mesh
		m_basicMeshes->DrawConeMesh();
```

</details>

Add an original result image here

<details>
  <summary>Enhanced Result Image</summary>

![EnhancedScene](https://github.com/user-attachments/assets/398ef908-d168-4322-82c2-bada2986b3fd)

</details>



***

## Enhancement Two
- Description
- Enhancements
- Results



***
## Ehancement Three
- Description
- Enhancements
- Results



***
# Education
- Summary 1
- Summary 2
- Summary 3



***
# Work history
- summary 1
- summary 2
- summary 3



***
