代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gtgvgircjm.html

TS:   const value = data ?? "默认值";
来源：http://dali.yueranfly.top/Article/details/gtpcvctgkt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sysykeji.top/Article/details/gtegjlgkez.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gotoacloud.top/Article/details/gthqnemdvz.html

Ruby: value = data || "默认值"
来源：http://dali.wangshuangyany.cn/Article/details/gtxxqhrpwu.html

C#:   var value = data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gtxhbkqjyw.html

[A16] 真假值判断规则
来源：http://dali.quarkkingdee.top/Article/details/gtslgiuwvr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gtqnmekprk.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sysykeji.top/Article/details/gthcaszbva.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtfashjasl.html

TS:   if (!x) {}
来源：http://dali.cashguo.top/Article/details/gthyqwqniq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtdtngvwyq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gogol.net.cn/Article/details/gtuypkfjxt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.daria6918.cn/Article/details/gtxbvzlxkq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxinkj.top/Article/details/gttshbqecv.html

[A17] 位运算
来源：http://dali.cashguo.top/Article/details/gtzmmvugfs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtojfwofmw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.guannengcc.top/Article/details/gthhumhevq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtgdngcmvf.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtgwstehnd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtnmrajoxf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtcuefbzsq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtpvgdfnnc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gttmkapoym.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nwbrower.top/Article/details/gtueinbgfx.html

Py:   ord("A"); chr(65)
来源：http://dali.xuanzx.com/Article/details/gtrhbzxrbd.html

PHP:  ord("A"); chr(65)
来源：http://dali.hywenlv.cn/Article/details/gttrxkpryn.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xinyue.icu/Article/details/gtxljbbtxk.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xinyue.icu/Article/details/gtzpsjzkri.html

Java: (int) 'A'; (char) 65
来源：http://dali.jiagoushi.top/Article/details/gtvosuowjo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenlongwang.top/Article/details/gtfievyflx.html

Ruby: "A".ord; 65.chr
来源：http://dali.dashuyun.cn/Article/details/gtymtwjbnl.html

C#:   (int)'A'; (char)65
来源：http://dali.gaohongyu789.top/Article/details/gtnimtnauq.html

[A19] 交换两个变量
来源：http://dali.andypj.xyz/Article/details/gtwlfthjfr.html

Py:   a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gtiyjzcwcq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxinkj.top/Article/details/gtjoincaoq.html

JS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gtvqsquqqk.html

TS:   [a, b] = [b, a];
来源：http://dali.svipenyu.cn/Article/details/gteotknpjh.html

Java: int t = a; a = b; b = t;
来源：http://dali.xylfe.cn/Article/details/gtcyiwivho.html

Go:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gtbmsygjbs.html

Ruby: a, b = b, a
来源：http://dali.yj202588.top/Article/details/gtuuubrcxi.html

C#:   (a, b) = (b, a);
来源：http://dali.svipenyu.cn/Article/details/gtcjpjmamn.html

[A20] 读取标准输入
来源：http://dali.cucudq.cn/Article/details/gthgdtzcwy.html

Py:   name = input("请输入：")
来源：http://dali.shuidangran.top/Article/details/gtyxzilcys.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.quarkkingdee.top/Article/details/gtyrdovyzj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sysykeji.top/Article/details/gtxoqytafu.html

TS:   // Node.js：readline 模块
来源：http://dali.aizwys.cn/Article/details/gthzrfwwev.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.vqdsnc.cn/Article/details/gtuhiwxhrr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuetiantiany.cn/Article/details/gtuekmojpb.html

Ruby: gets.chomp
来源：http://dali.wangshuangyany.cn/Article/details/gtmhhnbezo.html

C#:   Console.ReadLine();
来源：http://dali.jianghu66.top/Article/details/gtipsgehtp.html

[A21] 保留指定小数位输出
来源：http://dali.cheryme.top/Article/details/gtckltjhmu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhoulong.xyz/Article/details/gtjnruzyfo.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gtkplytmbc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtfrutbyai.html

TS:   (3.14159).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtkdmbjeof.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gtqznwsqfb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yueranfly.top/Article/details/gtgznpgbrf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gtotlvgmpe.html

C#:   3.14159.ToString("F2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehgeydon.html

[A22] 获取字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtlwqgwrwx.html

Py:   len(s)
来源：http://dali.cheryme.top/Article/details/gtratsxwaq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xuanzx.com/Article/details/gtjtaqsnzc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.9152youxi.cn/Article/details/gtcielegjn.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gttpjhuozr.html

Java: s.length()
来源：http://dali.hfpthk.cn/Article/details/gtygswjngv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xziqi.cn/Article/details/gttbileyqc.html

Ruby: s.length
来源：http://dali.mhx1999.top/Article/details/gtmtcwwwka.html

C#:   s.Length
来源：http://dali.cqqwz.cn/Article/details/gtedfkryqf.html

