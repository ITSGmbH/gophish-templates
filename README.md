# GoPhish Templates

A set of EMail and Landing-Page templates for GoPhish or any other phishing simulation system.

Under GoPhish  there is no possibility at the moment to upload images or any othe files.
Therefore all Templates are using base64 encoded inline images.
Use an online encoder such as [elmah.io Base64 Image Encoder](https://elmah.io/tools/base64-image-encoder/).

<strong>All these templates are thought to be used in a Phishing simulation only.</strong>

## Landing Pages

Landing Pages can be used to capture data but also to just track if someone clicked a malicious link.


| **Origin** | **Path** | **File** | **Description** |
|------------|----------|----------|-----------------|
| **Microsoft** | `/landing/microsoft/` | `login-single-page.html` | A simple Login-Page to capture login data. |
| **GE Healthcare** | `/landing/ge-healthcare/` | `register-change-login.html` | A simple Login-Page to a GE-Healthcare System. |



## Email Messages

| **Origin** | **Path** | **File** | **Description** |
|------------|----------|----------|-----------------|
| **Microsoft** | `/email/microsoft/` | `onenote-shared-notebook.html`, `onenote-shared-notebook.txt` | Someone shared a OneNote Notebook with the recipient. |
| **GE Healthcare** | `/email/ge-healthcare/` | `migrate-to-ge-care.html`, `migrate-to-ge-care.txt` | An Email to inform users about a migration to a new system from GE Healthcare. |

