# papers-pedestrian-detection
Curated list of papers on the topic of Pedestrian Detection

1. [Pedestrian detection in video surveillance using fully convolutional YOLO neural network](https://www.researchgate.net/publication/317967088_Pedestrian_detection_in_video_surveillance_using_fully_convolutional_YOLO_neural_network) 
    * Combine detection and classification tasks using CNN.
    * YOLO CNN - Drawbacks:
        * Full connected layers that obstruct applying the CNN to images with different resolution.
        * Limits the ability to disitinguish small close human figures in groups
    * Changed network architecture overcoming above drawbacks.
    * Datasets:
        * Caltech
        * Kitty
        * Moscow city surveillance data
    * Two stages of traning:
        * Pre-trained new added convolutional layers on Caltech, Kitti
            * Didn't freeze the initial layers
        * Fine tune on ow datasets
            * Learning only for new layers
     * For both stages, 
        * SGD RMSProp
        * Batch Normalisation
        
        
        
   2. [Caltech Pedestrain Dataset Converter for Python users](https://github.com/mitmul/caltech-pedestrian-dataset-converter)
     
