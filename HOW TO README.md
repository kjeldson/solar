# solar

Spørg endelig hvis i har nogle spørgsmål, vil dog lige sige jeg selv har taget noget af koden fra andre som jeg har findet på netter og mixet det 
sammen med min egen kode, og det kunne sikkert laves bedre og pænere. 
men det virker og er rigtig stabilt. 
det eneste jeg mangler at lave er at hvis mqtt taber forbindelsen så vil jeg gerne have at sensore står til unavalible istedet for at vise sidste værdi.


De 3 filer 
tracer-real-time
tracer-settings
tracer-stats
tracer-rated-datum
kopieres over i HA under bibloteket     \config\esphome ( samme sted som andre esp home programeringer ligger)
så laves der en ny esp home program med des esp man nu har og ligger koden fra filen "epever_bms_contorl" der i og tilpasser den med de ssid og password i nu har 

Jeg har valgt at bruge pin 17 TX og pin 16 RX som går til modbus modulet til EPEVER
og jeg har valgt at bruge pin 13 RX og pin 15 TX til SMART BMS som går direkte via kabel til "Smart BMS"

jeg har sat en onewire temp sensor på pin 23
så har jeg lavet 4 indgange til level senser på vand tanken osv
og 4 relæ udgange til div eks kunne tænde varme remote osv.
