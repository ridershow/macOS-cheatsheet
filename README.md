# macOS-cheatsheet
CLI commands cheat sheet for mac OS users

View All Users & Accounts on a Mac ==> dscl . list /Users

Show User Accounts Only ==> dscl . list /Users | grep -v '_'

Show All User Accounts, User Directories, & User GECOS Info on a Mac ==> dscacheutil -q user

---------------------------------------------------------------------------

a             | Description
------------- | -------------
afconvert     | Audio File Convert
afinfo        | Audio File Info
afplay        | Audio File Play
airport       | Manage Apple AirPort
alias         | Create an alias
alloc         | List used and free memory
apropos       | Search the whatis database for strings
asr           | Apple Software Restore
atsutil       | Font registration system utility
awk           | Find and Replace text within file(s)
  
b             | Description
------------- | -------------
basename      | Convert a full pathname to just a filename
bash          | Bourne-Again SHell
bg            | Send to background
bind          | Set or display readline key and function bindings
bless         | Set volume bootability and startup disk options
break         | Exit from a For, While, Until or Select loop
builtin       | Execute a shell builtin
bzip2         | Compress or decompress files

c             | Description
------------- | -------------
caffeinate    | Prevent the system from sleeping
cal           | Display a calendar
calendar      | Reminder Service
caller        | Return the context of a subroutine call •
cancel        | Cancel print jobs
case          | Conditionally perform a command •
cat           | Concatenate and print (display) the content of files
cd            | Change Directory •
chflags       | Change a file or folder's flags
chgrp         | Change group ownership
chmod         | Change access permissions
chown         | Change file owner and group
chroot        | Run a command with a different root directory
cksum         | Print CRC checksum and byte counts
clear         | Clear terminal screen
cmp           | Compare two files
comm          | Compare two sorted files line by line
command       | Run a command (not a function) •
complete      | Edit a command completion [word/pattern/list] •
continue      | Resume the next iteration of a loop •
cp            | Copy one or more files to another location
cron          | Daemon to execute scheduled commands
crontab       | Schedule a command to run at a later date/time
csplit        | Split a file into context-determined pieces
csrutil       | Configure System Integrity Protection (SIP)
cupsfilter    | Convert a file to another format using cups filters
curl          | Transfer data  from or to a server
cut           | Divide a file into several parts
  
d
  date      Display or change the date & time
  dc        Desk Calculator
  dd        Convert and copy a file, clone disks
  declare   Declare variable & set attributes •
  defaults  Set preferences, show hidden files
  df        Display free disk space
  diff      Display the differences between two files
  diff3     Show differences among three files
  dig       DNS lookup
  dirname   Convert a full pathname to just a path
  dirs      Display list of remembered directories •
  diskutil  Disk utilities - Format, Verify, Repair
  disown    Unbind a job from the current login session •
  ditto     Copy files and folders
  dot_clean Remove dot-underscore files
  drutil    Interact with CD/DVD burners
  dscacheutil  Query or flush the Directory Service/DNS cache
  dseditgroup  Edit, create, manipulate, or delete groups
  dsenableroot Enable root access
  dsmemberutil View user and groups rights
  dscl      Directory Service command line utility
  du        Estimate file space usage
  
e
  echo      Display text on screen •
  ed        A line-oriented text editor (edlin)
  enable    Enable and disable builtin shell commands •
  env       List or Set environment variables
  eval      Evaluate several commands/arguments •
  exec      Execute a command •
  exit      Exit the shell •
  execsnoop Snoop new process execution
  expand    Convert tabs to spaces
  expect    Programmed dialogue with interactive programs
            Also see AppleScript
  export    Set an environment variable •
  expr      Evaluate expressions
  
