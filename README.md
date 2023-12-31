# tone_mapping_model

Manual Exposure Correction:

<img width="733" alt="Screenshot 2023-10-17 at 3 27 25 PM" src="https://github.com/jasonshin1127/exposure-correcting-model/assets/101506840/22372644-91c7-43db-9cd0-78a9a3ac2943">

Dataset:

![112195940-e7091780-8be0-11eb-869d-8a40675beb3a](https://github.com/jasonshin1127/exposure-correcting-model/assets/101506840/ac5b22b8-363b-46f5-96b4-0225dc35d335)
ImageX : Images that require exposure correction

ImageY : Images that are manually edited

Patchify (patch.py): python files that extract 16*16 patches from the original image

<img width="996" alt="Screenshot 2023-10-17 at 5 37 23 PM" src="https://github.com/jasonshin1127/exposure-correcting-model/assets/101506840/30081fcb-4111-47ca-a410-7c0c9840c888">

then, run model.py to start training and reassemble the patches:

<img width="610" alt="image" src="https://github.com/jasonshin1127/exposure-correcting-model/assets/101506840/191dcc31-8b9c-4be8-9865-f5ad63f0cd2f">

(left: input image, Right: output image)

Result:

the result image quality diminishes due to the patch reassembling process but gives critical guidelines for manual tone editing engineers







