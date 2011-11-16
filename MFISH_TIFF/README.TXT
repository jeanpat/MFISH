Copyright (c) 2000 Advanced Digital Imaging Research
All rights reserved.

Permission is hereby granted, without written agreement and without license or royalty fees, to use, copy, modify, and distribute these images and their documentation for any purpose, provided that the above copyright notice and the following two paragraphs appear with all copies of these images.

IN NO EVENT SHALL PSI RESEARCH BE LIABLE TO ANY PARTY FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OF THESE IMAGES AND THEIR DOCUMENTATION, EVEN IF PSI RESEARCH HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

PSI RESEARCH SPECIFICALLY DISCLAIMS ANY WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE IMAGES PROVIDED HEREUNDER ARE ON AN "AS IS" BASIS, AND PSI RESEARCH HAS NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.

--------------------------------------------------------------------------------

PSI M-FISH IMAGE SET #1

The accompanying image set contains 200 M-FISH Images.  The images are divided into directories based on karyotype and slide.

File Nomenclature

The first character in the directory name represents the probe set (A, ASI; P, PSI/Cytocell; V, Vysis).  The second two characters are a number designating which slide the images in that directory came from.  The next two characters are underscores, and the final two characters are a code for the karyotype of that image (The ISCN designations for each code are listed below.)  Therefore a directory containing only the images with normal male karyotypes from slide 99 (using PSI probes) would be P99_XY.

The names of the images follow a similar naming scheme.  The first character represents the probe set.  The next two characters represent the slide number that the image came from.  The next two characters are the number of that image on the slide.  The final two characters represent the karyotype code.  Therefore, if image number 12 from slide 98 (using ASI probes) were a normal female metaphase, its file name would be A9812XX.

M-FISH Format

If the image set is stored in PSI's M-FISH format, all probes and image planes are stored in the same file.  If a file ends in an E, it means that that image has been enhanced manually.  Any file that ends in E, unless it is an extreme case (labeled karyotype code EX), also contains my diagnosis of the correct karyotype for that metaphase.

If the images set is stored in PSI's M-FISH format, one directory from each slide will also contain the M-FISH classifier used to come up with the karyotype.

Non-MFISH Format (PNG, TIFF, JPEG, PICT)

If the images are not stored in PSI's M-FISH format, each plane of the image is stored in a separate file.  The file name will have 8 characters, and the 8th and last character represents the probe that the image represents.

3   532
5   Cy 5.5
6   568
A   S. Aqua
C   Cy 5
D   DAPI
E   DEAC
F   Far Red
G   S. Green
I   FITC
O   S. Orange
R   S. Red
T   Texas Red
Y   S. Gold

In addition to a file for each plane in the M-FISH image, there is another file that contains my diagnosis of the correct karyotype for that metaphase.  This file has a 'K' for its 8th character.  This image is labeled such that all the pixels belonging to chromosome 1 are 1, all the pixels belonging to chromosome 2 are 2, etc.  All background pixels are 0, and all pixels that are part of a region of overlap are -1.  (This is a little meaningless in the case of a translocation.  In this case, the whole chromosome is labeled the same-- generally that class which makes up the most of the chromosome.)

In non-MFISH versions of this image set, each directory will also have a text file (of the same name as the directory) which contains the ISCN designation of the karyotype contained in that directory.

DISCLAIMER:

The karyotypes in this image set are my interpretation of the metaphases.  If you feel that I have made an error in my diagnosis of any image, please let me know at wade@psires.com

August 25, 2000
Advanced Digital Imaging Research
Wade Schwartzkopf
wade@psires.com

--------------------------------------------------------------------------------

Karyotype codes:


Code     ISCN karyotpe designation  Batch(es) in which this karyotpe is
                                       found (number of times karyotype
                                       is found in that batch)
XY       46, XY                     74 total images:
                                    01 (5), 02 (6), 04 (3), 05 (7), 06 (18),
                                    07 (2), 08 (6), 09, 11 (3), 13 (12), 17 (3),
                                    18 (4), 19 (3), 27
XX       46, XX                     8 total images:
                                    14 (3), 15, 16 (4)
EX       Extreme                    17 total images:
         (very difficult            23, 30 (3), 31 (2), 32 (3), 33(8)
         to karyotype
         properly)

