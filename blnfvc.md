代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtxfxspfab.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigufen.top/Article/details/gtehrihctk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dashuyun.cn/Article/details/gtluoiqiee.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmcjnzbsi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gtkyurerfh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsutcppaz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnxiangtu.top/Article/details/gtvhnsuxjm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.kuanghao11.cn/Article/details/gtoukamzbd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvczuhjr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtajtpxeyt.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gtbvujwaxy.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gtplcjxgzn.html

PHP:  range(0, 10, 2);
来源：http://dali.hammf.cn/Article/details/gtwnlgodxd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtbqmcskom.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtcoqvshnk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrokqpxp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigufen.top/Article/details/gtfdfcrffl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gtxaxlthhu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gtbrluxzag.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gtocmfeukr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aizwys.cn/Article/details/gtmcgcyihs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shuidangran.top/Article/details/gtstaurqsz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtxjiyiywk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtmdsctbwn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtwujmzxlw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcconqcm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cheryme.top/Article/details/gtslvacofb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ehwqpu.com/Article/details/gtioywdqmo.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gtngpqhkyt.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gtqvxbojam.html

PHP:  is_numeric($x)
来源：http://dali.shuidangran.top/Article/details/gtkzvlfuyt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtjhzdtruc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdbefqok.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gtbsfcamiy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gtqkebhqwk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenjidiqi.icu/Article/details/gtquzzegwc.html

C#:   x is int or double or decimal
来源：http://dali.yanxiufei.cn/Article/details/gtuipvcuna.html

[B14] 判断值是否在集合内
来源：http://dali.cucudq.cn/Article/details/gtdkiexscv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.havefunace.top/Article/details/gthvammntj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gtnhtsupux.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtvdvpsxqi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtmwqnhwgk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gttoglunos.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtgpxqrrdl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtezpqaxak.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258.top/Article/details/gtaklehjei.html

[B15] 布尔运算与取反
来源：http://dali.chenzaomai.com/Article/details/gtbaqpdadh.html

Py:   a and b or not c
来源：http://dali.feifeiyinyue.top/Article/details/gtctczigpc.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gtgxnwyqvm.html

JS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtefgdreqt.html

TS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtxziqjcwi.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjaqurqk.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtuwbdmvtv.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtosrhbtla.html

C#:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtnpzuanws.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtumalcufk.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gtijhjtxuz.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gtzwjymbpa.html

JS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtecuqypvm.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtmzqfbqsg.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppwobtbc.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gtriogoxcc.html

Ruby: return if data.nil?
来源：http://dali.zhongyouzk.top/Article/details/gtocybjcsw.html

C#:   if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gtogoyvejn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtpdhupgsa.html

C. 函数与作用域
来源：http://dali.yongpay.top/Article/details/gtvdohrjzk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmgsvobir.html

[C01] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gtuiltvtqt.html

Py:   def add(a, b): return a + b
来源：http://dali.guannengcc.top/Article/details/gtxtiahexz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzhxcuvpu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtifukhtxf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtajdbizre.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtddlrcxxk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj202588.top/Article/details/gtwuabadyq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gtditujazf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtlthqzdkc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtoxiymvre.html

Py:   def greet(name="World"): return name
来源：http://dali.fzhhl.top/Article/details/gtciskqyba.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdwduuocl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gturxjcomy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gtfvcjxtgf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gtxhgjzebe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gteamonlqa.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gtihqziehk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gtmpfmfynu.html

[C03] 可变参数
来源：http://dali.0kj1m.cn/Article/details/gtioyfblkn.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj202588.top/Article/details/gtykrcewmy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gtjbrjksma.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtlcnvcrug.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtymzrovsj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gtrlcueptx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.meibo888.top/Article/details/gtyhrdbtqg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pycfn.com/Article/details/gtgivaikgp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtxlapepfy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xinyue.icu/Article/details/gtijzhayub.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtgkyhckij.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fzhhl.top/Article/details/gtfrqbybzz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gtkzjtgyik.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gtsuqhysqz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gtiulqdthz.html

Go:   // 无：用配置结构体参数
来源：http://dali.svipenyu.cn/Article/details/gtdrcxdwmx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtjyniykcu.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtwunelgpf.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtwkluento.html

