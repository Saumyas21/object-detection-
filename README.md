# object-detection-
I have created a folder called "dataset" to store images of different types of vehicles. Within this folder, I have organized subfolders for each vehicle type, such as "car" and "bus."

To work with these images, I have imported libraries such as TorchVision, OpenCV, and Numpy. After preprocessing the data, which involves training the model over several epochs, the model learns from the entire dataset, adjusting its parameters to improve accuracy. Multiple epochs are often used to refine the model's understanding of the data.

Moving on to the detection process, I have imported the Coco variables, which hold information about objects, into the code. During detection, the CNN model plays a crucial role. By providing the image path, the model automatically detects objects, draws square boxes around them, and labels them, identifying whether it's a vehicle, human, or tree.
