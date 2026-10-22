代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gt2crtsmbva.html

[A15] 空值判断与默认值
来源：http://dali.aizwys.cn/Article/details/gt2rmpbscdu.html

Py:   value = data or "默认值"
来源：http://dali.xinyue.icu/Article/details/gt2mqcltujm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pycfn.com/Article/details/gt2njvlzdji.html

JS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gt2lpsehknx.html

TS:   const value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gt2ukmmwjoz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yuanzhike.top/Article/details/gt2fyorybzb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xziqi.cn/Article/details/gt2gdxbnsbz.html

Ruby: value = data || "默认值"
来源：http://dali.guowangkeji.top/Article/details/gt2lqiyvriu.html

C#:   var value = data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gt2znukupsz.html

[A16] 真假值判断规则
来源：http://dali.nanxinkj.top/Article/details/gt2kgaihwsi.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gzhubu.top/Article/details/gt2dtebetzj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yuanzhike.top/Article/details/gt2fxrmbvto.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jianghu66.top/Article/details/gt2lynuinir.html

TS:   if (!x) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vegqxhnz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2otesgdqw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tanke756.top/Article/details/gt2afkaprwg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xylfe.cn/Article/details/gt2tuzjyrxx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tian-w.cn/Article/details/gt2mwflnwxq.html

[A17] 位运算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqlaqrew.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gt2ywybhtfe.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftokbsgs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkqejyhr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2lqmmoysc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gt2ujvejsfg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2jshtmdkw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gt2fosdkpuw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gt2hdsjkqrh.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yj202588.top/Article/details/gt2qrhoepdb.html

Py:   ord("A"); chr(65)
来源：http://dali.zhoulong.xyz/Article/details/gt2qukzuogx.html

PHP:  ord("A"); chr(65)
来源：http://dali.smart0.xyz/Article/details/gt2ysataulm.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gt2qhjbjmxa.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258.top/Article/details/gt2qajrwnkf.html

Java: (int) 'A'; (char) 65
来源：http://dali.yuanzhike.top/Article/details/gt2casizhbb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gzhubu.top/Article/details/gt2lgundqil.html

Ruby: "A".ord; 65.chr
来源：http://dali.xinyue.icu/Article/details/gt2kawlwivy.html

C#:   (int)'A'; (char)65
来源：http://dali.kuanghao11.cn/Article/details/gt2jgjbvbgd.html

[A19] 交换两个变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suxernzd.html

Py:   a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gt2cwfyyugq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.birdmap.top/Article/details/gt2hyqstwsa.html

JS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gt2gddwpvwg.html