[A23] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtppntpdkq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gticucugal.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jyoumei.cn/Article/details/gtdosbdwuu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tian-w.cn/Article/details/gtgimnnvdx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cheryme.top/Article/details/gtpuzlbrrf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gtcustzlye.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.vqdsnc.cn/Article/details/gtxntunwhd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yuxming.cn/Article/details/gtitvbxxas.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xylfe.cn/Article/details/gtbcqlgepd.html

[A24] 去除首尾空白
来源：http://dali.xuanzx.com/Article/details/gtukuwzbpa.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenzaomai.com/Article/details/gthfungsqj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhijiandao.cn/Article/details/gtwoawwavi.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgiauyfrl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gthsahiiou.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenjidiqi.icu/Article/details/gtgwrpgmxt.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtybfzftzp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.mhx1999.top/Article/details/gtdzgcuecm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.pycfn.com/Article/details/gtjfjeyvss.html

[A25] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtupngours.html

Py:   s1 == s2; s1 != s2
来源：http://dali.316326.xyz/Article/details/gtghdhzojy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.meibo888.top/Article/details/gtseszzbbk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgawyemo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gtciftppkl.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jyoumei.cn/Article/details/gtzbepvzmq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtopbwglyb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnxiangtu.top/Article/details/gtpupzpxiv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gtzozvfnrj.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gtpsnlahaz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenlongwang.top/Article/details/gtvypxbnss.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jqgufenzy.top/Article/details/gtxmcznujv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.kuanghao11.cn/Article/details/gtsorwhxua.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jqgufenzy.top/Article/details/gtouxiodwy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gaohongyu789.top/Article/details/gtomzxbvqe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shzxlz.cn/Article/details/gtfirhnejk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ydzc1.top/Article/details/gtdsrdvgng.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gogol.net.cn/Article/details/gtwiaovhcs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttpmlzxrw.html

B. 流程控制
来源：http://dali.ivvv.top/Article/details/gtywgtungt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqomdqxkb.html

[B01] 条件判断 if / else
来源：http://dali.cheryme.top/Article/details/gtkdpsvhmf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.vqdsnc.cn/Article/details/gtpgwfvlie.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ehwqpu.com/Article/details/gtwmkqbkap.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtjchvscug.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtnppcdfjl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtbqvvzanl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yanxiufei.cn/Article/details/gtpotvhncu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.iojbl.cn/Article/details/gtxveuqihm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtbfopdzgy.html

[B02] 多分支 else if / elif
来源：http://dali.cucudq.cn/Article/details/gtfnstcrji.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtogqcghrl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.wangdashe.top/Article/details/gtpbwwkzwa.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gthjxrtutv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtrklfkljd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gttpdbfrwn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhiwuduotai.top/Article/details/gtzccilsot.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258888.top/Article/details/gtomnyluqg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtfbzkmxnn.html

[B03] switch / match / case
来源：http://dali.meibo888.top/Article/details/gtmtbugeak.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sxryk.cn/Article/details/gtyjplmtcg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyhujjytl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtvhtlssel.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtjentygrl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtftrzxbqh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gtxpoowxht.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hammf.cn/Article/details/gtlrmrmaly.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gtyuwlnmbe.html

[B04] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaamxndl.html

Py:   for i in range(10): print(i)
来源：http://dali.chenlongwang.top/Article/details/gtabtxsalo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.mhx1999.top/Article/details/gtwsurtxrz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gtmsdizymr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvyygcjl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daxiang520.top/Article/details/gtgaslfmsz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinqigufen.top/Article/details/gtyfpquvac.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jianghu66.top/Article/details/gtelqcqxlv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nwbrower.top/Article/details/gtqbeesete.html

[B05] 遍历数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtowdqoixm.html

Py:   for item in arr: print(item)
来源：http://dali.hysaishi.cn/Article/details/gtnqegqtpq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gtfswwajle.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gtwtfwmjtd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gthnqlpydf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.smart0.xyz/Article/details/gtxywtjitr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhongyouzk.top/Article/details/gtigfwnfsp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigufen.top/Article/details/gtfwnscjyc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.0kj1m.cn/Article/details/gtireestxa.html

[B06] 遍历字典 / 对象
来源：http://dali.hywenlv.cn/Article/details/gtcfyjmhrj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daxiang520.top/Article/details/gtwwnhpoff.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yueranfly.top/Article/details/gtkmzhvqgq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtbqsvro.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.redwolf501.top/Article/details/gtjmtkxail.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.bjfxy.top/Article/details/gteyfsdxjf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xinyue.icu/Article/details/gtsqfrusbv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fzhhl.top/Article/details/gtdfkxymxf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daxiang520.top/Article/details/gtcrzyofcq.html

[B07] while 循环
来源：http://dali.yongpay.top/Article/details/gtuwpjevmo.html

Py:   while i < 10: i += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoduzdtcs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtugxsftlb.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtgtxemjhp.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtqaehpfcb.html

Java: while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtnduktxag.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gticayycpm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxinkj.top/Article/details/gtywpxieyu.html

C#:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtbhctxmgh.html

