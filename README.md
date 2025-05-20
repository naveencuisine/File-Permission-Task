# File Permission Task

## Objective:
Create a file `/home/demo.txt` and assign permissions:
- Owner: read, write, execute
- Group: read, write
- Others: read

## Steps Followed:
```bash
touch /home/demo.txt
chmod 764 /home/demo.txt
ls -l /home/demo.txt
