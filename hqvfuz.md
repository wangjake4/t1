代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.jianghu66.top/Article/details/gt2xnotzmav.html

C#:   var value = data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gt2oyejarew.html

[A16] 真假值判断规则
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtbxqslt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.c1oappe.top/Article/details/gt2wquhlesm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.andypj.xyz/Article/details/gt2dsqcsyrz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhoulong.xyz/Article/details/gt2heznaaoh.html

TS:   if (!x) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgszugmf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.c1oappe.top/Article/details/gt2rzcovjyz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2heovccyo.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.fengsongda.top/Article/details/gt2lpzetrgn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2daiddaor.html

[A17] 位运算
来源：http://dali.xuanzx.com/Article/details/gt2qtrmsqvk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2qdljvyvy.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2glgxvzdu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gt2iylflrbv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gt2umltivvi.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2rjbdjgna.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gt2ufcotcnq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dhkbfsch.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2qwinkkeh.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nwbrower.top/Article/details/gt2yziaaspl.html

Py:   ord("A"); chr(65)
来源：http://dali.redwolf501.top/Article/details/gt2eounhbuu.html

PHP:  ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gt2wepdhcqq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xinyue.icu/Article/details/gt2cndlnuui.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gogol.net.cn/Article/details/gt2bacrszfq.html

Java: (int) 'A'; (char) 65
来源：http://dali.snrcjt.cn/Article/details/gt2mvyamjqm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yuxming.cn/Article/details/gt2kalqkjmx.html

Ruby: "A".ord; 65.chr
来源：http://dali.yj202588.top/Article/details/gt2qmlkvmgr.html

C#:   (int)'A'; (char)65
来源：http://dali.cashguo.top/Article/details/gt2awqsltxk.html

[A19] 交换两个变量
来源：http://dali.zhixingplan.top/Article/details/gt2fabipycs.html

Py:   a, b = b, a
来源：http://dali.pengpengdd.cyou/Article/details/gt2axxxttkt.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.bjfxy.top/Article/details/gt2bhufslqt.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gt2ftqkakmp.html

TS:   [a, b] = [b, a];
来源：http://dali.kuanghao11.cn/Article/details/gt2bnuxxsxo.html

Java: int t = a; a = b; b = t;
来源：http://dali.xuanzx.com/Article/details/gt2pgamwuij.html

Go:   a, b = b, a
来源：http://dali.dianchejie.cn/Article/details/gt2scwaqosb.html

Ruby: a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gt2zeakktrc.html

C#:   (a, b) = (b, a);
来源：http://dali.shzxlz.cn/Article/details/gt2wzvfgnpv.html

[A20] 读取标准输入
来源：http://dali.jinqigfzy.top/Article/details/gt2hrfyednl.html

Py:   name = input("请输入：")
来源：http://dali.yangfankeji.com/Article/details/gt2rbjrtods.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.andypj.xyz/Article/details/gt2anumoxje.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.smart0.xyz/Article/details/gt2sheecrpg.html

TS:   // Node.js：readline 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vygyfomx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jianghu66.top/Article/details/gt2ryunmmvo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.birdmap.top/Article/details/gt2klizhwlr.html

Ruby: gets.chomp
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbsnixbc.html

C#:   Console.ReadLine();
来源：http://dali.havefunace.top/Article/details/gt2xvoxxwed.html

[A21] 保留指定小数位输出
来源：http://dali.hysaishi.cn/Article/details/gt2pbbwkmtu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yj202588.top/Article/details/gt2myjsjrpa.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swcphidr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxoeatvb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlffdafo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gt2krpsdagr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gt2jxfjsnfe.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2dmnhvmyd.html

C#:   3.14159.ToString("F2")
来源：http://dali.daxiang520.top/Article/details/gt2wrjtqxkd.html

[A22] 获取字符串长度
来源：http://dali.aibaodan.cn/Article/details/gt2wfoodyqs.html

