# Snapshot a Package Repository

Snapshot a Package Repository

## Usage

``` r
snapshot_package_repository(
  url,
  destdir = basename(url),
  type = c("source", "mac.binary", "win.binary"),
  r_version = NULL
)
```

## Arguments

- url:

  URL to the CRAN-like repository.

- destdir:

  Folder where to save the archives.

- type:

  Type of package archives.

- r_version:

  R version (character vector)

## Examples

``` r
if (FALSE) { # \dontrun{
snapshot_package_repository("https://jeroen.r-universe.dev", type = "source")
} # }
```
