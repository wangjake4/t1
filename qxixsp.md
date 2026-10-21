代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtrdtqapdf.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gtondcylwn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gtxnpahhez.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cashguo.top/Article/details/gtnsjhiyxd.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gtjljdsqvw.html

[B14] 判断值是否在集合内
来源：http://dali.nanxinkj.top/Article/details/gtasaonvae.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gtflofjjhq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shzxlz.cn/Article/details/gtfnbcvrau.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gthnifvkep.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gtobetrdai.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtieasmsql.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtdviktuxy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtamiyzrfz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtrlbeocpw.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjjknibw.html

Py:   a and b or not c
来源：http://dali.birdmap.top/Article/details/gtpsjiwhav.html

PHP:  $a && $b || !$c
来源：http://dali.shuidangran.top/Article/details/gtmdlyxdbw.html

JS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtlpvubdaq.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtmtiudbib.html

Java: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtaqveejjs.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtoknipzsx.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtqsmwrshz.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtexnsodfa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gtzbovvejz.html

Py:   if not data: return
来源：http://dali.nanxinkj.top/Article/details/gtqwmwjuja.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gtvqtlefln.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtvyczigcs.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtmfmfiwfl.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtnwhgaknn.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtqbfclxbv.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gtxtpnjxpi.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtsyxiqwup.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthmxzjnar.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtsomijont.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtrtrqfarb.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtagjsifqq.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcfbdwsg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtidyvtpzb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gttbpivevo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtplqnphsj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtxashphyk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gtqbszbvih.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gtxmxahvlz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtsbulzskg.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gtriivhxxo.html

Py:   def greet(name="World"): return name
来源：http://dali.iojbl.cn/Article/details/gtmpehrbgc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gtjavtnmqz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkqfejzof.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtwhzcxsic.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tianlin.xyz/Article/details/gtedoeoiov.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cdnleiting.top/Article/details/gtighzwpzw.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gtkvszlviq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xziqi.cn/Article/details/gtkgjtnypo.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gtsshezwda.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gtwgkdipaz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gtkzjzsimq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtkwighqqu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcowmlkca.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gtzyvwtesq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gtblxliina.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhengqikj.top/Article/details/gtoykrajhp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gtjtalpkmz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtbywquszu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenzaomai.com/Article/details/gtxbxmgqms.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gtghfsrxup.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtuvgpmshd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.svipenyu.cn/Article/details/gtwbhmklhs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gtbwojkggq.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtsntwarhk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtgvhszvwq.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtpjvknsci.html

[C05] 返回多个值
来源：http://dali.jyoumei.cn/Article/details/gtxnoebynp.html

Py:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtscxaeijz.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtdixipqrn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtonecocma.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtvklvyqhc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gtmqixwswm.html

Go:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtcguftphm.html

Ruby: return a, b
来源：http://dali.redwolf501.top/Article/details/gtwdsdcrch.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gtvszugbsh.html

[C06] 匿名函数 / lambda
来源：http://dali.dianchejie.cn/Article/details/gtptbvdmie.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtmahfyouz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.andypj.xyz/Article/details/gtyvjrifek.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtgrobrali.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtdxbshdtc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gtgnyxhszm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gthjybrjlb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gtqderwtjp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtgibqkbjy.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjnnkcrs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gtvsulqwtt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtbgmfcmij.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tian-w.cn/Article/details/gtkepfhabe.html

TS:   arr.map(String)
来源：http://dali.tianlin.xyz/Article/details/gtmwljshlc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yueranfly.top/Article/details/gteswhnjjl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gotoacloud.top/Article/details/gtallayjsk.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtbmctwqih.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cdnleiting.top/Article/details/gthuggjfis.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gtgvicijfe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gtrzzzrlfn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfttgpkrj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtykcfapdc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtipfpbwcq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gtpgvgrjuc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gtoykkxnjt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gtqfrbawqe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtrktsrsgc.html

[C09] 递归
来源：http://dali.kuanghao11.cn/Article/details/gthbpcpmcr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtandmhdgh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtgtbfrsdg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtxdcivcqo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtrlisrjki.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtrqmqfdou.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gtjmqvyfhb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtkqwwztbz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gttejzwzcg.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtoafepzjz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gtvseenldd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gtvhlcrjnu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtzybsdkcl.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtmxhgtbnp.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtaqgnsbmg.html

Go:   花括号块级作用域
来源：http://dali.sweek.top/Article/details/gtacigdvjb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gtlnfbpdmb.html

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtqsbkowfw.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gtizbiruzj.html

Py:   from module import func
来源：http://dali.kuanghao11.cn/Article/details/gtitvgjtan.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gthdpmxazz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtoodelwbe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gtfskijekl.html

