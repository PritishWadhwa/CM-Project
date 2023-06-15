<object data="[https://path/to/your/file.pdf](https://github.com/PritishWadhwa/CM-Project/blob/master/CM_Project.pdf)" type="application/pdf" width="700px" height="500px">
    <embed src="[https://path/to/your/file.pdf](https://github.com/PritishWadhwa/CM-Project/blob/master/CM_Project.pdf)">
        This browser does not support PDFs. Please download the PDF to view it: <a href="https://path/to/your/file.pdf">Download PDF</a>.
    </embed>
</object>

# Computing For Medicine Final Research Paper
## Abstract
Medical data often contains various forms of image data such as
x-ray scans, MRI scans, and CT scans. Computer-aided diagnosis
systems can benefit from making use of such image data. Our problem statement is to perform classification tasks on medical image
datasets, specifically Retinal OCT and Blood cell microscope images. In recent times, the application of computational or machine
intelligence in medical diagnosis is a new trend for large medical
data applications. Most of the diagnosis techniques in medical field
are systematized as intelligent data classification approaches.

## Conclusion
In this project, we explored the power of transfer learning on medical image datasets using the BloodMNIST and OCTMNIST datasets
from the MEDMNISTv2 database. Visualizing the data showed us
that the data was not clearly separable, possibly requiring complex
deep learning models to achieve good results. We applied several
models with different specifications including AlexNet, BEiT, Inception, VGG, ResNet and SqueezeNet by fine-tuning them on our
chosen datasets. We found the BEiT model (BERT Pre-Training
of Image Transformers) to perform best on both the datasets, giving accuracy of 0.9664 for BloodMNIST and 0.818 for OCTMNIST.
This beats the baseline performance obtained by Yang et al. on
OCTMNIST (ACC: 0.776) and matches that of BloodMNIST (ACC:
0.966). Thus, we can see that transfer learning can be a powerful
tool in the classification of medical image datasets.
