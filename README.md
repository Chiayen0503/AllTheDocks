# AllTheDocks
* Step 1: download AllTheDocks dataset from [link](https://drive.google.com/drive/folders/1q3FO1b1ofJ8oQzntih3IJ4Nmo1uuAHjO?usp=share_link)
* Step 2: check folder structure, both ```gopro_videos/``` and ```gopro_images/``` have two subfolders:
  - ```images/``` 
  - ```csv/``` -> save numerical data except for images
* Step 3: check available data types for ```gopro_videos/``` and ```gopro_images/```

    | DataType | ```gopro_videos``` | ```gopro_images``` |
    | -------- | ------------ | ------------ |
    | Millisecond or Date/Time  | V         | V         |
    | Image  | V         | V         |
    | Longitude  | V         | V         |
    | Latitude  | V     | V         |
    | Altitude  | V         | V         |
    | Speed2D  | V        | X        |
    | Speed3D  | V        | X         |
    | AcclX  | V        | X         |
    | AcclY  | V        | X        |
    | AcclZ  | V        | X      |
    | Accl3D  | V         | X        |
    | GyroX  | V       | X    |
    | GyroY  | V         | X       |
    | GyroZ  | V        | X      |
    | IRI  | V       | X        |
    | Preprocessed IRI  | V        | X         |

