def handleTimerEvent():
	a = system.tag.readBlocking('[default]Station_11/ph')
	a1 = a[0].value;
	c1 = S1.myS(a1, 5)
	
	system.tag.writeBlocking('[default]NT', c1 )
	