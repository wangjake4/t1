代发 wailian999

[B01] 条件判断 if / else
来源：http://dali.pycfn.com/Article/details/gtwnttdfgc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjznzhri.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gogol.net.cn/Article/details/gtxqflfris.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtahcijusm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtnofsssob.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtsxkycxrk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuxming.cn/Article/details/gtndikjirw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ydzc1.top/Article/details/gtlrrfutsk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gtueikchzm.html

[B02] 多分支 else if / elif
来源：http://dali.tianlin.xyz/Article/details/gtqehmbllp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tanke756.top/Article/details/gtpniqtztu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hammf.cn/Article/details/gtyasohjtz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gttzmnqhbq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtahmvmlpg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtwsbcssbu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sysykeji.top/Article/details/gtsqjjkdcy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjffcwhm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtdlvokxds.html

[B03] switch / match / case
来源：http://dali.jyoumei.cn/Article/details/gtmffjktya.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yongpay.top/Article/details/gtmxqzdhno.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtfnkwhhyz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtduvvxtmj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtpejkwdpi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtgjtlknyj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtwmtsjfsr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tian-w.cn/Article/details/gtyfksfikj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtbjetqeai.html

[B04] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtobkunycc.html

Py:   for i in range(10): print(i)
来源：http://dali.yj20258888.top/Article/details/gtxqnrxppm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxuanxn.top/Article/details/gtlidyvuto.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtljbsrtyh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gtinysrxej.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtzllqciny.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.9152youxi.cn/Article/details/gtjtyheuzg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gotoacloud.top/Article/details/gtuxflmplk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gzhubu.top/Article/details/gtepqmviuv.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gttojsnpby.html

Py:   for item in arr: print(item)
来源：http://dali.jiagoushi.top/Article/details/gtbamlyhjk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tanke756.top/Article/details/gtrmitznfi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuoicfiuz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gtrjrohwws.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zycfv.cn/Article/details/gttccjffdv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxuanxn.top/Article/details/gtywfmtupp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nwbrower.top/Article/details/gtfghtbads.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttjzlkugn.html

[B06] 遍历字典 / 对象
来源：http://dali.hywenlv.cn/Article/details/gtohajpfwz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.c1oappe.top/Article/details/gtfpzcmviu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gaohongyu789.top/Article/details/gtfyjgpwqm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gtlgkwwgcq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtwocrnxxa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gtjfoubhfw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gtifpvkotf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jyoumei.cn/Article/details/gtmgfeobyr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdajotjgo.html

[B07] while 循环
来源：http://dali.ybcxt.top/Article/details/gthcvlfmcw.html

Py:   while i < 10: i += 1
来源：http://dali.hnqzz.top/Article/details/gtgycgxklx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zycfv.cn/Article/details/gtusjlcbdi.html

JS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtrpsbfzlm.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtkgxtmumx.html

Java: while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtixkqdild.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhoulong.xyz/Article/details/gtjibbynuv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shuidangran.top/Article/details/gtppqgofcg.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtewrgmtrb.html

[B08] do-while（至少执行一次）
来源：http://dali.havefunace.top/Article/details/gtakulryfa.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.vqdsnc.cn/Article/details/gtltqwzkgd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtgebuethq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtkrtrznje.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtktbzfhhb.html

Java: do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtpezzodei.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gtjupsswhx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shuidangran.top/Article/details/gtlmoqmjyf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtbvwdkmsq.html

[B09] break 与 continue
来源：http://dali.sweek.top/Article/details/gtdfycnjmx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhoulong.xyz/Article/details/gtblxdpbyg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtlwfclssh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtiafzzwoj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtgpqfjogu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtsahnobhf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtpufvdmvw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnqzz.top/Article/details/gtmgciuccf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtjofgkpmu.html

[B10] 遍历同时拿索引
来源：http://dali.fzhhl.top/Article/details/gtwuafpozu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tian-w.cn/Article/details/gtkbsmxdjw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pycfn.com/Article/details/gtwzjcchmm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtzdnymlqb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtjnnaqyjn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hfpthk.cn/Article/details/gtwpmlkkap.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ehwqpu.com/Article/details/gtrhlopvrl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtwirbpoov.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgfzy.top/Article/details/gtoimvhlwy.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuanzx.com/Article/details/gtrstgrjax.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gtmnhalvnf.html

PHP:  range(0, 10, 2);
来源：http://dali.cqqwz.cn/Article/details/gtjdvjcilv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtrniinmtq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gtaqrskjfh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhlqgjjf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gtmovpansi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yongpay.top/Article/details/gtlcafbsyw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gteexvbbaq.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscnpqxbs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gteeatjses.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.316326.xyz/Article/details/gtclyibqhg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtamuanlxq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtezusytvu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gtsenejjvp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gtqsipnlmj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhoulong.xyz/Article/details/gtbkjgkjit.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtxyhtenup.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gtgfghnwrr.html

Py:   isinstance(x, (int, float))
来源：http://dali.meibo888.top/Article/details/gtgrhovtzg.html

PHP:  is_numeric($x)
来源：http://dali.sufxvd.cn/Article/details/gttdzhzcsc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtfqyzuoqw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gtyjcyvltq.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gtkallvwua.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258.top/Article/details/gtzatqaylv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fzhhl.top/Article/details/gttayhvapx.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gttrqwrinc.html

[B14] 判断值是否在集合内
来源：http://dali.andypj.xyz/Article/details/gtxnbmioaw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ybcxt.top/Article/details/gtneajsutx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ppjwa.cn/Article/details/gteintdfqt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtwdheylvh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtshsduxvu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gtsqpknzyr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gtjhhblrlk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtwwufwmhu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtieowedag.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gtrxyrbhvs.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gthzpoenhl.html