Py:   len(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2fnjicygl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sysykeji.top/Article/details/gt2hhwxeeqa.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinqigufen.top/Article/details/gt2irqqtcft.html

TS:   s.length
来源：http://dali.bjfxy.top/Article/details/gt2lpmtjftd.html

Java: s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2iolcyswu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2uzwaqpzy.html

Ruby: s.length
来源：http://dali.iojbl.cn/Article/details/gt2bjlxwcvj.html

C#:   s.Length
来源：http://dali.fzhhl.top/Article/details/gt2ayavmglg.html

[A23] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2oahsnmzs.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2qptrgoeg.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yvedp.cn/Article/details/gt2ykzorldq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gt2weapxflf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenzaomai.com/Article/details/gt2tqrchnyn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gt2uykarmui.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.guannengcc.top/Article/details/gt2spacbads.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xinyue.icu/Article/details/gt2dkeahayd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guowangkeji.top/Article/details/gt2jraprzxc.html

[A24] 去除首尾空白
来源：http://dali.zhengqikj.top/Article/details/gt2enyhbwco.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sxryk.cn/Article/details/gt2qlpptvvh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.havefunace.top/Article/details/gt2lemdognp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gt2wpjjugzj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gt2fzdhvjkb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.vqdsnc.cn/Article/details/gt2hncqvkup.html

Go:   strings.TrimSpace(s)
来源：http://dali.aizwys.cn/Article/details/gt2mjdkdbsq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xylfe.cn/Article/details/gt2dlsimext.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gt2ittixdox.html

[A25] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gt2kwgaentk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.andypj.xyz/Article/details/gt2etqhkyfa.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxqvcbcl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gt2vogdaaey.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gt2onxwdrvn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhongyouzk.top/Article/details/gt2nuklkaae.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbbhwxkq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pengpengdd.cyou/Article/details/gt2suxqaikn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gt2gtdjfyfa.html

[A26] 类型转换总览
来源：http://dali.nanxuanxn.top/Article/details/gt2yxwudvii.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.mhx1999.top/Article/details/gt2gxsklppo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nwbrower.top/Article/details/gt2ecoczgsm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrkrvoah.html

TS:   Number() String() Boolean() x as number
来源：http://dali.iojbl.cn/Article/details/gt2qayprabz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gaohongyu789.top/Article/details/gt2pyoaxkow.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258.top/Article/details/gt2qlxxbdpm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jqgfzy.top/Article/details/gt2gwlwccxm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuxming.cn/Article/details/gt2ufhfwfjr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2gobnledg.html

B. 流程控制
来源：http://dali.havefunace.top/Article/details/gt2kaljkiug.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2yhcdkpwm.html

[B01] 条件判断 if / else
来源：http://dali.vqdsnc.cn/Article/details/gt2zyoiflhx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.meibo888.top/Article/details/gt2yfwxloic.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.iojbl.cn/Article/details/gt2gydzqgwq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2jcidnklr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gt2qlfduhgm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gt2lzsotsfg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cqqwz.cn/Article/details/gt2ctycharu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.c1oappe.top/Article/details/gt2ymcnknrj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gt2jggywlle.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgjzxhyy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sufxvd.cn/Article/details/gt2txwzwutv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenzaomai.com/Article/details/gt2vaihfcmj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gt2cnuljyvr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkaiuuxv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gt2mwveoujz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhoulong.xyz/Article/details/gt2wuhyzmhq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgoadnfv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gt2pcrzikbz.html

[B03] switch / match / case
来源：http://dali.cashguo.top/Article/details/gt2xuirpusz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gt2dodqnvak.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzummkhc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gt2nolawdiu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gt2ibfzvqdp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrgdpcw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yueranfly.top/Article/details/gt2anjynvkr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhongyouzk.top/Article/details/gt2kbvnacsa.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gt2clcgumro.html

[B04] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gt2yoykekrg.html

Py:   for i in range(10): print(i)
来源：http://dali.pycfn.com/Article/details/gt2fszohhva.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yvedp.cn/Article/details/gt2kwzxpnxi.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2rwwznmkn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gt2uofpzqok.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ppjwa.cn/Article/details/gt2jouedtiz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gt2twmtkpov.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sdofbjjc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gt2rapficxl.html

[B05] 遍历数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gt2aymgmdjm.html

Py:   for item in arr: print(item)
来源：http://dali.vqdsnc.cn/Article/details/gt2hbmbtdmz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvjurefe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gt2dnyfdaij.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2octvmrtd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xinyue.icu/Article/details/gt2rcxrgrjf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuanzx.com/Article/details/gt2ldhemzem.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yanxiufei.cn/Article/details/gt2plgvqtbr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daxiang520.top/Article/details/gt2cfovqgef.html

[B06] 遍历字典 / 对象
来源：http://dali.ydzc1.top/Article/details/gt2jvznifyi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sysykeji.top/Article/details/gt2bgxinyox.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yvedp.cn/Article/details/gt2jhslwlnk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gt2hernailt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gt2totewibh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhixingplan.top/Article/details/gt2jbamvujw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cashguo.top/Article/details/gt2nzwdyepj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxuanxn.top/Article/details/gt2hvvmuqih.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigfzy.top/Article/details/gt2igbmbknz.html

[B07] while 循环
来源：http://dali.jyoumei.cn/Article/details/gt2eheoezkd.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kiikdyjj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.redwolf501.top/Article/details/gt2iyqaufpg.html

JS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gt2clgcczpx.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gt2kvswbujv.html

Java: while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2paajaxre.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuanzx.com/Article/details/gt2wanussnt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ivvv.top/Article/details/gt2ekyszmwa.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqrcotvi.html

[B08] do-while（至少执行一次）
来源：http://dali.iojbl.cn/Article/details/gt2gwfcpobg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnxiangtu.top/Article/details/gt2luokovhz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2pgiasvic.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2cjfmhruh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2eflfedkw.html

Java: do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2lvkirzkq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gt2cauapexc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gt2kcdihbxc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2enxqfwub.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gt2hhercpsm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cucudq.cn/Article/details/gt2rfegjeiw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pztqzvjz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2gerwbzxt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2beeztbcr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2ysdrglqx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aizwys.cn/Article/details/gt2jnhxupmn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aizwys.cn/Article/details/gt2imwyruei.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gt2uzudydnp.html

[B10] 遍历同时拿索引
来源：http://dali.xylfe.cn/Article/details/gt2oubniqcp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhixingplan.top/Article/details/gt2znvzlbya.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jwelbapc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vogeaxvn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gt2gqghjrvc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gt2njwhroea.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zycfv.cn/Article/details/gt2gfjrlmyx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gt2ersgguih.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.vqdsnc.cn/Article/details/gt2pgfcokts.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gt2mwsaeilz.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gt2gdmvuepb.html

PHP:  range(0, 10, 2);
来源：http://dali.c1oappe.top/Article/details/gt2uotdafpt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zujfsyym.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2ozwioglp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sysykeji.top/Article/details/gt2ivnfhmoq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gt2mhpvpulx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gt2wpnzytez.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2diwqbhvh.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gt2hvwfjdrx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgufenzy.top/Article/details/gt2tcmsqmyv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzryculc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trbykoah.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2xxuxztyo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gt2bzexvnsj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gt2wlzijvew.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gt2mdwqxngo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gt2zoszcjas.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gt2wlndgrnx.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gt2yfccwtlb.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ijleapka.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gt2lwzuosdc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gt2jgbsnkji.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gt2pigbbfic.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cirmlqou.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gt2gljjejpt.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gt2wcypawlr.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gt2rylqtkio.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlcxhea.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gt2xoxsejuz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gt2tslrhfwp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2qpttkdsn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2vqblwqne.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ehwqpu.com/Article/details/gt2skdsrkvm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gt2fzmqekon.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2luvfprgc.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gt2awysznhh.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gt2fmjapzvz.html

PHP:  $a && $b || !$c
来源：http://dali.zycfv.cn/Article/details/gt2muekycju.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2rghphpnh.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2zvumdzdb.html

Java: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2nuqlyhlt.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2msshxyyx.html

Ruby: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2fcwwprvh.html

C#:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2yrzyljwv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgrwlqvq.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wezyjncz.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gt2bsjegjqh.html

JS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gt2lcbnqunc.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gt2nphxhbmg.html

Java: if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gt2tvicaabu.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gt2ighausap.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gt2ktxgnrdk.html

C#:   if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcrulijr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2dwipisxk.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzbjfhed.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2bqpxqzyc.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gt2farnclvj.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2vfkwsdod.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2cspmqbtj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2kvyqdvpe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2ezbenogi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbeeiwjr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gt2ozrfzhie.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gt2oyiluqrn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2iagkzhkr.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gt2huokzoug.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gt2madoeets.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gt2kzmsteag.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2eywqmrvz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2vbeuvhjn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxmzvkzn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iocmimnr.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gt2kinwtznv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gt2hdeebqjr.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gt2sgtqdhgr.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gt2krkqlnul.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gt2gdangwas.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gt2rbwlhmda.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cehqptae.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gt2xmsjddkr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sxryk.cn/Article/details/gt2theymhhd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2aeqykfiv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gt2gvojtrxv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfvgcjto.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gt2cnirlrrm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gt2oqikgocj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gt2glywkpza.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2topbhkhb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gt2jahkmxib.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gt2idqmndwi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2vqpvvxmb.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2yxgwyusa.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gt2wsxjbrjx.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gt2lwyopnmm.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gt2rtfkjano.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yonumen.top/Article/details/gt2oxrqrepv.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gt2zuunyfhb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gt2peskwytq.html

Go:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akiiyomv.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2qxtwvzmt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvtzajdg.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqjhboio.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gt2snhfinyz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxobdwxf.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2scpkkvpp.html


<!-- 参考信息 -->