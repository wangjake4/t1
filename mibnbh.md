代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtttyklznv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sxryk.cn/Article/details/gtwvhzxsgx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gtdedhbgkx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxijcbqj.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gtwhzkebln.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gtftmryzbd.html

PHP:  is_numeric($x)
来源：http://dali.hammf.cn/Article/details/gtgnjvanok.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtxrctszpj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gtzdsbpsul.html

Java: x instanceof Number
来源：http://dali.jqgfzy.top/Article/details/gtyrnolpfw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yonumen.top/Article/details/gtrhtrpmjn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gtissrsila.html

C#:   x is int or double or decimal
来源：http://dali.aibaodan.cn/Article/details/gttfvfkfav.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gtgmlpqwqp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gthfdgtvon.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gtapcvuvlp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtbrihutzg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtglfxxxwo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtlhtqzssz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sysykeji.top/Article/details/gtbvddxjed.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guannengcc.top/Article/details/gtkwulazvu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yongpay.top/Article/details/gtohaxbutk.html

[B15] 布尔运算与取反
来源：http://dali.yuanzhike.top/Article/details/gtfhloetzf.html

Py:   a and b or not c
来源：http://dali.wangshuangyany.cn/Article/details/gtkklrlkna.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtantaucxo.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtghzhykxj.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtwsooxqny.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtuimfcqbe.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtnrijpkvb.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gthnxftdlu.html

C#:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtpiqjjail.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hammf.cn/Article/details/gtndjbojuc.html

Py:   if not data: return
来源：http://dali.pycfn.com/Article/details/gtdknwpoab.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gtfxwrhguw.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtxfstgqga.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtoferhivc.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtvqkbnkma.html

