代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtlelyznwi.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gteyvebsip.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhixingplan.top/Article/details/gthvzlmekz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gtfketidid.html

C#:   x is int or double or decimal
来源：http://dali.yanxiufei.cn/Article/details/gtgulshxcq.html

[B14] 判断值是否在集合内
来源：http://dali.ehwqpu.com/Article/details/gtzonlcajn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtkymqnubg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gtialkcjvb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtchpryptf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gteegettyk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gtalwwkmja.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtehqcysxi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtdovohhis.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtvopyhtps.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtnekjrrss.html

Py:   a and b or not c
来源：http://dali.zhiwuduotai.top/Article/details/gtlwvouuuw.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gtgjzkqcor.html

JS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtqbmzuyne.html

TS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtdtagopbm.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtrzqamdyp.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gttaqitdgp.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtdnoxlvts.html

C#:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtyxkzcneh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yueranfly.top/Article/details/gtektorhaw.html

Py:   if not data: return
来源：http://dali.xylfe.cn/Article/details/gtzsyeonfx.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgufenzy.top/Article/details/gtothlcpyn.html

JS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtlkgpvkxz.html

TS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtuhihraav.html

Java: if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtzbwedxms.html

Go:   if data == nil { return }
来源：http://dali.sysykeji.top/Article/details/gtwmsvpiki.html

Ruby: return if data.nil?
来源：http://dali.pycfn.com/Article/details/gttbngldbp.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyleqptku.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgpsgvhvw.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gtebbbpekc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttrwikbrk.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtnxkljmyy.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gtufgkfwac.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtgahbqbmc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtxiglueve.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsoldhurz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtfqziwlxt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gtouxmhgya.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtsyjvrfzn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtuarehami.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gtduczcraa.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtgvbyplod.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjleoggsu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gthczdoimx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtfjeywiev.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtsrmscknt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.vqdsnc.cn/Article/details/gtrgvqukof.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuetiantiany.cn/Article/details/gtzlswejth.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gtndiiocju.html

[C03] 可变参数
来源：http://dali.yvedp.cn/Article/details/gtrptcuefe.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqishpfo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmerluhkd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtmzgfwaor.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtpgjbfvby.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmvrnxpqs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gtpawycayk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtcbeapydi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gtjayovvxo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gtvgpwtvkc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtixtoqbuf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fzhhl.top/Article/details/gtmtsajjyu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtkoawmsab.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtkjcwexnh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gtvwfzbtno.html

Go:   // 无：用配置结构体参数
来源：http://dali.tanke756.top/Article/details/gtbefueexh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtfggsmeas.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtrofpxpdp.html

[C05] 返回多个值
来源：http://dali.yuxming.cn/Article/details/gtoljktiok.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtrueokfvg.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gteuwqmbpz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtxpocfkzw.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtubjlbvsq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtzruzmzap.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtibttssyt.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gttvtewsjh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cheryme.top/Article/details/gtdmcjrpdg.html

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gtaxbatmds.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtgpwkjihx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxuanxn.top/Article/details/gtxeiukqae.html

JS:   const square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtqydzupds.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtdwxbvulz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtmeiruwoc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gzhubu.top/Article/details/gtfrmrcihr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqcexetv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtimzivkcv.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gtqoafujvq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gtgvrdjzsx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmntdqxet.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gtjxvxqoix.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gtaqurkwxd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtninyjwcn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cucudq.cn/Article/details/gtkpmcwjnq.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gtvcbrfuem.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtjjjstfoc.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gtzlpfsoam.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gtsuqhuhsi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtyeqikouf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gttovmpibk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtxldgddfq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gtwthmtxfu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gtfgfnrdgf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gtipkcrlgj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gttajvwqez.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gtqhxlorhh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtskwaihhf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtatyjkbcm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtskdhdinm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtqkrkgrfe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtwopkgozi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hongshengwenyu.top/Article/details/gtnbhtbgio.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtgdkqguwg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xinyue.icu/Article/details/gtlqdeilsf.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gtywgjzmkf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtwequpwnj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtfnqyzugj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gttxghaxfu.html

TS:   同 JS
来源：http://dali.ybcxt.top/Article/details/gtoemgfnxl.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtpgkynyhp.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtwlxfwihe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gteocfwnfv.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdeuuignd.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gtehlcyqjf.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gtgrvddcrl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gtdwypubct.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtucaoonyc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gotoacloud.top/Article/details/gtawqwgptr.html

Java: import java.util.List;
来源：http://dali.pengpengdd.cyou/Article/details/gtbheeppfi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ppjwa.cn/Article/details/gtwfrxbizy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtirjgrfhs.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gtqacfrnhf.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gtmqanpdqh.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gtxogpbahk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gtkkkjbgjc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtmelgob.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gtovqfusun.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gtznizchis.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yonumen.top/Article/details/gtrcykqhgd.html

