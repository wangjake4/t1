代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.snrcjt.cn/Article/details/gtachhxgcn.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xziqi.cn/Article/details/gtnawglpel.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gtkdadooyk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqzctgxwx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zycfv.cn/Article/details/gthnjkivef.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.andypj.xyz/Article/details/gtkqyrksti.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtufhatfft.html

[A17] 位运算
来源：http://dali.yonumen.top/Article/details/gtvkuztqhr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtwptjskjt.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ybcxt.top/Article/details/gtnijtxnyu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtyhjapjpb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtnxqsklvg.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtzfawiois.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmhgpjso.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtqtdkelsk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtadmrwyxy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cqqwz.cn/Article/details/gtzlnlvbtr.html

Py:   ord("A"); chr(65)
来源：http://dali.ehwqpu.com/Article/details/gtngmxjelp.html

PHP:  ord("A"); chr(65)
来源：http://dali.kuanghao11.cn/Article/details/gtgdakidhb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gthtdyhhha.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shzxlz.cn/Article/details/gtwczxmpaq.html

Java: (int) 'A'; (char) 65
来源：http://dali.ivvv.top/Article/details/gtosuvdqae.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigufen.top/Article/details/gtsupravoc.html

Ruby: "A".ord; 65.chr
来源：http://dali.kuanghao11.cn/Article/details/gtrzwzzeyg.html

C#:   (int)'A'; (char)65
来源：http://dali.jinqigfzy.top/Article/details/gtkhyrnijf.html

[A19] 交换两个变量
来源：http://dali.bjfxy.top/Article/details/gteksfeghp.html

Py:   a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gthrxphlzq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.daria6918.cn/Article/details/gtrfxqrnmu.html

JS:   [a, b] = [b, a];
来源：http://dali.yonumen.top/Article/details/gtvkmhqosc.html

TS:   [a, b] = [b, a];
来源：http://dali.0kj1m.cn/Article/details/gtobixzdov.html

Java: int t = a; a = b; b = t;
来源：http://dali.ehwqpu.com/Article/details/gtcsekaymv.html

Go:   a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gtzktehcea.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gtptxiquof.html

C#:   (a, b) = (b, a);
来源：http://dali.zhongyouzk.top/Article/details/gtxqxelxxt.html

[A20] 读取标准输入
来源：http://dali.xuanzx.com/Article/details/gtxuvijdtc.html

Py:   name = input("请输入：")
来源：http://dali.0kj1m.cn/Article/details/gtzjgmjjog.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yvedp.cn/Article/details/gthwkrvddu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjhvcsxd.html

TS:   // Node.js：readline 模块
来源：http://dali.ehwqpu.com/Article/details/gtebiwegsf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.mhx1999.top/Article/details/gtbgpbnjwb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinghuilouyu.cn/Article/details/gttnvuftxh.html

Ruby: gets.chomp
来源：http://dali.yuanzhike.top/Article/details/gtuscialzs.html

C#:   Console.ReadLine();
来源：http://dali.yuxming.cn/Article/details/gtlgldzljf.html

[A21] 保留指定小数位输出
来源：http://dali.redwolf501.top/Article/details/gtkxqvmvgc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hywenlv.cn/Article/details/gthtbhwrsl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gtmzullvny.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtfopslnsb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gthjomqzsr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gtxpzwkdhm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gtxcbuhzyk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtymyriszz.html

C#:   3.14159.ToString("F2")
来源：http://dali.vqdsnc.cn/Article/details/gtpxqerhua.html

[A22] 获取字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtjzyicxnf.html

Py:   len(s)
来源：http://dali.yuxming.cn/Article/details/gtrqgbfmat.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yvedp.cn/Article/details/gtyrozfkdf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhiwuduotai.top/Article/details/gtekpmqhyc.html

TS:   s.length
来源：http://dali.hnqzz.top/Article/details/gtzhpzlsso.html

Java: s.length()
来源：http://dali.yueranfly.top/Article/details/gtoswybsae.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj202588.top/Article/details/gtdmsciaxt.html

Ruby: s.length
来源：http://dali.vqdsnc.cn/Article/details/gtqdwadgzt.html

C#:   s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtgagnofht.html

[A23] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtdlomixfa.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.iojbl.cn/Article/details/gtfldwklyl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinqigufen.top/Article/details/gtkdemlbsp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjghpacy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtutrpktqq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gtqlboycot.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gotoacloud.top/Article/details/gtpamufcsc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.meibo888.top/Article/details/gtcuvqgocs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zdqjudy.top/Article/details/gttebvuzbn.html

[A24] 去除首尾空白
来源：http://dali.yj20258888.top/Article/details/gtkttuhjxb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gtlpeyvlxp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxihntypv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gtnjeujfbf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fengsongda.top/Article/details/gtohbekesi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhengqikj.top/Article/details/gtjqjdhqac.html

