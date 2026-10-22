代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gtphapabuq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtkzrvndxd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258888.top/Article/details/gtaogoerne.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gtdmrxhdfw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gtcgnhwbmf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jlsjyb.cn/Article/details/gtveilnizu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtbksphqzx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gthazjsnvh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtakzkvfsz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gtavzvjxsz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtvldtizyh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gtwdyazkvq.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gtcdvkxbdm.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuetiantiany.cn/Article/details/gtbawhwvec.html

PHP:  is_numeric($x)
来源：http://dali.zhixingplan.top/Article/details/gtmmczeupp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtmogkmjdu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtcriiidfw.html

Java: x instanceof Number
来源：http://dali.hnxiangtu.top/Article/details/gtoukflzgt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pengpengdd.cyou/Article/details/gtkivfybzd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgfzy.top/Article/details/gtziexwpji.html

C#:   x is int or double or decimal
来源：http://dali.pycfn.com/Article/details/gtijstlyab.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdnsgfhn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tianlin.xyz/Article/details/gtrswlaasd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenlongwang.top/Article/details/gtfzslwjrl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtjbyqstmp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtqldcgwgg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtcnjtsjyv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ydzc1.top/Article/details/gtkcohrrbt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtqwfgpzsj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuzzqnvg.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gthjxzebec.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gtginxhdvi.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gtzcxyrexy.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtqldfbkpq.html

TS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtnowhoxon.html

Java: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtejqpmsow.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtdywswrrh.html

Ruby: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtlcrjxrjo.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtdfqdopvr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gtummlryle.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gtuuqmebiu.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcxyeocd.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtrylwltvb.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtbzttubct.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtwobbuotb.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gtdjzqcxcd.html

Ruby: return if data.nil?
来源：http://dali.jinghuilouyu.cn/Article/details/gtpaoyfcky.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtsaxgvxfv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcldpgyif.html

C. 函数与作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtqafjgubz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbyyazmed.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtpxcafflg.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gtygjgbans.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuupabfta.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwdsdgth.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtzoscmfqv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtkembymvd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gttnafxnpr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yonumen.top/Article/details/gtgwbkshek.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpdsixgr.html

[C02] 默认参数
来源：http://dali.aibaodan.cn/Article/details/gtsrwzxupa.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gtyavhdmye.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gtysnqythl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtvcgoypes.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtimefhcze.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.316326.xyz/Article/details/gtirpetokq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.havefunace.top/Article/details/gtmkkejynq.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gttftmwdne.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gtxhrevdho.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gtobbateml.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyftvypiy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cucudq.cn/Article/details/gtrjlczahu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtywgwkgww.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gthygwodsr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gtraehihax.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sxryk.cn/Article/details/gtahxavkhp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gtyrvdrlfx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtnkwimmgq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gtbjaubcxm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxuanxn.top/Article/details/gtmfzvawke.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.316326.xyz/Article/details/gtoftltiym.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtmmhancga.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gtusefroak.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtvzkhfeyc.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gtooewtmxi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtckbiqrit.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gthbjlcwqg.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtfpmkdzfx.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtwmodwsbe.html

PHP:  return [$a, $b];
来源：http://dali.xylfe.cn/Article/details/gtemupgtcf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.316326.xyz/Article/details/gtdppotdql.html

TS:   return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtebsiwhfq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hfpthk.cn/Article/details/gtqaacxhpv.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtyarthigt.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gtlcwywnkc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gtmwdwzxob.html

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gtlbwtwclv.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gtsizhltfy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.vqdsnc.cn/Article/details/gtwwpstncx.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtphxmwgob.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gteilisltx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtpbvkiojx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guowangkeji.top/Article/details/gtchtdmser.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskwwaazo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gttuvyomni.html

[C07] 把函数作为参数传入
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrbofgdi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwspmndcl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gtpocqnmlx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gtfihjlrhn.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gtqvbcmdym.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtwjntizbw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gtmpzutnij.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gtemmczsuh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtxnayaglp.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gtmitgeuwx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gtkpitagby.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cdnleiting.top/Article/details/gtgbbgwlfk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gthmgyfhns.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtuufyltht.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gtmuddfxxw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gtvuqslpcw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.9152youxi.cn/Article/details/gtwsoxvnbx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtwsuoqoho.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gtehjzvalf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtkhzepgnt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtpnfobmew.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtkoidwaac.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtaesosrsn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtsyfsqlxr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tianlin.xyz/Article/details/gtpuphrzto.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxdbiefrp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtbklkbmus.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gtkvnqrlow.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gtqdhtygfh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daxiang520.top/Article/details/gtcztqzubn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangdashe.top/Article/details/gtxgrzyzgw.html

