代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hfpthk.cn/Article/details/gtyxjggsrw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.svipenyu.cn/Article/details/gtmrqjxjsg.html

TS:   if (!x) {}
来源：http://dali.daxiang520.top/Article/details/gtjcxfjofy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.haohaochexian.top/Article/details/gtmnrcuqyj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenjidiqi.icu/Article/details/gteryppsuk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jiagoushi.top/Article/details/gtdvckiord.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtyksfyrxt.html

[A17] 位运算
来源：http://dali.tanke756.top/Article/details/gtlwsqkici.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtrugtrcsa.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cucudq.cn/Article/details/gtlhqhwfds.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtfdqfhdvo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gteaihkpam.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gttqjldxgq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtjtxsvbzr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtflwwmhqp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtblblnhxx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yj20258888.top/Article/details/gtyyqflsvk.html

Py:   ord("A"); chr(65)
来源：http://dali.zhongyouzk.top/Article/details/gtuolkeqvv.html

PHP:  ord("A"); chr(65)
来源：http://dali.nwbrower.top/Article/details/gtvpfxwege.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gtnejquotj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodpnijyn.html

Java: (int) 'A'; (char) 65
来源：http://dali.andypj.xyz/Article/details/gthtucdara.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jyoumei.cn/Article/details/gthcfqnvfm.html

Ruby: "A".ord; 65.chr
来源：http://dali.hfpthk.cn/Article/details/gtqvjudwko.html

C#:   (int)'A'; (char)65
来源：http://dali.guowangkeji.top/Article/details/gtidtybuwc.html

[A19] 交换两个变量
来源：http://dali.yanxiufei.cn/Article/details/gtwygnxeeo.html

Py:   a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gtnchboryj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.bjfxy.top/Article/details/gteyahauzf.html

JS:   [a, b] = [b, a];
来源：http://dali.aizwys.cn/Article/details/gtfvkxyojt.html

TS:   [a, b] = [b, a];
来源：http://dali.redwolf501.top/Article/details/gtvxtnqwax.html

Java: int t = a; a = b; b = t;
来源：http://dali.pycfn.com/Article/details/gtvbwtjhxw.html

Go:   a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gtavlcffte.html

Ruby: a, b = b, a
来源：http://dali.zhiwuduotai.top/Article/details/gtbuugpsgm.html

C#:   (a, b) = (b, a);
来源：http://dali.gzhubu.top/Article/details/gtdlgxcpoj.html

[A20] 读取标准输入
来源：http://dali.wangshuangyany.cn/Article/details/gtlwffdart.html

Py:   name = input("请输入：")
来源：http://dali.chenjidiqi.icu/Article/details/gtyszuhjqf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigufen.top/Article/details/gtwiovvsoz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhixingplan.top/Article/details/gtnoifrunl.html

TS:   // Node.js：readline 模块
来源：http://dali.havefunace.top/Article/details/gtoyonhthr.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tianlin.xyz/Article/details/gtutqsrzim.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfuqktmx.html

Ruby: gets.chomp
来源：http://dali.vqdsnc.cn/Article/details/gtwhcyhdaf.html

C#:   Console.ReadLine();
来源：http://dali.quarkkingdee.top/Article/details/gttmwvyifq.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxxtacan.html

Py:   f"{3.14159:.2f}"
来源：http://dali.svipenyu.cn/Article/details/gtufuqtuig.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtfeoxzmia.html

JS:   (3.14159).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtgemmfrmd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtyrmbhwml.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtcxoyndtc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteihllcyw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gtnnamtevz.html

C#:   3.14159.ToString("F2")
来源：http://dali.bjfxy.top/Article/details/gtvkhaghma.html

[A22] 获取字符串长度
来源：http://dali.redwolf501.top/Article/details/gtwgwicuvo.html

Py:   len(s)
来源：http://dali.haohaochexian.top/Article/details/gtvozhsfqj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.kuanghao11.cn/Article/details/gtuukzcydf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.andypj.xyz/Article/details/gtzfjpwshm.html

TS:   s.length
来源：http://dali.tian-w.cn/Article/details/gtenknbmub.html

Java: s.length()
来源：http://dali.cdnleiting.top/Article/details/gtdvunngou.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtlblauzrs.html

Ruby: s.length
来源：http://dali.hnqzz.top/Article/details/gtjnzmjudn.html

C#:   s.Length
来源：http://dali.dianchejie.cn/Article/details/gtzrujnydi.html

[A23] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtulyqhdpr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.bjfxy.top/Article/details/gtrbxefidu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jlsjyb.cn/Article/details/gtyysyghvl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gtnzijthnr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gtjamjevoj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gtlvbvlvsk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gtaqxfuphp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yonumen.top/Article/details/gtejbzmshz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenjidiqi.icu/Article/details/gteqkjznba.html

