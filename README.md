# Sidebar iOS 14

This is a sample project demonstrating an iOS 14 bug when using the new UICollectionLayoutListConfiguration on iPhones with the appearance set to .sidebar.

The problem occurs when pushing from this list configuration to another ViewController. Because the appearance modifies the directional layout margins of the right bar buttons and the large title, the transistion looks buggy. To reproduce, press and hold the button "Listen Now" and release to be pushed to the next view controller. Observe how both the top right "Edit" button and the Large title slightly shift. Then pop back and observe how the Large title is misplaced and is misaligned with the bottom Collection View.
