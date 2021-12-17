# AMLS_21-22-_SN20055214
This task is to carry out binary classification and four classification of human brain tumor images. The purpose of this document is to inform the task content, the organization form of the document, the necessary packages and the running problems of the code.

Calls to external libraries:

            tensorflow2,numpy,matplotlib,keras,cv2,os,PIL,pickle,sklearn,pandas

Organizational form of documents：

1.data set：
            
            The original dataset is stored in /dataset/image1.
            The original testset is stored in /test
            The dataset label document is stored in label.csv
            The testset label document is stored in test_label.csv
            
2.For data processing：

            The code file of data conversion is located at load_data_3D.ipynb
            The data set is converted into numpy array which is stored in alldata_3D.npy
            The test set is converted into numpy array which is stored in testdata_3D.npy 
            
3.For binary classification:

            (The running of SVM takes more time, so it is divided into two files. SVM_pca_learningcurve.ipynb  is only drawn as a learning curve, not the main file.)
            The code file of SVM Learning Curve and Pca Dimension reduction is located at SVM_pca_learningcurve.ipynb(optional) 
            The code file of SVM model is located at SVM_binary.ipynb
            The code file of AlexNet softmax model is located at ALexnet_binary_softmax.ipynb
            The code file of AlexNet sigmoid model is located at ALexnet_binary_sigmoid.ipynb
            
4.For multi classification:

            The code file of VGG16 self training model is located at VGG_Self_Mup.ipynb
            The code file of VGG16 pre training model is located at VGG_Pre_Mup.ipynb
            The code file of Xception model is located at Xception_Mup.ipynb
