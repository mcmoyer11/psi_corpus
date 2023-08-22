# psi_corpus
swbd corpus study of psis


stting up environment variables in .bash_profile or .zshrc

# TDTLite
export TGREP2ABLE="/Users/momo/Dropbox/corpora/Treebank/tgrep2able/"
export TGREP2_CORPUS="$TGREP2ABLE/swbd.t2c.gz"
export TDTlite="/Users/momo/Dropbox/corpora/TDTLite"
export TDT_DATABASES="/Users/momo/Dropbox/TDTlite/databases"
export PATH="/Users/momo/Dropbox/TDTlite:$PATH"
(export PATH="$HOME/bin/linux_2_4/:$PATH")



tgrep2 -aftwc /Users/momo/Dropbox/corpora/Treebank/tgrep2able/swbd.t2c.gz "some"

test to see the whole sentence:
tgrep2 -aft "* << PP @> *" | more


to run: 
run -c swbd -e -o

tgrep2 -aftlw "/some/ .. /of/" | more

tgrep2 -aftlw "/some/ >> /all|every|no|most|least/" | more


