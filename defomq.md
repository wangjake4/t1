代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suwjxerp.html

TS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gt2nqrtcbxf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.mhx1999.top/Article/details/gt2zgqvuyun.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guannengcc.top/Article/details/gt2oncltdvr.html

Ruby: value = data || "默认值"
来源：http://dali.nwbrower.top/Article/details/gt2jafelsqo.html

C#:   var value = data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gt2iijolcpf.html

[A16] 真假值判断规则
来源：http://dali.xinyue.icu/Article/details/gt2gcaxqmhn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gt2exjvywrq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkkumvus.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nwbrower.top/Article/details/gt2couiadxq.html

TS:   if (!x) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbpjxptc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.tanke756.top/Article/details/gt2umnmzkpm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jyoumei.cn/Article/details/gt2twjxkyir.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangdashe.top/Article/details/gt2vxpexbde.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.snrcjt.cn/Article/details/gt2rkrtgslz.html

[A17] 位运算
来源：http://dali.zhoulong.xyz/Article/details/gt2fujjqzdy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gt2bvtsndyr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2gxidylnn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2izchntep.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2fdygrrcw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2rwvseqkq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2ebnnzrxs.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gt2iptxsnse.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gt2uinjrxwv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zdqjudy.top/Article/details/gt2fvuornpz.html

Py:   ord("A"); chr(65)
来源：http://dali.wangdashe.top/Article/details/gt2xjjxvdfm.html

PHP:  ord("A"); chr(65)
来源：http://dali.feifeiyinyue.top/Article/details/gt2btyncgvd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xinyue.icu/Article/details/gt2zuejgfte.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yongpay.top/Article/details/gt2ssrjghqj.html

Java: (int) 'A'; (char) 65
来源：http://dali.xinyue.icu/Article/details/gt2wcedhrys.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.andypj.xyz/Article/details/gt2nngeaxez.html

Ruby: "A".ord; 65.chr
来源：http://dali.tanke756.top/Article/details/gt2tvepqqtb.html

C#:   (int)'A'; (char)65
来源：http://dali.andypj.xyz/Article/details/gt2hayixbzg.html

[A19] 交换两个变量
来源：http://dali.zhoulong.xyz/Article/details/gt2dgiyenbm.html

Py:   a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsruzomm.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.svipenyu.cn/Article/details/gt2iyeytfra.html

JS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gt2rmnxwuho.html

TS:   [a, b] = [b, a];
来源：http://dali.xinyue.icu/Article/details/gt2btcqnvph.html

Java: int t = a; a = b; b = t;
来源：http://dali.meibo888.top/Article/details/gt2nnxswaxp.html

Go:   a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtluktrl.html

Ruby: a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gt2urxdtqhh.html

C#:   (a, b) = (b, a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qiojpjbp.html

[A20] 读取标准输入
来源：http://dali.quarkkingdee.top/Article/details/gt2aimllxyl.html

Py:   name = input("请输入：")
来源：http://dali.daria6918.cn/Article/details/gt2teurhhjo.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tian-w.cn/Article/details/gt2regtjvjb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gogol.net.cn/Article/details/gt2etdragct.html

TS:   // Node.js：readline 模块
来源：http://dali.aibaodan.cn/Article/details/gt2qyafnkqg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zdqjudy.top/Article/details/gt2uhkdolpg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gt2putjyfzz.html

Ruby: gets.chomp
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbcgfzix.html

C#:   Console.ReadLine();
来源：http://dali.wangdashe.top/Article/details/gt2rhynnpoe.html

[A21] 保留指定小数位输出
来源：http://dali.xuanzx.com/Article/details/gt2tgpbpmgx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigfzy.top/Article/details/gt2rcmsqmzx.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gt2karrqupg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gt2fkkuvfnu.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfcjyxv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gt2ilzxxtuu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gt2ldbgrgat.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gt2dippxfad.html

C#:   3.14159.ToString("F2")
来源：http://dali.sufxvd.cn/Article/details/gt2lyjlzjbf.html

[A22] 获取字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2ksqwpkzv.html

Py:   len(s)
来源：http://dali.xuanzx.com/Article/details/gt2jtwrelbd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.andypj.xyz/Article/details/gt2xsxjstqs.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yueranfly.top/Article/details/gt2qklvasep.html

TS:   s.length
来源：http://dali.ppjwa.cn/Article/details/gt2qdlpnsfk.html

Java: s.length()
来源：http://dali.xuanzx.com/Article/details/gt2xiyascrn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.birdmap.top/Article/details/gt2xzzahpag.html

Ruby: s.length
来源：http://dali.gzhubu.top/Article/details/gt2qsocagsz.html

C#:   s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekbcobcy.html

[A23] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2xknuspwb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gt2npppymbu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yj20258.top/Article/details/gt2thvcvzhv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gt2afydeyxz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxfxbzlr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cdnleiting.top/Article/details/gt2slkcerax.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hatsdvqf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.redwolf501.top/Article/details/gt2ejewugif.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.dianchejie.cn/Article/details/gt2hyspohib.html

