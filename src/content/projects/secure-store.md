---
title: "Secure-Store"
description: "A privacy-first, end-to-end encrypted password manager built with a zero-trust architecture and modern cryptography."
featured: true
tags: ["security", "password-manager", "go", "web-extension", "encryption"]
techStack: ["Go", "Vite", "React", "Libsodium", "Browser Extension"]
repoUrl: "https://github.com/anandukch/secure-store"
---

Secure-Store is a privacy-focused password manager built with a strict zero-trust model. All encryption happens on the client using modern cryptographic primitives, ensuring your data never leaves your device in readable form. The backend, written in Go, simply stores encrypted blobs — it can’t access or decode any of your credentials.

The extension is powered by Vite and React, offering a fast and minimal interface for managing sensitive information right inside your browser. Using libsodium for encryption and Argon2 for strong key derivation, Secure-Store is designed around one principle: only you should ever be able to decrypt your data.

Secure-Store combines clean engineering, modern security practices, and a simple workflow to create a password manager that puts privacy first.
