RFQuiltLayout
=============

A UICollectionViewLayout subclass to put items in a quilting pattern, with PSTCollectionView support in iOS5

`
    RFQuiltLayout *layout = (RFQuiltLayout*)self.collectionView.collectionViewLayout;
  	layout.blockPixels=CGSizeMake(256, 256);
		layout.direction=UICollectionViewScrollDirectionVertical;
		layout.predrawEverything=YES;
		layout.delegate=self;
		[layout setMinimumInteritemSpacing:5];
`
