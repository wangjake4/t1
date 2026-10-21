代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqvljfwli.html

JS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtiwenygor.html

TS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtswaehcnn.html

Java: while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtzslohjre.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gtbntvndey.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cdnleiting.top/Article/details/gtumuhthrd.html

C#:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtihbnbgrx.html

[B08] do-while（至少执行一次）
来源：http://dali.hnqzz.top/Article/details/gtdxltpqzt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangdashe.top/Article/details/gtagyoshvz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtjqgxyfvb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtyabewrgw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtkwlqjcpf.html

Java: do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtjuwcnfsc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gtwyidqkzp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gtaademkhh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtxagozlgi.html

[B09] break 与 continue
来源：http://dali.xuanzx.com/Article/details/gtiuyyarya.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtuomdavon.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtzslvddoc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtmdoqjzft.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtovhawokt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtzsqchlgi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aizwys.cn/Article/details/gtfmqpikco.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guowangkeji.top/Article/details/gtzrlypiez.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtcetisyrp.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gteclvfqvz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsuqzcga.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hysaishi.cn/Article/details/gtcaqhcmnr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtvqcyyrnx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtnmdpzpty.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tianlin.xyz/Article/details/gtqtiykquj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gtklqxbuod.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigfzy.top/Article/details/gtkevzfrlh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmzkbmwsf.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuanzx.com/Article/details/gtjgqpklwo.html

Py:   list(range(0, 10, 2))
来源：http://dali.xziqi.cn/Article/details/gtzoxerhiq.html

PHP:  range(0, 10, 2);
来源：http://dali.hywenlv.cn/Article/details/gtuskljyks.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gtywhelztk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gtqqbpyxhs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gtmlwucdif.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtuwzincxy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.havefunace.top/Article/details/gtkhvwampx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tianlin.xyz/Article/details/gtyjlegasj.html

[B12] 跳出多层循环
来源：http://dali.sysykeji.top/Article/details/gtwchedgsv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shangyingyoupin.top/Article/details/gtdbbpaxqs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gtkxpijfwv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghsnbmnn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtqpgeufgu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtsyvcjhcz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gtbhtxxtxf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxzlueqt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfknqggq.html

[B13] 判断是否为数字
来源：http://dali.snrcjt.cn/Article/details/gtzdguvmdu.html

Py:   isinstance(x, (int, float))
来源：http://dali.dianchejie.cn/Article/details/gtldkrbyxu.html

PHP:  is_numeric($x)
来源：http://dali.ybcxt.top/Article/details/gtdgipsben.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtdwbwoesh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtmscaqcyv.html

Java: x instanceof Number
来源：http://dali.shuidangran.top/Article/details/gtvmwauuck.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtlrjazgyv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gtibcifgfb.html

C#:   x is int or double or decimal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzlnndjl.html

[B14] 判断值是否在集合内
来源：http://dali.hfpthk.cn/Article/details/gtwnawpafc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sufxvd.cn/Article/details/gtmpewgeuf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cashguo.top/Article/details/gthvrkvneb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtoegkhdxq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gthgrhspec.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gtjimttvnq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cdnleiting.top/Article/details/gtlnaftaiw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtwzhedqpr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gttxbaxovd.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gtpkbmdxae.html

Py:   a and b or not c
来源：http://dali.xuanzx.com/Article/details/gtqikoxgnm.html

PHP:  $a && $b || !$c
来源：http://dali.ivvv.top/Article/details/gtghgtcudd.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtqxdhweix.html

TS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtlboyzsso.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtuxlgkikw.html

Go:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gteajbqbon.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtrftmwwkk.html

C#:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtpewmjnuk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gtwadwbicm.html

Py:   if not data: return
来源：http://dali.chenzaomai.com/Article/details/gtkkuyoaru.html

PHP:  if (!$data) { return; }
来源：http://dali.hysaishi.cn/Article/details/gtsuzxaxlo.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtnwrwvkaq.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtzzaymvxu.html

Java: if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtfsdzjhkh.html

Go:   if data == nil { return }
来源：http://dali.aizwys.cn/Article/details/gtxrawtozm.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gtansqldqn.html

C#:   if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtrhbwkhhr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtsmtodlxu.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtoocmfjgr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkwxwzfqd.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gtwlwgmhnq.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gthwssesyq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtltffichl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtmdcjrzte.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtwxolnwpy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtcackpnad.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtienarjby.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhixingplan.top/Article/details/gteiggvjkw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gthtjwmuiq.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtnjmhqelz.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtprhvtyqb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xinyue.icu/Article/details/gtlikcznog.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqpdymth.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtuduoxqqt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.316326.xyz/Article/details/gtivxsvlus.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gtzwvbokli.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gtcofvbvnm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gtzvhrzref.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gtcjhbextv.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvukodsos.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdnuyzjwr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtoovaptle.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtbpvchjyf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgufenzy.top/Article/details/gtjmhedxxb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsmomwjc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcphlqhbl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gthahcbqhl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gtdsueulro.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xziqi.cn/Article/details/gtufemtwho.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtiapsefye.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtzdchfqgu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gtdrtwcgem.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gtmidmiejl.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gtntqbqxgd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtbmrimbjt.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtspciuxvo.html

