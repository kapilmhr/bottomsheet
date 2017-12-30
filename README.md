# bottomsheet
Simple bottom sheet from google design library

## Bottom sheet

#### get the bottom sheet view
        llBottomSheet = (LinearLayout) findViewById(R.id.bottom_sheet);

#### initialize the bottom sheet behavior
        final BottomSheetBehavior bottomSheetBehavior = BottomSheetBehavior.from(llBottomSheet);

#### change the state of the bottom sheet
        bottomSheetBehavior.setState(BottomSheetBehavior.STATE_COLLAPSED);
        bottomSheetBehavior.setState(BottomSheetBehavior.STATE_EXPANDED);
        bottomSheetBehavior.setState(BottomSheetBehavior.STATE_HIDDEN);

#### set the peek height
       bottomSheetBehavior.setPeekHeight(40);
#### set hideable or not
        bottomSheetBehavior.setHideable(true);
