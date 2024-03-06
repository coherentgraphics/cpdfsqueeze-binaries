# cpdfsqueeze

(NB: These days, you should just use `cpdf -squeeze in.pdf -o out.pdf` instead.) http://community.coherentpdf.com/

Copyright Coherent Graphics Ltd http://www.coherentpdf.com/

Cpdfsqueeze is a lossless compressor for PDF files, which works by rearranging and coalescing content within the file.

```
Syntax: cpdfsqueeze <input file> [-upw <password>] [-opw <password>] <output file>

  -upw  Provide user password
  -opw  Provide owner password
  -help  Display this list of options
  --help  Display this list of options
```

The source code can be found at <https://github.com/johnwhitington/cpdfsqueeze>.

```yaml
SPDX-License-Identifier: LGPL-2.1-or-later
```
