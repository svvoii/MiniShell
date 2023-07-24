# Minishell

Welcome to Minishell, a simplified shell implementation developed as part of the curriculum at 42 School. This is the last version that was submitted and evaluated for 100% completion.

In this version, there are some tiny errors that need to be addressed:

- The command ```./ls``` executes the 'ls' command while bash returns an error. This issue needs to be fixed.

- The command ```echo "$? "``` is not expanded if it is inside double quotes, which is handled correctly in bash. This behavior needs to be properly implemented.

- The command ```echo something > file_with_no_access_rights``` in bash throws an error of permission denied. This error is not handled properly in our implementation and needs to be addressed.

Other than these specific cases, all functionalities of the Minishell project work well.

## Contributers

- @svvoii
- @SharkidFincher
