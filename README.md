# 🖼️ Image_Compression using K-Means Clustering

__________
🚀 Overview 
Project showcases a novel image compression method using the K-Means clustering algorithm. By reducing the number of colors in an image, we achieve significant size reduction. ”
This technique is ideal for large images, providing a balance between compression and fidelity. By partitioning the color space into clusters and mapping pixels to their closest cluster, we simplify the image without compromising quality heavily. 

This technique is particularly useful for reducing the size of large images. By adjusting the target width and number of clusters, users can balance compression and visual fidelity according to their needs.
_______________

🛠️ Tech Stack
Python 
Gradio(User Interface)
________________

⚙️ How It Works ?
Converting Image to Numpy Array: We start by converting the input image into a numpy array for further processing.
Resizing the Image: We dynamically resize the image based on its aspect ratio, ensuring that the visual quality is preserved.
Applying K-Means Clustering: We group similar colors together using K-Means clustering, reducing the number of unique colors and compressing the image.
Reshaping the Compressed Image: We reshape the compressed image back to its original dimensions, completing the compression process.
___________________

📸 Sample Use-Cases

- Compressing large images before uploading
- Reducing storage requirements for image-heavy applications
- Balancing compression and quality for web or mobile platforms
  _______

  🧪 Try It Out

Launch the interactive demo built with Gradio to experiment with image compression in real-time. 
Adjust:
- 📏 Image Width
- 🎨 Number of Clusters
- 
...and instantly visualize the compression results!


