代发 wailian999

[C02] 默认参数
来源：http://dali.hnqzz.top/Article/details/gtuilcaceb.html

Py:   def greet(name="World"): return name
来源：http://dali.feifeiyinyue.top/Article/details/gtsaaxcukv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdvxjzpu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gthgzfgqes.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtbuhxtlqs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gtnxpmjyei.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtexbiigrx.html

Ruby: def greet(name = "World") = name
来源：http://dali.xylfe.cn/Article/details/gtnypeenpf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtfgwgvmwn.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gtbfwjlvpp.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gtsqisjahw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.mhx1999.top/Article/details/gtesaiqusf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnysphpju.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtkcwdwmmy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtknwuwhey.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gtylwwpudh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtsjoxpctm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gtogniwhhd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gtwubauzkq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gtodpuuhuh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdfjcucn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtxastdosl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gttarygxkq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sxryk.cn/Article/details/gtouwodtux.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gtqfcxrmfd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtzormmggm.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtxllquzde.html

[C05] 返回多个值
来源：http://dali.chenjidiqi.icu/Article/details/gtljzubksq.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtjffsnszm.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gtpfrkybwf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuazwxhp.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtosddmhuz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtnbkunwbs.html

Go:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gtbvyjrqqe.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gtfvwmvgbd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtlbkkaxyg.html

[C06] 匿名函数 / lambda
来源：http://dali.gotoacloud.top/Article/details/gtgpkapdbp.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gtjphblnyw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtzkbpbdpb.html

JS:   const square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtlivwqxqc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtifxzrfgc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gttmtdwhlb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gtnnaylerj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gtmyjdophv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgerdvmax.html

[C07] 把函数作为参数传入
来源：http://dali.0kj1m.cn/Article/details/gtglwlwsgj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gotoacloud.top/Article/details/gtpxkdfnoi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gthwflltbm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sxryk.cn/Article/details/gtpffsdsqn.html

TS:   arr.map(String)
来源：http://dali.jlsjyb.cn/Article/details/gtmmbxpkve.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yonumen.top/Article/details/gtbknfsthi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.redwolf501.top/Article/details/gtrktscymd.html

Ruby: arr.map(&:upcase)
来源：http://dali.tian-w.cn/Article/details/gtmmijybbo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gtsrklqgcs.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gtbkekydbh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gtkajyecux.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gtbczlyreh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtgksmcjaw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtgxvdubml.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtyfdsjjlt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gtodhylrin.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sufxvd.cn/Article/details/gtpnltdgnc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtxfokufur.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqkwxewp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtirerzbee.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtaqwneowh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtijsnmomp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtbdosdlqg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtxqgwkjka.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gtwijffyhd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gterxhsvpo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gtvhewzndg.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gtuugbubsy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shuidangran.top/Article/details/gtmqexsbnd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gtyvsokzdg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gtcpvjpkfa.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtghzzmsqs.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtbeyeqmix.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gthoqaauoo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtwsytqhie.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtrrmqikcc.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmutbyuos.html

Py:   from module import func
来源：http://dali.daria6918.cn/Article/details/gtrftmznat.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gtvqekllhi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gtyxkacnre.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aizwys.cn/Article/details/gtlcoydarj.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gthzetuopm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gtktqfipwl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gtinwfkadq.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtwcxattwr.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gthvxfacxq.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gthldveuet.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gtlaepqwkd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawswrzkz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtimlbywjw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gtbrzaimno.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gtrvcvkvqa.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcocytvxg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gtorpvglpv.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gtgmsigkvi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gtqgsnikjk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtebrdflbb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtpjejqqwo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtpzqwnusu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtobouncoz.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtjttgedmf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtqzsdukvw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtqjrvegrk.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtdynbwawf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gtovqkxpre.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbeiekpkc.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtgcrvllfb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gtsbsxuuaf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gtnyzwqdjk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gtsdwvekhv.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtybjcmlwc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gtfjcxiwlm.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gtkrcsxxxd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuiynfgr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gtmimyzojw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtmmyiluip.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guannengcc.top/Article/details/gtmwwokznv.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtxmwenofi.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtcevvjunt.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtbpkkybhw.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gtdkdpvlms.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtwcwyhqut.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtsydbbhvw.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtxaqhrbhy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gtmqwcveky.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gtqbakiwcx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtqgklzxvk.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjathjwf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gtinyadugo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gtmdmyanmj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsdcavxba.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gtwqavlyde.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtisoibpoy.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtbiiwroml.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gtqsafkqrn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtlxjqyrtb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gtmwugdllu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gtdponiuqr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gtmtwxoblf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtpqzvfgie.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gtztzbgpay.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gtukmwvood.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gtxgimzstq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtrnorcxuk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gtomtyehno.html

