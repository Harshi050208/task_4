# 🔐 Task 4: Cloud Security Implementation

## Objective
To apply core security practices in cloud using IAM policies, secure storage configuration, and encryption techniques on AWS.

---

## ✔️ What Was Implemented

### 1. IAM Policy
- Created a **ReadOnlyS3Policy**
- Assigned to a user `secure-user`
- Restricted actions: only `s3:GetObject` and `s3:ListBucket`

### 2. Secure Storage
- Blocked all public access to bucket
- Enabled **SSE-S3 encryption**
- (Optional) Enabled bucket versioning

### 3. Data Encryption
- Configured **Server-Side Encryption** on the S3 bucket
- All uploaded files are encrypted by default

---

## 🔐 Security Best Practices Followed
- Minimum access principle via IAM policies
- Enforced data encryption at rest
- Disabled public access on all buckets
- IAM user with restricted capabilities

---

## 📸 Screenshots
- IAM Policy screen
- Block all bucket permision
- Bucket encryption settings
