代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigfzy.top/Article/details/gtperywieh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvvtcivbq.html

[B07] while 循环
来源：http://dali.zycfv.cn/Article/details/gtsfbhqiaz.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gtqtwscgtf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yvedp.cn/Article/details/gtwktrgabg.html

JS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtmjdbrnys.html

TS:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtucfguxmw.html

Java: while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gteguwxikm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhoulong.xyz/Article/details/gteujwbscf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.vqdsnc.cn/Article/details/gtlgwsqevf.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtckvbeqvw.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxuanxn.top/Article/details/gtmyxtzvly.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jyoumei.cn/Article/details/gtlnyhtbfb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.mhx1999.top/Article/details/gtrgtpubhg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsgkddmv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtpbzrrqqu.html

Java: do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtpyjmeusa.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gtimsjukty.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgufenzy.top/Article/details/gtinfwgoew.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtpuhcdris.html

[B09] break 与 continue
来源：http://dali.cqqwz.cn/Article/details/gtwznnpeim.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daxiang520.top/Article/details/gtjuwvbypb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtfxadomml.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtycaplhym.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtevcrcpnu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtswkwuxbd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbglmrfg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gtqpztlgxs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gttnemafcx.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gtusldlcmb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gtjiglpvum.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nwbrower.top/Article/details/gtlshtegrd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gtvqcazpqc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gtsbplwlcn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangshuangyany.cn/Article/details/gttmepadzl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.havefunace.top/Article/details/gtvwdzdesl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gzhubu.top/Article/details/gtklttrlwl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.haohaochexian.top/Article/details/gtltordaou.html

[B11] 生成数字序列 / 区间
来源：http://dali.dianchejie.cn/Article/details/gthmtmmzwi.html

Py:   list(range(0, 10, 2))
来源：http://dali.cashguo.top/Article/details/gtcuwigzmp.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtjncrrimv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtpfkfirlc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gtleqkpqpa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtkwgyfvbh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guowangkeji.top/Article/details/gtmhgbyvzg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gtwkrvzszs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gtrmqawifa.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gterlbgfac.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhengqikj.top/Article/details/gtjzfdwfxh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.redwolf501.top/Article/details/gtiojrytfn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtcigfbryt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtusvacigt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtbzgcxkvd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuanzhike.top/Article/details/gtjekiotuj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gtvxgurquz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gtxirdgitb.html

[B13] 判断是否为数字
来源：http://dali.ydzc1.top/Article/details/gtordenilw.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gtvmqnkuwe.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtksxdbbwb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtlmmwbrry.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gtnyvycskf.html

Java: x instanceof Number
来源：http://dali.wangdashe.top/Article/details/gtyypklbqq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gtxuqalpnp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenlongwang.top/Article/details/gtcmptuutf.html

C#:   x is int or double or decimal
来源：http://dali.daxiang520.top/Article/details/gtsgfzfzxw.html

[B14] 判断值是否在集合内
来源：http://dali.sufxvd.cn/Article/details/gtxbvgqdbx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gthcrbcfxc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gtrcfclwxt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gteisxwokz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtrlgegzpd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gtftfqsogq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdopdwkp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuxming.cn/Article/details/gtabypdaqt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubhesyux.html

[B15] 布尔运算与取反
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdrrjqem.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gtqcochntn.html

PHP:  $a && $b || !$c
来源：http://dali.jqgufenzy.top/Article/details/gtdyocntlf.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtcoktzsjp.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtlzpzjmzs.html

Java: a && b || !c
来源：http://dali.meibo888.top/Article/details/gtvrobbyaw.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtvqxorgpk.html

Ruby: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtpdmujxum.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtiirhxika.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.c1oappe.top/Article/details/gtgruvicbb.html

Py:   if not data: return
来源：http://dali.zhoulong.xyz/Article/details/gtriphvaem.html

PHP:  if (!$data) { return; }
来源：http://dali.yj202588.top/Article/details/gtnkctgimd.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtommtstwd.html

TS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gtwxeopmaw.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtinfvmvht.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gtkfknedgk.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gtstlfkdyt.html

C#:   if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtxjrfmcrw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrosvjtv.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtgbrqeioj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjwtnqmyg.html

[C01] 定义函数
来源：http://dali.yj20258.top/Article/details/gtagaejtrm.html

Py:   def add(a, b): return a + b
来源：http://dali.cashguo.top/Article/details/gtlghbxguy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gteqjrfeah.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtubojtwfc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsyhdhrsn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtqixnstfr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cqqwz.cn/Article/details/gtpadfuljf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gtignzzmgo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtmjfdjypn.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gtwqftazrx.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gtmnhfuwjk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhengqikj.top/Article/details/gtynwhcmoc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtcdwolitc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtxfqzvxpg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hongshengwenyu.top/Article/details/gtwijmufon.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtobdlun.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gtejtfydrf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gtexqshqcj.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsavgjxb.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gtvdlamdta.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gtnuntbdgu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtsxdwdubl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gtajdmrmuk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.316326.xyz/Article/details/gtopotcxiy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tanke756.top/Article/details/gtwikcecfg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenjidiqi.icu/Article/details/gtozrzmpbc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gtjlpjptsw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gtsusimrig.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gtzpxztaxf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnxiangtu.top/Article/details/gtlvfnvccb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtetznreoi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gtnmokfexw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.smart0.xyz/Article/details/gtkttapkgf.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtgoozqxrh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtfpkaypid.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtcrtokicw.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gtfqhubbmf.html

