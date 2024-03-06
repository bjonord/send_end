# send_end
share files (up to 5GB) easily by using S3 and expiring urls.

Ensure that you have run `aws configure` with the correct credentials before use.

## Command examples

`> ./bin/send_end upload /path/to/file some-bucket-name store-here`

`> ./bin/send_end expiring_url /path/to/file some-bucket-name store-here`

## File usage examples

If you are pulling a CSV file:

```
result = CSV.read(contents, headers: true, col_sep: ";")
```