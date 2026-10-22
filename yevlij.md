代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigufen.top/Article/details/gtoinopwai.html

Java: (int) 'A'; (char) 65
来源：http://dali.ivvv.top/Article/details/gtckrilyco.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxinkj.top/Article/details/gtryxgscyk.html

Ruby: "A".ord; 65.chr
来源：http://dali.cheryme.top/Article/details/gtmosmdnpx.html

C#:   (int)'A'; (char)65
来源：http://dali.yonumen.top/Article/details/gtvsuldupx.html

[A19] 交换两个变量
来源：http://dali.hammf.cn/Article/details/gthptigqtc.html

Py:   a, b = b, a
来源：http://dali.redwolf501.top/Article/details/gtigkehfin.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinqigufen.top/Article/details/gtuoupbnyh.html

JS:   [a, b] = [b, a];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkufsjkoh.html

TS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gtchtwdgzs.html

Java: int t = a; a = b; b = t;
来源：http://dali.guannengcc.top/Article/details/gttmdjyzdb.html

Go:   a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gtcntmybvv.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gtvsfrrxvv.html

C#:   (a, b) = (b, a);
来源：http://dali.wangshuangyany.cn/Article/details/gtipbhckru.html

[A20] 读取标准输入
来源：http://dali.xziqi.cn/Article/details/gtcicrlhfb.html

Py:   name = input("请输入：")
来源：http://dali.dashuyun.cn/Article/details/gtcgzlhcyk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aibaodan.cn/Article/details/gtdvtlcbqk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.smart0.xyz/Article/details/gtggffofob.html

TS:   // Node.js：readline 模块
来源：http://dali.guowangkeji.top/Article/details/gtyajfuczo.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.havefunace.top/Article/details/gtuzxlxtck.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenzaomai.com/Article/details/gtvzunngcf.html

Ruby: gets.chomp
来源：http://dali.cqqwz.cn/Article/details/gtkzsenibd.html

C#:   Console.ReadLine();
来源：http://dali.wangdashe.top/Article/details/gtixiseofw.html

[A21] 保留指定小数位输出
来源：http://dali.gzhubu.top/Article/details/gtsvxhbmly.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhoulong.xyz/Article/details/gtywljxzsu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbyvbafx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtuugutnot.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtkfjvgfcu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtlhxkpgqz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtuzkjktmr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtujiggczh.html

C#:   3.14159.ToString("F2")
来源：http://dali.cqqwz.cn/Article/details/gtexjduhiw.html

[A22] 获取字符串长度
来源：http://dali.daxiang520.top/Article/details/gtvhqqslzo.html

Py:   len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbgzwevcl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.svipenyu.cn/Article/details/gtxtnovvlt.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tian-w.cn/Article/details/gtgdaktchf.html

TS:   s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrilgjna.html

Java: s.length()
来源：http://dali.shuidangran.top/Article/details/gtluiwpmrv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.daxiang520.top/Article/details/gtxaoapurh.html

Ruby: s.length
来源：http://dali.yangfankeji.com/Article/details/gtsqwofuri.html

C#:   s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtttbjrbdm.html

[A23] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gthpryfano.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtymsickwi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinqigufen.top/Article/details/gtexazizqz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gtzuvsvald.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gtvoemecta.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gtvhrsrqrs.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenzaomai.com/Article/details/gtklwetkgo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtuljyewvf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangdashe.top/Article/details/gtlttjxaru.html

[A24] 去除首尾空白
来源：http://dali.shzxlz.cn/Article/details/gtgnoiidve.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyuilrkc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ehwqpu.com/Article/details/gtdkjoodkl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guowangkeji.top/Article/details/gtbhctvvwz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sxryk.cn/Article/details/gtkclevsdy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhongyouzk.top/Article/details/gttjsetmeq.html

Go:   strings.TrimSpace(s)
来源：http://dali.zycfv.cn/Article/details/gtlcjxmtmh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cdnleiting.top/Article/details/gtwbngrpnq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258888.top/Article/details/gtwvxbejug.html

[A25] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtgvsvsyan.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yonumen.top/Article/details/gtabpyhsvz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tanke756.top/Article/details/gtmtewcfxn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gttiqllrko.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gtifrdzvzz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yangfankeji.com/Article/details/gtqxuryjzf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtbclojkye.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xziqi.cn/Article/details/gtlopmgbsh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzbctcte.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gtpjiumvro.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknuczrtx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pengpengdd.cyou/Article/details/gttfveigsz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yangfankeji.com/Article/details/gtjnrfatat.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ydzc1.top/Article/details/gtvksalljk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtbwcoxhjh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zycfv.cn/Article/details/gthpevegcp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hfpthk.cn/Article/details/gtfnogygvj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gtjuhwcxem.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfgfwgvdn.html