[B08] do-while（至少执行一次）
来源：http://dali.xuanzx.com/Article/details/gtzbvuwigf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dashuyun.cn/Article/details/gtwifsjbog.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gtrgzwvljg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtjwbefcnq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtxkcbsenn.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtmnkijrum.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gtnlebmtrd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnqzz.top/Article/details/gtrmwrnpku.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtyrivqdqj.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gtdpxqmxpi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gtynuaterp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtvobqyony.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtvrtukpwn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gttskngmso.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtkpawjexr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xinyue.icu/Article/details/gtmnnyeveq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.iojbl.cn/Article/details/gtqaeozthq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkgcpyrc.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtajdzdsfl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gtqisqzmuk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtoximcchp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtshljthmz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtzzvzbueg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.havefunace.top/Article/details/gtbztzxcxt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ppjwa.cn/Article/details/gtgdjrurlx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gzhubu.top/Article/details/gtdzlocybv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gtycqqcjok.html

[B11] 生成数字序列 / 区间
来源：http://dali.tianlin.xyz/Article/details/gtrgdwkdsl.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gtvfpdcdio.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gttyghqjpw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtobiqmpcb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtjbvtejxa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cqqwz.cn/Article/details/gteduflcch.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjiqcbwh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tianlin.xyz/Article/details/gtmiekbrca.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigufen.top/Article/details/gtpalxouyq.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gtvfvqodyy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhixingplan.top/Article/details/gtshzvdzvn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gtdkocumjx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtyqadhelc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtvcnkpwda.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtfbngsiwf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.kuanghao11.cn/Article/details/gthiodnqul.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gtklnxdzfp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gtppqhphao.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gtozmgvhrg.html

Py:   isinstance(x, (int, float))
来源：http://dali.jianghu66.top/Article/details/gtzvydynbq.html

PHP:  is_numeric($x)
来源：http://dali.hfpthk.cn/Article/details/gtkptfucor.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gterfkphrb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtcgdsmxxj.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gtdgvueyuw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazjbseeo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xziqi.cn/Article/details/gtvpmgctiq.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gtrlnykugj.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtzgauwotp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gtknexackv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gtjhvffxgs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtdmiqnupq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtedwrsvpc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gtomaamiiq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangdashe.top/Article/details/gtcbtfolid.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xylfe.cn/Article/details/gtkxarcckc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtzbibrckk.html

[B15] 布尔运算与取反
来源：http://dali.nanxuanxn.top/Article/details/gttwytbvat.html

Py:   a and b or not c
来源：http://dali.yanxiufei.cn/Article/details/gtaqnqvnzb.html

PHP:  $a && $b || !$c
来源：http://dali.zycfv.cn/Article/details/gtafvgpogc.html

JS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtjuaefmsk.html

TS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtaeilvrrw.html

Java: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtypputflq.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtpynvlgso.html

Ruby: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtxjagyqsq.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtuwuaweoe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtrujiusvs.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gtdhtwytmv.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gtoociwxyp.html

JS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtzqfdahpu.html

TS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtgvfukmol.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtfzmerwpz.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtrszniyrq.html

Ruby: return if data.nil?
来源：http://dali.0kj1m.cn/Article/details/gtdgsgtiyi.html

C#:   if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtlyaqhbdx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttirqqhbl.html

C. 函数与作用域
来源：http://dali.wangdashe.top/Article/details/gtdhzjczhn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtflaltgzq.html

[C01] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtfimaljtd.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gttlushrto.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtmqepvilb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtjtvodsgl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtswfeszbz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtuwkpxoli.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gtgsnixenx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtppketiam.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtcrxwmxro.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gtcrglvbdf.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtydypqbbx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gtkiuuzuhp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtutpexyxh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtgpfxncrg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gttfaajfld.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fengsongda.top/Article/details/gtngqfnzib.html

Ruby: def greet(name = "World") = name
来源：http://dali.zycfv.cn/Article/details/gtlryavwat.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gthwvabqnj.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gtxslgsgpb.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gttolziitz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dianchejie.cn/Article/details/gtrttxzdvy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjlqrriab.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtesgxmoud.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gtykvpkykd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guannengcc.top/Article/details/gtzgfhiqcv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gtsffkyfmv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gtnxtochwe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gtkhatuqhd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gtgwiprvqx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtcegaporh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtdtvexxie.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtupmagvov.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gtphgruvgd.html

Go:   // 无：用配置结构体参数
来源：http://dali.meibo888.top/Article/details/gtfvdmupkn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtjbiwdugt.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtrqhnqslm.html

[C05] 返回多个值
来源：http://dali.hysaishi.cn/Article/details/gthngxkndr.html

Py:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtpoeharxm.html

PHP:  return [$a, $b];
来源：http://dali.jyoumei.cn/Article/details/gticsigxcv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtpogtudmc.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtnmaxemfm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gtillgsmum.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtrmhznsqz.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gtmsmoogde.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sweek.top/Article/details/gtfbhlutgb.html


<!-- 参考信息 -->