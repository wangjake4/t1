代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtqnazowpj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gtpknnwpzd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jiagoushi.top/Article/details/gtltukacfr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.redwolf501.top/Article/details/gtrdeqdoss.html

[B13] 判断是否为数字
来源：http://dali.fengsongda.top/Article/details/gtbsvryzls.html

Py:   isinstance(x, (int, float))
来源：http://dali.kuanghao11.cn/Article/details/gtnkwvwqkh.html

PHP:  is_numeric($x)
来源：http://dali.jqgfzy.top/Article/details/gtemubfllx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtxwneghyn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtradmehvg.html

Java: x instanceof Number
来源：http://dali.vqdsnc.cn/Article/details/gtinxqvxyz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gotoacloud.top/Article/details/gtebtiirrq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gtwgbxhwcb.html

C#:   x is int or double or decimal
来源：http://dali.yangfankeji.com/Article/details/gtyggnsrms.html

[B14] 判断值是否在集合内
来源：http://dali.zhixingplan.top/Article/details/gtxhjlupck.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gtpowlueqj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gtueyzcknq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtizgrffzm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfoftjaa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtjqjnykni.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gtptyhydrg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtnsujsoog.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtoxyhkyxz.html

[B15] 布尔运算与取反
来源：http://dali.chenzaomai.com/Article/details/gtmolsnxsh.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gtuboyushq.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gtqkjyfjme.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gthxvgxngu.html

TS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtkmqshdat.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtiuvmevzg.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtjopwlrya.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtuookuauh.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtnivchxvg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtuilcswmu.html

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtgzgtle.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gttyhnkltg.html

JS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gthlzgiicv.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtdngnnszo.html

Java: if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtlgyphffq.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtxnwrlwex.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gtrkyitrwx.html

C#:   if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtvunkddeh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtpqiqoiyo.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gtmiupaxss.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtajhplxdy.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtauenzttf.html

Py:   def add(a, b): return a + b
来源：http://dali.zycfv.cn/Article/details/gtzkghjrrt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtofizghvr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtbnnaophu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtuztjqumq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gterfxqsde.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtiizybiey.html

Ruby: def add(a, b); a + b; end
来源：http://dali.feifeiyinyue.top/Article/details/gtclizshgj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtcdnyaetx.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtltsanhyl.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtirjvitzg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gtcyhbhnqx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gttcujukmz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfytsfchb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gttpfsgegg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtxswoqxkt.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigufen.top/Article/details/gtbbypvdmw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtzywyrgct.html

[C03] 可变参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomvbooug.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gtxbaicuse.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gtbjsreoeo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtdpvtftco.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtzchklmfx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ehwqpu.com/Article/details/gtiiuopdme.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gtbhhbqhmc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhongyouzk.top/Article/details/gtewlnzpnb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gtozrbwcuv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gtoiihsmlx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jianghu66.top/Article/details/gtzrqipmpl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtmifrfhvj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtwrcxst.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtwnajbfju.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gtokrokinl.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gtpnlucckg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtvsgkamrs.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtxayfigxw.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtbnshfmhu.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtgdkyezaw.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gteawmstsn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtkdzfucer.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gttgufzwdv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gtsbscsooe.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtbjhmzwjp.html

Ruby: return a, b
来源：http://dali.hysaishi.cn/Article/details/gtebckcqbz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gtmbtzjhef.html

[C06] 匿名函数 / lambda
来源：http://dali.daria6918.cn/Article/details/gtezighsno.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gtokmsejyb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gtsfrxqnzx.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtwisjusni.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtbhnhmwnd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258.top/Article/details/gthgipqvef.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.birdmap.top/Article/details/gtbspdwiro.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtnmtrvena.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtzkiseqsl.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gtoymddzwh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gtzplnwvkd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gtewnhdiaf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.andypj.xyz/Article/details/gtysuhyezd.html

TS:   arr.map(String)
来源：http://dali.tianlin.xyz/Article/details/gthxfhucob.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gtdytsjuiy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtghdcivxm.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gtjymwqiws.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gtblbzwrwf.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gttjosqikb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gtoedkyxht.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtywxywrbk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtqxerjeaw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtgbxdhivr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gtynyamuex.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gtqfnuaebh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gtczbinlfl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtqwflvslr.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gtjzzqasbb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtfqvqlgmy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gteteyrbmp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtrcsnzxos.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtujardzat.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxrdnpct.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtybvjqvot.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtwbykpich.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwulsdok.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gtvhvgeeca.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fzhhl.top/Article/details/gtkzzvvslz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gtrefejvsf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gtjeslzchp.html

TS:   同 JS
来源：http://dali.ppjwa.cn/Article/details/gtbvolplpb.html

