> 以下文字語境需將嵌入式系統置先

### Lec01

- 特點
    - 應用面極廣
    - 專一功能
    - 部分非 programmable 
    - 成本較低
    - 相對較少的耗電,體積 

- 開發流程
    - 需求分析 
    - 編碼
    - 測試
    
- 原則 <small>(for now)</small>
    - 設計與測試並進
    - 軟體可先與硬體進行
    - 其應用與需求 一般在設計之初就已確定

- 開發
    
    | 硬體 | 軟體 |
    | --- | --- |  
    | 從頭開始 | 應用軟件 | 
    | 用現有的物件 | 系統軟件 <small>( OS 級別 )</small> | 

- SoC
    - 全稱 <small>*System on Chip*</small> 
    - 其由軟硬件兩部分組成<br>可看做 *迷你主機板*, *集成電路*.

### Lec 02 

- Cross compiler <small>( e.g. ARM, x86 )</small>
- Bootloader 
- FPGA
- 燒錄


### Lec 03

- Embedded Toolchain
- 流程
    - C code
    - Assembler Compiler 
    - Debugger (in host)
    - Emulation Hardware (like iPhone X in XCode)

- Toolchain 
    - Console 
        - GNU toolchain
            - gcc -- a cross-compiler
            - binutils -- a set of tools for manipulating binaries
            - glibc -- c-lib
            - gdb --  debugger (ICE is required)

    - IDE 
        - ADS
        - GNUPro

### Lec 04 