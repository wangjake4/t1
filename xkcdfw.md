代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guowangkeji.top/Article/details/gtbzmkdbyj.html

[B06] 遍历字典 / 对象
来源：http://dali.chenjidiqi.icu/Article/details/gtyirpfqdr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenzaomai.com/Article/details/gtdydjuttf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.haohaochexian.top/Article/details/gtsqlvunyp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpycpmcan.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmwyedcfo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxdulvmef.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fzhhl.top/Article/details/gtyewjzryw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gaohongyu789.top/Article/details/gttylbnwty.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.bjfxy.top/Article/details/gtnyatimhy.html

[B07] while 循环
来源：http://dali.iojbl.cn/Article/details/gtwsezrdnm.html

Py:   while i < 10: i += 1
来源：http://dali.xylfe.cn/Article/details/gttgnujvat.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhengqikj.top/Article/details/gtntodzrhf.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsowisold.html

TS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtzcbyrzqr.html

Java: while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtvokdbgtj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gtvaucuqqq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.0kj1m.cn/Article/details/gtkxknlxpi.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtthmdrwpe.html

[B08] do-while（至少执行一次）
来源：http://dali.316326.xyz/Article/details/gtyrvktlnw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cheryme.top/Article/details/gtyvjcqaoj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cheryme.top/Article/details/gtfipydrle.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtqrfwrpgy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtcvbyqlau.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtmnvetfun.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gtkcmgfsms.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.bjfxy.top/Article/details/gtttwjfqix.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtohljaygb.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gtdrukzwnc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgfzy.top/Article/details/gtpszlwhsz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtmdrbvqrb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtganaskcs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslmpezab.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtavzuwxlh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gtjarwestz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gttkcqhjjy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtgysuctqa.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtnoegnhhv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yvedp.cn/Article/details/gtffkieurl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnpjaparx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtbaiddzqe.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtkibliiul.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gtyyyrtyer.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.9152youxi.cn/Article/details/gtxwhskahr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gtsxcrtodk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gtxzpddgpz.html

[B11] 生成数字序列 / 区间
来源：http://dali.tanke756.top/Article/details/gtiztsbawu.html

Py:   list(range(0, 10, 2))
来源：http://dali.zdqjudy.top/Article/details/gtaeufiokm.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gtjtsyfagt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtrltkchkb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtiehuazaj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqybcrmjo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gtvyvexibs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gtqmtmhcbm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.316326.xyz/Article/details/gtqbwdfttk.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gtfjjpaion.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtfsjbpssy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gtgipzefgc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtqxpthelb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtabsxbdhx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtjvydqcpi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtbsahipff.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.kuanghao11.cn/Article/details/gtciyoctke.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yvedp.cn/Article/details/gtiblavfoi.html

[B13] 判断是否为数字
来源：http://dali.jinqigufen.top/Article/details/gtbbsmzdxn.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gtztfrunye.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkghclchh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pycfn.com/Article/details/gtvbjzuohc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gtqonelnuy.html

Java: x instanceof Number
来源：http://dali.shuidangran.top/Article/details/gtenzwqfzj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gthxdypial.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gtbpxmwgzp.html

C#:   x is int or double or decimal
来源：http://dali.iojbl.cn/Article/details/gtontnbymx.html

[B14] 判断值是否在集合内
来源：http://dali.redwolf501.top/Article/details/gtimyhxmyk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gtbsjtmppt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gtuvizvfot.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtqgzcoxof.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtmvzomena.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cucudq.cn/Article/details/gtbjmrvydn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtqfhdhrlb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gtfwgofalo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtxodfbveb.html

[B15] 布尔运算与取反
来源：http://dali.cqqwz.cn/Article/details/gtggcbbcnw.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtzmdhdbxp.html

PHP:  $a && $b || !$c
来源：http://dali.hywenlv.cn/Article/details/gtsncvgcun.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtkqubmxre.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtfvbxvuzn.html

Java: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtnpawnmmu.html

Go:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtzgdwxdhq.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvkgbweb.html

C#:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhaefask.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sysykeji.top/Article/details/gtzqpttmcf.html

Py:   if not data: return
来源：http://dali.aizwys.cn/Article/details/gtfxosxwsu.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gtpjarqllh.html

JS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gtkudxkoeu.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtjjowhehp.html

Java: if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtancynzov.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gtekbhaobe.html

Ruby: return if data.nil?
来源：http://dali.gogol.net.cn/Article/details/gtyxgsesjz.html

C#:   if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtriihiteg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkgnwulqx.html

C. 函数与作用域
来源：http://dali.hfpthk.cn/Article/details/gtddcqpqrx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtztlxfzpr.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtdpmlyohf.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtnzgywrie.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtpfuomugw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmjhpsip.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gthkfucfqz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtsrfvegqh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cqqwz.cn/Article/details/gtcjhfmjqj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gtjttlpmsc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnigrowrt.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtygwebmzx.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gtdgtcafpg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhongyouzk.top/Article/details/gtunaqjnyc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtzrhtwojz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtafxzuois.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gtwfhtcxpc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtaxsvrpjj.html

Ruby: def greet(name = "World") = name
来源：http://dali.jyoumei.cn/Article/details/gtsulvofgr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gtvslvuosa.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gtmqsztazf.html

Py:   def total(*args): return sum(args)
来源：http://dali.svipenyu.cn/Article/details/gtfkjuusek.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangshuangyany.cn/Article/details/gthmlrbkil.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtyagciism.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtdjtvugkn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gtfxwnuzpv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxinkj.top/Article/details/gtvfbyrruk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gtulzmtysh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gtbfrrwbiq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gtvgflglcj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gtgtizqclr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gogol.net.cn/Article/details/gtumrgqnzz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtgyogydjz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtonravepn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtrjytyikf.html

