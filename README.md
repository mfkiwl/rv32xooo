# Implementation of RISC-V(RV32IMAC) superscalar Out-of-Order processor in NSL
- This repository contains implementation of RV32IMAC named rv32xOoO.
- Re-implementation of [rv32x\_dev](https://github.com/koyamanX/rv32x_dev).
- This implementation is fully synthisable and also able to convert to software simulator(by verilator).  
- Written in [NSL](http://www.overtone.co.jp/products/and-the-nsl/) 
## NSL 
- NSLCORE is compiler tool for NSL.
- NSLCORE can convert NSL code into either Verilog HDL, VHDL, SystemC.
- You can download Trial version of Windows binary of NSLCORE from [NSLCORE Overtone(en)](http://www.overtone.co.jp/en/support/downloads/) or [NSLCORE Overtone(ja)](http://www.overtone.co.jp/support/downloads/). (registration is required, limitation of non-comercial use and code size for trial version (2000 lines?) )
- Currently over 2000 lines(must remove empty lines after preprocessing)
- You can also download [LiveCygwin](http://www.ip-arch.jp/#LiveCygwin) which provides minimum? environment of Cygwin without installing. 
- LiveCygwin includes verilator, gtkwave, iverilog, vim, NSLCORE and some implementation examples in NSL.
- If you need Linux version of NSL compiler, please consult Overtone.
### Documentations of NSL
- [NSL Reference en](http://www.overtone.co.jp/wp_overtone/wp-content/uploads/2010/06/NSL_Language_Reference_ver1.1E.pdf) and [NSL Reference ja](http://www.overtone.co.jp/release_data/documents/reference/NSL_Language_Reference_ver1.5.pdf)
- [NSL Tutorial](http://www.overtone.co.jp/software_download/ja/) (registation is required)

## Test with rv32xOoO
## Implementation Status

