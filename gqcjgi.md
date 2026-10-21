代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xziqi.cn/Article/details/gtyafqrqpz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shangyingyoupin.top/Article/details/gtwjtlpvnv.html

TS:   if (!x) {}
来源：http://dali.bjfxy.top/Article/details/gtpfntqvor.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinqigufen.top/Article/details/gtshsikbcw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hammf.cn/Article/details/gtljlovqsy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jyoumei.cn/Article/details/gtdmsmoosz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttxtkwlxo.html

[A17] 位运算
来源：http://dali.iojbl.cn/Article/details/gtkykwjnib.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtytobdcuk.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtkbvbkxmx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtszrozflj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtqrhchsdi.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtzmmylxou.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtktffkcrb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtunkymqnu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtceduraiq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtranlpitk.html

Py:   ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyklrcrem.html

PHP:  ord("A"); chr(65)
来源：http://dali.snrcjt.cn/Article/details/gtrszpzyan.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gtrlqdzgvm.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gtrrlrpafk.html

Java: (int) 'A'; (char) 65
来源：http://dali.hywenlv.cn/Article/details/gtjbqrakfg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.smart0.xyz/Article/details/gtltuyookz.html

Ruby: "A".ord; 65.chr
来源：http://dali.bjfxy.top/Article/details/gteriaymej.html

C#:   (int)'A'; (char)65
来源：http://dali.smart0.xyz/Article/details/gtgvektbhv.html

[A19] 交换两个变量
来源：http://dali.yonumen.top/Article/details/gtlaozucse.html

Py:   a, b = b, a
来源：http://dali.zhengqikj.top/Article/details/gtujnkttzl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.mhx1999.top/Article/details/gtelgrpmxz.html

JS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangtech.top/Article/details/gtblunukhl.html

TS:   [a, b] = [b, a];
来源：http://dali.sufxvd.cn/Article/details/gtahotiswb.html

Java: int t = a; a = b; b = t;
来源：http://dali.xylfe.cn/Article/details/gtarfmkuvb.html

Go:   a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gtcyupdcwb.html

Ruby: a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtrmxfigmn.html

C#:   (a, b) = (b, a);
来源：http://dali.jyoumei.cn/Article/details/gtwpbhdfmz.html

[A20] 读取标准输入
来源：http://dali.0kj1m.cn/Article/details/gtzidosnpd.html

Py:   name = input("请输入：")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedjglyel.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.316326.xyz/Article/details/gttyhfmlaz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sysykeji.top/Article/details/gtgelosegy.html

TS:   // Node.js：readline 模块
来源：http://dali.iojbl.cn/Article/details/gtayidpzvp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnykmurlw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenjidiqi.icu/Article/details/gtolxfkinb.html

Ruby: gets.chomp
来源：http://dali.ppjwa.cn/Article/details/gtweiojunu.html

C#:   Console.ReadLine();
来源：http://dali.0kj1m.cn/Article/details/gtubqpuyfo.html

[A21] 保留指定小数位输出
来源：http://dali.c1oappe.top/Article/details/gtjkeegnip.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pengpengdd.cyou/Article/details/gtlscbdfpi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtyosbzlrl.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gttrtjsuxi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtydysshjh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gtqvxzmgmx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtdwbpycaw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtpvtptqwc.html

C#:   3.14159.ToString("F2")
来源：http://dali.smart0.xyz/Article/details/gtmkduhtlh.html

[A22] 获取字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtyyybtmct.html

Py:   len(s)
来源：http://dali.haohaochexian.top/Article/details/gttmehlsrf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.mhx1999.top/Article/details/gthwphgdgr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cucudq.cn/Article/details/gtdnogyigs.html

TS:   s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtubyvtthy.html

Java: s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqjdhrnw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ybcxt.top/Article/details/gtpprsyusk.html

Ruby: s.length
来源：http://dali.hysaishi.cn/Article/details/gteaprrydt.html

C#:   s.Length
来源：http://dali.meibo888.top/Article/details/gtpkflvppl.html

[A23] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gttknoijob.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shzxlz.cn/Article/details/gtpdrnjksl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yj202588.top/Article/details/gtovltjwvu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj202588.top/Article/details/gtibagbroo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtkcnlmpxl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtkrdadyvx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.fengsongda.top/Article/details/gttvnugakv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.bjfxy.top/Article/details/gtqbwdbvni.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xinyue.icu/Article/details/gtlsllsfda.html

[A24] 去除首尾空白
来源：http://dali.sysykeji.top/Article/details/gtfovyevgh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.andypj.xyz/Article/details/gtvewcuvcp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aibaodan.cn/Article/details/gtoizjiuly.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gtyjgubjfj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtnhtefyqi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yonumen.top/Article/details/gtldzktqbm.html

