textobj Codeblock
=================

This plugin provides a custom text object to target github-style fenced code
blocks like the following:

<pre>
  <code>
``` ruby
class MyClass
  def my_method
    puts "hello world"
  end
end
```
  </code>
</pre>

The plugin provides a text object to select the contents of the codeblock, as
well as the entire codeblock (including the opening and closing backtick lines).

Usage
-----

The plugin provides the following mappings by default:

| Mapping | Functionality                              |
| ------- | -------------                              |
|    `ic` | Contents of the codeblock                  |
|    `ac` | Entire codeblock, including backtick lines |

**Note** - The plugin requires the opening line of the codeblock to include a
filetype declaration.
