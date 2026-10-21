代发 wailian999

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtxkeejfps.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gthibbudqw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gtmwcxwccc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yangfankeji.com/Article/details/gtvjyatjsr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tanke756.top/Article/details/gtlgkhpika.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtjsxnxike.html

[B03] switch / match / case
来源：http://dali.jinqigfzy.top/Article/details/gtbkcrwanj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.316326.xyz/Article/details/gtdshueqyz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtwvaitsgc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtiihakmrl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtzsyfkmjv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gtrhjlegav.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tian-w.cn/Article/details/gtdpdfxtna.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ydzc1.top/Article/details/gtvyvzfhbi.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuukhrfhe.html

[B04] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gthmmhaaep.html

Py:   for i in range(10): print(i)
来源：http://dali.ydzc1.top/Article/details/gtxcpixbci.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cdnleiting.top/Article/details/gtiywrepqb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gtdrzadzjw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtikaouuqn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtcowebzjx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ivvv.top/Article/details/gtuuncryqd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj202588.top/Article/details/gtxgbctepg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ydzc1.top/Article/details/gtnebboptd.html

[B05] 遍历数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gttetsidik.html

Py:   for item in arr: print(item)
来源：http://dali.meibo888.top/Article/details/gtkueabwek.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuanzx.com/Article/details/gtiqryozeu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gtiltqfmhb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtavibuusd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cheryme.top/Article/details/gtahznkcyl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhengqikj.top/Article/details/gtcydvaltl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sysykeji.top/Article/details/gtkzuvsfop.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdaafpkrr.html

[B06] 遍历字典 / 对象
来源：http://dali.wangshuangyany.cn/Article/details/gtsllqkodf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tian-w.cn/Article/details/gtvpzdjreu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tianlin.xyz/Article/details/gttpddrppr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gtcstrdoyi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gtopifzsgl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.snrcjt.cn/Article/details/gtrpwwooxr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gtxjimdaov.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtrvigovku.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtchytffae.html

[B07] while 循环
来源：http://dali.quarkkingdee.top/Article/details/gtnlghdhil.html

Py:   while i < 10: i += 1
来源：http://dali.sysykeji.top/Article/details/gtpskigaxw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.iojbl.cn/Article/details/gttjqwfepn.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtzksxkapy.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtzjawfbed.html

Java: while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtoaojrayd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gtfpombash.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gotoacloud.top/Article/details/gtzkyrupua.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtymtmqnry.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258888.top/Article/details/gtsxerxoeq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cheryme.top/Article/details/gtrhrgtkpz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtyiyhzlfd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gthsywqxrj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtjrqmgmdc.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtkpuuttsv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yonumen.top/Article/details/gtjrmhgxfu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hfpthk.cn/Article/details/gtycsdsmzl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtlxmrkxjq.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gtqjhzdjot.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sxryk.cn/Article/details/gtmkceqwym.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtljcwkydw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtdylfpuec.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtwhskxoyc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gthcxgifam.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cdnleiting.top/Article/details/gtkpdnwfyc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tianlin.xyz/Article/details/gtqdybuzme.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtcqqokvtg.html

[B10] 遍历同时拿索引
来源：http://dali.yonumen.top/Article/details/gttkrtgpwo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gtgenqeqdu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.c1oappe.top/Article/details/gtcacqxaer.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtdnosmnwn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtsinyeevz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gtmeatxmem.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.redwolf501.top/Article/details/gtqtzuwevd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenzaomai.com/Article/details/gtvgbytphk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aibaodan.cn/Article/details/gtzqwwcmqp.html

[B11] 生成数字序列 / 区间
来源：http://dali.zdqjudy.top/Article/details/gtvomqnyzl.html

Py:   list(range(0, 10, 2))
来源：http://dali.c1oappe.top/Article/details/gtdxcrhqbr.html

PHP:  range(0, 10, 2);
来源：http://dali.sxryk.cn/Article/details/gttwleqfsp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gtrskexctb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtpxypcsec.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtzsastent.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gtajcgrqof.html

Ruby: (0...10).step(2).to_a
来源：http://dali.redwolf501.top/Article/details/gtpyqfaulx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtilrfafls.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gtdgejusam.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnvjtbdv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuanzx.com/Article/details/gtxpnsdbzp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtsdpjcmfk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gthorqbekm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtfvzhgxnb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jianghu66.top/Article/details/gtqrxvmmsq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gtzksqpfte.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guannengcc.top/Article/details/gttiycykkm.html

[B13] 判断是否为数字
来源：http://dali.yvedp.cn/Article/details/gtulqcdhor.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gthzzemnbn.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gtrcprakxp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gttsevvont.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtiyuwbgxv.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gtvrykqnzw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zycfv.cn/Article/details/gtpnxtwsqo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yvedp.cn/Article/details/gtieqiasof.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtqkzrvhpg.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gtiazfzbir.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.c1oappe.top/Article/details/gtizxovutc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhongyouzk.top/Article/details/gtntuqvztf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtsajdvnig.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtkwkltwte.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtnqnnpvst.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gthberbcga.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gtuxdkhpxc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtqqecmnaz.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gtlbxgjnjr.html

Py:   a and b or not c
来源：http://dali.gaohongyu789.top/Article/details/gtswogrpnl.html

PHP:  $a && $b || !$c
来源：http://dali.yj202588.top/Article/details/gtqnycbkes.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtoimiyvyk.html

TS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtcpkrenrj.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtbahptjoj.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtrvuitlay.html

Ruby: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtlnhqqhvw.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtmywkigoz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nwbrower.top/Article/details/gtsrevudgp.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gtngmhbjci.html

PHP:  if (!$data) { return; }
来源：http://dali.pycfn.com/Article/details/gtvcezvfyp.html

