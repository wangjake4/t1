代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtsahgmtea.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jianghu66.top/Article/details/gtspbhyrhd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gtbixfodor.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aizwys.cn/Article/details/gtgnaeudvx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cashguo.top/Article/details/gttrxwovqw.html

[B06] 遍历字典 / 对象
来源：http://dali.sxryk.cn/Article/details/gtioyhazlv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gtlbxfxsbx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtclgzpecf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjphnukhj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gtckcuckgm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fzhhl.top/Article/details/gtnnyhpscc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.andypj.xyz/Article/details/gtbsjmmgec.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guowangkeji.top/Article/details/gtzydxqjvl.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gotoacloud.top/Article/details/gtsuszivod.html

[B07] while 循环
来源：http://dali.zhixingplan.top/Article/details/gtwxeougnc.html

Py:   while i < 10: i += 1
来源：http://dali.hnxiangtu.top/Article/details/gtysaluesd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aizwys.cn/Article/details/gtpurzqtkz.html

JS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtxixgoxbf.html

TS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtzviawyyi.html

Java: while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtseiuavds.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cashguo.top/Article/details/gtpxqzxcpg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gotoacloud.top/Article/details/gtxfvgtbdb.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtwxmecyjk.html

[B08] do-while（至少执行一次）
来源：http://dali.cashguo.top/Article/details/gtexqwclnd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gtjogeagwy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitcdxwbu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtljapzaiq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtfjotdokm.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtffhbonga.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtaqozlpfd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnxiangtu.top/Article/details/gtpxikaxws.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtdkjjcwpg.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gtrhvxqlmm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ydzc1.top/Article/details/gtbbonpyra.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcenmwhmq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtpxccgsdo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtpiaadaan.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtwhdbndnm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258888.top/Article/details/gteszmpqwx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sufxvd.cn/Article/details/gtbhlryufr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbdspeqjg.html

[B10] 遍历同时拿索引
来源：http://dali.xziqi.cn/Article/details/gtqjgwtfix.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenjidiqi.icu/Article/details/gtulexwazj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cashguo.top/Article/details/gtjkdmqiuy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtwspzvmak.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtjnearaai.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dianchejie.cn/Article/details/gtktakvinb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.quarkkingdee.top/Article/details/gtgivzupwl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.kuanghao11.cn/Article/details/gtfzzlflnv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.quarkkingdee.top/Article/details/gtmujlfdhx.html

[B11] 生成数字序列 / 区间
来源：http://dali.mhx1999.top/Article/details/gtcfcihhum.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gtnevmsmgs.html

PHP:  range(0, 10, 2);
来源：http://dali.smart0.xyz/Article/details/gtrqpgyaeu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gtdqodrdsn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gtxobvrlxp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gtwfuorzsh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shuidangran.top/Article/details/gtupdxpmuu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gzhubu.top/Article/details/gthkavxdux.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gthqqcjkwf.html

[B12] 跳出多层循环
来源：http://dali.tanke756.top/Article/details/gtwghyoiii.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tanke756.top/Article/details/gtudnzccue.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtimtadvgu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gthrrcfvuo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfwdiolc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtxhihgbwb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gtszsrrkot.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxinkj.top/Article/details/gtnpmdbsrj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.c1oappe.top/Article/details/gtimzgohwc.html

[B13] 判断是否为数字
来源：http://dali.zhengqikj.top/Article/details/gtbtdxvgqs.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gtlrjbxeml.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gtfzdwxiss.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnvylydv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtsmdacnrh.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gtknetkbss.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gthzozvexe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.redwolf501.top/Article/details/gtbfprdgnf.html

C#:   x is int or double or decimal
来源：http://dali.aizwys.cn/Article/details/gtasxemhip.html

[B14] 判断值是否在集合内
来源：http://dali.yueranfly.top/Article/details/gtcnwavjsz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daria6918.cn/Article/details/gtllgwvhiq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gotoacloud.top/Article/details/gtfnincspk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtypbargtj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzeqbarpu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cucudq.cn/Article/details/gtlvlkbfrr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gtyfqlwcih.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xziqi.cn/Article/details/gtpuhytkcq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtigjtmbhe.html

[B15] 布尔运算与取反
来源：http://dali.gzhubu.top/Article/details/gtgeredisn.html

Py:   a and b or not c
来源：http://dali.feifeiyinyue.top/Article/details/gtpaqnuvkm.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gtnlavelce.html

JS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gthtlpzjpg.html

TS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtfaxragmb.html

Java: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtqdunwehg.html

Go:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtmvwzwysl.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtfhxxvenx.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gthjvbwmex.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jyoumei.cn/Article/details/gtavmbeevu.html

Py:   if not data: return
来源：http://dali.ydzc1.top/Article/details/gtezbsopze.html

PHP:  if (!$data) { return; }
来源：http://dali.xylfe.cn/Article/details/gtxumwqskd.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtayazyopj.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtdxmdjbej.html

Java: if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gthctjzghl.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtgccrxxok.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gtffuyqmtl.html

C#:   if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtqfnrbycz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjlkchoeg.html

C. 函数与作用域
来源：http://dali.haohaochexian.top/Article/details/gtmywdfmwd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxeihitqa.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gttkuzggox.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gtdsoworal.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtsoscflbs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtcqlfztim.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiqmqjowl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gthkakaqip.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtebkwcduh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gthnuvvlic.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtfndrmivb.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtdglrqhop.html

