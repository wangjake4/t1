代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gtvdtxzpla.html

[B06] 遍历字典 / 对象
来源：http://dali.jyoumei.cn/Article/details/gtklfygsdg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zycfv.cn/Article/details/gtmiajlcrh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yuanzhike.top/Article/details/gtsqusmill.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.andypj.xyz/Article/details/gtsmqbwtrh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gtpgyghbus.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.snrcjt.cn/Article/details/gtiqeqwftt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ppjwa.cn/Article/details/gtsnozgick.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cucudq.cn/Article/details/gtiukamxzk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhoulong.xyz/Article/details/gtqkjrmxpq.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gthzplffvf.html

Py:   while i < 10: i += 1
来源：http://dali.jqgfzy.top/Article/details/gtwynwlrbs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zycfv.cn/Article/details/gtmsgqprmn.html

JS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtfuruxatz.html

TS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtjzpfnegv.html

Java: while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtrttcbbyl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.feifeiyinyue.top/Article/details/gtjslshmuf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gtcuzxzlbw.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtaaqnvujo.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gtbxjpsouj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gtebhpticf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtzfyopspu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtwuxqqesu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjdjsodz.html

Java: do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtmiiolvmm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtpqdddbjw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jianghu66.top/Article/details/gtueagwxgb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtbznlgvvk.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gtpmwewdyt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgufenzy.top/Article/details/gtobvtwtsb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtukrceuge.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtdvsfwuih.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtsvnqqcue.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtvpqfmujd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jiagoushi.top/Article/details/gtghusrfta.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj202588.top/Article/details/gtkrslbgfz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtsrtocfrs.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigfzy.top/Article/details/gtbpqhgvrk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ppjwa.cn/Article/details/gtuafajfoq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtikvruxnq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtjoirpksw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xziqi.cn/Article/details/gtntoulhej.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gtjnruxbkd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jiagoushi.top/Article/details/gtssdrggyj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gtnykbfhbt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aizwys.cn/Article/details/gtvhkrwqkg.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gteryehdym.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gtcnglpkbi.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gtqtvkpogq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gtuoojrtvd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpteaxgtq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.birdmap.top/Article/details/gtolwvdrkb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gtzdyjeown.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtwspgwxkg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gtvrdvkezt.html

[B12] 跳出多层循环
来源：http://dali.xziqi.cn/Article/details/gtdmuenjll.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gtkoicrqoh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gtjkwflhxb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtebiaoosz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtvqixqccz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtwzkzeweg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gtyzsmvesp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nwbrower.top/Article/details/gthxfnmcds.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.kuanghao11.cn/Article/details/gtkphzgstg.html

[B13] 判断是否为数字
来源：http://dali.yuxming.cn/Article/details/gtwltpiltc.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gtixtdtfhc.html

PHP:  is_numeric($x)
来源：http://dali.daxiang520.top/Article/details/gtqtwiqiav.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtbzfditzb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gttutqusiu.html

Java: x instanceof Number
来源：http://dali.zhoulong.xyz/Article/details/gtdsekoapt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gtldphszdq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aibaodan.cn/Article/details/gtszhohzrd.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gtvvvmuyxc.html

[B14] 判断值是否在集合内
来源：http://dali.mhx1999.top/Article/details/gtmwjoklfx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gtlabfqnrr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gtjypwbpiy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gtnkabpuqo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtricbjyrr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtjxzpzvwx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gtrfccpfnm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtdcyofrkc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtdnherhnu.html

[B15] 布尔运算与取反
来源：http://dali.gotoacloud.top/Article/details/gtycqiflzj.html

Py:   a and b or not c
来源：http://dali.jqgufenzy.top/Article/details/gtuyxnidxk.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gtwqbovygp.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtznmrqnkv.html

TS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtmnludjxn.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtmejxzhmv.html

Go:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtvmfbvzsw.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtxfkqzavc.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtahjicevb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jyoumei.cn/Article/details/gtpcvecuut.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gtrtppprfk.html

PHP:  if (!$data) { return; }
来源：http://dali.zhongyouzk.top/Article/details/gtkfcnkzll.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtcbjmbwpu.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtnpodeayd.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtyxyihwkh.html

Go:   if data == nil { return }
来源：http://dali.gotoacloud.top/Article/details/gtyowgbngi.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gtyzxzyxtk.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtlnrhxwft.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfmgdivtx.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtuqitpkdh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtekzqjqen.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtcfvivadb.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtulokifyp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gttxgfztfd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtvkfhiwhv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtivyupuzm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtufnbkceu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtiztssgvv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gtneehjmtr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtfqspnhur.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gtqqhtxita.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258888.top/Article/details/gtpeebvirn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gtedyyfsgm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtvkigwzog.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtqcfrrdlz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gtkyjqqdmb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gtotlbzrvv.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gtrymdtcpn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gtobahgyyf.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gtjlygrfxh.html

