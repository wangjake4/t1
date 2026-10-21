代发 wailian999

[A26] 类型转换总览
来源：http://dali.ydzc1.top/Article/details/gtsytuomrt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tanke756.top/Article/details/gtlxwkckjv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.kuanghao11.cn/Article/details/gtaudjqsld.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.smart0.xyz/Article/details/gtohycclmr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fengsongda.top/Article/details/gtiykrxumo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gtxofisnvd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hongshengwenyu.top/Article/details/gteemlzmmz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yvedp.cn/Article/details/gtqjfljluw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gtrkvahqmv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtaphncztd.html

B. 流程控制
来源：http://dali.aizwys.cn/Article/details/gtytuawpoc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnefnfkfa.html

[B01] 条件判断 if / else
来源：http://dali.316326.xyz/Article/details/gtjcftibcl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.snrcjt.cn/Article/details/gtnlypreau.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zdqjudy.top/Article/details/gtsghvyppy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsyhjdpy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtatxemyhc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtuteuqrvc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pengpengdd.cyou/Article/details/gtmuxjhckw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fzhhl.top/Article/details/gtxiiqvcgc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtcarffprd.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gtayftiucr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.9152youxi.cn/Article/details/gtcojghapm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yangfankeji.com/Article/details/gtrvmflszx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtwjfpwnad.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gtnvbhsjsw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gtplsfhumw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gtsrvrzthk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shuidangran.top/Article/details/gtluozfapg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gthjrtpixc.html

[B03] switch / match / case
来源：http://dali.xinyue.icu/Article/details/gtdvjnlsbd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ybcxt.top/Article/details/gtykoysqbn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtvkrjtdis.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtsmajdfvu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvxxczedh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtibevbwrp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gtbnunhexm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.mhx1999.top/Article/details/gtynhmemls.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fzhhl.top/Article/details/gtyerkqiso.html

[B04] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtbbrfjczx.html

Py:   for i in range(10): print(i)
来源：http://dali.shzxlz.cn/Article/details/gtwkjahqun.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gogol.net.cn/Article/details/gtsztzlewi.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gtpviidvdk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtaemiwkep.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenzaomai.com/Article/details/gtumztiixb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aibaodan.cn/Article/details/gtzjvkigoo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yonumen.top/Article/details/gtgsqpbuzk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yongpay.top/Article/details/gtfyftifio.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtwdpuijtd.html

Py:   for item in arr: print(item)
来源：http://dali.snrcjt.cn/Article/details/gtpwixstbu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gzhubu.top/Article/details/gtxbsepfdr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gtwwubzzoy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hysaishi.cn/Article/details/gtncmtoxbg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnhjuhyca.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.fengsongda.top/Article/details/gthydrouyz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.snrcjt.cn/Article/details/gtbgwlmcpr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yvedp.cn/Article/details/gthjsvacsj.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gtmprdlzso.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ppjwa.cn/Article/details/gthyghxolw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gaohongyu789.top/Article/details/gtrvbliafh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gtyvbxihvd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtlhsutbis.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cheryme.top/Article/details/gtidaeyllf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guannengcc.top/Article/details/gtebgccxjx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ppjwa.cn/Article/details/gtdegisdnd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cucudq.cn/Article/details/gtgyfsteeb.html

[B07] while 循环
来源：http://dali.tianlin.xyz/Article/details/gtvwjdylpv.html

Py:   while i < 10: i += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpdohhgz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cheryme.top/Article/details/gteszzdags.html

JS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtxphkxnfg.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtkdgfdnzp.html

Java: while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtjkxhidhz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hnxiangtu.top/Article/details/gtciaaczjm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gtaqujkvjs.html

C#:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtdmhnitrk.html

[B08] do-while（至少执行一次）
来源：http://dali.hnqzz.top/Article/details/gtbyjkgmqn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.pengpengdd.cyou/Article/details/gtvhlrbhny.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gtwdgjuolu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gterrrvqgp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtflgxbnsj.html

