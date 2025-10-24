Importent Basic Linux Commands:

    whoami - It will display UserName Whologged in
    
    pwd - Present Working Directory

    ls - List - list files in present Direcory

    ls -l  - List long - List files with premissions 

    uname -a - is used in Unix-like operating systems to display system information. 

    --

        pwd (Always know where you are)

    cd (Practice moving to different places)

        cd /var/log

        cd /etc

        cd .. (go up one level)

        cd ~ or just cd (go home)

        cd - (go back to the previous directory)

    ls (See what's there)

        ls

        ls -l

        ls -la


1. Linux Directory Structure
  | Folder  | Purpose                          |
| ------- | -------------------------------- |
| `/home` | User home directories            |
| `/root` | Admin (superuser) home           |
| `/etc`  | Configuration files              |
| `/bin`  | Basic executable programs        |
| `/var`  | Variable data (logs, temp files) |
| `/tmp`  | Temporary files                  |
| `/usr`  | User programs/libraries          |
| `/opt`  | Optional apps                    |
| `/dev`  | Devices (e.g., disks, USB)       |
| `/proc` | System processes info            |


2. Basic Linux Commands

Run these in a Linux shell (or WSL/Ubuntu on Windows):

🔍 Navigation
pwd             # Print working directory
ls              # List files
ls -l           # Long listing
cd /home        # Change directory
cd ..           # Go back

📂 File Management
mkdir projects              # Make directory
touch file.txt              # Create file
cp file.txt copy.txt        # Copy file
mv copy.txt newname.txt     # Move/rename
rm newname.txt              # Delete file
rm -rf myfolder             # Delete folder recursively

📖 Viewing Files
cat filename.txt            # View full file
less filename.txt           # View page by page
head -n 5 filename.txt      # First 5 lines
tail -n 5 filename.txt      # Last 5 lines

👤 Permissions
chmod 755 script.sh         # Give read/write/execute
chown user:user file.txt    # Change file owner
sudo su                     # Become root user

⚙️ System Info
uname -a                    # System info
df -h                       # Disk usage
free -h                     # Memory usage
ps aux                      # Running processes
top                         # Live process monitor



💻 Mini-Challenge: Linux Practice

In your Linux shell (WSL/Ubuntu or any online terminal):

1️⃣ Create a folder:
mkdir cloud_practice
cd cloud_practice

2️⃣ Make three text files:
touch info.txt todo.txt notes.txt

3️⃣ Add content to todo.txt:
echo "Learn AWS" >> todo.txt
echo "Practice Docker" >> todo.txt

