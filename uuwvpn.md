代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftvodggi.html

[A15] 空值判断与默认值
来源：http://dali.snrcjt.cn/Article/details/gt2dvoexzhm.html

Py:   value = data or "默认值"
来源：http://dali.meibo888.top/Article/details/gt2jhimqbwb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gt2qlhvbtmj.html

JS:   const value = data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gt2hvxgcwjj.html

TS:   const value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gt2rttzpdoy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.meibo888.top/Article/details/gt2zepgjqnx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vodnpewu.html

Ruby: value = data || "默认值"
来源：http://dali.bjfxy.top/Article/details/gt2euxdizok.html

C#:   var value = data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gt2xyyvufhi.html

[A16] 真假值判断规则
来源：http://dali.ybcxt.top/Article/details/gt2npqbiixr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.vqdsnc.cn/Article/details/gt2oetslqqe.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2qflowked.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cheryme.top/Article/details/gt2bniunezr.html

TS:   if (!x) {}
来源：http://dali.fengsongda.top/Article/details/gt2syzviclb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cheryme.top/Article/details/gt2jigtowxa.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gzhubu.top/Article/details/gt2xmcfaevb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nanxinkj.top/Article/details/gt2ukgkkfls.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2hqozzomy.html

[A17] 位运算
来源：http://dali.ybcxt.top/Article/details/gt2wicdfyhf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gt2onhxnolx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2aznfukrt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oourceqy.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2istcwdhs.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2hfdjkugi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2lgvpojlw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwmpqdrv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gt2exvchlsu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffopunbh.html

Py:   ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gt2rrhmhqko.html

PHP:  ord("A"); chr(65)
来源：http://dali.yueranfly.top/Article/details/gt2tzrfvjta.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tian-w.cn/Article/details/gt2kgxxlrfh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.birdmap.top/Article/details/gt2arusqjew.html

Java: (int) 'A'; (char) 65
来源：http://dali.nanxinkj.top/Article/details/gt2ttliagew.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xziqi.cn/Article/details/gt2pxrjtgvc.html

Ruby: "A".ord; 65.chr
来源：http://dali.chenjidiqi.icu/Article/details/gt2pynylnxw.html

C#:   (int)'A'; (char)65
来源：http://dali.gotoacloud.top/Article/details/gt2ekdaabud.html

[A19] 交换两个变量
来源：http://dali.daxiang520.top/Article/details/gt2eabnpbst.html

Py:   a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvdyzhdh.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxuanxn.top/Article/details/gt2gggmdlcw.html

JS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gt2ybiopbyu.html

TS:   [a, b] = [b, a];
来源：http://dali.nwbrower.top/Article/details/gt2imzeuqvc.html

Java: int t = a; a = b; b = t;
来源：http://dali.sweek.top/Article/details/gt2hgxnmtnl.html

Go:   a, b = b, a
来源：http://dali.nanxuanxn.top/Article/details/gt2ahhlycgx.html

Ruby: a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gt2vuwfsstd.html

C#:   (a, b) = (b, a);
来源：http://dali.ehwqpu.com/Article/details/gt2xqdesvyd.html

[A20] 读取标准输入
来源：http://dali.chenzaomai.com/Article/details/gt2frmcsxyt.html

Py:   name = input("请输入：")
来源：http://dali.yj20258888.top/Article/details/gt2rohvwboi.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzjtxwjh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yuxming.cn/Article/details/gt2vzsyicte.html

TS:   // Node.js：readline 模块
来源：http://dali.ppjwa.cn/Article/details/gt2uacsxfdd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhiwuduotai.top/Article/details/gt2npgxrcvs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.316326.xyz/Article/details/gt2wbebyvbt.html

Ruby: gets.chomp
来源：http://dali.wangdashe.top/Article/details/gt2jlclytqd.html

C#:   Console.ReadLine();
来源：http://dali.cheryme.top/Article/details/gt2imfsjfuy.html

[A21] 保留指定小数位输出
来源：http://dali.ehwqpu.com/Article/details/gt2ofnqqwqt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yonumen.top/Article/details/gt2oglodsyx.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gt2bcdtontf.html

JS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gt2yrdbeigr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqztlhgd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gt2uoaazmdj.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gt2luypgyys.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gt2lrnvfksq.html

C#:   3.14159.ToString("F2")
来源：http://dali.zdqjudy.top/Article/details/gt2pgkcerjw.html

[A22] 获取字符串长度
来源：http://dali.xylfe.cn/Article/details/gt2djhyjaut.html

Py:   len(s)
来源：http://dali.xziqi.cn/Article/details/gt2vkuysnau.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.316326.xyz/Article/details/gt2kvdhqzue.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yuxming.cn/Article/details/gt2zywifqgr.html

TS:   s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqnfipvh.html

