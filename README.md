# 🗂️ PHP Schema.org Category Mapping

A comprehensive PHP mapping of **Schema.org entity types** to **human-readable categories**.  
Ideal for **structured data**, **SEO automation**, **taxonomy systems**, and **semantic content classification** in CMS or API projects.

---

## 📖 Overview

This repository contains a well-structured **PHP associative array** (`$categories`) that maps global content and business categories (like *Health*, *Travel*, *Finance*, *Education*, etc.) to **Schema.org identifiers**.

It serves as a unified taxonomy for projects that require semantic categorization, automated schema generation, or consistent data tagging.

---

## 🧩 Structure

```php
$categories = [
    'Main Category' => [
        'SchemaType' => 'Readable Category Name',
        ...
    ]
];
