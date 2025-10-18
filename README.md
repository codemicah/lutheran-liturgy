# Lutheran Liturgy

A structured data repository containing Lutheran orders of service and liturgical content.

## Overview

This project contains JSON-formatted liturgical content for various Lutheran church services, including worship orders, sacraments, and special ceremonies.

## Structure

- **`toc_index.json`** - Table of contents index listing all available sections
- **`sections/`** - Directory containing individual liturgical sections as JSON files

## Content Sections

The repository includes 15 liturgical sections:

- Order of Sunday Worship
- Order of Christmas Worship
- Collects for the Church Year
- Collects for Special Occasions
- Church Lectionary
- Sacrament of Holy Baptism
- Confirmation Service
- Holy Communion Service
- Order for Marriage Solemnization
- Order for Blessing of Marriage
- Consecration of a Burial Ground
- Church Foundation Laying Service
- Consecration of a New Church Building
- Consecration of Places not Consecrated for Worship
- Receiving into Fellowship non Lutheran Members

## Data Format

Each section file follows a standardized JSON schema containing:

- **Source metadata** - Document title, section number, and page references
- **Content** - Structured liturgical elements (rubrics, prayers, hymns, etc.)
- **Cross-references** - Links to related sections

## Usage

This data can be consumed by applications or tools that need access to Lutheran liturgical content in a structured, machine-readable format.