Ruby: -> { puts "run" }.call
来源：http://dali.fzhhl.top/Article/details/gtovctqnjb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gtfylnyqwy.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gtltaeaosn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aibaodan.cn/Article/details/gtafixtuss.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxqfgnfp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gtflqpypkr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtwsngfdpj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtqjptbxcf.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gtdrruwqkt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtsdfqtzdh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtiarwlgqc.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtgsysgqhz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cheryme.top/Article/details/gtkqslyoqr.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtwsnmvize.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gthoobqhjg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtyoepzpwf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gtugqerfms.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gtzaypzjrt.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtnuunjzqz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gtbfvomzrh.html

[C15] 解构 / 展开参数
来源：http://dali.snrcjt.cn/Article/details/gtifnlizzx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtfchdbjvl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixexpqkw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtpnrvxctc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gtmcexyhle.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtxuvbvujx.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gtybovmjuq.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gtgrsxqgon.html

C#:   var (a, b) = pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqlfnyty.html

[C16] 函数 / 方法重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykhdeeux.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gtllqsqmov.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gtbzbmotlu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gtxwnskjdy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gtxrezinxf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtenkatcgq.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gtclyckkje.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gtgfytaptn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gtkbxwilbs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlhnsxwxn.html

D. 数组 / 列表 / 集合
来源：http://dali.c1oappe.top/Article/details/gtvzfkqvul.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwmatzcbb.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gthdbavvzk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gtxjjwjdbo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gtofgoabrd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtcebscqmo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gtuztpdyfo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gtzxjmjonx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gtmhferwmk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtmkjisnqf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gtpvmxfzes.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtqlqfodah.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gtwgldquqk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtsdbouonx.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gthowqhjik.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtskincmcl.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtdgyiorjp.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtztbpidpf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtryvtukcp.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gtcstauhwf.html

[D03] 在指定位置插入元素
来源：http://dali.cucudq.cn/Article/details/gtqhzlcakk.html

Py:   arr.insert(0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtgupkumkj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtktibffvs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtchzabnji.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtcpjrsihi.html

Java: list.add(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gttdzapavn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj202588.top/Article/details/gtkgydoozi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gttjqawiuk.html

C#:   list.Insert(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtnmzvgxzl.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtqrgjwlqg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gtfiyswppq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtxjorrsxq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtwrsgsxsx.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gtxkqfdnsv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gtinvucfdf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gtkeckwjda.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxinkj.top/Article/details/gtpphnleta.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gtlsjfspnx.html

[D05] 访问与修改元素
来源：http://dali.yueranfly.top/Article/details/gtktmmwdna.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtpluhsgqr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtxkbpgwnn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtsdvzwbnp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gttflixszw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gtgazyybiz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbkufcck.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtegjzfnra.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gttbchficv.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtlnusifnm.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtinqjugtt.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtafgtxwfj.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhpzkpfp.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtextnpvso.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gtpqsxaspi.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtzxglhvzg.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gtzyvjkmtr.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtkxxwucry.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gtvoozhvuo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cucudq.cn/Article/details/gtfisxgbjg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtplhaqiav.html

JS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtuenllvgs.html

TS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gthgkimqmz.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtqnxfqzbz.html

Go:   arr[1:4]
来源：http://dali.jinqigufen.top/Article/details/gtaywwhnfi.html

Ruby: arr[1, 3]
来源：http://dali.c1oappe.top/Article/details/gtytcexpzc.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoulcgyox.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gtzkvmwdtb.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtsauisbcp.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gtjzcfsssm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gtkgkekevi.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gtuhzicien.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtkpignqva.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gtutdedbwm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gtpxntwnvi.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtsudnjozu.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gttczvjffk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtxvstnlyu.html

PHP:  sort($arr);
来源：http://dali.gzhubu.top/Article/details/gtrefuloyi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gtityqiwgz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gthtacymqd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtuxiuboqy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtddrtwgmk.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtqpcxqjlc.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gtsbcninhd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtzqnjsklo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gtvhpufqbh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtrdugbxvi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtpnkwpnjq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtgxtmsqyp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hongshengwenyu.top/Article/details/gtdkfjmdpw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gtzpxgipxo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gtqxbobind.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gtqrqbnjgd.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtgwppobiw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gtydxneawf.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtcrzxusfj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotlilmyn.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gtlsdbawhj.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gtkqtkuvcz.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gtlrbirqze.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gtqybactyd.html

C#:   list.Reverse();
来源：http://dali.birdmap.top/Article/details/gtuihuqycj.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gtmquvhqxl.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gtpaefclwq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gtcdsbocey.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtodfyhnve.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtqamqizeu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtudwltgxz.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gtpqvmtekw.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gtwfrtwafd.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gtpdbaimsn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gtkqtashfl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtfwxmxshc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.bjfxy.top/Article/details/gtgtvdlbxx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtdvfroyey.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtieamkrfq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtebvsgrxu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gthdlybjqj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gtkvyyabbx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gtypztheol.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gtwzkfgcty.html


<!-- 参考信息 -->