Java: do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtkoygnnds.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtjfnyzayu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxinkj.top/Article/details/gtcmjaeass.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtydymwlib.html

[B09] break 与 continue
来源：http://dali.wangshuangyany.cn/Article/details/gtrahmbgzz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ehwqpu.com/Article/details/gtsbfdupld.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtlygcywpl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtukmadbqq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtquwfmpey.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtyrhvldwo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gtxhqtpxeh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gtqefmtbem.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtvpoxfbkq.html

[B10] 遍历同时拿索引
来源：http://dali.cdnleiting.top/Article/details/gtmoxqjbch.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gaohongyu789.top/Article/details/gtvcdnupts.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtumgknffi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtkvaibjns.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gtmvwzevxv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxuanxn.top/Article/details/gtnwxfrpyu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gthhzpyzdj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtivefbjko.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.bjfxy.top/Article/details/gtaxtskwpj.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gtlsdfnxot.html

Py:   list(range(0, 10, 2))
来源：http://dali.9152youxi.cn/Article/details/gtyqzyxdhd.html

PHP:  range(0, 10, 2);
来源：http://dali.zdqjudy.top/Article/details/gtatpjmrfa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ehwqpu.com/Article/details/gtiapznlvt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtusvdkasy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gtayjztpeh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gttzefsdae.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sysykeji.top/Article/details/gtwbzfgwou.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gzhubu.top/Article/details/gtlmovntqq.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gtoqhcnkbb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gtrssmmddh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj202588.top/Article/details/gtemaomnwm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtfvganipl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtwwyvctka.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebpgvyaf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.meibo888.top/Article/details/gtftdyemzk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtmgayvpcq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gtwwujqnql.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gtogbsdird.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gtlkzudbyg.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gtpkzgqrbe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtxadatkkj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtvwlxxkif.html

Java: x instanceof Number
来源：http://dali.havefunace.top/Article/details/gtxbbgpkex.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtnjytlslp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cheryme.top/Article/details/gtpnkgqwqr.html

C#:   x is int or double or decimal
来源：http://dali.cheryme.top/Article/details/gtriekwwrt.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gtgtidqjhg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nwbrower.top/Article/details/gtezlvvuud.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gtnimkrqmh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtmundykct.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtdnhktahj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxngfxdi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkjesxwm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtnnhqomae.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtmumrhgkt.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gtttpiwnxr.html

Py:   a and b or not c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyptuofr.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gtyrdktmqc.html

JS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtpjljtaxi.html

TS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtkkdtsekj.html

Java: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtvewyenhb.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtjxqtviqn.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtwbuhcufw.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtcgpfhcjp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtunttxtfo.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gtencvrgvu.html

PHP:  if (!$data) { return; }
来源：http://dali.dianchejie.cn/Article/details/gtfbzdnkkk.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtkowuwvwy.html

TS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gtqnnivsva.html

Java: if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtcsbzobke.html

Go:   if data == nil { return }
来源：http://dali.hywenlv.cn/Article/details/gtgqvfosup.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gtlonawnra.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtdfshihdd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtekkfhbey.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtbkrftump.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjfedymkq.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gtoorcahjv.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtsvvhozej.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtrpdppckm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtmrxfvwtt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gthjowaxyd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtzkoyogfe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gtswezzody.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gtpiwxdrxc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtprjovjut.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gtogqewvfc.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gtvdrjlhgj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gtxusjiqzr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gthoycqcnj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtbasmuamh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gtasfoygdr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hywenlv.cn/Article/details/gtxztcxupc.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtplajvati.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuanzx.com/Article/details/gtdmdluygz.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gtqvcwwwqh.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gtnkqvyage.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cashguo.top/Article/details/gtgetqaick.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtjqksrjnv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkzuglrw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gthpzxjvre.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxuanxn.top/Article/details/gtjeoqvlnj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwiryjosu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtyevnyqtr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtzbmqdbyn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gtqqjpzhpf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xylfe.cn/Article/details/gtpfquinfc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtagcehusz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sweek.top/Article/details/gtiscgyrtw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngjzjqgx.html

