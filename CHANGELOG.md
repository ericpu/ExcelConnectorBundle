# CHANGELOG

## 1.4.0
 - Made compatible with PIM CE 1.3.x
 - Updated the init file from fixtures:
    - Removed default_value and usable_as_grid_column from attributes and family tab
    - Corrected the codes for wysywig_enabled and available_locales in the attributes and family tab
    - Removed the is_default column from the options tab
    - Removed garbage characters

## 1.3.2
 - Added compatibility with PIM CE 1.2.6

## 1.3.1
 - Fixed write count for homogeneous CSV writer

## 1.3.0
 - Added SpreadsheetReader, for compatibility with all formats supported by Akeneo Spreadsheet parser
 - Compatibility with version 1.2 of Akeneo PIM CE
 - Removed content type constraint on readers
 - pim_excel_connector.reader.xls_init service was renamed pim_excel_connector.reader.xls

## 1.2.x
- Added support for Akeneo Spreadsheet parser

## 1.1.x
- Added Office XML 2003 export
- Compatibility with version 1.1 of Akeneo PIM
