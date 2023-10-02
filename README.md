# README

**Medscribe: Open Source Health Data Analysis Library**

Medscribe is an open source health data analysis library that provides a comprehensive set of tools for extracting insights from health data. Medscribe is designed to be easy to use and accessible to a wide range of users, from data scientists to clinicians. Medscribe would supports a variety of HIPAA-compliant health data formats, including FHIR, HL7v2, and DICOM.

**But we would start with FHIR first**

Medscribe would include modules for converting unstructured text data (such as clinical notes and patient records) into structured data that can be easily analyzed.

## **Modules**

- **Synthentic data generation:** The synthetic data generation module in Medscribe can be used to generate synthetic health data that is statistically similar to real health data. This can be useful for a variety of purposes, such as:

  - Training machine learning models without the need for real health data, which can be privacy-sensitive and difficult to obtain.
  - Testing and evaluating new health data analysis algorithms and methods.
  - Simulating clinical trials and other medical research scenarios.

  The synthetic data generation module in Medscribe can be implemented using a variety of techniques, such as:

  - **Generative adversarial networks (GANs):** GANs are a type of machine learning model that can be used to generate realistic synthetic data.
  - **Variational autoencoders (VAEs):** VAEs are another type of machine learning model that can be used to generate synthetic data.
  - **Statistical modeling:** Statistical modeling can be used to generate synthetic data by sampling from probability distributions that are estimated from real health data **(check out SMOTE)**.

- **Comprehend:** The comprehend module can be used to extract structured data from the transcribed text. This can be used to create documents, such as clinical reports and patient summaries, or to populate databases.

- **Speech-to-text:** The speech-to-text module can be used to transcribe audio recordings of medical consultations and other medical procedures. The comprehend module can then be used to extract structured data from the transcribed text.

```text
    |speech-to-text| -> |comprehend| -> structured text(for database storage)
```

Medscribe would be written in Python and C++. The Python code is used for the high-level functionality, while the C++ code is used for some performance optimizations.

## **Resources**

- **GitHub repository:** https://github.com/arjun-dureja/Medscribe
- **AWS Health Scribe features:** https://aws.amazon.com/healthscribe/features/
- **AWS Comprehend Medical:** https://aws.amazon.com/comprehend/medical/

## How to contribute

If you would like to contribute to Medscribe, please fork the GitHub repository and create a pull request. We welcome all contributions, including bug fixes, new features, and documentation improvements.

## Q/As

- Should it be called modules or components?
