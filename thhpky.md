代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj20258.top/Article/details/gtmyylwsxr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fzhhl.top/Article/details/gtnvsdrifl.html

TS:   if (!x) {}
来源：http://dali.guowangkeji.top/Article/details/gtobqjszmd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.chenlongwang.top/Article/details/gtdzcrwqrn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zdqjudy.top/Article/details/gtlewlqfol.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ydzc1.top/Article/details/gtabhsycva.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ivvv.top/Article/details/gtgbklxbsk.html

[A17] 位运算
来源：http://dali.birdmap.top/Article/details/gtxzsuajho.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtyaukfqtl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yongpay.top/Article/details/gtlynszjaw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtkfvsjqup.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtuurnyvot.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gthtfrheml.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtyebadefv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtglziftoh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtyaukvmus.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtexctagft.html

Py:   ord("A"); chr(65)
来源：http://dali.tianlin.xyz/Article/details/gtnasoamlr.html

PHP:  ord("A"); chr(65)
来源：http://dali.guannengcc.top/Article/details/gthrmlxieo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shangyingyoupin.top/Article/details/gtslvdeacd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtrteihfkn.html

Java: (int) 'A'; (char) 65
来源：http://dali.jqgufenzy.top/Article/details/gtzeknqqht.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sxryk.cn/Article/details/gtphxiwhko.html

Ruby: "A".ord; 65.chr
来源：http://dali.kuanghao11.cn/Article/details/gtlfjgtyxv.html

C#:   (int)'A'; (char)65
来源：http://dali.yueranfly.top/Article/details/gtxppzzmcg.html

[A19] 交换两个变量
来源：http://dali.aizwys.cn/Article/details/gtwhbbripi.html

Py:   a, b = b, a
来源：http://dali.hammf.cn/Article/details/gtrllltjbz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.aibaodan.cn/Article/details/gthiaqccng.html

JS:   [a, b] = [b, a];
来源：http://dali.hnxiangtu.top/Article/details/gtjtxzwrhx.html

TS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gtwllidiqq.html

Java: int t = a; a = b; b = t;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpduzbzqp.html

Go:   a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gtipasrblo.html

Ruby: a, b = b, a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahwfjejl.html

C#:   (a, b) = (b, a);
来源：http://dali.jiagoushi.top/Article/details/gtshmwjkxg.html

[A20] 读取标准输入
来源：http://dali.jlsjyb.cn/Article/details/gtwwztnzmx.html

Py:   name = input("请输入：")
来源：http://dali.svipenyu.cn/Article/details/gthdgrpqja.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yj20258.top/Article/details/gtkoilptmi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.iojbl.cn/Article/details/gtiktrlmkf.html

TS:   // Node.js：readline 模块
来源：http://dali.xinyue.icu/Article/details/gtcrgpszxg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.dianchejie.cn/Article/details/gtzmiyhiay.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.quarkkingdee.top/Article/details/gtfvmcqypr.html

Ruby: gets.chomp
来源：http://dali.sxryk.cn/Article/details/gtajhorqcl.html

C#:   Console.ReadLine();
来源：http://dali.yanxiufei.cn/Article/details/gtetespnyd.html

[A21] 保留指定小数位输出
来源：http://dali.zhixingplan.top/Article/details/gtrieqndjd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.andypj.xyz/Article/details/gtsvuhkpcg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmmfoicx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtcgxaylto.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtwvldomqb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gtlvknthgt.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gtplphuqhx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtknvfumhh.html

C#:   3.14159.ToString("F2")
来源：http://dali.guannengcc.top/Article/details/gtreoeuqzb.html

[A22] 获取字符串长度
来源：http://dali.c1oappe.top/Article/details/gtbzdojyhw.html

Py:   len(s)
来源：http://dali.snrcjt.cn/Article/details/gtmmuodkir.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.dashuyun.cn/Article/details/gtqdywiizz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.svipenyu.cn/Article/details/gtapiuiodb.html

TS:   s.length
来源：http://dali.fzhhl.top/Article/details/gtcndlpgut.html

Java: s.length()
来源：http://dali.xziqi.cn/Article/details/gtbcfougqk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xylfe.cn/Article/details/gtssjikgsq.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gtdbxqkiei.html

C#:   s.Length
来源：http://dali.mhx1999.top/Article/details/gtxeofljuc.html

[A23] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gthtutivmy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xziqi.cn/Article/details/gtlibihonp.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yj202588.top/Article/details/gttfyzbmkt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aizwys.cn/Article/details/gtepxrtsey.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.0kj1m.cn/Article/details/gtazodvgvu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gtmzwfyarj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daxiang520.top/Article/details/gtbxaiysrk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtvixwndik.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hysaishi.cn/Article/details/gtepprqylh.html

