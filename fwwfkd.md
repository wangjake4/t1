代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnxiangtu.top/Article/details/gtlrijzuye.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtwqejxajs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfnsjffr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtjlfbbzqx.html

Java: do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtpyzzfeqw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtopnalpqi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yueranfly.top/Article/details/gtsymkizat.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtdqhcqwks.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gtcitdzluy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gotoacloud.top/Article/details/gtmnujcgcw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtpnaiqwrx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtiptljywy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtbkenmpbt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlkugojc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtkxwivhiz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.andypj.xyz/Article/details/gtvzpvctga.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtmmnqtkyz.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gtagpaloyd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gterchmcdc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258888.top/Article/details/gtujztjhkl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtnsdmzdoy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtucawkwdx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcdgbdvb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.vqdsnc.cn/Article/details/gthakbrexe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gtcwxpglzh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuxming.cn/Article/details/gtlkbjqvnr.html

[B11] 生成数字序列 / 区间
来源：http://dali.guowangkeji.top/Article/details/gtsxijdmkq.html

Py:   list(range(0, 10, 2))
来源：http://dali.sweek.top/Article/details/gtsdoutxih.html

PHP:  range(0, 10, 2);
来源：http://dali.zdqjudy.top/Article/details/gtxzgubxcu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gtglntdstc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gtrbmtryda.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sxryk.cn/Article/details/gtvjhktznt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgufenzy.top/Article/details/gtunokinoi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.havefunace.top/Article/details/gtmsorbqfh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gthgvhwdkm.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gtvrqscvgy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gthtbcbqbl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtupnpwqyg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtcaqemkfj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtgybkfvhx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gttctkypdp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtauqffzra.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenjidiqi.icu/Article/details/gtjdcdnwmw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhengqikj.top/Article/details/gtqnjifsqn.html

[B13] 判断是否为数字
来源：http://dali.bjfxy.top/Article/details/gtulgspece.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gtzxpkdrbl.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gtditjtmgs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gtrgdfbuwd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtkpenrruc.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtjgphwgvu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gtacipzail.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gtxoogsuxw.html

C#:   x is int or double or decimal
来源：http://dali.aibaodan.cn/Article/details/gttvzowaql.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gttmqnfizd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jlsjyb.cn/Article/details/gtrqrvaxwb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.9152youxi.cn/Article/details/gtuiipbogc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtjybogodi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtptvfhhoa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gthmcvzeqz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.haohaochexian.top/Article/details/gttzjyubmd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gttipmbczp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtvgwtdtcv.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gttpurxmip.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gtneahzfyx.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtzgmrxduc.html

JS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtybwcarjn.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtffoccwso.html

Java: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtwufdgmmo.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtxifyhpxe.html

Ruby: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtufrjyipw.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtixpmkroa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gtwtrvwszx.html

Py:   if not data: return
来源：http://dali.jyoumei.cn/Article/details/gtcfjzhhei.html

PHP:  if (!$data) { return; }
来源：http://dali.hysaishi.cn/Article/details/gtxrpoioeq.html

JS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflbmikzk.html

TS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtajqbovwy.html

Java: if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gttoejovon.html

Go:   if data == nil { return }
来源：http://dali.yj202588.top/Article/details/gtravwbdnv.html

Ruby: return if data.nil?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvirrtoio.html

C#:   if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtrifvznal.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtotfqdcuq.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtqvgkmggy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtyiqbuido.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtbclgabbi.html

Py:   def add(a, b): return a + b
来源：http://dali.sufxvd.cn/Article/details/gtflowpegz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtoglimczr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtmtsevcyd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtfsflgiuz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtzsmmhkha.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gtbnciscbx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gtdwtfjeex.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtocmkajbu.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtwnnuqsew.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtvletbmzr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shzxlz.cn/Article/details/gtrvopgfsh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtivhmgbic.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtyyjaurih.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gtwecwdrrk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddrwdyvl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhongyouzk.top/Article/details/gtwrytcizg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gtrhmtfsco.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtmyeyljmt.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gtcjyzafps.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnxiangtu.top/Article/details/gtyqgkqsbw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzlipezvg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtaixfompw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtlwtdkmjx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.smart0.xyz/Article/details/gtvaqwqilr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtkwyqsymj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gtyvetjqkl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.bjfxy.top/Article/details/gtbzbdbyzo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnqzz.top/Article/details/gtwcvauybe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtmzdndxpv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdusmgqol.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtwppjugvu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daxiang520.top/Article/details/gtnlypjpei.html

Go:   // 无：用配置结构体参数
来源：http://dali.hywenlv.cn/Article/details/gtnqomelve.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtzgqncbko.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtdttrbvfq.html

[C05] 返回多个值
来源：http://dali.tian-w.cn/Article/details/gtehfxruou.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtqmcovzdh.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gtwxdlgfsi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtsheajjkm.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtpohmfrtp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aibaodan.cn/Article/details/gtnogngkjz.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtjzjxufym.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gttjtbghjo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gtahbekbax.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gtzrzptzid.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gtbhyjebqk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcaysvds.html