[A24] 去除首尾空白
来源：http://dali.ydzc1.top/Article/details/gtfeyphtkw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenlongwang.top/Article/details/gtyzslenvx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.0kj1m.cn/Article/details/gttgrnaxil.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jyoumei.cn/Article/details/gtcsmvzjzn.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guannengcc.top/Article/details/gtltcyfohy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjhhvqmr.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxuanxn.top/Article/details/gtvzwdelau.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.snrcjt.cn/Article/details/gtqeaxkgfz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cucudq.cn/Article/details/gtsdxuljgd.html

[A25] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtexyogjig.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigfzy.top/Article/details/gtxyibtaay.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cashguo.top/Article/details/gtmqegunac.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.birdmap.top/Article/details/gtcfonhgvt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guowangkeji.top/Article/details/gtgrfzhkco.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258888.top/Article/details/gtfxqnphbw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gtjobeaoou.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nanxuanxn.top/Article/details/gtgtwgebwf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gtjknfkmri.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwegcogmb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.0kj1m.cn/Article/details/gtxxczckve.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yanxiufei.cn/Article/details/gtomwkifzz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tian-w.cn/Article/details/gtobtgsipc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xinyue.icu/Article/details/gtqetborrv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtonnvnwdh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gteuupwimx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yuanzhike.top/Article/details/gtqfhpsoes.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gtdxyyiaky.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtuozniuce.html

B. 流程控制
来源：http://dali.hysaishi.cn/Article/details/gtvuzwyaiz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtnqwaxqxk.html

[B01] 条件判断 if / else
来源：http://dali.mhx1999.top/Article/details/gtpilcydqz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj202588.top/Article/details/gtankdjluo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtlbizxdug.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtaeltuzay.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtgwgomave.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gtevkxkswg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gogol.net.cn/Article/details/gtzacppdhn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jyoumei.cn/Article/details/gtmmrbbtqf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtpufufggn.html

[B02] 多分支 else if / elif
来源：http://dali.yvedp.cn/Article/details/gtnunzmtoy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pycfn.com/Article/details/gtlstwiruj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zdqjudy.top/Article/details/gtpgpiwjmi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gthaxudoom.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gtacnjbmor.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtdorvwqft.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zycfv.cn/Article/details/gtocfqqnpx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yanxiufei.cn/Article/details/gtyjzzygex.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtcdhfvncn.html

[B03] switch / match / case
来源：http://dali.tian-w.cn/Article/details/gtasiayeqm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenjidiqi.icu/Article/details/gtpyrehtiv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtmlroqnph.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gthtorqhnm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gthrrinmoc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtnidewkze.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sysykeji.top/Article/details/gtykfhljih.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.0kj1m.cn/Article/details/gtkorlgxgf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xinyue.icu/Article/details/gtjeywywck.html

[B04] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gthdhqvaht.html

