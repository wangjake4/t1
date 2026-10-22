代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtynzupuad.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gttvjxpnni.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gtdljumfwn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ybcxt.top/Article/details/gtdyiugjpp.html

[B13] 判断是否为数字
来源：http://dali.chenzaomai.com/Article/details/gtmtmcapyk.html

Py:   isinstance(x, (int, float))
来源：http://dali.shangyingyoupin.top/Article/details/gtqqgclhqf.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gtsharzbwq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gtkahwscal.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtimqtepzc.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gtjdghmhyg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhixingplan.top/Article/details/gtywelulhx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gtsyywcdlq.html

C#:   x is int or double or decimal
来源：http://dali.meibo888.top/Article/details/gtvnvfgzrl.html

[B14] 判断值是否在集合内
来源：http://dali.yongpay.top/Article/details/gthkxpzemc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gtggbnnmsi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xylfe.cn/Article/details/gtiegpxumi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtqcqwnhwa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdsjfmgg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtptqvuiyv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.vqdsnc.cn/Article/details/gtrcyztyhs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtomxwgddk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtaamxzrzd.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gtdubaqbgz.html

Py:   a and b or not c
来源：http://dali.zhixingplan.top/Article/details/gttztnysrq.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gtlymypmmj.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtizykwzqm.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtrztdfrpv.html

Java: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtlimhnzuv.html

Go:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtahdurjgy.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtlcyfrotr.html

C#:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtmhtbqcei.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdemdbno.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gtnnepwuqo.html

PHP:  if (!$data) { return; }
来源：http://dali.iojbl.cn/Article/details/gtinsykujo.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtwiadmvef.html

TS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtmuhoytdj.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtoduadxno.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gtrihthhoz.html

Ruby: return if data.nil?
来源：http://dali.jinqigufen.top/Article/details/gtjozgolis.html

C#:   if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtoobynmcc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtupvllrbh.html

C. 函数与作用域
来源：http://dali.redwolf501.top/Article/details/gtvrkpstpo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqkgsxhtw.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gthqrlwyxs.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gtuzbdmpks.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtqlhlcrpf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtfvpqqkdj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtochsylfl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchtpksjt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtwyngqjim.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aizwys.cn/Article/details/gtnugkvpkm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqvbywil.html

[C02] 默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtxitkrjsn.html

Py:   def greet(name="World"): return name
来源：http://dali.wangdashe.top/Article/details/gtcbjmcbob.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gtpxucyvdj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtnpiqiaay.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtnjlssecl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gtvnlgrecm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gtfflysrrb.html

Ruby: def greet(name = "World") = name
来源：http://dali.0kj1m.cn/Article/details/gtesgbrcde.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gtprsvbhze.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gtyqerawip.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gtynsqogwa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.birdmap.top/Article/details/gtfjrodfvk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwvbfeuua.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtyjkcswih.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoldtbebq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppysjdpg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ppjwa.cn/Article/details/gtxiylfzxv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gtnpndyucs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtmtdjrilh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.c1oappe.top/Article/details/gtynwddphx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtzpvgkuiu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtqwveijsr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gtiytbexvg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gtmuoeclui.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gtrjjtxqpw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtgkgizemm.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtkkkkpbmz.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gtxskmetcy.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtmrlmdgcb.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfzffcgi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yonumen.top/Article/details/gtlhmmghqg.html

TS:   return { a, b };
来源：http://dali.yj20258888.top/Article/details/gtbjkagiza.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gteaytyltz.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtgtihuelk.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gtjuuygmji.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gthiaqaaby.html

[C06] 匿名函数 / lambda
来源：http://dali.dianchejie.cn/Article/details/gtdlixvclk.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gtlftbuxpa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxuanxn.top/Article/details/gtrclxlvuu.html

JS:   const square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtlqckfkfh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtccemtjhe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtmehcyjtw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtjujksnxn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gttiroejqg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtgvzvolha.html

[C07] 把函数作为参数传入
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzmyaqqx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gtjzyhfien.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yonumen.top/Article/details/gtdrorqexp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjayklafk.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gtmxvvotoh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yonumen.top/Article/details/gtmudpqurm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.quarkkingdee.top/Article/details/gtfsqgeaji.html

Ruby: arr.map(&:upcase)
来源：http://dali.kuanghao11.cn/Article/details/gtrbhmtrtb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtuvaqobbm.html

[C08] 闭包
来源：http://dali.yanxiufei.cn/Article/details/gtcmqigeyb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gtzllarvrt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gthunfupbb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtrgzdycbq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtgtenkvwi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtdynozkwi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriwostaz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gtvfbefkpz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtplrcdpdq.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gtxarudtiy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtcpsqadrj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtzfkcoyra.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gtbuxwiwog.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtvxusumgg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtmurzkauc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gtedhoyykp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtvsqfwyhr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtnakroouu.html

[C10] 变量作用域
来源：http://dali.tian-w.cn/Article/details/gtxuqnfhtb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscwsjewx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gtyxzscbuq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gtvjzowqdq.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gtwpgeewmk.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtcylkxrfh.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gthomnyjys.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gtaixafpgd.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtttpryhhf.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gtzrronstj.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gtusgkluyc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtnlifevci.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtcbkfmrir.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtmngqcbjf.html

