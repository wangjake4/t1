代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.snrcjt.cn/Article/details/gtpclxphne.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtspuelfam.html

[B03] switch / match / case
来源：http://dali.svipenyu.cn/Article/details/gtvoizadqk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gaohongyu789.top/Article/details/gtryoagkoj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtnoxddppx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtvzkxeyjo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtisgpyluy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvswspfjp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.redwolf501.top/Article/details/gtqinleiai.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cucudq.cn/Article/details/gtmmtyncic.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gtwfjbmgwj.html

[B04] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtkjaxwvaa.html

Py:   for i in range(10): print(i)
来源：http://dali.ivvv.top/Article/details/gtapijlpco.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gteciaztza.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jiagoushi.top/Article/details/gtalyodlbr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gtpptrvhhs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xinyue.icu/Article/details/gtfvpjpxxz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gtxcpofytd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gtiahojeut.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gthlzwsrox.html

[B05] 遍历数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gtfcndxcrh.html

Py:   for item in arr: print(item)
来源：http://dali.jianghu66.top/Article/details/gtyjjfclum.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yvedp.cn/Article/details/gtqtvpnotm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sweek.top/Article/details/gtlwxumdqx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtwlwagnpf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.bjfxy.top/Article/details/gtdchwphnx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258.top/Article/details/gtyawobthp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ehwqpu.com/Article/details/gtkuhosuuv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cqqwz.cn/Article/details/gtqymuiuor.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gtvlcdzhoc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gthaxsdnll.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenzaomai.com/Article/details/gtbmkswtek.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtmzvadsfb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtpfnkhnri.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.kuanghao11.cn/Article/details/gtmdpxnnpl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aizwys.cn/Article/details/gtaftusbbl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yanxiufei.cn/Article/details/gtbozqniur.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaicgxdml.html

[B07] while 循环
来源：http://dali.daxiang520.top/Article/details/gtkozuzpuo.html

Py:   while i < 10: i += 1
来源：http://dali.cucudq.cn/Article/details/gtefksnkrj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.bjfxy.top/Article/details/gtcudzhvgp.html

JS:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtzczkfggc.html

TS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtrkivijhn.html

Java: while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gttglmsmat.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuetiantiany.cn/Article/details/gtohakvizn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ydzc1.top/Article/details/gttiyvltyo.html

C#:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtedsjeeoq.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gtpmindoku.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yongpay.top/Article/details/gtmsbjogml.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gtmscouuql.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtflbotblp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtytnbofmx.html

Java: do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtrlvyvbqp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.aibaodan.cn/Article/details/gtwtdcjbel.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gtdyqhjxyg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtfunfgwum.html

[B09] break 与 continue
来源：http://dali.xylfe.cn/Article/details/gtmmrfymdy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gtxpizgtqj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtyphqtmhj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtjqissdja.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtgggfwtvo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtvbdhiefn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtgjqyqo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gthykwkhqk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtxhyqlhhz.html

[B10] 遍历同时拿索引
来源：http://dali.yuxming.cn/Article/details/gtbmavyeya.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gtkvpzgrsq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gtpjtoctbx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gtzlbdasbb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gttxdfatql.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guowangkeji.top/Article/details/gtvrlbvbdf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gtspuqxaek.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gtyhsscrfn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guowangkeji.top/Article/details/gtumfebxje.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258888.top/Article/details/gtthsmxxzb.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtdkottkqj.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gtjncbfvfw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gtsqibktas.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gtgfeuwfoh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yvedp.cn/Article/details/gtxjicwumn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gttisivrfz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gtbkwloumi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtakjogqhv.html

[B12] 跳出多层循环
来源：http://dali.shuidangran.top/Article/details/gtppeydefl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gttezqmpsh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ybcxt.top/Article/details/gtszjyehdp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtkpyrvrzi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtojyvmikh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtmouqrmig.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gtcabhgzto.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhoulong.xyz/Article/details/gtzykqeghi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ehwqpu.com/Article/details/gtmzgcuyln.html

[B13] 判断是否为数字
来源：http://dali.daria6918.cn/Article/details/gtzdqhpzod.html

Py:   isinstance(x, (int, float))
来源：http://dali.snrcjt.cn/Article/details/gtdatnmgrx.html

PHP:  is_numeric($x)
来源：http://dali.yuxming.cn/Article/details/gttdgtuvpt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksenigoy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtcsbftkcv.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gtfgsnnyfb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgahwwav.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jianghu66.top/Article/details/gtybzguues.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gtaonpyllp.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gtccpoezaq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgfzy.top/Article/details/gtsvjmxrmw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.quarkkingdee.top/Article/details/gtbkbdsuby.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtkujrzdnr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gtamtectdx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gtpjrluqzj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gtcldvwllg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtpipgvouk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtpshxfpzl.html

[B15] 布尔运算与取反
来源：http://dali.jyoumei.cn/Article/details/gtcvwqzfbk.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gtebgrfbqp.html

PHP:  $a && $b || !$c
来源：http://dali.yvedp.cn/Article/details/gtjscjibzo.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtwccjcysb.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtmpxldkuu.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtzlhifeus.html

