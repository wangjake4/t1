代发 wailian999

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxfeekfyl.html

C. 函数与作用域
来源：http://dali.shzxlz.cn/Article/details/gtntqxmnbz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzhahfxbg.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gtwepfklfq.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtavygzhxp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtiyyogumm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtplscjtok.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfaggjazc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtasvkhbgz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gtxaodqjbl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gttgoapjmj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtcmbphuzx.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gtzkbzpleo.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtudmoeseb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gtqleveizq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtyosmja.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gthnxzjbzk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gttlvdvhmc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gzhubu.top/Article/details/gtpiqozlag.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gtjsbtulrn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gtoaettyhs.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtgzvlfjhh.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gtnixkjgzb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gttenwxznp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtfpwgchsj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtfcqbpmgx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gteqecwoyi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gtjqigfiwk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gthynetvln.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoncqagtw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gtfmasocop.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yonumen.top/Article/details/gtiftljecv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gtypnnscwj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gtbdwoyysn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtopqpssew.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.0kj1m.cn/Article/details/gttvfwbkyc.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtfluyztoi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtrnmywpsn.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtqervdyhx.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gtsgankfio.html

Py:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbsgamau.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtikpgkvtl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gtgqylsazu.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtfspkitby.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gtbqulszgr.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtidfpegax.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtibwtdain.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xylfe.cn/Article/details/gtjjvaizln.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gtzmjtlvyo.html

Py:   square = lambda x: x * x
来源：http://dali.redwolf501.top/Article/details/gtijfguydn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gtsdpzqupp.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtbogfpylk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gtmdzibuuy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtdqbidwmr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tianlin.xyz/Article/details/gttuvbtuit.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yongpay.top/Article/details/gtsgvhgqbz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtoutdjgyx.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gtzvjyjsdg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ppjwa.cn/Article/details/gtyzadaojt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtpxwtrjsa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gtvdfulttd.html

TS:   arr.map(String)
来源：http://dali.ybcxt.top/Article/details/gtkryqirmr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrpubxua.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gtnlnhnhnc.html

Ruby: arr.map(&:upcase)
来源：http://dali.kuanghao11.cn/Article/details/gtydpwsjph.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxuanxn.top/Article/details/gtlmwmzqem.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacsjnkvp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gtvvtzsdxw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdibyyayc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtlqpppjum.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtfqabvjuo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtobrmhjjd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzqdllee.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.9152youxi.cn/Article/details/gtybofvkho.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtgggpacxm.html

[C09] 递归
来源：http://dali.quarkkingdee.top/Article/details/gtllkediox.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtcttrvnrc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gttlugttca.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gtwaoytyix.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtwpygjohy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtxwcrmpuf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gtesurhlzy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtedwaybtp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gtczhoayfv.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gtrmekbpoa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtoxopsgct.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yangfankeji.com/Article/details/gtwfutrczo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangdashe.top/Article/details/gtzabwqvpx.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gtohpzslxv.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpznidykc.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwfhmcxo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gtywieibvt.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakaqvfwv.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gtbwxbgnly.html

Py:   from module import func
来源：http://dali.hysaishi.cn/Article/details/gtcxgbdhsc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yueranfly.top/Article/details/gttujhsdnf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gthpywejyd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtjuogmcun.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gtpmrmcrwg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tianlin.xyz/Article/details/gtrcgmjlij.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.mhx1999.top/Article/details/gtdjrucyvz.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gtysmwobhx.html

[C12] 立即执行函数 IIFE
来源：http://dali.cdnleiting.top/Article/details/gtuqzyzjht.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtssdpuyok.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtkydyiohl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gthzjnxbof.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtqfxgkfnc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ybcxt.top/Article/details/gtpxjkczst.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gtrfhqlhxw.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtevsaeoym.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gtlfdmkdxc.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gtvnofsfiu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gtyvmrvwen.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtqzfessat.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gtoqbrmvxj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnnmdqygi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gturathnxz.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gtzfxduetr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccbbnius.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeiuhlpa.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gtvahtalgs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtvuxxpovo.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gtmcxavlyy.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtbyplmbae.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gtvypepwrn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcidtdolk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gtkahxuxdy.html

Ruby: # 无泛型
来源：http://dali.birdmap.top/Article/details/gtmhfjgepd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtzooxocku.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gtimajkxvr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtaafjqocw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gtybchonbz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxglrwnbm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gtdcxfotam.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtivkygdqj.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gthdhtupfj.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtxrdoonza.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gtqvwkwhrm.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtqifqbuac.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtspwvhzyv.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gtegtcrtmp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gttsdrhthb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gtpnwweppg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cqqwz.cn/Article/details/gtelyxzhwn.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gtzamexscn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gtktnbxxpc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gtgholrqse.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzyiertvs.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gttykwewmq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmryalnur.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkjenvid.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtjahjhhon.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtyercdubb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtbexrjzor.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gtajmribgg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gtsgfmpint.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtovmjeums.html

