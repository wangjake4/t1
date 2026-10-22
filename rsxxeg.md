代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jiagoushi.top/Article/details/gtmsxtmkej.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtdivifzfp.html

[B03] switch / match / case
来源：http://dali.andypj.xyz/Article/details/gtyvyuptlk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxinkj.top/Article/details/gtwxaddjos.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gthyfmxfdp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtkjkjnpjx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtrrsgsgrz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtldoxrwfx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xinyue.icu/Article/details/gtgrwrjtmm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuxming.cn/Article/details/gtqhqnghwj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.guannengcc.top/Article/details/gtwlohvqah.html

[B04] for 计数循环
来源：http://dali.sweek.top/Article/details/gtgbdnjqvp.html

Py:   for i in range(10): print(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvytsozz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinqigufen.top/Article/details/gtgwixopen.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gtibfsgieq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.birdmap.top/Article/details/gtviwxmnjf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtzhhdqbtv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.smart0.xyz/Article/details/gtjhwgkuby.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sxryk.cn/Article/details/gtuilnqtlp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzkiokubp.html

[B05] 遍历数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtpqnsfmpc.html

Py:   for item in arr: print(item)
来源：http://dali.daxiang520.top/Article/details/gtqkkymdki.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xylfe.cn/Article/details/gtyvhgwilb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gtewboxrbq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtyiqqgdtj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ybcxt.top/Article/details/gtrhzmolke.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hfpthk.cn/Article/details/gtdjmysqth.html

Ruby: arr.each { |item| puts item }
来源：http://dali.meibo888.top/Article/details/gtatihrerb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gtdpjwceuw.html

[B06] 遍历字典 / 对象
来源：http://dali.shangyingyoupin.top/Article/details/gtadnixjxk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fzhhl.top/Article/details/gtesftcjdf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkrrjqxt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gttoomzcrq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmbpxaox.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenlongwang.top/Article/details/gtkehxnfwf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.c1oappe.top/Article/details/gtvhcebqzg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxuanxn.top/Article/details/gtiocbhtfm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gotoacloud.top/Article/details/gtdhzqhlyw.html

[B07] while 循环
来源：http://dali.sysykeji.top/Article/details/gtvwmgvwwg.html

Py:   while i < 10: i += 1
来源：http://dali.sxryk.cn/Article/details/gthkjbwfcc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xylfe.cn/Article/details/gtvonmdnpw.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtansrtbvx.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtymfxhuzf.html

Java: while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtmfputfta.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gttihhsrxu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gtfmbxsydh.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxziiivkr.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gtwjguwqdq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hammf.cn/Article/details/gtekjgcoew.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtaiuyrabd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtfvzddgfw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtizasxxui.html

Java: do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtpmeucqvs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cucudq.cn/Article/details/gtixemmznp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.316326.xyz/Article/details/gtrazxrtig.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtkcukgidi.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gtqrdmjwhf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gtgsktqfsi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtxsvmwlbc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtcgblazbt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtlszhkvkp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtqlqlddnp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gtmxgssnkd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gtdfcpkvvc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gthhuccgdc.html

[B10] 遍历同时拿索引
来源：http://dali.wangdashe.top/Article/details/gtsyqngghx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gtmmwvqaix.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zdqjudy.top/Article/details/gtvbggmkfn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gtjzomwfzr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gtzwlfjzgd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gthevhbnft.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwreqmmog.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gtgzwkjedl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgfzy.top/Article/details/gtsvqfrqij.html

[B11] 生成数字序列 / 区间
来源：http://dali.yonumen.top/Article/details/gtumspoidy.html

Py:   list(range(0, 10, 2))
来源：http://dali.birdmap.top/Article/details/gtrukjkfbp.html

PHP:  range(0, 10, 2);
来源：http://dali.xziqi.cn/Article/details/gtdjhlqeoi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gthnhrkmol.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtqeqnxzof.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.guannengcc.top/Article/details/gtntfcdhfz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.c1oappe.top/Article/details/gtwkrzpijf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shuidangran.top/Article/details/gtjibydjak.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtaayamhhv.html

[B12] 跳出多层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtnmblalqm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gtlpsvhevr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqsckauu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtsuwfozdg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtdqnmovmk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtndheahts.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dashuyun.cn/Article/details/gtaolsuygt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenjidiqi.icu/Article/details/gtggsxwagg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gtshkgwotj.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gtwwgsxock.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gtmiozrnoc.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gtvieerjih.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtwhofifha.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gttnuiysqm.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gtvjdemqrg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jlsjyb.cn/Article/details/gtnqqjoqgt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aibaodan.cn/Article/details/gtsusiqvyf.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gtqmslusox.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gtcsvnlyvj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pengpengdd.cyou/Article/details/gtfcfreuno.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.vqdsnc.cn/Article/details/gtrrjsadnw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gthvpwcahh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtoykbkxly.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.c1oappe.top/Article/details/gtofdblesq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtasxbidet.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.havefunace.top/Article/details/gtibjqphuc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gthjoqeosw.html

[B15] 布尔运算与取反
来源：http://dali.smart0.xyz/Article/details/gtgrxcavsv.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gtyzqigrvx.html

PHP:  $a && $b || !$c
来源：http://dali.iojbl.cn/Article/details/gtrpbjovtg.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjafzpehs.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtamfskcrv.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtqqvefyxw.html

Go:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtjyqryfvt.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtvwargioe.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtnedwfaar.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shuidangran.top/Article/details/gtaszxnpds.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gtoprkzicn.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gttvoildgp.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtncvbhxcq.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcelcfnf.html

Java: if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtzutsbcoi.html

Go:   if data == nil { return }
来源：http://dali.ivvv.top/Article/details/gtjbwrxitq.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gtkqweeiqa.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtbefahdge.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzbevcoxb.html

C. 函数与作用域
来源：http://dali.hammf.cn/Article/details/gtnwppjycf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttqldwygb.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxkrypam.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gtlqptevat.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtvezihqod.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtvydsyafq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtuiejwajp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtlmrjtmnp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gtywdgfndf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtkwsgrovm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtkqeqlxpu.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtzhlynrdi.html

Py:   def greet(name="World"): return name
来源：http://dali.wangshuangyany.cn/Article/details/gtdqtnxxbj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcujoxonb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgitciok.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtcjgmjouf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pengpengdd.cyou/Article/details/gtvadfeijg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtuacfnwix.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gtbibpqfal.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtfkyrwjon.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gtlfxbxzfe.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gtcwrscbxq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gtojeyttie.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtikxcjdgv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtzpoevgcv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtpephyypz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gthjcsresk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gtjxglnflp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gtenbnaszx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjnhmznc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gtkeyuectv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aizwys.cn/Article/details/gtdlazcdvl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtilitczcy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jiagoushi.top/Article/details/gtuylylyxs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gtwnccifwr.html

Go:   // 无：用配置结构体参数
来源：http://dali.ppjwa.cn/Article/details/gtjkwgcpdp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gttolqeqqc.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtceotnwpd.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gtkffqirqb.html

Py:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtpxvibjgv.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gtxxxhwrku.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtfmxqeniu.html

TS:   return { a, b };
来源：http://dali.redwolf501.top/Article/details/gthmjudlrg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gtaxvegcwd.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtgwuizsgv.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gtlzptcxht.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtaitattfk.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gttbpntscn.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gttcdonjjm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gtimynwtbg.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtlhiffovk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pycfn.com/Article/details/gtebkgsdos.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtzysownxt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.svipenyu.cn/Article/details/gtairdxufr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gtpyjuuwhm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtevkqwzav.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gtkvshmyjd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gtawetapyr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gtemeiqqvw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yangfankeji.com/Article/details/gtizaxlnrt.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gtkaqjxnzo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvehttqac.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cdnleiting.top/Article/details/gtcqtlkjwk.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gtsbnajnbo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtrxfkwsqq.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gtfeivcvlq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gtlfekzhrz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gtzwmbgqmf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhkdxwth.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtzqrgpohc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shzxlz.cn/Article/details/gtddurmbwf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gteayytctt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cqqwz.cn/Article/details/gtdvbrpbkv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtlvnnfhnf.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gtqlbuzeze.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtdelvtkzi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtsldoclsy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtretnakff.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gthszjsine.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtxnvzmbom.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gttnckvlob.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtlfzexpfx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gtmtqvjzep.html

[C10] 变量作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwamjcmdf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gthutmitiq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gthdetvvtu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gtqsstwouj.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtdjcageqy.html

Java: 方法内为块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtixdiktah.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gteyhhemgv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gttvwzjsly.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtzkhiftxx.html

[C11] 模块导入与导出
来源：http://dali.hysaishi.cn/Article/details/gtbztubqrp.html

Py:   from module import func
来源：http://dali.jinqigufen.top/Article/details/gtkzjspngb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtmzuyqbmi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gttardhazs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gtixjhoclb.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gtotrddrpw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gtgifaineo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutkmeyev.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gtggljqafw.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gthqaguomz.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gtzhdchixh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gtudokwggs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtazzteshb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtnxfcicpx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gtgufmtktn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtebicmgnf.html

Ruby: -> { puts "run" }.call
来源：http://dali.gotoacloud.top/Article/details/gtrodqxdgg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gtrfmvbkkg.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gtltocbrqy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtteuuvctb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtuoeayjhi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangshuangyany.cn/Article/details/gtvfzjfyhp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbiohimup.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtmlhjwqaf.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtfwfhujtg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfdwieer.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gtnskbgtik.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gtgfkapmro.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigufen.top/Article/details/gtitpzmlwc.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtscgqlses.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gtysvuszgv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtvxsapavy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtlejcwmac.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.quarkkingdee.top/Article/details/gtvxqzbxnx.html

Ruby: # 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtnifoswbu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvjfnvhf.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gtqovdswgf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gtzvmdulvh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gthiurhbxb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtjtkgsfos.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cucudq.cn/Article/details/gtirchdukp.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtiptccvbv.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gttskoxxxp.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtowcmcwbp.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gtfqzqttuj.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gtnklsyohw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtsiewiihp.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gteqkdhuil.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gtvxyxovqw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtzepcljyy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yonumen.top/Article/details/gtupidouys.html

Go:   // 无重载：用不同函数名
来源：http://dali.kuanghao11.cn/Article/details/gtnvbtipcf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gtshcebqcc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gtxdgggoyh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbukstdcy.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gtyfuubozc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtcowdkbwk.html

[D01] 创建数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gtxgmknvfh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gtpmfwwkcz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gtspteelai.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtblsfaypk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gtbrbirldc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gtcfuabidd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenlongwang.top/Article/details/gttxlfwuxg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdnjcdos.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gtycvxotrr.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gtcmvadoag.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gttxzodnuu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtjqvaghav.html

JS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtxzufhsef.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtibnedmvd.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gtbepmltxp.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gtixsusqnj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xziqi.cn/Article/details/gtswszhirf.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gtbvkwgfea.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gtavhuwsih.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtinoxbdlf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gtucxxtgpt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtuttzdpru.html


<!-- 参考信息 -->