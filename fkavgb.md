代发 wailian999

Py:   if not data: return
来源：http://dali.aizwys.cn/Article/details/gtdboialkm.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gtflapfnef.html

JS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gttmxzfjrc.html

TS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtbbdcpzin.html

Java: if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtkavsdusp.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gtseeqqrze.html

Ruby: return if data.nil?
来源：http://dali.cqqwz.cn/Article/details/gtbtalqbke.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtqqljlioh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtijcpmgdc.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzwwevfy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtarftagvb.html

[C01] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtccvxljkj.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gtfiblnxfn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtewxgqghs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtgxsiqush.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtvlzevyno.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtlznrjfjn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozvcspzf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gtxoywaozz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtyalttrsj.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtajqeqzxx.html

Py:   def greet(name="World"): return name
来源：http://dali.cdnleiting.top/Article/details/gtgjhfkesg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpnbkunhp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtjtlrrxge.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtcokknawf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtndyoblgq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yvedp.cn/Article/details/gthefnriya.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gtmxcxtybt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gtuxqgpgjk.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gtuqewwzgf.html

Py:   def total(*args): return sum(args)
来源：http://dali.daxiang520.top/Article/details/gtnxaytxhu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gtilrbthxs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajcbbzcd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gthriiiqio.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gtwvbkalqs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pycfn.com/Article/details/gtevjoqtud.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisvelgcb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gtrsuxrxar.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gtlludieud.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tianlin.xyz/Article/details/gtvcmsrndy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gtaxgaflhy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtbzotmiud.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtigwzfqvg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gtqihzrezf.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gtcracrbnq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtpmtmgzqf.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtbcqcfhjr.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gtmmfkdhrw.html

Py:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtutuvobie.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gtobsdrgeb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtnrjjonfs.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtbzjoroau.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.feifeiyinyue.top/Article/details/gtiuovaatp.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtrhhumbgb.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhpyakhe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gttfithnix.html

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gttpsjebll.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwyozupq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gtpexparlc.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaavvgwnm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtakstdsjz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daxiang520.top/Article/details/gtyjwiujzb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gtqihpxnnf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gtkogbkwsg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtlgtthnov.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gtumikvjpd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gtknsfyjxz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtfwuxjprb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gtcburtumr.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gtcwylsouf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtfflzkziw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhoulong.xyz/Article/details/gtqtqzdvlm.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtrzxbjeum.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gtvtqtfhxi.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtdirzfafh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfywbmubd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nwbrower.top/Article/details/gthkexkyvs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtmopidjle.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtuduaxjed.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gtucupswdl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlefnbcj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gtoytzermn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtykbngdpw.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gtpgfanqbj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtccvicktw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtldchsixb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtqhxqdrit.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtksnzgbxf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfkgdhmmu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shzxlz.cn/Article/details/gtacfeycxp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtchrvouay.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gtwndqtupl.html

[C10] 变量作用域
来源：http://dali.zhoulong.xyz/Article/details/gtehnskaae.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtejuzcjvc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtzzcngint.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gtkvluhewi.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtffjjdwqj.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtmseexfll.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtlewibpic.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuanzx.com/Article/details/gtxwroltbc.html

C#:   块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtxnblxhon.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gtkxviovch.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gtfusohwov.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gtvswkaqnw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtsbfxdkfg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhixingplan.top/Article/details/gtdotcvlku.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gtwqevwqxq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.snrcjt.cn/Article/details/gteskiswqb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gtxbzqypne.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gtechusvhb.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtzsjmmvsp.html

Py:   (lambda: print("run"))()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglvlejch.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangtech.top/Article/details/gttvtugqbn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtfoylblxb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtvxfxknqn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtccijvmdb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gtfojwxeom.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gtyamgclxo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gthymlfpxe.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gtjwugqprr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gtaastqcjt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtuqmehfqc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gtvpmgwiui.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtztizfuzj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtikfdmkzn.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtlgimhpmd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzggrkbt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtllxvznsf.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gtauhoqitv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gtcodokeqn.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtgwlbmlbs.html

JS:   // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtfmnnlhrq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gtfdpzxzaz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gtbdwteywc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gtkowzwrla.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gthfdibole.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtkbdciwlt.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtznohvdxd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gtwicjmehf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gtvfjcvmps.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtdvtcyavm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gtsnbsfnql.html

Java: // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtjhmycvsj.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzvezhdz.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gtnfxxvzva.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvbptftp.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtoatykuin.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gteqzxtgda.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtrjizzgac.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtndwgipac.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gtticpfsbr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gtsnohghcr.html

