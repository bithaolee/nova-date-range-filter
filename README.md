## Date Range Filter for Laravel Nova

Nova filter that displays a Date Range Picker instead of a select.

### Install

Run this command in your nova project:
`composer require bithaolee/nova-date-range-filter`

### How to use

Just use DateRangeFilter class instead of Filter

```php
 public function filters(Request $request)
    {
        return [
            new \Marshmallow\Filters\DateRangeFilter('created_at', 'Created date'),
        ];
    }
```
