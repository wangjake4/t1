代发 wailian999

[A26] 类型转换总览
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngwmbsbu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjlwmfjo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dianchejie.cn/Article/details/gtfzmcgupb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.svipenyu.cn/Article/details/gtkzjzfxjc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hongshengwenyu.top/Article/details/gtjcudingx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtpdfgnptu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.fengsongda.top/Article/details/gtxqspdhfq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guannengcc.top/Article/details/gtopjmurgw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gtkfsrowso.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtckagsmge.html

B. 流程控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamygsdtc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpgpyndcs.html

[B01] 条件判断 if / else
来源：http://dali.sufxvd.cn/Article/details/gtotabznur.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tianlin.xyz/Article/details/gtzvhfvueu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zycfv.cn/Article/details/gtqncvlwud.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtwujxopra.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtlsnfelio.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtzmzlkeyp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hammf.cn/Article/details/gtsuhnzupv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuanzx.com/Article/details/gtwfpgsepe.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gtylwibosc.html

[B02] 多分支 else if / elif
来源：http://dali.yueranfly.top/Article/details/gtqwvgrzrz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yonumen.top/Article/details/gtjrlilitq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nwbrower.top/Article/details/gtceamjpkg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtxjoqccme.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtioqwrcad.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtjljfxqta.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbqrikuv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xylfe.cn/Article/details/gtnajbltce.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtehkpwnie.html

[B03] switch / match / case
来源：http://dali.jqgufenzy.top/Article/details/gtrfoicudl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.andypj.xyz/Article/details/gtjrfqxarp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtvnodpodx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqwuzftz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gthrtkskth.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtwtwyyczd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.iojbl.cn/Article/details/gtrwjuabhi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shangyingyoupin.top/Article/details/gtlxvtvwcs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tianlin.xyz/Article/details/gtcxjvgqpu.html

[B04] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gttgyaywal.html

Py:   for i in range(10): print(i)
来源：http://dali.cucudq.cn/Article/details/gtdpblffet.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenzaomai.com/Article/details/gtiymhgipn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gtcbezwyha.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtkqdubjvp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhixingplan.top/Article/details/gtjfojbxei.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenjidiqi.icu/Article/details/gtzbxmsujr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jiagoushi.top/Article/details/gtfkbdxpko.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gogol.net.cn/Article/details/gtppmomlyz.html

[B05] 遍历数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtzgtgarxh.html

Py:   for item in arr: print(item)
来源：http://dali.gogol.net.cn/Article/details/gtqwukkfvx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinqigufen.top/Article/details/gtfexipfby.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gtxejvkaii.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gtluoaqdxm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sysykeji.top/Article/details/gteqvqymdj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenlongwang.top/Article/details/gtnzxngqed.html

Ruby: arr.each { |item| puts item }
来源：http://dali.snrcjt.cn/Article/details/gtctoayxts.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwriynqnl.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gtbgsmxmpl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.feifeiyinyue.top/Article/details/gthpfmohhh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnqzz.top/Article/details/gtjhwdxhxk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtahkpbvdr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtsnfygntb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.havefunace.top/Article/details/gtiorxfafw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhixingplan.top/Article/details/gtaalaagdc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.c1oappe.top/Article/details/gtzdtrxore.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfkputwz.html

[B07] while 循环
来源：http://dali.xylfe.cn/Article/details/gtfhddfskx.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigufen.top/Article/details/gtyjfmsnhx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinqigufen.top/Article/details/gtayebawqz.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtqeaibikl.html

TS:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtowvalxkj.html

Java: while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtwzmvuviq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hammf.cn/Article/details/gtpypsfqog.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gtymrosmpt.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtiqswxvbl.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gtgjauoegp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yvedp.cn/Article/details/gtnolsjvnq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtxyuqyerl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtohzmnvkw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtcyukiuvl.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtetnvgqjt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtmmruyvjl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtojkmkkpx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtundihonn.html

[B09] break 与 continue
来源：http://dali.xylfe.cn/Article/details/gtktpjwtqd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daxiang520.top/Article/details/gtvpyqlulr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgfevzenl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gteakakmbu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyigjdfje.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtjzceqiyf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtqwipdnqd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxuanxn.top/Article/details/gtxibihkkb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtvcrmipzz.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gtyerngoye.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkqxnfsh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwtsczjlr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gtjkjatsec.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtwbvxakab.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuxming.cn/Article/details/gtqqterjvb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tanke756.top/Article/details/gtwvccrdlf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gtmpukccby.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.meibo888.top/Article/details/gtpuimcudf.html

[B11] 生成数字序列 / 区间
来源：http://dali.hongshengwenyu.top/Article/details/gtwlrbopwu.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gtrgpvchju.html

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gtliglwfsq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gtzaoczonk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtmxcchtrb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gtuqiusahy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtxwugtfog.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gttreukevv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tanke756.top/Article/details/gtnftyzrjn.html

[B12] 跳出多层循环
来源：http://dali.redwolf501.top/Article/details/gtytswmydk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtcbtdwfsb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gtznljqcnw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtwrlehfit.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtyaoxduus.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtqvdzvugk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gtuswrpmid.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gthoszdtsw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gtygrpthil.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gtdznrgmqk.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gtoersxiaw.html

PHP:  is_numeric($x)
来源：http://dali.shangyingyoupin.top/Article/details/gtezdalzub.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gtxbqsqbsh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtbzzuyqim.html

Java: x instanceof Number
来源：http://dali.chenzaomai.com/Article/details/gtsmskwohh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xylfe.cn/Article/details/gtctrybnrl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cashguo.top/Article/details/gtabqcrjvb.html