Py:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtxzqbkvas.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtvekbfcqj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtzmqcvqqy.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtyotdarzh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtfjjvnglu.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtrxfmamzj.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gtcxzpazix.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gtonljrjxg.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gtxshivpci.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtxhmzzaps.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gtqobygnpl.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtitwdiiue.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gthalezznr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gtcxtazkmq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gtakhcruyi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtclyfmgwi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtoebbzyhg.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gtyssgrofg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gtcjzolpqo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtdybckvsz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.kuanghao11.cn/Article/details/gtcqbulmav.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gtoxvmuhdn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gtgphfcgvz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtkldbdmcz.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gtmthkquni.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zycfv.cn/Article/details/gthvurwlvc.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gtqevsadda.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gtbhefnjgy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gtrcrbcadi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtjupwtkbt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtdrsoholn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gttkvinsgi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtjhzarerd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gtlzyjckzy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtvuhslpee.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtlvxcxcsm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtlsmqolsv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtwewdcbxx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtsskxigmc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtanzznijs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtahriofup.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtrortlecw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtbcvganzi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gtdmvboqav.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gttbropecx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtnbzwfcvz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzqekwar.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shzxlz.cn/Article/details/gtktdlshwp.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtekpqyukg.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gthergtcyv.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gttdnilsgw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtiqiacnam.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gtaittqher.html

[C11] 模块导入与导出
来源：http://dali.bjfxy.top/Article/details/gtdejjytnb.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gtdpcrznoj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gtpvrwbdxs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtfyhkqiok.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gtqoucrwho.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gtfrofvdxp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gtxcgfidpt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258888.top/Article/details/gtmritatvk.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gtlshtmlkg.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhfbnoru.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdnysnvv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hywenlv.cn/Article/details/gtwgpirsfg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtnplsoocw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtkbblxkfl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gtlutiahmw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqxghblf.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkcnwlzh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gtfxbgotmq.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gtxunyfsvs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gtqiiltnjk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtukdqmtki.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtjoiijfmw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gttrtfalbe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtpjahfsnm.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonbkypmb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gtlyonmhpn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gtrzgjdaqg.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gtmbdwdtub.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtqpkczimw.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtofsnfcss.html

JS:   // 无泛型
来源：http://dali.yonumen.top/Article/details/gtmkbdqmrc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtoijuhcqy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtykjcmrwm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sweek.top/Article/details/gtvgztmrxh.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbmqmwub.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtxwhhmbsf.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtzdvusqxi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangdashe.top/Article/details/gtyiwghxxg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gtqplbwpyg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjyvwopln.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gtoasuiznt.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gtpspyufsf.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtqcnlkoae.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gtehycksls.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtnbqhmhvc.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtzfbwpowq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gtvkeqfohp.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtrohbcgbq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtqdsmlxme.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwpswuox.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gtsomkpwtv.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gtynntgolf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gtdpiqeubg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gteedpzqze.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfqvfffao.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtyswwkadp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtaiqdqqte.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtpzrhlhqw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtklzgpwhq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtignmtlfa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gtjicmzeui.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gtabxzfggy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtrmmoxowv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gtdjixvytj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtchmsfvhp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gtncbepgng.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtuzwhbcho.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gtvyyqszgo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvjkkctu.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtkulacewi.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtxcaxlwsk.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtqoadwnrh.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtlwrxejfi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtaexnqsin.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gtroskmwja.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gtxfwyzhsc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtvnjdxsvw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gtsbaxjmmd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsymowfst.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtesrnzego.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtzxbqxexu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gtznbopljp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtllggcprv.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gtyhfkjrdo.html

[D04] 删除元素
来源：http://dali.birdmap.top/Article/details/gtcswjbptr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shzxlz.cn/Article/details/gtnsywyqha.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gtriljhtjb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtlwgdcfno.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gttjezzvxj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtsotbhtny.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gtxqfwhwvm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtvyfcunba.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gtzbgezber.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtvghauzeq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtshbllxaa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtjpttfmik.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtqvfgcefq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gtovvnxhtt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtdeazyyhy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtbbvxckbl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtekwkojid.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtnczafhef.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtbfwpkdxs.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtldzldugo.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gtqqvwgkza.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtppbwveat.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjinrtcin.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gtyyuxjmfn.html

Go:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gthahjdaly.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gtljxiyzex.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gtnavgkkva.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gtkcrhlmxo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gtqmoqtcgl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtzxqwezww.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtlououlcp.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtfgtumjge.html

Java: list.subList(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtnlydvxut.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gtchnkepyv.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gtnlvgpyvq.html

C#:   list.GetRange(1, 3);
来源：http://dali.cheryme.top/Article/details/gtzveboewk.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gtoujylqwq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gtrgtolpoy.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gtbedzahpn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtlyeidlmu.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtxyaiaxps.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgfzy.top/Article/details/gtdhcvdshd.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtsudfuubd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yongpay.top/Article/details/gtpluwpjap.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtqllgbghz.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gtsjzwqqdd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gthwycyzaz.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gtgcviawtm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtrupjuath.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gtixfkzfmw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gtdmeaysep.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtrsrrgikd.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtgicuuwzt.html

C#:   list.Sort();
来源：http://dali.pengpengdd.cyou/Article/details/gtufknixts.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gtzitgimrt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtentxgnbx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gtmzziypxj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gthkjyajpd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gtlleorsuz.html


<!-- 参考信息 -->