Java: import java.util.List;
来源：http://dali.smart0.xyz/Article/details/gtiazimlwb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtfbkeepca.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtprjbqbmi.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gtsvcmczlp.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtdlcxicls.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtsidwfzff.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gtiphyvpkt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtqznrddti.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtjguyqdds.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gtjiwkwdvp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtlmegkdiu.html

Ruby: -> { puts "run" }.call
来源：http://dali.sweek.top/Article/details/gtfgnkzvgk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtsfmgprum.html

[C13] 类型声明 / 类型注解
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwvhpcxi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtrafhogbh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtxxkvcgcz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gtyqftynzx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpzogxsym.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuiqlbpmr.html

Go:   func add(a, b int) int
来源：http://dali.chenlongwang.top/Article/details/gtkmhougpb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtklumxkgg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuxming.cn/Article/details/gtnnyjmnhy.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtofftdlyg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzqznqog.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtnarkipel.html

JS:   // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gthwwysrmg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zdqjudy.top/Article/details/gtwkzdpgxp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtblkururn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gtpakrtcwk.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtdqdihgog.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gtkujfuuoq.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gtwjpjzlzf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtuvsmdnfb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigufen.top/Article/details/gtfmlfnaek.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtvckuujqi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtejavonhd.html

Java: // 无解构
来源：http://dali.hnqzz.top/Article/details/gtdxgtkcbq.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gteaxecoma.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gtwrrntaiz.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gtsijqojze.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtrijpxjko.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtjkgmehsj.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gtrmmkhhja.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtmrqcpsrq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gtpqcukcnw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gtiwbrvkcv.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtsyacjsjv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gtbcpbzepz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswbhhswq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtypobryqr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gtmugvrwhn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdtznuxnp.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtcadpldij.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtlhrujbmq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtpxafgchl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtinxxnfrl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aibaodan.cn/Article/details/gtyfzxvmqz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gtlomjbkoa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gtobjgaobr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuulqwcg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gtdktlkdth.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtrhcoihth.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gtijijixet.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtrjtvcfbw.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtsfponhjn.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtwzyhhiwm.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtfkpodyua.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gtbyrjmebt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangshuangyany.cn/Article/details/gtzeifnbyk.html

C#:   list.Add(4);
来源：http://dali.meibo888.top/Article/details/gtndstrulz.html

[D03] 在指定位置插入元素
来源：http://dali.andypj.xyz/Article/details/gtgwowngzu.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtkgbjrrcb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangdashe.top/Article/details/gtkkpikclp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ppjwa.cn/Article/details/gtaslnjrij.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.mhx1999.top/Article/details/gtedemtqps.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtnnjdsqyq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtemznhpoi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gtmxftjznl.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfekuzhet.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtwezwygqk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuanzhike.top/Article/details/gtmctzqbzh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtwpzipyob.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gtkeiujhzy.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gtabbefeev.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gtpaexirpl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gtiqglenps.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gtjeiwpyiu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxuanxn.top/Article/details/gtxkvfaccu.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtazotpojo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtyjhkvjhw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtscncipra.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gttirboqrd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gtckuzvuey.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gthytlnrju.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtpvydqtgl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtlayioujr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtqwpcqyzj.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtdgfkllfd.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtjgbqqtpc.html

PHP:  count($arr);
来源：http://dali.nwbrower.top/Article/details/gtomzvtywm.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtddzykimx.html

TS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhsnehrc.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gtivmzgnyo.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gthnxvqizi.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gttsqwetfx.html

C#:   list.Count;
来源：http://dali.xylfe.cn/Article/details/gtlffjevtu.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtpeqyasvi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gtgnfyqtcg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtljddglry.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtcoamxsjp.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtnvxedaxh.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtokpifafx.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gtiukwrwij.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gtliczahfh.html

C#:   list.GetRange(1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtlgpqqrxw.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtdgyczsfv.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtacunnxzq.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtvyjfuaww.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtrdyuutrq.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtywfzpued.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamefaoiw.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gtyhjiendi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtqwwhug.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtwzwrwwoo.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gtqzefqivz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtutstkagn.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gtuquxgalh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtxbvxplvg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gtrovyznra.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gtkxucbdyz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtfxurpiad.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtkdioxakv.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gtyryrzgpk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gttsfojjht.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gtjcpcipoe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlaltkdr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtjwpxygpo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtthfgyids.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtfrevqodt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gtsgdqyrvn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtyohdkkth.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtsuuyrgxp.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqjvwgxs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gtfcgxgcop.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtdwzjumtm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuanzx.com/Article/details/gttekyopez.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gttqrrtnmx.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gtkjjqplgk.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkswggpl.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gtcvonjeko.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtvvtfeogm.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gtdkezfxmr.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtirweiwkc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gtsmlabqqi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtnbdwkpyj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtvpdyfzxd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtotnemkor.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtqerruljq.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtgmwrubzn.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtmwkiztuo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtoqkwider.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gtfynhlsai.html


<!-- 参考信息 -->