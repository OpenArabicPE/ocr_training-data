---
title: "OpenArabicPE: OCR training data"
author: Till Grallert
date: 2019-05-22
tags:
    - OpenArabicPE
    - Arabic periodicals
---

This repository holds training data for OCR/HTR algorithms and some tools for converting TEI files into one `.txt` file per page required for this task.

The oXygen project [OpenArabicPE_OCR.xpr](OpenArabicPE_OCR.xpr) is configured with a single transformation scenario, which makes use of an XSLT stylesheet (`convert_tei-to-plain-text-pages.xsl`) from another GitHub repository ([convert_tei-to-markdown](https://github.com/OpenArabicPE/convert_tei-to-markdown)). In order for this conversion to work, both repositories (`ocr_training-data` and `convert_tei-to-markdown`) need to be children of the same folder and input TEI should validate against the [OpenArabicPE ODD](https://github.com/OpenArabicPE/OpenArabicPE_ODD).

