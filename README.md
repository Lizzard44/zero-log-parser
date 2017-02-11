# Zero log parser

This is a little decoder utility to parse Zero Motorcycle main bike board (MBB) logs.

## Usage
### Getting Logs
These may be extracted from the bike using the Zero mobile app: http://www.zeromotorcycles.com/app/help/ios/
  * Download the Zero mobile app.
  * Pair your motorcycle with it via bluetooth.
  * Once the pairing is working, select `Support` > `Email bike logs` and send the logs to yourself rather than / in addition to Zero Motorcycles support.

### Running
You'll need to install Python 2 somehow from https://www.python.org/downloads/

`$ python zero_log_parser.py <*.bin file> [-o output_file]`

## Development
Basic log documentation is at [log_structure.md](log_structure.md).

## Authors
Originally developed at https://github.com/KimBurgess/zero-log-parser
this ist a Fork of https://github.com/zero-motorcycle-community/zero-log-parser

* **Kim Burgess** - *Initial Work, Inactive* - [@KimBurgess](https://github.com/KimBurgess/)
* **Brian Rice** - *Maintainer* - [@BrianTRice](https://github.com/BrianTRice/)
* **Keith Thomas** - *Contributor* - [@keithxemi](https://github.com/keithxemi)

