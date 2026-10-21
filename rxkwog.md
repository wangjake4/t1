代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aizwys.cn/Article/details/gtplsfpaan.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yonumen.top/Article/details/gtpeogpmlq.html

[B07] while 循环
来源：http://dali.zhongyouzk.top/Article/details/gtivtqvbcs.html

Py:   while i < 10: i += 1
来源：http://dali.mhx1999.top/Article/details/gtxhziizts.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nanxinkj.top/Article/details/gtlnolcxqu.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtygcuzljf.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtmnlhefiz.html

Java: while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwpgviffb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.svipenyu.cn/Article/details/gtebjzfdvj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gtdhelpbby.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtejracqql.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gtjfmznnok.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yvedp.cn/Article/details/gtkfmiikgh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xylfe.cn/Article/details/gtiwcyuchh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtwvoypzzx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gthpexyntf.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtghwyebyd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtomqsdxev.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gtfbzclnwe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtsierhpsr.html

[B09] break 与 continue
来源：http://dali.sweek.top/Article/details/gteeqjjqui.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cucudq.cn/Article/details/gtjnhdxqyf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtgxvdahkh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtfnclytwg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtgohquudw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtluhtvghj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtmsltxkoy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tianlin.xyz/Article/details/gtndqslniw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtvgfazzlw.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gtrhwbrxis.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenjidiqi.icu/Article/details/gtldnhjrbi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlgyymugv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gttiexsqif.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gtvfromwth.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jiagoushi.top/Article/details/gtklqnnnew.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gtflkohecy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gtsxpvcanu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.havefunace.top/Article/details/gtwzzmjvrh.html

[B11] 生成数字序列 / 区间
来源：http://dali.sxryk.cn/Article/details/gtihwkqdnh.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gtpryylecr.html

PHP:  range(0, 10, 2);
来源：http://dali.xuanzx.com/Article/details/gturkspkqd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gtysbofpjb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtkblvejzd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pycfn.com/Article/details/gtmifwvalw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yvedp.cn/Article/details/gtabrtlxtl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gtggbbvnkl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gtfldffokr.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqttfoyb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gttbgniqek.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gtsylxfjtg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkrzwqgp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gthzozpvjb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gthlvpfqqh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gtwpoyomiz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gtsbuoeobm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.snrcjt.cn/Article/details/gtanzdewlo.html

[B13] 判断是否为数字
来源：http://dali.sufxvd.cn/Article/details/gttnrfkhug.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gtflrdrxfe.html

PHP:  is_numeric($x)
来源：http://dali.jlsjyb.cn/Article/details/gtugirgjxb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtxkvoydby.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gtcgfptdmc.html

Java: x instanceof Number
来源：http://dali.c1oappe.top/Article/details/gthcpdnpds.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gttmdeoeai.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gtvgwlbixs.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gtopogzbds.html

[B14] 判断值是否在集合内
来源：http://dali.shangyingyoupin.top/Article/details/gtvwesfhdi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gthuholzof.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jyoumei.cn/Article/details/gtllmwvcvz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtructoyxy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtajxykvll.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtngfyrwiu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtwnbcoows.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtbuiepzag.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtlwdzkmjf.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gtlzvmzruo.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gthhryblwt.html

PHP:  $a && $b || !$c
来源：http://dali.ybcxt.top/Article/details/gtocbfzxln.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtbqoabbam.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtnoqhxtft.html

Java: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtfvkfxggt.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtjqzpnxpq.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtzgjwdoal.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtioodewkm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shuidangran.top/Article/details/gtxcjbxdgb.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gthveoxbhi.html

PHP:  if (!$data) { return; }
来源：http://dali.pycfn.com/Article/details/gtmtqrsnch.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtfdikfpdp.html

TS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gtmxjibjis.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtyafztmeh.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gtgkmvqnsp.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gtbjjnuohe.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlewxlbx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwouodbfg.html

C. 函数与作用域
来源：http://dali.daxiang520.top/Article/details/gtxsuvoopw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtpnwvboov.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtcqasveqi.html

Py:   def add(a, b): return a + b
来源：http://dali.cqqwz.cn/Article/details/gtpokjdxsr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gttogjkfnx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtglxyotmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtluefsnev.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtrrnnbgol.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gtfkkmvtwr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorwzhdou.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtajacwvgy.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpmlvcdi.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gtklbxjgjs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gttnolhjfv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtxgkctgil.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtqzjvooqm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenjidiqi.icu/Article/details/gtfjpwvjjs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gtnunyvmkk.html

Ruby: def greet(name = "World") = name
来源：http://dali.cucudq.cn/Article/details/gtmaddxghu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gtvkphyqww.html

[C03] 可变参数
来源：http://dali.dianchejie.cn/Article/details/gtdtzayzrd.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvylxxyjc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtolqemdsh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtwigqfgkn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtipaduoyj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gtqwdepupy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gtcepcheyl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gtkcztklyn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gttocljkjy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtterhrirq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gtgkrpdekw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.316326.xyz/Article/details/gtvdcwaqeu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtvfrlqfqj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jiagoushi.top/Article/details/gtzcxdxfvp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gtikaublcn.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gtulmesdrt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtcyivzegq.html

