# Opening-tar-file-
import tarfile

my_tar = tarfile.open('D:\Mathew\code.tar.gz')

my_tar.extractall('D:\Mathew') # specify which folder to extract to

my_tar.close()
