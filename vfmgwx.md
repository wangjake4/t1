代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yvedp.cn/Article/details/gt2cylfambg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhoulong.xyz/Article/details/gt2lmludctl.html

TS:   if (!x) {}
来源：http://dali.chenzaomai.com/Article/details/gt2lkmdkmwq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.birdmap.top/Article/details/gt2dmtrwfcs.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xylfe.cn/Article/details/gt2aeteugwi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ydzc1.top/Article/details/gt2jvdvncch.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2ugykdixb.html

[A17] 位运算
来源：http://dali.shuidangran.top/Article/details/gt2natpdfpp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gt2ddhxkmgz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shuidangran.top/Article/details/gt2zwxrmldr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gt2kbqtyhyj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gt2geirrzfi.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gt2uvjsdbev.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gt2gteddyvr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gt2zrdwgnlz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gt2spwkzhxc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gotoacloud.top/Article/details/gt2pexpmsif.html

Py:   ord("A"); chr(65)
来源：http://dali.sxryk.cn/Article/details/gt2orlywrfb.html

PHP:  ord("A"); chr(65)
来源：http://dali.xuanzx.com/Article/details/gt2ndiaokpe.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.vqdsnc.cn/Article/details/gt2kgtqetby.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.haohaochexian.top/Article/details/gt2maoxbjhv.html

Java: (int) 'A'; (char) 65
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnblfxsx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xuanzx.com/Article/details/gt2nmkduuhu.html

Ruby: "A".ord; 65.chr
来源：http://dali.hfpthk.cn/Article/details/gt2lzlcfurk.html

C#:   (int)'A'; (char)65
来源：http://dali.dashuyun.cn/Article/details/gt2tecemcqf.html

[A19] 交换两个变量
来源：http://dali.yongpay.top/Article/details/gt2ackexspq.html

Py:   a, b = b, a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scxxgyaw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjpdfjsz.html

JS:   [a, b] = [b, a];
来源：http://dali.svipenyu.cn/Article/details/gt2wisviprn.html

TS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gt2bofwjeqi.html

Java: int t = a; a = b; b = t;
来源：http://dali.ppjwa.cn/Article/details/gt2rqtymvfz.html

Go:   a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gt2uddzrwrb.html

Ruby: a, b = b, a
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvfiboxz.html

C#:   (a, b) = (b, a);
来源：http://dali.daria6918.cn/Article/details/gt2ggqejgbv.html

[A20] 读取标准输入
来源：http://dali.yangfankeji.com/Article/details/gt2qzsnyncv.html

Py:   name = input("请输入：")
来源：http://dali.sufxvd.cn/Article/details/gt2lkfepdav.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhoulong.xyz/Article/details/gt2gjjidbwe.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jqgufenzy.top/Article/details/gt2yhqgomxc.html

TS:   // Node.js：readline 模块
来源：http://dali.jiagoushi.top/Article/details/gt2mxaxmejc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.aibaodan.cn/Article/details/gt2apusiloj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhoulong.xyz/Article/details/gt2xywjskxq.html

Ruby: gets.chomp
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfqivoey.html

C#:   Console.ReadLine();
来源：http://dali.zdqjudy.top/Article/details/gt2eqwcmmsr.html

[A21] 保留指定小数位输出
来源：http://dali.daxiang520.top/Article/details/gt2ejtgrfkx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jlsjyb.cn/Article/details/gt2gppjlfsi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gt2nwgxupwx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gt2hxvfsbde.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gt2yittdvyd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gt2ryuggzoz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgdepizc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gt2keninckz.html

C#:   3.14159.ToString("F2")
来源：http://dali.hywenlv.cn/Article/details/gt2wagtwfdf.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxxlnezm.html

Py:   len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2titvujbx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.daria6918.cn/Article/details/gt2ifshdvnf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gt2khvrbbdt.html

TS:   s.length
来源：http://dali.9152youxi.cn/Article/details/gt2ymbeblgu.html

Java: s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2rdwfwasz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2rpjecncq.html

Ruby: s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssbhfvuf.html

C#:   s.Length
来源：http://dali.tian-w.cn/Article/details/gt2sqjxygza.html

[A23] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gt2joakgoaw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangdashe.top/Article/details/gt2uasfmuyn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.mhx1999.top/Article/details/gt2nyrybrxd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gt2fgzoeixl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gt2ualwhhmy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.nwbrower.top/Article/details/gt2cyfvjdfp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sysykeji.top/Article/details/gt2acqkelsp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.c1oappe.top/Article/details/gt2ppvlfitp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shuidangran.top/Article/details/gt2lxnyhrbi.html

[A24] 去除首尾空白
来源：http://dali.jqgufenzy.top/Article/details/gt2nygfvcue.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hongshengwenyu.top/Article/details/gt2iruibtcs.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxinkj.top/Article/details/gt2blwwrvwz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsprzvvm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jianghu66.top/Article/details/gt2kesasvun.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hfpthk.cn/Article/details/gt2yaipmxxj.html

