BB to LRS via Kettle
====================

*Note that these files contain no database connection data and will require this to work*

*LRS connection data exists (because including it has no implications for security), but will be inaccurate since the job was run against a local LRS*

## How it works:

	kitchen /file JOBFILE COURSEFILE

### JOBFILE

Full path to marist_bb_to_lrs.kjb. Run by Kitchen.

### COURSEFILE

Full path to text file with course IDs, one per line.

## Author

[Cameron Finn Kelly](mailto:a.fell.ninny.mocker@gmail.com)

## License

```
Copyright 2015 Cameron Finn Kelly

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```