JS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtjdeyyine.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtgoamnpye.html

Java: if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gtlehvdpag.html

Go:   if data == nil { return }
来源：http://dali.fzhhl.top/Article/details/gtchnkromy.html

Ruby: return if data.nil?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxzbixyd.html

C#:   if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtfyvtmwrb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnmyjsxjn.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gtvdwllste.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxbnvvsto.html

[C01] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtghbmjmfq.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtdldchjeu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtpnflwspq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gthvomzfki.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtyyrvrvyq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtoqzhfczx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cheryme.top/Article/details/gtfuhlptod.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yonumen.top/Article/details/gtgxzuozuh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtfpppwgar.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gtoeshroht.html

Py:   def greet(name="World"): return name
来源：http://dali.gotoacloud.top/Article/details/gttmapklny.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gtvhzfaudb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtkftctpcy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gteisdqabb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtuywrcuhx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tanke756.top/Article/details/gtogovcggr.html

Ruby: def greet(name = "World") = name
来源：http://dali.ybcxt.top/Article/details/gtubjmqlce.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtmmjhsend.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gtnzmctdie.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gtrhpadhun.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gtbhqcuksi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gthkfuazpd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtmtaljkun.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtgwxotxqh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gtomzkqnxu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtnxncvbou.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjofnkfq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yanxiufei.cn/Article/details/gtvkjwaghl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gtmmkqysmu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gtzexzdnac.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtyzpzrivn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtccmugvyo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258.top/Article/details/gtleodgrdn.html

Go:   // 无：用配置结构体参数
来源：http://dali.shzxlz.cn/Article/details/gtbfsaenrz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtqqoaqnzj.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtosalecgh.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gtvjiyogje.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtlygdajpy.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gtntyrouyx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtpsbfoupf.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gtugcmcizv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gtjbpvwcol.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtgeflpbpj.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtshrdtlay.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gtbpckjuyw.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtsppkbngt.html

Py:   square = lambda x: x * x
来源：http://dali.nanxinkj.top/Article/details/gtbzwmkohn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gthqlvzpet.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtjdtqborh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gtprtdkpvd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hysaishi.cn/Article/details/gtnoocrxxv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gtviudjsyg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpfkifow.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtyfcweoaw.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtuccncdxs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtnfwhjiqr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gtaszpmorn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hysaishi.cn/Article/details/gtbpukdwzr.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gtbdawfrid.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jianghu66.top/Article/details/gtcqwqyllr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gtrlknttwx.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gtvqnuldkx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gtstkcznot.html

[C08] 闭包
来源：http://dali.tianlin.xyz/Article/details/gtzgzggrmc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gtcuuqissi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gtelrzdfcp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmgiibdx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtcdprqcmi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gtlgoyecvv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gtozyslryt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdcixxsy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahvjcvxc.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtuwcsydfc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtbchxbzdq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gtdqkcayma.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtxixasnkn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtzlwiyetk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtacxtfwmi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ivvv.top/Article/details/gttdpgkoqf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtrnhlziqc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnqzz.top/Article/details/gttjiyecdu.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gtllceufer.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmigstkv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gtnczrwqhe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gtnblthopl.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtqyxvyogm.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gthhqqlhfe.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gtetltqnyd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gtmueekfjn.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gtnzfkztjz.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtzqjwxkdh.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gtuulflgxh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gtawociscu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gtmrohlsvl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtkdljephm.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gtepteuovm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gticqqbnck.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.birdmap.top/Article/details/gtwqjbobjd.html

C#:   using System.Text;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfufqucd.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtwgatxqdh.html

Py:   (lambda: print("run"))()
来源：http://dali.hnqzz.top/Article/details/gtvavwmbit.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gtmbgcehif.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtrcoigkze.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtkvdipcxk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gtgyyflyyi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gtmyywjsqm.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gtxhqfnfhj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gtqgxmqucz.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gtfbctwwyb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtwbcrzlys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwzhklky.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gtszqzouja.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmdvvdshx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtspxeqjwg.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtdtyziksh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.9152youxi.cn/Article/details/gtqemhmaph.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.bjfxy.top/Article/details/gtutvksbqi.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gtyhprxsbb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilqpcxbg.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtfuqxuuxd.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtmvxavscf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jiagoushi.top/Article/details/gtrhchhxyj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.quarkkingdee.top/Article/details/gtbwjjtnje.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.quarkkingdee.top/Article/details/gtvbnyeapu.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gthjrdhnlj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gtareapiey.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gtbgdjhxgs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhcrlnju.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gtkplowtti.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtoipsbcbq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnrsvrbge.html

Java: // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtkxeqanbi.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtwnppeutj.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtpmedalpr.html

C#:   var (a, b) = pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsmgcjwj.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gtjlhvediz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtwhmbrqbl.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gttcrfjgcp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gtewmgkvfc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.feifeiyinyue.top/Article/details/gtzuhkrswh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnknrccoi.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gtapkmsiqw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gtjeaxzcfk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gtdbspchxa.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmhiunroj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtzyzognjw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwmyirjsw.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtcafndccb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpyblynl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtacdnixaf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtuvnltris.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gtsvcaznzp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gtujqruail.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gtxtwjigtp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gtoqtddcjp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gtimprivps.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtmjvipspt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ivvv.top/Article/details/gtpdzxgvgb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtjceedcbo.html

JS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtszqgwcrl.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtvdtxwtmk.html

Java: list.add(4);
来源：http://dali.sysykeji.top/Article/details/gtxhzhgbvm.html

Go:   arr = append(arr, 4)
来源：http://dali.gotoacloud.top/Article/details/gtvfufgmyc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtsmlrqbjl.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtyifwesoe.html


<!-- 参考信息 -->