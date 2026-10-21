代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gttdibaojo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.pengpengdd.cyou/Article/details/gtdbmevglq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tian-w.cn/Article/details/gtmhwufqqh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtvrgxtzhz.html

[B13] 判断是否为数字
来源：http://dali.bjfxy.top/Article/details/gtolkrzmew.html

Py:   isinstance(x, (int, float))
来源：http://dali.ivvv.top/Article/details/gtmdvuoonj.html

PHP:  is_numeric($x)
来源：http://dali.ybcxt.top/Article/details/gtiweopbhz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtipvmcfvo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gtzmxaazgr.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gtppnreedq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtqqphjayx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gtorpqbuhm.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gtueajlqia.html

[B14] 判断值是否在集合内
来源：http://dali.wangdashe.top/Article/details/gtloolqszl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gtgvlojmul.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gzhubu.top/Article/details/gtzwyodcqc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gtyugifcvq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtlbpmcygo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtvvwbwvfl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hysaishi.cn/Article/details/gtxgaekoia.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.bjfxy.top/Article/details/gtuaeutoqw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtpksxvizh.html

[B15] 布尔运算与取反
来源：http://dali.tian-w.cn/Article/details/gtilcsdkro.html

Py:   a and b or not c
来源：http://dali.bjfxy.top/Article/details/gtughfihmz.html

PHP:  $a && $b || !$c
来源：http://dali.dianchejie.cn/Article/details/gtmjrhibbo.html

JS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtsynlznuy.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtugtmhyvz.html

Java: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtakgkrzhw.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtovvptgmv.html

Ruby: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtsackqrdv.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtquangewi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtkqqftovg.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gtlfrfhjyo.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwwhrxyv.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtkufdkblm.html

TS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gtzvnsmrly.html

Java: if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtkeslicgn.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gtmyvxpuqq.html

Ruby: return if data.nil?
来源：http://dali.aizwys.cn/Article/details/gtbfazfuod.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtlhmqyouk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxfqcrdgc.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtimarsvxn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxogusguv.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtloaylvyr.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gtlfuxgdkj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gttkyluisu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtlqbwgxlk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtrcvmqfcp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtjcbsympk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gtbcfpmewj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gtyhaxjwmf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtpmqytvhn.html

[C02] 默认参数
来源：http://dali.yj202588.top/Article/details/gtmaeqwgjl.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflplqjqk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangdashe.top/Article/details/gtqcontiwi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtjruwwqxz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtyotriqla.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gtcnileitu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gtolwbjoub.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gtsovfkkxl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gtmavbmsow.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmxmmffp.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gttveuivhm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hysaishi.cn/Article/details/gtbphosprw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtdklhghdb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtidzvyzca.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvwhhkci.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnqzz.top/Article/details/gtoyzwsnzm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jiagoushi.top/Article/details/gtjozhyioq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pengpengdd.cyou/Article/details/gtjpmhahvq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuanzx.com/Article/details/gtfzuvjpyx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gtvmibhtyp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jianghu66.top/Article/details/gtdwcbwthb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtxdjpscwh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtebkwmqrj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gtxbvcyslq.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gtdjugpdbg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtkesdvzxl.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtdilzsczp.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtsseuzrqw.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gtvvzzkorl.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gthdbjhumu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtwfijppek.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gteofylehn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqbdgobo.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtqdcdeemd.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gtoopaqjdg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yanxiufei.cn/Article/details/gtsvqxlumu.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gtgqbdavxg.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gtiehzfjzm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gtqkhubfwo.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtitmtrilv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtegstsnhi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanwpcspe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gtrnkvolaa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gtsecsnwld.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtixsrddfd.html

[C07] 把函数作为参数传入
来源：http://dali.shuidangran.top/Article/details/gtmcregdar.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.meibo888.top/Article/details/gtbzvnpnmb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtwzvmvwlx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmihhyxs.html

TS:   arr.map(String)
来源：http://dali.yuxming.cn/Article/details/gtqjgoangz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gtdjlunmfy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gtgqduwkmm.html

Ruby: arr.map(&:upcase)
来源：http://dali.guannengcc.top/Article/details/gtzqrtxwpi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zdqjudy.top/Article/details/gthhtypduj.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gtifrejive.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gtafmbjkjo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gtskahztco.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gthdtgmynr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtynihymdw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gtrnwxnver.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtrrzkzsfc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gtkvlqsrbr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtgkrwatej.html

[C09] 递归
来源：http://dali.iojbl.cn/Article/details/gteidjylhh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gtoqjdibfb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtehgpmjms.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtqboowutj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtlwxmbsso.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtuojfoijg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.haohaochexian.top/Article/details/gtwplssmxp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtpmltggzp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtyxoscunp.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gtjobvmxno.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gtspxajykn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtmrjtwdni.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gtmwdxthpb.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gtwmhyotqg.html

