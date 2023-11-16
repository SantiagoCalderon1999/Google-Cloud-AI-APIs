# Google Cloud AI APIs

This repository includes examples that were created as part of a workshop to teach King's College London students about the following Google Cloud APIs:

- [Google Cloud Natural Language API](https://cloud.google.com/natural-language/docs)
- [Google Cloud Text-to-Speech API](https://cloud.google.com/text-to-speech/docs)
- [Google Cloud Vision API](https://cloud.google.com/vision/docs)
- [Google Cloud Document AI OCR API](https://cloud.google.com/document-ai/docs)

## Getting Started

To get started, create a `.env` file in the root directory with the following variables:

```env
PROJECT_ID=<YOUR_PROJECT_ID>
LOCATION=<YOUR_LOCATION>
PROCESSOR_ID=<YOUR_PROCESSOR_ID>
```

Replace <YOUR_PROJECT_ID>, <YOUR_LOCATION>, and <YOUR_PROCESSOR_ID> with your actual GCP project ID, preferred location, and Document AI processor ID, as used in the OCR example.

The primary code for exploring and interacting with the Google Cloud AI APIs can be found in the `GoogleCloudAIAPIs.ipynb` notebook. This notebook is designed to guide you through practical examples and demonstrations.