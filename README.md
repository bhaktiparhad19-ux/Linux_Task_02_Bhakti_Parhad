# Linux Task 02 - Users, Groups & File Permissions

## Student Information

**Name:** Bhakti Mahadev Parhad
**Internship:** White Band Associates Summer Internship Cyber Security
**Task:** Linux Task 02 - Users, Groups & File Permissions

---

# Objective

The purpose of this task is to understand Linux user management, groups, file ownership, and file permissions.

These concepts form the foundation of Linux security and system administration.

---


# Part A - Understanding Users

Commands Executed:

```bash
whoami
id
cat /etc/passwd
```

Tasks Completed:

* Identified current username.
* Observed User ID (UID).
* Observed Group ID (GID).
* Reviewed user account information stored in /etc/passwd.

Screenshots:

* whoami.png
* id.png
* cat_etc_passwd.png

---

# Part B - Create Users & Groups

Groups Created:

* interns
* cyberteam

Users Created:

* student1
* student2
* student3

Tasks Completed:

* Created groups.
* Created users.
* Assigned users to groups.
* Verified group membership using groups and id commands.

Screenshots:

* groups_users.png
* group_user_verification.png

---

# Part C - File Ownership

Project Directory Created:

```text
CyberSecurity_Project
```

Files Created:

```text
report.txt
notes.txt
credentials.txt
```

Tasks Completed:

* Verified file ownership using ls -l.
* Changed ownership of a file using chown.
* Verified ownership changes.

Screenshot:

* file_ownership_file_permission.png

---

# Part D - File Permissions

File Created:

```text
security_policy.txt
```

Permission Changes Performed:

| Permission Type | Permission |
| --------------- | ---------- |
| Read Only       | r--r--r--  |
| Read & Write    | rw-rw-r--  |
| Full Access     | rwxrwxrwx  |

Commands Used:

```bash
chmod 444 security_policy.txt
chmod 664 security_policy.txt
chmod 777 security_policy.txt
```

Tasks Completed:

* Checked existing permissions.
* Modified permissions using chmod.
* Verified permission changes using ls -l.

Screenshot:

* file_ownership_file_permission.png

---

# Part E - Permission Analysis

Permissions Studied:

* 755
* 644
* 777
* 600
* 700

For each permission the following were analyzed:

* Owner Rights
* Group Rights
* Other User Rights
* Real-world Use Cases

Detailed analysis is available in:

```text
Permission_Analysis.txt
```

---

# Part F - Security Challenge

Recommended permissions were assigned for:

* password_backup.txt
* public_notice.txt
* system_log.txt
* personal_notes.txt

Each permission was selected based on security requirements and the Principle of Least Privilege.

Detailed answers are available in:

```text
Security_Challenge.txt
```

---

# Part G - Linux Security Research

Research Topics Covered:

* Importance of File Permissions
* Risks of 777 Permissions
* Principle of Least Privilege (PoLP)
* Reasons Organizations Restrict User Access

Detailed answers are available in:

```text
Research_Answers.txt
```

---

# Concepts Learned

During this task I learned:

* Linux Users and Groups
* User Management
* Group Management
* File Ownership
* File Permissions
* chmod Command
* chown Command
* Numeric Permissions
* Symbolic Permissions
* Principle of Least Privilege
* Linux Security Basics

---

# Conclusion

This task provided hands-on experience with Linux user management, group management, file ownership, and permissions.

Understanding these concepts is essential for securing Linux systems and forms a strong foundation for future cybersecurity and system administration tasks.

---
