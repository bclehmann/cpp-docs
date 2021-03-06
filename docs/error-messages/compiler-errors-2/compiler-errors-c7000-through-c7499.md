---
description: "Learn more about: Compiler errors C7000 through C7499"
title: "Compiler errors C7000 through C7499"
ms.date: 04/18/2021
f1_keywords: ["C7001", "C7002", "C7003", "C7004", "C7005", "C7006", "C7007", "C7008", "C7009", "C7010", "C7011", "C7012", "C7013", "C7014", "C7015", "C7016", "C7017", "C7018", "C7019", "C7020", "C7021", "C7022", "C7023", "C7024", "C7025", "C7026", "C7027", "C7028", "C7029", "C7030", "C7031", "C7032", "C7033", "C7034", "C7050", "C7051", "C7052", "C7053", "C7054", "C7055", "C7056", "C7057", "C7058", "C7059", "C7060", "C7061", "C7062", "C7063", "C7064", "C7065", "C7066", "C7067", "C7068", "C7069", "C7070", "C7071", "C7072", "C7073", "C7074", "C7075", "C7076", "C7077", "C7078", "C7079", "C7080", "C7081", "C7082", "C7083", "C7084", "C7085", "C7086", "C7087", "C7088", "C7089", "C7090", "C7091", "C7092", "C7093", "C7094", "C7095", "C7096", "C7097", "C7098", "C7099", "C7100", "C7101", "C7102", "C7103", "C7104", "C7105", "C7106", "C7107", "C7108", "C7109", "C7110", "C7111", "C7112", "C7113", "C7114", "C7115", "C7116", "C7117", "C7118", "C7119", "C7120", "C7121", "C7122", "C7123", "C7124", "C7125", "C7126", "C7127", "C7128", "C7129", "C7130", "C7131", "C7132", "C7133", "C7134", "C7135", "C7136", "C7137", "C7138", "C7139", "C7140", "C7141", "C7142", "C7143", "C7144", "C7145", "C7146", "C7147", "C7148", "C7149", "C7150", "C7151", "C7152", "C7153", "C7200", "C7201", "C7202", "C7203", "C7204", "C7300"]
helpviewer_keywords: ["C7001", "C7002", "C7003", "C7004", "C7005", "C7006", "C7007", "C7008", "C7009", "C7010", "C7011", "C7012", "C7013", "C7014", "C7015", "C7016", "C7017", "C7018", "C7019", "C7020", "C7021", "C7022", "C7023", "C7024", "C7025", "C7026", "C7027", "C7028", "C7029", "C7030", "C7031", "C7032", "C7033", "C7034", "C7050", "C7051", "C7052", "C7053", "C7054", "C7055", "C7056", "C7057", "C7058", "C7059", "C7060", "C7061", "C7062", "C7063", "C7064", "C7065", "C7066", "C7067", "C7068", "C7069", "C7070", "C7071", "C7072", "C7073", "C7074", "C7075", "C7076", "C7077", "C7078", "C7079", "C7080", "C7081", "C7082", "C7083", "C7084", "C7085", "C7086", "C7087", "C7088", "C7089", "C7090", "C7091", "C7092", "C7093", "C7094", "C7095", "C7096", "C7097", "C7098", "C7099", "C7100", "C7101", "C7102", "C7103", "C7104", "C7105", "C7106", "C7107", "C7108", "C7109", "C7110", "C7111", "C7112", "C7113", "C7114", "C7115", "C7116", "C7117", "C7118", "C7119", "C7120", "C7121", "C7122", "C7123", "C7124", "C7125", "C7126", "C7127", "C7128", "C7129", "C7130", "C7131", "C7132", "C7133", "C7134", "C7135", "C7136", "C7137", "C7138", "C7139", "C7140", "C7141", "C7142", "C7143", "C7144", "C7145", "C7146", "C7147", "C7148", "C7149", "C7150", "C7151", "C7152", "C7153", "C7200", "C7201", "C7202", "C7203", "C7204", "C7300"]
---
# Compiler errors C7000 through C7499

The articles in this section of the documentation explain a subset of the error messages that are generated by the compiler.

[!INCLUDE[error-boilerplate](../../error-messages/includes/error-boilerplate.md)]

## Error messages