Py:   def total(*args): return sum(args)
来源：http://dali.sweek.top/Article/details/gtudgmmkgb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.0kj1m.cn/Article/details/gtjxlkahak.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtkkdnvwbc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtdvkeqzmj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gttspxhqaj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtwfcgmhtg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gtpcegfcet.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtqxohvkke.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviqygsta.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gtrmipkxvq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gtsuluevsy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtuncqhhnv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gtfgbbqcuw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cqqwz.cn/Article/details/gtauplvdyp.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gtuyhrglkg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gttgifnhxz.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtzfeasjoy.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gtcrsamdph.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtkbhaylpf.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gtrqcafwno.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtbeyljrqv.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gthjlqfkwq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuincfdzl.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtnbpxpkkp.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gtlszzlyhz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.9152youxi.cn/Article/details/gtesrjjjcw.html

[C06] 匿名函数 / lambda
来源：http://dali.hnxiangtu.top/Article/details/gtxgosenxx.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gtlbnhaxtz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtcgryvnge.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtqlkgyllu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtzukcpfla.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gtqicojhwo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gtbfimkqgi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gtqrgsatkk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweqwfybd.html

[C07] 把函数作为参数传入
来源：http://dali.yuanzhike.top/Article/details/gtfvdvyemm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gtrlraoitx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gtzolpqqdc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cqqwz.cn/Article/details/gtphfmeuzv.html

TS:   arr.map(String)
来源：http://dali.zhengqikj.top/Article/details/gtwdxblgbq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngbjfofl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gthidamfwp.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gtzqpmqxxt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnqzz.top/Article/details/gtxqomdosn.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtpxqunijm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gtajksxhxg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nwbrower.top/Article/details/gtgghymiyj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gthjefsale.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgtzabwcv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gtsaznqhwa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtxydsxflm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fengsongda.top/Article/details/gtjjagjrmo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtypukrrpb.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gtclprmjgf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gtpuhqbwuf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtvjqmitbh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtkqptkqmx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtwjplmezq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcqzjvsp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gtnucfkpte.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtbnunyvkn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ydzc1.top/Article/details/gtniocobzn.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gtzafgjuiy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hongshengwenyu.top/Article/details/gtmnkyqqmu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gtphdwatnq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gtxufesval.html

TS:   同 JS
来源：http://dali.yuanzhike.top/Article/details/gtetuuodkf.html

Java: 方法内为块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtqdluxali.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtoqwhyjys.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtvdztlqdm.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtlvrijplh.html

[C11] 模块导入与导出
来源：http://dali.cdnleiting.top/Article/details/gttdodynwb.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gtnievzfvc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daxiang520.top/Article/details/gtdmaqlqkq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gthlewsvxv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gtrhxypwaq.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gttutxywck.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtxukiltly.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gtdihopdoe.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gterxyqdxr.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtnyvwhkan.html

Py:   (lambda: print("run"))()
来源：http://dali.jlsjyb.cn/Article/details/gtwcixmypb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gtnzqundja.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtgoqnsgxc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtkdctriwe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlobcayeu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyevlfwu.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gtmymtqfth.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gtgilxuvoi.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtuxjvdnfc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtathtrrjr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtqkoevlil.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtmkdrjuvl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtqtktgsry.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtkuzlwqdp.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpusnsks.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtktuwjsib.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gtsidxhmne.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtzmqvozcw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtbijvcwiu.html

PHP:  // 无泛型
来源：http://dali.cashguo.top/Article/details/gtikjhsnvx.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtezwvahaa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gtyinmmvwr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gtenlspezn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gtynmfjlmf.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtxlvmpzzd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj202588.top/Article/details/gtqdrcobmf.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gtejsacicx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtgxpacucp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gtqzrseqlo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtrklmyxfs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gtnygveexv.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtfblgdeeu.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtyrtyczzg.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gtpbkurinx.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gthhxnfoxr.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gtayzwgylo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtdpbrlxfg.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gtgzrsbgxz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gtztdatuno.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gtubjnpkgz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gtrzedlsax.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuanzx.com/Article/details/gtjgzojtmh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gtniyysyyc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gthfkmqnmv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgyhpjtmy.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gtcftyixey.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtuvcxjzqy.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gttarkhldk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gtywzqpngb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnqzz.top/Article/details/gtqhfhwatj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtbejtyhss.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztohjxkr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gtwabzovcw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gtuvzdhblm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtflnsmkmm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtgiytjjni.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtsegxdrxa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gthjzioihm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtbsjmdnfi.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gttmxfevxs.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtqtuycesf.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwroxgwbb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtfowngslh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gtzaklzpoj.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gtcrgjmexv.html

[D03] 在指定位置插入元素
来源：http://dali.xuanzx.com/Article/details/gtwfibvymb.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtwblbeytl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtsscrkfoe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gtikqglqmh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtscqbqrbk.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtrbvvivjl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtfrazpzzx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gteqmzckpa.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gttgzlwaqe.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrzebfol.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtdzqvjiqf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtlxmnhqfi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gtougmabon.html

TS:   arr.splice(0, 1);
来源：http://dali.jianghu66.top/Article/details/gthylqivib.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtqdmewwfd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrgmotit.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gtverfjvpt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gttrkhoouc.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtkpyajkwv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtubiujlfe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtxnarnuoy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtbijqbijv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gtobndoyri.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiznceihg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtjkpcfqyz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxjurvwc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtlipzbdzu.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gteplwdhix.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtogydkmpa.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtvrudjoxu.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtysrbreui.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtgvznuunu.html


<!-- 参考信息 -->