This is the folder where the UI icons are placed
================================================

File format advice
------------------

The icons should be 160x160 .PNG files with transparent background (Alpha channel). Other format can work but this is what FunPimps use.

Naming advice
-------------

If the icon file is named the same way as the item or block you want to use it for, you do not need any extra XML or XPATH code in your mod.

Example, for the following block

    <block name="steelBlock">
		<property name="Extends" value="steelMaster"/>
		<property name="SortOrder2" value="0050"/> <!-- SortShape -->
		<property name="DowngradeBlock" value="rConcreteBlock"/>
	</block>

if you use the filename `steelBlock.png` for the icon, the new icon will automatically be replaced in the game. It also works for blocks or items that are not reference in your mod.