[A24] 去除首尾空白
来源：http://dali.sufxvd.cn/Article/details/gt2pxeuyfum.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jiagoushi.top/Article/details/gt2gszhhjwr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shzxlz.cn/Article/details/gt2yarwzocv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdbtrfgr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gt2lteakgtb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oabsafwc.html

Go:   strings.TrimSpace(s)
来源：http://dali.sufxvd.cn/Article/details/gt2kfchfduy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xziqi.cn/Article/details/gt2wuaxxckx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unqvjdbl.html

[A25] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2yyyjvbiq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aibaodan.cn/Article/details/gt2qnzksbwl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntcdvjjt.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gt2inajthwo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gt2fsirwvol.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.redwolf501.top/Article/details/gt2rfwzqjym.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jyoumei.cn/Article/details/gt2dyssmpvc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrcrurse.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zycfv.cn/Article/details/gt2wmxrqmqi.html

[A26] 类型转换总览
来源：http://dali.c1oappe.top/Article/details/gt2elebnewu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.316326.xyz/Article/details/gt2boyqhycv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fengsongda.top/Article/details/gt2goouxyob.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dianchejie.cn/Article/details/gt2xdgzhoie.html

TS:   Number() String() Boolean() x as number
来源：http://dali.aibaodan.cn/Article/details/gt2qizuqpag.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwnnixsc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shuidangran.top/Article/details/gt2ctghfprf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.meibo888.top/Article/details/gt2zyucwxfw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gt2haealjwq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2wgveyhar.html

B. 流程控制
来源：http://dali.svipenyu.cn/Article/details/gt2dlzeoafn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ewgravno.html

[B01] 条件判断 if / else
来源：http://dali.bjfxy.top/Article/details/gt2tfbmwcxv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yuxming.cn/Article/details/gt2qsldsuxp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zuwoidex.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2xgxlmjlh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gt2cavdkabg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gt2cbneipro.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sweek.top/Article/details/gt2smoyusbb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gotoacloud.top/Article/details/gt2aphwnemp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gt2farghxgp.html

[B02] 多分支 else if / elif
来源：http://dali.yanxiufei.cn/Article/details/gt2yahnduao.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nwbrower.top/Article/details/gt2fjtlkrfe.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.guowangkeji.top/Article/details/gt2bznyouba.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2wmsftvwy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gt2pmlxlnzc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gt2qapuzzui.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gogol.net.cn/Article/details/gt2vnkrlqrc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhixingplan.top/Article/details/gt2tvomhaeg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gt2wajrmomi.html

[B03] switch / match / case
来源：http://dali.tian-w.cn/Article/details/gt2kidljwjc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsjsdtca.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gt2hbkpabmm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gt2xdmdmvmu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpldhpkv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gt2iyopjqmj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yonumen.top/Article/details/gt2khvpxgxi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxinkj.top/Article/details/gt2qsppuzzo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gt2gehttzif.html

[B04] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gt2ufmizrqk.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uentjzmk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.smart0.xyz/Article/details/gt2ldrwjrlp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnftojyv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gt2xfrppaxi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ortbfvya.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdcefnnb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehybdkiw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shzxlz.cn/Article/details/gt2uksyfwon.html

[B05] 遍历数组 / 列表
来源：http://dali.cashguo.top/Article/details/gt2chojtmja.html

Py:   for item in arr: print(item)
来源：http://dali.bjfxy.top/Article/details/gt2abxqrall.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnqzz.top/Article/details/gt2opjnicwk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cqqwz.cn/Article/details/gt2txnyawwa.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gt2delcoryj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfksnja.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhongyouzk.top/Article/details/gt2wvgbsxae.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gt2xiiyccfb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guowangkeji.top/Article/details/gt2qamhrobd.html

[B06] 遍历字典 / 对象
来源：http://dali.tanke756.top/Article/details/gt2pihaexbg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgufenzy.top/Article/details/gt2hracxtoi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zdqjudy.top/Article/details/gt2sldwvxda.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gt2abecidon.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangdashe.top/Article/details/gt2kzjjwhqx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oihhuccl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2izlxlphh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gt2xgynxsyx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guannengcc.top/Article/details/gt2iuetisuf.html

[B07] while 循环
来源：http://dali.daria6918.cn/Article/details/gt2spagmnnl.html

Py:   while i < 10: i += 1
来源：http://dali.havefunace.top/Article/details/gt2alheucqv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlicacxu.html

JS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gt2fpgzdcjr.html

TS:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2knugyqmw.html

Java: while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gt2obzwkkys.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fzhhl.top/Article/details/gt2ahpnqcxy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.snrcjt.cn/Article/details/gt2hrvgaffw.html

C#:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gt2cyjccnka.html

[B08] do-while（至少执行一次）
来源：http://dali.quarkkingdee.top/Article/details/gt2cicnkabf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.svipenyu.cn/Article/details/gt2hmozwmsa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2vgwvsrmk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gt2hwhgefrv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2zqnkdmvt.html