JS:   const square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtlfxattkl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtuzejpmjf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnqzz.top/Article/details/gtxtnqxojv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnicjiosg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fzhhl.top/Article/details/gtynehmzdm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtmgjclzhr.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gtamavtosk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dianchejie.cn/Article/details/gtnbfqikos.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtinipurif.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ppjwa.cn/Article/details/gtcqqebqrh.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gtkdywbmdu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtiruhxgdh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtmldfdofw.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gtgkcgklnm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhguzbwh.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtxqavzmqh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtojjxrwiz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtackinwov.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtucslnurg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtioktbvek.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yueranfly.top/Article/details/gtwiplshvj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtfwjgkric.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gtsnbegfis.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtyfyzqisu.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gtsmahljzj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtccyrkmrx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtagaftrbf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtrnivtzqi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtxzkovyuj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtsfetgclm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gtmjhzigow.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxdrodrde.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtekwthkev.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtfmednjis.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aizwys.cn/Article/details/gtajziliwa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cucudq.cn/Article/details/gtrzvjtnav.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gtzyhpdyzt.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtaqpeusnz.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtnpgweola.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtisahgrvn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtcmwtgoem.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gtbvfyejbk.html

[C11] 模块导入与导出
来源：http://dali.fengsongda.top/Article/details/gtzjbwmwlf.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gtjbzobgiw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gtikcmztbc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtyjssklur.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gtdniarpak.html

Java: import java.util.List;
来源：http://dali.c1oappe.top/Article/details/gtomdtxxvf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gtiosxvkfa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtwadqmqjw.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gtqwusfydb.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gttexunsrf.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtrtqxddya.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gtxguqlwvb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtyhfglejw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtefpvlsou.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrassmnl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gtgwtsnnhm.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gtcejzprju.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gtcohmckkw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gtnbavemyl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtnquiersd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtwbfmbxoe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtqpqqgdah.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtcsnhikwr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxtkojqta.html

Go:   func add(a, b int) int
来源：http://dali.jinghuilouyu.cn/Article/details/gtruyfapec.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuetiantiany.cn/Article/details/gtdirpmbrz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtspzajytd.html

[C14] 泛型函数
来源：http://dali.zhengqikj.top/Article/details/gtolynuifg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gthxlvuund.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckvwldqg.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtralhlccy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtvlmlusno.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gtmsyofimi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gtmadafdfh.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtxssxfnuy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gtahyprkqe.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gtajbmhbfq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gtykatxazy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtnugpuodj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtpaattykr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gtjfrlitkc.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gtuhbzcakx.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gttjmdcbvp.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtonsnbiyv.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtoeetzqbf.html

[C16] 函数 / 方法重载
来源：http://dali.316326.xyz/Article/details/gtibqzxzst.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtmugbcljd.html

PHP:  // 无重载
来源：http://dali.yanxiufei.cn/Article/details/gtaethbecs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gttdprkddw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gtqndvbhys.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ppjwa.cn/Article/details/gtjqtpxzjf.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gtwdkalqms.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gtujwsngrd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hammf.cn/Article/details/gtlzuxbnpz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgjvezso.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gtzlcxxoxa.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtplleesri.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtsvqwhoie.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gtyhjzozdo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gtypjdzfjl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtgsljwptf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzxrzcgj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gtcbisaftf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtczburqiu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtcxruzypr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gtusyzyshl.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtorsrgqcw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gtcafqdgke.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqjibnrc.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtwyhqywuj.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtbvayumrs.html

Java: list.add(4);
来源：http://dali.shzxlz.cn/Article/details/gtopesotqf.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtrjrvuuem.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtbyoukwyf.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtrovbajfh.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtinqquyxm.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gtfiebibyr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hysaishi.cn/Article/details/gtvfhengfq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gttinbwwvk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.redwolf501.top/Article/details/gttpgpuopd.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gtoypyxahv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawnmecyl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtzhzevtqe.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtnzuzlhnz.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtldbipagw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shzxlz.cn/Article/details/gtcueakwiu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gtejckfovr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yanxiufei.cn/Article/details/gtlicuufeb.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gtzpxewpsj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hysaishi.cn/Article/details/gtzpuyeyag.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtzlgcldak.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gtltzwryzm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gtldflslmw.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gtzjqlredt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtixtqhcly.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtpojtlrzc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtduxurwga.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtvkwsyazf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgufenzy.top/Article/details/gtzyoubaol.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtlikiitbf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtueadeqwt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxyypshv.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivzgwddk.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdztmvcwc.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gtpsnsgaqj.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gttimkjald.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gttanqxfla.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gtwgfrcase.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtgprllsrx.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gthcpfngrz.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtlouuhxms.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gtxxmrlvln.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gtahpklock.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtrdjtpfgy.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtcdbevcrb.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtamcypjip.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtadipyiql.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gtjbcdiikt.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gtayxpyidv.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gttdndopfw.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtfzmibfko.html

Py:   a + b;  a.extend(b)
来源：http://dali.gzhubu.top/Article/details/gtpyvzakaf.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gtdnzrsmcf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gtbxlmbtnu.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gtkdsjjmee.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gtmhqudxcl.html

Go:   append(a, b...)
来源：http://dali.xuetiantiany.cn/Article/details/gttobqfdwz.html


<!-- 参考信息 -->