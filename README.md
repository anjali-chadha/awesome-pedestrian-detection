# awesome-pedestrian-detection
Curated list of papers on the topic of Pedestrian Detection
## Papers
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
        
2. [Deep convolutional neural networks for pedestrian detection](https://arxiv.org/pdf/1510.03608.pdf)
      * Extends R-CNN
      
      
      
## Github Repositories
        
1. [Caltech Pedestrain Dataset Converter for Python users](https://github.com/mitmul/caltech-pedestrian-dataset-converter)
2. [Convert Caltech annontations to Yolo compatible format](https://github.com/Jumabek/convert_caltech_annos_to_yolo)     
3. [DeepPed: Deep CNN for Pedestrian Detection (2016)](https://github.com/DenisTome/DeepPed)
4. [LSTM-RCNN Pedestrian Detection](https://github.com/buffer51/lstm-rcnn-pedestrian-detection)
5. [Segmentation Based Approach for Pedestrian Detection](https://github.com/colegulino/Deep-Neural-Networks-for-Pedestrian-Detection)
