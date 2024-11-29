## LLM-CDIP Benchmark

This repository contains the experimental data used for the following paper, which has been accepted for publication at [ICPR 2024](https://icpr2024.org):

Anna Scius-Bertrand, Michael Jungo, Lars Vögtlin, Jean-Marc Spat, and Andreas Fischer, **"Zero-Shot Prompting and Few-Shot Fine-Tuning: Revisiting Document Image Classification Using Large Language Models"**. *Proc. 27th Int. Conf. on Pattern Recognition (ICPR), 2024.*

The original images can be downloaded here:

* LLM-CDIP (263 MB, a subset of 2560 images from the [RVL-CDIP](https://adamharley.com/rvl-cdip/) dataset): [LLM-CDIP-images.tgz](https://www.dropbox.com/scl/fi/nf6sgqbhfgbqcx3y5ni9s/LLM-CDIP-images.tgz?rlkey=gwoz4tpsfpfwts9qytkielyrn&dl=1)

The repository contains:

* Ground truth: The class label is integrated in the filename, e.g.  "test\_0017\_11.png" designates a test image with the class 11. There are 16 classes in the RVL-CDIP database, for more details please visit: <https://adamharley.com/rvl-cdip/>.
* OCR: The Textract OCR results for the document images.
* Splits: The IDs used for training, validation, and testing.
* Prompts: The system prompts used for OCR-based and image-based document classification. *Please note that in the prompts the classes are between 1 and 16, while the ground truth is between 0 and 15.*

Please contact the authors if you have any questions.