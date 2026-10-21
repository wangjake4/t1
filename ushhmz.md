代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hywenlv.cn/Article/details/gtpeqgurri.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gtwgmwysvp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhiwuduotai.top/Article/details/gtboutskkg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cheryme.top/Article/details/gtrccfqiph.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gtsajozkzw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gtviggocfa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.iojbl.cn/Article/details/gtvolnqtab.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shzxlz.cn/Article/details/gtfglbeqdz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gtywqusvgs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gtfsmnywlz.html

[B07] while 循环
来源：http://dali.wangshuangyany.cn/Article/details/gtargohwmw.html

Py:   while i < 10: i += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtpfqmlmje.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gtbdsmkemg.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtddkkpguz.html

TS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtfyejidbq.html

Java: while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtiazlyadh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sweek.top/Article/details/gtulftuulk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.andypj.xyz/Article/details/gtbjfnqmgo.html

C#:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtudhcvhwl.html

[B08] do-while（至少执行一次）
来源：http://dali.xylfe.cn/Article/details/gtmvfedqfb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuxming.cn/Article/details/gtzchsfxfm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtrccxtjln.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtkulrhphh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtkpeuxkmj.html

Java: do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtgzfjlyzs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gtzfpuitsj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhongyouzk.top/Article/details/gtlyvychan.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtkxgxxbko.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gttpqdkcws.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dashuyun.cn/Article/details/gtlpggqvul.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtintvuwpb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtfkhvbitr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtzhwdcvgs.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtfsfhbgcw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gtnsxcwzxs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guowangkeji.top/Article/details/gtgfgdbkem.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtoiinalzc.html

[B10] 遍历同时拿索引
来源：http://dali.fengsongda.top/Article/details/gtdhiphyjy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckenwrow.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.0kj1m.cn/Article/details/gtovfytfis.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gtqdfahmdu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtikrsfime.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gtzvfhlprl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhiwuduotai.top/Article/details/gtrefcwwha.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.haohaochexian.top/Article/details/gtafxgkbip.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aizwys.cn/Article/details/gtzyueycev.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gtnlwofyqs.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gtkiamcdtp.html

PHP:  range(0, 10, 2);
来源：http://dali.hfpthk.cn/Article/details/gterkloarr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtkklvamio.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gtjyduusvm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dashuyun.cn/Article/details/gtuwhspoii.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tian-w.cn/Article/details/gtuaoywnrd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxmoitge.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shuidangran.top/Article/details/gtlmncqpte.html

[B12] 跳出多层循环
来源：http://dali.cdnleiting.top/Article/details/gtsomrexdd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yanxiufei.cn/Article/details/gtktehzadg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hywenlv.cn/Article/details/gthtbidzpa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtraoncjkz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gteruekisv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtkhohclpo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gtrqdijrex.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gtbteyfqxm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cdnleiting.top/Article/details/gtttywhymj.html

[B13] 判断是否为数字
来源：http://dali.aibaodan.cn/Article/details/gtzbbntrgd.html

Py:   isinstance(x, (int, float))
来源：http://dali.yvedp.cn/Article/details/gtvlgyarvw.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gtfulcvtyj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtvsjtqrmn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtrmglocgb.html

Java: x instanceof Number
来源：http://dali.fzhhl.top/Article/details/gtpoipqwqv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fengsongda.top/Article/details/gtpaibwxva.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aizwys.cn/Article/details/gtojqnxzev.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gtmnecbiwa.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gtugvkycwe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gtgyglwnff.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtvyiywvmm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtthupafso.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtjzyfgblr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtjulbqsez.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tanke756.top/Article/details/gtsogncoll.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtbckkrmzc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtsjitbveo.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gtngqfojxr.html

Py:   a and b or not c
来源：http://dali.birdmap.top/Article/details/gthhctrahw.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gtxwajjhcx.html

JS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtvgcezoqs.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtleasnozv.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtrivzwflb.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtxfxevyan.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtguycvtze.html

C#:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtdxfuwiui.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtctfhukhf.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gtlwgyzbka.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258.top/Article/details/gtvnpozsrj.html

JS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtsesjpqyj.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtbztrzvmf.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtqjeojeqo.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gtparwggsw.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtplbpovyq.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gttgyboean.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuqxfrrom.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gtazfubnuc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndlkdqsw.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtmchvlzga.html

Py:   def add(a, b): return a + b
来源：http://dali.smart0.xyz/Article/details/gtofzywwkx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtpdarnzdo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtrqpgfsfk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtzpnhtaex.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtttusmvsj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtklvqkqtk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gthmibsdaz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtyheofbsj.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gtoyiipoys.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtzjcakzvg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gtwemevccz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gtvnpiassi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gttrpszeaz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gtvuegjifm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.316326.xyz/Article/details/gtsymvkrjs.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtkqnqkyhv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtdatrxsuj.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gtkfgidiyl.html

Py:   def total(*args): return sum(args)
来源：http://dali.9152youxi.cn/Article/details/gtomiinefj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.mhx1999.top/Article/details/gtmdbretub.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gthiuthxyv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtqrqijhhy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gtijsglaev.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gtpvlicgcx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gtpixawncl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtseeovlea.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guowangkeji.top/Article/details/gtgrdwhkds.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gtqfdllgrs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dashuyun.cn/Article/details/gthiykurps.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gteurjqjmh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtkzaicpak.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtueupavfn.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gtikhwostv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtubviiazd.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtxlqapdro.html