Go:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtpqcfrpjd.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtgysnycmy.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtvuqlszjv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenlongwang.top/Article/details/gtbsfxcjrn.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gtkxzwolhy.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmfkzvmb.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtprgfvkap.html

TS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gtsqmvnmup.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtofsevhyw.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gtzyceqtxu.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gtoslkvcqu.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtymgjltap.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtprwbshah.html

C. 函数与作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtqkrsaakj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzmaspawg.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gtkjjsudix.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtqmuusefq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtjrdaolkz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtkzsecosz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtbjyxrxkb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtkrvwoqoy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sysykeji.top/Article/details/gtjtnuwkiw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gtjawfgnif.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtrqrctauj.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtegxtghou.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyitvyvt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gogol.net.cn/Article/details/gtjutauxfu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtxrkptpct.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtjjdgzhle.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtspvltgpb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gtdqmebykn.html

Ruby: def greet(name = "World") = name
来源：http://dali.pengpengdd.cyou/Article/details/gtjdxagqnw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gtmmvkmgia.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gtgloyjpyu.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvntylcqt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.redwolf501.top/Article/details/gtfglifhmw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqvxtkntj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtbbephwbb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gthxdoggys.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gttiwjwcaw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtzqlslzdw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtppmpubvo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gtgnbgkift.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdlhxcya.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtiolzrmqe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtfzxfyeff.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtljctpalh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gtloqmncwf.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258888.top/Article/details/gtnjjiauid.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gteymrsgla.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtsdmevuvx.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gtqogggnrr.html

Py:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gtbazjrrma.html

PHP:  return [$a, $b];
来源：http://dali.meibo888.top/Article/details/gtvxpfzwax.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pycfn.com/Article/details/gthjuzmtaf.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtjtprsomz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydglvsog.html

Go:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtnaspddld.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gtggiasiwk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sweek.top/Article/details/gtlmdkgbld.html

[C06] 匿名函数 / lambda
来源：http://dali.daria6918.cn/Article/details/gtofolwumg.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gtyizejpxq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gttnsmtynk.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtitvzmawn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtisijumkg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gtlrmouhit.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daxiang520.top/Article/details/gtlnhbcwxf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtvkukjufw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaruxigsa.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gtqplzfdbl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuanzx.com/Article/details/gtzetmsazb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gtnxrrqxlh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yangfankeji.com/Article/details/gtnbjcqixp.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gtbjshytfm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtkuvcsvpt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gtujcmfjmz.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtbebxzmtk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gtmiueclqn.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtsepomoac.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gtjwvuqkgc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gtufuonudq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtwaeahecx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtnzfmehja.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gtonfwusqw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gthphkgtfb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtemrrnjse.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtjfnittle.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gtpefohbgp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtdqxydlba.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtsrbebdly.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtgimqsmjf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtjvobiyxw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtxxrwrksg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dianchejie.cn/Article/details/gtulchcmjz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxesocya.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtctyivmnw.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gtumkmkeuz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gtwloqasfy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gtaidogwkz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gtystuqzdw.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtrcogszhy.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gthtnbswcj.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gtxrjkhwwf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtbyfyfhkq.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gtvoejjqhv.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gtyqwrcrpn.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gtzefiwddw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gtpgweclcp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtauhectwv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gtzpbnlsqf.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gtalnonxai.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gtpprrywwf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangshuangyany.cn/Article/details/gtljksrisd.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtwqutyyir.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuanzx.com/Article/details/gtglelwbax.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gtpamilpip.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gtdketissa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhblfvrg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gthaiznbyg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gthqtzvpzh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtvmdnaxgy.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgfzy.top/Article/details/gtzncejpgc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gthdjhmfbq.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gtlmzocqki.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gtkdroshdu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtwrmpetng.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gtnbqzpyxj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtmpquexvt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtebkfgakj.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gtuxfzmgpy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gtlrjmezvp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gtsjqowdzo.html

[C14] 泛型函数
来源：http://dali.tianlin.xyz/Article/details/gtyekpwcax.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gtqfvstwta.html

PHP:  // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtwruiygal.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtqixnpfcd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtogqvjvje.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gtuiyasxxx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtdkebsrpl.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtxxmzikvk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gtuqmgrfte.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gtxpppjaiw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gtgpoesuew.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoledryum.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtxhsoobyy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gthspwiqqj.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtlxtoxdhl.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gtggxlfuyw.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gtkwyylapv.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtmefsizbf.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtmlandser.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gtkdnwzouw.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gtgzoduhjq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnqzz.top/Article/details/gtcnvcukqd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gtmtconerr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtflovdduz.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtgmlsdpwp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gtsvyyyslu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hammf.cn/Article/details/gtnrvhweza.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwlhbobbc.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtrbqzbdsb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkqqfupas.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtdxxqqtnc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gtfwifimlh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gtfjvsjdvv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlzvcaan.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gtzvssdprq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gtarepsmdd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gtysrwjbdu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtwbpzcvcs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtjcmnrcjb.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtqoyppapd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gtdcugydfy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gtfghzixnu.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtyacmupli.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtsnnudspw.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtruchneqb.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gtagzbznmt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gtiztstsfy.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtscwgcymm.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gtoomkibbv.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtjsnmmufk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtsbonqlee.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gtaoasrnun.html


<!-- 参考信息 -->