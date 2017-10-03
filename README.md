# weboffice-infra3d
Integration of infra3D into WebOffice

##Installation
Das Tool muss auf demselbem Server wie WebOffice bereitgestellt werden. Entweder im /pub Verzeichnis von WebOffice oder auf IIS als virtuelles Verzeichnis, z.B. /webofficeinovitas.

In WebOffice erfolgt die Konfiguration als Externes Gui Modul im Abschnitt Projektkonfiguration.

* Aufzurufende URL: https://server.com/webofficeinovitas/tool1_form.htm
* Modus http GET
* Anzeigemodus: IFrame-Floating

Getestet mit WebOffice 10.4 und 10.5
