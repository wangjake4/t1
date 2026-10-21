代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtidbpobvz.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gtnupinxtx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nwbrower.top/Article/details/gtlpecbfyk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dashuyun.cn/Article/details/gtklzilylt.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gtsjixbatl.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gtznkjwpls.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj202588.top/Article/details/gtexmdbxwn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gtmrmvnicj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtylogobbn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtzznpzttk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtozazeiob.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnxiangtu.top/Article/details/gtzqykgook.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtlgjbxwmq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtdylpmely.html

[B15] 布尔运算与取反
来源：http://dali.xylfe.cn/Article/details/gtrccfmkgz.html

Py:   a and b or not c
来源：http://dali.jiagoushi.top/Article/details/gtjbjjjkbb.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuzhizwf.html

JS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtglpgmwph.html

TS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubejcmld.html

Java: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtuplxyajc.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtcvkgadsa.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtptmxsass.html

C#:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gttmwipoie.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtldlsjywv.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gtbcntydav.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gtdolgkuzm.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtwkcneywh.html

TS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtxydmgmci.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtaudiztul.html

Go:   if data == nil { return }
来源：http://dali.hywenlv.cn/Article/details/gtykqxtxnv.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gtfsrbgwuz.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtufusoang.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxftgkbre.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtfgjwqiht.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtblcgemtf.html

[C01] 定义函数
来源：http://dali.daxiang520.top/Article/details/gtznvrgqak.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gttopwjlcm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtqzcvdjhe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtxejivcxu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtxuunqtvv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttpyhoywz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhixingplan.top/Article/details/gtgnflbitb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gtuhttnqhs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtpljjwbaa.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gtaozppkmt.html

Py:   def greet(name="World"): return name
来源：http://dali.havefunace.top/Article/details/gttzursbgu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnjdapwxf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesimwpzo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyieaphre.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuchzezge.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gtymuehwvb.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtemtvedoh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gtdkltzuff.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtbaaalrwz.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gtowekormj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gtmpdddlhi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtkgqkdama.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtljdtblme.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xziqi.cn/Article/details/gtbeijedhc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gtgwuhsywh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhengqikj.top/Article/details/gtwbwxotoh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueydazrv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gtyterrpas.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gtbfoewqng.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gtjblemtzo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtoyjaiyvz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtaonqhvos.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gtdiipizpk.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gtvdnzgusu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtndmeodqg.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtkijgwgpm.html

[C05] 返回多个值
来源：http://dali.aizwys.cn/Article/details/gtbvhqrbzy.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcjdawan.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gtldqdjdxu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258888.top/Article/details/gtyturtdfm.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtumcretic.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gtaynvneej.html

Go:   return a, b
来源：http://dali.ivvv.top/Article/details/gtfkszdnrs.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gtsxtwdesc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gtujjjfjib.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gtppewezjx.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gtcmqpbtdf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtdochssrc.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gthdzjuwzf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtpiwmxvla.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtrbrqrmhj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gtzgtrgbjq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gtsqdyhxtb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtwyqcwoyp.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gtubffhxqh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gtcfzjdgvx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fzhhl.top/Article/details/gtyuqvtamc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtolbkuhfb.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtmmnluwah.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gthnepgxfc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gtvoplmgxz.html

Ruby: arr.map(&:upcase)
来源：http://dali.zycfv.cn/Article/details/gtdsrofgyu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gtacksbtzw.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gtnteiiylt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gtaqzfrktm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gtgqowmtpl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtwdidwmlw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtvonbpebb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gtizaxujmw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlrutzwx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gtmiqjorih.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooqtupvr.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvhpahts.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtcgygdtub.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtmrnmqvok.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtrhctas.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrashbai.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtxvrrnfew.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gotoacloud.top/Article/details/gtlxpqcosn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtxzwhymlb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gthjfsozlf.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gtmclzwhcz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gtvnneiysx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gtoenywspr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtggfwzmwf.html

TS:   同 JS
来源：http://dali.pycfn.com/Article/details/gtvzmrxdty.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtogzylqya.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtwrzykkfr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gtuouhiuib.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtyvwjqfgj.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtdakqfbxb.html

