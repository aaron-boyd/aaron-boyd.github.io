## $ ./corvus.py

<a href="https://github.com/aaron-boyd/Corvus" class="btn btn-github"><span class="icon"></span>View on GitHub</a>

Corvus is a binary data visualization tool written in Python using a PyQt front end and PyOpenGL. This project was heavily influenced by [Cantor Dust](https://www.battelle.org/case-studies/case-study-detail/accelerating-cyber-vulnerability-analysis-with-binary-files-rendered-as-images), a Battelle product. It can be used to analyze binary data in a quick visual manner. It may take days for an engineer to understand the binary data they are looking at. With Corvus, however, certain characteristics byte frequency and different file formats create easy to interpret visuals. I took on this project to further develop my interest in reverse engineering because in reverse engineering it is not always clear what kind of data one is dealing with and this tool makes it a lot easier. By creating easy to understand visuals, this tool can allow reverse engineers to cut down on analysis time by showing them where and what the important data is. Through the development of this tool I have learned how to make graphical interfaces in python using Gt and rendering large amount of data points with PyOpenGL.

<video autoplay loop>
  <source src="/videos/corvus_demo_3D_violin.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

This video demonstrates opening a `violin.wav` file in Corvus. The 'hollow cube' in the 3D viewer in a characteristic shape of wav files. The magic bytes in the hex dump also give away that the file is of wav format.

<video autoplay loop>
  <source src="/videos/corvus_demo_3D_bin64.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

This video opens a 64 bit binary executable. The 'cube' in the center is an indication of ASCII text. This can indicate that the file has some sort of readable text inside.

<video autoplay loop>
  <source src="/videos/corvus_demo_3D_apple.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

This video opens a bitmap image of an apple. Due to the layout of a bitmap file the resulting 3D and 2D plots have very dramatic triangular shapes. The heat map on the left also has characteristic checkerboard shapes.
