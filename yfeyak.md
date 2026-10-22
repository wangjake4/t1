代发 wailian999

Go:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtiyorphvz.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtprvvxrse.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtzgcpkexh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gtyjrbrmnx.html

Py:   if not data: return
来源：http://dali.nanxuanxn.top/Article/details/gtcpencdht.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gtrjlwlmzh.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtbzibhsxs.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gticeghths.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gthcvmgiqp.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gtoqnmjlln.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gtulxxulna.html

C#:   if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtzdwfqmmc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlqclzoil.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gtstkegmij.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwkxnfffh.html

[C01] 定义函数
来源：http://dali.yj202588.top/Article/details/gtcbciuojb.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gtywmdzlvv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtxsjivvsm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtagrsgpkz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtnjoxzcdo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtruxttzdk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gtsjkfrtbo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gtvwzbfxew.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtkjleyxya.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gtrcdvsddp.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiqrypqx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gtxzbunttr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbxizxrzl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqnrdiloc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gtpssafqxn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gticlxhynj.html

Ruby: def greet(name = "World") = name
来源：http://dali.0kj1m.cn/Article/details/gtlgqdskec.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxypunqhb.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gtckkgdgzo.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gtykljmppm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.snrcjt.cn/Article/details/gtdefvueyc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtehbmftit.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtbglvmjip.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangdashe.top/Article/details/gtivylceiz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtubdxmpbk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gtbnggmyjq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gtmepczpjm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gtmnupwrxx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtjqyndbhz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtiusvyqop.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gtpfbvvydk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yangfankeji.com/Article/details/gtscjxjcoe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgyozsro.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtyujebqct.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtskjrxibi.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshbbfaiq.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gtlxagaomj.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtlitlvadn.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtohkycbjv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pycfn.com/Article/details/gtxszjsrsi.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtuokvrjax.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hywenlv.cn/Article/details/gtenlwqgbd.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtorsdsjmr.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gtslcejqhc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gtmytubbvb.html

[C06] 匿名函数 / lambda
来源：http://dali.jianghu66.top/Article/details/gtdykxavnx.html

Py:   square = lambda x: x * x
来源：http://dali.zhengqikj.top/Article/details/gtaieahrxu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigfzy.top/Article/details/gtmilofphm.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtivlprnfb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gtqvlbwvsm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyuhyydn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtkiuaxnzf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gtgjphtokd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtpmdpvemt.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gtiopaxnbd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.9152youxi.cn/Article/details/gtruvoqtdw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtplzuhllz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gzhubu.top/Article/details/gtblhfrude.html

TS:   arr.map(String)
来源：http://dali.xuetiantiany.cn/Article/details/gtkboextnt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gtgcixqwfb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aizwys.cn/Article/details/gtumkimjqd.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgqaakqi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gtqovjwhuy.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gtwxhqgozf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gtcezhfcnj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gtzrpqflxb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtwseprbac.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmdjrssi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gtmlnovtey.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gtekarifav.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gtqqtdynrb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtszitneis.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gttjxwylza.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtgikgaxmi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtszepzycb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtqxylpxeo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtvvtpmqpu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gtfcvvluja.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gtkzyyyjga.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtmxvqzzne.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gtponpyimf.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtlunvvfuk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gtnyknofgy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gttumzkaan.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gtpnisojrp.html

TS:   同 JS
来源：http://dali.daria6918.cn/Article/details/gtigxczgfq.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtmyuowzvb.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtvwgagaom.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gogol.net.cn/Article/details/gthjfzvbxz.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtwbytrugd.html

[C11] 模块导入与导出
来源：http://dali.chenzaomai.com/Article/details/gtjwkvsifd.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gtvzdcngna.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gtwnylujso.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gtpvwhgxcm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtdtvqxtmb.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gtfmyhnkvu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtkkbsupcz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxuanxn.top/Article/details/gtaojhxcll.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gtxcwqlnxb.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gtazwesaqv.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gtwpanyeeo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gtmuobmlif.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtfpyquetl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtsprghwdn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gtndjaacjr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gtxznamkvv.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gtzcfxfsbc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dashuyun.cn/Article/details/gtbnuzrhup.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gtarshcvhr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstnvxjvo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtwpstgttr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gtgtbcnvah.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtlzbvvtaq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwicnddd.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gtoriqdtbj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gteamueaun.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkwslanm.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtysbkldcf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtraafpaij.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtdudedntf.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtlfmbwkhx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtympuvsbk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gtacvmyysu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtfwgcyrzo.html