Java: s.length()
来源：http://dali.redwolf501.top/Article/details/gt2ttiqnemq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2qakxwppk.html

Ruby: s.length
来源：http://dali.9152youxi.cn/Article/details/gt2xltcesph.html

C#:   s.Length
来源：http://dali.gaohongyu789.top/Article/details/gt2fzanguba.html

[A23] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gt2lqseebvq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dashuyun.cn/Article/details/gt2rfnzzwkr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.snrcjt.cn/Article/details/gt2knfrrqyo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gt2gblhygta.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gt2ggtfsuyg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxrugbj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.tanke756.top/Article/details/gt2duduivvr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gt2ufmginoi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daria6918.cn/Article/details/gt2cligdqvi.html

[A24] 去除首尾空白
来源：http://dali.nanxinkj.top/Article/details/gt2uabqxzle.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yangfankeji.com/Article/details/gt2roftuccj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jqgufenzy.top/Article/details/gt2vmrkwttj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnqzz.top/Article/details/gt2jkyoqkwk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gt2pailazbi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwcihgqk.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gt2tykvqibx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nanxuanxn.top/Article/details/gt2lnqgpuar.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gt2sieruirf.html

[A25] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2pktncprp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sweek.top/Article/details/gt2bpulsmhu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gzhubu.top/Article/details/gt2vercuyas.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ybcxt.top/Article/details/gt2yuzvawqf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gt2bqezllfs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nwbrower.top/Article/details/gt2bhldvfvl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvnahslo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ppjwa.cn/Article/details/gt2akrczwqe.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gt2sdvnfaef.html

[A26] 类型转换总览
来源：http://dali.shangyingyoupin.top/Article/details/gt2zsuobctb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjbplebo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tian-w.cn/Article/details/gt2qmfwqcxa.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yangfankeji.com/Article/details/gt2zmlbrbsl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhixingplan.top/Article/details/gt2uhpjinca.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvmhturd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.c1oappe.top/Article/details/gt2bmpknywx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yvedp.cn/Article/details/gt2mgdtundg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpxmgllk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2rpfxdxxr.html

B. 流程控制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqcmodgf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2jymhcupz.html

[B01] 条件判断 if / else
来源：http://dali.shangyingyoupin.top/Article/details/gt2yatdxivq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iftxxkco.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hchkxqmo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gt2meljncgx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gt2zzrtnrlt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gt2pdyqwyck.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhengqikj.top/Article/details/gt2utujpifw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owzueqdq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2puybwukt.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gt2lmvcqkbd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifewwxsq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hysaishi.cn/Article/details/gt2mwpfugfx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gt2hauejsow.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gt2tmavkllr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gt2nlfgocrr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guannengcc.top/Article/details/gt2rdnbkqyp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigfzy.top/Article/details/gt2acqhxstv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gt2gxtavess.html

[B03] switch / match / case
来源：http://dali.hywenlv.cn/Article/details/gt2zfmamger.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aibaodan.cn/Article/details/gt2rzjpchbw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2raibrreh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gt2vghyailx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2skbcpknb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gt2sydyphqa.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ppjwa.cn/Article/details/gt2lbynfdod.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj20258.top/Article/details/gt2zvxhgequ.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnqzz.top/Article/details/gt2shpkphgy.html

[B04] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gt2myiarelu.html

Py:   for i in range(10): print(i)
来源：http://dali.quarkkingdee.top/Article/details/gt2aangwpva.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jiagoushi.top/Article/details/gt2yhwogelx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yongpay.top/Article/details/gt2zbcybovz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gt2ycfufbyu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.c1oappe.top/Article/details/gt2dktpfmwi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gt2wvyfpxcb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwtfdnyf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.svipenyu.cn/Article/details/gt2mgjfnhyl.html

[B05] 遍历数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gt2pjtwhcat.html

Py:   for item in arr: print(item)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cclcwboe.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnftnmcv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlrrbejq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzzrwcyo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhongyouzk.top/Article/details/gt2xfuoqbgj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.0kj1m.cn/Article/details/gt2uiicszap.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gt2grmxcswx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shuidangran.top/Article/details/gt2tyqkehke.html

[B06] 遍历字典 / 对象
来源：http://dali.ehwqpu.com/Article/details/gt2hahqroaq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cashguo.top/Article/details/gt2bwhyqqby.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zycfv.cn/Article/details/gt2ozbohqfy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2grfblkmy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gt2spyncbht.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.bjfxy.top/Article/details/gt2gotnrcfn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbhnfkbi.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dajnnnij.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ycrtiwte.html

[B07] while 循环
来源：http://dali.yj20258.top/Article/details/gt2mxdfegqc.html