C#:   x is int or double or decimal
来源：http://dali.0kj1m.cn/Article/details/gtzawnprsr.html

[B14] 判断值是否在集合内
来源：http://dali.yuanzhike.top/Article/details/gtwaplxuow.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tianlin.xyz/Article/details/gtuhjxvewx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gthqclqlyg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gtzuvjafxg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtpyxsixil.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtjgzqweyb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gtcrwyxkdt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisbvjeby.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtjnyryycg.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gtawjnygyz.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gtltxunics.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gtklqcdsen.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtoomejmoi.html

TS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtcpsqkopl.html

Java: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gthynubvgh.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtnhrdgepb.html

Ruby: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxrrzesv.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtutmgloot.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtkzxzivmh.html

Py:   if not data: return
来源：http://dali.dashuyun.cn/Article/details/gtuaoowxqw.html

PHP:  if (!$data) { return; }
来源：http://dali.fengsongda.top/Article/details/gtodzxhzjb.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtpdaygvgr.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gttllizpsq.html

Java: if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtefsnohbz.html

Go:   if data == nil { return }
来源：http://dali.yvedp.cn/Article/details/gtahtzxlml.html

Ruby: return if data.nil?
来源：http://dali.wangshuangyany.cn/Article/details/gtngcxpcig.html

C#:   if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtkkrjhbrw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgiihkugo.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gtgnbyzbdp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwekskfjv.html

[C01] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gtusdoueew.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtognkrflg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtfznsgngk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtiidpxhwc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtorpprnqd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtkegzmszr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gtghtroccr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gtvxeoszip.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gthmshnyje.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtvaizuphz.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gtvtloyrjh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gtdyslndme.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtbviarvya.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtndczdgok.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shuidangran.top/Article/details/gtgbcyozxd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ppjwa.cn/Article/details/gttfxdmmev.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gtykpnihey.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gtccexeikf.html

[C03] 可变参数
来源：http://dali.hnqzz.top/Article/details/gtgaezkkua.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gtmqjjlino.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jlsjyb.cn/Article/details/gtqyjsmgss.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtbyropzgw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtksysksul.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gtekcvzavt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gtzcwxnovw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gtjurgutoy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gtbsxxjsqx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gtrpbkquzc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangdashe.top/Article/details/gtrqtvrujm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gttchenqiw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtyvmlfsot.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwixwwvqb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtbivyxbmu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtwgtaewfd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gteyiyeeol.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtciwpbcmr.html

[C05] 返回多个值
来源：http://dali.bjfxy.top/Article/details/gtrxwyvxgi.html

Py:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtkpnvdahk.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gtpkhjbvdk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtpgdclivc.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcffikoq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gtlhomhpeg.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtdhsqvybq.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtdbpfnigy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gtehnqkigx.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gtyslmstpe.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gttwzjushw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgumyburn.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtdshitais.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtiibudtwa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtrdhebhst.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbseegde.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gtnklforko.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtnbsvggcp.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gtftndqyad.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gtpyntsfdo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtrwsuucpg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtnwadeodq.html

TS:   arr.map(String)
来源：http://dali.dashuyun.cn/Article/details/gtlykoyhod.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkooasbr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gtrrxpzmeq.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gthqunfxfd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtaouhlril.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtwsmhrkrg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gtmvgxvjzw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gtpfdeznho.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtymfwrvov.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxhslubay.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtrpzknwvz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gtyvpeypuv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gttjrhmabu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobexqcnz.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtsjqrcnhz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtlcmgwijs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttweyyncy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtezphfygb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gteupdpccl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtoxuaexxv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gttzodziaq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtptmrcxty.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gthcxclokb.html

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gtomtusezh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhiwuduotai.top/Article/details/gtrnynzftv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflipwbii.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuanzx.com/Article/details/gtnnynnulg.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtdazmwmdu.html

Java: 方法内为块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsopxpcm.html

Go:   花括号块级作用域
来源：http://dali.cucudq.cn/Article/details/gtcvxccdjg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gtzjslnxlm.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gtejnzmdcy.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gtyrduymmm.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gtxuunlhve.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gtowbvjkqk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gtratvitbl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigufen.top/Article/details/gtsmxvrdiq.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtsrpqpkjw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gtetqrvtts.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gtvsdwtsii.html

C#:   using System.Text;
来源：http://dali.wangdashe.top/Article/details/gtgvgfsguw.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gttuajzevc.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gtpkxvoytn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtlynsgqte.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtqfzzxxyh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtgrimtcpw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gthgxcsiqn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gtrtlpruyd.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gtqdutaqvq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtnhputlxz.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gtvdqccjfs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtwggpzuvt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtztdgnbek.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtiyyukuhp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtwcqkteam.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtffwrwwnn.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gtervmcgbx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gtbvdtbtvd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hfpthk.cn/Article/details/gtccyvbdsp.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gtphyyzsup.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gtndbifbtw.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtebnqcozb.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtoqpzxwxc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwadbudev.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.quarkkingdee.top/Article/details/gtkrwfncpi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.quarkkingdee.top/Article/details/gtzqysbzla.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gtijpflscw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gttqvcnril.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gtutbdsmiw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gtlsvlyvym.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gtdfbsynmp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtklwnesdi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gthwrvaogx.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gthubyuwmz.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbimznym.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gthnygwzem.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gtmmiymgnt.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gtynqhjgbj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gtfgykwwwo.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gtvogjyvai.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gtdavegwyi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtqtdueeru.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gtqyyodpks.html


<!-- 参考信息 -->