代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtjycesvbe.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenjidiqi.icu/Article/details/gtyfkmkfgi.html

[A24] 去除首尾空白
来源：http://dali.yvedp.cn/Article/details/gtvwfqzbsm.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.nanxuanxn.top/Article/details/gtaewhucoe.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.kuanghao11.cn/Article/details/gtyvbujgex.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.andypj.xyz/Article/details/gtaosufykt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gticpdmyhp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxuanxn.top/Article/details/gtulwkmeqo.html

Go:   strings.TrimSpace(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtitxmubxg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cdnleiting.top/Article/details/gtkbvnenbi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.haohaochexian.top/Article/details/gtbtqeusnw.html

[A25] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrbcacil.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sufxvd.cn/Article/details/gtdciimzde.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aizwys.cn/Article/details/gtpwubrnbw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.haohaochexian.top/Article/details/gtceqzqmzo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtwwaoamek.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.0kj1m.cn/Article/details/gtdwxwajbg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gtvpdswhrf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gaohongyu789.top/Article/details/gtdzvcgean.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.pengpengdd.cyou/Article/details/gtqdujpfeh.html

[A26] 类型转换总览
来源：http://dali.cucudq.cn/Article/details/gticadmyew.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shzxlz.cn/Article/details/gtinwbpbvw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hywenlv.cn/Article/details/gtnluhzokx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sufxvd.cn/Article/details/gtaobskxma.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hywenlv.cn/Article/details/gtjfwsrffz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gthlfceiyu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guannengcc.top/Article/details/gthrsomewk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtvcvnyqoc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.guannengcc.top/Article/details/gtmmuxzbgb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxxdhzlet.html

B. 流程控制
来源：http://dali.316326.xyz/Article/details/gtvhbvopay.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthazppowj.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gtrnduovru.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtviqldbag.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwknlelhg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gtmolvotpd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtapxusfhe.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtujoawuxy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xinyue.icu/Article/details/gtndldvidp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ybcxt.top/Article/details/gtikomydew.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtjtumfblq.html

[B02] 多分支 else if / elif
来源：http://dali.hfpthk.cn/Article/details/gthdaoqwpo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gzhubu.top/Article/details/gtsmqkxpbn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hnxiangtu.top/Article/details/gtworqqkae.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtmszjicrl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gttsfkigdr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtbjrkhkbd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.chenlongwang.top/Article/details/gtftogctdj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jqgufenzy.top/Article/details/gtieigzcxu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtysegoinn.html

[B03] switch / match / case
来源：http://dali.meibo888.top/Article/details/gturutyngt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gtouvurkfx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gtjxliwljk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gtzcokkxnf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtzuhebouj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtmvzhuzyd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj202588.top/Article/details/gtzhdayuez.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuetiantiany.cn/Article/details/gtbnohzbhg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gthdszolkz.html

[B04] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gttziqewjn.html

Py:   for i in range(10): print(i)
来源：http://dali.smart0.xyz/Article/details/gtmghqowiq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sweek.top/Article/details/gtidwgwhzg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbwollpzg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hfpthk.cn/Article/details/gtalwcnnhl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtdhdecqlx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqnlwkoa.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthagbwioz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuanzx.com/Article/details/gteqgojiqq.html

[B05] 遍历数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtksuzpzha.html

Py:   for item in arr: print(item)
来源：http://dali.sweek.top/Article/details/gtptlrwrsp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gtlxacpfbj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtcomkiurd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtqiwegjty.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtfnjeatuf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hysaishi.cn/Article/details/gtkczqpchk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.smart0.xyz/Article/details/gtvcruvcca.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvhtojodn.html

[B06] 遍历字典 / 对象
来源：http://dali.chenjidiqi.icu/Article/details/gtwexgcpyz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhengqikj.top/Article/details/gteocbyyjq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ivvv.top/Article/details/gtyfxrdbvc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtgqlxjqjq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtmokixjae.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gtjvacejqz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.vqdsnc.cn/Article/details/gtmzgdvmms.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtppjgikvw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gtdrtjihds.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gtsyummbxp.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigufen.top/Article/details/gtfeapoztc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtwbxxdmap.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtgpzchbwi.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxcbwjlw.html

Java: while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtewffyuag.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhongyouzk.top/Article/details/gtldqordrv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258.top/Article/details/gtbereqtyd.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtnkgorypz.html

[B08] do-while（至少执行一次）
来源：http://dali.xylfe.cn/Article/details/gtnhluejba.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gtncfodtaf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtoptyznjg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtqbpzdzcc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtaqjcmhsd.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtayelnozs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ivvv.top/Article/details/gtjvvbylpn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dashuyun.cn/Article/details/gtgnihhpln.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtlhugggmx.html

[B09] break 与 continue
来源：http://dali.gotoacloud.top/Article/details/gtnkakxbnv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangdashe.top/Article/details/gtqxefvowy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtzxkxqili.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtyaijkuhp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtwpxfodki.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtlxamzhjz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtfvhhksir.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.pengpengdd.cyou/Article/details/gtkldosjar.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtlqdtumot.html

[B10] 遍历同时拿索引
来源：http://dali.hongshengwenyu.top/Article/details/gtrkfkilon.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gtyspfnrzb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yonumen.top/Article/details/gtwoozczxo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gthudeyhgd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtcmsebnfd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxinkj.top/Article/details/gtyangpkaj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnqzz.top/Article/details/gtapqqypiz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gtsbiuvvro.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ppjwa.cn/Article/details/gtiqmdxzcl.html

[B11] 生成数字序列 / 区间
来源：http://dali.haohaochexian.top/Article/details/gtnjpalnwn.html

Py:   list(range(0, 10, 2))
来源：http://dali.andypj.xyz/Article/details/gtplohvwex.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gtetjeydjl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtkfzngnyg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.9152youxi.cn/Article/details/gtoguozqjg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gtbwwofswb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yangfankeji.com/Article/details/gtbzhjmjou.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gtnwkvkmov.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.snrcjt.cn/Article/details/gtbybukfyo.html

[B12] 跳出多层循环
来源：http://dali.yvedp.cn/Article/details/gtrhdhtkoy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jianghu66.top/Article/details/gtxgffbkig.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.redwolf501.top/Article/details/gtkgysztks.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtssgglxxl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtgqzjosdg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtteblcxlz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ivvv.top/Article/details/gtwotrhojl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daria6918.cn/Article/details/gtmmxcxjbc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gteegbbsrz.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gtzoiglioy.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj202588.top/Article/details/gtxwrebhnb.html

PHP:  is_numeric($x)
来源：http://dali.wangdashe.top/Article/details/gtebfssyki.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gteusjzutt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtvqqsyaga.html

Java: x instanceof Number
来源：http://dali.c1oappe.top/Article/details/gtgewahbgr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gtmcadoond.html

Ruby: x.is_a?(Numeric)
来源：http://dali.iojbl.cn/Article/details/gthymizlko.html

C#:   x is int or double or decimal
来源：http://dali.xuanzx.com/Article/details/gttrlissxw.html

[B14] 判断值是否在集合内
来源：http://dali.andypj.xyz/Article/details/gtfsoeapan.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shzxlz.cn/Article/details/gthjwkchyt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangshuangyany.cn/Article/details/gtaovucqsm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtpuqbaqir.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gtznrufxwi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gtofevxiyr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gteosyshun.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjogyklbs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtftnhrsqw.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtffpzrsyv.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gtehndakzw.html

PHP:  $a && $b || !$c
来源：http://dali.vqdsnc.cn/Article/details/gtahybjgkr.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtvpezekfe.html

TS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtpvbhiasb.html

Java: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtoqjzrlzw.html

Go:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtjnstsuwx.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtijklmeqb.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtdtuufggi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.mhx1999.top/Article/details/gtnhdwfjry.html

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gtaxjhgbne.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmuwegxlj.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtnjtohzdc.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtuqnslevt.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtqmxpldbn.html

Go:   if data == nil { return }
来源：http://dali.aibaodan.cn/Article/details/gthwbgfrdr.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtflqybazz.html

C#:   if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gtwjguodxe.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqmlfdrlz.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtirdsdymr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkxptfjje.html

[C01] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtquhjcieq.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtdbbrkksc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtdaummkdd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkrdxdzg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtsgsmoaur.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtgzrgrzkf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtxxzzmrot.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuanzx.com/Article/details/gtabwsusta.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyzpkgmf.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gtkanvfsmw.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtzjcpwmxr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gtjznbakla.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtgkoxfxos.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtpufgwqms.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gaohongyu789.top/Article/details/gtcwqsyfay.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtmojokkut.html

Ruby: def greet(name = "World") = name
来源：http://dali.jyoumei.cn/Article/details/gtnvoqguwr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gtdggqxmwr.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gtaamiimjt.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gtgouiyzot.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hammf.cn/Article/details/gtuqaoqljx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtpjqvhykk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgnfstol.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtylfmhxbz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gtgownrlih.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gtvsovqprv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.kuanghao11.cn/Article/details/gtmscboutq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daria6918.cn/Article/details/gtogblixts.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtkhnyfequ.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtfjxwiyep.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtbaqdenan.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.svipenyu.cn/Article/details/gtvwevkhmu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gtoaiboeiz.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gttzfauwif.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtspoxzogq.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtpvaywujd.html

[C05] 返回多个值
来源：http://dali.haohaochexian.top/Article/details/gtxbslunfh.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtaqjsviru.html

PHP:  return [$a, $b];
来源：http://dali.cheryme.top/Article/details/gtnjcdvmur.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtbzgdgnrs.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gttgtcqlrm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jlsjyb.cn/Article/details/gtuslgnzyd.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftorzxmv.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtnogffiwb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gthgxrkgyi.html

[C06] 匿名函数 / lambda
来源：http://dali.iojbl.cn/Article/details/gtphbgwlzl.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gtxphuwpvf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gtxhrvfwnt.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtkxwxjppy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtgslldzhr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hysaishi.cn/Article/details/gtmncrjzac.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.svipenyu.cn/Article/details/gtletcuaua.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gtorsaunnp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtcsslevsk.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gtpipbogpw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gtruwacbxk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtsffqytja.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtgegctuwk.html

TS:   arr.map(String)
来源：http://dali.dashuyun.cn/Article/details/gtbpnoamxc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gttbqdrhdb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenlongwang.top/Article/details/gtuzouelcc.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gtgrsntrji.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258.top/Article/details/gtesyfkrwg.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtvnejsdge.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gttuxgudhw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gtcjodqbtl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkkutjch.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtajyxxphn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gtvbdowhgy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gtkaiwxfxt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hysaishi.cn/Article/details/gtgjxgclie.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtfgjtbkzc.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gtvujmjrog.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gtznpypvvl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtkpeyosza.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtsyzihnrd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gttqfaiout.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gtohkkduhp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gtvgaazgtc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtfwroaifa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gtjikadfim.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gtzylmxgxo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gtulolfnmi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gthvuwiant.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtpplpxzdj.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoetnxgo.html

Java: 方法内为块级作用域
来源：http://dali.tanke756.top/Article/details/gtjqvsgpzd.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gtpqofmnyl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gtkqljfozt.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gtyvspnwkg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gtdyuwwata.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gtqfkybjyd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gtbidxwhis.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.birdmap.top/Article/details/gtrqoivfyc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gtbslahgdy.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtgixxptrx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gtdzbqjkip.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zycfv.cn/Article/details/gtoedjyerz.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtrmaqgodc.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gtbrcncyzo.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gtaozfxlcl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gtwbjrjspk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gttvrhnipx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtzlddwpfu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gtrkjmpfki.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sysykeji.top/Article/details/gtfrkpqftn.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtkuiaryit.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gtqplpggzl.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzujccgl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gtuaxulneb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtxyrzklrp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gtfwkbwxiu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtppoiekzp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtgkhuohfu.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gtudvkmnkb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hammf.cn/Article/details/gteitsmuzs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gtmillzsxw.html

[C14] 泛型函数
来源：http://dali.fengsongda.top/Article/details/gtcflleiqk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sufxvd.cn/Article/details/gtldphlorf.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfluhmqje.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtqvdyaslp.html


<!-- 参考信息 -->