# Cygwin
Unix like systems for windows CLI list.

### **Cygwin CLI Commands**

#### **1. File and Directory Management**

- **List files and directories:**
  ```bash
  ls
  ```

- **Change directory:**
  ```bash
  cd directoryname
  ```

- **Create a new directory:**
  ```bash
  mkdir directoryname
  ```

- **Remove a directory:**
  ```bash
  rmdir directoryname
  ```

- **Remove a file:**
  ```bash
  rm filename
  ```

- **Copy files:**
  ```bash
  cp sourcefile destinationfile
  ```

- **Move files:**
  ```bash
  mv sourcefile destinationfile
  ```

- **Find files:**
  ```bash
  find /path/to/search -name filename
  ```

#### **2. File Viewing and Editing**

- **Display file contents:**
  ```bash
  cat filename
  ```

- **View file content page by page:**
  ```bash
  less filename
  ```

- **Search within files:**
  ```bash
  grep "searchtext" filename
  ```

- **Edit files:**
  ```bash
  nano filename
  ```

  or

  ```bash
  vim filename
  ```

#### **3. System Information and Management**

- **Display current working directory:**
  ```bash
  pwd
  ```

- **Show system information:**
  ```bash
  uname -a
  ```

- **Display disk usage:**
  ```bash
  df -h
  ```

- **Display memory usage:**
  ```bash
  free -m
  ```

- **Show process list:**
  ```bash
  ps aux
  ```

- **Kill a process by PID:**
  ```bash
  kill pidnumber
  ```

- **Show active network connections:**
  ```bash
  netstat -an
  ```

#### **4. Package Management**

- **Update package lists:**
  ```bash
  apt-cyg update
  ```

- **Install a package:**
  ```bash
  apt-cyg install packagename
  ```

- **Remove a package:**
  ```bash
  apt-cyg remove packagename
  ```

- **Search for a package:**
  ```bash
  apt-cyg search packagename
  ```

#### **5. Networking**

- **Ping a host:**
  ```bash
  ping hostname
  ```

- **Trace route to a host:**
  ```bash
  traceroute hostname
  ```

- **Download a file from the web:**
  ```bash
  wget http://example.com/file
  ```

#### **6. File Compression**

- **Create a tarball archive:**
  ```bash
  tar -cvf archive.tar filename
  ```

- **Extract a tarball archive:**
  ```bash
  tar -xvf archive.tar
  ```

- **Create a gzipped tarball archive:**
  ```bash
  tar -czvf archive.tar.gz filename
  ```

- **Extract a gzipped tarball archive:**
  ```bash
  tar -xzvf archive.tar.gz
  ```

#### **7. Shell Scripting**

- **Execute a script:**
  ```bash
  ./scriptname.sh
  ```

- **Make a script executable:**
  ```bash
  chmod +x scriptname.sh
  ```

#### **8. Permissions**

- **Change file permissions:**
  ```bash
  chmod permissions filename
  ```

- **Change file owner:**
  ```bash
  chown owner:group filename
  ```

### **Summary**

This list covers essential Cygwin CLI commands for file and directory management, system information, package management, networking, file compression, and basic shell scripting.
