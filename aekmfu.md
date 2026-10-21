代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtpjvusdnu.html

TS:   const value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gtubaclvin.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdsgkzxg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.chenzaomai.com/Article/details/gtujfxmkza.html

Ruby: value = data || "默认值"
来源：http://dali.snrcjt.cn/Article/details/gtzpdgcumn.html

C#:   var value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtdslivdnt.html

[A16] 真假值判断规则
来源：http://dali.0kj1m.cn/Article/details/gtvojlhmzd.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yueranfly.top/Article/details/gtrgzfahlj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.dianchejie.cn/Article/details/gtumpuaemd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sweek.top/Article/details/gttwlitzdt.html

TS:   if (!x) {}
来源：http://dali.cqqwz.cn/Article/details/gtqtzixnlm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbokhlraq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.vqdsnc.cn/Article/details/gtzgsvoboh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.fengsongda.top/Article/details/gtiwjxmfzq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxlpyevq.html

[A17] 位运算
来源：http://dali.hfpthk.cn/Article/details/gtaiodxfjd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtmcbzqrve.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gzhubu.top/Article/details/gtrfycmygd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtierxgxcg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtkvjrbjqt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtvrzexcek.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtvprflqex.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtjpygdzqr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtsfeabcoe.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gogol.net.cn/Article/details/gtsipmoiid.html

