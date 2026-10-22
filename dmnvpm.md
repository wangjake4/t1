代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sxryk.cn/Article/details/gteghbgpke.html

JS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtzpbhahli.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtlquqvejp.html

Java: while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtapnifkvm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuanzx.com/Article/details/gtyhtkgvbn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shangyingyoupin.top/Article/details/gtbyshixup.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtolrvaeqb.html

[B08] do-while（至少执行一次）
来源：http://dali.nwbrower.top/Article/details/gtlztrpfop.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhcxiydw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtptktqoow.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdnjbxrd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtmswvsfla.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtphejadct.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gttujeugvz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.9152youxi.cn/Article/details/gtitqyjshn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtwuejfgnv.html

[B09] break 与 continue
来源：http://dali.316326.xyz/Article/details/gtzfchqvht.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.feifeiyinyue.top/Article/details/gtrlfjnmas.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtugdjierb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtpuixtpac.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtfdqvvtvw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtipflfgsb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gtixovwevb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cucudq.cn/Article/details/gtfryhtlto.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtiskwfztp.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gtmcdzdmru.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gaohongyu789.top/Article/details/gtacvftgwi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.c1oappe.top/Article/details/gtxbdhcgjm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gtnppuxyek.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gtkpebjxsi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgufenzy.top/Article/details/gtvhzyapyv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgufenzy.top/Article/details/gtaxuyadnr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ybcxt.top/Article/details/gthpbbwogn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sufxvd.cn/Article/details/gtnzudinkj.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigufen.top/Article/details/gtuihddxtw.html

Py:   list(range(0, 10, 2))
来源：http://dali.bjfxy.top/Article/details/gtguanbyrw.html

PHP:  range(0, 10, 2);
来源：http://dali.zhixingplan.top/Article/details/gthxiavlth.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtshaseqqf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtkegfhsjo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gtbagccels.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gtubyrfhkr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gtgtjimyji.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gtzkzfjrla.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gtrcagwgyq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ybcxt.top/Article/details/gtxnxmxhzb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gtttcymvng.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtallolhgo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtpslfeoow.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gttwqwwkgq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ybcxt.top/Article/details/gtqygoodlr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pycfn.com/Article/details/gtsgcsdwul.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gtgcoyzttd.html

[B13] 判断是否为数字
来源：http://dali.yonumen.top/Article/details/gtuijwobbb.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtziottqvj.html

PHP:  is_numeric($x)
来源：http://dali.jqgfzy.top/Article/details/gtimxgnglv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtqomhbpoz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtsnemndrr.html

Java: x instanceof Number
来源：http://dali.feifeiyinyue.top/Article/details/gtafxxdplm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258.top/Article/details/gtcwvecuif.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shuidangran.top/Article/details/gtwyivyfbl.html

C#:   x is int or double or decimal
来源：http://dali.shuidangran.top/Article/details/gtyxlfmehs.html

[B14] 判断值是否在集合内
来源：http://dali.yuanzhike.top/Article/details/gtyhmwamlm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nwbrower.top/Article/details/gthdksemdp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yongpay.top/Article/details/gtrreqevsd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtoocasegm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtjpwtksbq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtpkptpglp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tianlin.xyz/Article/details/gtuxzalxgw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.bjfxy.top/Article/details/gtorvktdou.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtvocwsssb.html

[B15] 布尔运算与取反
来源：http://dali.sufxvd.cn/Article/details/gtxgasamle.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gttzoxjwzt.html

PHP:  $a && $b || !$c
来源：http://dali.svipenyu.cn/Article/details/gtondinxvb.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtkqedbqjo.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtobpvbarx.html

Java: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gthksmfmyg.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtkmgsdawr.html

Ruby: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtzshdsbof.html

C#:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtqxyotlja.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtcmvfiflo.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gtabyljvgf.html

PHP:  if (!$data) { return; }
来源：http://dali.aizwys.cn/Article/details/gtosjphlth.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtmuhukyah.html

TS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtjskabbyn.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtjoidfdsz.html

Go:   if data == nil { return }
来源：http://dali.andypj.xyz/Article/details/gtrccinngf.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gthxapapij.html

C#:   if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtelyikbmu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqhrnkcjf.html

C. 函数与作用域
来源：http://dali.zhengqikj.top/Article/details/gtqlzfoqgq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpkuuvgof.html

[C01] 定义函数
来源：http://dali.yj20258.top/Article/details/gtsembmwim.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gtuavrfozs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtspbovimu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtnkcdrhrc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtsdpbfmrg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtkdmjbgix.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gtpoxvcaep.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtmccmqnbw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrudpqneq.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gtetlbvjwb.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtqrcvvfsy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gtwgmvqnte.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtwzhyyovt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtvoofifsd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dianchejie.cn/Article/details/gtijfrodfq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtupbkvvlr.html

Ruby: def greet(name = "World") = name
来源：http://dali.aizwys.cn/Article/details/gtzwtsxegs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqycpurt.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gtnlybidff.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtqzjhlgbs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtrlfgjvkb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtfdyagbfo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtjsrddndw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shzxlz.cn/Article/details/gtchmtjazl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gtfvgckfps.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gtbgvobclm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gtbkcdypao.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gtelvjeeos.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gtjpwmfzoi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtirnptqca.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gttbbmyfye.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gtpbpnjpqj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangshuangyany.cn/Article/details/gtyliluakq.html