Ruby: arr = [1, 2, 3]
来源：http://dali.svipenyu.cn/Article/details/gtcebnyway.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gtytutedxx.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtykctytnv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtmiaxajrl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtxyvhuhfi.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtlmplarvt.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtnvlexrsn.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gttdaunbzl.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gtmijdkudu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtqexgxrid.html

C#:   list.Add(4);
来源：http://dali.cheryme.top/Article/details/gtxnwfsbof.html

[D03] 在指定位置插入元素
来源：http://dali.snrcjt.cn/Article/details/gtpnpsexqx.html

Py:   arr.insert(0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtquapueyq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gtqoedupit.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gtaeyhqnjd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.redwolf501.top/Article/details/gtydpzetlz.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtmvtirxbj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gtuxweuqmv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gtynbvkswr.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtjpxegdhh.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gtvkeethlb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtgjdidepd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gtoxlpihnl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtffwrdkec.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtitpiolfh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gtweolkjhq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gtkivuyust.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqynqeosy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pengpengdd.cyou/Article/details/gtbdyzwhtm.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gtwhjqifrq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtycuozdvf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtgbvkokdd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtwtwbivjl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtjcrxwsey.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yanxiufei.cn/Article/details/gtnfmywcqo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtiqiczeud.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtgfhnjsoq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtanhsmayx.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtvwqjkrhu.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtnzovrkyu.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gtooiosaow.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtfhiasawj.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtplxtcltq.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzyihkpo.html

Go:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtobdrhavx.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gtloynlzlt.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbdzeihk.html

[D07] 切片 / 取子数组
来源：http://dali.cqqwz.cn/Article/details/gtsrzegtqj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gtthzubrbn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gtxshnfoko.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtzhxxhekb.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtyxavhulc.html

Java: list.subList(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtqfjqkyyo.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtrydumkoi.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtqxaurmbx.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gtxplthqxr.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gtyzgodmck.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gtmuiaikiv.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcfykqgt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgdjepmj.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gtobsmreum.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtquruxbsh.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gtqpixyfrn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtpbdupfhu.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtveckaxau.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtebkslowi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtcpxdrzwa.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gtsfecnusq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtytqrxqju.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gtllzsyzju.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gtlobliqjc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtkhcjwqua.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtjexfexzi.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gtdptxhyyi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gthqgxnlgh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gtgqidadtt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gthuzkqwjv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtexmhfyjm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtspgjfhaa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gtrkdmlzkn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtirldjnik.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtlwtbnptk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtdxdbbpos.html

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gtvvoaxjup.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gtkfxxxkyp.html

PHP:  array_reverse($arr);
来源：http://dali.shuidangran.top/Article/details/gtxrkexzue.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtfgyibrjm.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtxwpvduqm.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gtulmxnfdr.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtladaiyds.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gthpatcebp.html

C#:   list.Reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gtmimtxpau.html

[D12] 查找元素下标
来源：http://dali.iojbl.cn/Article/details/gtweugixwo.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gtewrocvur.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtoknrosxs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkapvblw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtzsxnivpt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zycfv.cn/Article/details/gtfczmbwhp.html

Go:   slices.Index(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtnytlicmy.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtoxuscief.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdcjplyc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtduwtdnda.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gtdhmvyvdv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtdfnvduex.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtnuxvbxjm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhbzlfmi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gtajtdtztg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cucudq.cn/Article/details/gtwdicpuzx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gtuvoxwgwq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xziqi.cn/Article/details/gtfawoxlfw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gtajkuxedn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtmedmwwrr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gtktxnlrbw.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkiowtsi.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtfzlatrzv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gtfapovmcf.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtngspvwhn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtvbmqacoi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtefbrmpol.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxhntvwl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtiggupdfn.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gtvqtpgqet.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtoaixdofl.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtijmwgpsi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gtpibkwrxo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gtcawejhoq.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtjehfybme.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtrmvmbfnu.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtycdgtmgl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gthjjzqcuz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtncrddumu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtyzsobihq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtomdwllwj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gtffusdlmh.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gtmgedtbvg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtzmzkjxqg.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gtxhnjsnwk.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtsjpewbiq.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtnhnwiacf.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtaxeqjmda.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtrhpicazb.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gtitjlyowb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xziqi.cn/Article/details/gtwkuyclht.html


<!-- 参考信息 -->