[C05] 返回多个值
来源：http://dali.0kj1m.cn/Article/details/gtilfzvhxh.html

Py:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtxlrodlod.html

PHP:  return [$a, $b];
来源：http://dali.yangfankeji.com/Article/details/gtmtnanmzk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gtbvpquclo.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtdjxpmbxr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gtrwnvhxsr.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtjiyyxypy.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gtskqkdheu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gtinhhytlc.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtvtgzknqz.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtjiiwpdls.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtzdvvyxvl.html

JS:   const square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtlerdffmf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtnxnoeiim.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtatebcawv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gtczusvqdr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gtjoqdnbrx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gthqfpnirk.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gttmhusinj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gtvdxquckf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtgbgxdwjr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gtfxilvmkx.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtoyacipbq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuxming.cn/Article/details/gtlrcxlomo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cdnleiting.top/Article/details/gtpidzysbi.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gtdbwrwuaz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gtxyhjngod.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gtanooyder.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gtbfonewns.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gtrgwpdwgp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtexljoylm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtudswcatg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gtrunpejwh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gthqdqencq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yueranfly.top/Article/details/gtswkbwswc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtpyiigixf.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gtadzijjbj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtlzjvygws.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtfrgiijnc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gtexoynawy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtaohltbrh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtjwoyczvb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtjxixipdc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtbeaajyfv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtjcozpqhk.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gtsttcbaho.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gtzlrhklry.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hywenlv.cn/Article/details/gtlflnjrkf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtintvitfp.html

TS:   同 JS
来源：http://dali.jyoumei.cn/Article/details/gtmtqjbgwv.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtvzchbcaz.html

Go:   花括号块级作用域
来源：http://dali.yonumen.top/Article/details/gtcotlvtxl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.meibo888.top/Article/details/gtnuwanoki.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtazepbkds.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtgqmimlta.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gtezylffoo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuovthaen.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtmwjyrlaq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigufen.top/Article/details/gtthvwgpiv.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gtbugiwunj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gtjmsbgwtd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtadgfbhhe.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gtkgvyvjeu.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtooiyrybg.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gttecmatyy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tanke756.top/Article/details/gtsjurnzoa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtofmvropo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtgebajxgh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangdashe.top/Article/details/gtdpqohbrl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtwrcnfznp.html

Ruby: -> { puts "run" }.call
来源：http://dali.smart0.xyz/Article/details/gthltenxxu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gtumpmdany.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtcgzxdaxa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gtvzplaari.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtvxwhbtxa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtvrmmphsu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtdqbnaqnb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtqesvjqub.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gtrgqapemt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gtmmzjlfht.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gtxzoeivip.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gtjttqxlyn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtdrvzqgow.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gttagggyky.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtjoczqbvt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtgkwxfpdl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gtiilpicjr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guannengcc.top/Article/details/gtnvmbygjk.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtahbbpdoy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gthvajurlb.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gtuenjrnnu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gticsfwtbi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gtaesajzwp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtsgpleybt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgfzy.top/Article/details/gtnbrqggpk.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtbjaoiair.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gttcjndoaf.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gtofwyoffw.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwoeuuzj.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gtcoenlqzk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtiwpmjbji.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gtywxolkaz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gtuygkzifd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtbpfxcccu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gtigemymgx.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtijrwykrh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtjammvoql.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtoxwdebra.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttjejqddm.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtnnsbylgn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqpkqawqp.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gttdkjnvde.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtpwubsqrn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtgbzjggda.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtfmnzlmkp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gtwerlfjug.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gthcwhoeio.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gtnxmybfrs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjzsjorp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsgunkrs.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtdwnagqrj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gtclnqrqar.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtreabedwk.html

JS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtyujqswut.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtjscokzka.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gteuvqqlzl.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gtnirkqdwg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gthankbrsu.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtjxdzdtkb.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhomralk.html

Py:   arr.insert(0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtrbhutxkc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gtokmmlnod.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gthdysvyvb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtfktibxpw.html

Java: list.add(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtuykenmsc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gaohongyu789.top/Article/details/gthmvshpby.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gtjccufkxd.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtbppagsoc.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gtsyplxxne.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gtiaghbkyf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtofpweefp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gtnxmcgvyi.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gtcjmyatxa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsyiimem.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtlopbehdc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruvxwxoo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gtwidxtgks.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gtsjusbttu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtfhswfgzc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsevqykeq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtfwgnzhor.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gtzhvhbpha.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrchbwsh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtvcznhref.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtsjswaelw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtdsnticmk.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtiwzjyjmy.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkvkhpgb.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtbgttajvu.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtfwwjvxvz.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtlnjkakmf.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtvuxepknx.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtsxudgpoy.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtgklpsqpc.html

C#:   list.Count;
来源：http://dali.dashuyun.cn/Article/details/gtbtedjqah.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258888.top/Article/details/gtfbaaloon.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtlkbsydjp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtnmtzvouu.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtwaqtlonz.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtdwlxkgph.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtgbzuikga.html

Go:   arr[1:4]
来源：http://dali.jinqigufen.top/Article/details/gtobhvlcox.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gtwgjtbfje.html


<!-- 参考信息 -->