marigold
========

## つかいかた
system/Initialize.tjsか何かでStorages.addAutoPathで読みこませるか、
var subfoldersをしている部分にmarigoldを追加する。
その後、AfterInit.tjsか何かで
Scripts.evalStorage("marigoldLoader.tjs");
をすれば、
global.marigold
以下に便利スクリプト群がロードされます。