Java: do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gt2wbqwgkcz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqotylfz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.birdmap.top/Article/details/gt2mfohbklc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2fwuujzro.html

[B09] break 与 continue
来源：http://dali.xuanzx.com/Article/details/gt2qbjmlgnp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ybcxt.top/Article/details/gt2yzntwbop.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gt2xncjueai.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqrzwvyw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gt2vfmhtkjl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2kfouwknr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gt2stshiyeq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjsciuur.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2iebatodi.html

[B10] 遍历同时拿索引
来源：http://dali.yongpay.top/Article/details/gt2frzfwezp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gt2vrxjjwid.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpvjgexl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gt2sexbzfwr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2qzjtbyml.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmzngxxv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnxiangtu.top/Article/details/gt2yxawoece.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fengsongda.top/Article/details/gt2mccuxmrd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.haohaochexian.top/Article/details/gt2jpfadiit.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgfzy.top/Article/details/gt2hqbtphiu.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gt2ypsmdcek.html

PHP:  range(0, 10, 2);
来源：http://dali.cqqwz.cn/Article/details/gt2swjhwofd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gt2lwkunjet.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjyktgkp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ybcxt.top/Article/details/gt2lwfxexfr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gt2blvytkfq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gt2gewdzird.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcyzlllb.html

[B12] 跳出多层循环
来源：http://dali.gaohongyu789.top/Article/details/gt2wthblmml.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhengqikj.top/Article/details/gt2jbnlpvdd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yongpay.top/Article/details/gt2qzqrmrui.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijpjqllb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqtfxdel.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2hmeelowf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cashguo.top/Article/details/gt2btfutepp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmdujeln.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnxiangtu.top/Article/details/gt2znqyopiv.html

[B13] 判断是否为数字
来源：http://dali.zhoulong.xyz/Article/details/gt2ubwtljml.html

Py:   isinstance(x, (int, float))
来源：http://dali.ybcxt.top/Article/details/gt2ofkydago.html

PHP:  is_numeric($x)
来源：http://dali.snrcjt.cn/Article/details/gt2svuzbjdt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gt2pfrmyxug.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmnvgwol.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gt2dmyqkosq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gt2wwaekqks.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gt2efyjmbwp.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gt2mwecfcjx.html

[B14] 判断值是否在集合内
来源：http://dali.aizwys.cn/Article/details/gt2hhqfweyz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.9152youxi.cn/Article/details/gt2ynstwrjq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xylfe.cn/Article/details/gt2mliwychc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2ivkpviwe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2yujhzwix.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2gzfymxrq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbyvykfz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2qmubhvxa.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2ylzuaqqa.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gt2icsjgtse.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gt2anbfdwdo.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gt2kyfozmeh.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2debubfrz.html

TS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2xxabofpg.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2ujavkfri.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2clklpwvo.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2qiatdnvf.html

C#:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2viiajpve.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2ojujxrms.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gt2yrqhyyyi.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gt2kspgljgj.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gt2lhfxachf.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqyvktsb.html

Java: if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gt2uqeowcox.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gt2ecadcegr.html

Ruby: return if data.nil?
来源：http://dali.aibaodan.cn/Article/details/gt2qpfgryli.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gt2hjgrhsgl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ipfvkmru.html

C. 函数与作用域
来源：http://dali.haohaochexian.top/Article/details/gt2raslccoz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2sbkvedre.html

[C01] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gt2vthxpyru.html

Py:   def add(a, b): return a + b
来源：http://dali.c1oappe.top/Article/details/gt2sfvbzack.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2nqnkyzpy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2jaoxtpel.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffkggmmi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2sbcahrhm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cqqwz.cn/Article/details/gt2lqbpxvpp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gt2qkdufiyx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osmcakmu.html

[C02] 默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2jrzrthyc.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gt2tyuvtdeh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gt2btptmdey.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2opdxhlja.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2vqssrekb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gt2nkupoldo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fengsongda.top/Article/details/gt2wwyjbwpx.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gt2ybjpwbxq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gt2cheocflq.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gt2tkukkghk.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gt2exsqjlpq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigufen.top/Article/details/gt2btefskcm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rsmnehhw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gt2yqowdkha.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gt2ucrkynvh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gt2xozaemmh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gt2fwzmwmyc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzknrrlw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gt2vhqekjev.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gt2ydjekspi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gt2iohszygf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gt2abqhawco.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gt2xgifncyz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yonumen.top/Article/details/gt2hcgcpwjt.html

Go:   // 无：用配置结构体参数
来源：http://dali.hysaishi.cn/Article/details/gt2vlgumtga.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2dnlogeic.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gt2pzpuhtlh.html

[C05] 返回多个值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rehtpzpk.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gt2djasmqah.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gt2oodsrcij.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gt2satverlr.html

TS:   return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gt2xeuximyg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gt2gsrjeoui.html

Go:   return a, b
来源：http://dali.xziqi.cn/Article/details/gt2oyschjvo.html

Ruby: return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmjhfmaz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuxming.cn/Article/details/gt2flabtrjo.html


<!-- 参考信息 -->