# bootstrap for www

bootstrap-5.2.3.zip

Edit `scss/style.scss` for any changes.

### bb tasks
A bb task is implemented in the `bb.edn` file, to compile and copy over the result run:

```bash
bb run www
```

That task runs the two subtasks compile-www and copy-www.

### Manual

If you want to do it by hand, here we go:

Compile: `sass scss/www-style.scss css/www-style.css`

Copy to target project: `cp css/www-style* <path-to-www>/resources/public/assets/css/`