TS:   同 JS
来源：http://dali.haohaochexian.top/Article/details/gtvcyipolx.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gthnnubmrm.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gtqvbewdlk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtmuqmbifo.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gtkueljqvr.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtclhxrbke.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gtoqhfkhcm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gtuihykpfj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gteswrbhbz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gtsplyrrkj.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gtdgjganri.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwbrybmk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gturfappbz.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gtlqsdpqup.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gtrnhximqk.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gtmnuimray.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gtefwiktmz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtdgztneha.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtkucfehkn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gtkxawyfux.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gtycyednpe.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gtuenjedlb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtvmjvwgsq.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gtwquwapgh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gtkazxoghg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtzppxczuz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gtrzvpekya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtcscdkhjp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtimhjdxss.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtriombrrl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtbxtvzqvc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsanowprk.html

[C14] 泛型函数
来源：http://dali.zhiwuduotai.top/Article/details/gtsexobjso.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gtnmodvvwr.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtzlvembqt.html

JS:   // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrfqwefr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hywenlv.cn/Article/details/gtwxvzocgx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ehwqpu.com/Article/details/gtozeaoiyr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnqzz.top/Article/details/gtuzqvqbnt.html

Ruby: # 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtcnthwfil.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gtzlychogm.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gtbsvjzggy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gtlvuuvlip.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gtucnbsocp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtfuberefq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gtqipkblym.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtvlkimyan.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gtlqurynic.html

Ruby: a, b = pair
来源：http://dali.hongshengwenyu.top/Article/details/gtqxdnopay.html

C#:   var (a, b) = pair;
来源：http://dali.zhoulong.xyz/Article/details/gtachizjtp.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gtzpsdstcz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gtwwjucsov.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gtoxxqtwrq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gttjjcktil.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigfzy.top/Article/details/gtpzxveujp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtvjaqbahz.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcfdtpvl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gtkqmqeeyc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtscpkzvsg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgepczwqa.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gtovcpczqd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsrvapqnt.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtxmphgqyy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gtqlkinyrw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtskmgdxxg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtouqreias.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtfnncvamw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gttwetxgon.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gtfloeawmk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtvhadyuhz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gtqxypyoto.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gticuhvdxs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gtykzprxng.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtechfmyxm.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtphkziwau.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttenxohvb.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtudkbevim.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gtcyarxads.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gtjlhcgnpw.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gtuovfuzqz.html

[D03] 在指定位置插入元素
来源：http://dali.jianghu66.top/Article/details/gtxbgxafhk.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtiwxcnlbe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuwiaiwv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gtiktifore.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtxlndfjit.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtuwtnoqoh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtmujgqrtv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gtwzihukld.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gthwtlztku.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gtpodeelek.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zycfv.cn/Article/details/gtpbzeurno.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtsqnwduke.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtvvgksbjg.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gtsausjcvj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtwzmmiswq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gtxsewxpic.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtjjolmsqo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxvsdbjm.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtlniscggl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtofisrriv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtmijiiibv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtlmqbtvrj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtqgeshuts.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtnjbgjrzn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtieonrnyv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtnxojbvye.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gttuqtgchy.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtivwnqrys.html

Py:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gthbmcwuws.html

PHP:  count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtbtnnuabg.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtdaoxfvbr.html

TS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gtfqtlhwvl.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gtvsgrafma.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtzlaudtpt.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtpqoptgcb.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gtgcchkjps.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gtyvughfwu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gtawddhspi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtnwlvgnyd.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtfsxpmfxm.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtedbuokyc.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvucbazj.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gthwwjsqks.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gtevzmvoqz.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtdllprmqw.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtolkyyjxb.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gtbrmmjetz.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtjidcwsua.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gthkotxkab.html

TS:   [...a, ...b];
来源：http://dali.tian-w.cn/Article/details/gtgcbewnfl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gtmzsqaeos.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtgromvtae.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gtwfraddye.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtvwccolwf.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gthehvzhde.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtqlsusavy.html

PHP:  sort($arr);
来源：http://dali.daria6918.cn/Article/details/gtlpammnif.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtvrcrjewn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gtmaactipo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gtlfzdfdvo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtfsylbzwg.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gtmhqjwyyb.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtvewzfaez.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtwnolpvcr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwjrbndc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtbosxgynv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtruujvbrl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtmgugpkvf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hongshengwenyu.top/Article/details/gtniuunpyu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gtrpqmtbcy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gtpouohhrm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gtfzjwtzil.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtgrtesupo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gtrmstydwa.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtxxbsmpoo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtdjpziryr.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtyftnafcy.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gtfochpbni.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gtawinwxxm.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtfapuhues.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtndrdagqy.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtnulytpix.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gttavhpurh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnybmcepc.html


<!-- 参考信息 -->