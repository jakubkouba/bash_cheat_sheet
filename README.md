# Bash commands cheat sheet

## Searching files

### Sort files in folder by the number of lines DESC
`find {directory} -type f -name '*.rb' | xargs wc -l  | sort -nr`