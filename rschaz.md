代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.gzhubu.top/Article/details/gtedfbknhs.html

Py:   ord("A"); chr(65)
来源：http://dali.redwolf501.top/Article/details/gtrudhcuhn.html

PHP:  ord("A"); chr(65)
来源：http://dali.jlsjyb.cn/Article/details/gtklovkmda.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhengqikj.top/Article/details/gtmieojnsy.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cashguo.top/Article/details/gtsyjnhbyu.html

Java: (int) 'A'; (char) 65
来源：http://dali.yangfankeji.com/Article/details/gtrhnmphsv.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.iojbl.cn/Article/details/gtlfcvieds.html

Ruby: "A".ord; 65.chr
来源：http://dali.xuanzx.com/Article/details/gthsyvgheq.html

C#:   (int)'A'; (char)65
来源：http://dali.zhoulong.xyz/Article/details/gtevejyjqs.html

[A19] 交换两个变量
来源：http://dali.fzhhl.top/Article/details/gthkexcvzs.html

Py:   a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gtegddezyi.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.havefunace.top/Article/details/gtmmfwlwqq.html

JS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyummpfj.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgufenzy.top/Article/details/gtgohrtmug.html

Java: int t = a; a = b; b = t;
来源：http://dali.hywenlv.cn/Article/details/gtucaseusw.html

Go:   a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gtqukehryg.html

Ruby: a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtmozcuuxi.html

C#:   (a, b) = (b, a);
来源：http://dali.9152youxi.cn/Article/details/gtoxgmijgl.html

[A20] 读取标准输入
来源：http://dali.gogol.net.cn/Article/details/gtwgcenhty.html

Py:   name = input("请输入：")
来源：http://dali.xinyue.icu/Article/details/gtbetmsins.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlcfrlsj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.fengsongda.top/Article/details/gttdngrzzv.html

TS:   // Node.js：readline 模块
来源：http://dali.shzxlz.cn/Article/details/gtuxbkpliz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jyoumei.cn/Article/details/gtrlawwine.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gotoacloud.top/Article/details/gtkqkcdhun.html

Ruby: gets.chomp
来源：http://dali.zhixingplan.top/Article/details/gtahzdtzcw.html

C#:   Console.ReadLine();
来源：http://dali.haohaochexian.top/Article/details/gtsduplrza.html

[A21] 保留指定小数位输出
来源：http://dali.ivvv.top/Article/details/gtdtzceznw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cqqwz.cn/Article/details/gtetsliavr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikloykxp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gthzxqfnth.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtggttulkv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtohfezomx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtmdcsrxbj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gthsqzscye.html

C#:   3.14159.ToString("F2")
来源：http://dali.yongpay.top/Article/details/gtgcqbyjzb.html

[A22] 获取字符串长度
来源：http://dali.zycfv.cn/Article/details/gtbbehsxbc.html

Py:   len(s)
来源：http://dali.ivvv.top/Article/details/gtzygatvfr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.havefunace.top/Article/details/gtgruexpfv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cashguo.top/Article/details/gtrozvtihj.html

TS:   s.length
来源：http://dali.316326.xyz/Article/details/gtgoqbbicp.html

Java: s.length()
来源：http://dali.sysykeji.top/Article/details/gttiswtaof.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yonumen.top/Article/details/gtdhpvcvtj.html

Ruby: s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtybysiwiv.html

C#:   s.Length
来源：http://dali.bjfxy.top/Article/details/gtuxfheumj.html

[A23] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtwdixthoh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cashguo.top/Article/details/gtraarlxys.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jianghu66.top/Article/details/gtyidthtbo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gtnwsmufda.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gtszlosolz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gtchkchtli.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.tanke756.top/Article/details/gtqzfiwyub.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtkbjseuet.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xziqi.cn/Article/details/gtpljikyra.html

[A24] 去除首尾空白
来源：http://dali.havefunace.top/Article/details/gtcsrdyjzg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cheryme.top/Article/details/gtvwyqzkwc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.smart0.xyz/Article/details/gtgqpwlozu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gtcdfvfsyy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gtefyxgpec.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhiwuduotai.top/Article/details/gtfbfpwotp.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhengqikj.top/Article/details/gtrlbgzgoz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shanyushiyangtech.top/Article/details/gtttszsoih.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yueranfly.top/Article/details/gteylvbtip.html