[C05] 返回多个值
来源：http://dali.hfpthk.cn/Article/details/gtedxctpqf.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtoxhghbkv.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gtqghzjsfx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtuoiteuue.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtshsisuvv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gtyfkcpgfc.html

Go:   return a, b
来源：http://dali.mhx1999.top/Article/details/gtdrmetket.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtufwlbkme.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gtsvjklkxm.html

[C06] 匿名函数 / lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpzrjlwi.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtgoelhfdr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbigrmudx.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtxqrjcrdv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtlywtblva.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gtxqfyraot.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gtvaegvgbn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhthxedw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtfzexyumq.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtmuhzexob.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gtmumhljze.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnqzz.top/Article/details/gtprpwrhvw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gtejmoxtgc.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gtajenchmn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gtmpzfougv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sxryk.cn/Article/details/gtsaflcldm.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtuijvhfnv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjdqhcir.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqmurqyy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gtyqcddmoc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sxryk.cn/Article/details/gttnveqhwk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtxpitjdwt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexcgtxld.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gtkqjmotzf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gtkypfhgqb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangdashe.top/Article/details/gtqrcfyykn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtsqzirvok.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtrtooswvy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtsyxaysmb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtylwnykir.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasdhaogm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtfoxztfpx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtjollcbsf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangshuangyany.cn/Article/details/gtlixnoxhy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtizezzyrr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gteiskypac.html

[C10] 变量作用域
来源：http://dali.zhoulong.xyz/Article/details/gtzcyvwbql.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.iojbl.cn/Article/details/gtkbmftsnq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqdccbjh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gtmalswmjd.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gtfpysgazo.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gtcfmvrzcj.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gttkxkhlzi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gtzodrujmm.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gtkzfpoljq.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gtoxddcnvg.html

Py:   from module import func
来源：http://dali.xylfe.cn/Article/details/gtaoatssuo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gtjxkmhycn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gthtbufwmc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gthjoewjys.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfofsxlf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jyoumei.cn/Article/details/gtsfawauhm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gtdwessrzm.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gtaraoqwfr.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhengqikj.top/Article/details/gtdtdizoae.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gtiuptbiwv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtcxcmtvnq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtaqsiuagv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtpgvwmuqo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtvpgynqdc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gtipimtlgx.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtsehqtwqh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtdkiyyawu.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gtspyyeygl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtjhengvho.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtojtjqskg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gtwfprjvfx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtbjdixeyt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtoscgfnpl.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtiecrslxu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtpxnoehjw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gtwpbslrvz.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gtruzcwpgb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtakdkowzp.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtsdsqwxvn.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtvkddgaub.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gtzzyggihl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttsniydvz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtdsftahyr.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gteeqjtfzf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhengqikj.top/Article/details/gtdlnjzwoy.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gtkqfwobtq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gtuqeycqoo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gtlmumqcdg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtzdblhhum.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtyilwyoyr.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtpwdyzpce.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtysxsrvse.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtxhtovmip.html

C#:   var (a, b) = pair;
来源：http://dali.zycfv.cn/Article/details/gtqmjesnjj.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtlpvkhhmb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtyssvwxka.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtdazsvglz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtstqueoys.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gtzcuoryel.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gtfhlmdzvp.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gtosioagal.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gtaqfjdrbx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gtgncflewf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtaoxvajbl.html

D. 数组 / 列表 / 集合
来源：http://dali.sweek.top/Article/details/gtnvwvbvba.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgvwezibs.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gthehijbew.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gtnyyohixr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtvpuewiue.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gthlpaomnq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dianchejie.cn/Article/details/gtukaazmyd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gtxfczaszm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gthmoiewym.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtqgifbkqx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gtqrborlpe.html

[D02] 追加元素到末尾
来源：http://dali.yanxiufei.cn/Article/details/gtglcupvbu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtmkxvklqk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gtapablyho.html

JS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthktqfkes.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gttytyyrki.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gtwemsilam.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gtyscvuqyy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gtqoovgqvm.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtozcppfux.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gtqnnjnqui.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gtazzexadf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gtwbwifbre.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gtjdvzmccd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtroqnalyg.html

Java: list.add(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtjjdtxvwt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gtowrfxwxv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gtsaqjvwcm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtgaeyyuhj.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtdngfeodd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258.top/Article/details/gtjyefegtq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtdfzzcdym.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gtrhjzrytg.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtkgxkweiu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnqzz.top/Article/details/gthxtpcsoz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtglhbyctc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guowangkeji.top/Article/details/gtbtuooogd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpxuavtm.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gtffzrrxkq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtiiansjvi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtvlyzkwvq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gttzhewozz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gtjfzdruub.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gtdweypomx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtwywtyudd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtpwbfdajp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtfzcbqmwi.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gtjjcsfdxw.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtdefbajoj.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gthceobylz.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtejzgtqjt.html

TS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtcwyqekle.html


<!-- 参考信息 -->