Go:   // 无：用配置结构体参数
来源：http://dali.yvedp.cn/Article/details/gtbjqvzbkp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtvpgbvzur.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtfhtxzuvg.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gtchuqwedq.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gthfolecdx.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gtklvuxafy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtmqqpnlul.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtkwzbhlgt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtpowgortb.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gthuwjtpsa.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gtzncevllg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gttyquffuc.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gtuktapcjb.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gttfeejcki.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fengsongda.top/Article/details/gthgdnbgid.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtrergxiid.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmanzeqx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gthuhqcsyh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyerrfgku.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gtrozicrlh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtvkpstugg.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gtfhahhtnc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gtdwlfhzwg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtxvbrmlwk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gtygrxxhji.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gthnlnbnqr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yangfankeji.com/Article/details/gtgsotzqij.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtekuqjenk.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gtrvsofafl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gtsvqxzhhs.html

[C08] 闭包
来源：http://dali.hammf.cn/Article/details/gttojywmdc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gtflrmtsfr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gtpnrdyyux.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtlygzamam.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtmcjzychi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gtvzoblrsv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtsqfmetzr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gthjjhaigj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtbvmoosyn.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gttbeesaec.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtbayykjfx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gtraxjhjlg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvvcfzel.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtkonnspur.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwemrqua.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gtrfpxuvvc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtalmipywh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gtwyodrcqg.html

[C10] 变量作用域
来源：http://dali.hammf.cn/Article/details/gtmoxfbiio.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shuidangran.top/Article/details/gtnopasown.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yangfankeji.com/Article/details/gtrlfzunte.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.svipenyu.cn/Article/details/gtmagvgyto.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtqjywjcav.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfupwlgij.html

Go:   花括号块级作用域
来源：http://dali.ivvv.top/Article/details/gtmmfnaayo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gtdmikdxno.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtajstfzvg.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gttupdrmbu.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gtgjkkfigf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gtnjtalzwe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtuztrmzmm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhixingplan.top/Article/details/gtorzlxawi.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gtxlfuqwns.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gthloseput.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gthfhsnzua.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gtbbibpird.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gtjyextpdi.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gtkqmxqmef.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gtyjpmisyq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtidwppagl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtfyedvpqu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jianghu66.top/Article/details/gtmyydnvpf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gtacstasxz.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gtqyjzreul.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gtwfqphodw.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtjmojifxm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gttfgzcoaf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtzdbzdnbj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ydzc1.top/Article/details/gtzmsoahyd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtisqwvpfw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtpwwndhwz.html

Go:   func add(a, b int) int
来源：http://dali.yangfankeji.com/Article/details/gtwoprnaih.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gtxrnvaawm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtjjwpvqgs.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gtomyvzzde.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gogol.net.cn/Article/details/gtlzicmhne.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtsmpkeqem.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtvxylpset.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gtsjgzkixu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gtzeusilsj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gtliimvklr.html

Ruby: # 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtrgnpqdxs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gtjneqixob.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gthikhvdbu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gtdlbokqvm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtqvdqmc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtsyuvpflq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gtrkciwfyq.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gtwvgcsbrq.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtamnokrgu.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnhnpvav.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsohafknl.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gtgencvofd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gturqjwqwx.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gtvbaflmyn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gthjybhjwc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenjidiqi.icu/Article/details/gtacfhxzap.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtwcfgqmqu.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gtpgnddxxv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gtqvivtlho.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtddunlmhw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtclmuyrus.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gtdwbkvbit.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmwoflsrh.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gttotkfibv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gthvjelfkh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxeongai.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hammf.cn/Article/details/gtsevhlbgn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gtyvemkhdv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtqpxuwjpr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gtvhnakrjg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gtdcircrkl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gtvhfzibng.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gtwynkoimx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtcdmdmrnj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gtfybcxnap.html

JS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtqkvzadwf.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtfchqajcb.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtwmiysiqb.html

Go:   arr = append(arr, 4)
来源：http://dali.yonumen.top/Article/details/gtcfxadvuv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtzfarommk.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gtuywuauaz.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtizjhgtrq.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtepmdhjho.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuanzhike.top/Article/details/gtyyhqzqyt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gturzrkcmf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gttplidpqk.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtjkxbtydj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtqjwuqyek.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gtegmotnfd.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtooifaptd.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gtvryeqcvg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gtkvyzwrpj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guannengcc.top/Article/details/gtzctkagih.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtzkfidagi.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gtzedwztfn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gtltrwyllh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gtrblmdhka.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gtdyuqvzxa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gtarltpkyh.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gtclemuqwv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gthhzjqxlv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpkftcie.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtvjqkbkei.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gtfvrerswc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zdqjudy.top/Article/details/gtdzkboial.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtvjednrwg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtouzjetoy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gttsfbuvzk.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gtblmkwnzz.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgxgoupz.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtpcqyyudx.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtyhnbffsm.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtdvcogaip.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtuhfaispd.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtbguwhxzs.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gtjxskcvcp.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtksijrftg.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gthbskvwmv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gttmvzwcdv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gthlvxlonn.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtmhggskjh.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtjevqlhey.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtpmiicwjq.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gtzwokokts.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtfwxguqmy.html


<!-- 参考信息 -->