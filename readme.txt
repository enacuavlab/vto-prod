# Network warning !
# To avoid network problem while getting multicast traffic from optitrack
# add route address:224.0.0.0, mask:240.0.0.0

-------------------------------------------------------------------------------
cd Projects

git clone https://github.com/enacuavlab/vto-prod.git

cd vto-prod

git submodule update --init "submodule_name"

"submodules_name":
vto-realsim
vto-tellowifi
vto-wifimonitorinject
