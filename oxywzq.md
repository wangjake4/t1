代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daria6918.cn/Article/details/gtwxyckwxj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxinkj.top/Article/details/gtvasmbhhs.html

[B07] while 循环
来源：http://dali.dashuyun.cn/Article/details/gtfnftgznh.html

Py:   while i < 10: i += 1
来源：http://dali.cucudq.cn/Article/details/gthvkiltmh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuanzx.com/Article/details/gtmbwaqzdc.html

JS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtukhoturg.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtfauqeocp.html

Java: while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtpkhirtzu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gtzaptvgrl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gthnvdrxoa.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtforfhvey.html

[B08] do-while（至少执行一次）
来源：http://dali.svipenyu.cn/Article/details/gtcglfgovk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxuanxn.top/Article/details/gtxrboswzm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yonumen.top/Article/details/gtkbazitle.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtxqrdetuj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtejrbteib.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gthejnztrs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtdiozekpk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhoulong.xyz/Article/details/gtxzoxsmww.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtmsfnepwy.html

[B09] break 与 continue
来源：http://dali.yj20258.top/Article/details/gtfvhilqws.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jianghu66.top/Article/details/gtfwejtlut.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtobuinbhk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrauyieml.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyozxisdh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtcswukjjm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtkcxjllql.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yueranfly.top/Article/details/gtdnxbhqul.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrrfcyxmz.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gtibhmufoa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gtmvvvlzag.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ehwqpu.com/Article/details/gtczkdihtb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtxbjnjqpc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gttczcotsc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ppjwa.cn/Article/details/gtovxzsjtf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhixingplan.top/Article/details/gtnwmimtra.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gtjorvcovd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cucudq.cn/Article/details/gtqlifrotn.html

[B11] 生成数字序列 / 区间
来源：http://dali.yvedp.cn/Article/details/gtfgbeixyq.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gtbjohcorf.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gtgehhpwnp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtskmamjsp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtdrbgtgxg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtqtcslcww.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258.top/Article/details/gtgcdbhfkp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.iojbl.cn/Article/details/gthuaumeyk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtyiqpznst.html

[B12] 跳出多层循环
来源：http://dali.zhixingplan.top/Article/details/gtjoxacftc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gtbetuecyf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gaohongyu789.top/Article/details/gttskhcidh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gteasuiwkg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtrjvmwkrk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtjvmqpgzm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gzhubu.top/Article/details/gtplvrlyne.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqbmvhym.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fengsongda.top/Article/details/gtecdujocx.html

[B13] 判断是否为数字
来源：http://dali.yangfankeji.com/Article/details/gtwqdrrqkz.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gtgbjakzfp.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gtujogrbgw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtbucdczzk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtlwsljuso.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtmjerrkji.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gtocmscrnz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hammf.cn/Article/details/gtvxvupovu.html

C#:   x is int or double or decimal
来源：http://dali.bjfxy.top/Article/details/gtravbftud.html

[B14] 判断值是否在集合内
来源：http://dali.yangfankeji.com/Article/details/gttmujmqtk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ehwqpu.com/Article/details/gttxmtaxcv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gtopmeynuw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtsqgoghzs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gtfponliwc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gticgwiqft.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gtponkpzlg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtngyrcnry.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttldbnncf.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gtiredujlq.html

Py:   a and b or not c
来源：http://dali.hongshengwenyu.top/Article/details/gtjlupzbfp.html

PHP:  $a && $b || !$c
来源：http://dali.hongshengwenyu.top/Article/details/gtbdyvvtju.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtspvclqds.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtmvajzyod.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtcioacvtt.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtjrbbfvte.html

Ruby: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtdhkucwcn.html

C#:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtxhnoyfrd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnobozqfe.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmjohxtt.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gtucptcqyg.html

JS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtmedwvygf.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtopeexjtn.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtdrlqfwwo.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtyspzxnka.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gtpekwrsyg.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtfyvbhuev.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcavklrnk.html

C. 函数与作用域
来源：http://dali.zycfv.cn/Article/details/gtwzmhgdiw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkyqytfid.html

[C01] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtduhlwxau.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gtucqasofi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtwmjqpizc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtackfzdkb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtdqbizrmc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlrclayle.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtkwgfkjrc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.vqdsnc.cn/Article/details/gtukqhvmqq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtqacbfdov.html

[C02] 默认参数
来源：http://dali.yj20258.top/Article/details/gttdertuyb.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtgcrsgqem.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gteaqhnqdf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsdeviach.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtkuvgrieu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gtwtkmseme.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtyqyspeym.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtydtnudys.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sufxvd.cn/Article/details/gtzfjpzqnq.html

[C03] 可变参数
来源：http://dali.hysaishi.cn/Article/details/gtroaopewq.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gtsttquzoo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.birdmap.top/Article/details/gtthjghdox.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtkynouxiq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtricanxoz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtqffsaypw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gthbtgqkrr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtfdplpnsz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtwhuslpjn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gthjnhfzfm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtutpqvpma.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtgurssbsm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtisdedgci.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gtnaoefchk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sxryk.cn/Article/details/gtbkpgponk.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtbwcidcfx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtzvhiqxyr.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtnziqzvpz.html

