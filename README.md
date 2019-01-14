# EG4S20BG256
Exploration du FPGA Anlogic EG4S20BG256

## description

Le EG4S20BG256 est un FPGA de 20K LUT4/5(dit hybride waw kezako) capable de supporter un softcore risc-v E203.
La doc chinoise resort bien via google translate : https://translate.google.fr/translate?sl=auto&tl=fr&u=http%3A%2F%2Ftang.lichee.pro%2F

la carte embarque un debugger fpga et est reconnu comme jlink usb. Je n'ai pas encore reussi à faire fonctionner openocd mais j'ai pu communiquer avec la carte via l'ide TD(Tang Dynasty) sans controleur supplementaire. J'ai testé quelques programmes d'exemples et constaté que le softcore risc-v e203 était déjà flashé. Je précise que j'ai testé les exemples en jtag et n'ai rien flashé pour le moment.

J'ai également testé une connexion uart : https://asciinema.org/a/0kQnYZWiAnfUu6bdKKefU5R0P

Je prépare actuellement l'environnement de dev risc-v ça prend un peu de temps patience...

## sources

[documentation lichee-tang en vo](http://tang.lichee.pro/index.html)
[pdf descriptif](20181113213840SipeedlicheeTangSpecificationsV1.0)
[e203 softcore sur github](https://github.com/SI-RISCV/e200_opensource)