Code     ISCN karyotpe designation  Batch(es) in which this karyotpe is
                                       found (number of times karyotype
                                       is found in that batch)
02       45, XY, -2                 2
08:      45, XY, -8                 18
09:      45, XY, -9                 7
12:      45, XY, -12                6
13:      45, XY, -13                3 (5)
15:      45, XY, -15                2
17:      45, XX, -17                16
18:      45, XY, -18                2, 7
20:      45, XY, -20                6
21:      45, XY, -21                11
25:      44, XY, -8, -13            3
26:      45, XY, -13, -18, 3
            +der(5)
27:      42, XY, -1,-7,-9,-22       6
28:      44, XY, -1, -12            8
29:      44, XY, -11, -22, 8
            (8,10,13 on edge
            of image)
30:      43, XY, -19, -19, -22,     8
            (16 on edge of image)

Code     ISCN karyotpe designation  Batch(es) in which this karyotpe is
                                       found (number of times karyotype
                                       is found in that batch)
31:      44, XX, -7, -22            10
32:      43, XX, -7, -21, -22       10
33:      43, XX, -7, -22, -22       10
34:      41, XX, -5, -6, -7,        10
            -9, -22
35:      42, XX, -7, -15, -19,      10
            -22
36:      43, XY, -14, -16, -22      11
37:      40, XY, -2, -7, -16,       12
            -16, -17, -18
38:      36, XY, -1, -3, -4,        12
            -9, -9, -14, -16,
            -16, -18-, 18
39:      32, XY, -2, -3, -8,        12
            -9, -9, -10, -13,
            -14, -14, -15, -18,
            -19, -22, -22

Code     ISCN karyotpe designation  Batch(es) in which this karyotpe is
                                       found (number of times karyotype
                                       is found in that batch)
40:      42, XY, -7, -11, -12,      13
            -15
41:      47, XX, +r(9)              15 (3)
42:      50, XY, +7, +8, +15,       19 (2)
            +20
43:      49, XY, +7, +15, +20       19
44:      44, X, -5, -14, +18,       20 (5), 22(5) 23
            Ins(11;8), t(5;16),
            t(7;16), t(9;14),
            t(14;15), t(5;17)
45:      45, X, -5, 14, +18,        20
            Ins(11;8),
            +Ins(14;9), t(5;16),
            t(7;16), t(9;14),
            t(14;15), t(5;17)
46:      46, XY, t(9;22)            21 (2)
47:      45, XY, -22, t(9;22)       21
48:      43, XY, -5, -12, -16,      21
            -17, +9, t(9;22)
49:      45, XY, -20, t(9;22)       21

Code     ISCN karyotpe designation  Batch(es) in which this karyotpe is
                                       found (number of times karyotype
                                       is found in that batch)
50:      43, X, -5, -6, -14,        23
            -21, +2, +18,
            Ins(11;8), t(5;16),
            t(7;16), t(9;14),
            t(14;15), t(5;17)
51:      42, X, -5, -14, -21,       23
            -21, +18, Ins(11;8),
            t(5;16), t(7;16),
            (9;14), t(14;15),
            t(5;17)
52:      46, XX, t(4;9)             24 (10)
53:      46, XY, t(1;7)             25 (2)
54:      46, XX, t(X;4)             26 (5)
55:      45, XX, -11, t(X;4)        26
56:      44, X, -6                  26
57:      45, XX, -21, t(X;4)        26
58:      44, XX, -14, -21,          26
            t(X;4)
59:      46, XY, t(3;13),           27 (3)
            t(8;3), t(16;8)

Code     ISCN karyotpe designation  Batch(es) in which this karyotpe is
                                       found (number of times karyotype
                                       is found in that batch)
60:      47, XY, +?13, t(3;13),     27
            t(8;3), t(16;8)
61:      45, XY, -5, t(3;13),       27
            t(8;3), t(16;8)
62:      45, XY, -18, -22,          28 (4), 29(13)
            t(7;8), t(9;10),
            t(11;20), t(15;18),
            +t(20;5)
63:      44, XY, -4, -18, -22,      29
            t(7;8), t(9;10),
            t(11;20), t(15;18),
            +t(20;5)
64:      46, XY, -18, t(7;8),       29
            t(9;10), t(11;20),
            t(15;18), +t(20;5)

August 25, 2000
Advanced Digital Imaging Research
Wade Schwartzkopf
wade@psires.com
