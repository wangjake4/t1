代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.svipenyu.cn/Article/details/gtmrvmhzrz.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gtpvgikyzj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fzhhl.top/Article/details/gtelrnnian.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gttbrafrkq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtdeqttnee.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtpvcqfqte.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hysaishi.cn/Article/details/gttynqpenk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj202588.top/Article/details/gtanpraxwu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ivvv.top/Article/details/gtiqzabuqy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.redwolf501.top/Article/details/gtxtxfostp.html

[B07] while 循环
来源：http://dali.vqdsnc.cn/Article/details/gtyruxkzsm.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gtuviztgsa.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtjtsvobir.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqsyhcofj.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtjrvxqveq.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtdzllufte.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gtrsfpufgm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shzxlz.cn/Article/details/gttwwvvipc.html

C#:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtiuomevpr.html

[B08] do-while（至少执行一次）
来源：http://dali.yuxming.cn/Article/details/gtxnlxqgxx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258.top/Article/details/gtpjkrrxrb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtgjrgewcq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtohtvdrhh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gttvfwkbgh.html

Java: do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtejeiuctf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gtaansopbk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnqzz.top/Article/details/gtzlkbtifo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtprsqqkol.html

[B09] break 与 continue
来源：http://dali.redwolf501.top/Article/details/gttswermke.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.snrcjt.cn/Article/details/gtjhpsgqlw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtvuttkohs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfllvonkw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtxgzznfih.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtzauntczi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gtnaavghrz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhoulong.xyz/Article/details/gtsjlvdckm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfovqypw.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtvrmjavtu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ybcxt.top/Article/details/gtntnhalmu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hfpthk.cn/Article/details/gtvkiedywq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtkbgcmxlt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gtfcwyoarh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gtiqrdwybn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.vqdsnc.cn/Article/details/gtlwxbcdrh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuanzx.com/Article/details/gtlomvgxbc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.9152youxi.cn/Article/details/gtwwrsvjpc.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gtwzhdnaza.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gthqzsecuf.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gtfwwcmeng.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtdqiuwxuw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtfqcmucza.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuanzx.com/Article/details/gtrrkojrnt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.c1oappe.top/Article/details/gtoscgephz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrcruhgj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cheryme.top/Article/details/gtxxonaldq.html

[B12] 跳出多层循环
来源：http://dali.smart0.xyz/Article/details/gtolaxalts.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gogol.net.cn/Article/details/gtowyxygrq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jianghu66.top/Article/details/gtbzweolqh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtdnmcisep.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gthfbwxncz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtrzbbyast.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gtpaxfktdn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gtzamuquhs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jianghu66.top/Article/details/gtnbdznnms.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gtqdulnryz.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258.top/Article/details/gtrbxfberv.html

PHP:  is_numeric($x)
来源：http://dali.jiagoushi.top/Article/details/gtqohqacaa.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtumfjmkjx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtgcaruwcq.html

Java: x instanceof Number
来源：http://dali.redwolf501.top/Article/details/gtuylplqtk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gteuzvzxuh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtqrfstjfq.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gtdzaaoxyt.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gtmigaqrjk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pycfn.com/Article/details/gtbyzekltm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiodlocky.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtdlbyeczc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtvdlajnwl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gtftdwgqih.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtavpmyfnj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtdzwtrjrq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtcnxkahmk.html

[B15] 布尔运算与取反
来源：http://dali.jyoumei.cn/Article/details/gtmamdlxbe.html

Py:   a and b or not c
来源：http://dali.yj20258888.top/Article/details/gthaxnjzpr.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gtylqocvgn.html

JS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtjcuciovt.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtnouweuoo.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtxncjgojl.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtnihycouw.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtuykeedrg.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtrnxouegw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jlsjyb.cn/Article/details/gtildeqcwx.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtkgwceilg.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gtuilmtfyj.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtotynrdvf.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtehrfsrxk.html

Java: if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtaicqylpw.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gtuvtsxxbk.html

Ruby: return if data.nil?
来源：http://dali.daria6918.cn/Article/details/gtdhfjkecn.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtfjzjprhd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthrhmcrdi.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gtcolkvwwn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtslsrxxhj.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtvlychffb.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtefescdtt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtkgaahlyj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtpzawaayt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtslwmtxau.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtofvifruc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sxryk.cn/Article/details/gtnycxampm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gttvrpeiro.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gttzqkfmbh.html

[C02] 默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gthvjapufv.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gtlcbheoez.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gtuqoeuard.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtdnjuptvv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtppdwfvik.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzyvrgbm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtzluknxuw.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gtijbcqvpm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.iojbl.cn/Article/details/gtdcjdzifd.html

[C03] 可变参数
来源：http://dali.chenjidiqi.icu/Article/details/gtotswhyvq.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gtmyqwwclm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shuidangran.top/Article/details/gtjtadfpul.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtrusevonl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtclqdkxdu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtjohhvtjz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.smart0.xyz/Article/details/gtnqrbnfux.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenjidiqi.icu/Article/details/gtecmwthhb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gtyiwhejyv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gtvkquugnx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtjgqckwml.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gtoduzscrr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtgpuwsoik.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gtksxxmajl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gtftsympzo.html

