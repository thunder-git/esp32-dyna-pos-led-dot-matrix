# ESP32 driver for DynaPos Led Dot Matrix Display

## ESP32 / JP2 interface

|JP2 pin#|Function|Description|ESP32 pin#|
|--------|--------|-----------|----------|
|1|row_A0_demux|Bit A0 of row demux|D13|
|2|row_A1_demux|Bit A1 of row demux|D12|
|3|row_A2_demux|Bit A2 of row demux|D14|
|4|E1_demux|Bit E1 of demux enable|D27|
|5|col_latch|Latches bits to columns|D26|
|6|col_clock|Serial clock|D25|
|7|col_serial_in|Serial input|D33|