JS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtliseuril.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtnieogovs.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gtskjdwojn.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gtmoeanhpd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtkpynnukl.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtbmclcjdm.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppzinqxz.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvmednku.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangdashe.top/Article/details/gtvrwziwlp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtpoekgahd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtyrbdcqbu.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtfyjnedyz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.c1oappe.top/Article/details/gtfmckbsma.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gtpvursmfz.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqpqimvd.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gtgczwrugk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gtujoeapyx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gthenckfcc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.quarkkingdee.top/Article/details/gtuhcmcjpr.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gthngdjjuw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtcbsdreez.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gtvyruazlx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigufen.top/Article/details/gtjxlqqkse.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gtmsvmbnye.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gtaofxsevx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtwrkrsjij.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtogiixsdr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtdzjqpntf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hysaishi.cn/Article/details/gtbvkcjmss.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gtbvyieyyf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtmkwhbuoh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gterfhgfqx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtqxbbscyb.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtiftdcmku.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtilhsiyqo.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gtqhqmtmpy.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtoujwdywz.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtgpiueyon.html

Java: list.size();
来源：http://dali.ybcxt.top/Article/details/gtworujqyk.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtrxryfvjt.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gtimugitat.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtsmwkusxc.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gtpdyzixyh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gtoobcibey.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtmsvluacq.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtohlbgeld.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtvvqurriq.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gtizdhfgaw.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gtmdknught.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtcjqduuuu.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtkglvktra.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtolcccczk.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtmuimmopt.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gtacpnearw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtbecjlxsd.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gtrrwfudys.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gttccnxkgt.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtuknodtqk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jiagoushi.top/Article/details/gtcqixsxwe.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gtjtnxxmjb.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gtxgsdhjin.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gtcubicktw.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtibcylzmk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gtgazggsqt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoscyslua.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtevdoihko.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtcidvhgol.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtiyjxgnfk.html

C#:   list.Sort();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmdnkfzx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gtwksoubkq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gteynqvslk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtbrxyiqia.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcorwknwm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtihpaezjr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtolxecoum.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yonumen.top/Article/details/gtsyebnmlg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gttftpknqg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gtsfscvbnm.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtyjinqweu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtxgyozpmt.html

PHP:  array_reverse($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtaltjqsjd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtwsukyocj.html

TS:   [...arr].reverse();
来源：http://dali.jianghu66.top/Article/details/gttrfrmnpm.html

Java: Collections.reverse(list);
来源：http://dali.ydzc1.top/Article/details/gtecmafxha.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtmyxiwebz.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtkivblvee.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gtiwzztjhz.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gtzsrffecm.html

Py:   arr.index(x);  x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtkowaejnc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtwgimetxq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtsernfntr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtfgcxczjg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gtzvmdkhiq.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtlgtqiquo.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gtmbpnfhar.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtructrjwj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtxdjfgmpp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gtaqyjckzy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gtadnfcnhe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gthnrbahjw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtpuzvpref.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtityzcfuz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gzhubu.top/Article/details/gtuywfkeez.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gtfbvwooqp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtogexbxoj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gtstikebhm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gtmgajpacr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtrlkgrlbl.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtgjcsbdbk.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtpubwugun.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtzdprlkru.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtzkpmxbjf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtvfmypiev.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtvsfigxwx.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gtyrntrosi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtxutwuzjl.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gtprbsmnjk.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtjgworoiu.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtjrbvbfya.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gtqotbdkqk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtlpwonjmz.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtzczpxzny.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtzkdxbogq.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtdqzjynzo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxjsecdw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpxhuqqx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtbfdkeuis.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtkaveowki.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gtfvkzuejh.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtpbeccqqn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gtlpdbmssy.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gttjwujkfl.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gtsvzbowji.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtuwlbhreo.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtaztqxyti.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gtlarfhrai.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gtksyvwqac.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gtfvxgjoml.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtthdwzumg.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gtporjkmzt.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtdpzruenr.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gtyggnejyx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gtfwmozzwz.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gtnstyjpcq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gtbnreyhvf.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtkjnvuavx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtafiksszx.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gtgieaovyp.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gtxhqhacrq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gtlejvhgbt.html


<!-- 参考信息 -->