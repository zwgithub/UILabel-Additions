UILabel-Additions
=================

用于UILabel的高度和行数自动适应UILabel的内容

调用方法：
	
	UILabel *label = [[UILabel alloc] initWithFrame:CGRectMake(0,0,20,20)];
	[label adjustFontWithMaxSize:CGSizeMake(label.width, MAXFLOAT)];

`注意`
  需在设置label的text属性之后调用adjustFontWithMaxSize方法。
