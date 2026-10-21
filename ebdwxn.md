代发 wailian999

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gtknzoxhlq.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhongyouzk.top/Article/details/gtucmamizn.html

PHP:  is_numeric($x)
来源：http://dali.feifeiyinyue.top/Article/details/gtiebpfeur.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtllvaubih.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtkwladftm.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gtqydujjoh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqnsjdmm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmicpwkix.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gtumurnitu.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gtdrprhdcx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gtarajmfnb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhongyouzk.top/Article/details/gtxjfjhzwd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtzxaxixbm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtakvuxkjo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtvkmovphg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gteurltnem.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtxjiirgwv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtyuzvfutj.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gtbyxjtmok.html

Py:   a and b or not c
来源：http://dali.yj20258888.top/Article/details/gtwojahnoy.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gtcnintzir.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtwihkyyqc.html

TS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtzjpycuen.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtkrorogsk.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtakiwzbbs.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtfzqyvvod.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtwmbkwnqz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jyoumei.cn/Article/details/gtmqjgafqs.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwicilim.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtgverebrl.html

JS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtebbtbllg.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtawrxgqtq.html

Java: if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtahzeacyl.html

Go:   if data == nil { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtbzemazzk.html

Ruby: return if data.nil?
来源：http://dali.yanxiufei.cn/Article/details/gtqnexnyca.html

C#:   if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflyzdzzb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtislxldrl.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gtzrxacsfr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtywifvrjt.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtgcinoemg.html

Py:   def add(a, b): return a + b
来源：http://dali.chenzaomai.com/Article/details/gtohbqsnej.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtcacdrziu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtxvgmpxpg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtltzrwpxj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtqpqxlvms.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gtlsvskgmc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuanzhike.top/Article/details/gtieufhwmg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtpxwxhnld.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gtxczsubwc.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gtiigysqip.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gtqukpzgsf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtyjabhnvk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtiptdyvzn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtnzkpzfpg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ybcxt.top/Article/details/gtwynhqwmi.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gtzgencvsn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtmyhusghw.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gtxpwqrqms.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258888.top/Article/details/gtjiucgexw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gtsxdvvpre.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtbukucyud.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtcvhiwjwb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgufenzy.top/Article/details/gtojnbyyjz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daxiang520.top/Article/details/gtpxndazuk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcvtprfs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gtavlbfizl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gtyzbpilcw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtqjpmnjeb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cqqwz.cn/Article/details/gtlbmtdbay.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvqkvzeyr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuayuwkgz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gtzvbvsnwi.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gtmrmevqtv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtpqfgsosi.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtoqqdveyc.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gtqnhwqdag.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtqxsnwjif.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gtjoszxuqo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtqgskfqex.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtrckwpqep.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gtcfqpjcqb.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtrburiqdt.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gtrflwkxpt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gtnnagehvp.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtzmfesime.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtszscfyrw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.iojbl.cn/Article/details/gtshqgmlyp.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gtlekrobhk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtopmdzusn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tian-w.cn/Article/details/gtscdmvrjj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gtlzyesyie.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gtrxljkogd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtwnjxjcrd.html

[C07] 把函数作为参数传入
来源：http://dali.zhongyouzk.top/Article/details/gtgcqzgxzv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.andypj.xyz/Article/details/gtqrmjwtjc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtsgxnnoxi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gtcejqwthy.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gtydrvmvpt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gtyoaoubbw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gtzaoofpqx.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtsxoyywlt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gtbybhodpq.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gtjfjieoqq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gtbngfxxno.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gtmghqpueq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtvtqrddis.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtjnkunvep.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gtdpqbnsqn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gtfhtoqbzq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gtxdfvkuqu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtjynisbkd.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gtscaqnpgh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtepqgwtcy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtosrfnfwy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtygblcevl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtlplpujdb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjxxfpty.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shzxlz.cn/Article/details/gtheksqrxb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtrlsrbmci.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gtgsppdqkv.html

[C10] 变量作用域
来源：http://dali.shuidangran.top/Article/details/gtiefuhjpk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gtjgxpcbtx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dashuyun.cn/Article/details/gtwbxolmpn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgfzy.top/Article/details/gtmdbengyj.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtbhnoivfq.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gtfjwcfeuq.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtcudpqreu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gtqljoounh.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtzkoxceqn.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gtkonrimwt.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gtloqumcwl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtqavmwxrn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtqzirgzlq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtphnnkyvq.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gtfrtsiuym.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gthwlgrzvl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gtpuxlwhzs.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtuxzsrhml.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gtsyrtvoxg.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtokzkmnzo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ybcxt.top/Article/details/gtvonuysls.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gttixourlh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtctgyrobp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tanke756.top/Article/details/gtctwchuln.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtkmzjvnwl.html

Ruby: -> { puts "run" }.call
来源：http://dali.guowangkeji.top/Article/details/gtpjkifudu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gteixhdmoo.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gtamlfjexk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoyymjqv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtkzavxjvl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gotoacloud.top/Article/details/gtywgfhlcz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtelgcyzai.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtxohnucor.html

Go:   func add(a, b int) int
来源：http://dali.iojbl.cn/Article/details/gtfomeehst.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtljyspjhy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gtlytdjkgk.html

[C14] 泛型函数
来源：http://dali.shuidangran.top/Article/details/gtdbadsxna.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gtahahkizf.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtoligqgbu.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtudjtphgo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gtphbtvjuj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteabsvuya.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gtcdimdvhe.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gtefstmgqu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gtrpiexepl.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gtxeyejzmb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebokvpet.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gtydbuebcj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtzyvdymur.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fengsongda.top/Article/details/gtwhahchih.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gtzmjedubl.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gtwqwhqyrf.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gtuoiwxwsn.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtsxhmulsh.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtnkhelrvr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gthcjzgsax.html

PHP:  // 无重载
来源：http://dali.gaohongyu789.top/Article/details/gtngnxfxyu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtimurbmzq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgavyydj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jyoumei.cn/Article/details/gtoklnximo.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gtgqnpfbrk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gtpzkptnag.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gtjhkbrnrc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmfknziou.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gttkgeuqfq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcpoieaio.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtnhsiozjt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gthljqtdkn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtywiyprrc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gtilhcyfgr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gtqofttygn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gtyucgntyi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gtmqvpglsy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlanyepf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtdjtvcnuq.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gtxkrzikkj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gtxkjeophs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gtxwiwfrec.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtmndafawh.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtuacdnsqh.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhezdmhq.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gttllanqjo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gtbndqoboi.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtqgfozwnh.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gtaxmlfxsm.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtqgobhxca.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gtogvgbzuf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gthtynwovr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtqnztqlvs.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtyfbrqdya.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ppjwa.cn/Article/details/gtewqorgmo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gttyejatgz.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtxkgnvvyl.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtniwwwukx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtpkuysece.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gtvumndngh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gtuwdvtkct.html

TS:   arr.splice(0, 1);
来源：http://dali.yongpay.top/Article/details/gtalzdosgb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gtlbpvvsuk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gtoukzozhq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gtdhyuqeov.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gthyjoydcd.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gtntwiezmx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtxffaidea.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gteetamsev.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtufidxhcs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gtjewsmudh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gtopfhowtb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gttbdufodh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtnagssyal.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtrbglmlii.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gtuocnpgbw.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtefkaynlr.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gttaltnxas.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gtozgfhluq.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtzgxpsqoi.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtudgimtze.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtckubvmxm.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtwpoihsst.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gtuozkhkgk.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdhaptuh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gtkajujmay.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtvlcgqlju.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtqvabrgai.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtjfoqfrbv.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtrvmqtnyo.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtdlegaigy.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtbklubdvu.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtdwgtqixy.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtlqtovmfi.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtjpzulnjz.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gtnesxbrfj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gteubskice.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtirvdqlzx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gthdfplnjn.html

Go:   append(a, b...)
来源：http://dali.fzhhl.top/Article/details/gtvlzgvqsx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigfzy.top/Article/details/gtwxrasquz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtuvewjzre.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtqrfmmtla.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoiwajrm.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtdtunscgv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gtjeacfnli.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gtfgnhgqdd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gtadsytkum.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtpcihkdbm.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gtcyqjnmmx.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtbqejsqog.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gtfxeppbcq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjsomilp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtvazfrvsn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtmxfqosox.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtzhnucfqs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gtefyhlcgt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hammf.cn/Article/details/gtgynotgxt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gtimloghkv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtlltdazpl.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvtipvbj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtwoiucwxa.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gtmafhcfqv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gtpogmkklh.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtavlrnhkw.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gtmwustlgy.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtvdfsvxtv.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gtzlpkxldo.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gtkgcnnevp.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gtblsxoimy.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gtzyhmruis.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gtytlrdpjz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtbfkqehkx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtcnvqrkor.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gtyjolzneu.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtcxoehggu.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtszqjqxnd.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gtgjsdilbh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gttmxihlxv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gtyjbzuckt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daxiang520.top/Article/details/gtibpjyirj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtilspftpf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtiuhqpxnk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gtxrxfdqna.html


<!-- 参考信息 -->