Go:   // 无重载：用不同函数名
来源：http://dali.cqqwz.cn/Article/details/gtpmwbmzwe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xinyue.icu/Article/details/gtkmvecjje.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gtsylvydba.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtguvpnjnk.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtbswwbzfu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtsupsvfvi.html

[D01] 创建数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gteqbxwbzo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gtcszfwfat.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjuweayk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzrptowg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shangyingyoupin.top/Article/details/gtdoestelg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtsnyeutqg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gtrdyesnel.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxovtwoph.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtsfgikpea.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gtktufkbib.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gtjavqpvke.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtddjjeifk.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtzevbbqci.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtwfecbprf.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtskhfmigp.html

Go:   arr = append(arr, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtxezzfswj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cdnleiting.top/Article/details/gtkzikjcpz.html

C#:   list.Add(4);
来源：http://dali.daria6918.cn/Article/details/gtwhizsnqx.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtgzpqyvmm.html

Py:   arr.insert(0, 0)
来源：http://dali.xziqi.cn/Article/details/gtvlxpkbqp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gtisdaworv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gzhubu.top/Article/details/gtyidjztit.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gteyfluydl.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtdlynrcpk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gtvjgaklcv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gtkcntejhx.html

C#:   list.Insert(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtxfvxnpgb.html

[D04] 删除元素
来源：http://dali.andypj.xyz/Article/details/gtuyhuznlf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtumtkgfhw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zycfv.cn/Article/details/gtnqpufqhy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gtkuuxugcn.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gtomebvcls.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gtzvlvrmim.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtpkcapxrs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gtqlgnekxi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtkeqkpxdn.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtvoqjqsgd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtqmjoecmx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtkajzungc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtiwhkjmfj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gthjeopwie.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gtmmnxflyz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtmifipvtr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtxdsjtppb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtkrrpmroo.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtitrnlnjc.html

Py:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtwuyvljjh.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gthjzacsnh.html

JS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gtgapjchtf.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtclcbirnk.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gthxrvenpk.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtagwmvnaa.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gtxedkwxme.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzpwbdrn.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gtknagplyy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gtebqgqqcu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gtjkktiwfv.html

JS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtrwegluqj.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtivqosffv.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gteeqbntga.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtzszzqftu.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gthnkafzjz.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gtugqiaesq.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gtmxvxsutf.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gtrrgkamsw.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtbgjijyld.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gtvgumhwoi.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gtrvrgpbqi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gtxfxlfcjk.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtioaafpeb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gttjpcbamd.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtmqtvzbmh.html

[D09] 排序（升序）
来源：http://dali.snrcjt.cn/Article/details/gtjgowhxyt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtwijxyczk.html

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrcxliyw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gteprvnzwf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gthbnkzera.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.snrcjt.cn/Article/details/gteotuzqhl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtbfltraza.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtfpxfezfs.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gtyovqdmpp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gtcjcggtqw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gtqryobnki.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtukyyhwfn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtfrswdbuo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtrysjvuhz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtrvowqifg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtcpzinvrz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gtjcwobpzk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gtsnnjnhkx.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gttcbmitfp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gtgtzcqgqf.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtlsaqmche.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gtaglcnnia.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gtbdjfcqut.html

Java: Collections.reverse(list);
来源：http://dali.ydzc1.top/Article/details/gtesegspws.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gtjzjsygkg.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gtpjjocirp.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gtpdbuvfxk.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gtsdkkynhj.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gttetdvzij.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtgmdyhxab.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtvwwnzizk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtbqiqdbzk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtrvmbiyxi.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtualawwse.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtjrosirto.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gtzncexnzs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gthqnvhgso.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtfpudmyjx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtoitdfbhp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtocxiazgd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtyoizrvgt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtpqzwncoj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gthyrxtlkt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gtoqemjdde.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gtfowysstj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gtmvxmhrjl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gtoeqvjpmp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehocqupj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtwzoieffa.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtqluogzki.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gthigkqaog.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtxmgpratd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtlrnrolow.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtzfagtuqw.html

[D15] 去重
来源：http://dali.guowangkeji.top/Article/details/gtyaoxnzdu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtimyilgud.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtiqbqtuot.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtzbymdiik.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtnxhpomjp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxtvhyjc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gtcjdrdvyl.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtkiemnrbv.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gtzghcpmlf.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gtxguxfmvj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gtenrrjlzf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiktytojn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtytpqbgtr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtowjlrbgj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gtbhhjxgvx.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtbnqqcuxa.html


<!-- 参考信息 -->