f
  false     Do nothing, unsuccessfully
  fc        Fix command (history)
  fdisk     Partition table manipulator for Darwin UFS/HFS/DOS
  fdesetup  FileVault configuration, list FileVault users
  fg        Send job to foreground •
  file      Determine file type
  find      Search for files that meet a desired criteria
  fmt       Reformat paragraph text
  fold      Wrap text to fit a specified width
  for       Loop command •
  fsck      Filesystem consistency check and repair
  fs_usage  Filesystem usage (process/pathname)
  ftp       Internet file transfer program
  function  Define Function Macros
  fuser     List processes that have one or more files open
  
g
  GetFileInfo Get attributes of HFS+ files
  getopt    Parse positional parameters
  getopts   Parse positional parameters •
  goto      Jump to label and continue execution
  grep      Search file(s) for lines that match a given pattern
  groups    Print group names a user is in
  gzip      Compress or decompress files
  
h
  halt      Stop and restart the operating system
  hash      Refresh the cached/remembered location of commands •
  head      Display the first lines of a file
  hdiutil   Manipulate iso disk images
  history   Command History •
  hostname  Print or set system name
  
i
  iconv     Convert the character set of a file
  id        Print user and group names/id's
  if        Conditionally perform a command •
  ifconfig  Configure network interface parameters
  iostat    Report CPU and i/o statistics
  ipconfig  View and control IP configuration state
  info      Help info
  install   Copy files and set attributes
  iosnoop   Snoop I/O events as they occur
  
j
  jobs      List active jobs •
  join      Join lines on a common field
  
k
  kextfind  List kernel extensions
  kextstat  Display status of loaded kernel extensions (kexts)
  kextunload Terminate driver instances and unload kernel extensions.
  kickstart Configure Apple Remote Desktop
  kill      Kill a process by specifying its PID
  killall   Kill processes by name
  
l
  l         List files in long format (ls -l)
  last      Indicate last logins of users and ttys
  launchctl Load or unload daemons/agents
  ll        List files in long format, showing invisible files (ls -la)
  less      Display output one screen at a time
  let       Evaluate expression •
  lipo      Convert a universal binary
  ln        Make links between files (hard links, symbolic links)
  local     Set a local (function) variable •
  locate    Find files
  logname   Print current login name
  login     log into the computer
  logout    Exit a login shell (bye) •
  look      Display lines beginning with a given string
  lp        Print files
  lpr       Print files
  lprm      Remove jobs from the print queue
  lpstat    Printer status information
  ls        List information about file(s)
  lsregister Reset the Launch Services database
  lsbom     List a bill of materials file
  lsof      List open files
  
m
  man       Help manual
  mdfind    Spotlight search
  mdutil    Manage Spotlight metadata store
  mkdir     Create new folder(s)
  mkfifo    Make FIFOs (named pipes)
  mkfile    Make a file
  mktemp    Make a temporary file
  more      Display output one screen at a time
  mount     Mount a file system
  mv        Move or rename files or directories
  
n
  nano      Simple text editor
  nc/netcat Read and write data across networks
  net       Manage network resources
  netstat   Show network status
  networksetup Network and System Preferences
  nice      Set the priority of a command
  nohup     Run a command immune to hangups
  ntfs.util NTFS file system utility
  nvram     Manipulate  firmware variables
  
o
  onintr    Control the action of a shell interrupt
  open      Open a file/folder/URL/Application
  opensnoop Snoop file opens as they occur
  openssl   OpenSSL command line
  osacompile Compile Applescript
  osascript Execute AppleScript
  
p
  passwd    Modify a user password
  paste     Merge lines of files
  pbcopy    Copy data to the clipboard
  pbpaste   Paste data from the Clipboard
  pgrep     List processes by a full or partial name
  ping      Test a network connection
  pkill     Kill processes by a full or partial name
  pkgbuild  Build a macOS Installer component package
  pkgutil   Query and manipulate installed packages
  plutil    Property list utility
  pmset     Power Management settings
  popd      Restore the previous value of the current directory •
  pr        Convert text files for printing
  printenv  List environment variables
  printf    Format and print data •
  ps        Process status
  pushd     Save and then change the current directory
  pwd       Print Working Directory •
  
q
  quota     Display disk usage and limits
  
