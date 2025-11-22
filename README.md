# AWS IAM Authorization Practical

This project demonstrates how IAM authorization works by creating a user, assigning permissions through a group, and verifying allowed and denied actions via AWS CLI.

---

## ✔️ Steps Completed

1. Created IAM user `dev-user` (no console access)
2. Created IAM group `Developers`
3. Attached `AmazonS3ReadOnlyAccess` policy to the group
4. Added the user to the group
5. Created AWS CLI access keys
6. Tested permissions using AWS CLI

---

## ✔️ Results

### Allowed:
- Listing S3 buckets

### Denied:
- Uploading objects
- Deleting objects
- Modifying buckets

This proves **least privilege** in action.

---

## 📸 Screenshots


---

## 📚 Concepts Demonstrated

- IAM Users (authentication identity)
- IAM Groups (authorization container)
- AWS managed policies
- Least privilege principle
- Programmatic access using Access Keys
- Permission evaluation: Allow vs Deny

---

## 🧩 Why This Is Important

This practical demonstrates real-world IAM use:

- Secure programmatic access for developers
- Separation of authentication and authorization
- Reusable permission groups
- Preventing unauthorized modifications
- Understanding IAM policy behavior


