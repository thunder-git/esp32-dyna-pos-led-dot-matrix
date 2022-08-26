# ESP32 driver for DynaPos Led Dot Matrix Display

## ESP32 / JP2 interface

|JP2 pin#|Function|Description|ESP32 pin#|
|--------|--------|-----------|----------|
|1|col_A0_demux|Bit A0 of column demux|D13|
|2|col_A1_demux|Bit A1 of column demux|D12|
|3|col_A2_demux|Bit A2 of column demux|D14|
|4|E1_demux|Bit E1 of demux enable|D27|
|5|row_latch|Latches bits to rows|D26|
|6|row_clock|Serial clock|D25|
|7|row_serial_in|Serial input|D33|
