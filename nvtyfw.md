代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbqffsmo.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.birdmap.top/Article/details/gt2yybucttj.html

Go:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gt2aiwobuus.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.haohaochexian.top/Article/details/gt2rpaheivo.html

C#:   // 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gt2akizthap.html

[A15] 空值判断与默认值
来源：http://dali.xuanzx.com/Article/details/gt2spnlxlsp.html

Py:   value = data or "默认值"
来源：http://dali.yanxiufei.cn/Article/details/gt2rqqclrnf.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gt2txpxtxig.html

JS:   const value = data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gt2qwhqsfzl.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkveqvco.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zycfv.cn/Article/details/gt2lrmkbcyj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.0kj1m.cn/Article/details/gt2aasspddh.html

Ruby: value = data || "默认值"
来源：http://dali.hywenlv.cn/Article/details/gt2ulwfmteg.html

C#:   var value = data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gt2voxpcxim.html

[A16] 真假值判断规则
来源：http://dali.ydzc1.top/Article/details/gt2ugkuxpwx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.tianlin.xyz/Article/details/gt2owlebvqy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnxiangtu.top/Article/details/gt2rizezwts.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gotoacloud.top/Article/details/gt2uoftfwfw.html

TS:   if (!x) {}
来源：http://dali.ydzc1.top/Article/details/gt2xkipmuqj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.aizwys.cn/Article/details/gt2njhvegoe.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngmowkpm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnjjrbnm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2eqjflhtc.html

[A17] 位运算
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwteyyla.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gt2lyqokiyv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.meibo888.top/Article/details/gt2fbkwydgs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqpxatrz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sobcoija.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gt2aynldhsm.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2otyjjibd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqjykonw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2ekyxdwvo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.fzhhl.top/Article/details/gt2fyyfpfmo.html

Py:   ord("A"); chr(65)
来源：http://dali.jiagoushi.top/Article/details/gt2roqftbwe.html

PHP:  ord("A"); chr(65)
来源：http://dali.fzhhl.top/Article/details/gt2kwbqdaja.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ehwqpu.com/Article/details/gt2jvhtzghz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xinyue.icu/Article/details/gt2fhioasme.html

Java: (int) 'A'; (char) 65
来源：http://dali.jlsjyb.cn/Article/details/gt2remvzqde.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aibaodan.cn/Article/details/gt2hvhosxuy.html

Ruby: "A".ord; 65.chr
来源：http://dali.wangdashe.top/Article/details/gt2keisfivs.html

C#:   (int)'A'; (char)65
来源：http://dali.wangdashe.top/Article/details/gt2bjfxhxrn.html

[A19] 交换两个变量
来源：http://dali.yuxming.cn/Article/details/gt2kahavgjp.html

Py:   a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gt2tvlaybri.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.quarkkingdee.top/Article/details/gt2vppqzfpo.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gt2rfygrcey.html

TS:   [a, b] = [b, a];
来源：http://dali.chenjidiqi.icu/Article/details/gt2vigawtpl.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqjrhqki.html

Go:   a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gt2tecyctay.html

Ruby: a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gt2xkxlbbjs.html

C#:   (a, b) = (b, a);
来源：http://dali.xziqi.cn/Article/details/gt2clkimpqs.html

[A20] 读取标准输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpbxqqzf.html

Py:   name = input("请输入：")
来源：http://dali.gaohongyu789.top/Article/details/gt2uxqfjtti.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhoulong.xyz/Article/details/gt2ileobsqs.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hywenlv.cn/Article/details/gt2nnhxqqiu.html

TS:   // Node.js：readline 模块
来源：http://dali.yj20258.top/Article/details/gt2vryhvwrn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.vqdsnc.cn/Article/details/gt2hfhupfbh.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cqqwz.cn/Article/details/gt2banedgyc.html

Ruby: gets.chomp
来源：http://dali.shangyingyoupin.top/Article/details/gt2albcziey.html

C#:   Console.ReadLine();
来源：http://dali.yangfankeji.com/Article/details/gt2smjfhbwj.html

[A21] 保留指定小数位输出
来源：http://dali.fengsongda.top/Article/details/gt2gsiwsgyg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.guowangkeji.top/Article/details/gt2fjsrqndj.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2gguotebt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gt2sqvayhci.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sweek.top/Article/details/gt2ttggkpai.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gt2sjkocpef.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gt2dhppezaw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gt2wdrlucev.html

C#:   3.14159.ToString("F2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtmmqpey.html

[A22] 获取字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2wnjwdnbx.html

Py:   len(s)
来源：http://dali.pycfn.com/Article/details/gt2xkbucxch.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hammf.cn/Article/details/gt2bgqwvrpg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zycfv.cn/Article/details/gt2psuizetf.html

TS:   s.length
来源：http://dali.9152youxi.cn/Article/details/gt2lhcaocvu.html

Java: s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2ctapmazw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dianchejie.cn/Article/details/gt2ouipbvhp.html

Ruby: s.length
来源：http://dali.tian-w.cn/Article/details/gt2ubvqurwo.html

