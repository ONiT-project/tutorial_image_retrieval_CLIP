# Tutorial: Image Retrieval with CLIP
In this notebook, you will learn how to load a CLIP model from Huggingface, how to prepare and load data into the model, how to embed the images and text prompt, and how to use cosine similarity to rank the images according to their similarity with the vectorized text prompt. You will also learn how to inspect the results, assess how well the model performs by calculating precision/recall metrics, and understand the limitations of the pretrained model.

Image and annotation data used in this tutorial can be downloaded from the following URL: https://1drv.ms/f/c/869f28ab041d44d9/ErTeV8fMekFCvtgexDOCxZoBCxCoxLJYUBOjam6rrwBSdw?e=IiKiVF
The image data and annotations used in this tutorial are provided by the FWF-funded project Ottoman Nature in Travelogues, 1501–1850: A Digital Analysis (ONiT). The images that we will be using were extracted from travelogues about the Ottoman Empire in English, French, German and Latin language that were printed between 1501 and 1850 and survived in the holdings of the Austrian National Library (ÖNB) in Vienna. The images have been scanned in the course of the Austrian Books Online project – a public private partnership between the ÖNB and Google Books.

Links:
https://onit.oeaw.ac.at/
https://www.onb.ac.at/
https://www.onb.ac.at/digitale-angebote/austrian-books-online

## ONiT Explorer
Inspect the full extracted image dataset from the ONiT project in the ONiT Explorer:
https://labs.onb.ac.at/en/tool/onit-explorer/
