代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.bjfxy.top/Article/details/gtykkpagke.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xinyue.icu/Article/details/gtanypxhqd.html

[B07] while 循环
来源：http://dali.shzxlz.cn/Article/details/gtrtufaglv.html

Py:   while i < 10: i += 1
来源：http://dali.havefunace.top/Article/details/gtozjbldxm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cdnleiting.top/Article/details/gtxsnlvwjr.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtqhkqkxjt.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtfnuhfrnn.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtwxmctwrt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gthyktfgpy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkharxhoo.html

C#:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtjuycnotk.html

[B08] do-while（至少执行一次）
来源：http://dali.dashuyun.cn/Article/details/gtlsebsxdc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tian-w.cn/Article/details/gtvfzggwcq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.meibo888.top/Article/details/gturljtsqf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtniaqttgd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtjydqmmvz.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtmnagrdnr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtyttzzndb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gtdoytscuq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gthtridxej.html

[B09] break 与 continue
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzafvntui.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gttolojvdy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtsigoxtpl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtykcyyrvl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtglgsxtyx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtmxviieze.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdjrbxjg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hysaishi.cn/Article/details/gtilmuuikf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtefiaglfi.html

[B10] 遍历同时拿索引
来源：http://dali.nwbrower.top/Article/details/gtrmmbpiwe.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gtuckkqbdy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgufenzy.top/Article/details/gtjnbdmncd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtlfkzwsjy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqammooi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.316326.xyz/Article/details/gtaqksapuf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xinyue.icu/Article/details/gtqhhqeapv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gtopdrfwru.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gteckoszrv.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gtrxniadsh.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgfzy.top/Article/details/gtmdvdkibk.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gtwcdcqsit.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtrcghtahr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtqyhqbcqr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuanzx.com/Article/details/gtnenqyjsz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.iojbl.cn/Article/details/gtwqrsgcku.html

Ruby: (0...10).step(2).to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtgdtkyflq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cheryme.top/Article/details/gtdpnchsnv.html

[B12] 跳出多层循环
来源：http://dali.nanxinkj.top/Article/details/gtcpfsinqm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gtdvwfdkhe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hywenlv.cn/Article/details/gtfujjydyi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtvmwlymyn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtltxqmyhc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtxatydktk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gtyonajffe.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gtyjbdgayc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ybcxt.top/Article/details/gtfnczaugn.html

[B13] 判断是否为数字
来源：http://dali.c1oappe.top/Article/details/gthcrtpstp.html

Py:   isinstance(x, (int, float))
来源：http://dali.sysykeji.top/Article/details/gtlrwvptdx.html

PHP:  is_numeric($x)
来源：http://dali.chenjidiqi.icu/Article/details/gtampyphwu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtzhpmwxdx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gteyjhsvoh.html

Java: x instanceof Number
来源：http://dali.yanxiufei.cn/Article/details/gtfuykyjep.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxuanxn.top/Article/details/gtgbjdrsbt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gtsffblbck.html

C#:   x is int or double or decimal
来源：http://dali.jyoumei.cn/Article/details/gtmiygijcy.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrishfyur.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gtasnukvol.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ydzc1.top/Article/details/gtxqyttnnr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtpllodfxw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gthcladfap.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtheyonqhu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.svipenyu.cn/Article/details/gtytipmmrq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtmfwxbquj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtsxwazgqe.html

[B15] 布尔运算与取反
来源：http://dali.hongshengwenyu.top/Article/details/gtzvrtfhnc.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtchtkgapl.html

PHP:  $a && $b || !$c
来源：http://dali.chenjidiqi.icu/Article/details/gtquqzjvdm.html

JS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxpcllnb.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtctegzuno.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtkhticjpm.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtvymwyija.html

Ruby: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtyukxnvlz.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtzmxmwrfn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhengqikj.top/Article/details/gtsetbnvqv.html

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gtbhbcczma.html

PHP:  if (!$data) { return; }
来源：http://dali.gzhubu.top/Article/details/gtranhsurx.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyyykwor.html

TS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtwukhsqqq.html

Java: if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gttleznhey.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdvnhyhl.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gtgdjjyeyk.html

C#:   if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtehnfdnnk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnzxvftxt.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gthqhngrvo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtcljqhrtp.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtacqtjrte.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gtbrolreky.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gthgkyxfbh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtrlvywjmu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzyencto.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtmnfiqevt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gtxxqztppb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtxpeqwnru.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtklzdchrv.html

[C02] 默认参数
来源：http://dali.yvedp.cn/Article/details/gtfwmdrksu.html

Py:   def greet(name="World"): return name
来源：http://dali.sweek.top/Article/details/gtgevgzenm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtkkrjslqz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtjjkpmqrb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtysqjpvqa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenjidiqi.icu/Article/details/gtidsmjfuu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gtztjukhys.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuetiantiany.cn/Article/details/gtqbgwrsze.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gtyzeqyizs.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gtcduqkfsz.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gtrxldeexk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.316326.xyz/Article/details/gtuqjsaqzz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtkzfehvwx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtlmsudcqu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gtcxubyhuj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtmdlfaiji.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gtfnufheqj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.quarkkingdee.top/Article/details/gterqgkwho.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gtqpwoxvwl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gtayboenip.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtwcyhffeh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtiojecmhd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtmwdvzujy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangdashe.top/Article/details/gtwgihysft.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gtlpbfsmwu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtczeenuks.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtgjxljumx.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtqdvakyav.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtwafrkrna.html