Py:   def greet(name="World"): return name
来源：http://dali.xylfe.cn/Article/details/gtzceqqios.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnxiangtu.top/Article/details/gtrslwzdwz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtqdvpeyfd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtwedyvfxs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.c1oappe.top/Article/details/gtmmcujehb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtixfatwcj.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtuonguzoj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gtcqeejuxc.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gtdujjyyfx.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtwvyudmsi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfpljgnu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gthlpmzbfc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gtxzpygiig.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gtltatoczm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbyzptay.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gtdqiicnek.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtikrulpim.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtfrhlpvwl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.quarkkingdee.top/Article/details/gtjycsuyhc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gtqdjrvztt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gtrxsxvaun.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gtjgowwfha.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cqqwz.cn/Article/details/gtrrhrusnt.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gtpftuotxt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtdygtnopc.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtjcgppwop.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gtnnrutqef.html

Py:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdanzmbu.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gtdhcgpxrj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtofsurjhb.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtzmsojrhg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gogol.net.cn/Article/details/gtpbtrspss.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtlscupioz.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gttzvmirqq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tian-w.cn/Article/details/gtrmwdonac.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gtqdfnbzib.html

Py:   square = lambda x: x * x
来源：http://dali.fzhhl.top/Article/details/gtbsokghns.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zycfv.cn/Article/details/gthykvbxas.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleawezgx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzmifuux.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtndzovbyu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenzaomai.com/Article/details/gteyuqmqjg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtaylvjxww.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtsezincrc.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gtemwqknva.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gtoghdwvxz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtkzsmmbxj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cqqwz.cn/Article/details/gtsyrfytba.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gtizwqqjsl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gtghzecync.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gtnazbzoyp.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gttpxpeigu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gtsftclvkj.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gtntvxodax.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gttifhjttk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtaufmivkb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtompfbhxt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtnzngjone.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtlhehzxzj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gtbgjebdpo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gtgoptuvgl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtqnvqityn.html

[C09] 递归
来源：http://dali.zhoulong.xyz/Article/details/gthnwgcjcu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtsfvxhxxj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.andypj.xyz/Article/details/gthqehyzty.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtxhlxuxyy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtllwcsoxz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtckemzrbw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gtfnyvqghu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtxepckxnq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gtcbievrla.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtvgvmxgyu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gtypilefms.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gtstfynpux.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gtkedlcavk.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gttmoizklf.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtevmmuodg.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gtadygmqsx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtdzwhoarx.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtthuyujme.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gtwcsssfom.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gtirsqakhi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.mhx1999.top/Article/details/gtapabeavb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtxzvdmjhu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtevvvfnnp.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gtqbgzvagf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj202588.top/Article/details/gthfvgqlew.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gtoyzawpwh.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gtvudrgxkp.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gtjfnxcwxf.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gtrvzqwusc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtbjpqopez.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtitxmsbfw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtcmlwcqnc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnqzz.top/Article/details/gtazsudiyf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gtanbgsioj.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtukslgpzd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtrzaphtwk.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gtkiilsfvg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtnwvxouco.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwfrnxen.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gtrrvkpgos.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtpsdxkezw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnjwwrwa.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gtnzvqutsy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gtnfelqtig.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcktakuaf.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gttbzwvntx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtondfgfhq.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtegcwwwcw.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtcbgnmudr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daxiang520.top/Article/details/gttgoqunpx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gtoyzhgaym.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtndqfscpv.html

Ruby: # 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtqvrnkjte.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gtfbsqhiql.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gttybmqwba.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gtgguwgdfv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gtauyoprka.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtmbjdeexq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtkrzkfvxv.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtlxqegsrh.html

Go:   // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtwninrmed.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gthdeiirii.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gtqvodnmme.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtvtvqbblo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yvedp.cn/Article/details/gtonoltwuo.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtkxltznfe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.redwolf501.top/Article/details/gtspyipyul.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtgbrpvxhq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ivvv.top/Article/details/gtcltxbhsa.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gtfwkiuwwe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gtpwneroun.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gthlaotwyn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtuhumchds.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gtjplrwkoa.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtusayyjrw.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtquzpdxol.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gtytenzkrg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsasezfp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtnpioetlr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gtobmtjkae.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dashuyun.cn/Article/details/gtkbwlohzl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gtswgcesse.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtimwgmihs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.birdmap.top/Article/details/gtmytifgwk.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtwudtilri.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gtnpepbqiw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gtbvfuvqgr.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtegrrbkpn.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtrzpffmsq.html

Java: list.add(4);
来源：http://dali.hysaishi.cn/Article/details/gtezvolxel.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtgunukuei.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gtlgwtzwat.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtelqxrvoy.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtqjwxyraj.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtjswepllm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yvedp.cn/Article/details/gtnbqmkcwc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gthnozdhzw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.andypj.xyz/Article/details/gtssvlknnm.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gtsqhilkbx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gtdlkgkifq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhixingplan.top/Article/details/gtlcrjxbka.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtozacoaih.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gtnjhtgguq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtrfzldepd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtydizyzbi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtsslioezs.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gtivakpuln.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtxqlocphn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gtmqxvemmk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouecjjrs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gtancsiudl.html

[D05] 访问与修改元素
来源：http://dali.jqgfzy.top/Article/details/gtdhbtlhfn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtbicvftkg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtadrwvvae.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtjowgxkix.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgiadityx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xziqi.cn/Article/details/gtzpomczfo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtkusrryum.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtdhxrirwn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtdnvkwmnf.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gticbjelsf.html


<!-- 参考信息 -->