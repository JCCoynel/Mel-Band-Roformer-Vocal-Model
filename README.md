This is a fork of https://github.com/KimberleyJensen/Mel-Band-Roformer-Vocal-Model, with a few small improvements, mostly to deal with the [flac](https://xiph.org/flac/) format :
 - `--skip_already_processed` : skips files where an output file with similar name already exists in the store_dir
 - `--read_flac_files` : reads flac files as input (in addition to the default WAV)
 - `--output_as_flac` : generates flac files instead of wav
 - `--flac_compression_level` : defines the compression level for the flac files generated with `--output_as_flac` (between 0 and 12, where 12 is the slowest compression but smallest file size). Only used if --output_as_flac is set. Default is 12.

# How to use

Please refer to the original Github for full instructions : https://github.com/KimberleyJensen/Mel-Band-Roformer-Vocal-Model




