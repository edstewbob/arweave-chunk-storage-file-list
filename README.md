# arweave-chunk-storage-file-list  
This script lists all the chunk_storage files, their sizes, and locations and creates file file_list.csv  
for input into a spreadsheet for further analysis. The script assumes that all of the storage_modules  
are mounted under the arweave subdirectory and searches for all directories named chunk_storage.  
If this is not the case for you the script will need to be modified.  The format of the command is:  
./create_file_list.sh /mnt/md0/arweave. Rocksdb data is not listed.  The argument may be different   
for your configuration.  Sample output looks like this, one line per file:  
"/mnt/md0/arweave/lv2/chunk_storage","9487515648000","27-Mar-2023 20:52:49.3449289240","2097176000"   
"/mnt/md0/arweave/lv2/chunk_storage","8703180800000","20-Mar-2023 14:59:33.9523942130","916465912"  
"/mnt/md0/arweave/lv2/chunk_storage","9682550784000","31-Mar-2023 02:45:10.6456328450","2097176000"  
"/mnt/md0/arweave/lv2/chunk_storage","10278141952000","16-May-2023 02:41:31.2697854530","2097176000"  
