# faster_julia_str_search
Just looking for faster julia string search / searchindex options

Using `stsrt` is about 10 times faster depending on the input on my Arch Linux.

| Tables    | strstr (Arch Linux) | julia searchindex |
| :-------: |:--------------------| :-----------------|
| SIMPLE    | 0.0183              | 0.0836            |
| MEDIUM    | 0.0664              | 0.3389            |
| HUGE      | 0.1331              | 1.5678            |
| ADN       | 0.645               | 6.7267            |