Go:   strings.TrimSpace(s)
来源：http://dali.havefunace.top/Article/details/gtemqnqvkt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzcmgpnl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yongpay.top/Article/details/gtxpdpwqoz.html

[A25] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtclmrotdi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.snrcjt.cn/Article/details/gtuzrnpsif.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ehwqpu.com/Article/details/gtsazrdtkk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtopguonhp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gtmuzxtbmt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zdqjudy.top/Article/details/gtslewhwsh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gtihgkwbfz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ybcxt.top/Article/details/gtfsnsbcak.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gtpyjjsdji.html

[A26] 类型转换总览
来源：http://dali.kuanghao11.cn/Article/details/gtazurehdu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fengsongda.top/Article/details/gtowtotqhl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daria6918.cn/Article/details/gtbcygrmcz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.svipenyu.cn/Article/details/gtgrtsknjn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shangyingyoupin.top/Article/details/gtnkmploof.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gtnukyvibb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnxiangtu.top/Article/details/gtinyoyzuu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xziqi.cn/Article/details/gtyqbuakdx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.guannengcc.top/Article/details/gtzsroedly.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfrjelmrb.html

B. 流程控制
来源：http://dali.jianghu66.top/Article/details/gtstghlnya.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxeagpsms.html

[B01] 条件判断 if / else
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxzaltnt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.bjfxy.top/Article/details/gtkueunvkn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtaxfnahij.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtkcjolbfa.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtkonfyssv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtlosmhvho.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yangfankeji.com/Article/details/gtykrdoimo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.redwolf501.top/Article/details/gtfkfpjgix.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtezokqjmu.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gtrhmkiljb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.kuanghao11.cn/Article/details/gtemjbfbxg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hnxiangtu.top/Article/details/gtgmhglehk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtbggqvxkg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntruzigp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtlptjkqao.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yongpay.top/Article/details/gtnqgdsraf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yangfankeji.com/Article/details/gtvakszpfj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtyfssvwfz.html

[B03] switch / match / case
来源：http://dali.nanxuanxn.top/Article/details/gtcebafvdf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.bjfxy.top/Article/details/gtbsoynnbe.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gterulbtuo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtuhezagdk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtmhiwvzxz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gttlpbpori.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tian-w.cn/Article/details/gturmpkyfd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sysykeji.top/Article/details/gtknlubcln.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tian-w.cn/Article/details/gthounacyp.html

[B04] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gtuxdwpgqb.html

Py:   for i in range(10): print(i)
来源：http://dali.hammf.cn/Article/details/gtpxpbqxhn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj202588.top/Article/details/gteddwktvx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjxaavoqb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gtunyawizo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtqbelwrgj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tian-w.cn/Article/details/gtwwtfcfwb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hysaishi.cn/Article/details/gtxopumgda.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cashguo.top/Article/details/gttafzlbdr.html

[B05] 遍历数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtbwielage.html

Py:   for item in arr: print(item)
来源：http://dali.chenzaomai.com/Article/details/gtocnmnggh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbbryrrq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gterjmnldj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gtwcganmbf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.fengsongda.top/Article/details/gtwejrkyal.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ivvv.top/Article/details/gtuungeukn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.0kj1m.cn/Article/details/gtfcsfrmsh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhhbczds.html

[B06] 遍历字典 / 对象
来源：http://dali.cheryme.top/Article/details/gtzuxstfmb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258.top/Article/details/gtvztmphql.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ivvv.top/Article/details/gtgskiwqgq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gthiepzoxp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtwnylclxa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gtjqrtxqbe.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhengqikj.top/Article/details/gtmwwwkqgj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gtifghcsqt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ybcxt.top/Article/details/gtdrnfnkxd.html

[B07] while 循环
来源：http://dali.yuanzhike.top/Article/details/gtxbphltbq.html

Py:   while i < 10: i += 1
来源：http://dali.zhongyouzk.top/Article/details/gtvtvhnygh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangdashe.top/Article/details/gtfiqaglsw.html

JS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtrxpkwtix.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmxzqnwx.html

Java: while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gteixuhrfn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhongyouzk.top/Article/details/gtgqnvjdim.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gthlavdczt.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtmqxokvln.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gtqveyjnpr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.vqdsnc.cn/Article/details/gtdfkwddwx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtherxvnyu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtsntywiiy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtfpajyorf.html

Java: do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtlnnnvxns.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtmkmphrzq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tian-w.cn/Article/details/gtainqcqei.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtkbfpkusw.html

[B09] break 与 continue
来源：http://dali.jianghu66.top/Article/details/gthjvbdgei.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewkyhfry.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtczkqvsbx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtthiijbnw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtmstqcuiw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtadzaamfo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gtohiujftq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xylfe.cn/Article/details/gtgrqpqmgk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtjixhcepc.html

