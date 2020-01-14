mkdir cli_tmp
touch je_suis_dans_tmp.text ~/cli_tmp
cd cli_tmp
touch in_cli_tmp.text
rm je_suis_dans_tmp
rm -r cli_tmp
mkdir grand_parent parent grand_frere grande_soeur ami connaissances
cd grand_frere
touch bachir.docx
mv bachir.docx ~/ami
cp -rf ami ~/parent 
rm bob.text
pwd
cd /
rm -rf cli_tmp