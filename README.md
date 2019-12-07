# tampering_detection
Detecting tampered/fake images using Deep Learning

This is a rough implementation of the following forensics challenge.
http://web.archive.org/web/20171013200331/http://ifc.recod.ic.unicamp.br/fc.website/index.py?sec=5
(Data corpus can be downloaded from this link)

Phase1- Using ELA (Error Level Analysis) and standard CNN architecture using softmax to just detect whether an image is real or fake.

Phase2- Finding the exact tampered region of an image using transfer learning.

Results:
Phase1- F1 score=0.88
Phase2- Dice coefficient(custom metric) = 0.94
