代发 wailian999

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gtjqhpyzfw.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gtaqcqdsei.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gtpnkqswuf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtlocaatnl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtipfgrshe.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gtgntstngr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtlcmqqyni.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gtdeaaxzxq.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gtdurgvcwt.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gtdjzzfvgh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gtlarwpagd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvlnjqeu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtdidurjap.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gtifmybryi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gtegqmommc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hysaishi.cn/Article/details/gtppcjeljw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnfevygm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtkztzatcz.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gtnmzymmmb.html

Py:   a and b or not c
来源：http://dali.sysykeji.top/Article/details/gtgbfrcpan.html

PHP:  $a && $b || !$c
来源：http://dali.pycfn.com/Article/details/gtasyhvlup.html

JS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtrgjhlykt.html

TS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmqwbbat.html

Java: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtrdigjgfh.html

Go:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtvgmkkbzh.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtahuvmkkt.html

C#:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtnmyepoim.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gtdigcegbu.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gtnqnoptsu.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gtvmrpicqo.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtywqnyatc.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gttylhcame.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtlwfdmzgq.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gtihzmtblw.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gthknlcnsm.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydnochir.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzrvzrlzw.html

C. 函数与作用域
来源：http://dali.zdqjudy.top/Article/details/gtppwemjnk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthyjluapz.html

[C01] 定义函数
来源：http://dali.hammf.cn/Article/details/gtpexqiymq.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtojhkumwi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtpdezpggs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtxcdngiin.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtvktrpccx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonvaqohv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gtgzxnqtov.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknofrgmf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtddpaxsbg.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gtxuwjgbsg.html

Py:   def greet(name="World"): return name
来源：http://dali.cheryme.top/Article/details/gtgbnckaas.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtjodsqnvm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmhllhfo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttnsuddni.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gtrkhokpif.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gthingneve.html

Ruby: def greet(name = "World") = name
来源：http://dali.316326.xyz/Article/details/gtryheslzb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gtdvfwjbhb.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gthnkuysww.html

Py:   def total(*args): return sum(args)
来源：http://dali.ehwqpu.com/Article/details/gtfgyrzysi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.316326.xyz/Article/details/gtjadskekf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtpmycsrqs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtdcpzaoip.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gtyjezmpca.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gtyzlylrqj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gttpwjfsdh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258.top/Article/details/gtjpijbcfd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoleevpk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtiqgtqvvm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtjvonhccb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gtbnnulojq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zdqjudy.top/Article/details/gtdwtfkzxr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtmfjadsgq.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gtrtmvcvwa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtfpodnxng.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtuwnwnryk.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gtiphngllv.html

Py:   return a, b
来源：http://dali.yongpay.top/Article/details/gtzmguhdgn.html

PHP:  return [$a, $b];
来源：http://dali.sxryk.cn/Article/details/gtlgfqljwt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtmyhzhcdv.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtlvkfjdxc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gtmaoxnufs.html

Go:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtgmhjcfse.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gtsoquppzw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gtzvxufpif.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtkimyiadr.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gtczqflssr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gtwbvmgooo.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtaflwpiru.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gteavjzqlr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gtdlzgqaul.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dashuyun.cn/Article/details/gtwbpdgafw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtolptxzmo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtkdllckee.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gtkafvvpia.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtqtqxwgsf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gthauaztqq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gtpmjootuv.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gthwyhcgff.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuxming.cn/Article/details/gtzoknwojy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlrhvqfg.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtdcbpzffy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gtoyfpkxmt.html

[C08] 闭包
来源：http://dali.dianchejie.cn/Article/details/gtsiiupkgw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuetiantiany.cn/Article/details/gtipnszafn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gtqehazdkh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtgfvofgea.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtbmbbsmxg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gteueiebxl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxuanxn.top/Article/details/gtzbingonq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jlsjyb.cn/Article/details/gtdtxepkmk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtgalqowfy.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrycrqzvp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtqnyjunrf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gtuphpzjam.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtxythadzz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gtkmzmswin.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtjbqrlpmg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jianghu66.top/Article/details/gthqbimnfi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtxxpnrzcb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gtiojjamud.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gtdrsloxmt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tanke756.top/Article/details/gtluovwsxm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yongpay.top/Article/details/gthscwtgyj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gtcbpdfmhv.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gtqmcjhifi.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtgwsnufuc.html

Go:   花括号块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtdwjzgewx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gzhubu.top/Article/details/gtrushvray.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gtbkpqxfqh.html

[C11] 模块导入与导出
来源：http://dali.kuanghao11.cn/Article/details/gtubdvtgrh.html

Py:   from module import func
来源：http://dali.sufxvd.cn/Article/details/gtlfgyqlvn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gtcirbaieo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtfemtwggn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtmjcdcnxg.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gtdqxicvij.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuanzx.com/Article/details/gtrgraahas.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpawfctmp.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtivvisobl.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gtlxvunzgr.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gtdgpygiik.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtzcveqntm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtgucmluyj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtwpmykfnu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtwjgflodo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtfteqacti.html