[A24] 去除首尾空白
来源：http://dali.chenlongwang.top/Article/details/gtawziuuaz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.0kj1m.cn/Article/details/gtdfpuunrj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guowangkeji.top/Article/details/gtebcjchae.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cqqwz.cn/Article/details/gthxjxbcmy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gtwsspcofk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sufxvd.cn/Article/details/gtjxupgirt.html

Go:   strings.TrimSpace(s)
来源：http://dali.xziqi.cn/Article/details/gtqwtlygmc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.meibo888.top/Article/details/gtzvvadaud.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgsunnhj.html

[A25] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtgcqghwac.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ivvv.top/Article/details/gtifzfjzwt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jyoumei.cn/Article/details/gthvfijbao.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gtmxuvhuth.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daxiang520.top/Article/details/gtgjbixoei.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtckwpyivt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cashguo.top/Article/details/gtuvjjafad.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yanxiufei.cn/Article/details/gtpurorphu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.daxiang520.top/Article/details/gtcvuzykyd.html

[A26] 类型转换总览
来源：http://dali.ybcxt.top/Article/details/gtlreptmmg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shzxlz.cn/Article/details/gtmslsljue.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258.top/Article/details/gtkeluyznr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aibaodan.cn/Article/details/gtsekymfop.html

TS:   Number() String() Boolean() x as number
来源：http://dali.daria6918.cn/Article/details/gtvudcucam.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gtgplmnrlg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jianghu66.top/Article/details/gtgzkpwiuk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxinkj.top/Article/details/gtyiboezgh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtzawbucmr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtaddloirf.html

B. 流程控制
来源：http://dali.xinyue.icu/Article/details/gtpvkpferb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaywrdwu.html

[B01] 条件判断 if / else
来源：http://dali.ivvv.top/Article/details/gtfdbzdkzs.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yanxiufei.cn/Article/details/gtvzvgxjkm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuedlgho.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gtoxefdngq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtcxyzgmwu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtzhoqyccu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hywenlv.cn/Article/details/gtyyrxtxqw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fzhhl.top/Article/details/gtzueaborn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtwelzedfg.html

[B02] 多分支 else if / elif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvtizjeu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gtajkffkfe.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sufxvd.cn/Article/details/gtdyunlivz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gteyfmzuem.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtvhmmfsrm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gtrjiulaaf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gzhubu.top/Article/details/gtgkvhrpky.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhengqikj.top/Article/details/gtgwxwbtxj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtvetbiruv.html

[B03] switch / match / case
来源：http://dali.gotoacloud.top/Article/details/gtvycimhro.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gtwlxpdhek.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtgjuempln.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtldnxfwwo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtycbzfwtw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gteftjoryq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258888.top/Article/details/gttbnazold.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhongyouzk.top/Article/details/gtqsmdywfq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gtmpincehu.html

[B04] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtamauamdz.html

Py:   for i in range(10): print(i)
来源：http://dali.ybcxt.top/Article/details/gtxvkkokfu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlthmbnbu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cqqwz.cn/Article/details/gtmpdvnaer.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gtyeiyhhzg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiffhmfv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gtzfiegwrp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jlsjyb.cn/Article/details/gtdbtosfis.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.andypj.xyz/Article/details/gttffwdduo.html

[B05] 遍历数组 / 列表
来源：http://dali.birdmap.top/Article/details/gtpojtzqkv.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gtptlgeqde.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gtbaxboqxq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gtmtqhabxo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gtogsajhny.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258888.top/Article/details/gtvghlaxec.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cqqwz.cn/Article/details/gtpwcnpcgl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gtraxivwvs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jianghu66.top/Article/details/gtwfhpxzzt.html

[B06] 遍历字典 / 对象
来源：http://dali.meibo888.top/Article/details/gtlvakqgkn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.iojbl.cn/Article/details/gtsmshwgfg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfdlmfks.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fengsongda.top/Article/details/gtgqspkuxs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtgyhbpmxs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daxiang520.top/Article/details/gtdsqinhix.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hywenlv.cn/Article/details/gtirmrsyfs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sweek.top/Article/details/gtxhcfxvvm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.aizwys.cn/Article/details/gtqgumtlde.html

[B07] while 循环
来源：http://dali.sweek.top/Article/details/gtzfbyjvpu.html

Py:   while i < 10: i += 1
来源：http://dali.316326.xyz/Article/details/gtpvvxwkqb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258888.top/Article/details/gtbmpmbsgj.html

JS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtwbdmqkct.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtgsmovopa.html

Java: while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtryznwwih.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gtdynrujpu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zycfv.cn/Article/details/gtplpddadk.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtulgxyrue.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gtqnjtthvl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxinkj.top/Article/details/gtgzmslhhu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtntmubeaq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwzwenwk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtfyiinilc.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaftvrgaz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shuidangran.top/Article/details/gtgecotcjf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gzhubu.top/Article/details/gtfrsaxqlh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtgeshaean.html