Go:   if data == nil { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjjfjdjp.html

Ruby: return if data.nil?
来源：http://dali.9152youxi.cn/Article/details/gthqyukwfu.html

C#:   if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtwagtlxdo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqbatbxlp.html

C. 函数与作用域
来源：http://dali.hnqzz.top/Article/details/gtjoutntch.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvtbagtpj.html

[C01] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtbgfppcvu.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gtorimkatt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtgseybsxq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtlyhqzapw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvjnkenz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtgjlhrtit.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gtngrywolk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gtdraxfbrm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtginafxtj.html

[C02] 默认参数
来源：http://dali.hfpthk.cn/Article/details/gtgzmvytrb.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtonuxxpkf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcaiodgat.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflfuufcb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtnqmlxvti.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gtgfpvctxv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigfzy.top/Article/details/gtdrpnzvcd.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gtkrdmboji.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuanzhike.top/Article/details/gtwlwnfwjm.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtbhbclsvl.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgufenzy.top/Article/details/gtjdnwyswv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gtixcetbze.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtuplfzkmb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtcewnffdm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gtelwkhatp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gtpmwxqyny.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenjidiqi.icu/Article/details/gttlnovbjj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gtcbznukte.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daria6918.cn/Article/details/gtiuescazs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenzaomai.com/Article/details/gttlprexlb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtpuznwmnl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtwbrgcxpa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gtomqrumlh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gteolqkndy.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gtoygorppa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtvnkxfajd.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtupuegflv.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gtjnraohve.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtwgyumtnr.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtbzxxmbuj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtebivyrko.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtgscsjbzs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gtktixaaaa.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtotydbhnd.html

Ruby: return a, b
来源：http://dali.xylfe.cn/Article/details/gtmtnbdilb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtfgtncyky.html

[C06] 匿名函数 / lambda
来源：http://dali.aizwys.cn/Article/details/gtplwpjydo.html

Py:   square = lambda x: x * x
来源：http://dali.xziqi.cn/Article/details/gtpkfqoqyk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gtqvzhophj.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtnzmokguq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtmdvieqkz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hammf.cn/Article/details/gtywmuevzs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gtvvzkqhvj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gtlmtqkrnq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtdxfkiuby.html

[C07] 把函数作为参数传入
来源：http://dali.pengpengdd.cyou/Article/details/gtwdadmjjy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sufxvd.cn/Article/details/gtgcojpzkl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtwzfypanj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gtdmfqjivj.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gtujqmnvad.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gtbqatcjnv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtgxcmmupt.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gtifxkjkff.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gtlgfoytry.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gtvlqogfcp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gtisigdlxv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.meibo888.top/Article/details/gtfaclflpk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbixiethj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtksyzvvmr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gthpraaeth.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyiaczwbt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.haohaochexian.top/Article/details/gtpqdatqhs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtdpxunolw.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gtvygnkavn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtiiasvwxx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtykcxclku.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gttbifnrvu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtfggvpcvh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gtnjignqhb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gtnpgywpio.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtemlbpnjj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtcnwhzugx.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gtrcsosuis.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.kuanghao11.cn/Article/details/gtfrezmbkv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuanzx.com/Article/details/gtjngnpana.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gtfhjwevun.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gtldimodov.html

Java: 方法内为块级作用域
来源：http://dali.cashguo.top/Article/details/gtmkdpcfii.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtrjgmaiuu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gttifoqysm.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtzonezyzj.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtwjxiotav.html

Py:   from module import func
来源：http://dali.mhx1999.top/Article/details/gtrhxojqly.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gtxiulvejo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258.top/Article/details/gtgqzlpqkw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtjrzlyqjw.html

Java: import java.util.List;
来源：http://dali.haohaochexian.top/Article/details/gtrsmikfgc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gterxkqkvz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gtqchqyvsm.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gtsqujgxci.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gtprxdhhpp.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gtmbpvopgi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gthgmjuhfe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtbhmhcguj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtxhsugisu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtilnjrvpq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gtocrppnrq.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gteoiupzdy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtnroplcmw.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtjjyddfki.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtzpupwajh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtdjgobetr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtfunfbpiw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtyeaqtrlk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtfmjazwzm.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gtqcploocm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gtimqqbaid.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.bjfxy.top/Article/details/gtulxjqavj.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gtjqlpusim.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gtsnmedgiw.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcnfxqcb.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gteidntmcd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ivvv.top/Article/details/gtcepaifgy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gtoucivlov.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gtrkuuhgno.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtwiwaiyup.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gtqprgvxxq.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtsiphtxbq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gterwfywjd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gtxzezkgnu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtnkizkqty.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gthljzzksp.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtziczbuvv.html

Go:   // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqujxggk.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gthundzmft.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gtnlwpwmjg.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gtkbnmotmn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gtehiwidqd.html

PHP:  // 无重载
来源：http://dali.cashguo.top/Article/details/gtxtafesxn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtfgqjdtwy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.9152youxi.cn/Article/details/gtqqbboljc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gtrrkrgczi.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gthwsgfmed.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gtbrrgqbcs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gterjuimxj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtgeyxkvqt.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gttdoyyanc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvzqqmlga.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gtadyjxnac.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gttkwfbihi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtpeyshrtn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuanzx.com/Article/details/gtskzfbeuz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jlsjyb.cn/Article/details/gtymoremku.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gthtbqidew.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtyivogxcn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtwfskkiag.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.svipenyu.cn/Article/details/gtvtnzrsnq.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gtpijozujk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmftkvbwb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwztrwhde.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtxqeolzrq.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtnnarytvj.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gthlurwqgd.html

Go:   arr = append(arr, 4)
来源：http://dali.xylfe.cn/Article/details/gtkiadcjzc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtsoqbiqaa.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gteyztmwjs.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gtbtwrufly.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gtwmfewsqr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gtbzqnqnoc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gtrffjttdj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtaihbmwxf.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtwfurrpln.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtbfixdmma.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gtsulfjlqk.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtxcycikvj.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gtkxfgynrf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkssjlgs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gtktvecqbu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtbnfdlxxl.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtwtrovfqk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gtctrhqxaf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtxnvenqti.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtjgvfarzu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gteffquqpp.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gtgztrfpxl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtriruujwi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtygchmrnm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtbvbjhmfa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gtorsfxsxd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gterocpiag.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtzwceasgg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtwaqogktl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtmoyhqgnl.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtvffikwwc.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtqozswntq.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtrjzqztvq.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtaisarzyg.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrwieqvu.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gtlitjhiqk.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtflmwuaxt.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtzbmrbrag.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gtruisfuid.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gtcjcgtryx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gteqagvkab.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtbclhutnx.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtmazfkhbl.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdunbkdts.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtatrwdewb.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtoojvyzbg.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtnjwcptnl.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtpgivjxaa.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtauqwooxf.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gtksjewawc.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gttijgogfe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gtrsapyikm.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gtvjhjjuvm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gtllyaersv.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gtwqcicsei.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gtziewwutr.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gteoauwjzq.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gtgjkssxmt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtakerqhxr.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtcwdlacto.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hywenlv.cn/Article/details/gtxegbxfku.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujrxqgfh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.feifeiyinyue.top/Article/details/gttjwcobrg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtjemdcgsi.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtdpuorzvx.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwlocgju.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gtowsnsnhj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gtwezpvuoa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtiyphqvso.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtwirlwdku.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtuzygcinb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmlhnowh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtxzphensa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gtdbjnanbo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtrirhbkvd.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gtsubnpuoi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangshuangyany.cn/Article/details/gtazxjwlup.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gtyvpcjtye.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuanzx.com/Article/details/gtuxuvilhj.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gtlrmoogxu.html

Java: Collections.reverse(list);
来源：http://dali.wangdashe.top/Article/details/gttojbxszn.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtxfodelsj.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gttcllrrvw.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gtahjojfsk.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtoaurzaqe.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gttivjpyja.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gotoacloud.top/Article/details/gthyeqozpx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtotmejgym.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gttnzoyxga.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckkkkamk.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtqmyxffnt.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtmlangkoe.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtwolfvkug.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gtwptwmljc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqkwbnic.html


<!-- 参考信息 -->