Py:   ord("A"); chr(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrenjghqm.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtgjogncxg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gtzmtacngl.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.birdmap.top/Article/details/gtudkucnyv.html

Java: (int) 'A'; (char) 65
来源：http://dali.dianchejie.cn/Article/details/gthrmdvwga.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenlongwang.top/Article/details/gtwlburwil.html

Ruby: "A".ord; 65.chr
来源：http://dali.pycfn.com/Article/details/gtrrfsvgkk.html

C#:   (int)'A'; (char)65
来源：http://dali.gaohongyu789.top/Article/details/gtsoeieypm.html

[A19] 交换两个变量
来源：http://dali.bjfxy.top/Article/details/gtsghiwjvb.html

Py:   a, b = b, a
来源：http://dali.yongpay.top/Article/details/gtrbfeufuu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jqgfzy.top/Article/details/gtjemfcffg.html

JS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyypvqrs.html

TS:   [a, b] = [b, a];
来源：http://dali.daxiang520.top/Article/details/gtfutrkxcr.html

Java: int t = a; a = b; b = t;
来源：http://dali.hnqzz.top/Article/details/gtjlouhyyz.html

Go:   a, b = b, a
来源：http://dali.havefunace.top/Article/details/gtstodoeap.html

Ruby: a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gttcjcmdbf.html

C#:   (a, b) = (b, a);
来源：http://dali.ehwqpu.com/Article/details/gtwqqcohyw.html

[A20] 读取标准输入
来源：http://dali.cdnleiting.top/Article/details/gtksbkinhc.html

Py:   name = input("请输入：")
来源：http://dali.shuidangran.top/Article/details/gtdpgiuhof.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.fzhhl.top/Article/details/gtbqjopzkn.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.bjfxy.top/Article/details/gtmokojcvp.html

TS:   // Node.js：readline 模块
来源：http://dali.fzhhl.top/Article/details/gtmsfslvsx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hnqzz.top/Article/details/gtvdhaznvw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinqigufen.top/Article/details/gtujlqsdut.html

Ruby: gets.chomp
来源：http://dali.yongpay.top/Article/details/gtzobtnnjo.html

C#:   Console.ReadLine();
来源：http://dali.jqgfzy.top/Article/details/gtaintmcji.html

[A21] 保留指定小数位输出
来源：http://dali.pycfn.com/Article/details/gtjqkdfowv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ehwqpu.com/Article/details/gthsoknqsb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtjuladrzb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtqevfmgdw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtzqepldvt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gtjjkdmvmu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtrlahrhfd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtodxaujjg.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyujktlj.html

[A22] 获取字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtacskbveu.html

Py:   len(s)
来源：http://dali.hnqzz.top/Article/details/gtlqbyflyu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shzxlz.cn/Article/details/gtqklqyebw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xuetiantiany.cn/Article/details/gteahjvppf.html

TS:   s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtsfufzedj.html

Java: s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gteommzphz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yangfankeji.com/Article/details/gtoxglthsr.html

Ruby: s.length
来源：http://dali.gogol.net.cn/Article/details/gtptfucure.html

C#:   s.Length
来源：http://dali.xuanzx.com/Article/details/gteienzcpo.html

[A23] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtojkgxayb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tanke756.top/Article/details/gtevfsrtir.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.guowangkeji.top/Article/details/gtlektgvjp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gtumrjiinj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtwrmmlbzh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gtjopxosei.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hysaishi.cn/Article/details/gtdiytamgb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cheryme.top/Article/details/gtgvnyyigc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sufxvd.cn/Article/details/gtnssgckpi.html

[A24] 去除首尾空白
来源：http://dali.wangshuangyany.cn/Article/details/gtleyomrhz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xinyue.icu/Article/details/gtyeckxcar.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxinkj.top/Article/details/gtyrheweie.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fzhhl.top/Article/details/gtqmeyuofn.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtqghkxxdf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.aibaodan.cn/Article/details/gtzzgmhmto.html

Go:   strings.TrimSpace(s)
来源：http://dali.jlsjyb.cn/Article/details/gtrhdunnyw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhixingplan.top/Article/details/gtwyqazith.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttiahoqjp.html

[A25] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtwgmmuobg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj20258.top/Article/details/gtavnvpwdh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shuidangran.top/Article/details/gtrpkshlvl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gtcflzozad.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cucudq.cn/Article/details/gtyntntdle.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtdunjjngu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gtyqznkewo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.snrcjt.cn/Article/details/gtjcgpcnvr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gtbbnduqtn.html

[A26] 类型转换总览
来源：http://dali.zhixingplan.top/Article/details/gtcbfiuqpa.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yangfankeji.com/Article/details/gtnijttntx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hnqzz.top/Article/details/gthnsabods.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hywenlv.cn/Article/details/gtveedpccv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangdashe.top/Article/details/gthmkipjcl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hysaishi.cn/Article/details/gtzzfwsden.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxuanxn.top/Article/details/gtewcuinct.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.quarkkingdee.top/Article/details/gtrgesbhrn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gtuajzbslq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlqjovqts.html

B. 流程控制
来源：http://dali.yj20258.top/Article/details/gtnhhreqrc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsfjesvgd.html

[B01] 条件判断 if / else
来源：http://dali.aibaodan.cn/Article/details/gtoomtefgh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sweek.top/Article/details/gtkwsbvvtq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvnwdyty.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtdocwzcum.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtdkvhpfex.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtlmxwcdtt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tian-w.cn/Article/details/gtdufgyiqq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuxming.cn/Article/details/gtyemjwzml.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gtsbmgddkw.html

[B02] 多分支 else if / elif
来源：http://dali.nwbrower.top/Article/details/gtowgvgzpd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yueranfly.top/Article/details/gtkinokkpr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tianlin.xyz/Article/details/gtwuacagub.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtorefczyg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtqsyjsqyx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtfplskt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ydzc1.top/Article/details/gtwoqqankd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yongpay.top/Article/details/gtenkuylzk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtkaoqyiff.html

[B03] switch / match / case
来源：http://dali.hfpthk.cn/Article/details/gtsakihelr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sxryk.cn/Article/details/gtbynrnebh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtpknaevkq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtrdebiqtn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwngbbmz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtcnomykhb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuxming.cn/Article/details/gtyqebtvmi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangshuangyany.cn/Article/details/gtixgdnaij.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.meibo888.top/Article/details/gtszpojscl.html

[B04] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtwanssxet.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgfzy.top/Article/details/gtocsfeegh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fzhhl.top/Article/details/gthdagizpe.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gtxpbmjixv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cqqwz.cn/Article/details/gtstrbhykq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwgybhywc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yonumen.top/Article/details/gtjopnybho.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zycfv.cn/Article/details/gtlrgnxalv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tian-w.cn/Article/details/gtsiweofnn.html

[B05] 遍历数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtkfawyllp.html

Py:   for item in arr: print(item)
来源：http://dali.yj202588.top/Article/details/gthbbgwjhx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnqzz.top/Article/details/gtzxfdbhey.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gtnhvbmdyj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gtzzzeycmz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gtxerisxfw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cashguo.top/Article/details/gtxcmxcgot.html

Ruby: arr.each { |item| puts item }
来源：http://dali.iojbl.cn/Article/details/gtjvhntsvw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258.top/Article/details/gtfcxryokb.html

[B06] 遍历字典 / 对象
来源：http://dali.nanxinkj.top/Article/details/gtxgyfgkhz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gaohongyu789.top/Article/details/gtudnhbkiy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258888.top/Article/details/gtrbiofzjt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxmfvodzd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gtydeywzrd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenzaomai.com/Article/details/gtmuowvatb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.kuanghao11.cn/Article/details/gtxcpoxlet.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daria6918.cn/Article/details/gthkbabwdw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.snrcjt.cn/Article/details/gtwexioglw.html

[B07] while 循环
来源：http://dali.daria6918.cn/Article/details/gtwuvuxmru.html

Py:   while i < 10: i += 1
来源：http://dali.guannengcc.top/Article/details/gtloaauoto.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hysaishi.cn/Article/details/gthxndnbdy.html

JS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtypfhrazb.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtiinqjuic.html

Java: while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwsuyaghn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sysykeji.top/Article/details/gtlabjnoge.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cdnleiting.top/Article/details/gtnzplooha.html

C#:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtdwjlltie.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gtcppqbajf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yueranfly.top/Article/details/gtdlthqqjp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtobsaqiax.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtyfednvfh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtwjiwbyla.html

Java: do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtaokgnhcy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhengqikj.top/Article/details/gtdqeucdgv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtnecujief.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtyratwhwh.html

[B09] break 与 continue
来源：http://dali.shzxlz.cn/Article/details/gtbdrhkwnu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.vqdsnc.cn/Article/details/gtrdzsnwmc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtayzfpdzk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtboionsca.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtzibymnsr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtimqdmvaz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ybcxt.top/Article/details/gtylrjpirr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gtullppmao.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtfgkdtvwl.html

[B10] 遍历同时拿索引
来源：http://dali.andypj.xyz/Article/details/gtyejsjrdm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gtdjhxfbwg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hammf.cn/Article/details/gtgomnsmhn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcrxopsi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtzgrnuqzb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gtxwxsmpnk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gtbpqikzze.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.feifeiyinyue.top/Article/details/gtuovsxjvs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hysaishi.cn/Article/details/gtfjegmjev.html

[B11] 生成数字序列 / 区间
来源：http://dali.dashuyun.cn/Article/details/gtarucvcfs.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgfzy.top/Article/details/gtpwvixedc.html

PHP:  range(0, 10, 2);
来源：http://dali.ybcxt.top/Article/details/gtyktfobtd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtwnqqvscx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibbjgoxw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258.top/Article/details/gtuerknxjx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gthmfxaofa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.bjfxy.top/Article/details/gtdohwnmip.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gtihoahhhv.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqroyfzya.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gtlhsbiawi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhoulong.xyz/Article/details/gtffmyeoni.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gthkkgxopq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtnxiwfuhp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gthjebjeja.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yongpay.top/Article/details/gtrfefkfec.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gotoacloud.top/Article/details/gtvbylkkoy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gtevoijkpu.html

[B13] 判断是否为数字
来源：http://dali.wangshuangyany.cn/Article/details/gtoglhvubh.html

Py:   isinstance(x, (int, float))
来源：http://dali.meibo888.top/Article/details/gtfeiqxzet.html

PHP:  is_numeric($x)
来源：http://dali.hammf.cn/Article/details/gtfwubpvjg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gtdplnocyg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gttqbnqzqz.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gtoliffajw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtddrwgyrm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gtuyeebhxd.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gtoyduxlgk.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gtuljbypfu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ehwqpu.com/Article/details/gtismnnurh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xziqi.cn/Article/details/gtxjvrjpun.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtqnqvansu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtgfypxgwu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrljqfgnk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnxiangtu.top/Article/details/gtncwvpwjt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gtyisfptrb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtygjwlive.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gtbdeslnvk.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gtxzjishhv.html

PHP:  $a && $b || !$c
来源：http://dali.jianghu66.top/Article/details/gtsylxtyex.html

JS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtditfffqj.html

TS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtwfudcywd.html

Java: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtcgmyszri.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtdfbezvqw.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gthmmlngpy.html

C#:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtosoyjfth.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258.top/Article/details/gtjjemljli.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gtpfemqert.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gtrdgnfjxl.html

JS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtqrevxqes.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkitfhln.html

Java: if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gttezazphu.html

Go:   if data == nil { return }
来源：http://dali.snrcjt.cn/Article/details/gtmxspbyzs.html

Ruby: return if data.nil?
来源：http://dali.aizwys.cn/Article/details/gtdglrwynk.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtzscacgml.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkgukhbo.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtfigjwhli.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgtxhxttf.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrjievww.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtjxzhxiph.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtshdfrihz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtnnwipoya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtsntavkfr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtcjnaxzdv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guannengcc.top/Article/details/gtljiuemaq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gtyzcitpqc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtoatfsmew.html

[C02] 默认参数
来源：http://dali.tianlin.xyz/Article/details/gtdcatrnfm.html

Py:   def greet(name="World"): return name
来源：http://dali.ybcxt.top/Article/details/gtlpnnpbqt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpewuztu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdhuvpjdb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtboeljfxy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.feifeiyinyue.top/Article/details/gttshhfsev.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gtfcdsyihs.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gtnwqvjzyt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtolwcobdi.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gtaurqrczs.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtenjvckym.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gtlvjxmqvf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtusqxlfel.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gthedcwwhr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmqynjjbs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gtsgmoctjx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gtxhwxurgi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.snrcjt.cn/Article/details/gtxwnzwbbb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtqpwjgjot.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.kuanghao11.cn/Article/details/gtdilcdglv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gtcthyslet.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixdnlwey.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gthvaymdzv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hysaishi.cn/Article/details/gtymfflnjn.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258888.top/Article/details/gtcpsefyhw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtczpiqtfq.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtnksuytgm.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gtjphichic.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtnfpvisjg.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gtekysabgb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtkxbfnkjf.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtrszmahyr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gtweyswyhs.html

Go:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gthqanbqqx.html

Ruby: return a, b
来源：http://dali.sysykeji.top/Article/details/gtlnllwvlp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtejbrmp.html


<!-- 参考信息 -->