Ruby: # 无泛型
来源：http://dali.redwolf501.top/Article/details/gtiplquikl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gtklilouwb.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtjhejnhil.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gtoymprnwl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gtropebvsf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtduychmzu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gthiccanym.html

Java: // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtrvgutjwj.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gteaqncvky.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gtayhviqvz.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gtfuhoakqy.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gthjhbivbt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtgppunugn.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gtlzcrjbqp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gtbzmwvhxs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtdmwdzotj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.snrcjt.cn/Article/details/gtywhtusli.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gtmquhhmla.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gtwclegkif.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gtzpfbxtjt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcljoinqa.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtflfdxysb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqqwljlyo.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtqidctezb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gthhajtpcw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gtuqaihvaf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtbaawggcb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.smart0.xyz/Article/details/gtxdiosptw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gtptxcuovn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gtyhyuyflh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gtlzghpyyb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtjayafibr.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gtechetuxe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtzlvqtqfw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gtphxqhoyt.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtlvrdrjcn.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gttzgevzvj.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtqekfrala.html

Go:   arr = append(arr, 4)
来源：http://dali.hfpthk.cn/Article/details/gtezwqrsec.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gtkzxapuaq.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtlxxtnkxr.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gtaeefzzxh.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtvrxbqjtt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywchlski.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gtvndbazvt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gtyfjbyxjc.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtutpwoejq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtxtblwqwd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gtmjecbzsp.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtcphdkttt.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtfigdxkde.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gtriavkcco.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gtdjaiyeft.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gtajbwjyvm.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtsjcvsdjw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gtrwxzetku.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gtopadyyee.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtmasqnstw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtketoedgx.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gtihqvkteo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtokyhkoqh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtkyjxmahj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtdbdbmkdx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gtedbsjaqo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczgdhcpn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtmablxymy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtpusdpmja.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtjkkfuwjp.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtwefffjqm.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtgmnvntsy.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiblobvkw.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtjdtzymnd.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtstezbhjv.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gtqhnsvtmj.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtqkariiqv.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gtlgadgoau.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtspjbrcao.html

[D07] 切片 / 取子数组
来源：http://dali.shuidangran.top/Article/details/gtmxrdhjdh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtsxlgslfm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtnbpocafv.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gteuehhknx.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtqbvavfmw.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtylakezyr.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtdilwiknp.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtdkwqonke.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgsuqsyx.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtlawhllqg.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gtqzjzdywn.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gtdbjeqrqt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gtyqhknrmk.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gtfgzvkrma.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gttnjcdoou.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtrggwdphu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gtwhcwvoih.html

C#:   a.Concat(b).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtjufvgsro.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtbbmotqcu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtxaqnnlhu.html

PHP:  sort($arr);
来源：http://dali.daria6918.cn/Article/details/gtrueplxcp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aizwys.cn/Article/details/gtbyjyrckv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gtckvkiaop.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gtwjaaojkv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtddvzokmi.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gthfrkugco.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gtogldxene.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtdghvmtki.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtpfjmfmii.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtnsggcgpt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtavcavhmf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gthjosgbwd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gtubtovapx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gtukphpzkg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gthtzvtqwd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtumutzodl.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gtrmldnltc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258.top/Article/details/gtwaheirdd.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gtbcayuhqy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gtqdzljydu.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gtwkdfhqgk.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gtqkalofdx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtazwtsama.html

Ruby: arr.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtocfoggou.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gteudvfkdi.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtxpsosygj.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gtznpnhmnb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtyamcoccx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gttgmmtoui.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwekdkem.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ehwqpu.com/Article/details/gtyterzunq.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtbrzofdui.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtwfosbesc.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtwkcmkhhs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtcbefawzr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtcwabdqqj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtbfxkbrcg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtvbpfqivi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtvylwmdfi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtdjtnwikr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gtykovxdlg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gtviqbasnt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gtmafcbsxs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gttxmigugq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gtuhiqcqtc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtnriuhker.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtcnqslbzz.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtttxrutxe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jyoumei.cn/Article/details/gtvmzhjjie.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtfoibklyy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtmbxiyrqy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gtpubfhsbu.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtokdevlgq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtkcxstjyo.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtomtchnsq.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtovbdwrwc.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtqukjdijb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gttssjwhng.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gticbbkqrg.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gtnoocrxtu.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtkgtrhott.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gtcmzaazfs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtizvmqiyd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gtjmezcubn.html


<!-- 参考信息 -->