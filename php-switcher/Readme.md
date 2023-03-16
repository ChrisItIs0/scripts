# php-switch script

The `php-switch` script allows you to quickly switch between two specified PHP versions on a Linux machine. The script assumes that you have multiple PHP versions installed and configured using the `update-alternatives` command.

## Usage

To use the script, simply run it on your terminal: ``./php-switch``


The script will automatically detect your current PHP version and ask you to select one of the two versions that you have configured. Once you make your selection, the script will switch to the corresponding PHP version.

## Configuration

Before using the script, you will need to configure it by setting the values of the `first_version` and `second_version` variables in the script file. These variables should be set to the versions of PHP that you want to switch between.

# configurePHPswitch script

The `configurePHPswitch` script is used to configure the `php-switch` script by setting the values of the `first_version` and `second_version` variables in the script file.

It will show you a list of all installed PHP versions on your system and prompt you to select the ones two switch between.

## Usage

To use the script, simply run it on your terminal: ``./configurePHPswitch``




