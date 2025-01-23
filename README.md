# PHP CodeIgniter - Bootstrap 5 Paginator

## Description
A simple pagination solution for CodeIgniter projects that automatically generates pagination based on the number of items and the user’s required information.

## Features
- Supports a range-based pagination display (e.g., pages 1 to 5 at a time).
- Displays a configurable number of items per page.

## Installation Guide
1. Download the pagination script.
2. Refer to the usage example below and embed it in your CodeIgniter project.
3. It is recommended to structure the source URL as `'url?pageIndex='` for proper functionality.

## Usage
```php
echo view('your_paginator_view',
            [
                'posts' => items to show,
                'itemPerPage' => number of items to show,
                'paginationRange' => range of pagination,
                'totalCount' => total number of items,
                'src' => url when user clicks a page number (recommended format: 'url?pageIndex=')
            ]
        );
```

## Technologies Used
- PHP
- CodeIgniter
- Bootstrap 5

## Contributing
Contributions are welcome! If you have any improvements or fixes, feel free to submit a pull request.

## License
This project is licensed under the MIT License.

## Contact Information
For any inquiries or support, contact: cuu2252@gmail.com