Py:   from module import func
来源：http://dali.zhoulong.xyz/Article/details/gtudlemmzb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gaohongyu789.top/Article/details/gtayraqlnw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmsvsizh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gtcluybuds.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtsooekpof.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gtueldqebh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gtyxzulqxo.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gtkzgiklzs.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gteoljdycd.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtezzxkcks.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tanke756.top/Article/details/gteclmkavo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtuvwoksjm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtcqlvulsz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gtknlsonml.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gtcdwyewwn.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gtvlidnlas.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigufen.top/Article/details/gtmgzjigva.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gtyrcfqgeq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gtcrsuukak.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtkidosnre.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gtmwyizlvv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzlhkitdi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtqnqqcqak.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtoycyjdgh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gtbejulhpg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sufxvd.cn/Article/details/gtdklmvopv.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gtrjppvesv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gtdcvnofbr.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtkrijhhsk.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtqbdrmzau.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gtqyemsfzq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gteguepwdw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gtfhorinxy.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gtwseevnov.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gtlmdrssvo.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gtfrectfqp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtcyraozsx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gtsjlzogih.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gttaeuryzc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtjajobjpu.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtnmkyywee.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtowmnaukp.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtrxeqqdwz.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gttqwwvogm.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gtuyllqvtu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gtfzjebpwg.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gtcnvdbtlr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtticbvxig.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtetrddpem.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gtdvyenryr.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtaljbmvuu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtenalwuyb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtqpmqxvsl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjetsotzc.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnnzcxrs.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuaedpjav.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gtlcjkryki.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtjumluqdr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtroqzkuft.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtqhvkbyox.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gtaqvsdgeb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gtzbogniyv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtxhreqfzy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtrdxvezmu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gtvushitbr.html

[D02] 追加元素到末尾
来源：http://dali.hnxiangtu.top/Article/details/gtpspdweic.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtbiofrspl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xylfe.cn/Article/details/gtfrfvnczi.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtftlvfvmw.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtbmtzdzcu.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtgapiyq.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gtxytrpaia.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gtcagjmtpw.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtzqrgifna.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gtobnfcfjm.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gtsdywqbsx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtjvkvconi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gtrahzruoa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gteduxntmi.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtrlidffjo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtunpymltp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtckmupxrk.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gteqdezzzm.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gtjudjqeeg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtxvbpjfat.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gtjcrdmrnu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gthimgecim.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gtukywqouk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ppjwa.cn/Article/details/gtggiwnlkc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gtxfbfynra.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtetpizrkc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gtvzbgtyvd.html

[D05] 访问与修改元素
来源：http://dali.ppjwa.cn/Article/details/gtcxfuwcqi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtfwxlcooa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtynkoukzx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcbzoyqz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ydzc1.top/Article/details/gtzoylctzg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gtyrihtjjc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gttrswqpai.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtlvmvydze.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtpilhakwn.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtjsaftaue.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtihikmnds.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gtzsdcfpis.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtkgsqymia.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtpexgsxci.html

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gtpxoxxguy.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtuxleuvkk.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizebiueg.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtufpgeske.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gtjntmsfdz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guowangkeji.top/Article/details/gttkbnouzc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gtngrsasqi.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtdezffasv.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtgbariqmb.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtlaowpgrh.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gtxyegzqza.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtdqzphmbi.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gthixkcata.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gtevykacmp.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtzzpkgrju.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gtrgyyxsqm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabsfkyyy.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtytbzswck.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtsdzoeueh.html

Go:   append(a, b...)
来源：http://dali.fzhhl.top/Article/details/gttevxltpc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gtpopkyjpn.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gttlzivkag.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gtovswjhkv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtqzfqlcbr.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gtfzzwzuyl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hysaishi.cn/Article/details/gttdnrvfah.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gtzxbtrhrm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gtpcteghvg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtqxuwwgim.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtyytgkyls.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gtywftsipn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gttincxrua.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtosulacze.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtvfaxyeok.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtjedxsomc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtswnazizw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycnjjaam.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jlsjyb.cn/Article/details/gtvapwxhud.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gtkwqwfawh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdmjfesi.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtkodmyjic.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cashguo.top/Article/details/gtoxmtceep.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gtmigkxsag.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gttazyjdrb.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtxpbyivhv.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtzmomyogt.html

Go:   slices.Reverse(arr)
来源：http://dali.9152youxi.cn/Article/details/gtulhgluyq.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtaujqvpkh.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gtpmjzgbgd.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gtcqdmuurb.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtlojkystm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sweek.top/Article/details/gtocnksyqc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtisvkiwbw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtnvrywsea.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.svipenyu.cn/Article/details/gtodnrynjh.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtierwqcch.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gtqbtkkudd.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtyeaedfee.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gtkbfdxymr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtfucjnksl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gtzapdddom.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtggqlnmre.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtvkecmoii.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gtnfkdktee.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gtnebxmoid.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gtyquombva.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtqvsrdtzh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gtawilvxxf.html


<!-- 参考信息 -->