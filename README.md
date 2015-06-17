# Hyde-mod

This is a theme derivated from [Hyde](https://github.com/spf13/hyde).
Supports Hugo since version 0.12.

## Improvments

- Display only `post` section at home page
- Support of tag and category taxonomies
- List posts grouping by date
- Support table of contents
- Optimize template structure

## Hints

### Side menu items

Put these lines in `config.toml`:

    [[menu.main]]
    name = "Posts"
    weight = 1
    url = "/post/"

    [[menu.main]]
    name = "Categories"
    weight = 10
    url = "/categories/"

    [[menu.main]]
    name = "Tags"
    weight = 20
    url = "/tags/"

and put these lines in frontmatter of a single post:

    menu = "main"
    weight = 999

### Todo

- Merge CSS files

## Author

Modified by [Yan Gao](https://github.com/tagaoyan).

Original author [Steve Francia](https://github.com/spf13)

## License

MIT License.