TS:   [a, b] = [b, a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2olwrmklk.html

Java: int t = a; a = b; b = t;
来源：http://dali.fengsongda.top/Article/details/gt2jfdxnlmb.html

Go:   a, b = b, a
来源：http://dali.jqgfzy.top/Article/details/gt2zynwgnhw.html

Ruby: a, b = b, a
来源：http://dali.yj20258.top/Article/details/gt2gxjjetsp.html

C#:   (a, b) = (b, a);
来源：http://dali.chenlongwang.top/Article/details/gt2hwkvassx.html

[A20] 读取标准输入
来源：http://dali.yj20258.top/Article/details/gt2zruhwgkt.html

Py:   name = input("请输入：")
来源：http://dali.pycfn.com/Article/details/gt2nvjowegg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.kuanghao11.cn/Article/details/gt2afutdaeh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gogol.net.cn/Article/details/gt2gqfcqrwh.html

TS:   // Node.js：readline 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2gelsotjn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.andypj.xyz/Article/details/gt2wtmmzuub.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpjbsqzr.html

Ruby: gets.chomp
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqsemajm.html

C#:   Console.ReadLine();
来源：http://dali.pycfn.com/Article/details/gt2bojkynot.html

[A21] 保留指定小数位输出
来源：http://dali.xinyue.icu/Article/details/gt2nnopuiaf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvrfnijn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gt2atkqblii.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gt2lpxnenyb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gt2mqqimgvo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yddedlkx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gt2xsglokrb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gt2qjzqsgbz.html

C#:   3.14159.ToString("F2")
来源：http://dali.andypj.xyz/Article/details/gt2hdlnqcuk.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzigsswc.html

Py:   len(s)
来源：http://dali.iojbl.cn/Article/details/gt2jammdabb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.dashuyun.cn/Article/details/gt2fhoyscpk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.guannengcc.top/Article/details/gt2xppvhsma.html

TS:   s.length
来源：http://dali.cdnleiting.top/Article/details/gt2utoungyp.html

Java: s.length()
来源：http://dali.daxiang520.top/Article/details/gt2zlonaeai.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.tian-w.cn/Article/details/gt2vcvhmuvm.html

Ruby: s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2swblyisn.html

C#:   s.Length
来源：http://dali.tanke756.top/Article/details/gt2ebfusrzj.html

[A23] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gt2oojpitot.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sysykeji.top/Article/details/gt2hvkcqjdp.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jianghu66.top/Article/details/gt2xqoqrzlc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gt2xtxldcgr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gt2yplixvrt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gt2hooijxwx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.bjfxy.top/Article/details/gt2bxegtshj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.c1oappe.top/Article/details/gt2gcitayws.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.9152youxi.cn/Article/details/gt2bzahipry.html

[A24] 去除首尾空白
来源：http://dali.hnqzz.top/Article/details/gt2ulgkhluc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xylfe.cn/Article/details/gt2juzysajp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hywenlv.cn/Article/details/gt2ipnzokdt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gt2oyupaklb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gt2ajxnzbpp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.smart0.xyz/Article/details/gt2ctcnkimk.html

Go:   strings.TrimSpace(s)
来源：http://dali.9152youxi.cn/Article/details/gt2lzrmngkh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sxryk.cn/Article/details/gt2yxikkcpl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gt2zvpksjia.html

[A25] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwgwiotv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gaohongyu789.top/Article/details/gt2qqvviati.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nwbrower.top/Article/details/gt2falyzdzd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gt2wsvvwwob.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jprmkwfe.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqgydojc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gt2zbdlgkjf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pycfn.com/Article/details/gt2ujxdidwz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gt2mdwjunoz.html

[A26] 类型转换总览
来源：http://dali.havefunace.top/Article/details/gt2sfkbmqfl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.guowangkeji.top/Article/details/gt2jccqcvav.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fengsongda.top/Article/details/gt2zlhalkzb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj20258.top/Article/details/gt2gtkbpsly.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nwbrower.top/Article/details/gt2byuufrqf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.wangdashe.top/Article/details/gt2bqzrliys.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cashguo.top/Article/details/gt2gpxtarvp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sysykeji.top/Article/details/gt2dauwjbpi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daria6918.cn/Article/details/gt2yfppbkpx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxtjxkdo.html

B. 流程控制
来源：http://dali.daria6918.cn/Article/details/gt2zqfyjyfx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ygkjnnqn.html

[B01] 条件判断 if / else
来源：http://dali.cucudq.cn/Article/details/gt2kydwamtc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjpaujih.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2omxlfrnf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gt2hmojngaa.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gt2jmiwnxex.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vccdhjsg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuanzx.com/Article/details/gt2odxyzftt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tanke756.top/Article/details/gt2thfqnsqq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqoltcst.html

[B02] 多分支 else if / elif
来源：http://dali.aibaodan.cn/Article/details/gt2mjckrmrv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxuanxn.top/Article/details/gt2spynhzlp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tian-w.cn/Article/details/gt2aqewvxtf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gt2mukmpehy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gt2qvnswugc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2wbzyimms.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.andypj.xyz/Article/details/gt2ogudsexh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yvedp.cn/Article/details/gt2bgkuomzx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2vdpzthuf.html

[B03] switch / match / case
来源：http://dali.jlsjyb.cn/Article/details/gt2khpnbzjm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.meibo888.top/Article/details/gt2qedtafjj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gt2bnhoezbv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udnojong.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gt2oquhyelq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gt2cxaytwva.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guowangkeji.top/Article/details/gt2kwhucmzc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhixingplan.top/Article/details/gt2ywzvpqsd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.iojbl.cn/Article/details/gt2mwmsxtry.html

[B04] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gt2qdetruvx.html

Py:   for i in range(10): print(i)
来源：http://dali.hammf.cn/Article/details/gt2onygehaq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hfpthk.cn/Article/details/gt2svfkpfux.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.redwolf501.top/Article/details/gt2wueeplmh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gt2igbyjxjs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yongpay.top/Article/details/gt2hoylciqb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gt2gahnolip.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gt2zwfaktdf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnqzz.top/Article/details/gt2ciikbsrc.html

[B05] 遍历数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gt2mnevxtxj.html

Py:   for item in arr: print(item)
来源：http://dali.meibo888.top/Article/details/gt2wjkabmrt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gt2eqqphhvi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gt2juxrdkon.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gt2luxybcdm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2amxfruli.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgfzy.top/Article/details/gt2ntftzfna.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yueranfly.top/Article/details/gt2jqfilfbn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gt2vqzohhvl.html

[B06] 遍历字典 / 对象
来源：http://dali.jianghu66.top/Article/details/gt2gnkaging.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guannengcc.top/Article/details/gt2okdoiqpm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj202588.top/Article/details/gt2rpyqmtaa.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2swqupqdp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gt2xodpkpcc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cashguo.top/Article/details/gt2saxidxdw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jlsjyb.cn/Article/details/gt2iyfbhuwr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.snrcjt.cn/Article/details/gt2yrttfqpz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangdashe.top/Article/details/gt2xhzszhjt.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odufbrwj.html

Py:   while i < 10: i += 1
来源：http://dali.zdqjudy.top/Article/details/gt2ewaxethv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sysykeji.top/Article/details/gt2fqzmldpg.html

JS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gt2uwnmhafi.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwwzvijn.html

Java: while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gt2cbekkwrl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2taxbwjwh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjwfwtje.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwispioa.html

[B08] do-while（至少执行一次）
来源：http://dali.pycfn.com/Article/details/gt2mvmlalrc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gt2hsvbkwzy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2wxcbsqkt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2hclwjlqc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2zgvfbujt.html

Java: do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2ioqjmkvv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gt2qsofvbbm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gt2ciiczdqc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjthzhkx.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gt2sucxdeav.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gt2bfkrjwuv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2shfcgjbi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2hywrjvbc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pquthgcp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2ukiuzksh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guowangkeji.top/Article/details/gt2atczmofy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhltqmde.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2ldhtxhsm.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gt2mqixotde.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxuanxn.top/Article/details/gt2ztwstdjx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gt2bmzwykxi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gt2gcrrmrhl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwrbmiqb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yonumen.top/Article/details/gt2zilbycgz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gt2fkeifpbg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gt2dnssqpmj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hfpthk.cn/Article/details/gt2uqjydtkp.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gt2llnazeur.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gt2vqdlwvcy.html

PHP:  range(0, 10, 2);
来源：http://dali.sufxvd.cn/Article/details/gt2wwtkqpgv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.9152youxi.cn/Article/details/gt2rzdckppw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gt2zhjpcxgs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2iagefdef.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gt2viclltzk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gt2sklihtru.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gt2opmqsyem.html

[B12] 跳出多层循环
来源：http://dali.iojbl.cn/Article/details/gt2yrisitgd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tanke756.top/Article/details/gt2wzlwkynf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gt2anjwhmhh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gt2eorbjwni.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2rhlyivbv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2rnmamwgk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.svipenyu.cn/Article/details/gt2swexdgoy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guannengcc.top/Article/details/gt2hmtuzsdj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gt2hhdwxrcf.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gt2pfnzfstr.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gt2hjrgzcmi.html

PHP:  is_numeric($x)
来源：http://dali.havefunace.top/Article/details/gt2ibcnvukg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gt2pnlndgar.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gt2nedchszv.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gt2zczegiag.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xylfe.cn/Article/details/gt2zgcizlff.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ybcxt.top/Article/details/gt2luoffdwy.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gt2sfhtiohf.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnwnzgoy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.quarkkingdee.top/Article/details/gt2entluuqo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.havefunace.top/Article/details/gt2fsgtljpt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2swdkhpsz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2ikjzfmbu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2xwntdkms.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sufxvd.cn/Article/details/gt2pixptrzh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2dgivtwho.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258.top/Article/details/gt2kggyxyie.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gt2zdodvgvn.html

Py:   a and b or not c
来源：http://dali.zhongyouzk.top/Article/details/gt2vkacimil.html

PHP:  $a && $b || !$c
来源：http://dali.sysykeji.top/Article/details/gt2cxfowzqf.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2opsjxgae.html

TS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2jgcsenel.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2amuxivpw.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2ojsijkqh.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2umxsxizg.html

C#:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2fyfauavi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hammf.cn/Article/details/gt2knrovekj.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gt2jpwexrto.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gt2wofefwaw.html

JS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gt2rpfesivz.html

TS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gt2vmnlnvff.html

Java: if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gt2ncnazoih.html

Go:   if data == nil { return }
来源：http://dali.jqgfzy.top/Article/details/gt2vuclkonv.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gt2ugdzngzy.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2eacafwpy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2vrlcgkss.html

C. 函数与作用域
来源：http://dali.0kj1m.cn/Article/details/gt2qfxxcnrf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2fymkhlbr.html

[C01] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gt2ktesrknp.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gt2zzairufe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2ufrcrvwb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2mnmudtxj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2ofgdmwct.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2vnwkpmnh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gt2yemhxacw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gt2irtzfddh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2hlvdhnjt.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gt2intvoqsz.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gt2vrtytqky.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbzwlhvb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2aybnwrxn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2yscliswt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gaohongyu789.top/Article/details/gt2uvovfqwo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gt2cvzhdysd.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gt2vwzecjfx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftwlgdtv.html

[C03] 可变参数
来源：http://dali.zhixingplan.top/Article/details/gt2qkjevprk.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gt2ppwarhmc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gt2dtqohqhk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gt2nqaiqdzp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gt2plogruwy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gt2lhrdccnd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdyekgmi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.haohaochexian.top/Article/details/gt2jzwtuzzu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aizwys.cn/Article/details/gt2pclbxmro.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gt2esfuzqfd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gt2kylmpgro.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gt2vcvnhhec.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ecdsglaj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gt2wbgcrbsa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gt2icgbzvxo.html

Go:   // 无：用配置结构体参数
来源：http://dali.meibo888.top/Article/details/gt2bdlwhenb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2hmbwdpwa.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gt2ncysxnot.html

[C05] 返回多个值
来源：http://dali.fzhhl.top/Article/details/gt2yzogmsnu.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gt2tvrhwqbm.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gt2vwejvecx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gt2ihgjnxmn.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gt2nbyxzqlo.html


<!-- 参考信息 -->