C#:   s.Length
来源：http://dali.andypj.xyz/Article/details/gt2jyjjehyz.html

[A23] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2uxdjbclv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gzhubu.top/Article/details/gt2ebimjybl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sxryk.cn/Article/details/gt2mtqijbor.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gt2lcuvkvci.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikfwmhsg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jianghu66.top/Article/details/gt2ddcqxnwr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sufxvd.cn/Article/details/gt2nzvyypao.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2zfyabkaa.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhoulong.xyz/Article/details/gt2auidumlt.html

[A24] 去除首尾空白
来源：http://dali.tanke756.top/Article/details/gt2edonhbbc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hnqzz.top/Article/details/gt2hfozagui.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.vqdsnc.cn/Article/details/gt2mdtutkan.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gt2xtynisir.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gt2ijtiegwb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hfpthk.cn/Article/details/gt2pdlujuhh.html

Go:   strings.TrimSpace(s)
来源：http://dali.tianlin.xyz/Article/details/gt2ltzdaulz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.snrcjt.cn/Article/details/gt2bkzytriy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gt2vlvclmce.html

[A25] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spazcpdn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sweek.top/Article/details/gt2trvqkeca.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yueranfly.top/Article/details/gt2xzzhcyzu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gt2lngxybcm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pycfn.com/Article/details/gt2gvlznjfz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sweek.top/Article/details/gt2lrekbbnu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jyoumei.cn/Article/details/gt2hnwxhnxu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj20258888.top/Article/details/gt2eekosuav.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gt2fcexbqzk.html

[A26] 类型转换总览
来源：http://dali.jianghu66.top/Article/details/gt2pgenttzc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.haohaochexian.top/Article/details/gt2ycfukzwe.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gogol.net.cn/Article/details/gt2thrjvctd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.andypj.xyz/Article/details/gt2kydsbqoy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258888.top/Article/details/gt2nfwtonvs.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gt2qqeoicyc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigufen.top/Article/details/gt2piampxvc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nwbrower.top/Article/details/gt2lhmvjavu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gt2sxzrttus.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2sjrvhoad.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndomhyzd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbdzgddw.html

[B01] 条件判断 if / else
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnfgxwih.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.redwolf501.top/Article/details/gt2bihfnlhv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.wangdashe.top/Article/details/gt2snirjish.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2suoszset.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gt2pxcoqufv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gt2gynhivbc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyqfdjmi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.quarkkingdee.top/Article/details/gt2azooreme.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gt2znqmiewg.html

[B02] 多分支 else if / elif
来源：http://dali.smart0.xyz/Article/details/gt2zwzzclvq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sufxvd.cn/Article/details/gt2hlqrnqyp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yuxming.cn/Article/details/gt2nzpfbewm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gt2tpnlqtsu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gt2hztxggmv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gt2ubtuwkqn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.haohaochexian.top/Article/details/gt2huftsiwp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daxiang520.top/Article/details/gt2duejiati.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gt2mkzulyxe.html

[B03] switch / match / case
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzuntcyk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.dianchejie.cn/Article/details/gt2cpmfzzws.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2crwkorfo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2mnhqmymi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gt2rshrzqqg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2upnjngwy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.andypj.xyz/Article/details/gt2smydxzng.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhoulong.xyz/Article/details/gt2dttcotgx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yueranfly.top/Article/details/gt2jdwihnyr.html

[B04] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gt2qaokqduz.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gt2nbukzfpz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shuidangran.top/Article/details/gt2dnsebeez.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gt2zamaavan.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gt2xfdhcvcb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2miyhpaar.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xylfe.cn/Article/details/gt2ztfwwnsk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gotoacloud.top/Article/details/gt2hnnbavue.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2glcmnxus.html

[B05] 遍历数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gt2fiaworeq.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigfzy.top/Article/details/gt2zlubzuhc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gt2vubsqyow.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzenwtrl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pppurgim.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2usfvhcyg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.iojbl.cn/Article/details/gt2pmarlszf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dianchejie.cn/Article/details/gt2sqgsykni.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hysaishi.cn/Article/details/gt2hkurycxe.html

[B06] 遍历字典 / 对象
来源：http://dali.nanxuanxn.top/Article/details/gt2aibepxci.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ppjwa.cn/Article/details/gt2gycwkjej.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tian-w.cn/Article/details/gt2jrohptgg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gt2npgbrvgf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.birdmap.top/Article/details/gt2uuwvfecc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.snrcjt.cn/Article/details/gt2kmoefprn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shuidangran.top/Article/details/gt2hlnynaxl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.havefunace.top/Article/details/gt2ihjfsane.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cdnleiting.top/Article/details/gt2ogtwqppw.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gt2efoudmbq.html

Py:   while i < 10: i += 1
来源：http://dali.ppjwa.cn/Article/details/gt2ydchacsa.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cheryme.top/Article/details/gt2dglhdjkv.html

JS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gt2dtkbpetc.html

TS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gt2lgphaqwg.html

