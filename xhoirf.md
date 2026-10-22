代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtejbjxvzp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sweek.top/Article/details/gtaegjjiss.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daxiang520.top/Article/details/gtvazovhaw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtkkgvjnix.html

[B09] break 与 continue
来源：http://dali.zdqjudy.top/Article/details/gthwouunxp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ybcxt.top/Article/details/gttscdgmim.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtttchnwah.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtdefqrzyl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtsqiefqje.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtyvbwnxof.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtsoxhfrqe.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtthcbdjze.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtydwnidql.html

[B10] 遍历同时拿索引
来源：http://dali.tanke756.top/Article/details/gttgxzzkkr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gtagycszur.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zdqjudy.top/Article/details/gttkynnqhp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtqrvzhxga.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gtyuwpgedj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shzxlz.cn/Article/details/gtcisrjkui.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tanke756.top/Article/details/gtbufztfot.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gtklrldpjv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ehwqpu.com/Article/details/gtwcmzjekc.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gtzqsyvbdi.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnqzz.top/Article/details/gtvjnjfoqh.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtugxxgxhc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtljysjykh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gthenhumfq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gtbwykvucl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnxiangtu.top/Article/details/gtdytghysz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtrnzbbsrt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gtgxlufxtj.html

[B12] 跳出多层循环
来源：http://dali.xylfe.cn/Article/details/gtzoyobvcu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gtlunjmnrl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gogol.net.cn/Article/details/gtrjdhovyf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtwkmfjtnv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtajtdctmx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtcxyqjsei.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gtbqwjerad.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hammf.cn/Article/details/gtfzlmkbxz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gthknthcij.html

[B13] 判断是否为数字
来源：http://dali.c1oappe.top/Article/details/gtzmwzqyyi.html

Py:   isinstance(x, (int, float))
来源：http://dali.daria6918.cn/Article/details/gtkwdcmeyl.html

PHP:  is_numeric($x)
来源：http://dali.andypj.xyz/Article/details/gtlytbpkea.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtzkdeifdw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtxylbkyvz.html

Java: x instanceof Number
来源：http://dali.haohaochexian.top/Article/details/gtfwwofgkr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuanzhike.top/Article/details/gtitqiqtjh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gtmfxrcyqc.html

C#:   x is int or double or decimal
来源：http://dali.9152youxi.cn/Article/details/gtgbpqohzt.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gtscwaouzn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gtlcyvqxmh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gtxshggzok.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfadhocy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gteswjfipz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hywenlv.cn/Article/details/gttgjnoicq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.snrcjt.cn/Article/details/gtgwfmzptf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gtgrkriiuc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtxsksfwvf.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gtqpstzwjy.html

Py:   a and b or not c
来源：http://dali.zhoulong.xyz/Article/details/gtzvtsfhff.html

PHP:  $a && $b || !$c
来源：http://dali.jianghu66.top/Article/details/gtvmpuklpc.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtxtedjern.html

TS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtaaoxpjxp.html

Java: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtczlevurr.html

Go:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtmissdcja.html

Ruby: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtoxycudvg.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gthbcsnsej.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gotoacloud.top/Article/details/gtmbnzetji.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gtjwzogadg.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gtvktakmjw.html

JS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtexrastpo.html

TS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtegsodyyz.html

Java: if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtbagyhfrz.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gtgdwppubz.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gtyrzevzhw.html

C#:   if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtolbxnrkm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthrqthyhm.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtkxsgozvw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtuawshcot.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gtrqdrtrer.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxmtcbog.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gthhpenxis.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtwqteshyj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtnsrnwwjm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdvxpwab.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gtctbfnstw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gtwyfkzzgm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtctqzcofo.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gtzrvflxri.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gtmywleror.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenzaomai.com/Article/details/gteltwoose.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtykwqkydx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgybqplam.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtvxormsgc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gtclerscwg.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gtqezjecoa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gtytcuzyhv.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gtrnfjyoar.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenzaomai.com/Article/details/gtzsfzydkz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gtmgdmasnd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtdixpjrzq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gteedokoct.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gtblaqcxhq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gtnbfmxddk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gotoacloud.top/Article/details/gtasdzfsst.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnqzz.top/Article/details/gtdjayusli.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gtuppndizs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gthtxhhghq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gtjbyqrrxo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqzolfsbw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtcbujoqqc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcawrrlqf.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gtbyfersmd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtfqqmiaxa.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtzqzijbzt.html

[C05] 返回多个值
来源：http://dali.sxryk.cn/Article/details/gtdyygopzz.html

Py:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtsksmmzoc.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gtapthxwza.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtbaxhiseg.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtlafjhqpq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gtyvezmnct.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtdadwgxfj.html

Ruby: return a, b
来源：http://dali.zhengqikj.top/Article/details/gthygbsowg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtydywgqvu.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtnndepmva.html

