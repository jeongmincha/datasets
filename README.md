# datasets
A repository for datasets
- online-handwriting-signature.zip
  - It contains photos of strokes for handwriting signature.
    - If a data set contains only perfect signature images, the data set is considered as an offline dataset.
    - If a data set contains other informations such as timestamps and details of strokes, the data set is considered as an online dataset.
  - Image file names are cut\_U[user id]\_[signature id]\_[stroke id]\_[elapsed time].png.
    - For example, \"cur\_U1\_1\_0\_15.png\" means the first stroke of the first signature of the first user. This stroke was written within about 150ms. (Here, the unit of the timestamp is 10ms.)
    - [user id] and [signature id] starts from 1.
    - [stroke id] starts from 0.
    - [elapsed time]'s unit is 10ms.


