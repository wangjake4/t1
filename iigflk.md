代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ppjwa.cn/Article/details/gtzhnrjock.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtynuwcndm.html

[B03] switch / match / case
来源：http://dali.sysykeji.top/Article/details/gtqdgbybru.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.tianlin.xyz/Article/details/gteuyvxvio.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtlpteqyga.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtowyrspqg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtqccamzho.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuiryijbq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtjfqfhycq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zycfv.cn/Article/details/gtikffdkmq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gtxujejcsw.html

[B04] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtqbvrzdrl.html

Py:   for i in range(10): print(i)
来源：http://dali.0kj1m.cn/Article/details/gtfziajaum.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.haohaochexian.top/Article/details/gtzkaljgrc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tianlin.xyz/Article/details/gtgxowajmk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtguuhfiaz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.andypj.xyz/Article/details/gtcvxpwozc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ydzc1.top/Article/details/gteaqeyrre.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shuidangran.top/Article/details/gtmkhdebbm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtinbuotqa.html

[B05] 遍历数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtrsqnbjbd.html

Py:   for item in arr: print(item)
来源：http://dali.nwbrower.top/Article/details/gtqxnrkwxj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tian-w.cn/Article/details/gtnxenhjtu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gtftwexrcy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gtviamogdv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtexomfzsv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gtouktdvvw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jlsjyb.cn/Article/details/gttwcyrucn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtcasvdhrf.html

[B06] 遍历字典 / 对象
来源：http://dali.daria6918.cn/Article/details/gtmadzoafj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ehwqpu.com/Article/details/gtvwquefop.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cdnleiting.top/Article/details/gtdnhsxdpf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtkbcxrspm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtcksxrdlg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gogol.net.cn/Article/details/gtxnawooqi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.quarkkingdee.top/Article/details/gtqqnipveq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkldgwkm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.mhx1999.top/Article/details/gtfovyveex.html

[B07] while 循环
来源：http://dali.kuanghao11.cn/Article/details/gteqontenl.html

Py:   while i < 10: i += 1
来源：http://dali.pycfn.com/Article/details/gtnjrkdxnx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.snrcjt.cn/Article/details/gthkhlaymq.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtwiiunwqg.html

TS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtbvqlxgkj.html

Java: while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gthpxdkfrx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fengsongda.top/Article/details/gtdthkwsdp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.wangshuangyany.cn/Article/details/gtkxsjbllb.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtotgjkugt.html

[B08] do-while（至少执行一次）
来源：http://dali.yangfankeji.com/Article/details/gtyqkpqyvg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.vqdsnc.cn/Article/details/gtodkqmool.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtthufwrcv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdyhyxqn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtafocppgy.html

Java: do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtnyfdperu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nwbrower.top/Article/details/gtauhqwfcq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yanxiufei.cn/Article/details/gtxmgmcavv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtgtezhgog.html

[B09] break 与 continue
来源：http://dali.tanke756.top/Article/details/gtfhmccfkd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gtpabbnfdo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtvsbilivk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtcfoiaron.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtyswgbapv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gttanhojmn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gtnhgezpjz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuanzhike.top/Article/details/gtuqpvctpj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtqouyhpgh.html

[B10] 遍历同时拿索引
来源：http://dali.sweek.top/Article/details/gtzmxwduij.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhongyouzk.top/Article/details/gtzmgdwehe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cucudq.cn/Article/details/gtzplyuwfp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gtsgdoougv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gtbawzscvu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gtnuhhqjqn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gtmgcnrfjn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigufen.top/Article/details/gtzgdtczkz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgufenzy.top/Article/details/gtsxbltvsy.html

[B11] 生成数字序列 / 区间
来源：http://dali.pengpengdd.cyou/Article/details/gtbegcwaip.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpksozee.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gteraemdqa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtjlgoqzua.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtsmclijje.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmbjlarr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gtfajsrnmc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtiscwhwlp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hongshengwenyu.top/Article/details/gttwyxmcvl.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gtgjmmykze.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtvtbfnktu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ydzc1.top/Article/details/gtvvjnrjjt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtzfsfoscj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtrnuglcgc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtxpnwusaw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daria6918.cn/Article/details/gtqlpjszcg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpwtgkhw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ybcxt.top/Article/details/gtuxlioktf.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gtcumyptks.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxuanxn.top/Article/details/gtfefpeyoi.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gtovfyeybq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gtplvzfliu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtdgfqzfhn.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtosomlrtu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.havefunace.top/Article/details/gtkahezofz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gtrmlbpjlg.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gteplmbpue.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gtvsaktbyb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtedypnoxz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.havefunace.top/Article/details/gtzumvsauu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cheryme.top/Article/details/gtkyvbnwrl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gthlkkgszi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtfhhbplwp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gtpukfksng.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfntikdle.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtzvbizanm.html

[B15] 布尔运算与取反
来源：http://dali.havefunace.top/Article/details/gtqosufevz.html

Py:   a and b or not c
来源：http://dali.9152youxi.cn/Article/details/gtbbjyrojj.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gtgegukfar.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtjwfytzzg.html

TS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtobijhkeh.html

Java: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtllpzwrrm.html

Go:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtehhififb.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtcvkwdwxn.html

C#:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtfbvtbrtw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gttqtweecp.html

Py:   if not data: return
来源：http://dali.yj202588.top/Article/details/gtzaujisjq.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gttyjzpttp.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtryfrrgyc.html

TS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmccadoev.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtxmxoyxiv.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtsebacoph.html

Ruby: return if data.nil?
来源：http://dali.nanxinkj.top/Article/details/gtnzyaytfv.html

C#:   if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gtnuuxpnqy.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtkaceqnnu.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gtueowkktb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlghcbvyv.html