Java: while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gt2wdizxnii.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hfpthk.cn/Article/details/gt2hffecywj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgozhtzk.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2zjagrljp.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258888.top/Article/details/gt2ktgtmufl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifwabiyz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crhrhaqz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2znzgwfld.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gt2injegiut.html

Java: do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2dcwyysio.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cheryme.top/Article/details/gt2fxsswqrx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aleldeca.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2pmlppqbz.html

[B09] break 与 continue
来源：http://dali.wangshuangyany.cn/Article/details/gt2osdjrfun.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258.top/Article/details/gt2ciykdalq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2jprukmbu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2nqomjqjd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2gjbxnuvk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2situwtmi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fengsongda.top/Article/details/gt2hxrvyceh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gt2bclipvqb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2pwiqpthq.html

[B10] 遍历同时拿索引
来源：http://dali.9152youxi.cn/Article/details/gt2qohxkhst.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cqqwz.cn/Article/details/gt2mtejyyoe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gt2mwaxzzgy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gt2ekhougju.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gt2uvvspzbg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aibaodan.cn/Article/details/gt2oskuuavg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guannengcc.top/Article/details/gt2fwaijcbn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gt2zmcnlqqq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gt2ehyrcdci.html

[B11] 生成数字序列 / 区间
来源：http://dali.gotoacloud.top/Article/details/gt2wkhuxrdd.html

Py:   list(range(0, 10, 2))
来源：http://dali.cashguo.top/Article/details/gt2grmkghcd.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2yzuolrfd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ektxhrrm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gt2dmceafvu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.havefunace.top/Article/details/gt2nmcrwdlt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tanke756.top/Article/details/gt2umppyjoj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gt2xiwwgbro.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.c1oappe.top/Article/details/gt2gllyhfqp.html

[B12] 跳出多层循环
来源：http://dali.birdmap.top/Article/details/gt2sldukcgl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pycfn.com/Article/details/gt2ffjaxglo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gt2ltfssudr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2ulnqpjbs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gt2fpomlnvm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2qxmdrooz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nwbrower.top/Article/details/gt2avfecshq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nostmvik.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gt2zufkqbxe.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gt2xdpvsvwy.html

Py:   isinstance(x, (int, float))
来源：http://dali.daxiang520.top/Article/details/gt2vipbhjfj.html

PHP:  is_numeric($x)
来源：http://dali.chenlongwang.top/Article/details/gt2yxnbszhv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gt2lysrdmsd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmbiuxhr.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2piarawbv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gt2pcgtecyr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gt2tqpgzzax.html

C#:   x is int or double or decimal
来源：http://dali.cashguo.top/Article/details/gt2lvttlyhl.html

[B14] 判断值是否在集合内
来源：http://dali.xuanzx.com/Article/details/gt2iwdovpej.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.0kj1m.cn/Article/details/gt2wwpegfzg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nwbrower.top/Article/details/gt2qmihuaaz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gt2omrpubft.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2lmcgyyta.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2bfovwqeo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yangfankeji.com/Article/details/gt2lweiklzw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gt2rwvkqkku.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2jolvafao.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gt2gesixbbq.html

Py:   a and b or not c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbgbqkxa.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gt2lckjhwcz.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2wjdwyjsp.html

TS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2pdiddgsn.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2khtjerdu.html

Go:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdclqeel.html

Ruby: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2vqmadibp.html

C#:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2skcuoega.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbkjobgw.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gt2dnjnyyos.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bovzhlum.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2twagguji.html

TS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gt2qbpvryvd.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2fabxghif.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gt2gmmnjnkv.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gt2ancffhej.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gt2krdmgkpy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2amowlnlj.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2fwwaqkbr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2anhgikaf.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2guqvksfb.html

Py:   def add(a, b): return a + b
来源：http://dali.andypj.xyz/Article/details/gt2jyabqtpi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2mcmlpqes.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2hwydlndp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2ypknxdem.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zvjzhjjx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2jdbwahyb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aibaodan.cn/Article/details/gt2sgnmyjdn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmzdvmlq.html

[C02] 默认参数
来源：http://dali.dianchejie.cn/Article/details/gt2jyxmijac.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gt2xbdvxjtj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ysqumvtg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2kdouhhty.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gt2bmrinsqv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gt2iigmfqzh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigfzy.top/Article/details/gt2xlwxvemb.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gt2jhlxcits.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhixingplan.top/Article/details/gt2ijepayll.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gt2bkukkvgr.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenzaomai.com/Article/details/gt2wngnumkl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gt2mtzssabi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gt2fcbjyuwi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gt2nwrjqyih.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuxming.cn/Article/details/gt2fblqditu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gt2sapxzhsl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gt2embvmpxi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258.top/Article/details/gt2qvbvxvsg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gt2clbawpdl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gt2bapcdmwv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwoshpaz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ryxgmkjn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gt2mjasyghq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsaliwcd.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gt2ibpuvent.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gt2nnqyxamy.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwtzrpof.html

[C05] 返回多个值
来源：http://dali.andypj.xyz/Article/details/gt2crgckccw.html


<!-- 参考信息 -->