[A25] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtfotccqdp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yvedp.cn/Article/details/gtitbbjrum.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hfpthk.cn/Article/details/gtgucfhgid.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxuanxn.top/Article/details/gtkfceydhm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yongpay.top/Article/details/gthohuvvva.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.svipenyu.cn/Article/details/gtcwypixsu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gtggdrvkgk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tianlin.xyz/Article/details/gtbovzthqm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtaoaospay.html

[A26] 类型转换总览
来源：http://dali.yvedp.cn/Article/details/gtwnktmfiv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zycfv.cn/Article/details/gtzdbblnhg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.vqdsnc.cn/Article/details/gtuxxygyuq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.guannengcc.top/Article/details/gtraianokp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nwbrower.top/Article/details/gtjchhzhzi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gttxrvtqyr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.feifeiyinyue.top/Article/details/gtsnvnnatg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtmmnwctcx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtznpsjmni.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtaskshwmd.html

B. 流程控制
来源：http://dali.zhiwuduotai.top/Article/details/gtawjtogyx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmvcjjxno.html

[B01] 条件判断 if / else
来源：http://dali.jianghu66.top/Article/details/gtszaqduni.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gtjncdbpsr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pycfn.com/Article/details/gtvcsfdywc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtqmpwozvi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtosciladm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtwsntfvrd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnqzz.top/Article/details/gtbgnpgmnw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.316326.xyz/Article/details/gttvturjfk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtxoiowbdi.html

[B02] 多分支 else if / elif
来源：http://dali.gaohongyu789.top/Article/details/gtpbvixgdv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zycfv.cn/Article/details/gthsnkrbck.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xylfe.cn/Article/details/gtsijxkiog.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtksybvqdc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtsmmxanpn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtwpenjrpe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gogol.net.cn/Article/details/gtreijeyga.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cdnleiting.top/Article/details/gttwpraxqd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gteviwqlvd.html

[B03] switch / match / case
来源：http://dali.jiagoushi.top/Article/details/gtlgitozqp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shangyingyoupin.top/Article/details/gtuhppxxbx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtzpqxdbmz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtztohggpe.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtjzxtsbib.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtwuotmbxt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.iojbl.cn/Article/details/gteniwligo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxinkj.top/Article/details/gtkkdysqdf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gtbseymzan.html

[B04] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtlcvkokss.html

Py:   for i in range(10): print(i)
来源：http://dali.cdnleiting.top/Article/details/gtqcsvwosg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tian-w.cn/Article/details/gtxfwjdjpj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxmqdmlll.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtxhjkggpq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtagxwedwu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gtbqktxgsz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbhojpoc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xziqi.cn/Article/details/gtjldbkjmp.html

[B05] 遍历数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqsullrs.html

Py:   for item in arr: print(item)
来源：http://dali.zhoulong.xyz/Article/details/gtwnkrjwzi.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jianghu66.top/Article/details/gtpqfdfxys.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtmxpgutpd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlqmfzbzt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtmlbhhlfx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gtkxdffbug.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ydzc1.top/Article/details/gtgzqsoebn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xinyue.icu/Article/details/gthvosiijt.html

[B06] 遍历字典 / 对象
来源：http://dali.gogol.net.cn/Article/details/gtizbvtehu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yueranfly.top/Article/details/gtdxvuugij.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dashuyun.cn/Article/details/gtpyamiblu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.snrcjt.cn/Article/details/gtbhepdbfg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbduxdyue.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gtqxqhhexo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gaohongyu789.top/Article/details/gtvadqwkfl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhiwuduotai.top/Article/details/gttjlrqngq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtgifedebm.html

[B07] while 循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtclpzrvqe.html

Py:   while i < 10: i += 1
来源：http://dali.cheryme.top/Article/details/gtklcikysf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.andypj.xyz/Article/details/gtbtbvvick.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfovzdgx.html

TS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtkywzkaja.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtwzvurdfm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gtoqhccboi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258888.top/Article/details/gtdbsptrbj.html

C#:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gteycvtefd.html

[B08] do-while（至少执行一次）
来源：http://dali.snrcjt.cn/Article/details/gtnuyanvds.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daxiang520.top/Article/details/gthretyaui.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.haohaochexian.top/Article/details/gthyrscvgv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtbpxgbzsu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtxxhhudsp.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtgysildge.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtvxntgbdv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhhiokqf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtjcxqgnyw.html

[B09] break 与 continue
来源：http://dali.cashguo.top/Article/details/gttfoxcsut.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daxiang520.top/Article/details/gtpexywlqi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtryzqebay.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtksiandnw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtqdyddgvk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtenqlonpd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gtwgqtjlhv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ehwqpu.com/Article/details/gtjhpyrpds.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtogfptbhe.html

