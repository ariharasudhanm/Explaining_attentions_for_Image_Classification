<div id="top"></div>
<!--


<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<div align="center">
  
[![Contributors][contributors-shield]](https://github.com/ariharasudhanm/Image-classification-using-transfer-learning/graphs/contributors)
[![Last-commit][last commit-shield]](https://github.com/ariharasudhanm/Image-classification-using-transfer-learning/graphs/commit-activity)
[![MIT License][license-shield]](https://github.com/ariharasudhanm/Image-classification-using-transfer-learning/blob/main/LICENSE)
[![LinkedIn][linkedin-shield]](https://www.linkedin.com/in/ariharasudhan/)
<!-- [![Forks][forks-shield]][forks-url] If needed add it later
[![Stargazers][stars-shield]][stars-url]  If needed add it later -->
 </p>
</div>
  
  
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ariharasudhanm/Image-classification-using-transfer-learning">
    <!-- <img src="images/logo.png" alt="Logo" width="80" height="80"> -->
  </a>
  <h3 align="center">Image classification using transfer learning </h3>

  <p align="center">
    Classification of acoustic and electric guitar with transfer learning methods using tensor flow
    <br />
    <a href="https://github.com/ariharasudhanm/Image-classification-using-transfer-learning"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <!-- <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a> -->
    ·
    <a href="https://github.com/ariharasudhanm/Image-classification-using-transfer-learning/issues">Report Bug</a>
    ·
    <a href="https://github.com/ariharasudhanm/Image-classification-using-transfer-learning/community">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Training samples][product-screenshot]](https://github.com/ariharasudhanm/Image-classification-using-transfer-learning/blob/main/Images/Samples_from_original_dataset.png) | [![Sample data augmentation][product-screenshot]](https://github.com/ariharasudhanm/Image-classification-using-transfer-learning/blob/main/Images/Image_augmentation.png) |  [![Training and validation accuracy][product-screenshot]](https://github.com/ariharasudhanm/Image-classification-using-transfer-learning/blob/main/Images/Training_and_validation_accuracy.png)


Project Overview:
* Dataset creation(train, validation, test splits) including data augmentation.
* Training few layers layers and perform validation to know whether to further train few more layers.
* Validation and testing.

<p align="right">(<a href="#top">back to top</a>)</p>


### Built With

These are programming languages, libraries, frameworks and other tools used in this project.

* [Python](https://www.python.org/)
* [Tensorflow](https://www.tensorflow.org/tutorials/images/transfer_learning)
* [Numpy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Usage
* There are three directories inside the dataset directory called test, val(for validation) and train  where each directories contains 2 directories called    acoustic and electric which contains respective categories of images (this is done manually to avoid API contradictions in tensorflow but it is better to split it randomly in order to avoid bias in train,validation,test set splitting process).
* In the notebook we use absolute path of these directories to feed it when creating a train, test, validation datasets(be aware of this while running).
* In order to avoid confusions running it on different OS platforms we are considering the absloute path of the images while creating datasets.
* You can add more images to their respective images directories if needed.


<!-- ROADMAP -->
## Roadmap

- [x] Data split and data augmentation
- [x] Training and validation
- [x] Testing

See the [open issues](https://github.com/ariharasudhanm/Image-classification-using-transfer-learning/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Results -->
## Results

Testing the trained model for first six images from test set `Images/Test_Samples.png`.


![Testing_few_images](https://user-images.githubusercontent.com/49080561/147982594-b16cfff7-fd0c-4b13-a242-7542360e4c28.png)

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@AriharasudhanM](https://twitter.com/your_username) - ariharasudhan.muthusami@gmail.com

Project Link: [Image-classification-using-transfer-learning](https://github.com/ariharasudhanm/Image-classification-using-transfer-learning)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Tensor flow transfer learning documentation](https://www.tensorflow.org/tutorials/images/transfer_learning)
* [Tensor flow transfer learning tutorials](https://www.tensorflow.org/tutorials)
* [Transfer Learning Guide: A Practical Tutorial With Examples for Images and Text in Keras](https://neptune.ai/blog/transfer-learning-guide-examples-for-images-and-text-in-keras)
* [Transfer Learning with TensorFlow Tutorial: Image Classification Example](https://lambdalabs.com/blog/transfer-learning-with-tensorflow-tutorial-image-classification-example/)
* [Transfer learning for Deep Neural Networks using TensorFlow](https://medium.com/@saitejaponugoti/transfer-learning-for-deep-neural-networks-using-tensorflow-d628e454e9e5)
* [Transfer learning and fine-tuning in Keras and Tensorflow](https://voxpow.com/blog/transfer-learning-and-image-recognition-system/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ariharasudhanm/Image-classification-using-transfer-learning?color=Green&logoColor=Red&style=for-the-badge
[contributors-url]: https://github.com/ariharasudhanm/Image_classification_Kaggle_Competition/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Commit-shield]: https://img.shields.io/github/commit-activity/m/ariharasudhanm/Image-classification-using-transfer-learning?color=Green&style=for-the-badge
[Last-commit]: https://github.com/ariharasudhanm/Image_classification_Kaggle_Competition/graphs/commit-activity
[last commit-shield]: https://img.shields.io/github/last-commit/ariharasudhanm/Image-classification-using-transfer-learning?style=for-the-badge
[matplotlib-shield]: https://img.shields.io/badge/Matplotlib-v3-Green