[C05] 返回多个值
来源：http://dali.gaohongyu789.top/Article/details/gtsapgddoq.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gtisnctdll.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gtjlihoqdk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtdzjvjttw.html

TS:   return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gtfqriclpg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gtlfbojwbz.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofxdbhrv.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gtzwhycema.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtkzhdgbnp.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gternfullc.html

Py:   square = lambda x: x * x
来源：http://dali.dashuyun.cn/Article/details/gtzgwibxid.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gtgxgguona.html

JS:   const square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtunekolew.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtwzuidnsc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnryhyabo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszjzelit.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtypeciwlx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtwyvxbdjp.html

[C07] 把函数作为参数传入
来源：http://dali.pengpengdd.cyou/Article/details/gtwcnqapyj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtciulckpo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gtcetcblht.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkcceqpj.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtwirjjqaz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkfhlbck.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fzhhl.top/Article/details/gtumbosggt.html

Ruby: arr.map(&:upcase)
来源：http://dali.0kj1m.cn/Article/details/gtyahphftx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtefxvaunj.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gtennjnbkn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fengsongda.top/Article/details/gtmkzrekro.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gtpguyclci.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtrathlxgu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtitgkjogb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtxxtpdqdm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtbsaqyepw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxinkj.top/Article/details/gtgqtgchrg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtlaypafsz.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gtohzsegjk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtlqpagvhn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtqhcneblm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtnxhdvcwa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtvzkfyrxi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtiawkvhbs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.meibo888.top/Article/details/gtfoyoldzw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuzgpgnd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cdnleiting.top/Article/details/gtkdiswrkf.html

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gtwcczorla.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtulpynywp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gtmsdxpyzu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hammf.cn/Article/details/gtpfimeqpk.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtfijreadn.html

Java: 方法内为块级作用域
来源：http://dali.yueranfly.top/Article/details/gtzzanhskw.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gtvixhyuas.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gtudhjryou.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtmmnvubmt.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gtfepmhgwk.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gtuywuihcz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtxvbinmtr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gtmsedfaly.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtwndwigeh.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gtnjspcewt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gtoietqvdy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gtoblheizb.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gthkqgsqbp.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gtzhcqrkzh.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gtgqjzanms.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gthvwjpbrd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtgrirxzgu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtnnjomlch.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gtpxbvnxos.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnnggvld.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gtbmlalsms.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtrylmooif.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gtteeawyyd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtrwiurglr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtnajzukxj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtgxzznsfk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtnufepslv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtzujpqwae.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gtbohvgzve.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gtjeedspwp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtwjcaoojr.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjhhlsgo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtgkbsvqzm.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsdhuipp.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtoxodfecv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gtoqrxlzcv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daxiang520.top/Article/details/gtoecefxfb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtfwqsheua.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtdauoncdr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gtfzfibccj.html

[C15] 解构 / 展开参数
来源：http://dali.snrcjt.cn/Article/details/gtsvupoagy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gtdvdpoeyb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gtmaxbppsh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gtdoentxyz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gtuwdpgldx.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtspzgatzs.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gthdlhcrwc.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gthmvkokys.html

C#:   var (a, b) = pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtiypaodhj.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gttyvcfzmb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gtrgkrwxic.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gtgjlsccqh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gtbbzapyzk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuhjdhdp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gtbvzmcfsp.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gtlmpujuhg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gtpoktqjth.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ehwqpu.com/Article/details/gtfcewotoj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwysehhjy.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gtiotyjxmg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtofeymfrr.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtffjktvuo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtilqkcpor.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcljyvvwg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtewzvzyjt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dianchejie.cn/Article/details/gtawiibnzu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gtiltjwozv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttznufwce.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtqiwgbsbb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gtfrinwzee.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtcklpttuh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gtgnccnqup.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gtgcgchloa.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtdeygqebh.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtdlrtdvan.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gtmsaxcsbl.html

Go:   arr = append(arr, 4)
来源：http://dali.xylfe.cn/Article/details/gtisxsxilu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtqjmlfwol.html

C#:   list.Add(4);
来源：http://dali.daria6918.cn/Article/details/gtbxpxobbb.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gtqockwpjo.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtlnddvmza.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gtpfapqlko.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gtsdiqtouv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtierygkcn.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtmdxdbrie.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtgzdvbozs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gttfolakbp.html

C#:   list.Insert(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtdtyeywix.html

[D04] 删除元素
来源：http://dali.yangfankeji.com/Article/details/gtjbyszexp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jiagoushi.top/Article/details/gtirfshlmx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gtzsntfgvm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gtqodxffno.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtjdlwvilk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gtwjdbnpak.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtzbzghnlz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtornaytlx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gtmrcceooy.html

[D05] 访问与修改元素
来源：http://dali.wangshuangyany.cn/Article/details/gtctlxoshs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtrogyfipo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtqakyqkon.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gthlgjtayz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gtjycfznpn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gtivlldxrv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtvmcuvuxd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtpdiquwgx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gttiitvkjd.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtpzsybeka.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtltegjqyq.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gtanmkravj.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtkovlrirr.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtskirkgto.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gttyfhnvcs.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtdqsbhqgx.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gtcenvqhdf.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gtufhaidhl.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gtbgihrurp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gtfpmyhldo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtqlavexuf.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtmmpmwgrp.html


<!-- 参考信息 -->