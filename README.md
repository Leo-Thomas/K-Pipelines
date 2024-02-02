# K-Pipelines: Synthetic Generated Data for Intelligent Corrosion Classification in Oil and Gas Pipelines

<!-- ABOUT THE PROJECT -->
## About the project

This research presents the K-Pipelines dataset, a pioneering synthetic image collection designed specifically for the classification of corrosion in oil and gas pipelines. Deviating from the traditional approach of training custom architectures, our research utilized an online image generation tool powered by Stable Diffusion. This choice was anchored in the platform's robust ability to rapidly produce a high volume of diverse and detailed images, a task that would be resource-intensive and time-consuming if starting from scratch. The dataset was carefully constructed using a sequence of refined prompts, derived from a review of pipeline characteristics including material types, environments, and corrosion forms. K-Pipelines consist of 600 PNG images of 512x512 resolution, with an equal split of corroded and non-corroded pipeline images across various conditions and settings. Further enhancing its value, an augmented version of the dataset was developed, totaling 1080 images, to improve the depth and breadth of the data available for model training. Our comprehensive evaluation employed state-of-the-art deep learning classifiers, specifically VGG16, ResNet50, EfficientNet, InceptionV3, MobileNetV2, and ConvNeXt-base, to test the integrity of the K-pipelines dataset. These models showcased its robustness by consistently achieving accuracies around the 90\% mark, illustrating the dataset's substantial promise as a resource for both AI research and real-world applications in the oil and gas industry. The dataset is publicly available for access and use within the scientific community.

### Paper

Soon

<!-- GETTING STARTED -->
## Installation

pip install git+https://github.com/Leo-Thomas/K-Pipelines

## Data set description

This dataset consists of 600 synthetic generated images of corroded and non-corroded pipelines. 

We have two versions, the standard one and the augmented one that amounts to 1080 images.

Distribution of the pipeline dataset: standard and augmented versions with training, validation, and testing splits:

| Version    | Total  | Training (80 \%) | Validation (10 \%) | Testing (10 \%) |
|----------|---------|--------------|--------------|--------------|
| Standard  | 600 | 480 | 60 | 60 |
| Augmented  | 1,080 | 864 | 108 | 108 |

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CITAITON -->
## Citation

Soon

<!-- CONTACT -->
## Contact

Leo Ramos - [LinkedIn](https://www.linkedin.com/in/leo-thomas-ramos/) - leo.ramos@kauel.com

Francklin Rivas-Echeverría - [LinkedIn](https://www.linkedin.com/in/francklin-rivas-echeverria-514180144/) - francklin.rivas@kauel.com

Edmundo Casas - [LinkedIn](https://www.linkedin.com/in/edmundocasas) - edmundo.casas@kauel.com

<br>
<br>


<p align="right">(<a href="#top">back to top</a>)</p>
