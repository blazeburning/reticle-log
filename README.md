                             *************************************************************
                             *                           FUNCTION                          
                             *************************************************************
                               undefined  FUN_00512bd0 ()
                               assume FS_OFFSET = 0xffdff000
             undefined         <UNASSIGNED>   <RETURN>
             undefined4        Stack[-0x8]:4  local_8                                 XREF[3]:     00512c08 (W) , 
                                                                                                   00512c23 (W) , 
                                                                                                   00512c46 (W)   
             undefined4        Stack[-0x10]:4 local_10                                XREF[1]:     00512f83 (R)   
             undefined4        Stack[-0x14]:4 local_14                                XREF[1]:     00512beb (W)   
             undefined4        Stack[-0x18]:4 local_18                                XREF[2]:     00512c00 (W) , 
                                                                                                   00512c55 (R)   
             undefined4        Stack[-0x1c]:4 local_1c                                XREF[2]:     00512bf4 (W) , 
                                                                                                   00512f80 (R)   
             undefined4        Stack[-0x20]:4 local_20                                XREF[2]:     00512bf1 (W) , 
                                                                                                   00512f7d (R)   
             undefined4        Stack[-0x24]:4 local_24                                XREF[2]:     00512bee (W) , 
                                                                                                   00512f7a (R)   
             undefined4        Stack[-0x28]:4 local_28                                XREF[2]:     00512e14 (W) , 
                                                                                                   00512e17 (R)   
             undefined2        Stack[-0x30]:2 local_30                                XREF[3]:     00512e08 (W) , 
                                                                                                   00512e0b (R) , 
                                                                                                   00512e20 (R)   
             undefined4        Stack[-0x34]:4 local_34                                XREF[24]:    00512bfd (W) , 
                                                                                                   00512c0f (R) , 
                                                                                                   00512c34 (R) , 
                                                                                                   00512c4d (R) , 
                                                                                                   00512c64 (R) , 
                                                                                                   00512c7c (R) , 
                                                                                                   00512ca3 (R) , 
                                                                                                   00512cac (R) , 
                                                                                                   00512cdb (R) , 
                                                                                                   00512d2a (R) , 
                                                                                                   00512d5f (R) , 
                                                                                                   00512d87 (R) , 
                                                                                                   00512dbc (R) , 
                                                                                                   00512dbf (R) , 
                                                                                                   00512de2 (R) , 
                                                                                                   00512dea (R) , 
                                                                                                   00512e74 (R) , 
                                                                                                   00512e9c (R) , 
                                                                                                   00512ed1 (R) , 
                                                                                                   00512ee9 (R)   
                             FUN_00512bd0                                    XREF[1]:     FUN_00512b04:00512ba6 (c)   
        00512bd0 55              PUSH       EBP
        00512bd1 8b  ec           MOV        EBP ,ESP
        00512bd3 6a  ff           PUSH       -0x1
        00512bd5 68  4c  43       PUSH       DAT_008d434c                                     = B8h
                 8d  00
        00512bda 64  a1  00       MOV        EAX ,FS:[0x0 ]=>ExceptionList                     = 00000000
                 00  00  00
        00512be0 50              PUSH       EAX
        00512be1 64  89  25       MOV        dword ptr FS:[0x0 ]=>ExceptionList ,ESP           = 00000000
                 00  00  00  00
        00512be8 83  ec  24       SUB        ESP ,0x24
        00512beb 89  65  f0       MOV        dword ptr [EBP  + local_14 ],ESP
        00512bee 89  7d  e0       MOV        dword ptr [EBP  + local_24 ],EDI
        00512bf1 89  75  e4       MOV        dword ptr [EBP  + local_20 ],ESI
        00512bf4 89  5d  e8       MOV        dword ptr [EBP  + local_1c ],EBX
        00512bf7 8b  45  0c       MOV        EAX ,dword ptr [EBP  + Stack [0x8 ]]
        00512bfa ff  75  08       PUSH       dword ptr [EBP  + Stack [0x4 ]]
        00512bfd 89  4d  d0       MOV        dword ptr [EBP  + local_34 ],ECX
        00512c00 89  45  ec       MOV        dword ptr [EBP  + local_18 ],EAX
        00512c03 e8  e4  8a       CALL       FUN_0052b6ec                                     undefined FUN_0052b6ec()
                 01  00
        00512c08 c7  45  fc       MOV        dword ptr [EBP  + local_8 ],0x0
                 00  00  00  00
        00512c0f 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512c12 c7  01  60       MOV        dword ptr [ECX ],PTR_FUN_00aff860                = 005124cc
                 f8  af  00
        00512c18 81  c1  b0       ADD        ECX ,0x3b0
                 03  00  00
        00512c1e e8  25  3e       CALL       FUN_00576a48                                     undefined FUN_00576a48()
                 06  00
        00512c23 c7  45  fc       MOV        dword ptr [EBP  + local_8 ],0x1
                 01  00  00  00
        00512c2a 68  ec  70       PUSH       FUN_005770ec
                 57  00
        00512c2f 68  3c  71       PUSH       FUN_0057713c
                 57  00
        00512c34 8b  45  d0       MOV        EAX ,dword ptr [EBP  + local_34 ]
        00512c37 6a  04           PUSH       0x4
        00512c39 05  d4  03       ADD        EAX ,0x3d4
                 00  00
        00512c3e 6a  1c           PUSH       0x1c
        00512c40 50              PUSH       EAX
        00512c41 e8  f0  5a       CALL       `eh_vector_constructor_iterator'                 void `eh_vector_constructor_iter
                 34  00
        00512c46 c7  45  fc       MOV        dword ptr [EBP  + local_8 ],0x2
                 02  00  00  00
        00512c4d 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512c50 a1  04  b4       MOV        EAX ,[PTR_DAT_009bb404 ]                          = 00a72d1c
                 9b  00
        00512c55 8b  55  ec       MOV        EDX ,dword ptr [EBP  + local_18 ]
        00512c58 8b  19           MOV        EBX ,dword ptr [ECX ]
        00512c5a 89  41  04       MOV        dword ptr [ECX  + 0x4 ],EAX =>DAT_00a72d1c
        00512c5d 52              PUSH       EDX
        00512c5e ff  93  4c       CALL       dword ptr [EBX  + 0x14c ]=>->FUN_00786848         undefined FUN_00786848()
                 01  00  00                                                                   = 00786848
        00512c64 8b  75  d0       MOV        ESI ,dword ptr [EBP  + local_34 ]
        00512c67 8b  46  38       MOV        EAX ,dword ptr [ESI  + 0x38 ]
        00512c6a 8b  56  3c       MOV        EDX ,dword ptr [ESI  + 0x3c ]
        00512c6d 8b  5e  40       MOV        EBX ,dword ptr [ESI  + 0x40 ]
        00512c70 89  86  a4       MOV        dword ptr [ESI  + 0x2a4 ],EAX
                 02  00  00
        00512c76 89  96  a8       MOV        dword ptr [ESI  + 0x2a8 ],EDX
                 02  00  00
        00512c7c 8b  55  d0       MOV        EDX ,dword ptr [EBP  + local_34 ]
        00512c7f 89  9e  ac       MOV        dword ptr [ESI  + 0x2ac ],EBX
                 02  00  00
        00512c85 8b  ba  a4       MOV        EDI ,dword ptr [EDX  + 0x2a4 ]
                 02  00  00
        00512c8b 8b  8a  a8       MOV        ECX ,dword ptr [EDX  + 0x2a8 ]
                 02  00  00
        00512c91 8b  82  ac       MOV        EAX ,dword ptr [EDX  + 0x2ac ]
                 02  00  00
        00512c97 89  ba  98       MOV        dword ptr [EDX  + 0x298 ],EDI
                 02  00  00
        00512c9d 89  8a  9c       MOV        dword ptr [EDX  + 0x29c ],ECX
                 02  00  00
        00512ca3 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512ca6 89  82  a0       MOV        dword ptr [EDX  + 0x2a0 ],EAX
                 02  00  00
        00512cac 8b  55  d0       MOV        EDX ,dword ptr [EBP  + local_34 ]
        00512caf 8b  82  98       MOV        EAX ,dword ptr [EDX  + 0x298 ]
                 02  00  00
        00512cb5 89  42  44       MOV        dword ptr [EDX  + 0x44 ],EAX
        00512cb8 8b  82  9c       MOV        EAX ,dword ptr [EDX  + 0x29c ]
                 02  00  00
        00512cbe 89  42  48       MOV        dword ptr [EDX  + 0x48 ],EAX
        00512cc1 8b  82  a0       MOV        EAX ,dword ptr [EDX  + 0x2a0 ]
                 02  00  00
        00512cc7 89  42  4c       MOV        dword ptr [EDX  + 0x4c ],EAX
        00512cca 8b  81  70       MOV        EAX ,dword ptr [ECX  + 0x370 ]
                 03  00  00
        00512cd0 89  81  3c       MOV        dword ptr [ECX  + 0x33c ],EAX
                 03  00  00
        00512cd6 e8  b9  02       CALL       FUN_00512f94                                     undefined FUN_00512f94()
                 00  00
        00512cdb 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512cde a1  0c  2d       MOV        EAX ,[DAT_00a72d0c ]
                 a7  00
        00512ce3 8b  b9  70       MOV        EDI ,dword ptr [ECX  + 0x370 ]
                 03  00  00
        00512ce9 8b  90  2c       MOV        EDX ,dword ptr [EAX  + 0x42c ]
                 04  00  00
        00512cef 03  ff           ADD        EDI ,EDI
        00512cf1 8b  5c  fa  08    MOV        EBX ,dword ptr [EDX  + EDI *0x8  + 0x8 ]
        00512cf5 89  59  34       MOV        dword ptr [ECX  + 0x34 ],EBX
        00512cf8 8b  b0  2c       MOV        ESI ,dword ptr [EAX  + 0x42c ]
                 04  00  00
        00512cfe 8b  54  fe  0c    MOV        EDX ,dword ptr [ESI  + EDI *0x8  + 0xc ]
        00512d02 89  51  24       MOV        dword ptr [ECX  + 0x24 ],EDX
        00512d05 c7  81  d8       MOV        dword ptr [ECX  + 0xd8 ],DAT_009bb300             = 01h
                 00  00  00 
                 00  b3  9b  00
        00512d0f 8b  80  30       MOV        EAX ,dword ptr [EAX  + 0x430 ]
                 04  00  00
        00512d15 89  81  dc       MOV        dword ptr [ECX  + 0xdc ],EAX
                 00  00  00
        00512d1b 33  c0           XOR        EAX ,EAX
        00512d1d 50              PUSH       EAX
        00512d1e 66  89  81       MOV        word ptr [ECX  + 0xb8 ],AX
                 b8  00  00  00
        00512d25 e8  9e  77       CALL       FUN_007aa4c8                                     undefined FUN_007aa4c8()
                 29  00
        00512d2a 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512d2d 6a  01           PUSH       0x1
        00512d2f 0f  b7  81       MOVZX      EAX ,word ptr [ECX  + 0xb8 ]
                 b8  00  00  00
        00512d36 8b  91  3c       MOV        EDX ,dword ptr [ECX  + 0x33c ]
                 03  00  00
        00512d3c 66  89  81       MOV        word ptr [ECX  + 0xb8 ],AX
                 b8  00  00  00
        00512d43 8d  1c  12       LEA        EBX ,[EDX  + EDX *0x1 ]
        00512d46 03  db           ADD        EBX ,EBX
        00512d48 2b  da           SUB        EBX ,EDX
        00512d4a 03  db           ADD        EBX ,EBX
        00512d4c 03  db           ADD        EBX ,EBX
        00512d4e 2b  da           SUB        EBX ,EDX
        00512d50 03  db           ADD        EBX ,EBX
        00512d52 8d  b4  1b       LEA        ESI ,[EBX  + EBX *0x1  + DAT_009bb260 ]
                 60  b2  9b  00
        00512d59 56              PUSH       ESI
        00512d5a e8  29  6d       CALL       FUN_007b9a88                                     undefined FUN_007b9a88()
                 2a  00
        00512d5f 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512d62 8b  1d  08       MOV        EBX ,dword ptr [DAT_00a72d08 ]
                 2d  a7  00
        00512d68 8b  15  04       MOV        EDX ,dword ptr [DAT_00a72d04 ]
                 2d  a7  00
        00512d6e a1  00  2d       MOV        EAX ,[DAT_00a72d00 ]
                 a7  00
        00512d73 8b  b1  3c       MOV        ESI ,dword ptr [ECX  + 0x33c ]
                 03  00  00
        00512d79 ff  34  b0       PUSH       dword ptr [EAX  + ESI *0x4 ]
        00512d7c ff  34  b2       PUSH       dword ptr [EDX  + ESI *0x4 ]
        00512d7f ff  34  b3       PUSH       dword ptr [EBX  + ESI *0x4 ]
        00512d82 e8  71  3b       CALL       FUN_007868f8                                     undefined FUN_007868f8()
                 27  00
        00512d87 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512d8a 8b  81  3c       MOV        EAX ,dword ptr [ECX  + 0x33c ]
                 03  00  00
        00512d90 0f  b7  b1       MOVZX      ESI ,word ptr [ECX  + 0x334 ]
                 34  03  00  00
        00512d97 03  c0           ADD        EAX ,EAX
        00512d99 03  c0           ADD        EAX ,EAX
        00512d9b 8d  14  00       LEA        EDX ,[EAX  + EAX *0x1 ]
        00512d9e 03  d2           ADD        EDX ,EDX
        00512da0 03  d2           ADD        EDX ,EDX
        00512da2 2b  d0           SUB        EDX ,EAX
        00512da4 8d  9a  00       LEA        EBX ,[EDX  + DAT_009bb200 ]
                 b2  9b  00
        00512daa 89  99  58       MOV        dword ptr [ECX  + 0x358 ],EBX
                 03  00  00
        00512db0 66  89  b1       MOV        word ptr [ECX  + 0x346 ],SI
                 46  03  00  00
        00512db7 e8  50  45       CALL       FUN_0078730c                                     undefined FUN_0078730c()
                 27  00
        00512dbc 8b  75  d0       MOV        ESI ,dword ptr [EBP  + local_34 ]
        00512dbf 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512dc2 8b  86  00       MOV        EAX ,dword ptr [ESI  + 0x300 ]
                 03  00  00
        00512dc8 8b  96  04       MOV        EDX ,dword ptr [ESI  + 0x304 ]
                 03  00  00
        00512dce 8b  9e  08       MOV        EBX ,dword ptr [ESI  + 0x308 ]
                 03  00  00
        00512dd4 89  46  74       MOV        dword ptr [ESI  + 0x74 ],EAX
        00512dd7 89  56  78       MOV        dword ptr [ESI  + 0x78 ],EDX
        00512dda 89  5e  7c       MOV        dword ptr [ESI  + 0x7c ],EBX
        00512ddd e8  da  3d       CALL       FUN_00786bbc                                     undefined FUN_00786bbc()
                 27  00
        00512de2 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512de5 e8  c6  23       CALL       FUN_007751b0                                     undefined FUN_007751b0()
                 26  00
        00512dea 8b  75  d0       MOV        ESI ,dword ptr [EBP  + local_34 ]
        00512ded d9  05  f4       FLD        float ptr [DAT_009205f4 ]
                 05  92  00
        00512df3 dc  c9           FMUL       ST1
        00512df5 d9  c9           FXCH
        00512df7 d8  0d  f0       FMUL       float ptr [DAT_009205f0 ]
                 05  92  00
        00512dfd de  f1           FDIVRP
        00512dff 8b  8e  e8       MOV        ECX ,dword ptr [ESI  + 0x2e8 ]
                 02  00  00
        00512e05 8b  5e  30       MOV        EBX ,dword ptr [ESI  + 0x30 ]
        00512e08 d9  7d  d4       FNSTCW     word ptr [EBP  + local_30 ]
        00512e0b 0f  b7  45  d4    MOVZX      EAX ,word ptr [EBP  + local_30 ]
        00512e0f 0d  00  0c       OR         EAX ,0xc00
                 00  00
        00512e14 89  45  dc       MOV        dword ptr [EBP  + local_28 ],EAX
        00512e17 d9  6d  dc       FLDCW      word ptr [EBP  + local_28 ]
        00512e1a db  9e  b0       FISTP      dword ptr [ESI  + 0x2b0 ]
                 02  00  00
        00512e20 d9  6d  d4       FLDCW      word ptr [EBP  + local_30 ]
        00512e23 b8  0f  00       MOV        EAX ,0xf
                 00  00
        00512e28 66  89  86       MOV        word ptr [ESI  + 0x342 ],AX
                 42  03  00  00
        00512e2f 81  cb  00       OR         EBX ,0x40000
                 00  04  00
        00512e35 66  89  86       MOV        word ptr [ESI  + 0x344 ],AX
                 44  03  00  00
        00512e3c 33  d2           XOR        EDX ,EDX
        00512e3e 66  89  96       MOV        word ptr [ESI  + 0x330 ],DX
                 30  03  00  00
        00512e45 66  89  96       MOV        word ptr [ESI  + 0x37c ],DX
                 7c  03  00  00
        00512e4c 66  89  96       MOV        word ptr [ESI  + 0x37e ],DX
                 7e  03  00  00
        00512e53 89  96  80       MOV        dword ptr [ESI  + 0x380 ],EDX
                 03  00  00
        00512e59 89  96  84       MOV        dword ptr [ESI  + 0x384 ],EDX
                 03  00  00
        00512e5f 83  c9  02       OR         ECX ,0x2
        00512e62 89  8e  e8       MOV        dword ptr [ESI  + 0x2e8 ],ECX
                 02  00  00
        00512e68 89  5e  30       MOV        dword ptr [ESI  + 0x30 ],EBX
        00512e6b e8  fc  df       CALL       FUN_00520e6c                                     undefined FUN_00520e6c()
                 00  00
        00512e70 85  c0           TEST       EAX ,EAX
        00512e72 74  28           JZ         LAB_00512e9c
        00512e74 8b  55  d0       MOV        EDX ,dword ptr [EBP  + local_34 ]
        00512e77 8b  82  3c       MOV        EAX ,dword ptr [EDX  + 0x33c ]
                 03  00  00
        00512e7d 83  f8  01       CMP        EAX ,0x1
        00512e80 75  07           JNZ        LAB_00512e89
        00512e82 bb  40  00       MOV        EBX ,0xffff0040
                 ff  ff
        00512e87 eb  39           JMP        LAB_00512ec2
                             LAB_00512e89                                    XREF[1]:     00512e80 (j)   
        00512e89 83  f8  02       CMP        EAX ,0x2
        00512e8c 75  07           JNZ        LAB_00512e95
        00512e8e bb  00  ff       MOV        EBX ,0xffffff00
                 ff  ff
        00512e93 eb  2d           JMP        LAB_00512ec2
                             LAB_00512e95                                    XREF[1]:     00512e8c (j)   
        00512e95 bb  20  ff       MOV        EBX ,0xff20ff20
                 20  ff
        00512e9a eb  26           JMP        LAB_00512ec2
                             LAB_00512e9c                                    XREF[1]:     00512e72 (j)   
        00512e9c 8b  55  d0       MOV        EDX ,dword ptr [EBP  + local_34 ]
        00512e9f 8b  82  3c       MOV        EAX ,dword ptr [EDX  + 0x33c ]
                 03  00  00
        00512ea5 83  f8  01       CMP        EAX ,0x1
        00512ea8 75  07           JNZ        LAB_00512eb1
        00512eaa bb  00  00       MOV        EBX ,0xffff0000
                 ff  ff
        00512eaf eb  11           JMP        LAB_00512ec2
                             LAB_00512eb1                                    XREF[1]:     00512ea8 (j)   
        00512eb1 83  f8  02       CMP        EAX ,0x2
        00512eb4 75  07           JNZ        LAB_00512ebd
        00512eb6 bb  00  ff       MOV        EBX ,0xffffff00
                 ff  ff
        00512ebb eb  05           JMP        LAB_00512ec2
                             LAB_00512ebd                                    XREF[1]:     00512eb4 (j)   
        00512ebd bb  ff  00       MOV        EBX ,0xff0000ff
                 00  ff
                             LAB_00512ec2                                    XREF[5]:     00512e87 (j) , 00512e93 (j) , 
                                                                                          00512e9a (j) , 00512eaf (j) , 
                                                                                          00512ebb (j)   
        00512ec2 8b  82  b0       MOV        EAX ,dword ptr [EDX  + 0x3b0 ]
                 03  00  00
        00512ec8 8d  8a  b0       LEA        ECX ,[EDX  + 0x3b0 ]
                 03  00  00
        00512ece ff  50  0c       CALL       dword ptr [EAX  + 0xc ]
        00512ed1 8b  45  d0       MOV        EAX ,dword ptr [EBP  + local_34 ]
        00512ed4 c7  80  98       MOV        dword ptr [EAX  + 0x398 ],0x1
                 03  00  00 
                 01  00  00  00
        00512ede 53              PUSH       EBX
        00512edf 68  30  30       PUSH       0xa0303030
                 30  a0
        00512ee4 e8  db  5d       CALL       FUN_00578cc4                                     undefined FUN_00578cc4()
                 06  00
        00512ee9 8b  55  d0       MOV        EDX ,dword ptr [EBP  + local_34 ]
        00512eec 53              PUSH       EBX
        00512eed 68  30  30       PUSH       0xa0303030
                 30  a0
        00512ef2 89  82  cc       MOV        dword ptr [EDX  + 0x3cc ],EAX
                 03  00  00
        00512ef8 e8  c7  5d       CALL       FUN_00578cc4                                     undefined FUN_00578cc4()
                 06  00
        00512efd 83  c4  10       ADD        ESP ,0x10
        00512f00 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512f03 8b  91  3c       MOV        EDX ,dword ptr [ECX  + 0x33c ]
                 03  00  00
        00512f09 89  81  d0       MOV        dword ptr [ECX  + 0x3d0 ],EAX
                 03  00  00
        00512f0f a1  fc  2c       MOV        EAX ,[DAT_00a72cfc ]
                 a7  00
        00512f14 8b  1c  90       MOV        EBX ,dword ptr [EAX  + EDX *0x4 ]
        00512f17 8b  33           MOV        ESI ,dword ptr [EBX ]
        00512f19 89  b1  a0       MOV        dword ptr [ECX  + 0x3a0 ],ESI
                 03  00  00
        00512f1f 8b  3c  90       MOV        EDI ,dword ptr [EAX  + EDX *0x4 ]
        00512f22 8b  5f  04       MOV        EBX ,dword ptr [EDI  + 0x4 ]
        00512f25 89  99  a8       MOV        dword ptr [ECX  + 0x3a8 ],EBX
                 03  00  00
        00512f2b 8b  1c  90       MOV        EBX ,dword ptr [EAX  + EDX *0x4 ]
        00512f2e 8b  5b  08       MOV        EBX ,dword ptr [EBX  + 0x8 ]
        00512f31 89  99  a4       MOV        dword ptr [ECX  + 0x3a4 ],EBX
                 03  00  00
        00512f37 8b  04  90       MOV        EAX ,dword ptr [EAX  + EDX *0x4 ]
        00512f3a 8b  40  0c       MOV        EAX ,dword ptr [EAX  + 0xc ]
        00512f3d 89  81  ac       MOV        dword ptr [ECX  + 0x3ac ],EAX
                 03  00  00
        00512f43 33  db           XOR        EBX ,EBX
                             LAB_00512f45                                    XREF[1]:     00512f6a (j)   
        00512f45 8d  04  1b       LEA        EAX ,[EBX  + EBX *0x1 ]
        00512f48 03  c0           ADD        EAX ,EAX
        00512f4a 8d  14  00       LEA        EDX ,[EAX  + EAX *0x1 ]
        00512f4d 03  d2           ADD        EDX ,EDX
        00512f4f 03  d2           ADD        EDX ,EDX
        00512f51 2b  d0           SUB        EDX ,EAX
        00512f53 8d  8c  11       LEA        ECX ,[ECX  + EDX *0x1  + 0x3d4 ]
                 d4  03  00  00
        00512f5a e8  3d  44       CALL       FUN_0057739c                                     undefined FUN_0057739c()
                 06  00
        00512f5f 83  c3  01       ADD        EBX ,0x1
        00512f62 83  fb  04       CMP        EBX ,0x4
        00512f65 7d  05           JGE        LAB_00512f6c
        00512f67 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512f6a eb  d9           JMP        LAB_00512f45
                             LAB_00512f6c                                    XREF[1]:     00512f65 (j)   
        00512f6c 8b  4d  d0       MOV        ECX ,dword ptr [EBP  + local_34 ]
        00512f6f 8b  01           MOV        EAX ,dword ptr [ECX ]
        00512f71 ff  90  50       CALL       dword ptr [EAX  + 0x150 ]=>->FUN_004adce0         undefined FUN_004adce0()
                 01  00  00                                                                   = 004adce0
        00512f77 8b  45  d0       MOV        EAX ,dword ptr [EBP  + local_34 ]
        00512f7a 8b  7d  e0       MOV        EDI ,dword ptr [EBP  + local_24 ]
        00512f7d 8b  75  e4       MOV        ESI ,dword ptr [EBP  + local_20 ]
        00512f80 8b  5d  e8       MOV        EBX ,dword ptr [EBP  + local_1c ]
        00512f83 8b  4d  f4       MOV        ECX ,dword ptr [EBP  + local_10 ]
        00512f86 64  89  0d       MOV        dword ptr FS:[0x0 ]=>ExceptionList ,ECX           = 00000000
                 00  00  00  00
        00512f8d 8b  e5           MOV        ESP ,EBP
        00512f8f 5d              POP        EBP
        00512f90 c2  08  00       RET        0x8
        00512f93 90              ??         90h
