# Las-Reglas-de-las-particiones-BIOS-MBR-DOS

1. Como máximo hay **4 particiones primarias**
2. Una de las primarias puede ser **extended** .
3. Dentro de la extended (si existe) pueden haber **'n' lógicas**
4. Es obligatorio que una primaria sea **Active** .

- Si es el sistema operativo es **Windows**, es **obligatorio** la norma de que una partición primaria sea Active para que el S.O pueda arrancar.
- Pero si es **Linux** , puede iniciarse sin ninguna particion Active porque puede poner el grub donde sea.
- El máximo tamaño por partición son de **2T**, como son 4 particiones en total serán 8T.