[B09] break 与 continue
来源：http://dali.hnqzz.top/Article/details/gthzuditcy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gtgnzcxgsc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gthybpdrho.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtliydkuzp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtiejamfsj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtbsgpudxh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gtopkmrkyg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hysaishi.cn/Article/details/gtjosmteiz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtrrtqcncg.html

[B10] 遍历同时拿索引
来源：http://dali.yangfankeji.com/Article/details/gtubtmxmtr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gaohongyu789.top/Article/details/gtghpnabjt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gtwqcccowf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtjrxufroq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gttmmsxnvn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cucudq.cn/Article/details/gtiggprcdf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gtifsdxchb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gtdrlxmsbt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlzbjtdpr.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuxming.cn/Article/details/gtukbkmzom.html

Py:   list(range(0, 10, 2))
来源：http://dali.havefunace.top/Article/details/gticzkilum.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gtopmvkwmc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtsfqptsbt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gtrvfmqzqh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fzhhl.top/Article/details/gtbyxhmccp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dashuyun.cn/Article/details/gtbmtvvizh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gtrsnvnzgp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ydzc1.top/Article/details/gtxricqisl.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gtckkhspjy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gtshihgwyv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gtnrrimbpr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtbxdumjhe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtbhhkulcc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtzvmhrvmv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.andypj.xyz/Article/details/gtjmmiveck.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sufxvd.cn/Article/details/gtqurqgjdi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xylfe.cn/Article/details/gtnltoeims.html

[B13] 判断是否为数字
来源：http://dali.yuxming.cn/Article/details/gtibaxbolv.html

Py:   isinstance(x, (int, float))
来源：http://dali.pengpengdd.cyou/Article/details/gtcdgigtpj.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtnxdlvigy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gthnlvvrxz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtwjrgrcqu.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gtgxsecpaw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnxiangtu.top/Article/details/gtoibqldzg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aizwys.cn/Article/details/gtuvncxcsb.html

C#:   x is int or double or decimal
来源：http://dali.chenjidiqi.icu/Article/details/gtswgylldz.html

[B14] 判断值是否在集合内
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzpejnjk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ydzc1.top/Article/details/gtdvuezlya.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gtknurbgqv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtxfszoeoi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtgpzebyyr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtocwqjnal.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gtwvzeveuk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqkyqwpk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtszlfcinp.html

[B15] 布尔运算与取反
来源：http://dali.shzxlz.cn/Article/details/gttgnxdjre.html

Py:   a and b or not c
来源：http://dali.yvedp.cn/Article/details/gtrnqcqqvc.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gtmbhptiig.html

JS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidopylew.html

TS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtahfcgrcc.html

Java: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtfqcwwmww.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtqsnglapb.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gttatvoxmz.html

C#:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtfnioziwu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtddthxeti.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtahcsvurc.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzhufmino.html

JS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtcuydphso.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtivkfugkn.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtrpfzfysf.html

Go:   if data == nil { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprrodofv.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gtssjwfpfo.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtjjbeuwrf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgdxuomsg.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtyzsmfyos.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtnumqenyp.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gtaoptaosq.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtaddgggno.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtlwuhohip.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtpknsqdsn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtfzmbusrf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtkbcszpuo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtkubrbbdi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gthsyuljjh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtooyrngyk.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtecgzqspy.html

Py:   def greet(name="World"): return name
来源：http://dali.hnxiangtu.top/Article/details/gtvdsnotrp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gtnwhirugn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtrwjxjeyo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtqlsvxxwc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitthheoh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gtuanxljkq.html

Ruby: def greet(name = "World") = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjjyihsb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gtrlbewarj.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gtzehppavu.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gtyhuqocqr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenzaomai.com/Article/details/gtyvwkramf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtmswiyqpt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtjuekijsc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gtvisxpcyo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gthyveytrz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gtwyfzswud.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gtlapezhdt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtpapcumzz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gtuqejuaqi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtlfpppjgm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtwqvvdbqv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtcnppiftr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbpregnk.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtmxfhiaki.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtmjzufppt.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gttcjzrmth.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtjtvtbkax.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtokfeobjy.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gtjmzhivld.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtioznmbae.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtxmnynidk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gtwsbobfjx.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gtebebyhcg.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtbunkmzdp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yueranfly.top/Article/details/gtxpafiqtm.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtrmkisaaq.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gthxvywmvc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gtthueexwq.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtpxjnwwkd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtsvhvmdtv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtsbykgijm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xylfe.cn/Article/details/gtyljrujrv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtjvnrnmzg.html


<!-- 参考信息 -->