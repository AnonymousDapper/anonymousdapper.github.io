# Howdy Dub

This file is accessible at [test_page.md](https://github.com/AnonymousDapper/anonymousdapper.github.io/blob/master/pages/test_page.md)

This is a new page just for you.

Here's some bad C code for you.

```c
  fseek(input_file, 0, SEEK_END);
  long in_file_size = ftell(input_file);
  fseek(input_file, 0, SEEK_SET);

  char *in_file_content = malloc(sizeof(char) * in_file_size);

  if (in_file_content == NULL) {
    fprintf(stderr, "Could not allocate memory to read input file\n");
    exit(2);
  }

  fread(in_file_content, 1, in_file_size, input_file);

  fclose(input_file);
```
