<h2>XYDroneExtra v2.1</h2>

------------------------------

這是一個爲XYDrone無人機組件提供放置傳送門/本地無人機照明/機載座位的附屬組件<br>
意爲解決傳統傳送門組件受限於使用定距/自身/注視點爲放置條件而無法將傳送門放置到厚牆或者遠距之外<br>
<br>
注1：本組件依賴的XYDrone的原有設計意圖爲本地化使用，但本組件的傳送門功能需要修改並依賴參數爲同步才可用，即，這項改動會致使參數佔用增加，且原本在別人視角下不可見的無人機變的可見，如果你不想讓無人機在別人視角內可見，目前本組件提供了爲無人機本體改變透明度的折中選項<br>
<br>
注2：目前本組件受每個玩家於VRChat服務器之間的網絡延遲，會導致由飛離自身之後放置的傳送門存在玩家之間看到的位置不同步而有所差別，所看到傳送門的玩家的網絡延遲越大，落點偏離也會越大。目前尚未找到有效的杜絕或者減少偏離差值的方式，如果你有更好的建議或者解決方法，也希望你能在issue中反饋給我<br>
<br>
注3：本組件中包含了3個VRC Station，由於VRChat對於Avatar的VRC Station的數量限制爲6個，所以需要你的Avatar中已經存在VRC Station不超過3個才能使本組件正常生效<br>

------------------------------

前置條件：<br>
<br>
確保你已經安裝了Modular Avatar和XYDrone本體<br>
<br>
XYDrone<br>
[無料]Vrchat Simple Drone 作者：Arcxingye<br>
https://booth.pm/en/items/6305653<br>
<br>
感謝以上作者，如果喜歡他們的作品，也請支持他們<br>
如果相關作者不希望作品被應用在此組件上也請留言給我，我將會刪除他們<br>

------------------------------

安裝方法：<br>
<br>
1.確認已經將你的XYDrone安裝至你的Avatar的層級內<br>
<br>
2.將XYDronePortalLight.Prefab拖動到你的Avatar的層級內<br>
<br>
3.完全解壓縮已經放入Avatar中的XYDronePortalLight預製件<br>
<br>
4.在XYDronePortalLight預製件下找到"菜單"中的MA Menu Installer，選擇安裝到於你的XYDrone的"极简无人机<br>[完全本地]"內（如果你沒更改過XYDrone的默認目錄名稱將會是這個名字）<br>
<br>
5.將已經放在層級中的XYDronePortalLight預製件內的"約束點"拖至XYDrone層級內的Drone>Container>MotionPoint>Motion>Object內<br>
<br>
6.將原XYDrone中的MA Parameters的以下參數勾選上同步按鈕：<br>
XYDrone/Follow<br>
XYDrone/ForBackWard<br>
XYDrone/LeftRight<br>
XYDrone/Reset<br>
XYDrone/TurnLeftRight<br>
XYDrone/UpDown<br>
XYDrone/Speed<br>
XYDrone/On<br>
XYDrone/Moving<br>

------------------------------

製作環境<br>
VRCSDK 3.8.2<br>
Modular Avatar 1.14.3<br>

------------------------------

Log:<br>
v2：新增了機載座位，計劃之後添加全屏視角切換開關和濾鏡功能<br>
v2.1：修復機載座位無法跟隨無人機的問題