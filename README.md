# specification13
This repository contains a revised [ICANN Specification13](https://newgtlds.icann.org/en/applicants/agb/base-agreement-contracting/specification-13-applications) list of gTLDs where only the Registry operator, its affiliates or trademark licensees are registrants of domain names in the TLD.

## Structure

> **Note:** The information contained in this repository may differ from current information due to update delays. Please consult the respective original publisher to obtain up-to-date information.

To access a specification13 generic top-level domain record, please use either on of the following schemes:

```
egisty/specification13/{granted}/data.json
egisty/specification13/{notApproved}/data.json
```

All generic top-level domain records have the following internal structure:

```json
{
    "gTLDs": [
        {
            "Generic top-level domain": "example",
            "Registry operator": "Example registry",
            "Organization": "Example organization",
            "Specification13": true
        }
    ],
    "updatedOn": "dd.mm.yyyy, hh:mm:ss",
    "version": 2,
    "source": "https://www.icann.org/resources/registries/gtlds/v2/gtlds.json"
}
```

## Report incorrect or missing data
If you have found wrong or missing generic top-level domain data in our domain records, you can get started very easily.

#### Please choose if you want to report incorrect or missing data.
- Report incorrect organization: [Click here](https://github.com/egisty/specification13/issues/new?assignees=&labels=&template=incorrect-organization-report.md&title=)

**Note:** The more information you provide, the better we can help you. Therefore, always pay attention to a large amount of detail.

## License

Please see the [license file](https://github.com/egisty/specification13/blob/master/LICENSE) for more information.