r
  rcp       Copy files between machines
  read      Read one line from standard input •
  readonly  Mark a variable or function as read-only •
  reboot    Stop and restart the system
  ReportCrash Enable/Disable crash reporting
  return    Exit a function •
  rev       Reverse lines of a file
  rm        Remove files
  rmdir     Remove folder(s)
  rpm       Remote Package Manager
  rsync     Remote file copy - Sync file tree
  
s
  say       Convert text to audible speech
  screen    Multiplex terminal, run remote shells via ssh
  screencapture Capture screen image to file or disk
  scselect  Switch between network locations
  scutil    Manage system configuration parameters
  sdiff     Merge two files interactively
  security  Administer Keychains, keys, certificates and the Security framework
  sed       Stream Editor
  select    Generate a list of items •
  serverinfo Server information
  set       Set a shell variable = value •
  setfile   Set attributes of HFS+ files
  sharing   Create share points for afp, ftp and smb services
  shasum    Print or Check SHA Checksums
  shift     Shift positional parameters •
  shopt     Set shell options •
  shutdown  Shutdown or restart macOS
  sips      Scriptable image processing system
  sleep     Delay for a specified time
  softwareupdate System software update tool
  sort      Sort text files
  source    Execute commands from a file •
  spctl     Security assessment policy/Gatekeeper
  split     Split a file into fixed-size pieces
  sqlite3   SQL database (download history)
  srm       Securely remove files or directories
  stat      Display the status of a file
  stop      Stop a job or process
  su        Substitute user identity
  sudo      Execute a command as another user
  sum       Print a checksum for a file
  suspend   Suspend execution of this shell •
  sw_vers   Print macOS operating system version
  sysctl    Get or set kernel state
  system_profiler  Report system configuration
  systemsetup Computer and display system settings
  
t
  tail      Output the last part of files
  tar       Tape ARchiver
  tccutil   Manage the privacy database
  tcpdump   Dump traffic on a network
  tee       Redirect output to multiple files
  test      Condition evaluation •
  textutil  Manipulate text files in various formats (Doc,html,rtf)
  time      Measure Program Resource Use
  times     Print shell & shell process times •
  tmutil    Time Machine utility
  top       Display process information
  touch     Change file timestamps
  tput      Set terminal-dependent capabilities, color, position
  tr        Translate, squeeze, and/or delete characters
  trap      Execute a command when the shell receives a signal •
  traceroute Trace Route to Host
  trimforce Enable TRIM commands on third-party drives
  true      Do nothing, successfully
  tty       Print filename of terminal on stdin
  type      Describe a command •
  
u
  ufs.util  Mount/unmount UFS file system
  ulimit    limit the use of system-wide resources •
  umask     Users file creation mask
  umount    Unmount a device
  unalias   Remove an alias •
  uname     Print system information
  unexpand  Convert spaces to tabs
  uniq      Uniquify files
  units     Convert units from one scale to another
  unset     Remove variable or function names •
  until     Loop command •
  uptime    Show how long system has been running
  users     Print login names of users currently logged in
  until     Execute commands (until error)
  uuencode  Encode a binary file 
  uudecode  Decode a file created by uuencode
  uuidgen   Generate a Unique ID (UUID/GUID)
  uucp      Unix to Unix copy
  
v
  vi        Text Editor
  
w
  w         Show who is logged on and what they are doing
  wait      Wait for a process to complete •
  wall      Write a message to users
  wc        Print byte, word, and line counts
  whatis    Search the whatis database for complete words
  whereis   Locate a program
  which     Locate a program file in the user's path
  while     Loop command •
  who       Print all usernames currently logged on
  whoami    Print the current user id and name (`id -un')
  write     Send a message to another user
  
x
  xargs     Execute utility - passing arguments
  xattr     Display and manipulate extended attributes
  xcode-select --install  Install the command line developer tools
 youtube-dl Download video
  yes       Print a string until interrupted
  zip       Package and compress (archive) files.
  !!        Run the last command again
