# PHP Schema.org Category Mapping

A comprehensive PHP mapping of **Schema.org entity types** to **human-readable categories**.  
Ideal for **structured data**, **SEO automation**, **taxonomy systems**, and **semantic content classification** in CMS or API projects.

---

## Overview

This repository contains a well-structured **PHP associative array** (`$categories`) that maps global content and business categories (like *Health*, *Travel*, *Finance*, *Education*, etc.) to **Schema.org identifiers**.

It serves as a unified taxonomy for projects that require semantic categorization, automated schema generation, or consistent data tagging.

---

## Structure

```php
$categories = [
    'Main Category' => [
        'SchemaType' => 'Readable Category Name',
        ...
    ]
];
```

## Example

```php
'Jobs & Education' => [
    'Preschool'   => 'Preschool',
    'ChildCare'   => 'Child Care',
    'ChildCare'   => 'Daycare Centers',
    'EducationalOrganization' => 'Early Childhood Education'
]
```
## License
This project is released under the MIT License.
You may freely use, modify, and distribute it with attribution.

## Author
 [**Volar Agency**](https://thevolar.com)