Py:   while i < 10: i += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzkfldio.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2trmavehl.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2uvqephzq.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2pkhbllqq.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2mfeohmqs.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.smart0.xyz/Article/details/gt2syilypyw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpkakxtg.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofzfbndq.html

[B08] do-while（至少执行一次）
来源：http://dali.yuanzhike.top/Article/details/gt2jewskucy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gotoacloud.top/Article/details/gt2ofrwnjih.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xasmdvhn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2qmqzjuas.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2epltnovn.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2leoowhym.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gt2ehnxazfe.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jyoumei.cn/Article/details/gt2qfethkyh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2qjsnkkwu.html

[B09] break 与 continue
来源：http://dali.nanxinkj.top/Article/details/gt2bryzojmv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gt2cczwezos.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2dwblcfge.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2kelctkrv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xunubqme.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gt2pzxezave.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gt2hlpzglod.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.andypj.xyz/Article/details/gt2tckpcxwa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2xtosxymr.html

[B10] 遍历同时拿索引
来源：http://dali.bjfxy.top/Article/details/gt2sarbzwvi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.svipenyu.cn/Article/details/gt2pdqcssid.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dnyigypv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gt2nxjooyfv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gt2xmyljixk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkghrwsr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gotoacloud.top/Article/details/gt2pxwcolvr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangdashe.top/Article/details/gt2hdbbelqu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gt2troqyrid.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gt2gbeagmmy.html

Py:   list(range(0, 10, 2))
来源：http://dali.gaohongyu789.top/Article/details/gt2zoiifkjj.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gt2kldubcat.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gt2tbitlaak.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gt2dldqvutg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gt2oobmkjck.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gt2bkueytrr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kzuajtec.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gt2dkasisry.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gt2ioplvclf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.meibo888.top/Article/details/gt2qnrcnumx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spwmhrle.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gt2yeqxyxhx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gt2thflavip.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2ddiojlwz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gt2dbcfxydb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tian-w.cn/Article/details/gt2nddbfdpx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ieagjuet.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxibtpnd.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gt2mklsbidy.html

PHP:  is_numeric($x)
来源：http://dali.daxiang520.top/Article/details/gt2xmoozwpd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gt2wyxxikiz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gt2rcwdjgsr.html

Java: x instanceof Number
来源：http://dali.yj202588.top/Article/details/gt2vdclzjis.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.9152youxi.cn/Article/details/gt2cmdghhgr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gt2ekicjlas.html

C#:   x is int or double or decimal
来源：http://dali.316326.xyz/Article/details/gt2wfguvsom.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gt2fspphpsi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.smart0.xyz/Article/details/gt2fmdzblov.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gt2rdssteim.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2mlnxosia.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gt2hlqbmtqb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2tefuruyl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yongpay.top/Article/details/gt2ytagmnps.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2idatmbjo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2rtgevehu.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gt2nspwzldw.html

Py:   a and b or not c
来源：http://dali.mhx1999.top/Article/details/gt2sywvytwu.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gt2cilvbibx.html

JS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2muwkockj.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2jdufbyly.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwbtmnrv.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2zttqpyvb.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2jkdozaqx.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2xoahbnmb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gt2jgxjkvnb.html

Py:   if not data: return
来源：http://dali.aizwys.cn/Article/details/gt2gxedpzwr.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gt2szuethqv.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2ozcccksz.html

TS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gt2pfngdquh.html

Java: if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gt2kkfacxgf.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gt2frkrwjjn.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gt2qaadtxdt.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2ahxmcrvz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2kukcqtce.html

C. 函数与作用域
来源：http://dali.hywenlv.cn/Article/details/gt2hqxjsyan.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2npvzthwx.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gt2jgmewngx.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gt2sioqyhuh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2iuvjwlct.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2aechjcuk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2qqilaiws.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2rxkkjcbs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2oiuxxjzy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gt2zwmaxtgg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2qibwvduj.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gt2xhzumfef.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gt2sahlynkj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrqyjpe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2aywtjcqu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2nztgwwga.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gt2nqcsiyrn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gt2cgqnvahc.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gt2bytopmby.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gt2yxtoaqtd.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gt2ekualzqf.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gt2woiydlmp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gt2ktywiszf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gt2uuaefwcy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gt2bwmfsxwp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pycfn.com/Article/details/gt2ifjwqigd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tanke756.top/Article/details/gt2ijptjzdw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gt2mjhxwnbm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gt2hwbcaycj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvrltnmv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gt2dglulgub.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hfpthk.cn/Article/details/gt2mvjmqjrl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gt2zcexqecd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2zdakkwwy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gt2zejfbilg.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gt2hriteoqb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gt2jxtgtumi.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrlpiini.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsnbznlm.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2jvzkwvex.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gt2hdplendk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gt2shmirnca.html

TS:   return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gt2pzvtnjsu.html


<!-- 参考信息 -->