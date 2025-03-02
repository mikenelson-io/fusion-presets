<p align="center">
<img src="/images/purefusionrings112x91.jpg" widht="112" height="90">
<h1>Repository for Pure Fusion Presets</h1>
</p>

The purpose of this is to provide a centralized repository for Pure Fusion Preset templates. These files can be shared freely and should be modified to suit the specific workload requirements.

These files are contributed by Pure employees, partners, and customers.

## Guidelines for submitting Presets:

- All files submitted **should be in Presets JSON output format**. To download Presets from an array, follow the instructions in the FlashArray CLI guide for the following CLI command: 
'''
purepreset
'''

- Please remove any sensitive information from the file before submission.

- **Commenting is highly encouraged!!** Since comments are not natively allowed in the JSON language, please create a custom element in the object called `_comment` as shown in the example below
```
    {
        "_comment": "This is your comment. Be as descriptive as possible for others."
        <your json data pair code here>
    }
```

## To submit a Preset:

- Prepare your file. ***Remove any sensitive  information from the file***. Add comments for clarity and information.

- Create a Pull Request and add the file to it, providing any relevant comments if necessary.

- Pull Requests are automatically submitted for review and your request should be merged soon after submission.


## Disclaimer:

Absolutely no warranty or guarantees whatsoever are either stated or inferred with these files, and neither Pure Storage Incoroporated or any of it's employees shall be liable for any potential damage done by executing these Presets within your environment. Consult Pure Support or your Pure Account Team for evaluation and more information.

It is advised that Presets be tested before full implementation in to a Production environment. Put simply, if anything breaks in Production without testing first, it is no one else's fault except your own.

Please refer to the [Code of Conduct](https://github.com/PureStorage-OpenConnect/Code-of-Conduct) for more information.