| Error | Message |
|--|--|
| Compiler error C7001 | Invalid register. |
| Compiler error C7002 | Invalid branch offset. |
| Compiler error C7003 | Invalid branch offset greater than 4094 or less than -4096 |
| Compiler error C7004 | Invalid branch offset outside of __asm statement |
| Compiler error C7005 | Wrong number of arguments (missing comma?) |
| Compiler error C7006 | BRA to register is illegal.  Using BRAF |
| Compiler error C7007 | Invalid double register. |
| Compiler error C7008 | Invalid float register. |
| Compiler error C7009 | Invalid argument |
| Compiler error C7010 | Register not valid as arg |
| Compiler error C7011 | Argument types not valid for opcode |
| Compiler error C7012 | label redefined |
| Compiler error C7013 | label was undefined |
| Compiler error C7014 | Variable not valid with opcode |
| Compiler error C7015 | Inline Asm block too large.  Please use blocks of 3000 lines or less. |
| Compiler error C7016 | Load / Store operation not valid in context |
| Compiler error C7017 | Invalid register(r0) in LOAD/STORE operation |
| Compiler error C7018 | Could not find valid register |
| Compiler error C7019 | Could not find valid register for argument 1 |
| Compiler error C7020 | Could not find valid register for argument 2 |
| Compiler error C7021 | Could not find valid register for argument 3 |
| Compiler error C7022 | Instruction invalid without /QSsh4 |
| Compiler error C7023 | Instruction invalid without /QSshx |
| Compiler error C7024 | Instruction invalid without /QSdsp |
| Compiler error C7025 | Branch into delay slot is illegal |
| Compiler error C7026 | Final instruction has an empty delay slot |
| Compiler error C7027 | Given instruction is invalid in a delay slot |
| Compiler error C7028 | Unrecognized opcode.  Treating unknown text as a label |
| Compiler error C7029 | Final argument of PADD/PSUB can only be X0/Y0/A0/A1 |
| Compiler error C7030 | First argument of PMUL can only be X0/X1/Y0/A1 |
| Compiler error C7031 | Second argument of PMUL can only be Y0/Y1/X0/A1 |
| Compiler error C7032 | Final argument of PMUL can only be M0/M1/A0/A1 |
| Compiler error C7033 | Valid arguments are X0/X1/A0/A1/Y0/Y1/M0/M1 |
| Compiler error C7034 | Misaligned displacement value |
| Compiler error C7050 | symbol already defined |
| Compiler error C7051 | the symbol wasn't found in local table |
| Compiler error C7052 | missing definition for label |
| Compiler error C7053 | floating point Opcode used without -QMFPE- |
| Compiler error C7054 | invalid floating point number |
| Compiler error C7055 | coprocessor3 is undefined for the architecture given |
| Compiler error C7056 | FPU uses the computation opcode space for coprocessor3 for MIPSIV |
| Compiler error C7057 | PC register not allowed here |
| Compiler error C7058 | SP register not allowed here |
| Compiler error C7059 | RA register not allowed here |
| Compiler error C7060 | Not allowed to use AT without .set noat |
| Compiler error C7061 | Int register not allowed here |
| Compiler error C7062 | Int32 register not allowed here |
| Compiler error C7063 | FP register not allowed here |
| Compiler error C7064 | condition code register not allowed here |
| Compiler error C7065 | particular condition code register given not valid |
| Compiler error C7066 | unrecognized register |
| Compiler error C7067 | integer or floating point constants are not allowed here |
| Compiler error C7068 | indirection not allowed here |
| Compiler error C7069 | expected SP register |
| Compiler error C7070 | expected PC register |
| Compiler error C7071 | expected Mips 16 register |
| Compiler error C7072 | expected character: ')' |
| Compiler error C7073 | memory references are not allowed here |
| Compiler error C7074 | expected index register, not integer offset |
| Compiler error C7075 | this is not a valid register number |
| Compiler error C7076 | index indirections not allowed here |
| Compiler error C7077 | expected register |
| Compiler error C7078 | this type of register is not allowed here |
| Compiler error C7079 | '$' is not followed by a valid register identifier |
| Compiler error C7080 | expected register - macro, not literal |
| Compiler error C7081 | this is not a valid argument register number |
| Compiler error C7082 | '%' is not followed by a valid register identifier |
| Compiler error C7083 | expected string constant |
| Compiler error C7084 | expected character: ' |
| Compiler error C7085 | undefined symbol in expression |
| Compiler error C7086 | function literal used with call optimization |
| Compiler error C7087 | entering label into table failed |
| Compiler error C7088 | expected function, found label |
| Compiler error C7089 | expected label, found function |
| Compiler error C7090 | label not valid here |
| Compiler error C7091 | expected label name |
| Compiler error C7092 | unrecognized operand |
| Compiler error C7093 | unidentified .set directive |
| Compiler error C7094 | macro requires .set noreorder |
| Compiler error C7095 | macro instruction used |
| Compiler error C7096 | labels not allowed in repeat block |
| Compiler error C7097 | .endr without matching .repeat found |
| Compiler error C7098 | Immediate size is too large.  Using LI. |
| Compiler error C7099 | expected character: ',' |
| Compiler error C7100 | expected character: ':' |
| Compiler error C7101 | expected character: %C |
| Compiler error C7102 | expected another operand |
| Compiler error C7103 | unidentified operand |
| Compiler error C7104 | expected a positive integer constant |
| Compiler error C7105 | expected character: ',' or ':' |
| Compiler error C7106 | Symbol is not a label. Can't branch to this location. |
| Compiler error C7107 | label or symbol redefinition |
| Compiler error C7108 | unidentified instruction |
| Compiler error C7109 | unsupported instruction |
| Compiler error C7110 | is not a global function |
| Compiler error C7111 | must use RA |
| Compiler error C7112 | nop must be inside .set noreorder section |
| Compiler error C7113 | did not find information on branch instruction |
| Compiler error C7114 | expected immediate |
| Compiler error C7115 | immediate too large |
| Compiler error C7116 | opcode used without -QMn32 |
| Compiler error C7117 | must use label immediate in order to use PC offset |
| Compiler error C7118 | one of the registers must be a MIPS16 register |
| Compiler error C7119 | extra source text found beyond the end of instruction |
| Compiler error C7120 | opcode used without -QMFPE- |
| Compiler error C7121 | Invalid instruction for switches given.  Check instruction set against switches given. |
| Compiler error C7122 | unimplemented directive |
| Compiler error C7123 | symbol is not a label |
| Compiler error C7124 | LAU not supported in inline assembly |
| Compiler error C7125 | instruction has unhandled dope for form given |
| Compiler error C7126 | unable to branch to location given |
| Compiler error C7127 | valid function not given |
| Compiler error C7128 | invalid operand type |
| Compiler error C7129 | instruction is not supported for inline assembly |
| Compiler error C7130 | JALR should not use $31 alone or any register twice |
| Compiler error C7131 | shift amount not in the range [0, 63] |
| Compiler error C7132 | shift amount not in the range [0, 31] |
| Compiler error C7133 | immediate value not in the range [0, 31] |
| Compiler error C7134 | offset of the source operand not in the range [0, 7] |
| Compiler error C7135 | offset of the second source operand not in the range [0, 7] |
| Compiler error C7136 | vector-vector operation is not applicable for this instruction |
| Compiler error C7137 | shift amount not in the range [0, 7] |
| Compiler error C7138 | expected FP Control Register - 0 or 31 |
| Compiler error C7139 | invalid hint |
| Compiler error C7140 | must use even register (64 bit register) |
| Compiler error C7141 | must use vector (64 bit floating point register) |
| Compiler error C7142 | invalid InlnExpression |
| Compiler error C7143 | '/': division by zero |
| Compiler error C7144 | '%': modulo by zero |
| Compiler error C7145 | bitwise operations are not applicable on a float constant |
| Compiler error C7146 | expected an operand |
| Compiler error C7147 | unable to evaluate indirection |
| Compiler error C7148 | undefined function |
| Compiler error C7149 | label or symbol redefinition |
| Compiler error C7150 | branch target is invalid |
| Compiler error C7151 | branch and link instructions not supported in inline assembly |
| Compiler error C7152 | BC1ANY2x can use only $fcc{0,2,4,6} |
| Compiler error C7153 | BC1ANY4x can use only $fcc{0,4} |
| Compiler error C7200 | '%s:' can only generate hybrid pop thunk for symbols with C linkage |
| Compiler error C7201 | can only generate hybrid thunks for non-static functions |
| Compiler error C7202 | '%s:' hybrid unsupported feature '%s.' |
| Compiler error C7203 | '%s': '__declspec(hybrid_patchable)' can only be applied to class declarations or definitions, or non-static functions |
| Compiler error C7204 | '%s': guest reference call signature does not match ('%s' != '%s') |
| Compiler error C7300 | only a call to '%s' is allowed in this function |

## See also

[C/C++ Compiler and build tools errors and warnings](../compiler-errors-1/c-cpp-build-errors.md) \
[Compiler errors C2000 - C3999, C7000 - C7999](../compiler-errors-1/compiler-errors-c2000-c3999.md)