PHP:  return [$a, $b];
来源：http://dali.mhx1999.top/Article/details/gtyjkhsiow.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtisgpulwx.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtiexbwspi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gtipuvinkg.html

Go:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gtgpsoskzi.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gtxabjvwfl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtqtlvpjzb.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gtufsovxdm.html

Py:   square = lambda x: x * x
来源：http://dali.zdqjudy.top/Article/details/gtntjcamwr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gtogqosdpb.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtigyqcngm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtqgmavedc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtpztmvqhf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtnwgzriss.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gtfdmbhfrz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtwinxtmhn.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gthnvnvogc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtzyljjbaw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtezkjzeyx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gtiysvfpie.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gtvljrykxn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtbmconyko.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gtjuhxvypa.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gtfvhhicyb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtvoqfuwlg.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gtopbcnyxb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gtiowrkzsn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtdzacneyc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtbfwlbqiw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsezorbxb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtxsrqcppv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gtjuvqkjpx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gtxxgfcywi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstrfotdv.html

[C09] 递归
来源：http://dali.wangshuangyany.cn/Article/details/gtprzyiddk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgvkjviu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuxming.cn/Article/details/gttwyjswhk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtbrrlqkwm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtmjjnwgaz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gtjrsduahd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gtlfijbxvf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gttomgrldc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gtrnphdhac.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gtmvebnvxh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fzhhl.top/Article/details/gtkkjtczxa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtzworyedb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.316326.xyz/Article/details/gtciaomguq.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gtktefdqjj.html

Java: 方法内为块级作用域
来源：http://dali.andypj.xyz/Article/details/gthmdfjrak.html

Go:   花括号块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtbawlnlut.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsiilsxd.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gtcrmvucsn.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gtryjufnru.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gtufcxwuuo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gtefsabsag.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtofjowlgn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.mhx1999.top/Article/details/gtifhzbger.html

Java: import java.util.List;
来源：http://dali.mhx1999.top/Article/details/gtadbmmulw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gtkycvbzmg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gtxbqpgdsz.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gtzocqujxa.html

[C12] 立即执行函数 IIFE
来源：http://dali.xylfe.cn/Article/details/gtjphqreua.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gtktpnvzzk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtlehzwtxi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkldmrvjq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbpqmwxv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gtprgextbm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gtuffjnmnh.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtkhpacncu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtmgfkwzoa.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gtjmkhleow.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gtwqxfspgp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtczwmleto.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gtihvkncrf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtuurknhno.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtxtnbdiao.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gtlkbmskfj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gtqtlgqcxt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gtedqfkfdl.html

[C14] 泛型函数
来源：http://dali.pengpengdd.cyou/Article/details/gthcgkglgo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xinyue.icu/Article/details/gtuciqhhpb.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtmejbekjg.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtvfwdrrpw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gtiojbgyek.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gtfdkgaxjd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gtpiteynwz.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtmubpdmng.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gtheyidyxz.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gtwbpxzrrp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtijumsoua.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gtbuxcxowz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtjpgkdvko.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gtllxmfoat.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtolqhyyge.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtceiwwcpr.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtbdahslif.html

C#:   var (a, b) = pair;
来源：http://dali.hnqzz.top/Article/details/gtzezdxipr.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gtikrzyxsj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gtgoxpyibl.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gtmbcknhct.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtwoyqnilq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gtsqpqtptq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtwzxbhqxf.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtxplofvsx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gtiblmgzof.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtupkhtzdw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtiwimtlaj.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gtonuhefaz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtluurejmt.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtczwxhftg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gtepjfhljn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gtddhglnqo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gtumfulihs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtxvdmtfsl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gtcyqsbrvq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gtvmucehsl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gtaxkgolna.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gtijccqeap.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gtlaujokoi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gtlgabzrgl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtgtxnehek.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtkakrbtye.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrjfkjwb.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gtitychixh.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gterjfueyv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gthugcnhka.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gtqednmylr.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gtlqfhdmyi.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtfvnajvet.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gteksadcgo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gtruepmasw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtpfljncwv.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtpksoxdau.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtafxyjvmp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gtxtfaqvek.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtbasdyteu.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtcaodvvld.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuanzx.com/Article/details/gtwstyunvi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gtmmrpfqgp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtqtqvsezr.html

TS:   arr.splice(0, 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckvafgmn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gtamwtjvub.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwraicxoy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtjesrjkfh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gtukwajcbf.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gtwdfsshla.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtozrfgqcs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtxtzgqzbg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtogbsqdcc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtmbyeilff.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gtbfhgwmdj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gttlsdtemp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtumlupakc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gttvhjkuzt.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtsqublzmx.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtfijagrzl.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtpxmgirzx.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtemhzhmcf.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtbtbaizcc.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtzvtsango.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtgfjxsylf.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gtyhwrhvgp.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtshgmyvzg.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gttoqkcqaz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gaohongyu789.top/Article/details/gtazarvmpk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtxplplsul.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtjdsugggi.html


<!-- 参考信息 -->