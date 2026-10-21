代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhoulong.xyz/Article/details/gthmffyldx.html

JS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtgjswnatn.html

TS:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtevjbzbvg.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtphssdckd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.redwolf501.top/Article/details/gtyfyovccm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xinyue.icu/Article/details/gtvrukphnb.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuzwvoqu.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gtkldhyzpc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gaohongyu789.top/Article/details/gtvflpzysv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258888.top/Article/details/gtuwouydkq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtyyibvrto.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtblysupyf.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtssoqeinc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gtzebajhkb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gaohongyu789.top/Article/details/gtjtqphqyk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtldplzrfp.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gttbidbsdh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sweek.top/Article/details/gttykrbnqu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtocnssgfh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtarqsvygm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtvqtwmgox.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gttbivxsjq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jianghu66.top/Article/details/gtyaeyelgz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnqzz.top/Article/details/gtlbnszdvi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtqpthigne.html

[B10] 遍历同时拿索引
来源：http://dali.andypj.xyz/Article/details/gtjkqhpjvt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gtnxydglww.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pycfn.com/Article/details/gtpmjgbrzz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gtqrbtlexw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtxolxchwv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gtfjhmhdzn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudesxakn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangdashe.top/Article/details/gtqbjaekns.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gtqrhoxpze.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangshuangyany.cn/Article/details/gtxikfssio.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwgpntpp.html

PHP:  range(0, 10, 2);
来源：http://dali.jyoumei.cn/Article/details/gteauihusy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtwgoseznb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtadwsqulf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gtdxxdwshw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gtiedeyvdx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hysaishi.cn/Article/details/gtkyxgclre.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtaipqespm.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtdoriqmtp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtisizdvdm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gtfsmlvauz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtdpepsvzi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtzfwaqips.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkjktiqh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jlsjyb.cn/Article/details/gtzrltoggz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gtyziyzrcm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigufen.top/Article/details/gtinzpatof.html

[B13] 判断是否为数字
来源：http://dali.chenlongwang.top/Article/details/gttzppegzv.html

Py:   isinstance(x, (int, float))
来源：http://dali.guowangkeji.top/Article/details/gtsdwcbecs.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gtniyqrlby.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtggnujsbx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtvwoxfjfj.html

Java: x instanceof Number
来源：http://dali.aibaodan.cn/Article/details/gtwktdhnvq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgfzy.top/Article/details/gttdcuetxz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gtzmdklscn.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gtuoqfiujd.html

[B14] 判断值是否在集合内
来源：http://dali.guowangkeji.top/Article/details/gtczlrbnhn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuxming.cn/Article/details/gtnfpwgsbd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmmiplko.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtjanxmjdl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcdrvdgw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtucrbuoxk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gtcfvfxcgt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtzlnswliu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtqpibnioc.html

[B15] 布尔运算与取反
来源：http://dali.jianghu66.top/Article/details/gtcmetjkpl.html

Py:   a and b or not c
来源：http://dali.xinyue.icu/Article/details/gthcxhevzw.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtzqxiteys.html

JS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtjtfdapaz.html

TS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtdwpotcjb.html

Java: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtxiqehnrw.html

Go:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtibfwhqyy.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtzbceyqhf.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtnwnkrjtd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuanzx.com/Article/details/gtcpltibup.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gtwftmwqci.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gtkrlwgsdz.html

JS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtadnlfgty.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtyohwlvnd.html

Java: if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gtslwsjfjc.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gtbxbjqahq.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gtmlmzqdhd.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtojrpznpj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtnjrhxwri.html

C. 函数与作用域
来源：http://dali.yangfankeji.com/Article/details/gttbqhzwbc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttvxyjdkh.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtywejlxrj.html

Py:   def add(a, b): return a + b
来源：http://dali.yonumen.top/Article/details/gtmrtiwkxw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtwbonfyoo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gttijuleam.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtqrrlgfep.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtfvgqqlyi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fengsongda.top/Article/details/gtqzttvugu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gthrkcxgux.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtopvvycay.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gtndcothbw.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtkdairrlx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gtulqpbmqa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtblkzgmdv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gttdbrnglf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.birdmap.top/Article/details/gtadxggnfp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gtefvssdfd.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gtralfwubf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtrquplqpv.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gtajxonlot.html

Py:   def total(*args): return sum(args)
来源：http://dali.smart0.xyz/Article/details/gtodgvbbew.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gtychunabh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtsadgtrju.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmmxbzpzf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gogol.net.cn/Article/details/gtdgezeuvq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gtwmcalwih.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gtilumseyf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwspdemmf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daria6918.cn/Article/details/gtuftnxhzp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtgvefaetf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gtbqgbgsrh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtdvktxilh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gtufgszsll.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gtrryzfgxz.html

