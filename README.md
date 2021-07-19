# TensorFlowLite-Microcontrollers-Challenge

TensorFlow Lite for Microcontrollers Challenge

# Summary

This experiment is made for [THE TENSORFLOW MICROCONTROLLER CHALLENGE](https://experiments.withgoogle.com/tfmicrochallenge)
The project is used to classify the emotion of environment by listening voices (Angry, Calm, Happy, Sad, Surprised). 
As hardware setup, [Arduino Nano 33 BLE Sense](https://store.arduino.cc/usa/nano-33-ble) is used and the Workshop Kit (Arduino Nano 33 BLE Sense, USB micro-B Cable - 6 Foot, Low Current Lithium-Ion Battery Pack - 2.5Ah (USB)) is supplied by Google to us for free. Additionally, we included 3 RGB LEDs, 4 jumpers and 1 stripboard to be able to perform analogWrite function, too.
Speech Classification Dataset is obtained from [Kaggle](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio). Additionally, [Google Speech Commands dataset](https://storage.cloud.google.com/download.tensorflow.org/data/speech_commands_v0.02.tar.gz) is used to combine noise with original dataset. 
The model is constructed and optimized by using [Edge Impulse](https://studio.edgeimpulse.com/) Digi-Key YouTube Tutorial [https://www.youtube.com/watch?v=fRSVQ4Fkwjc] is used to understand the usage of Edge Impulse and informed us how to process speech with Arduino.
This Project is completed by Onurcan Köken and Yavuz Balı.

# TinyML

It is important to note that this is our first-time usage of TensorFlow Lite and TinyML, therefore we were not aware much about the concept, but it was a great challenge for us! We have learnt a lot.
During the learning process, we have followed YouTube tutorials of TensorFlow and Digi-Key. Additionally, there were online courses on edX; [Deploying TinyML](https://learning.edx.org/course/course-v1:HarvardX+TinyML3+1T2021/home) and [Fundamentals of TinyML](https://learning.edx.org/course/course-v1:HarvardX+TinyML1+3T2020/home) that we have followed.
However, generally we have followed [Digi-Key YouTube Tutorial](https://www.youtube.com/watch?v=fRSVQ4Fkwjc) to perform this ML project.

# The Dataset

Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) Dataset which contains Speech Audio files (16 bit, 48kHz, .wav). There were originally 8 emotions, and the dataset was separated by number of actors. 
We have decreased number of emotions to 5, and instead of separating actor by actor, it is decided to separate by emotions. Then, [AudaCity](https://www.audacityteam.org/) program is used to arrange frequency of speech files. Sampling frequency of Arduino Nano 33 BLE is 35000 samples per second, so the maximum frequency can be half of the maximum value, 17500 samples per second. That is why, frequency of each audio file is set to 16kHz. Additionally, there were some gaps before and after each speech, so we deleted those parts. 

# Training the Model


# Hardware Setup


# YouTube Link 
The demonstration video 