Go:   strings.TrimSpace(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjpxqptv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nanxinkj.top/Article/details/gtpqyxeqqp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.nwbrower.top/Article/details/gtffbavhan.html

[A25] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtgetxtiar.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zdqjudy.top/Article/details/gtdmkzomqq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ppjwa.cn/Article/details/gtlafersji.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shzxlz.cn/Article/details/gtduykjwbz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gtmpgiigho.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daria6918.cn/Article/details/gtjzhhatcq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gtavauliik.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tanke756.top/Article/details/gtojowcruv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtvvmzrfje.html

[A26] 类型转换总览
来源：http://dali.nwbrower.top/Article/details/gtiewevtkv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fengsongda.top/Article/details/gtjrcvcybz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shuidangran.top/Article/details/gtdcaiebpz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.guowangkeji.top/Article/details/gtieoqubhn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cdnleiting.top/Article/details/gtbejzfoev.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gtwnltaagr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shangyingyoupin.top/Article/details/gtwyvipfub.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pycfn.com/Article/details/gttnauybof.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gtrsezzcmx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtlacefoxy.html

B. 流程控制
来源：http://dali.cheryme.top/Article/details/gtszcbquao.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtukvvarrb.html

[B01] 条件判断 if / else
来源：http://dali.dashuyun.cn/Article/details/gtffwtuscw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj202588.top/Article/details/gtfisvjtqs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cheryme.top/Article/details/gtzhawdrlo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtdmphqidc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtkjmhdqkt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtsulidzyl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gtbwcthtgu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yanxiufei.cn/Article/details/gtadhppwrn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gtiwoembno.html

[B02] 多分支 else if / elif
来源：http://dali.nanxuanxn.top/Article/details/gtqovakhhb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daria6918.cn/Article/details/gtxnpphjht.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.smart0.xyz/Article/details/gthwlelmqp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtmzstryff.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtxbhojsfk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtldajxzef.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnqzz.top/Article/details/gtwztczyeh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuanzhike.top/Article/details/gtqayoqkbx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtheuhrone.html

[B03] switch / match / case
来源：http://dali.haohaochexian.top/Article/details/gtfrivglnq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxuanxn.top/Article/details/gtkvlwizwu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevxajxkc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtmtzozyit.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtbrokihpd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtqizvqyqm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.aizwys.cn/Article/details/gtiiutbzlt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.meibo888.top/Article/details/gtbuibxgky.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfoziuvt.html

[B04] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrrhpxmq.html

Py:   for i in range(10): print(i)
来源：http://dali.yuanzhike.top/Article/details/gtpeuzeoqg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.quarkkingdee.top/Article/details/gtwkzvoarb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gthrmyfgtk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtizclidfp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepxzkehm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xylfe.cn/Article/details/gtcusyiqsh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.9152youxi.cn/Article/details/gtoepzulhm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.svipenyu.cn/Article/details/gtejnzqgux.html

[B05] 遍历数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtctyiczrb.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gtjruxfgey.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jlsjyb.cn/Article/details/gtgdyhmtaz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gtidzueave.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnxiangtu.top/Article/details/gtotdotlte.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gtiysxwymy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hammf.cn/Article/details/gtyntaehia.html

Ruby: arr.each { |item| puts item }
来源：http://dali.daxiang520.top/Article/details/gtpfmknrbh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gtpvwtkbhu.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gtreiupzcp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.birdmap.top/Article/details/gtzcywyqok.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgfzy.top/Article/details/gtlzldpeye.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.316326.xyz/Article/details/gtgjsexkkq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gttfklrqun.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.quarkkingdee.top/Article/details/gtnomnopwh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ybcxt.top/Article/details/gtfolxzgtm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tanke756.top/Article/details/gtadmgvhvf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.kuanghao11.cn/Article/details/gtsuxfespq.html

[B07] while 循环
来源：http://dali.9152youxi.cn/Article/details/gtirvqrrbq.html

Py:   while i < 10: i += 1
来源：http://dali.svipenyu.cn/Article/details/gtjxtaihrf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenlongwang.top/Article/details/gtarwipsek.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtdicrzsmu.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpojvrgpn.html

Java: while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtbhtmgftx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gtpvonkgdr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.wangdashe.top/Article/details/gtlsdtvrbq.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnevnacon.html

[B08] do-while（至少执行一次）
来源：http://dali.tian-w.cn/Article/details/gtdxxphuno.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gtyzyflzjv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gtuitlvbzo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtbwjsalzg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtzczqnebw.html

Java: do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtfldsftbg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxinkj.top/Article/details/gtntqfkpcl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jlsjyb.cn/Article/details/gtlzmdxtdw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtdaadqlcl.html

[B09] break 与 continue
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjrlmsbm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.meibo888.top/Article/details/gtcewatirm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtqrkfcdyg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtxzdxyyyq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtqmpwfxvt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtdydwcvld.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtovkoxhvt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gtppscikiz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtmjlwmfdd.html

[B10] 遍历同时拿索引
来源：http://dali.hnxiangtu.top/Article/details/gtllgjlcfj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tianlin.xyz/Article/details/gtcnuvqjfc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdovndtux.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtwxfhznjn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtqelclwuz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gtdmtjdwma.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangdashe.top/Article/details/gtqfwwbifh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sufxvd.cn/Article/details/gtqsglzyki.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ppjwa.cn/Article/details/gtzycztlub.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gtzcpfxkkn.html

Py:   list(range(0, 10, 2))
来源：http://dali.gotoacloud.top/Article/details/gtgzqauwak.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258888.top/Article/details/gtkrmeyjtn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gtbttcrmql.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtglycrayx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cashguo.top/Article/details/gtvpngybos.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gtjomspjku.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yangfankeji.com/Article/details/gtekuksdrm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtduiezlrb.html

[B12] 跳出多层循环
来源：http://dali.nanxuanxn.top/Article/details/gtvdoyvurh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtmvdydojf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gtbofuxxkh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtbbjlcmlr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gttjasqzdu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtmllgcini.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gtzauuhbqy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tian-w.cn/Article/details/gtlseffnkn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gtxvaqwlvl.html

[B13] 判断是否为数字
来源：http://dali.dashuyun.cn/Article/details/gtqsakrkzh.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrbnmeff.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtoafanpyx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gteuyubdrd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtzsirmqhl.html

Java: x instanceof Number
来源：http://dali.snrcjt.cn/Article/details/gtgtkljklc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yangfankeji.com/Article/details/gthgeogkbi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhixingplan.top/Article/details/gtfcvsrcab.html

C#:   x is int or double or decimal
来源：http://dali.guowangkeji.top/Article/details/gtaxogosvd.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtoibwlwaq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gtihwgbmpa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuanzhike.top/Article/details/gtynzyukuw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtuzvffkpb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtcymracbn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtepnouwzz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenlongwang.top/Article/details/gtedbucpiq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fengsongda.top/Article/details/gtagpgmzkl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtikqrabnh.html

[B15] 布尔运算与取反
来源：http://dali.nanxinkj.top/Article/details/gtostfjygx.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvmfnbos.html

PHP:  $a && $b || !$c
来源：http://dali.sysykeji.top/Article/details/gtspiuqzuq.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtnrrcaely.html

TS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtjnfwbjlr.html

Java: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtnndqkuky.html

Go:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtegkvycro.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtjzzievjh.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gteizpcrvg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gtwggddlug.html

Py:   if not data: return
来源：http://dali.wangshuangyany.cn/Article/details/gthrvyyunp.html

PHP:  if (!$data) { return; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwjmarupb.html

JS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gtqmipaain.html

TS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtzmjczbol.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gthywdijuh.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxwkmifx.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gtmstxauay.html

C#:   if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgkbymst.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkzwzffhj.html

C. 函数与作用域
来源：http://dali.hysaishi.cn/Article/details/gtphhexvjl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttwevclll.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtepzjwnmb.html

Py:   def add(a, b): return a + b
来源：http://dali.sysykeji.top/Article/details/gtofmvbavo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtubyjjfhf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gthfyvnxjf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtpnwcmmxh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtzpleurbw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gtckhikvws.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gtbpmkrqxi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtdzqvoeka.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtdqtjglfe.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gtbrtlcuhw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gtlecmiddf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtxgguzvgj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrqftzojw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gtvfxgocxw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gtmehwrpbb.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gtsbhmzdcb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gtandacbvm.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gtqyombtnc.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gtvuysczut.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shzxlz.cn/Article/details/gtjjlwthok.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtdllinblv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtfyvbuyji.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj202588.top/Article/details/gtendiqxdi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtjwcttddz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gtxgcbawie.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtrkbtegbe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ehwqpu.com/Article/details/gtxwzhbvoe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxwxgvda.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gtxxtnmhii.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtxmrpiglu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gtcgwaowmx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gtevyfipwp.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaqyafif.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtbcgeuazq.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gthwqsxxmo.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gtvoqbyqvm.html

Py:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtjyhfhuyf.html

PHP:  return [$a, $b];
来源：http://dali.dashuyun.cn/Article/details/gtkktlhbck.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtijxpgxdo.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocmatvot.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gtwdqymngi.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtlseldlwa.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gtpvinwzim.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtbyhcxgxx.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxinkj.top/Article/details/gtswpbyuff.html

Py:   square = lambda x: x * x
来源：http://dali.redwolf501.top/Article/details/gtgwapqsek.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtlxqlcdju.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtuejawwga.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtpsckrxat.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gtnngddwij.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gtfoaznlte.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xinyue.icu/Article/details/gtiszectks.html


<!-- 参考信息 -->