PHP:  $a && $b || !$c
来源：http://dali.tanke756.top/Article/details/gtcyiapsdr.html

JS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtfzsleked.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtivzyowuy.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtkhhirbgq.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtcaphfteg.html

Ruby: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtftkfvoxj.html

C#:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtqfwlzvne.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fzhhl.top/Article/details/gtcvwpzfum.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtbzlqqlib.html

PHP:  if (!$data) { return; }
来源：http://dali.yvedp.cn/Article/details/gtbwsmshvq.html

JS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtfgtltwcy.html

TS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtpkcvvphx.html

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtyioebsax.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gttslhgpnk.html

Ruby: return if data.nil?
来源：http://dali.aibaodan.cn/Article/details/gtamfjalbe.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtkajahpjb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttlvrncti.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gtmopzsbod.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmliaxtni.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtovqfeomb.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtpiuoflpf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtuzfztndh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtehrtnbgf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtiepsfbbb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtgbjzrksk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gtysxvxadc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuorrhkyd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtmrqydlvi.html

[C02] 默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtzbfnmofg.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gtpnewezwb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtfdknnoax.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtbambfxeu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtrwonilbn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gtbicjdurd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gttbnhrmze.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtvuvlbwlz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gtvzcfympo.html

[C03] 可变参数
来源：http://dali.hnxiangtu.top/Article/details/gtyxsrmcsa.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigfzy.top/Article/details/gtwsygxbsu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gtgdjwgjso.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gttdjobxtn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gttksijsge.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj202588.top/Article/details/gtglipqdkk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gtfpsewtmf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gtoogrlyvw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtkmvjeusy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gtnabcrnwg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gtfnqrbecn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcukqdpt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwtwitziw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuxming.cn/Article/details/gtwseaeloi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gtrpkczhlj.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gthudywzla.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhyyhjue.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtqebmlqat.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gtpsjzykdp.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gthzurxbid.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtfbghrmzt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtdmuokejt.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtazmpkfke.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.vqdsnc.cn/Article/details/gtbwslfzvu.html

Go:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtoerrgjpc.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtixzaxmwj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmrhamdc.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtixpoyjuz.html

Py:   square = lambda x: x * x
来源：http://dali.dashuyun.cn/Article/details/gttdtwxver.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jianghu66.top/Article/details/gtyzovssdp.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtdwgpqjul.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gtptineeto.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtzyhxsmnj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gtkxlyakzt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtbulxywkb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtvhjchheo.html

[C07] 把函数作为参数传入
来源：http://dali.guannengcc.top/Article/details/gtqlmpcnnl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxatugika.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtlajfgefu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtpackcrzw.html

TS:   arr.map(String)
来源：http://dali.yanxiufei.cn/Article/details/gthojzxjbz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gtulusdrti.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yanxiufei.cn/Article/details/gtwuzkeptn.html

Ruby: arr.map(&:upcase)
来源：http://dali.c1oappe.top/Article/details/gticknphsw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tanke756.top/Article/details/gtmupragvl.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gtzhqxvpwf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jlsjyb.cn/Article/details/gtazdftbtv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gtllglftad.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtkmybmjjg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtymvsvigk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gogol.net.cn/Article/details/gtbqauasuo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gtpwczpfbn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gtbskefxxz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtmzwodtit.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gtedjcosgf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtfknngllz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtevacstgv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtfhvfzynw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtyvfvdzlj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtdtvzqmcf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gtktmfmnyv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiluhqvq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtycqdraff.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gtwxxtlhml.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gtwcwdwcjh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gtctarzfeb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gtobzaoohh.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gtboimzcoo.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gtzwwpdhre.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gtxczeebru.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtxkrtvlfo.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gtstsldtjp.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gtaykalzbn.html

Py:   from module import func
来源：http://dali.hammf.cn/Article/details/gtkudmcsrb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gtbumdlgvu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gteryetnpw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.birdmap.top/Article/details/gtiqhngnoe.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtavizzvyh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtesmravzp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.iojbl.cn/Article/details/gtmovlemsx.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gtkflccxgo.html

[C12] 立即执行函数 IIFE
来源：http://dali.sufxvd.cn/Article/details/gthomihzwi.html

Py:   (lambda: print("run"))()
来源：http://dali.tanke756.top/Article/details/gtaeohrymd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gtbvlktygk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtucyctaaq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gttgjzokqn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gtqxuvretx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gtpmjfxjww.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gtxruwpyfd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gttogffhao.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gtfzbqmcey.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gtxyrrmsoi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtlztdrixr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gtvqckfpwv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtglkqhnhg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gttfcxpvsn.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gtyqkaqyfc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gtwsoejowc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtnreczbmp.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gtxyzkylbm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtagkzelrf.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gtsitpkmge.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtnyjyuqkg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gtgoxpnbrm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtggkmxkgl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cheryme.top/Article/details/gtztrjcfzh.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gtjkuryvld.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gtjjfganci.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gtlqmqhyex.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtixildiep.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gtmylvftdk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtcbsjhrsc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gtggykleey.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtjfmmrnnu.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gteuuqbfkx.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtwukinhpo.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gtcnqsxaoa.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gtkokuywwf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtjyxyuxcp.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gtviyxjadu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gtezzwsvih.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtuibztjyj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gtbklobtkz.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtscydzqbr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.vqdsnc.cn/Article/details/gtkcyggpzj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gtuylgvgja.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtumcditmt.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gtcatoiawo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpziwqyqt.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtgsutpkko.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gtukcdqubs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtypmwwzqg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gtxnrqdfcc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gtuknnfiaz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtctmmwonr.html


<!-- 参考信息 -->