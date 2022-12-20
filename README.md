# Transfer-Learning-of-Xception-and-Yolov5

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This project implement different Artificial Neural Network tasks to perform the flower species classification and car detection. Trained Xception model are implemented to perform flower species classification, trained Yolov5m model are implemented to perform car detection.

Car detection dataset includes 1001 training images with know labels and 175 test images with labels. About 60% of training images have no car in it.

Flower species dataset includes 1678 images from 10 classes, each RBG image is of size  300×300×3:

```
*Roses*  *Magnolias* *Lilies* *Sunflowers* *Orchids* *Marigold* *Hibiscus* *Firebush*	*Pentas* *Bougainvillea*
```


The data was visualized, preprocessed and used to train several neural network models.

After implementing performance evaluation metrics, we get 100% for train set and 88% for test set in fine-tuned Xception model for flower species. 
mAP0.5 = 0.993 for train set and mAP0.5 = 0.943 for test set are achieved in fine-tuned yolov5m model for car detection.



For more detail, please see my report paper. [https://github.com/Danielyaoan/Transfer-Learning-of-Xception-and-Yolov5.git](https://github.com/Danielyaoan/Transfer-Learning-of-Xception-and-Yolov5.git)


<!-- GETTING STARTED -->
## Getting Started


### Dependencies

* NumPy

```sh
pip install numpy
```
* Pandas

```sh
pip install pandas
```

* scikit_learn
```sh
pip install scikit-learn
```

* MatPlotLib
```sh
pip install matplotlib
```

* os
```sh
pip install os
```

* cv2
```sh
pip install opencv-python
```

* joblib
```sh
pip install joblib
```

* torch
```sh
pip install torch
```

* tqdm
```sh
pip install tqdm
```

* pillow
```sh
pip install pillow
```

* shutil
```sh
pip install shutil
```

* yaml
```sh
pip install yaml
```

* requirement for yolov5
```sh
pip install -qr requirements.txt
```

### Installation

1. Clone the repo
   ```sh
   https://github.com/Danielyaoan/Transfer-Learning-of-Xception-and-Yolov5.git
   ```
2. All preprocessed images, labels and trained models together with final results are included in the following google drive: 

[https://drive.google.com/drive/folders/1HGT-6jQzNyiMqwNzyaWHu_8lXWvLdLcD?usp=sharing](https://drive.google.com/drive/folders/1HGT-6jQzNyiMqwNzyaWHu_8lXWvLdLcD?usp=sharing)



<!-- USAGE EXAMPLES -->
## Usage

Download all file in google cloud, modify the directory in the Train notebook (the only do once part) to specify your ideal file location and run the Train notebook once so it can automatically generate the file for model and dataset for each task. The Test notebook calls all necessary trained models to evaluate performance for the test set.



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- Authors -->
## Authors

Yao An Lee - danielyaoanlee@gmail.com

Project Link: [https://github.com/Danielyaoan/Transfer-Learning-of-Xception-and-Yolov5.git](https://github.com/Danielyaoan/Transfer-Learning-of-Xception-and-Yolov5.git)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements



## Thank you