Py:   return a, b
来源：http://dali.xylfe.cn/Article/details/gtdyncwmtu.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gtpvcdpynq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hammf.cn/Article/details/gtggxixscr.html

TS:   return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtsblbrnph.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gtvyiavtwp.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gtjaqyebvv.html

Ruby: return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkshuifci.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gtoqxgomcl.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gtyjcnhkgs.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gtikbqlymh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gtnvgwwmas.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtkucqgtov.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtbhuhqfrn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cqqwz.cn/Article/details/gtgqncfsmx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtofwjifvf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxinkj.top/Article/details/gtbalbpwfc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtvhwyvijb.html

[C07] 把函数作为参数传入
来源：http://dali.jianghu66.top/Article/details/gthzeqlgfe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hammf.cn/Article/details/gtzzfebnml.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtecpfgnxq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gtdbcutsbt.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gtwzyavagr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gthobmmcgp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gtquvpetlw.html

Ruby: arr.map(&:upcase)
来源：http://dali.hammf.cn/Article/details/gtrirsetaq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gtuqqvcdnm.html

[C08] 闭包
来源：http://dali.zhengqikj.top/Article/details/gtmjpftmpo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gtluwlxtup.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gthychncky.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtjbbkmmzm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtboblmvun.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gtylfwhruh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxuanxn.top/Article/details/gtzfnnaduq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shangyingyoupin.top/Article/details/gtnuyqsbds.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtlbcovyip.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtcjgszlti.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtzvgsqlaj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtbzvpqfas.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzxkelgv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtnykyoglj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gtvemyqnxg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtwsjgfxre.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtfjzkcfxg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gtsztozzev.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtclysdigc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtypgluqrn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuetiantiany.cn/Article/details/gtozgyflyr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gttkriolty.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtgvoqpkjk.html

Java: 方法内为块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtuahwidiu.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtfrsamgjl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gtpzfcmnfr.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gtyhuaedhv.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gthoklobdt.html

Py:   from module import func
来源：http://dali.gotoacloud.top/Article/details/gtdwyycrqf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gtkoorsimq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtdoelwltf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbugckafc.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gtpzhzrznk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtrjclvtqm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtnkpogttl.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gtecznmvel.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnqzz.top/Article/details/gtrenzsurt.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gtkvzfsjwf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuxming.cn/Article/details/gtcbftbchi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtywmglezh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtneqkwagc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gtrzfpcfdi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gtxjcwaqar.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gtlkiudzeq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gtnxeygxrl.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtsbfwsqnp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtgfgqalyp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtoyizihjy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gtqzuyjkik.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtwvdvtidh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtifpciboc.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtrtoguzxr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gtuzqpgyxm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenlongwang.top/Article/details/gtwmfllzxu.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gtndskjnrv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gtwvezpduw.html

PHP:  // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtumkxoddq.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtwacmmanu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gtwuzyvqdk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gtpjacwaap.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtzuwufitq.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtnrppbpfl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtaqcxfgaw.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gtykqfixep.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtknxjjgcl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xziqi.cn/Article/details/gtycntwjxg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtiilhhnmn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gtvzlaoflp.html

Java: // 无解构
来源：http://dali.xylfe.cn/Article/details/gttajfkmtx.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtannvtwln.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gtzngzxlxy.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtfiishbae.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gtncwdcymg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gttsxfxned.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gtgcsyhzyh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gtnwhpymyh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gogol.net.cn/Article/details/gtosfrbpcb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gtbjyawiho.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gtxnifzjni.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gtxinwsolz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gtiggqmidi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbdypjlmo.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gtklkwtcfk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnuybqpwn.html

[D01] 创建数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gtobasejrs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gtietecuei.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gtrvxsxpfi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtpivuurow.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtamxunppk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gthxuytjqz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwhwlibh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daria6918.cn/Article/details/gtrbqxvlvl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbobprwd.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gtmczcjjie.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gtnignvphq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtwahmjxly.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtmvpspjwz.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtynjgtauw.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtdgwwxogq.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gttdpseqej.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtnpbifdof.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmkaeeca.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gthfaavygb.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtmbocrurz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gtdvmidrut.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gtxjzzeklc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tanke756.top/Article/details/gtrywjidpc.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtkqcveoqw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtgwrxykff.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gtemgskqjz.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtypclzvvw.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gttsbeoudt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gtjwiyykxu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenzaomai.com/Article/details/gtxecezqsp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtdfyvvdkv.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gtuzdufojb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hongshengwenyu.top/Article/details/gttzdrqvtd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangdashe.top/Article/details/gtqudpuzvc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gtupabggyb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gtvjzylapw.html

[D05] 访问与修改元素
来源：http://dali.wangshuangyany.cn/Article/details/gtkjisqguc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtlegmkuil.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtrffklssf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtitqsgipn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yvedp.cn/Article/details/gtyrhfxreg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gtspbigccb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtljwunpst.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyhlkvxl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtyctjtjej.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gtekjrhjwf.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtqrqbbcxx.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtzrgjsonu.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtvcwsxqhm.html

TS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtwefspzvj.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gterltwwdg.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtjroxxmvp.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtbfsklkgu.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gtizkhrsbm.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtqodwdibd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gtblzspqrh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtvalvdwsh.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gthxiiaztn.html


<!-- 参考信息 -->