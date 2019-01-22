# PruebasIOS
Pruebas IOS

copy_ipa.sh

#!/bin/sh
echo "copy IPA"
cp /Users/integracion/jenkins/workspace/Pipeline-ProduceRegistroIOS/iOSProduceRegistro/IPA/DEBUG/Apps/iOSProduceRegistro.ipa /Users/integracion/jenkins/workspace/Pipeline-ProduceRegistroIOS/iOSProduceRegistro/IPA/iOSProduceRegistro.ipa

chmod -R 777 /Users/integracion/jenkins/workspace/Pipeline-ProduceRegistroIOS/iOSProduceRegistro/IPA/iOSProduceRegistro.ipa

rm -rf /Users/integracion/jenkins/workspace/Pipeline-ProduceRegistroIOS/iOSProduceRegistro/IPA/DEBUG/Apps/*

echo "FIN copy IPA"