B. 流程控制
来源：http://dali.ivvv.top/Article/details/gtrhzaqixp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlgnibzfh.html

[B01] 条件判断 if / else
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkwtolkj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fzhhl.top/Article/details/gtviuvvocz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ehwqpu.com/Article/details/gtbijoqpaf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtvodphmqy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtaacaozcp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtbaqlbkcu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cheryme.top/Article/details/gtgakyruhq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gogol.net.cn/Article/details/gttljysvdd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtocmnwdow.html

[B02] 多分支 else if / elif
来源：http://dali.nanxuanxn.top/Article/details/gtkufjwdbz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yangfankeji.com/Article/details/gtepqncsfh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.bjfxy.top/Article/details/gtkjnxuntn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtaamzyefw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtoscrhtxf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtpyrpblke.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ydzc1.top/Article/details/gtckpbaojl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gtmxosxjwl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtwnhkycup.html

[B03] switch / match / case
来源：http://dali.guannengcc.top/Article/details/gtscrwrvrs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cashguo.top/Article/details/gtruamqnaj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gthyknkviy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfmeghpw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtomocympn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtjewfdchy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gtsipptfoc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.andypj.xyz/Article/details/gtktizurqc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gzhubu.top/Article/details/gtclesumqr.html

[B04] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtdvsmsdpv.html

Py:   for i in range(10): print(i)
来源：http://dali.gogol.net.cn/Article/details/gtngkwlkzm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sysykeji.top/Article/details/gtpdqeycgh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gtotlblbhw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gtdqrvzcqc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hysaishi.cn/Article/details/gtczwkunll.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jiagoushi.top/Article/details/gtrwuqcenm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.nwbrower.top/Article/details/gtavktdibh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtezjrtqzm.html

[B05] 遍历数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gtlehnqrjk.html

Py:   for item in arr: print(item)
来源：http://dali.hongshengwenyu.top/Article/details/gtrmmhveej.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.mhx1999.top/Article/details/gtsulkrwyp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hysaishi.cn/Article/details/gttyhtrydo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gtyxjiodbb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ybcxt.top/Article/details/gtukcqiosp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gtphyzbzrd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jqgfzy.top/Article/details/gtglnlzluo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yueranfly.top/Article/details/gtnqwslhin.html

[B06] 遍历字典 / 对象
来源：http://dali.wangshuangyany.cn/Article/details/gtktgbwfzk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guowangkeji.top/Article/details/gtqtkcryqh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dianchejie.cn/Article/details/gttycgugcw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yueranfly.top/Article/details/gtuzcxbdje.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtqjtdooun.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gtquoadrvh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj202588.top/Article/details/gtcdxucbsq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.feifeiyinyue.top/Article/details/gtcaqcrbfe.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhijiandao.cn/Article/details/gtswkevjtg.html

[B07] while 循环
来源：http://dali.yj202588.top/Article/details/gtrovmkrzp.html

Py:   while i < 10: i += 1
来源：http://dali.guowangkeji.top/Article/details/gttdfduipq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nanxinkj.top/Article/details/gtbvdonqcg.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtunrevpya.html

TS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtloktxrti.html

Java: while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtlxuxpyua.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ybcxt.top/Article/details/gtwazmmzwg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pycfn.com/Article/details/gtlqhpvxgu.html

C#:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtfiuocqgv.html

[B08] do-while（至少执行一次）
来源：http://dali.hongshengwenyu.top/Article/details/gtuuaolsus.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guowangkeji.top/Article/details/gtqtbfwitr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtrgllxdxq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtlcnfeccl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabymzxnm.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtuxbzkwgg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gtkskcdmfy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gtitqfmhyr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtjxhbqead.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gtrqbaafrt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gthltwnjbx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtfodrrfjf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtimriborb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtqqhqwyzm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gthyluthdg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuxming.cn/Article/details/gtuojbuynn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ydzc1.top/Article/details/gtkhdpsxcd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gthojrhvas.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gtbmyngmyp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jiagoushi.top/Article/details/gtafsgvocp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fengsongda.top/Article/details/gtylqkwotz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtojkimkps.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gtoqprgyzl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasnuaiif.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhoulong.xyz/Article/details/gtggimxcgn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.havefunace.top/Article/details/gtqvyfdcay.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xinyue.icu/Article/details/gtmyjsyele.html

[B11] 生成数字序列 / 区间
来源：http://dali.daxiang520.top/Article/details/gtcfjswmoc.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnqzz.top/Article/details/gtbwejvrgr.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gtqccsovhe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtdgsscdfw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gtebijvnqm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtkcbdbxhy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangshuangyany.cn/Article/details/gtavwaqecc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.haohaochexian.top/Article/details/gtajwkwsoe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258.top/Article/details/gtehngvhfv.html