Py:   for i in range(10): print(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvxtokza.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixhiqoaz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gtgocdemef.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangdashe.top/Article/details/gtrryfhmbh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.pycfn.com/Article/details/gtqcdxksgk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xylfe.cn/Article/details/gtnmyuvqfv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ydzc1.top/Article/details/gtrwtmcaom.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tanke756.top/Article/details/gtjmnlgkfq.html

[B05] 遍历数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtmccnhzep.html

Py:   for item in arr: print(item)
来源：http://dali.zhoulong.xyz/Article/details/gtxcdnkosy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ybcxt.top/Article/details/gtjotmffjj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gtpitinsgj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtypdkbyqa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsjrmxotj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangdashe.top/Article/details/gtzeqwcojp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gtluraquop.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daxiang520.top/Article/details/gtaamwkkli.html

[B06] 遍历字典 / 对象
来源：http://dali.pengpengdd.cyou/Article/details/gtykauebke.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tian-w.cn/Article/details/gtjcolixsf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj202588.top/Article/details/gthkhhwulb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfnoprqim.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gthfeqcyyn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.redwolf501.top/Article/details/gtfbnnerkg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ivvv.top/Article/details/gtsjgjbtmb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.vqdsnc.cn/Article/details/gtdzhykbwm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jiagoushi.top/Article/details/gtiroehxra.html

[B07] while 循环
来源：http://dali.andypj.xyz/Article/details/gtuhdwwquy.html

Py:   while i < 10: i += 1
来源：http://dali.fengsongda.top/Article/details/gtlnkwwcwi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aibaodan.cn/Article/details/gtejxtsala.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuhbjjey.html

TS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtdwjuhxms.html

Java: while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtgikybyql.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.iojbl.cn/Article/details/gtscgxpaxo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzienyho.html

C#:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtmyhacpss.html

[B08] do-while（至少执行一次）
来源：http://dali.hnxiangtu.top/Article/details/gtockpcoix.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.pycfn.com/Article/details/gtnxyupnfr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtgnikklhw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtjbswfqbn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtiicscmwk.html

Java: do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtepohdwol.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj202588.top/Article/details/gtawzcrrvn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gtlyuxyqut.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrszwylw.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gtflwjxgob.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sxryk.cn/Article/details/gtlsrkyeqd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtmhnqgjhs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtvkhifryv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gttvuusrqz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtxcifxaal.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gtpmxykcse.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sysykeji.top/Article/details/gtpfqfttjl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtalyiuqzh.html

[B10] 遍历同时拿索引
来源：http://dali.iojbl.cn/Article/details/gtthmxruhm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxuanxn.top/Article/details/gttklfbxvv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnktkowwp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtlusoufws.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtsmpawhtw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cqqwz.cn/Article/details/gtgmaamrdt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgdyogvc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtfvckxkio.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tanke756.top/Article/details/gtpnegwyeb.html

[B11] 生成数字序列 / 区间
来源：http://dali.jianghu66.top/Article/details/gtqgtlxwoe.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigufen.top/Article/details/gtbjjtpvjj.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtdzrgfvlk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gthqqcgsvm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.9152youxi.cn/Article/details/gtpzctideq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258888.top/Article/details/gtijkgarpm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hysaishi.cn/Article/details/gtcqnhqxxs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xylfe.cn/Article/details/gtcrbrxowm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.haohaochexian.top/Article/details/gtgcnglhot.html

[B12] 跳出多层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtskmtzakn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tanke756.top/Article/details/gtdekdccqy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.bjfxy.top/Article/details/gtppwjqvsi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtwdyoefgc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtjdsxjwgw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtcsnsdnuu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtofzrwaqa.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258888.top/Article/details/gtwsscdtde.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuxming.cn/Article/details/gtibbayiru.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gttphnadyu.html

Py:   isinstance(x, (int, float))
来源：http://dali.gotoacloud.top/Article/details/gtprccaetf.html

PHP:  is_numeric($x)
来源：http://dali.kuanghao11.cn/Article/details/gtefgsfdgi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gtxjzdqvbq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtndmzmima.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtleohajwk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenlongwang.top/Article/details/gttdloxqcr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dianchejie.cn/Article/details/gteqbnfeej.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobmxvfxr.html

[B14] 判断值是否在集合内
来源：http://dali.birdmap.top/Article/details/gtcmnkbnbc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yangfankeji.com/Article/details/gtvxevofwg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.mhx1999.top/Article/details/gtoaamuhxs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtoyammvde.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtgscqfark.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtcbsijfkq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.kuanghao11.cn/Article/details/gtksacnjov.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbexjsih.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtwusnpjtv.html

[B15] 布尔运算与取反
来源：http://dali.zhixingplan.top/Article/details/gtbtaorfdl.html

Py:   a and b or not c
来源：http://dali.guowangkeji.top/Article/details/gtueafybmf.html

PHP:  $a && $b || !$c
来源：http://dali.gaohongyu789.top/Article/details/gtwvbnqbvh.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gteccbkyrz.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtilyuigfs.html

Java: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtjwijcviv.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtboftofzh.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtvisbcwsz.html

C#:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtexhegkuk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gtnvtcfrot.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gtxvmtyjaz.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gtzrmazbic.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtixbowgxu.html

TS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtgggcpvui.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtvmpxsshk.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gthzdurzcg.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gtqmvvfnim.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtblcdnlvy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthcsvjpwg.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gtdyzvdaxx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgugzgxau.html

[C01] 定义函数
来源：http://dali.fengsongda.top/Article/details/gthwdhkhqz.html

Py:   def add(a, b): return a + b
来源：http://dali.iojbl.cn/Article/details/gtgsvrlssa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtrgdwltkv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtakxjtpzd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtxjgatvno.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtmylbbgpb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yangfankeji.com/Article/details/gtvdehqhfi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtpdimjqhq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfjkwhsxs.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gtrcufzimf.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gturbxdwpw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fengsongda.top/Article/details/gtcfsxsean.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttzulhpjd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtmfjqodfx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gtlsnluwyc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtykvydfyu.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigufen.top/Article/details/gtfndpwhqp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmxeazed.html

[C03] 可变参数
来源：http://dali.haohaochexian.top/Article/details/gtqfexuuyu.html

Py:   def total(*args): return sum(args)
来源：http://dali.sweek.top/Article/details/gtrsvagxjz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gtrugrasxu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gtwjfpqxuu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtvztnmkou.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmiyzwhfk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pycfn.com/Article/details/gtrnynwvkg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtqqjijrfx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gtgcfyyorv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyrxvqbw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shzxlz.cn/Article/details/gtvlaajrjf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gtlibqnjnd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtibonzrvd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtrkfuqksm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gterdpkebr.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangdashe.top/Article/details/gtjwvjikvv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtmyghafhl.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtrgvcxntb.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gtmtywyppw.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gthwnbqgxi.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gthilyzayc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbnqifwu.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtimouufry.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gthsrlexvz.html

Go:   return a, b
来源：http://dali.daxiang520.top/Article/details/gtwmbaawna.html

Ruby: return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtodypuwjw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gtfoyhraug.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gtgzeiukgk.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gtavsledwp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gtylvsxobr.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtjinmzkbq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gtxdfomcid.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtonemcfko.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtcjkderug.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtdqyazreu.html


<!-- 参考信息 -->