[B10] 遍历同时拿索引
来源：http://dali.sysykeji.top/Article/details/gtqvcfokzs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gthyltgowh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvfhawczv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gtygpgjpzj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtiqouynqm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gtiwinhiup.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gtzfospvmz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhengqikj.top/Article/details/gtxpaenlhg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gtegxagidh.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuanzx.com/Article/details/gtfbkuwvyx.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gtguikvbah.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gtnddjuada.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gtvvvhljam.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvpmbaur.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.redwolf501.top/Article/details/gtjlmsgrhl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqtsexen.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtfchkedlh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuxming.cn/Article/details/gtbmhkmfwp.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gtkpbqqfjl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gtqssmkisq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aizwys.cn/Article/details/gtdsfpjscv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtgtqctjev.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtndhqhjja.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtodbleouv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gtkekbkndd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gtenkgkzng.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gtljirfbvz.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gtamzkmvsp.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtkthumbou.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtasnkzitf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtmsknuuqs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtrxrehjbf.html

Java: x instanceof Number
来源：http://dali.wangdashe.top/Article/details/gtdarxbvkq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.kuanghao11.cn/Article/details/gtbgtirgrd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gtkerdmvup.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gtjjeytgvk.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gtssrjfhdz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gtpxduxptt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangtech.top/Article/details/gtszkzmllp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtyhbcsahx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtkktscwin.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtrxngbagx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.meibo888.top/Article/details/gtkehxlcus.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwahypwzk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtyeljuhmp.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtwydtaqlj.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gtalwajkrx.html

PHP:  $a && $b || !$c
来源：http://dali.xuanzx.com/Article/details/gtqndqdbhp.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtoddzvsen.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gthidvbhdg.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtwisudiik.html

Go:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gttfnutjhs.html

Ruby: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtzdvolqwj.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtvdbqclwf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258.top/Article/details/gtzymlrrsc.html

Py:   if not data: return
来源：http://dali.cqqwz.cn/Article/details/gtxoykrjyq.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gtxxdthjir.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtzzqjgucq.html

TS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gtdhvlmzar.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtdifognyk.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gttexkiycp.html

Ruby: return if data.nil?
来源：http://dali.xziqi.cn/Article/details/gtwvvukgbx.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtuneqzcxl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtoujsbizg.html

C. 函数与作用域
来源：http://dali.meibo888.top/Article/details/gtsvyfyaxa.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdfhcykz.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gttmwrqyzw.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gtciohpjfg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gttfhyhacf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsnrmcqo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtuxexwwgs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtnkrluynd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gtywwdtkcn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtszbsxllx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtkbjjtrjg.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtxkbunfsy.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258888.top/Article/details/gtnfxchhfl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlundjuzj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtumnpkfbt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtginakkbt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gtyedgrioa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gtadlbqoqe.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gtwwqlknlt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.andypj.xyz/Article/details/gtnwooxkpq.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gtqipurcrp.html

Py:   def total(*args): return sum(args)
来源：http://dali.aibaodan.cn/Article/details/gtxwzulihf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gtczsksunq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtiynmslqs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtgcycbgfq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gtamiqgeav.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gtfdrvxoxw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daria6918.cn/Article/details/gtvlucoykp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gtzzahhdnf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gtoynjmlwv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yonumen.top/Article/details/gtdbksvulr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gtyavankge.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtolfjxgxu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gtqqxmftvg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gtebnbnniy.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtuyijbazs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtlebdfqmn.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtxbpyygov.html

[C05] 返回多个值
来源：http://dali.chenjidiqi.icu/Article/details/gtgzynxmhl.html

Py:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffzbtfgb.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gtcxqepshs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.316326.xyz/Article/details/gtnwcguryi.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtkexuoxzc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gtgismmipm.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtndkbyqcs.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtflogyomo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtdasiipgh.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtstqigpvp.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gtriwkbxlx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtmymlcjan.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtvxmatycw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuanzx.com/Article/details/gtjrrkwjgr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtcvkidcgh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shzxlz.cn/Article/details/gtgzduvpwj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtbfhljgrj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtgfvqmjdx.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gtucjsgtdd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuanzhike.top/Article/details/gtfckesksz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gtfevatgal.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gtdtqssmqf.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteysbklkv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daria6918.cn/Article/details/gtmvxxwikt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gtgokihkst.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtcjdymjek.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenzaomai.com/Article/details/gtjoxhotlv.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtjicmrndn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gtnbivcrhm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gttoxjeszs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtshqpocws.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtxelugjqu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gtsvtohofp.html


<!-- 参考信息 -->