Java: 方法内为块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtbgbccbfd.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtjwmudqdp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gtqcbldekp.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtgxxcjgnv.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gtmwlymoqk.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtebgoynzb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.meibo888.top/Article/details/gtiapyasnq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtobmmtbhf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gtjdylwzjj.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gtcspfstpc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtddizckjs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gtufnwqsze.html

C#:   using System.Text;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvoomuua.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gtkbuceagw.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gtpaeftuig.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gttbfgjgvy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtstejqfab.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtphhnjxny.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gtwepclsqs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtvkiqleyk.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtlbwkbqrl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gthpotilza.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gtlwhdezqn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gtifuynpiz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtnyqidzke.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gtovbrazou.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtiosejvhe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtvmkwdyfr.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gtkdshlhnd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gtxultmiqd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelkvtcsm.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gtpmedtzco.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gtufvdvqto.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtowxgpoie.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gttxysngrm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gthozqnsfw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gtkphcpgdw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gtmraaplyc.html

Ruby: # 无泛型
来源：http://dali.0kj1m.cn/Article/details/gttebczluv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gtatbxduvz.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gtjkbwrcut.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gtzdqqtikj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtzgobdono.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyiftxyxc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtclpkhwla.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtlxekmykh.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gtcetgyjbc.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gtzgieuwki.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtynbcfrhd.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gtqhetnymn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtjtdoqpao.html

PHP:  // 无重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasvhbqey.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtrpvblzur.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gtpmumyhle.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gtvectleae.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtwrqckmjv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtllicvlea.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtvltlozcs.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkzkospzo.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gttgdkklio.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtakccwuil.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtpiyexkkz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtsjqzwmge.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtqwfdvkfg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gthwjzeitk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gtykyljtkv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtfosptcxr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gtxwbiljlv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjgjiwne.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gtwwfxayzm.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gtfjzltkza.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtnwlluoie.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gtjlnlqbwk.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyahyyxv.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtczircxes.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gtiwlppbhy.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujoqkzgs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gtpjfatrfq.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtipkqbpjc.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtqejuyufo.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gtrypahwsn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gtiryrjupv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gtsriscgok.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtcqldprne.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gtwjczwjjw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gtkeiupslw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gtrmmnjcfo.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmaiwzwv.html

[D04] 删除元素
来源：http://dali.jyoumei.cn/Article/details/gtqhltpbbi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtnvqsnfgc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gtzzmcnnpy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gthtlkpvzl.html

TS:   arr.splice(0, 1);
来源：http://dali.snrcjt.cn/Article/details/gtvugwnacg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gtlsonrpew.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gtcblfijdh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtswqsstdl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gtzddbsibu.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtyroituvz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtnbnadmyk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtvvxojfic.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gttghbdbiu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.birdmap.top/Article/details/gtbfpyqruc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gtlenaczra.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtsrrwnhgt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gthxbsunvn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtszgbitga.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkryrttqq.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtfldngjlq.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtrangaieu.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtpbgofxms.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gttbrrlhzy.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gtmghljgnp.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtoaunxucw.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtotpxefge.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gteolbdtag.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gtfrwtwsfs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtndfpxhfg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtlixknptm.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtviiqgvkc.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtsiixxdxg.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtgkbgpyag.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gtmrxnepkj.html

Ruby: arr[1, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtnavzkciy.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtbwqxhdcv.html

[D08] 合并两个数组
来源：http://dali.fzhhl.top/Article/details/gtdjfukswh.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gtxkozkwcx.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gtdbomlfak.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gthsxieiug.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtdptoawxe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cdnleiting.top/Article/details/gtsnwirmqx.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gtvhptasqy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gzhubu.top/Article/details/gtcpypozoz.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtggaktjdi.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gtgnjyonkm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtopbtrgvk.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtdpabkkcv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbffrbmjj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.9152youxi.cn/Article/details/gtorrlvygu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gthtrrictj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtumaugsdg.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtuozagjom.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gtfpbvtlau.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gtckylrfhp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtrucirgaj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtwhvmijkc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtjuyvzaly.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtuflwmqar.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtxlnkwanb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gtqkrwvbem.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvquyruif.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtczeopxng.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gtvfffrcyt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnirbuhmj.html

PHP:  array_reverse($arr);
来源：http://dali.jqgfzy.top/Article/details/gtybmohytl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtgcubnidc.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtwxruvktf.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gtykmnzhkn.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxqfxflu.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtajgecvmx.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gtqidadhci.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gtegcsyxld.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtorkdcvni.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gtaertqcoh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtxdyhincp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gtcsypfsii.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtmqdkqrhc.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtuwbexwvz.html

Ruby: arr.index(x)
来源：http://dali.meibo888.top/Article/details/gtmsphrpwi.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gthpiolphd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gtnvriduxx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtgwsprqdz.html


<!-- 参考信息 -->