C#:   f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gtelmwvzag.html

[C05] 返回多个值
来源：http://dali.sxryk.cn/Article/details/gtnhyprbab.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtzwhbkpjw.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtxxqjtgnk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtrjtvykhi.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtoypvjdbb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gtmchjshtg.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gtbkwtfklh.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gtyhflfffr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtjznjvuxw.html

[C06] 匿名函数 / lambda
来源：http://dali.hnqzz.top/Article/details/gtdzdagzyr.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoqppbee.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gtkigdctoy.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtwizmszuj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fzhhl.top/Article/details/gtqfyivhot.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtokycbite.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtcptknoxu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gtupjitfip.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtedoypuws.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gtnwsdupiy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtxtfdutrh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtygfuxgdj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtmkysoxzp.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gtyyutckee.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gteznifohm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.redwolf501.top/Article/details/gtbdsjepep.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gtqzcnbbgd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gtxpgrzcnr.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gtbxhhrrqa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gtsqoasqvi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.svipenyu.cn/Article/details/gtkhdbviuc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtyqeoeerm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtvgnthpjr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gtqfublnco.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtskicwivj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yvedp.cn/Article/details/gtmpzskast.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwopxsuur.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gtduaujmql.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtkvfgtbzr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtgpqrqmxs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtrtsqxzxi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtbvlqqbas.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gtedzabroa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gtbpncosyt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtawcghnli.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtkepxpoxq.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gtiyayqelt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtqwvmqziy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gttektxbkz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gtudkxpije.html

TS:   同 JS
来源：http://dali.fzhhl.top/Article/details/gtxrikudmv.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gtfhpkxovp.html

Go:   花括号块级作用域
来源：http://dali.redwolf501.top/Article/details/gtpyrjcpsc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gtxpnvqang.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtikqzwnmd.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gtxhfkoido.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtehugwrsa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gtojjxpduy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gtzbwnxpax.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gtgqcafaor.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtgytbeudk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtxhjrriwu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gtkllwctxl.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gtmmmrsbtw.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoopqenz.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gtdnarpalt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtdflycrsi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtedhggrau.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtvquwhcxg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.meibo888.top/Article/details/gtbrnvjcsd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gtpvefdgzf.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gttrdqaqxa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtterjqzvj.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gtrbdoejat.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtcbtyxzpi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtvyvsjkxb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gthxsjwykc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtpeyvhhtc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtndpyaxwl.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gtfnvdsjwl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gthliwgzfe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gtdxedfrnk.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gtuflqoigx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gtogixqpfj.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gtxthdnnnf.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtrdcshleg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gtsvihvsso.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gttbwymoza.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gtfbounmsl.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtstsugelk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtnddgplje.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gtuakbvfmk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtjibrjvnq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gtoispmwfo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtmdaidkcc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gtuiwttymv.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtbckcgxin.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gthqpwejqx.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtyyoizzrl.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gtladmyswf.html

[C16] 函数 / 方法重载
来源：http://dali.aizwys.cn/Article/details/gtrmfzkvmf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gtfzuprdhh.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gtoujepsue.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugezifda.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gtwkmxgjre.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gttxdfkshm.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gtxumammnm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gtbzaavcfm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsjaankx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetqcksdd.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gtwfbnsogb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtunrcskeg.html

[D01] 创建数组 / 列表
来源：http://dali.hnqzz.top/Article/details/gtctaqkqrq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gtmroepnke.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gtwukwyyvy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtjjvpsheq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcnzszmt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtfmodbllq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gtwuorvuzq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtlrnmpzwn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gttyhfhwho.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtqgktfwwo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gtvzjtelof.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtdsvcttrw.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtmffzweuq.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtcpmkmdwv.html

Java: list.add(4);
来源：http://dali.gogol.net.cn/Article/details/gtzfhmbfku.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtiwmofwuv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gtvxbpccei.html

C#:   list.Add(4);
来源：http://dali.zhixingplan.top/Article/details/gtdrgfntqm.html

[D03] 在指定位置插入元素
来源：http://dali.jianghu66.top/Article/details/gthnfvokun.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtwtsyjpcv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtusrnlshk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtpkhpdfij.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtqcnvtakn.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmwotplw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gtjbixjena.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gtjkcfljfx.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtkiulmcjl.html

[D04] 删除元素
来源：http://dali.andypj.xyz/Article/details/gtjrxjyexf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yongpay.top/Article/details/gtwjycqvxa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtzjbmmkhu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gttbcfxbzx.html

TS:   arr.splice(0, 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtcysydzxp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtbqaknzne.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gtsoyepkpu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouadivzh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gtpsosngxd.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gttxsnbiti.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnguhuni.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtupzlafqj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtoohrjswg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gtiybsdsor.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gtfaxzhvla.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtrmmlokfb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gteazxtcjr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtiborejfk.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtblbsbblf.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtkvjhdrkr.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gtmlmzxglx.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gttmddnytc.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtqjlirjha.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gtdtbwkcao.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtbiisrncu.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gtibvgnfnc.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlreefyle.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtflcbzsxt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gtflgfmcrw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gttvfxjftf.html

JS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gthdbqwilb.html


<!-- 参考信息 -->