List software after install new OS

For Fedora - fedora.txt

For autoinstall, create .sh file, code conains (sample):

for WORD in `cat fedora.txt`
do
   echo $WORD
   command $WORD > $WORD
done
