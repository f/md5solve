md5solve
========

MD5 decrypter. Generates content from it's MD5 sum. Work in progress.

## Example Usage

```bash
$ md5solve fb523bfc4bc9715fad11080d7a8eaf9b

Solving fb523bfc4bc9715fad11080d7a8eaf9b...
Solving %23...
Solving %43...
Solving %93...
Solved.

Result:

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam et malesuada erat. In tempus odio quis aliquam pharetra. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Mauris consectetur euismod mauris in auctor. Morbi nisi diam, tincidunt sodales pharetra quis, mollis posuere massa. Curabitur ac felis dapibus, tempus enim at, lobortis purus. Mauris egestas nibh at mauris pellentesque, vitae commodo tellus facilisis. Etiam a condimentum odio. Sed pretium ultricies urna a varius. Mauris porttitor mi neque, quis porta eros posuere et. Quisque mollis, eros quis ornare fringilla, massa leo rhoncus lorem, tempor laoreet risus purus sit amet leo. Nulla facilisi. Vivamus rutrum auctor enim quis iaculis. Nulla vehicula nibh erat, eget vestibulum turpis interdum nec. Vivamus dictum adipiscing arcu nec semper.

Reverse test with md5sum: fb523bfc4bc9715fad11080d7a8eaf9b is correct.
```

### Solving Salted MD5

```bash
$ md5solve --detect-salt a9ec3ce8dabe1e5b2f6e8e052e33e69c

Solving a9ec3ce8dabe1e5b2f6e8e052e33e69c...
Solving %43...
Solving %97...
Solved.
Detecting Salt...
Salt found.

Result:

Lorem ipsum dolor sit amet.

Salt: hello

```
