# Visit the OpenAR-Art-Exhition: 

https://openar.art/e/openar-art

Recommendations:
* [Jeremy Bailey - Sculpture No.3](https://openar.art/e/openar-art/Yq2kXKW4YuwVSkrn)

* [Tamas Pall - OVO/\map](https://openar.art/e/openar-art/h0JnLBknAIMXFDYq) (step into it)


# WebAR with google model viewer

Creates a simple AR Web Application for prototyping. 

## Create github account: 

https://github.com/

## Create your github page: 

### 1. Follow: https://docs.github.com/en/pages/quickstart (Skip steps 4-6 & Everything starting from "Changing the title and description")

### 2. Create index.html file in your repository:
![github](assets/github_1.png)

![github](assets/github_2.png)

Add the following code: 
```
<script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>

<model-viewer alt="AR Prototype" src="name_of_your_3d_model.glb" ar ar-modes="webxr scene-viewer quick-look" shadow-intensity="1" camera-controls enable-pan></model-viewer>
```
![github](assets/github_3.png)

### 3. Upload your glb file to the repository: 
![github](assets/github_4.png)
### 4. When you visit 

username.github.io

on your phone you should be able to use your model in augmented reality. (takes up to 20 minutes) 

Example: https://juliannetzer.github.io/

