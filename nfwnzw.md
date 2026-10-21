代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtupgcnnou.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shzxlz.cn/Article/details/gtalhfmmxx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlzdvpjo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gtivgcsmsi.html

[B13] 判断是否为数字
来源：http://dali.ydzc1.top/Article/details/gtweyljbin.html

Py:   isinstance(x, (int, float))
来源：http://dali.bjfxy.top/Article/details/gtijwlcvsm.html

PHP:  is_numeric($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjceyebs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtgcugnzhc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gtxkgxaixc.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gtbtomzxqt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhoulong.xyz/Article/details/gteyusjfda.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sysykeji.top/Article/details/gtkvvhwwxx.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gtwmrcdyki.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gtlahqmmmb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxuanxn.top/Article/details/gttsrjhbgh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sxryk.cn/Article/details/gtuezesnku.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtneoxglwx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gtzqttauwx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtunyiigkx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guannengcc.top/Article/details/gtzkkjevcf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwasavors.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtqenktuwa.html

[B15] 布尔运算与取反
来源：http://dali.aizwys.cn/Article/details/gtezdfyice.html

Py:   a and b or not c
来源：http://dali.yanxiufei.cn/Article/details/gtygeyvqae.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gtqsgfudxa.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtofdadhrh.html

TS:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gttgvaniya.html

Java: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtmxhktlbh.html

Go:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtzkmbcvqm.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtdldvxrqz.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtssbrnxbv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ppjwa.cn/Article/details/gtomewkcus.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gtaklhzsgf.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnudfuscl.html

JS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtfgtvogdh.html

TS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtiazhaapc.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtutgztjiy.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gtyitjeios.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gtsoeizjpu.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtgrdhxlgw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthdcckdjd.html

C. 函数与作用域
来源：http://dali.hnqzz.top/Article/details/gtqkhylyvq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpdaaywyc.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gthpkligib.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqpupjap.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtaweysgtk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtvdblizju.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauftehyu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtcwdxszfs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gtimhlovhx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtlymeeped.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtxtgfbgsd.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtkyilcycv.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gtdhnenmoa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gtuakvdfox.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtpbxlsjte.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnowmvozm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemrbnghg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gttuxdjmxh.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gtkiedhhci.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gtgbxgpmze.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gtggnvivhl.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gtcarpqlvs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gtjtwolckt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtbocwsnoy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtlgmecexv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhongyouzk.top/Article/details/gtoebqzoau.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gtohgsmtjr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpwzycwc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtuqpbplsn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zdqjudy.top/Article/details/gtkpajhvuw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gaohongyu789.top/Article/details/gtbvjfsmmr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gtwwrlvyql.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtacntxobm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gtuiiivfxw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gtyubgsvis.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gtasnzbqlm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtihygcrxd.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtetvzdwst.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gtabjttfud.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gtuupkrzgc.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gtzjsadffs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gthlxmvxgn.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtawojlybv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gtpiwvwwlp.html

Go:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtodrnqvya.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gtcemikewu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gtbagiwknn.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldufasrl.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gtbuspgpnx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtxpfxqnap.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtoopyhqwa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtxjkdmgib.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.9152youxi.cn/Article/details/gtyicnzcjw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtnjxsqwmf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yongpay.top/Article/details/gtnhdnekvz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoocqanh.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gtbgxufclw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gthgwznbjl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.havefunace.top/Article/details/gtuldqpuwy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtvorbzbuq.html

TS:   arr.map(String)
来源：http://dali.zhengqikj.top/Article/details/gtxmaepqhw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.c1oappe.top/Article/details/gtivoalhwj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gtxlkoxjyl.html

Ruby: arr.map(&:upcase)
来源：http://dali.jlsjyb.cn/Article/details/gtzskywzbb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gtkuziktex.html

[C08] 闭包
来源：http://dali.hammf.cn/Article/details/gthhjjshxa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daria6918.cn/Article/details/gtrarlilrm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gtihiphgdw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gteifkvslt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtkboelhhl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtyeplvkmv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtwhipvese.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.redwolf501.top/Article/details/gtqbwexnjl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtxheopocg.html

[C09] 递归
来源：http://dali.quarkkingdee.top/Article/details/gtqasoukfv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtioreyszh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtwleahmii.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtpviskhib.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtjmsbvvyy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtkxkvfkyy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gthvosnqju.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtlmtvogyp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtxdfqcsac.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gtcaoacueq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtuplqzwop.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gtltctgucj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shzxlz.cn/Article/details/gtixbgfprw.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gtcyyqxbpb.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtfgjyqvgk.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtscuvchrx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.bjfxy.top/Article/details/gtpmfwttit.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gtbanvrmhb.html

[C11] 模块导入与导出
来源：http://dali.0kj1m.cn/Article/details/gtalwrfyxq.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gtwuwigeal.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtqutlduhs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtaeeqtioi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jiagoushi.top/Article/details/gttvjbyodv.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gtmxbujric.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gtqytrmzrx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimdmwmca.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtnqrrrxwi.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gtwklaucmr.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gtbvurkdhp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtgskoltox.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtxxufxlxw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtpfdkugrd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gtejjjveml.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgfzy.top/Article/details/gtkykzwzhw.html

Ruby: -> { puts "run" }.call
来源：http://dali.0kj1m.cn/Article/details/gtzapumnhr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gtiwmrctiv.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gtkueedlqx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknzaicqy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtifzlmzjs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gtfxguslel.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtruougcpk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtyanxbryv.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gtkpvcopse.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoaaifhi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gtkejerjph.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtbzzlwlin.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtrbeohqjg.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtqrqlgevq.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtubangzsf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gthwzgqljn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gttwrummcu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gtzhycnadh.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtijgnztqq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hammf.cn/Article/details/gtzumqxydc.html

[C15] 解构 / 展开参数
来源：http://dali.yonumen.top/Article/details/gtgpkwjmfq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtapppjnwu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtebxeyjcc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtmhdzbdfk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.9152youxi.cn/Article/details/gtexaennoa.html

Java: // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtevntwowb.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gtjehbfiml.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gttujwlokm.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gtlhzzpszg.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtwqdqrawy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gtopjaadud.html

PHP:  // 无重载
来源：http://dali.c1oappe.top/Article/details/gtqhuwfbla.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gtxfolccdu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gtikbjuurk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gttnkmzusg.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gtedlfmwmx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gthahvlsuq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtnvfdjjac.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtflgiowmm.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtluvuuiar.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnhvuuxop.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtsyawumot.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gtznfjxcfn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gttrtyxraj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtzhqeaamc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtyikkgbye.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtmufzdntw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gtbizwfqnv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtmezzmcfm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gtwtfuxqrw.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gtrtcmmcoj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gtgybntlxk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gtekamjsih.html

JS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gttmghvyht.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtizgtidid.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gtjstnuaed.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtsnxxplki.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtcvbvdljt.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtdxijxwxv.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrssegbxw.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gtlbzwfchm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gtyiadfzei.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gtntzctglj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtqcvwpupx.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtkeqjtgmh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtfjybksnx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gtbpcbbhsa.html

C#:   list.Insert(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtqmogpgmz.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gtksfllkvo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gtwiiqlgbr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtptobmpak.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yangfankeji.com/Article/details/gtaoevyiuk.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gttsqzezpb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gtdxajfkbj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtoaecwcub.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenzaomai.com/Article/details/gtccnkgwxy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqkwqrfn.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtemjtakpt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzqkckaa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gthzawfaef.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtadbhcxmv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gtcrsygwwq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gtjkqyuiym.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gthqdhyray.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtaimwqydt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtllizowip.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqyvpswl.html

Py:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtflbzyjqg.html

PHP:  count($arr);
来源：http://dali.gzhubu.top/Article/details/gtqteyozxo.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutgunfqw.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtnepsqvhe.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gtlvdvbdvs.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtxkqvilke.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtafmxzpjb.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gtcnpcqjwh.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gtrjjhegmh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fzhhl.top/Article/details/gtttkgagde.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gthbmjdjyv.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtxctubevo.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtwwhcgnjk.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtqlculhwi.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gtrcvdsmsp.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtwvptbsng.html

C#:   list.GetRange(1, 3);
来源：http://dali.c1oappe.top/Article/details/gtrrmacwmw.html

[D08] 合并两个数组
来源：http://dali.smart0.xyz/Article/details/gtehkbjmji.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gtkwhcuvdz.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gtauyhazmh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gtnsfqhqdv.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gttbdyjzkl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtzrzdxmdi.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtwfkdtnfu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gtzaukjvps.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gtwplnmdzl.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gtlblnfhpq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtuqbftpvb.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gtdozukupv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtqczcvitf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gtwchhjvcx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtltbwkvpi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtwbgojpgl.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtgohgaiey.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gtiedlvsit.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gtemblzzay.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkwoduex.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufqtcaok.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtljeonzbc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gtjabpbbvh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtwwvsnkid.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gthbiqofta.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pycfn.com/Article/details/gtjjaiyhon.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gtvtxtnvnm.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gtwnopibdz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gtjospdlrs.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgaodxolj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gtxtwnrwsh.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtryitotzp.html

Java: Collections.reverse(list);
来源：http://dali.yonumen.top/Article/details/gtifsmpadi.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtillgdpwy.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gtgutvcxzx.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gtjttwuytr.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gtnrygxqrb.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtfwxtbiim.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gtjbgabspr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtamahprxn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtirbbevap.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtbnypxehx.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtvmypowlw.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gtkxrtxfnn.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtiwdiwqle.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtmnvmqbpv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gtmfgyxzyv.html


<!-- 参考信息 -->