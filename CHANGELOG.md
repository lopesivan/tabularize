0.2.9
-----
- Bug fix: exception on empty column

0.2.8
-----
- 1.8 compatibility

0.2.7
-----
- Customizable border
```ruby
  :hborder      => '─',
  :vborder      => '│',
  :iborder      => %w[┌ ┬ ┐ ├ ┼ ┤ └ ┴ ┘],
```
- `:border_color`
- Predefined border styles. `:border_style => :unicode`

0.2.5
-----
- Minor bug fixes

0.2.4
-----
- Improvment: Caching result of table generator
- Bug fix/feature: Handling rows of different number of cells

0.2.2
-----
- `screen_width` and `ellipsis` options to cut off trailing cells exceeding specified screen width

0.2.1
-----
- Multi-line support
- Vertical alignment

0.2.0
-----
- Tabularize::Table class for easy tabularization (doh!)
- Correctly handles ANSI codes

0.1.1
-----
- :unicode_display option added for CJK wide characters.

0.1.0
-----
- Initial release