[B12] 跳出多层循环
来源：http://dali.pycfn.com/Article/details/gtzolsazyl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpddrcbug.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yonumen.top/Article/details/gtdzdxgblp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtoaqhsfdv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfuhzpru.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtxfpwtjgi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuanzhike.top/Article/details/gtfrszxtsn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yongpay.top/Article/details/gtmgthvpnz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xylfe.cn/Article/details/gtxunarsqv.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwqfixvp.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gtwnurdpol.html

PHP:  is_numeric($x)
来源：http://dali.hysaishi.cn/Article/details/gtyboeulue.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtnaaaudve.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtjvzbkbxz.html

Java: x instanceof Number
来源：http://dali.zhixingplan.top/Article/details/gthnbllqws.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtjxgjptpx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkawnaxmh.html

C#:   x is int or double or decimal
来源：http://dali.nanxuanxn.top/Article/details/gtkftxrpea.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gtsbgtttxl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gtpilmagxj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gtefbwfjip.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtlflcpgru.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtljxmhgqh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtsrjpkcxl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jyoumei.cn/Article/details/gtpowkaknh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtdydhyxrw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtqpndldcu.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gtqkiiykhv.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtgczvthav.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gtpqjwpyna.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtxrhmtbcb.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtzxhtbucs.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtnthtmkwe.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtvzhudemo.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtkfskfnfx.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtdfvrhnqq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gtipqczasq.html

Py:   if not data: return
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpcwmslt.html

PHP:  if (!$data) { return; }
来源：http://dali.quarkkingdee.top/Article/details/gtoqquepux.html

JS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtswmsktqw.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gtgrwycwam.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlllghkgr.html

Go:   if data == nil { return }
来源：http://dali.guowangkeji.top/Article/details/gtqgrthibk.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtofnkixfz.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtblqvoorj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtofyngntq.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtxnhgwrqd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtupbskgfo.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtjkcyoggg.html

Py:   def add(a, b): return a + b
来源：http://dali.cdnleiting.top/Article/details/gtisthlale.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtzzzuwvez.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtwftvtodk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzeqjtog.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmobgpbrr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guannengcc.top/Article/details/gtyxecrfdt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gtbqoabjyj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtdeateuux.html

[C02] 默认参数
来源：http://dali.hywenlv.cn/Article/details/gtsfswlkma.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gtkwcdcimw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.birdmap.top/Article/details/gtnejqoulh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtzgwafrln.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzdhvwdws.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gtgsvpusoq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gtznqtldnn.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gtyhczivmf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yanxiufei.cn/Article/details/gtzbiarjmn.html

[C03] 可变参数
来源：http://dali.yj20258.top/Article/details/gtwrsubhzw.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuetiantiany.cn/Article/details/gtqcgtqize.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gtboqcbefi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtsjvyrszh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtxoiswodv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gtpczbbskl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gtlcapvznc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gtofnvgtry.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zycfv.cn/Article/details/gtzgydsmig.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gtdgxglykg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwikkdppt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtjkwvklms.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtobvqnyee.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.svipenyu.cn/Article/details/gtijzpkgdi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gtijqmphnv.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gtgymwtoos.html

Ruby: f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtgoduryhm.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtawmvvyyw.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gtlovwyklc.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtqxrvxasf.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gtbtbubgrz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gtxqeqnwqj.html

TS:   return { a, b };
来源：http://dali.gzhubu.top/Article/details/gtzxqqdcno.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyhlmeni.html

Go:   return a, b
来源：http://dali.tian-w.cn/Article/details/gthrwihzrw.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtvbssnljl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zdqjudy.top/Article/details/gtlgdsdqpo.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrovndfg.html

Py:   square = lambda x: x * x
来源：http://dali.jiagoushi.top/Article/details/gtgdqmwhbr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gtowijbsnq.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtndnjmyjx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtrqdiicdx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yangfankeji.com/Article/details/gtwaykopvc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gtfamzlbzv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtojamffpw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtppbciygw.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtdycbdjqi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuetiantiany.cn/Article/details/gtofuyrbfx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj202588.top/Article/details/gtxqzmyuif.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gtdknqmwlt.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gtznoxymhq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtzrbvvfqx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtwnquwyft.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gtitoauctb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtyccqagzl.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gtprevzyrs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gtzvfwpfct.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtkjpnitvk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtgmcpphnh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoqigquza.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gtffwqhjib.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenjidiqi.icu/Article/details/gtwcooginb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gtikrhyzqn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtvndueiag.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtfbdjpnzj.html


<!-- 参考信息 -->