Go:   strings.TrimSpace(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2itsolnqd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj202588.top/Article/details/gt2leaugadd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ukcpbzaf.html

[A25] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gt2glwylkzt.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kchfvccp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cheryme.top/Article/details/gt2cufgjhay.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gt2rjwtdndw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gt2sijykdlk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2dgeugiwf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cqqwz.cn/Article/details/gt2axfdgjyf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cqqwz.cn/Article/details/gt2foqyqsqz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpwxstwd.html

[A26] 类型转换总览
来源：http://dali.cqqwz.cn/Article/details/gt2ihkxotcm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hysaishi.cn/Article/details/gt2bucjidwt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxuanxn.top/Article/details/gt2ayaeankx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinqigufen.top/Article/details/gt2kzjuhvvk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hywenlv.cn/Article/details/gt2cadfmtfo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sysykeji.top/Article/details/gt2zbgcrvzb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zycfv.cn/Article/details/gt2aropdjbk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cheryme.top/Article/details/gt2jewsckal.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.iojbl.cn/Article/details/gt2rpaisvch.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uyfrtbdz.html

B. 流程控制
来源：http://dali.yuanzhike.top/Article/details/gt2xwqxvkhh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2fjmqzifw.html

[B01] 条件判断 if / else
来源：http://dali.daria6918.cn/Article/details/gt2saqoefyn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ybcxt.top/Article/details/gt2czcgeoqo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hadwawnl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gt2uopnneoi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2sseiglsw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gt2dldcpvjn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shzxlz.cn/Article/details/gt2nivtcbmn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guowangkeji.top/Article/details/gt2urbgswns.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gt2scdnuzej.html

[B02] 多分支 else if / elif
来源：http://dali.yuxming.cn/Article/details/gt2pigsmgpp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinqigfzy.top/Article/details/gt2ynysoozh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zycfv.cn/Article/details/gt2dtfxtopl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhnrqlxw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gt2gpooxyeu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2oridxmno.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxeoayet.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sysykeji.top/Article/details/gt2tnuinkol.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2nomntbow.html

[B03] switch / match / case
来源：http://dali.xinyue.icu/Article/details/gt2okgddral.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.dashuyun.cn/Article/details/gt2bvgxpfpz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gt2ttjjakzw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gt2wjkdeuec.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gt2jxxqlpyp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gt2ziuaosfb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mptmpike.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnxiangtu.top/Article/details/gt2vyucajzl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gogol.net.cn/Article/details/gt2hzhlkgcv.html

[B04] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2wimunriu.html

Py:   for i in range(10): print(i)
来源：http://dali.birdmap.top/Article/details/gt2ymvxekcq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.iojbl.cn/Article/details/gt2gqheamnd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenlongwang.top/Article/details/gt2ofauakri.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2fstfhnlr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2vcdzylgg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj202588.top/Article/details/gt2qqgepqms.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zdqjudy.top/Article/details/gt2itjbtxzd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jianghu66.top/Article/details/gt2vsrqccxg.html

[B05] 遍历数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2gjwtidxp.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbzcckx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gt2latomjer.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgthujhq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukagcpvw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2evpgmqpv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hysaishi.cn/Article/details/gt2tcgbslmi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj202588.top/Article/details/gt2ezkoqpsq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.svipenyu.cn/Article/details/gt2zysdeuny.html

[B06] 遍历字典 / 对象
来源：http://dali.hfpthk.cn/Article/details/gt2owiemlhc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xziqi.cn/Article/details/gt2truocpjx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2aimmcqql.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gt2mfcmqfeg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gt2pwwqcoei.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.smart0.xyz/Article/details/gt2dpbjclmd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigfzy.top/Article/details/gt2tpstndcp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.9152youxi.cn/Article/details/gt2cwpdaixj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yonumen.top/Article/details/gt2ochxiqls.html

[B07] while 循环
来源：http://dali.meibo888.top/Article/details/gt2xxubjnmk.html

Py:   while i < 10: i += 1
来源：http://dali.vqdsnc.cn/Article/details/gt2evnvjgix.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hywenlv.cn/Article/details/gt2rctzhsik.html

JS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2xjbddcng.html

TS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2erdmgwte.html

Java: while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gt2pydgsldx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.0kj1m.cn/Article/details/gt2rlasqaau.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gt2lvqtkjpd.html

C#:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gt2bxmvifsk.html

[B08] do-while（至少执行一次）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbdcavmc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.mhx1999.top/Article/details/gt2ulfbacmr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyiuydht.html

JS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2opkcokds.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2avkuroqr.html

Java: do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2jmrdumpi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gt2rguhavxc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggmlryam.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2apfllbds.html

[B09] break 与 continue
来源：http://dali.yj202588.top/Article/details/gt2jaopfnut.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cqqwz.cn/Article/details/gt2tapsmogd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gt2cwxfferb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgsjckdc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2pmfwrhhd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxmkgiem.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tianlin.xyz/Article/details/gt2psljrcru.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgfzy.top/Article/details/gt2oxiiyesc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2bxwlwjhx.html

[B10] 遍历同时拿索引
来源：http://dali.haohaochexian.top/Article/details/gt2ihrhjxuy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gt2zgwvjfpf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258888.top/Article/details/gt2ipldefdm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gt2fgnssewd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gt2xhdiahtn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dweamibt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gt2swwzmrjm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gt2usvblzdv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2aoeczmip.html

[B11] 生成数字序列 / 区间
来源：http://dali.pycfn.com/Article/details/gt2mserfwti.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gt2vwkjizsd.html

PHP:  range(0, 10, 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2ysmwcovl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gt2soojvmqv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdytvevb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258.top/Article/details/gt2oaakoxxv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gogol.net.cn/Article/details/gt2gxwkmbfu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.meibo888.top/Article/details/gt2zpzjwhox.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gt2rdgxakfv.html

[B12] 跳出多层循环
来源：http://dali.ydzc1.top/Article/details/gt2kyvzttai.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwnfuolj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gt2chtdnnrm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gt2jfuhyqap.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gt2xfgfidwa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2jqkhiurx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gt2tdugrxuv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gt2wstpklab.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gogol.net.cn/Article/details/gt2ssjfihor.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gt2bwvwoeph.html

Py:   isinstance(x, (int, float))
来源：http://dali.kuanghao11.cn/Article/details/gt2icqgzgzt.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xicrwazo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2pdnrecfm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nyccwncn.html

Java: x instanceof Number
来源：http://dali.zhiwuduotai.top/Article/details/gt2cttjpfhg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gt2wiaqpfla.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gt2pnrxzmlr.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gt2kuimnfdt.html

[B14] 判断值是否在集合内
来源：http://dali.meibo888.top/Article/details/gt2tuwrhzli.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gt2nczxcidu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gt2wendnixt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2oepapbfv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gt2hotejcyy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2nswldajl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2iuyeaira.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gt2ilowszcd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2noeenqpj.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gt2jjvrfbqz.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gt2qcvpwpvc.html

PHP:  $a && $b || !$c
来源：http://dali.cheryme.top/Article/details/gt2amaubofg.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2oywdzpzy.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2khpvezit.html

Java: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2clxrvnuw.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtbrsccm.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2swmhipzp.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2atgoxwqe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gt2tvjxurul.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gt2wcaitdpb.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvmlobuc.html

JS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gt2rwdgjxly.html

TS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gt2gyhrofol.html

Java: if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gt2pyluaskk.html

Go:   if data == nil { return }
来源：http://dali.yuanzhike.top/Article/details/gt2aqbohgly.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gt2casnumfn.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gt2ntpukiiw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2cfdysaaz.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gt2kpnuojtd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2edzernem.html

[C01] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gt2dbxbvuqo.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kggdnsmo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2vxjiqtqh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2sezbprqd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2qreqxdzm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlmcaavp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gt2fllazmeh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hammf.cn/Article/details/gt2sqnhviqr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2gzoanqdk.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gt2brylxite.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omfwniif.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fqaawawr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2fwoiqzrf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2nplujarw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daria6918.cn/Article/details/gt2gvcsqtsv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zdqjudy.top/Article/details/gt2jcqplfny.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gt2duxmbcac.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gt2lmlygbiq.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gt2odysjjrv.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gt2rmciftlh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gt2kaowjhbp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gt2xgchobdt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gt2prtnbvkj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gt2xefgzfyj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gt2ozrpzjbj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gt2jeboepds.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gt2phiipdwu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gt2wxtjfsyj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gt2zzfgntid.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gt2rwmbxqic.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gt2euejifap.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gt2cuylhlnq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezeytljb.html

Go:   // 无：用配置结构体参数
来源：http://dali.hysaishi.cn/Article/details/gt2zffclspl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gt2wovdnetm.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gt2qoqpyxge.html

[C05] 返回多个值
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlrnhtkl.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuurqeyo.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gt2sbyysbur.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xylfe.cn/Article/details/gt2pldxstvh.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gt2pekfiyqr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkilhxzm.html

Go:   return a, b
来源：http://dali.daxiang520.top/Article/details/gt2pltfhych.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gt2dnjvfajr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gt2oycfdhfl.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2wtkldlxw.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gt2llshbndt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gt2kwjztefe.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2awktrzjp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daria6918.cn/Article/details/gt2aevrlrtd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jianghu66.top/Article/details/gt2acgppduz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwbqdhfs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2ffmqujbm.html


<!-- 参考信息 -->