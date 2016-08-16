# KaggleAutoSubmission

## Author
- Debugging Sparrow / dbgsprw@gmail.com
- jangjunha / jangjunha113@gmail.com

## Requirements
- requests
- beautifulsoup4

# Use-case

## Init

import KAS<br>

email='your_email@email'<br>
password='your_password'<br>
competition_name='sf-crime'<br>

KAS.init(email, password, competition_name)

## Submission
KAS.submission("sampleSubmission.csv", True)
