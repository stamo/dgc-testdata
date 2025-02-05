# Slovenia - Test files

---

This directory contains test files produced by the Slovenian development team. The DGCs were signed with a DSC from ACC NB. The software used to produce the QR-codes is based on https://github.com/DIGGSweden/dgc-java.

## Test files

### 1

[1.json](2DCode/raw/1.json) - One vaccination entry. 

All tests should be successful.

![1](png/1.png)

### 2

[2.json](2DCode/raw/2.json) - One NAA test entry. The sc-attribute is tagged (0 tag before date-time). Valid only for 72hrs.

All tests should be successful.

![2](png/2.png)

### 3

[3.json](2DCode/raw/3.json) - One NAA test entry. The sc-attribute is not tagged. Valid only for 72hrs.

All tests should be successful.

![3](png/3.png)

### 4

[4.json](2DCode/raw/4.json) - One RAT test entry.  Valid only for 72hrs.

All tests should be successful.

![4](png/4.png)

### 5

[5.json](2DCode/raw/5.json) - One recovery entry. 

All tests should be successful.

![5](png/5.png)

