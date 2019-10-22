# Vizdnn







### Pip Install

```
!pip install vizdnn==0.0.1
```


### Use

```
import vizdnn

visualize_neural_network = vizdnn(keras.applications.resnet.ResNet50() , "network_layer_name" , "test_image_name.jpg")

vis_layer = visualize_neural_network.get_layer()
visualize_neural_network.viz_feature_map(vis_layer)

```