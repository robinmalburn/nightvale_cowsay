# Welcome To Night Vale Cowsay / Fortunes

This is a simple collection `cowsay` cow files and `fortune` quotes from [Welcome To Night Vale](http://commonplacebooks.com/)

## Files

### Cow Files

The following cow files are provided for use with cowsay / cowthink:

* `nightvale.cow`
    * ASCII cow interpretation of the series' eye logo
* `nightvale_small.cow`
    * Slightly smaller version of the above


### Fortune Files

The following files are provided for use with fortune:

* `nightvale_welcome`
    * Plain text file containing Cecil's various introductions
* `nightvale_welcome.dat`
    * Binary data file for the above plain text quotes
* `nightvale_proverbs`
    * Plain text file containing the "Today's Proverb" from each episode
* `nightvale_proverbs.dat`
    * Binary data file for the above plain text quotes
* `nightvale_combined`
    * Plain text file containing all of the introduction quotes and "Today's Proverb" quotes from each episode
* `nightvale_combined.dat`
    * Binary data file for the above plain text quotes
* `nightvale_welcome_trimmed`
* `nightvale_proverbs_trimmed`
* `nightvale_combined_trimmed`
* `nightvale_welcome_trimmed.dat`
* `nightvale_proverbs_trimmed.dat`
* `nightvale_combined_trimmed.dat`
   * Same as above, but with the "Today's Proverb:" header and "Welcome to Nightvale." removed


## Installation & Usage

These files can either be saved locally or for system wide use.

### System Wide Installayion

__Note__: The following paths are based on an Ubuntu based Linux distro - please ammend as required for your distro / OS of choice

Extract the cow files to: `/usr/share/cowsay/cows/`

Extract all the fortune files to: `/usr/share/games/fortunes/`

### System Wide Usage
`fortune [file] | cowsay -f [file]`

For example, to use the combined quotes with the standard sized Night Vale eye logo:

`fortune nightvale_combined | cowsay -f nightvale`

### Local Usage

`fortunate [path_to_file] | cowsay -f [path_to_file_with_extension]`

For example, to use the combined quotes with the standard sized Night Vale eye logo:

`fortune ./nightvale_combined | cowsay -f ./nightvale.cow`

## Credits

* __Welcome To Night Vale__ belongs to [Commonplace Books](http://commonplacebooks.com/)
* Quotes and proverbs extracted from the [plain text episode transcripts](https://github.com/Mara-K/nightvaledb)
