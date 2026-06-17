---
title: "Book Highlighter Privacy Policy"
author: Valerio Galano
type: page
date: 2026-06-01T00:00:00+02:00
url: /book-highlighter/privacy-policy/
---

Last updated: June 1, 2026

## Overview

Book Highlighter is designed with privacy as a core principle. The App does not collect, store, or transmit any personal data to the developer. Everything you create stays on your device unless you explicitly choose to export or share it.

## 1. Data Stored Locally

The following data is stored exclusively on your device using Apple's CoreData framework:

* Books you add: title, author, year, publisher, ISBN, and cover URL.
* Highlights you capture or import through the share extension: text, page number, optional note, creation date, and export status.
* Export destinations you configure: name, type, vault/folder settings, and security-scoped folder bookmarks.
* App preferences: Google Books API key, if provided, last backup date, and other settings stored in UserDefaults.

None of this data is transmitted to the developer or to any server controlled by the developer.

## 2. Data Never Collected

The developer does not collect:

* Your name, email address, or any other identifying information.
* Usage analytics, crash reports, or telemetry of any kind.
* Location data.
* Contacts, calendar, or any other sensitive device data.
* The contents of your highlights or notes.

## 3. Camera and Photo Library

The App may request access to your camera to take a photo of a book page and can access images you select through the system photo picker, PhotosPicker. Images are processed entirely on-device by Apple's VisionKit framework, Live Text / ImageAnalyzer, and are held only in memory for the duration of the scanning session. Images are never written to disk, uploaded, or stored by the App.

## 4. Share Extension

If you choose Book Highlighter from another app's share sheet, iOS passes the selected text to Book Highlighter's share extension. The extension stores the text locally only after you choose a book and save it. The developer has no access to shared text.

## 5. Third-Party Network Requests

The App sends network requests only in the following cases, and only when you explicitly trigger a book search:

* Open Library (openlibrary.org): the search terms you type are sent to retrieve book metadata. No personal data is included in these requests.
* Google Books API (books.googleapis.com): used only when you supply a Google Books API key in Settings. The search terms you type and your API key are sent. Your API key is stored locally in UserDefaults and is not shared with any party other than Google.

These services may log your IP address and search queries according to their own privacy policies. The developer has no access to these logs.

The App does not include any advertising SDKs, analytics SDKs, or other third-party tracking libraries.

## 6. Data You Export

When you export highlights, you control the destination:

* Obsidian: data is sent to Obsidian on the same device via a URI scheme. It does not leave your device.
* Markdown file: data is written to a folder you choose on your device or in Files/iCloud Drive.
* Share sheet: you choose the recipient app, such as Notes, Mail, or Messages. The developer has no visibility into what you share or where.
* Backup JSON: you choose where to save or send the file via the standard iOS share sheet.

The developer has no access to any exported content.

## 7. iCloud

The App does not use iCloud or any Apple cloud service directly. If you save a backup or a Markdown file to iCloud Drive, that file is governed by Apple's iCloud terms and privacy policy.

## 8. Children's Privacy

The App is not directed to children under the age of 13 and does not knowingly collect personal information from children.

## 9. Changes to This Policy

This Privacy Policy may be updated from time to time. The updated policy will be available on this page. Continued use of the App after changes are posted constitutes acceptance of the revised policy.

## 10. Contact

If you have questions or concerns about this Privacy Policy, contact: v.galano@daredevel.com