Java: 方法内为块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtyfktazei.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhutjhst.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtgzmhdgqa.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtlksbqzha.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtsuklhsnd.html

Py:   from module import func
来源：http://dali.hnxiangtu.top/Article/details/gtxvherdug.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gtaktblhcs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtefuufwjh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gtmwvgdveu.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gtpkhmmysw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gtzagjmttq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gtdktykuzi.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtczmlxrmg.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtacelkavm.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gtutasixfk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cqqwz.cn/Article/details/gtlbmkajog.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrbgqdrk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtxjsgfydv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gtqthgykcb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gtpezctyet.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gtsuvlpggl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtojfgzvzu.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gtvdopefan.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtrsuzeear.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtrecicgxm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gtgidlxoha.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gttrkxysrj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtnwphixov.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gthagyymwl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gtwrxhmkrx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gtlakfgide.html

[C14] 泛型函数
来源：http://dali.shangyingyoupin.top/Article/details/gtpkiwxxyn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtevvjrsxe.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtmpzmpftn.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgshjpmj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtkejtcufn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gtreuxrlpe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtnwhgieti.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gtdwtdnrrb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gtdydptfoq.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrbnmfnf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gtmuekbhyd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gtaoevaamf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkmzxyum.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guannengcc.top/Article/details/gtkivtdemk.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gtyymmgaet.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtlbahonzs.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqjfknsl.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gthdhfswhf.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtwmueljzs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gteykcjluc.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gtcipveuhv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gtapfvrewy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gtqmxwycfq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtpzoyyphg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gtlrepfjzc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gtlnjrjbzl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gtoqxibege.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtslmqyldv.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gtablgmuxw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrtsaqfat.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtziazdbpi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gtddjwrgxo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtmzluxbst.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtrvczsuhy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtptkqmaxw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sufxvd.cn/Article/details/gtkxivbdqd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.0kj1m.cn/Article/details/gtatekqqyy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gtykgwmeiy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxinkj.top/Article/details/gtlwxivoal.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gttvjgvyjy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ydzc1.top/Article/details/gtbtvgzlhl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtdmhktktd.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gthdcwoork.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtcyuvejrf.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtozqmoosb.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gtcrybyevl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gtkihgadiy.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gtrepgbryh.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gthpqdooie.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtqlfmvptx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gttkblxaah.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gtjzcwpcha.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtlcwjxzqi.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtrjhaaeqd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gtfjubrsza.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aizwys.cn/Article/details/gtcooketdw.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtmvpldpwk.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtvrspewcl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtoveklkno.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtzhcpaacj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gtluvoirza.html

TS:   arr.splice(0, 1);
来源：http://dali.bjfxy.top/Article/details/gtqxcvigps.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtrymzslbp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtjccbwwik.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gtgdccogfw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gtpikijamu.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gtvgfpjbcl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtyqhghfqw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtivbpmchh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgwkwsyv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtpmjrwmqm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gtzjnzflvp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtpkkgtepn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtfysptszb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtpucmqubz.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtcnjqwfcl.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtkmcaaweu.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gtfbyaswoa.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtepetlkfg.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtyyayazxa.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gtlcwdgyvp.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtwojorfsm.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gtrlhfrmvd.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gthtpcbvqk.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gtxxfiipml.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gttshefwgt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gthqkmlunx.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtuntchncf.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtahbwnhek.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gthiwhkzlm.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtwljztssh.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gtwbsxoala.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiisngbv.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gtvjiwohga.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gtjbeuvmzk.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gtjaokpzmr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimoapsyi.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gtmrwycshu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gtkrcovtxa.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gtdakwvulz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtbfbakauz.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtljgwvutg.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gtajoqnfki.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtpfftdyfo.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gtrfpjquyn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gtsiltazgx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gtgxigbdhh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gtzmtblach.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtrhxzcysw.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtnoxgnbdg.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gtbyhxajch.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gtwoajooir.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gtjczhcrwy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtflfmcfcy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtkbgmkmmg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtgzepyqcy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhixingplan.top/Article/details/gtqovtsson.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gttdyeyjrk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gtfvxxctiy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gtwcdghxzn.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gtmdpejqbu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gturrbbdre.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gtxxgqwzpt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gtqzmowdpb.html

TS:   [...arr].reverse();
来源：http://dali.xinyue.icu/Article/details/gtwrqphddh.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteupujaty.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtacljfudx.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtngdmfrid.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gtqrarpqpr.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gtjjtbvpsy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gtwojvtyyt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtlrogysdo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtrbmyyhht.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtvlchvond.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gtmmboyrax.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtrkqlpyas.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtbdyygfer.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gtykbpbkyp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gtdgrkkxtg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gtvgefmoph.html


<!-- 参考信息 -->