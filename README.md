# terraform
Terraform files for managing organization infrastructure


## Adding Users To Teams

In order to add a new user to an existing team, follow these steps:

1. Open the [variables.tf](https://github.com/Jakski-IT/terraform/blob/main/variables.tf) file.
2. Find the team you want to edit in the `variable "teams"` section.
3. Add the GitHub user name to the `members` array of the respective team.


## Adding New Repositories

TODO: Double check if this is correct or if repositories need to go under the `repositories` section.

In order to add new repositories, so that the respective permissions / protections are applied automatically, follow these steps:

1. Open the [variables.tf](https://github.com/Jakski-IT/terraform/blob/main/variables.tf) file.
2. Find the team to which you want to add the repository in the `variable "teams"` section.
3. Add the repository name to the `repositories` object of the respective team.
