Waste Allocation & Recognition Project


# Info: pile_dataset
	Images 0.jpg to 555.jpg are part of wade-dataset, all the other images are from google street view and 
  	annotated by me, because of the little time I had there should be some mistakes, feel free to email me
	if you find any.

# Info: pile_model
	This model is trained using the pretrained model: ssd_mobilenet_v1_fpn_640x640_coco17_tpu-8, to run this model download the
	tensorflow-object-detection api. Load the model using the script object_detection_tutorial.ipynb in models/research/object_detection/colab_tutorials/,
	you have to
	replace PATH_TO_LABELS = 'models/research/object_detection/data/mscoco_label_map.pbtxt' with the directory of the label_map.pbtxt that I provide in the repo.
	replace detection_model = load_model(model_name) with detection_model = tf.saved_model.load('__put the path to pile_model__')
	you are ready to go!

www.maestrostudio.org