Ruby: -> { puts "run" }.call
来源：http://dali.tianlin.xyz/Article/details/gttabzbard.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gttvczjtse.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gtctvubrcw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtduvmdgqm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtratvuxdb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqeuhned.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtfradzrcg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtxzzcruwg.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gtatjuuzic.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.quarkkingdee.top/Article/details/gtnzjzegir.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenlongwang.top/Article/details/gtkazwqjgp.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtloqhrrlo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtyyckpxrh.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtwbpbfigj.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtolywukex.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtxuhxitai.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gtwrgabszl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gtsskwhbmz.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gttnagebdh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtccfkgatr.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtvubdexrl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gtwjmtgbhi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gtfdukiudj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtuzgerknm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.9152youxi.cn/Article/details/gttlrtwudb.html

Java: // 无解构
来源：http://dali.bjfxy.top/Article/details/gtlvcfbrls.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtttszxskd.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gtgbswqgcv.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtzjqjrmsi.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbiqdzfjc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtguprprqy.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtfmerhrcc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gtmsekbpgf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtolywykvc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fengsongda.top/Article/details/gtniofgign.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gtuagqtayz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gturkrjunv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gttpimlzbo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtywzqfajc.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gtyctpviwt.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtygnkcjte.html

[D01] 创建数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtgahatbyr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xinyue.icu/Article/details/gtuksnftvv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtgasnbyvl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtclrqnnpw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gtzsvvgiiy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gtpcuelioz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gtqhfegaxy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gtsaafyrbf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gtllpcbghn.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gtndafujow.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gtfhvsaqrb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gttljluhky.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtfwlwzplu.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtlwsxqsas.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtuxwlkhom.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtcwzdwjpd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gtrtwegfmb.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gtdktkrveh.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gtbqclgvfi.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gthwnqsolx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtuazzsywx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtuqtjykmo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtvtoxbstd.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtgbuemxml.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtllwowiqu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aizwys.cn/Article/details/gtfbnrppht.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gthktizofv.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gtcwbxkfch.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gthbgghcmw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gtivofksym.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hfpthk.cn/Article/details/gtoomlsgjd.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtojyylgqa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hammf.cn/Article/details/gtkirfrhgx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhengqikj.top/Article/details/gthuvrwmps.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gtygpbmcjc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gtgglchdhn.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gttlsvkisk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtmawjkhcl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtbclexblv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtvisngmqj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gtvljtnfqm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtjlrnizzg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtpmmwkccx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtzbcpznax.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtcuzpwaxb.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtglbegfsb.html

Py:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtjbxveori.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gtiqawaeon.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtkcwbvovw.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtyfjhwc.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gtbbitezgk.html

Go:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtqjqcpmac.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtyxclfzhd.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtpteqxhbr.html

[D07] 切片 / 取子数组
来源：http://dali.meibo888.top/Article/details/gtfpwhowfu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gtteualatn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gttlnvfdld.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtcaueasqw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtuvljarpx.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtnmafflnc.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gtmhuflrlm.html

Ruby: arr[1, 3]
来源：http://dali.tian-w.cn/Article/details/gtckktgscc.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gtnojowpla.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtgkrcjnkl.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gtjvvpflvq.html

PHP:  array_merge($a, $b);
来源：http://dali.jianghu66.top/Article/details/gtksupmqmo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gtexgqrhfy.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gthyfbovjj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gttkaghyaz.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gtnogerrve.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gteqyjanmx.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangdashe.top/Article/details/gtgyozfcxg.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gtuumzbqkh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtkdqalygt.html

PHP:  sort($arr);
来源：http://dali.9152youxi.cn/Article/details/gtdukufqlq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtkisevscx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gtqnmyuqde.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gtrlqgjsdv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzzajyuq.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfdiabam.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtcdxvutpe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gtthiruneo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwppzxmpx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gthmjyudul.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtubdfmfpm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtmyqzidrn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gtyujkbkfa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gtygwhjzxg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtgnezvhpc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gtfkjrtxvu.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gtarptvfkz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.feifeiyinyue.top/Article/details/gtuisvbtet.html

PHP:  array_reverse($arr);
来源：http://dali.aizwys.cn/Article/details/gtceupjlsz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gtdhbwyyvo.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtynhovqxx.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtictaovnh.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtgutryfqi.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuavqlqwd.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtbetogtmj.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gtkuopcqxu.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gtkpfvaghr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtvdfeyqog.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtsqrotian.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtidezwpke.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gtqhutywar.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyasfyyed.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gtmaxelyee.html

C#:   list.IndexOf(x);
来源：http://dali.sysykeji.top/Article/details/gtmurapuml.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gtmphbzhgt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtulghkboi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtmwndsfze.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtqgaanhqp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtvohujfil.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daxiang520.top/Article/details/gtnpyxyzvt.html


<!-- 参考信息 -->