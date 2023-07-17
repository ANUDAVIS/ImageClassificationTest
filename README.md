# ImageClassificationTest
Food Classification


Step1: Dataset preprocessing
Original Input Dataset - contains 6 folders namely ApplePie, BagelSandwich, Bibimbop, Bread, FriedRice and Pork.
      * ApplePie - containing 93 images
      * BagelSandwich - containing 45 images
      * Bibimbop - containing 92 images
      * Bread - containing 90 images
      * FriedRice - containing 88 images
      * Pork - containing 89 images

This dataset is splitted using splitfolders() function into train set, validation set and test set and data augmented before training to avoid overfitting.

Number of classes = 6 

              Classes        Label
                 0     -    ApplePie
                 1     -    BagelSandwich
                 2     -    Bibimbop
                 3     -    Bread
                 4     -    FriedRice
                 5     -    Pork
   

Step2: Create base model using pre-trained model Vgg

Step3: Train the model along with using feature of earlystop to avoid overfitting

Step4: Model evaluation

Step5: Hyperparameter tuning

Step6: Test the model with custom image