Go:   // 无：用配置结构体参数
来源：http://dali.feifeiyinyue.top/Article/details/gtbhsopcrx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtrueyoptu.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtmouxjmnf.html

[C05] 返回多个值
来源：http://dali.0kj1m.cn/Article/details/gttcmgcflk.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtkdhxzxvt.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gtdwacilkh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gttfdzcfwb.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtedefojwz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqurtcni.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtsxpwebgo.html

Ruby: return a, b
来源：http://dali.redwolf501.top/Article/details/gttlhckfpe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gtrycwyyrf.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gtrwlbhbqq.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gteizjinky.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gtjsucmzxe.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gthzfhaoqk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gtelqkmebd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtajhpqozx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gtrlnzuegw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtugukvjim.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtjlqocnzc.html

[C07] 把函数作为参数传入
来源：http://dali.sxryk.cn/Article/details/gtzlskofwt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gtykrtlfkj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gtsuqrfxxr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gtyqytrcbn.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtavzabvhf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daxiang520.top/Article/details/gtwlngetjv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.haohaochexian.top/Article/details/gtpudkjwgq.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gtbnbzpvrh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gtgiuyxnoe.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtmqkxayvo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gtkphmoagv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpvrwcxsb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gteswngkas.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtglvxllzt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenzaomai.com/Article/details/gthholmvdw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtcethnros.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pengpengdd.cyou/Article/details/gtqahbooht.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gteehldxlj.html

[C09] 递归
来源：http://dali.quarkkingdee.top/Article/details/gtzicdbvzz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtmldtywqv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqzyeshdf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtwnwuxfwh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtlgmoeskj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtdjrsdjqq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangshuangyany.cn/Article/details/gtuefyidqh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtebupyohj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtckranqiq.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gtgcbubodo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gtrvqymskw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqnrjirc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gtqhdwzapv.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtygygburv.html

Java: 方法内为块级作用域
来源：http://dali.yj202588.top/Article/details/gtcmytehqv.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskafaqfv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gtysgeiauq.html

C#:   块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtuoncavfk.html

[C11] 模块导入与导出
来源：http://dali.hongshengwenyu.top/Article/details/gtdkkvstso.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gtygtjvvuh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gtyexhakbq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtxrxvlqmm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtmdoouiai.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gtkrayupky.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jiagoushi.top/Article/details/gtsjlcyvyv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtjzvulntl.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gtxwvuwwze.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gtneqapvik.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gtgxqpxqoq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gtmjdxgajc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtfxxinuct.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtyajpfcja.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gtlecbomqz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gthlivtljx.html

Ruby: -> { puts "run" }.call
来源：http://dali.sweek.top/Article/details/gtxzhgqgcs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtjongvkpl.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gthtamvqni.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gtonfmrwco.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtlaggmznl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gthmnuzokt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqwvovewh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfmnjaikg.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtzcugxpya.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gtzmewypba.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gtqzyxilie.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtwtqhayrn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gtcdjlctla.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtnvfcvckg.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtmezlzwnb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtuueadczo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shzxlz.cn/Article/details/gtnplcqckr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gttkljxfsh.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtiihvacub.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtwlgxurgm.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gtlzsxzlht.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtnggccont.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gtvsjfijws.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtihpqgdqd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtavcsjgcr.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtgprnkymp.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvtkdshe.html

Ruby: a, b = pair
来源：http://dali.ppjwa.cn/Article/details/gtcbglywst.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gtbzfyaqci.html

[C16] 函数 / 方法重载
来源：http://dali.nanxinkj.top/Article/details/gtcdzpaypz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtvtmlsfce.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtcszhzhuj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gtyzckirmv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xylfe.cn/Article/details/gttjaejtmf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtskzguvaa.html


<!-- 参考信息 -->