[C01] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtcognfsjf.html

Py:   def add(a, b): return a + b
来源：http://dali.daxiang520.top/Article/details/gtumjsqkew.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gthyubipty.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtjqlphmol.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtroigtltu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtzdpufaha.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gtviamhyhs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gtbdzmxqsu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtbvgxajxf.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gtlgitkzlz.html

Py:   def greet(name="World"): return name
来源：http://dali.ybcxt.top/Article/details/gtcgwojljx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gtbxnqssrj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtzforypqd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtpyxxymis.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gtcwcienrg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gtlqaonimv.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gtsdfudnhv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aizwys.cn/Article/details/gtkebodjvw.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gtpqtxrcch.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gthiygbizj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgblgagsi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtfsxwvyba.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepgqlhkn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gtwhovfbou.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gtlihggghm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.haohaochexian.top/Article/details/gtylsdgxey.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gotoacloud.top/Article/details/gtnstmkjcn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuanzhike.top/Article/details/gtkztjhaih.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gthquemdzq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gtvvzpnvay.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtpdrybagq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gtaltlkakg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gtmfguzymd.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gtdvmvnaiz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtqkdjrjbi.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gttfovhpfv.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gteadvbqsk.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtzzgqfiib.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gtzfcexuzu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtztgzkqqr.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gtgritnbmo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gtujvwoedi.html

Go:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtmgnvrnyz.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtnalhbymw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gtmgejsnzx.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gtagomingx.html

Py:   square = lambda x: x * x
来源：http://dali.zdqjudy.top/Article/details/gtkjflxeof.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.vqdsnc.cn/Article/details/gtpyaxneaa.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gttcbjjqum.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtjefxjnjs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gtzgeteszh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hysaishi.cn/Article/details/gtptfyvjdq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtuizsbbrm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtwsindtra.html

[C07] 把函数作为参数传入
来源：http://dali.chenzaomai.com/Article/details/gtnztuidnv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yanxiufei.cn/Article/details/gtpvmprhzu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gtdoxhwhvm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gtnrjkjysx.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtqhdiikqv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yonumen.top/Article/details/gtsqbgsidr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.smart0.xyz/Article/details/gtefqovroa.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gtnmpunldm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gtluvizamd.html

[C08] 闭包
来源：http://dali.hnxiangtu.top/Article/details/gtadbfgfqz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gtkuncocev.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gtvlfpfveo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtykjdvzyy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtxvehgtet.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gtteuyfyrh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.birdmap.top/Article/details/gtlgalvgym.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gtezntknti.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtwnugspqm.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gtqzysbowh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtpamzkcru.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gtxntzpuvq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtcxqwzzdu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtlrznbrvv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtqcoxaxyf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gtpholamwx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtkwbrpcpx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258888.top/Article/details/gtgwwdafeo.html

[C10] 变量作用域
来源：http://dali.zhoulong.xyz/Article/details/gtrnpikxjs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtslhfdtxl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gtqahuejdy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gtunvzdejs.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtviakurcy.html

Java: 方法内为块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtnsbsidvk.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtpgtfkzvt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gtfvgrjupl.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtbpivkfnf.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqhsfsip.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gtyjtosjwd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtbplimery.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gtvyulwdsz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daria6918.cn/Article/details/gtgmxkdqer.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gtplwmbduf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtmlcsiezg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gtdsdaftuk.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gtpwkanhem.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gtpgwuqvor.html

Py:   (lambda: print("run"))()
来源：http://dali.cheryme.top/Article/details/gtthrktibp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtsnrgnwnf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtwjermrbf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtqzsjgkjo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtbssomjip.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gtwwkguakh.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gtyqgkaqce.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtjeumfayq.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gttyonrdhe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtkljznvgz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtjlqtczai.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtrzvamqwz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtdengovdw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gthiydzhek.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtxopcqgro.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hammf.cn/Article/details/gtccvkaauw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gtuzhvfdup.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtmusqmfry.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gogol.net.cn/Article/details/gtkzroqnsv.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtsgojiwog.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtcjnimlag.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtquyvnlcy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gtawbrwqid.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gtowggqbrb.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gtcflkmuvs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gtqspyprgm.html

[C15] 解构 / 展开参数
来源：http://dali.sufxvd.cn/Article/details/gtfelxzedt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwbfunkn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gtkruphcpl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxgctytoq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtegaetssr.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gtdysvxywc.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtwgrcnqza.html

Ruby: a, b = pair
来源：http://dali.ivvv.top/Article/details/gtphozataa.html

C#:   var (a, b) = pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcnhtpti.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtkalzhrld.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xinyue.icu/Article/details/gtnmktdshk.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gtobawaxmk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gtxadtafsg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigfzy.top/Article/details/gtpookugtj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtourmppaf.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gtobrzlliz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gttdijszrg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprtaclcy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbrflbgxz.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gtnoetzdqm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtiumpkupx.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswmtwcbx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gtnrtndmqn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtndmrwwot.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtgvkmtraj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gtugumlkdm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuanzhike.top/Article/details/gtggkmilra.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gtlxbdgpys.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtvlljuboo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gtmditbdpw.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtytycpccn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gtuvjwnifv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtifhhfhup.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtwaphoznw.html

TS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtdqoxadru.html

Java: list.add(4);
来源：http://dali.ydzc1.top/Article/details/gteptkxrqz.html

Go:   arr = append(arr, 4)
来源：http://dali.yuanzhike.top/Article/details/gtguwpjpxj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtekrufyml.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtgypecrnw.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gttfjjnlvb.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtsfbcpigq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gtzpedxeoi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtvjidhcsj.html


<!-- 参考信息 -->