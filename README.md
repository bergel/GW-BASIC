# Microsoft GW-BASIC Interpreter Source Code

This repo contains the original source-code for Microsoft's GW-BASIC interpreter, as of 1983,
adjusted for assembling with available versions of the Microsoft Macro Assembler.

## Announcement blog
https://devblogs.microsoft.com/commandline/microsoft-open-sources-gw-basic/

## Information

Here I'm working to assemble the original code with Microsoft MASM 5.1A.
This is the version that currently seems to match the code most closely.

Following some changes, all files have been assembled.
The following identifiers cannot be resolved.
`CLREOL`,
`CLRSCN`,
`CSRATR`,
`CSRDSP`,
`DONOTE`,
`DOWNC`,
`EDTMAP`,
`FETCHC`,
`FKYADV`,
`FKYFMT`,
`GETFBC`,
`GETHED`,
`GRPSIZ`,
`GTASPC`,
`GWINI`,
`GWTERM`,
`INFMAP`,
`INICOM`,
`INKMAP`,
`KEYINP`,
`LCPY`,
`LEFTC`,
`MAPSUP`,
`MAPXYC`,
`NREAD`,
`NSETCX`,
`NWRITE`,
`PEKFLT`,
`PGINIT`,
`PIXSIZ`,
`PNTINI`,
`POKFLT`,
`POLLEV`,
`PRTMAP`,
`RDPEN`,
`RDSTIK`,
`RDTRIG`,
`READC`,
`RECCOM`,
`RIGHTC`,
`SCALXY`,
`SCANL`,
`SCANR`,
`SCRATR`,
`SCRINP`,
`SCROLL`,
`SCROUT`,
`SCRSTT`,
`SEGINI`,
`SETATR`,
`SETC`,
`SETCBF`,
`SETCLR`,
`SETFBC`,
`SNDCOM`,
`SNDLPT`,
`STACOM`,
`STOREC`,
`SWIDTH`,
`TDOWNC`,
`TRMCOM`,
`TUPC`,
`UPC`.
Most appear to be missing from the source code.


Pull requests for fixing the remaining compilation programs are welcomed.

## Building instructions
Under [DOSBox](https://www.dosbox.com/) mount a directory containing:
* This code
* The Microsoft Macro Assembler (MASM) version 5.1A
* The Microsoft make program that comes with MASM.

Run `make makefile` to assemble the files.

You can fetch MASM 5.1A from
[this site](https://www.pcjs.org/software/pcx86/lang/microsoft/masm/4.00/).
From the pull-down menu load and then save the corresponding disk.
Mount the image on a Linux computer and copy the files across to
your development directory.

## License

All files within this repo are released under the [MIT (OSI) License]( https://en.wikipedia.org/wiki/MIT_License) as per the [LICENSE file](https://github.com/Microsoft/GW-BASIC/blob/master/LICENSE) stored in the root of this repo.

## Contributing

Pull requests addressing problems in getting GW-BASIC to build and run
are welcomed.

## Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).  For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
