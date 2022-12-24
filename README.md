pdfmake build : 0.1.39

fonts:
	1. 微软雅黑
	
	
	
===usage===

	import pdfMake from "pdfmake-with-chinese-fonts/pdfmake";
	import pdfFonts from "pdfmake-with-chinese-fonts/vfs_fonts";

	pdfMake.vfs = pdfFonts.pdfMake.vfs;

	pdfMake.fonts = {
 	 Roboto: {
    	 normal: 'Roboto-Regular.ttf',
    	 bold: 'Roboto-Medium.ttf',
     	italics: 'Roboto-Italic.ttf',
     	bolditalics: 'Roboto-MediumItalic.ttf'
	 },
	 msyh: { 
   	  normal: 'msyh.ttf',
   	  bold: 'msyh.ttf',
   	  italics: 'msyh.ttf',
    	 bolditalics: 'msyh.ttf'
   	  }
 	};
 
	defaultStyle: {font: 'msyh' },`
