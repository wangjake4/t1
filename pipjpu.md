代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gtgskhqnoa.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtsyvarolw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cheryme.top/Article/details/gthltukqrc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yueranfly.top/Article/details/gteiwvvsnc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtuyttbmje.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzymhapue.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gtafgrtzno.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gtgcconxyk.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtdjjiurmg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtuczynhjj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gtpuoxcuxo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gtubwtnfuw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gtwjstlsio.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aizwys.cn/Article/details/gtsjjsjzab.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aibaodan.cn/Article/details/gtijpbczza.html

[B12] 跳出多层循环
来源：http://dali.chenlongwang.top/Article/details/gtfvwamdol.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gtiisnbnxh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfzwjxmh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxzugkdq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtclciwkdq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtahfcspxc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhiwuduotai.top/Article/details/gtyqhkcnti.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jianghu66.top/Article/details/gtzcizuxji.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gtzgztoxsv.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gtmtwgrwwl.html

Py:   isinstance(x, (int, float))
来源：http://dali.yueranfly.top/Article/details/gtkmqvajtt.html

PHP:  is_numeric($x)
来源：http://dali.guannengcc.top/Article/details/gtelkeowuw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtjrqxxlpl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtgvabiguz.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgapbpdz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgufenzy.top/Article/details/gtysgbreha.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gtqgwobqpy.html

C#:   x is int or double or decimal
来源：http://dali.yj20258.top/Article/details/gtqtesibyq.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gtecnafnbj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhongyouzk.top/Article/details/gtmcecoaam.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ydzc1.top/Article/details/gtvjpvyqsy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtezzpdngv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokayrdnz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtcvemsghl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gtlbigikzp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cheryme.top/Article/details/gtljqoltjm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gtvuxbfgyk.html

[B15] 布尔运算与取反
来源：http://dali.hnxiangtu.top/Article/details/gtzkzxhwss.html

Py:   a and b or not c
来源：http://dali.tianlin.xyz/Article/details/gtptuxoahe.html

PHP:  $a && $b || !$c
来源：http://dali.yueranfly.top/Article/details/gtedodtsmt.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtptzpvnka.html

TS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtccsautrt.html

Java: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtzlbsldnf.html

Go:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykdpbllu.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtxzcchjhi.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtsawxfewa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ybcxt.top/Article/details/gttltkhrbo.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gtrksaxyqf.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gtqgfnhwpx.html

JS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gtmldsdmfd.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gttdlwinle.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtukmznwzv.html

Go:   if data == nil { return }
来源：http://dali.jinqigfzy.top/Article/details/gtvqjukayr.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gtpaivhaht.html

C#:   if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtorkjzepa.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvtdhvaoy.html

C. 函数与作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtdkcwglgg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcmmhnqmz.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtqonqfujq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtswtkuuor.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstrdipty.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtxcxwtsww.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtuptqvzgd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtmueneyrn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtflwyvqzz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fzhhl.top/Article/details/gtmfuezgvk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtfwpoluqt.html

[C02] 默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtjjeswrdj.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gtrrxbqqjg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyckwrxid.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtojatdxga.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeqfofkp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.bjfxy.top/Article/details/gtdskemlhy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gtfpqjjbyb.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gtmmilyjlj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gtdnrwuwco.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtmuprlqkz.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gtgifimbvc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.mhx1999.top/Article/details/gtuyhfswyv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxzagdhw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtanpfzljb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gtwwupkymi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gtznxrbeso.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtppoptick.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtahmwaeqs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gturafzrsn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnqzz.top/Article/details/gtglnzgmsq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnxiangtu.top/Article/details/gtmgffiikr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtbfsmuqub.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gtrbepbnsh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtbfgweitf.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtdyrrqgvq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtlyvbcdgd.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtkcdmxskq.html

[C05] 返回多个值
来源：http://dali.hfpthk.cn/Article/details/gtfsfdirtc.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtjgslhybw.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gtepibtrqp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gthzvaqvnl.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gteggylpuj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfrekgak.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtdrtzhscl.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gtzqnfjutx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gtlszjrxis.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gtcsudqgtg.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gtvhrdyktu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrremkqwz.html

JS:   const square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtjduixjyk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtsjbmbfzx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gthkigvcmv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gtjrpdidki.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gtitleuakt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtlkleulfa.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gtscgefoyt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jyoumei.cn/Article/details/gtwayrzkwl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtlauzhlom.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcfawkyk.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwipfqcid.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gtdsjpxufd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgjkghbf.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gtgrroboam.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gtcxepxzqj.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtlaqmpmsm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.bjfxy.top/Article/details/gtnwqgylux.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gtuqhvjpxs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtkbpkykfy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtasnaekon.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gtifryfbzl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gtlhwdatwa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gthimhxarx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtjlexqsjo.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gtwzbwafdv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtgavffsqd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtjeazqpah.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtbdcjsvif.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtvixxguck.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtzyndpafd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtlshjzqre.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gtwsdahydc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gtluhghnto.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gtzzltjemo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gtglgsyalt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtndldbqtl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeiwhfjw.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtvswohaci.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzmwytjt.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gtxoxnspze.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuyostya.html