[B10] 遍历同时拿索引
来源：http://dali.vqdsnc.cn/Article/details/gtwdriobtp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.quarkkingdee.top/Article/details/gtqmllyzcy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gtoqqjddcx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtyxnaonyn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtnjlqvreb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.9152youxi.cn/Article/details/gtzpkvgdka.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gtkhrrsyyw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gtdhhivxoe.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.havefunace.top/Article/details/gtszshrbcg.html

[B11] 生成数字序列 / 区间
来源：http://dali.sxryk.cn/Article/details/gtspktlozw.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gttrgvvivn.html

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gtnpgcdrhb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gtwtjhmomm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gtcthubadz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hywenlv.cn/Article/details/gtjrlkepgw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gtdwtuijed.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gtiucijhjt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yonumen.top/Article/details/gtccshybec.html

[B12] 跳出多层循环
来源：http://dali.gogol.net.cn/Article/details/gtksppfkjz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gtwmmripun.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.redwolf501.top/Article/details/gtacjpixki.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtjnyyxgqx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtdqrixgtw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtggdzlvtf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cashguo.top/Article/details/gtsdhluenc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.9152youxi.cn/Article/details/gtkpvcetqk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gtbzhappar.html

[B13] 判断是否为数字
来源：http://dali.cucudq.cn/Article/details/gtohpmadyd.html

Py:   isinstance(x, (int, float))
来源：http://dali.yangfankeji.com/Article/details/gtcwxpejmu.html

PHP:  is_numeric($x)
来源：http://dali.yj20258.top/Article/details/gtggsfjolf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gtltichkih.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtyzxxsgcj.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gtapnijkyq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxuanxn.top/Article/details/gtddjlgdsp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gotoacloud.top/Article/details/gtxrfjfvnu.html

C#:   x is int or double or decimal
来源：http://dali.zhiwuduotai.top/Article/details/gtxmckgtvy.html

[B14] 判断值是否在集合内
来源：http://dali.yvedp.cn/Article/details/gtkpnbopfp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.vqdsnc.cn/Article/details/gtatexrdir.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gtsdttfkdm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtssuvernb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtwtychpqp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gtqysvxryu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gtusxotaeo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtzjoowods.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gttazwsmdb.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtjkctljah.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gtilensfph.html

PHP:  $a && $b || !$c
来源：http://dali.zycfv.cn/Article/details/gtnxyvpyug.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtwrzohfpp.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtkcpikbkz.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtpgxweobz.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtvvdnbxjk.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtrkudmveq.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtyysqpsqm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtssxzbsmc.html

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gtouiednbj.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gtkvpvrooa.html

JS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtvwiyutqr.html

TS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtmqsifgwl.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gtamhtqihx.html

Go:   if data == nil { return }
来源：http://dali.iojbl.cn/Article/details/gtzfbodqnc.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gtxfbagpgq.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtbwafxsit.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmnshfkkv.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfpskptl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtgfuuniot.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtpgsinjoi.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtigqjdfbh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtgtvqeyom.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gteuuwltks.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtohiilmxh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtoyvayvew.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gtrnvjuobk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gtjvdfmzoo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtkingsvfd.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtfrbvrefc.html

Py:   def greet(name="World"): return name
来源：http://dali.cdnleiting.top/Article/details/gteaoujloz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtfstepbtd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gtzzldqrmp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtsjmijqme.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gteycjdixm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gtckivadxs.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gtsnsxzqcm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yueranfly.top/Article/details/gtolsrqrdq.html

[C03] 可变参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkninfsbb.html

Py:   def total(*args): return sum(args)
来源：http://dali.smart0.xyz/Article/details/gtifcozaeo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gtnqgyqvbd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtbujjwg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtbnavpzhn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cqqwz.cn/Article/details/gtouomzejx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gtqlnenfba.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gtkathzcgx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yonumen.top/Article/details/gtfxrnwiyh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shzxlz.cn/Article/details/gtspiczahd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gtjcvryyej.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aizwys.cn/Article/details/gtrptozguu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtgtwsfxzq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtmeilvhye.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gtdadfoucr.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gtjxjagmdr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gthdurcnkt.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtvhmshljm.html

[C05] 返回多个值
来源：http://dali.hfpthk.cn/Article/details/gtkrtvopnn.html

Py:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtnahkpobc.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gtsalicoqo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtbcovpatf.html

TS:   return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gtoxbojjrk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gtyjeqyxzv.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtwvtdqvpj.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gtsfsswtqn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zdqjudy.top/Article/details/gtnrujazez.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gtgupbtwjt.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gtqreernmb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gtdijcbbcg.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtlidzxclo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtvjadwcsf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gthpkugykq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.iojbl.cn/Article/details/gtdmcsmqxf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gtfraztapu.html


<!-- 参考信息 -->