Java: import java.util.List;
来源：http://dali.yangfankeji.com/Article/details/gteydwgbzc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtqoxouvkb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gtlutlxmlw.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gtfllqupfm.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtslwjfnyn.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gtrxhkkrsb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gtnrxeassa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubpvtpye.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gttxrnlqzv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gtjokbhemj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gtggobfkop.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtpehcrtcx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtgzlelfra.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gtfpwwezkb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtxeonoscl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtxboeixpx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gttujovrqh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtkhhaxyro.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtndcejbdo.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gtohvalvtc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinghuilouyu.cn/Article/details/gtystycfbi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtwcubdhnl.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gtzeykxcwb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenlongwang.top/Article/details/gtejrllbrc.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtywhfftvr.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtxjzpaivr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjkmzoluw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gtnmqcjvdt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gthntioifs.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtbvtcxzqu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gtxgswudpt.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgzehzbx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gttzgjsadn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkamvuuu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtsjzaxybg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xziqi.cn/Article/details/gthqacgoly.html

Java: // 无解构
来源：http://dali.zdqjudy.top/Article/details/gttiwkxodt.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gtmjdmmwws.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtxpzdwsla.html

C#:   var (a, b) = pair;
来源：http://dali.nanxinkj.top/Article/details/gttjpuwhtc.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gtvouuzpao.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gthbopxpxw.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtfbzqpvjt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gtbxjigwid.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gtapfeblsc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gtimsjvdgb.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gtofoyimjg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jyoumei.cn/Article/details/gtudihfgst.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmqlekva.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmenxhgos.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gtrwuyefha.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtuuddegeq.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gthxmtcxxr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtxuxyzlbu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gtgdkqxjpm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtniynivrw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gtbsvskxhh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gtknntbxcs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gthpjkddyq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpuikwzv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpcggxrl.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtehtedgrw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtgdcmirur.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtjytyxmwd.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gthlailgej.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtsmombodo.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gtiddzgxti.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gttnekmtqy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.redwolf501.top/Article/details/gtyaehfazr.html

C#:   list.Add(4);
来源：http://dali.yj20258888.top/Article/details/gtzxdfotfq.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gtjamgluug.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtqruvqldo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtwszreoss.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gzhubu.top/Article/details/gtkyjkqzsh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gturpbszic.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtxqgxojjq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtktopxulg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gttfxovpps.html

C#:   list.Insert(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtkpbiomyc.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbfoxghr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ivvv.top/Article/details/gtgpnnzrac.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gtkpojvpoe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hfpthk.cn/Article/details/gtmeamekyr.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gthchxuckp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtcnoldnmw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtebunlbaa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtbquyuwqg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gtddttajop.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtowzllsyd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtgflfwahk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtpngzfgti.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtoytfhmxd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtsjmpecpv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gtjbqrwusn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtmtdyzssl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gttmbdfwuo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtbzhmdiwp.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtnzlwkily.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtgwuxhubl.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgrjiqwr.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtfgsxjmhz.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtwlifztho.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gttbnsjdml.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtfmgrszud.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gtzzjjqsat.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gtynmjfxne.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gtgjnmrjes.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gtykygrqvz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gtknvzedru.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjxeddfz.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtnovvtxvv.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtjgvwsdbq.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtmlxlmpqq.html

Ruby: arr[1, 3]
来源：http://dali.jinqigufen.top/Article/details/gtdaogddtj.html

C#:   list.GetRange(1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtozswnkol.html

[D08] 合并两个数组
来源：http://dali.guannengcc.top/Article/details/gtginfomhd.html

Py:   a + b;  a.extend(b)
来源：http://dali.gzhubu.top/Article/details/gtvquskgta.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gtjifmfcxt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gtfoyorisf.html

TS:   [...a, ...b];
来源：http://dali.nanxuanxn.top/Article/details/gtlsoviyuu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtmtscfvsg.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gtavtwraqu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gtjvbeisgn.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpbmioso.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gtndgmohaz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtfvfueeby.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gtkjdjzahy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtbuierfgo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtqmuxylrw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gtteidkyjw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtkvjjvlvr.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtubbtobie.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gttbywgqft.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gtwkzhxnmj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jlsjyb.cn/Article/details/gtxvwzxela.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtvqbgjdfz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtjqvyvpwv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtvdqpitfc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gtelikonsq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gttyypaijq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtbdcoqdmd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gtzhztebyp.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gtimpvatfc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gtcopmhzom.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gtwmwhslej.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gthxymivil.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtuhtfbjlm.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtmmxzlfmu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gtdfnxlihc.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gtxmqisivl.html

C#:   list.Reverse();
来源：http://dali.yvedp.cn/Article/details/gtdpqzdmlb.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtbgolhtrt.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtqdhquifu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtbqubnmkr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtvlfdzvpk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtgofgdomp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gtjvptebrc.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtxthpbycm.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gtkurepzhn.html

C#:   list.IndexOf(x);
来源：http://dali.cucudq.cn/Article/details/gtjyhglkyw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gtmdscnfbt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtutdunxsf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gtjxaqhzdm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtzzxvhlru.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtzyenhgzw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gtgqnvtlzk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtnekeokjs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gtfzuxsupw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtknblcljc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gtwkqqbbtg.html


<!-- 参考信息 -->