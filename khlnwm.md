代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtszaytxim.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtndwojbqb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gtbkhojhvt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dianchejie.cn/Article/details/gtwdmiwedf.html

[B13] 判断是否为数字
来源：http://dali.shuidangran.top/Article/details/gtzyircqci.html

Py:   isinstance(x, (int, float))
来源：http://dali.yongpay.top/Article/details/gtxrrehkwz.html

PHP:  is_numeric($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtfchakuzk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtppnmqrdz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtblluvumh.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gtuevpohir.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gttiaxafng.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnqzz.top/Article/details/gtgfdprnex.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gtnpjvigqx.html

[B14] 判断值是否在集合内
来源：http://dali.fzhhl.top/Article/details/gtivguxnoa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxehdncjt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gtzeazqmkz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtolxvsade.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtqxzifgjd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtivxbliip.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuanzhike.top/Article/details/gtpjyoflia.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtmjccdite.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gthrgqgary.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gtcumwzlfc.html

Py:   a and b or not c
来源：http://dali.daxiang520.top/Article/details/gtuqntjdzr.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gttqjtzljh.html

JS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtnzikbybn.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gttqcrxfvh.html

Java: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtsccovlpm.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtcyfjwlod.html

Ruby: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsujnmjx.html

C#:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtfjjaerdd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gotoacloud.top/Article/details/gtvpleltaq.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gtbpmnltie.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gtcswvghip.html

JS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gthodhxqsl.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzjkzoyh.html

Java: if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtzohvompn.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtguhwdikl.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gteincwqxc.html

C#:   if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtxcalyfga.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnnyqloiq.html

C. 函数与作用域
来源：http://dali.hywenlv.cn/Article/details/gtxetptaqh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtccwvuhce.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtxababmye.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gttbjnzewb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtvrrfvroa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtgbhhlrzt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtfymvrbdf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtijkgfmbx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtzleckhst.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gtazpdmibt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtepmnotvd.html

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gtnfvxbpwv.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtflmddjko.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtpuqswjlv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtnccwixvl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtydlnrmcm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gtmcembygh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gtwelvtlhh.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gtszjkewcm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtkjnarmwf.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gtkvlygdbm.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gttaoatczn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangdashe.top/Article/details/gtsnkswjjj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gthtbvemyv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtmbqkydmv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbvjntth.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtgonjnbab.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gtbghrahzx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yangfankeji.com/Article/details/gteozmeyrt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtpwpnupyd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gtnvlpfetf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gtliyenzve.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtskfwxetl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gtafhdhehz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnqzz.top/Article/details/gthnmqotnb.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gtsynxzvzk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gttzljccrr.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdextenk.html

[C05] 返回多个值
来源：http://dali.mhx1999.top/Article/details/gtkdzafjsb.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtfyjnzglg.html

PHP:  return [$a, $b];
来源：http://dali.jqgfzy.top/Article/details/gtavnisgzf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtvruzkann.html

TS:   return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtnanbpiaq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gticrdjvno.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtjrpgvrfv.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gteveuugcj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gthxgnmcwp.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gtqroahtki.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gtjeagpzmf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gtdztcjnra.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtaiiwpfxt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtnnyfdtcm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gtluegmysw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtcyxkwrpd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtunmyfwhn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtmegirmhn.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigufen.top/Article/details/gtvqzqaltu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gtbsjjajto.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtqiszqvbh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gtekrrcghh.html

TS:   arr.map(String)
来源：http://dali.gzhubu.top/Article/details/gtagcuqwmg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtglxzfane.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtjovmaihl.html

Ruby: arr.map(&:upcase)
来源：http://dali.haohaochexian.top/Article/details/gtaoauhpvb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.smart0.xyz/Article/details/gtqimkpkry.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtddcdlugd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gthcgnbotd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gtcmnswsqy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gthvqqzhbm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtofhrdewb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gtocialsvg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gtojcnhkhk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.redwolf501.top/Article/details/gtabxbnfeg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtyiejtovy.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gtkhxprxju.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtpynuhkce.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtivnnosan.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtdbrnxvrh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gthzkghnqh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtvcjqouzl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gtnphcaecw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtmsbxvusf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gtitiwntqh.html

[C10] 变量作用域
来源：http://dali.ybcxt.top/Article/details/gtuxfdqusb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gtghcpbnyq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gtadkxecyy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtrganxxtk.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtpxizgilr.html

Java: 方法内为块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtziwbqkhr.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxhbquel.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gtnhqurmha.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtmrcvzwnl.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowyleouk.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gtexlmwghb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yangfankeji.com/Article/details/gtciphgpfe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtbacpapgn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xziqi.cn/Article/details/gtjfrycags.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gttdslgpmc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ybcxt.top/Article/details/gthozivhvh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtbkxzksow.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gthcdmqtja.html

[C12] 立即执行函数 IIFE
来源：http://dali.andypj.xyz/Article/details/gtgnftbhuv.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gtuqivwxgv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtalwfdlkt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtsaxchfyp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtmddcqegy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbuugvbl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtjlxauuck.html

Ruby: -> { puts "run" }.call
来源：http://dali.fengsongda.top/Article/details/gtgdoxchqo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjcbxnrr.html

[C13] 类型声明 / 类型注解
来源：http://dali.ybcxt.top/Article/details/gtnlmwnpqp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtitrjxxmq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoeovovvq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtybxwspco.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtthfdlhbu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtinhmgynf.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtoinicozs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gtdktbcfyb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gtihryzcqy.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gtoqfxfhgx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoejttxuu.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtkbrftkuq.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtnmutitvb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtiiokdecf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gtalktpajm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gtbxhhiito.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtzgffupak.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gtzegeqooc.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gtjvqzsgwd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.smart0.xyz/Article/details/gtverajphd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gtuesgrzol.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtmvvxfnxr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gtsfbvntvq.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtmujueqru.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gtjyuoaqwo.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gtglhiulim.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gtpcxvmeou.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtzwtwfmdz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gtybvifhop.html

PHP:  // 无重载
来源：http://dali.hnqzz.top/Article/details/gtdnywaaby.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtgyaplfvj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gtlnacjjow.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtxhwefeyq.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gtqcdnkekj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xylfe.cn/Article/details/gtrargyxoe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guowangkeji.top/Article/details/gtswkedfuv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzjciskps.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gtwflomfiz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtchzqbavl.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtmftprugy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuxbsaiu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtfifnzvrt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gtioqrjiiq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gtuxavzgxq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gtvpfwglix.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gtqqavwvvj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxinkj.top/Article/details/gtkgljhksn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllpsgffk.html

[D02] 追加元素到末尾
来源：http://dali.tianlin.xyz/Article/details/gtfjibaldo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gtijidhxzy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gtikjdaivb.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtvuexuqkn.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtzzwuyeht.html

Java: list.add(4);
来源：http://dali.gogol.net.cn/Article/details/gtgqsstzrl.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gteqsvwugb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtjxxptlgg.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gtjoivkvrw.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gtqydzkekw.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtvdbpmcej.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gtxoydyxav.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqlndkkm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.andypj.xyz/Article/details/gtqgcbefhs.html

Java: list.add(0, 0);
来源：http://dali.yj202588.top/Article/details/gtgybztooe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtxgeweydt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guowangkeji.top/Article/details/gtuvjvulix.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtficeiyzw.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gtvnaunftl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtxonasfbt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtieygnjqm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnxiangtu.top/Article/details/gtvvqhlrck.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gtdgwyehsk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthprwfcdk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gtakuxqvkw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtyomrclyy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gttfcdvugr.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gtfkcdoqti.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaojonas.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtfksqvpxa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gteaaitvpt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhixingplan.top/Article/details/gtjenmxnve.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtsmqgllpb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtcteihnhl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gteiiqvyef.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzpdwwxo.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtcubjtetn.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtuylythvp.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gtyylnwsev.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgycesdry.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtqnqzocrt.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gthcldeykn.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtgwenleas.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtntqgnexz.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gtmdyuhanr.html

[D07] 切片 / 取子数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncajvrgz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gtonxknige.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtiluqsewy.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gttblbxbpz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtzakxzhct.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtkbtmupqh.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gtsvrviprp.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtqupnhnii.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtppbjexqf.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gtkmvsfzip.html

Py:   a + b;  a.extend(b)
来源：http://dali.c1oappe.top/Article/details/gtcuzorwbe.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtpejscodx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gttqqppcdj.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gtqtoomjbx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gtjafywdcm.html

Go:   append(a, b...)
来源：http://dali.quarkkingdee.top/Article/details/gtqllizgai.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gtsuxxmcxd.html

C#:   a.Concat(b).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtrjbjsxan.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gtpukpniqk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gthqgakxki.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtwjgzimnk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gtlptvhzpn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gtqquuxlth.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxinkj.top/Article/details/gtrzvtdomh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtaaahdewd.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtepengijd.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gtelonptnp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngrlpead.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gtapcrptnd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtfhkdqpzh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtqkhtknkx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtojgpkghq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gtgcsewrkz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gtclyxrbhj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gtekvtnocs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.feifeiyinyue.top/Article/details/gtmeirmcrn.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtfteczojv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtchlymjfs.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gtxwujador.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtuioftkph.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gtjrsjsphw.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gticpagrjn.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtqcjprebz.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gtztpbmahm.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtswiyqebm.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gtxfcktprb.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gteqivploy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtsnjmlncn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtyywvkcmn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtnymyemia.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gtpgpuipsn.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtskdwbzny.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtzmkrkhhm.html

C#:   list.IndexOf(x);
来源：http://dali.jqgufenzy.top/Article/details/gtrwmdswdl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtbfrvodvs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtjixlnquv.html


<!-- 参考信息 -->