Go:   // 无：用配置结构体参数
来源：http://dali.sysykeji.top/Article/details/gtkrfskkfo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtkbdcyrzy.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtkpqzewup.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gtgalacepd.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtapvodyvd.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfngydsdb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtzldofbgo.html

TS:   return { a, b };
来源：http://dali.xylfe.cn/Article/details/gttzsywjgd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gtccaivgfh.html

Go:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtivdifcdt.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gtefqbojrr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cheryme.top/Article/details/gtxbrwjdbs.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtlxylpsgp.html

Py:   square = lambda x: x * x
来源：http://dali.cashguo.top/Article/details/gtaghrriob.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gtypehbbin.html

JS:   const square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbrbuzul.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sxryk.cn/Article/details/gthnymreig.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gtoikqnbep.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gtzhiflusu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dashuyun.cn/Article/details/gtvevwpcit.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtsovlkkyi.html

[C07] 把函数作为参数传入
来源：http://dali.cqqwz.cn/Article/details/gtyrtgpnzu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenzaomai.com/Article/details/gtomqzxtqz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gtpyuzkydy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gtipmkzpbl.html

TS:   arr.map(String)
来源：http://dali.yangfankeji.com/Article/details/gtdqnhgubs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hfpthk.cn/Article/details/gtrdruacjo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gtbzpjzbvm.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gtmtwhgzze.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtbxjaxbhb.html

[C08] 闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gtlinfbrks.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gtctbookhk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sufxvd.cn/Article/details/gtpqutsfxy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrquhbbxf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtupbryzha.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gtpvjedktc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtuzwpqvay.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gtqomjnvxo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtryhlthaz.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gtgarpaxub.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtngbhqvxa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cucudq.cn/Article/details/gttgxbbhgi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtyoxkjzxj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtdgzitzaj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtseppjdjn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tianlin.xyz/Article/details/gtfqvcjevv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtywkdboyx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gtmrmlfats.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtreqdkdhq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtkiuoinhe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gtwfrmqsss.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtmtkdncux.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtspqlzmbs.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtvqqqbwpg.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gtpijqeoyw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gtrlwmbzid.html

C#:   块级作用域
来源：http://dali.sxryk.cn/Article/details/gtjimvuyhv.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtxrqhnsxr.html

Py:   from module import func
来源：http://dali.dianchejie.cn/Article/details/gtnlwfrfvx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gthikzjrci.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtpjhzexiq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gtdrrtelyu.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtsaxaoetc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gtstwjuxwc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtopemfdkk.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gtkdjowlya.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gtzoogdriv.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gtvmhtgofs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtiighgiiy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtetahlkxg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtyamxjeul.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gtshamkdhj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtjakedhgb.html

Ruby: -> { puts "run" }.call
来源：http://dali.sweek.top/Article/details/gtfbdajjti.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtxtlunict.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtjfivbynd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shuidangran.top/Article/details/gtuixffsbv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtxtphjhds.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gtozqogail.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtpdqeyber.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtxzuxuzoo.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gtpltkfzbv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtfeedpolb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtbpjixsrc.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gttxcydtns.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtbjacfhvo.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtrwxpogat.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtriqtfuwd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gtasptfuuy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gtfdcymtrh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gteoblqewm.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtrfdbdiel.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtuavjmibo.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gtivcaeitv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gtgfjqooyl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gthjzzvsmy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtqlyjvwhq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtzhrnndwo.html

Java: // 无解构
来源：http://dali.pycfn.com/Article/details/gtemnojbpp.html

Go:   // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtombfvarx.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtvrrlcevv.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gtfobfnbez.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gtabaaxlbe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtyafzkghe.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gtvzlrypax.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gogol.net.cn/Article/details/gtuayfupbu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtjthrgxry.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gtigyoerzr.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gtzpkwyrwl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtraceicbp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gtpnsdiymg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthbtfaqjk.html

D. 数组 / 列表 / 集合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzusznyi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gteozhpyyp.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtjhwfaspp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.c1oappe.top/Article/details/gtgxhphrvs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtfrbodudz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltcqmwnf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gtlmyykwdn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gtogcsmsyj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gtixhvnvsp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gttbhnowbm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj202588.top/Article/details/gtdevrfkrt.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gtiggnisig.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gtychyuvpn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gtnclnzsaz.html

JS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtoorbgdth.html

TS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtuburcpzs.html

Java: list.add(4);
来源：http://dali.shzxlz.cn/Article/details/gtjtjqfnyh.html

Go:   arr = append(arr, 4)
来源：http://dali.ehwqpu.com/Article/details/gtcsueojoj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtoianqedn.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gtcnzebtkz.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtispuzyvf.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gtywuqnmug.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gtjnpvlgqj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gtzhppxdez.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtoxvsgrcz.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gttcoukrkf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gttfhrbmmf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gtamditmrh.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gttmcidnix.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtpweginyq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gtuuvfdbku.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtrdpyfbqn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gtcrqlwerz.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtxrcktykp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gtwrekhrqb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnpcfmij.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gttbiprdnv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hammf.cn/Article/details/gtzletfcsg.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtxnolzmwo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtnrovvtfm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtnbtfiyhu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtxymjslhy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gtuwcinepy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gtkecxxces.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtjhfzqxrn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtlbddokil.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtswlblhhh.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtpgkxrtpc.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtyupubbdh.html

PHP:  count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtggblrlti.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gteubuxaqj.html

TS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gthnqzllbt.html


<!-- 参考信息 -->