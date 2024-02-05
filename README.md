1. Call data set on your own by using libraries
from keras.models import Sequential
from keras.layers import Dense, Conv2D, MaxPool2D, Flatten
from sklearn.metrics import classification_report
from tensorflow.keras.utils import to_categorical
from keras.models import Sequential
from keras.layers import Conv2D, MaxPooling2D, Flatten, Dense, BatchNormalization, Dropout
from keras.optimizers import Adam
from keras.preprocessing.image import ImageDataGenerator
from keras.callbacks import ReduceLROnPlateau, EarlyStopping
import numpy as np
2. Use the CIFAR dataset
3. Load dataset
4. Check dataset using EDA
5. Preprocessing dataset
6. Try different models
7. Evaluate the model performance by testing