Go:   // 无：用配置结构体参数
来源：http://dali.tian-w.cn/Article/details/gtrleaqzbx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gteeodkvts.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexahntay.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gtkuuejwnn.html

Py:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtrckxuxko.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtumuzzgsr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtwnxmqpkl.html

TS:   return { a, b };
来源：http://dali.cheryme.top/Article/details/gtsqsxvcpe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gthdjeifof.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gthkkavalx.html

Ruby: return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtahcqszxe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gtduldxntr.html

[C06] 匿名函数 / lambda
来源：http://dali.guowangkeji.top/Article/details/gtrcaiuzxx.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtzjbgzrey.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtudzsshay.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtjczdqnhb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtvbofvrzj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gtnipandpy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gtpaxjelii.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtpfpaiuih.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtzeaehhym.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigfzy.top/Article/details/gtczpqkgtw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ppjwa.cn/Article/details/gtduomwtbl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtqaadroiq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtqhjylpkg.html

TS:   arr.map(String)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoklzcoyu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtufhrzwsc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gtwiuraqxn.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtpwasgmpl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtpmniwapn.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gtagxexlmx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gtqzntbmmo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gtqzvjppuq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtqooddioa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtrcjvlydz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gtrjhnmcqh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtatjkglqn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gtohukpais.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtzqnulgha.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gtkpzmypfv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtxkopqfdz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gttzlxnvgz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gthxtqvunn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtecijirjz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtnjqfwqao.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dashuyun.cn/Article/details/gtdlqxcqhx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtartyjwob.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.kuanghao11.cn/Article/details/gthqerfvns.html

[C10] 变量作用域
来源：http://dali.gaohongyu789.top/Article/details/gtpxgzrxiu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gtbvupcmze.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxuzmnkp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtnckqwhzu.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtyngrcbzd.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtmbpgqpvf.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtmpikzrmw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gthozkweha.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtqvonjtvl.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtvtltwwes.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtswywicxb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gtmoulztsv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtfswlapvi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gtqrfavcdn.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gtutiitvvt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqkcsnas.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtbkybba.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtkwaibjaj.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtrodordeb.html

Py:   (lambda: print("run"))()
来源：http://dali.wangshuangyany.cn/Article/details/gtwplihydv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenzaomai.com/Article/details/gtvdoepvqq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtavssqdqu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtdoplxecf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gthlmfcoka.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hammf.cn/Article/details/gtusvggwyz.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gtacbuvipn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtjrfekjah.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gtryyzqxca.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gtjbpatslh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyqzcnnxe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gtbdfokwks.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdzqhhxs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtswjcbsvt.html

Go:   func add(a, b int) int
来源：http://dali.9152youxi.cn/Article/details/gtwwuceaiz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gteuarixbz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtggcxdpik.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlaxnhaqw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gtjwhkqeep.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzetcsgv.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtzeatypmr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gtfeplbdow.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.snrcjt.cn/Article/details/gtfslmkbpf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtcyyojgay.html

Ruby: # 无泛型
来源：http://dali.xuanzx.com/Article/details/gtwqqulwvn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gtdegptbkf.html

[C15] 解构 / 展开参数
来源：http://dali.ehwqpu.com/Article/details/gtghldqzot.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gtekxpltru.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gtklwxanyr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gtwqjbewda.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzljniixr.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtauenspfx.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtqjhkiaqh.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gtqrycieqd.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gtoeejxlnr.html

[C16] 函数 / 方法重载
来源：http://dali.yonumen.top/Article/details/gtezdxkykv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtptcvsfcw.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gtwnmeslsc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gtfwxbtvhq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aibaodan.cn/Article/details/gtppcmsupz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gtsyzsuqmq.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtqbsoiyin.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gtqrrtxzul.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxsomtrw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmvpphclk.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gtdpxhzgci.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzhttcvhx.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtbjxakioa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.snrcjt.cn/Article/details/gtidahwvsl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtvnkkwxro.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gtmhnzyvwp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gtyneywnkr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtszdthskd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhpoesnt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtzssrmplx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gtsprjtvdx.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqukpacq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtmxtoifoi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gthrjxmpjz.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtbefzdudf.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gttpsmvflf.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gtcboftbdw.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtgwdzprch.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gttanbrruo.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtkbpejuph.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gtioztnhir.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gtwjtezuno.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtfwiygwfg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtiwwfzoom.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gtrgdasenm.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gtlwcmpaca.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gtekbhkfyy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangtech.top/Article/details/gttzpavfln.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtsrrhqyje.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtikyavxlz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gtowczxrdt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtpltvrups.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gtemagcfug.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gtrnvllfmz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gtplsutkwq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtzgnzkxoj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.smart0.xyz/Article/details/gtdsrgkemf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gtumtsuawo.html

[D05] 访问与修改元素
来源：http://dali.daxiang520.top/Article/details/gtaetxlzxj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtpiogxwgl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtkitqmlgt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtqqfqafjd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gthrzsctid.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gtwlbrwutj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtpdwzcezh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtompukyyw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gttgwpqoet.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gtxfgovesm.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtkjnrbnye.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtsnmztpmk.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtsaakaqle.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtlarkfdsa.html


<!-- 参考信息 -->