Please use below steps to complete the set up.

Please install prerequisites by clicking below link.

https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md

Download latest protobuf releases from below link

https://github.com/google/protobuf/releases

Download models from below link --by choosing clone or download

https://github.com/tensorflow/models

Install spyder --recommanded to execute the project.

Please compile following command to create py files 

Navigate to models\models-master\research\object_detection 

execute following command

protoc object_detection/protos/*.proto --python_out=.

If the above command didnt work then my recommandation execute each proto separately to create py file.

Ex : 
models/protoc-3.5.1-win32/bin/protoc protos/hyperparams.proto --python_out=.

like this execute all the protos.

Then copy and paste py file provide here in models\models-master\research\object_detection 

Launch Spyder

Locate to to models\models-master\research\object_detection

Execute py file step by step 

Then at last step py file will be launched from cam.

Press q to exit from the step.