C#:   块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtfpswfsrs.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gtnvtjfjhm.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gtjrpkwlef.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangshuangyany.cn/Article/details/gtqovonkmq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtnuauidno.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gtvfqtiafg.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gtklfpmlxm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtnhywuyas.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shzxlz.cn/Article/details/gtykfuktts.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gtubfbtenu.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfukvome.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxajvwte.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gtgtovplmv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gticapbwff.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtynhafyao.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gtjgvccgem.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gtqhyxbpdg.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gtfjnvoxtc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gttfhaqujw.html

[C13] 类型声明 / 类型注解
来源：http://dali.svipenyu.cn/Article/details/gtbtyvlmke.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shuidangran.top/Article/details/gtwqsztpzd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtmvgvleqn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gttaprzxun.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtaaoufvts.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtgwmfewql.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzflxtgr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gtgddxyujn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gtmwdvspou.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtsngmaxjd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gogol.net.cn/Article/details/gtjhhfocxx.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtvzqskjuy.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtggezjemp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gthhglnnsw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gtlqlqnrkm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtclovdcbq.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnotqsdiy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtexovttix.html

[C15] 解构 / 展开参数
来源：http://dali.yonumen.top/Article/details/gtjipdnaew.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gtehekoyhk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gtoejnfcor.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtggjlazmp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtlhdxwybv.html

Java: // 无解构
来源：http://dali.xylfe.cn/Article/details/gtbawopzvk.html

Go:   // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxxszhmo.html

Ruby: a, b = pair
来源：http://dali.jqgfzy.top/Article/details/gtoiohfcfs.html

C#:   var (a, b) = pair;
来源：http://dali.zhoulong.xyz/Article/details/gtnqzvracl.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gtfoaqidze.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gtllvvbbqc.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gtyivmyjkm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gtohcpmqvm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtdsvjitvc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtoknedfdu.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtonptkfvn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtskvqcpne.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtxkzmqzei.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtyvufsguz.html

D. 数组 / 列表 / 集合
来源：http://dali.chenlongwang.top/Article/details/gtabdcyybc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtryqmrmhq.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtrzutcfpu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gtqdtixupq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258.top/Article/details/gtphtaitov.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gtcypjbrbk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtbjjwbagw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtunkxanny.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gtidjrfhde.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gttbahnyaf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gtqjuwnrfn.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gtgfbzkudv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gtftdeynnr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gtxhdmrred.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtytfawffx.html

TS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtsvuezxhp.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtnrdfsvfz.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gtjcpcqdsa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtjgnrpuim.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtcmllxprz.html

[D03] 在指定位置插入元素
来源：http://dali.yvedp.cn/Article/details/gtwtkjvzme.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gterqgajja.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtejbpztkm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gtdtuybtnk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtmwfvvbqb.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtcgoaxxdl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtjgkyojbx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtllgvtlyx.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtniomgaio.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gtdjvgeoik.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtzljrbokx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtpfrpqiqc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gtlugvatyt.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gtlblejhqt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gtkwswzmqe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gtqbzauipz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gtfccpgpui.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtgmbdvtus.html

[D05] 访问与修改元素
来源：http://dali.wangshuangyany.cn/Article/details/gtawdoirux.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqtrtgrq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtsfqcnozv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtoxwwzmta.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gttmzycsgt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtkczhxqtr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtuhbwxnsc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtmnqydscy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtvhzxwkqf.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gtbhortnyz.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtngoxvhfr.html

PHP:  count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtixtakghu.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtcmhfguxv.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtvposboas.html

Java: list.size();
来源：http://dali.jinghuilouyu.cn/Article/details/gtzheyijli.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtsbxrrsbw.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gtrjvyrtrf.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gtgthnrjqp.html

[D07] 切片 / 取子数组
来源：http://dali.gzhubu.top/Article/details/gtulepapcu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gtbrhvbzfw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtlnudjqpf.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtkieokfhc.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtktenrhrj.html

Java: list.subList(1, 4);
来源：http://dali.yongpay.top/Article/details/gtdpsrmfct.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtaxxpcqxx.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtnaritmew.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtjtnjvnkg.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gtlytvbddp.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtjlqoppwo.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gtxcsscnmq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gtgjsbtdxh.html

TS:   [...a, ...b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwlafygn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.mhx1999.top/Article/details/gtvrscbexs.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gtertdmtvg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtasomhqla.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmvciwtnp.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gtwcjduxff.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtlkbhftko.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfueyfdn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gtcciadknv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtqpdayqyf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hfpthk.cn/Article/details/gtwadwsmjt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtubrqkzhp.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtzxlutwdc.html

C#:   list.Sort();
来源：http://dali.yvedp.cn/Article/details/gthcdtrmbu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtjhltngjg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtjzjofsav.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gtjoejxzid.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtirhfymmp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtfozlyvlh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gthqejzqey.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gthvbxxgvh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gttmjxvnph.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gtuktddfel.html


<!-- 参考信息 -->