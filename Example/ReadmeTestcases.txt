BeagleBoneTracerAddSled.tdf is a trace created and interpreted by Texas Instruments Code Composer Studio.
The trace was recoded without contextIds,in cycle accourate mode and with Data address tracing.
The tdf fiel format contains the interpretation and also the raw data.
TraceDump.txt is the extracted raw data from BeagleBoneTracerAddSled.tdf
It can be analysed by etm2human and produces the same result as code compsoer studio with:
etm2human -C -c 0 -i ./TraceDump.txt

OneRoundTraceDump.txt: this file was created with the Debug Server Scripting API of Code Composer Studio and can be analyzed with:
etm2human -C -c 0 -i ./OneRoundTraceDump.txt 