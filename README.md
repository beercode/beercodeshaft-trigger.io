BeerCodeShaft-trigger.io
========================

Prvi projekat koji testira Trigger.io kao mobile builder.

Projekat portuje sjajan primer korišćenja paper.js biblioteke - http://zardina.org/resoshaft i portuje isti na touch ekrane.

Trčanje iliti Running
=====================

* Preuzmite trigger.io sa https://trigger.io/forge/ 
* Registrujte se da bi mogli da pokrećete build tražiće username.
* Idite u folder u kome ste otpakovali trigger.io i pokrenite:

*nix
 
    source go.sh
    
ili
  
    go.bat (ako ste na Windowsu)

Nakon toga nazad u folder gde ste klonirali repo i pustite forge da radi.

    forge build
    forge run android
    
Kod 'run' komande možete da birate da li hoćete ['android', 'chrome', 'ios', 'web'].

Kada terate android moraćete da dodate sdk path (ili da pustite da forge uradi download istog za vas automatski). Parametar je '--android.sdk'.


