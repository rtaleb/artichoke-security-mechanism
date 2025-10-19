
## 🚀 About Project
This project aims to enforce security rules on accessing a pdf document allowing the owner of the document to:
• have control over who is accessing what in his document.
• view, at any time, the sequence of changes done to the document.
• track the path followed by a piece of data accessed by a peer from its origin to its destination.
This is being done using the concept of a blockchain called ”Artichoke” that stores and manipulates an immutable sequence of peer-action verified by all peers in the network.
The document is a pdf file containing data fields about the owner of the document. 

  
## Tech Stack
We used [icedPDF](http://www.icesoft.org/java/projects/ICEpdf/overview.jsf) viewer library to deals with pdf, and java library to implement our solution in Eclipse.

We also used [Artichoke-x](https://github.com/liflab/artichoke-x). This helps making encryptions and decryptions, and includes useful security features that can be used. 
  
## How to Run the code

To run this code:
**First**, please download Intellij [IDEA software](https://www.jetbrains.com/idea/download)

**Second**, In the code, in the class called ArtichokeSwingController.java, you find a global variable "path" in which the path to the code should be written. To get the path, just right click on the ca.uqac.lif.artichoke package, then click copy path. Please write the path in the path variable in the format as shown the picture below.