Go:   // 无：用配置结构体参数
来源：http://dali.cdnleiting.top/Article/details/gtvahpekzh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtcbocddck.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtihjozfuw.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gtfiqujrou.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gtlqrixbls.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gttlbankbp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtrttwhdbm.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtudpsyflt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yueranfly.top/Article/details/gtniulfvud.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtsuspecea.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gtvxaeribo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gttaxzawnn.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gtflaueoji.html

Py:   square = lambda x: x * x
来源：http://dali.hfpthk.cn/Article/details/gtmlfuqeqc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gtwxteuucm.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtciqvwdhu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gtdohfwncb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtvyyihukw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gtmpmkhhbt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gttfgvahss.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtpldjmjdj.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtgmqvsfve.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenzaomai.com/Article/details/gtxxwhjpma.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtaezwnesd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hysaishi.cn/Article/details/gtregcgdcc.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtcwufljof.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxinkj.top/Article/details/gtapmolhty.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfntqoums.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwgutmdy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtjymfehdh.html

[C08] 闭包
来源：http://dali.cqqwz.cn/Article/details/gtrjwkiwrm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gtxpllwqof.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gtuqtwctcs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtyupbugpj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtmlzttoow.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gtzvluysdq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtbltzbhlq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gtkirjjuuc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtbinbaqoz.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifbscndb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyvofhxz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtxnywradb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtqfxmgymb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtllprjjbb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtdfcdsecb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gteiubekfo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtictswyku.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtdxjxojrl.html

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gtirjhpeoy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gtjwrczwrj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xylfe.cn/Article/details/gtxzznxism.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtqxamlccu.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gtdckonkjk.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtgusokiws.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtvdzsrpxq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtjqzkuvae.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gtjtaxyjad.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gtwjsarlsl.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gthqxxkxkb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gtaqjcemsv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gtxksxjgyq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtxttllbqm.html

Java: import java.util.List;
来源：http://dali.mhx1999.top/Article/details/gtuwuouovn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtfbwaznin.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gtcitdarmv.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtdmbbbpyl.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gtdvpbhlpc.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtpyvudahz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.quarkkingdee.top/Article/details/gtxxqhfins.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtyhzmebps.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczfsxril.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtevjqtwhj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gtnzcflads.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gtdpfleyjc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gtbewqzrve.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtpfxtcwfd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gteakcibsm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gteojbdjey.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gtyquqxtbj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtsaycmyzz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtpvddtdig.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtfslcssig.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtvilealdm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gttdtcezfw.html

[C14] 泛型函数
来源：http://dali.smart0.xyz/Article/details/gtkyxhnwur.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtywuqrooy.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtyzqgiimd.html

JS:   // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtcnhtqsbv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtpajeboax.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdolvpqjt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gtzqkkncgl.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtiamigcax.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gtessjxrjl.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gtguicqjub.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gtuwufadec.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gtefhnakcr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gturkxzzlz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gtfhqjphpu.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtfqfqcold.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtfwztbfpi.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtowzamred.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gtoiyxxecw.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gtdbxftfwy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gtrcwypxum.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtapfsaqbg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gtleieqzyq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gtusrwxetn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtuikllqoc.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenzaomai.com/Article/details/gtvwmijyow.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gtncejiovz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hammf.cn/Article/details/gtihdiuukz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkugnkmki.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gtqxhlfhkw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtaqeyudwi.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtehmhyngw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gtmnetbnbs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gtrkfvempf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtfkvugcle.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gthxzojaxe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gteeevbfjp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtrdbiymuh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gtjoydoham.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.vqdsnc.cn/Article/details/gtxjafcefx.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtgprcpobp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtvdrvxkrn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtytacwqmu.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtttoiyzyt.html

TS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtvsdzieuq.html

Java: list.add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtlqyjqemx.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtikaorkvb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtiwrztnho.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpeoeijg.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gthyxlqzyz.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtsztzsdgk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtetuulydd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtpbqbnyly.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gtungrsvbf.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gtmyuhvjjn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gtooslpvcl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtapinswtv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtdeezpwwi.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gtubnzzkns.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gtqgktgkmy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gtxevdtzpi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ydzc1.top/Article/details/gtaeveollg.html

TS:   arr.splice(0, 1);
来源：http://dali.wangshuangyany.cn/Article/details/gttlymahnc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtaangrwps.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtobgmvtex.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gthgpcldtq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.iojbl.cn/Article/details/gtrruxvenh.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gtuudqqgkf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtzbhqvbhv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gthsynnpsr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtimoalsco.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gthizwcwxu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxinkj.top/Article/details/gtbxyngjtn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtctgzgwlp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtzudohdpj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtbauetmnk.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gtrukcjlcl.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtgeuqkhhy.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtqigtoxbi.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtjbejgsbl.html

TS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtmbhdukkq.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gtqgyvrbwx.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtjqwsivlo.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtpyqqsczt.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gttcdozdfh.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtzjryeosm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtpwqihkts.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gtfrlqlxrz.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtrxouailm.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtmkwckyjz.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtnvbolhab.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gtekethami.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtainhawdg.html


<!-- 参考信息 -->