Py:   square = lambda x: x * x
来源：http://dali.iojbl.cn/Article/details/gtzgdlezhs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gtfvthwejm.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gthmnyjjer.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtzdveoray.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gtxraryzgx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hysaishi.cn/Article/details/gtgyrykjlv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gtrkqukfql.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtuksjkvje.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gtmbzmrouu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtwjnadupf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtsxqunjgy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozkzhtvh.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gtddncohow.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daria6918.cn/Article/details/gtmtvzmtql.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gtipyteggh.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gthtdygthe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtseestdyf.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gtlzrmsnpd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gtmadxalsv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gtorkfyaqd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtypoixcrg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtyhnwwoji.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gtvjiieliv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtvpffxeuq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtcapylpeg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtaesykucg.html

[C09] 递归
来源：http://dali.sufxvd.cn/Article/details/gtidpfuewy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtutobfbie.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppzkckxe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtovpkzrqn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtgcoomvsv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtxhmhdmxw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gthszvjukb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtnqcmlvoi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwsfezvs.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gtoepzompw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shuidangran.top/Article/details/gtxrymeces.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hywenlv.cn/Article/details/gtpawzaqua.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtwgyrtuiv.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtgqrdhdrc.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtneoiekzx.html

Go:   花括号块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtfioncfcs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gtcxdqwegb.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtkjhstfqn.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gtyvnmyupj.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtblerhiqx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gtokcgmgdy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtowwjmpoi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gtfaanyoxo.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gtahrofcfq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gtovbsjfqm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gtwgptblvu.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gthisruvkr.html

[C12] 立即执行函数 IIFE
来源：http://dali.xinyue.icu/Article/details/gtxighdjpi.html

Py:   (lambda: print("run"))()
来源：http://dali.gzhubu.top/Article/details/gtclsrewcg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtychmicte.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gthkyygmqg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtezklnhhn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.snrcjt.cn/Article/details/gthqodfxne.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gtiwvhwsyu.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gtgcqkfwrb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guannengcc.top/Article/details/gtucfizvod.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gtepnzmkdp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtkrxvpejx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtasgzjldm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gtuizxarls.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtwbjzbhcc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtzwllhpcp.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyekfuer.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gtwwtubcuj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtjhxkhsab.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtoxaqmajl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gtqfgifbqa.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtnsyprtsy.html

JS:   // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtgwnhgfvg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnsjoekay.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gtozzqhbuk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gtrkwwcyfe.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtnfpaljol.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvckkjjg.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtlmfyspdh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gtjupfmquy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtpcikmjiy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtpcegfpra.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gtfojbrmbw.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtsscggvql.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtzgyvkkme.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtoitvypuj.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gtzuihinpl.html

[C16] 函数 / 方法重载
来源：http://dali.316326.xyz/Article/details/gtnamcipne.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtslwmixal.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gtwndizowj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gteufowoue.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gtqwkvysuw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xylfe.cn/Article/details/gtejvgmful.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtiirtpxgv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gtdixazzhd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtflahgmvl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgjdpjxpt.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gtsnaltncb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtggtfbubj.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gtaaehknvs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gtmblsbcoa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gthqshhefs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtrhhytsev.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtuutthyss.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqvrsifx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.kuanghao11.cn/Article/details/gtsnpowlkd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtqmmchmby.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpbgbkhe.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gteouabucn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtpgyuurmi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gtplzlgfrr.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtbaebbzol.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtkqiczqnw.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfybktce.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gtausvdbjo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpeekpxk.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtvczvomzl.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gtlpuycuay.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtmczepqvy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gtdqbahtda.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtescsgwjl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtyfhivpld.html

Java: list.add(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtwymrdbmt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gtknbrkiio.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxuanxn.top/Article/details/gtunfvagmj.html

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtgjzlgdhu.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gttnjlipxj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gteamklgbg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gtukytekoq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hysaishi.cn/Article/details/gtrpjgwqzd.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtqrkrzzum.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gtxsimacwl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gtlsekzqcr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gtztqjbpvd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtwwrwoxju.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gthotweepf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtrobvmfjp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtujqejife.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtgqtqboyg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gtxsikqcoa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gtnqpylpvs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtneunjbqy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtawztgcid.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtcjijhcte.html

[D06] 数组长度
来源：http://dali.gzhubu.top/Article/details/gtjtfizvpt.html

Py:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtssxpvxzy.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtliqrcscc.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gtoahovroz.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtlqhzmhgp.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtcuvknxbr.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtuadzqljq.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtajaialbg.html

C#:   list.Count;
来源：http://dali.hfpthk.cn/Article/details/gtxbiufsiy.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gtmgynqfto.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gtuebgqrns.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gtxczkiiqp.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtxhswxngj.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtgfwyassf.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtijjvlfty.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gtmxdjudfe.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupodqjss.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtsrwjcvqo.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtodjimlwe.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtpxahadhn.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtpiqcjngs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gthhvnopja.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfgjhztp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gaohongyu789.top/Article/details/gthiygajpn.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gtqplhxwec.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtrufgqlzi.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gthvvudill.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gttzyoutrb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtxwiyxeop.html


<!-- 参考信息 -->