print (hello world) to print it
"\"(Ôo)'" to print the special chacarter of "(Ôo)'" 
 less, to display the content of another file 
cat /etc/passwd /etc/hosts : to Display the content of the two files
 tail -n 10 /etc/passwd : to print the last 10 lines of the file 
 head -n 10 /etc/passwd : to display the first 10 lines 
head -3 iacta | tail -1 : to display to third line of iacta
echo 'Best School' > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*:\) : to script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new 
 ls -la > ls_cwd_content : script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it 
 tail -n 1 < iacta >> iacta : script that duplicates the last line of the file iacta
find -name "*.js" -type f -delete ; script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
find . -type d ! -patch . -print | wc -l : script that counts the number of directories and sub-directories in the current directory.
 ls -t | head : script that displays the 10 newest files in the current directory.
sort | uniq -u : script that takes a list of words as input and prints only words that appear exactly once.
grep root /etc/passwd: Display lines containing the pattern “root” from the file /etc/passwd
grep -c bin/etc/passwd ; Display the number of lines that contain the pattern “bin” in the file /etc/passwd
grep -A 3 root/etc/passwd ; Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
