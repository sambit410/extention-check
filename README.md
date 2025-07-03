# extention-check

# 🔒 Browser Extension Security Audit – README

## 📌 Overview
This audit is part of a cybersecurity learning initiative aimed at strengthening browser hygiene and privacy awareness. The goal is to identify, evaluate, and remove unnecessary or potentially risky browser extensions from Microsoft Edge.

## ⚙️ Tools Used
- **Microsoft Edge
- **Extension Manager:** `edge://extensions/`
- Manual inspection of extension details and permissions

## 🔍 Audit Process

1. Accessed Microsoft Edge's extension manager via `edge://extensions/`
2. Reviewed all installed extensions:
   - Extension name
   - Permissions granted
   - Usage frequency
   - Developer source and version
3. Identified extensions that:
   - Were no longer in use
   - Requested excessive or unjustified access
   - Did not align with current privacy practices
4. Removed extensions after review
5. Restarted browser and verified performance

## ❌ Extensions Removed

| Extension                          | Reason for Removal                                          |
|-----------------------------------|--------------------------------------------------------------|
| Rakuten – Get Cash Back           | Unnecessary; requested full browsing access and was inactive |
| Shopping Helper / PDF Converter Pro | Suspicious behavior, excessive permissions, poor credibility |

## ✅ Outcomes
- Browser performance slightly improved
- Reduced third-party tracking exposure
- Leaner, safer browsing experience
- Best practices reinforced for future extension use
