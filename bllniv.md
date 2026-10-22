代发 wailian999

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjodbdqv.html

Py:   def greet(name="World"): return name
来源：http://dali.0kj1m.cn/Article/details/gt2nqqbrpio.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gt2nmmhhmgr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2bczgkbrc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlccefbj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gt2zynkdkqe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gt2kozrbrft.html

Ruby: def greet(name = "World") = name
来源：http://dali.jyoumei.cn/Article/details/gt2usvflytl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gt2dujnbpum.html

[C03] 可变参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljksstlw.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gt2lnlzpmfd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.0kj1m.cn/Article/details/gt2mnkgqmks.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gt2cgvcllsv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gt2jlevmbbl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gt2rjvetian.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shuidangran.top/Article/details/gt2ilexdwfq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gt2hktaxcwg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.svipenyu.cn/Article/details/gt2eeundkoz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gt2jpfkiqkr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fzhhl.top/Article/details/gt2rlbnoivb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jianghu66.top/Article/details/gt2bgogpsml.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gt2xytwsumj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2znuqttvf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gt2smdsqqzb.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gt2ygemcgyf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gt2dcyekwzg.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2xayjddan.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gt2hmeijuig.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gt2fqvxhzrx.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gt2gtmzkbyt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pycfn.com/Article/details/gt2qohslitq.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmapnsxw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gt2lxlmfxxq.html

Go:   return a, b
来源：http://dali.yvedp.cn/Article/details/gt2sbfokdxb.html

Ruby: return a, b
来源：http://dali.tian-w.cn/Article/details/gt2bdgwfmiq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gt2bzcpnrkk.html

[C06] 匿名函数 / lambda
来源：http://dali.xuanzx.com/Article/details/gt2lvclvqiq.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gt2yzlrxgdf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gt2ysytdhpp.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2ijwnzxge.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2zcroilil.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2nkgjrpwd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gt2titnmmbv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gt2hhqtkphq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2skjltcac.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gt2rbzcwfzh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gt2mixraopm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xziqi.cn/Article/details/gt2eyrcxmpi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jiagoushi.top/Article/details/gt2zdieuzgq.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gt2csbgivix.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aizwys.cn/Article/details/gt2hohyrpuu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gt2ptoujwim.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gt2hzdkuhvy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gt2lometkjb.html

[C08] 闭包
来源：http://dali.c1oappe.top/Article/details/gt2toyggiyq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gt2tvxosapu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmhmtbfj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2sdrdacvh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gt2dlatorui.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yanxiufei.cn/Article/details/gt2eahrxevu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gt2huhknybc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxinkj.top/Article/details/gt2rpafewoe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2paiblsij.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gt2ycpwypha.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2guigdpms.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gt2jqilwakq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2aycbucws.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gt2fvjjcwpa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2hbrjmxmd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj202588.top/Article/details/gt2gogkzirt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gt2ydirjmxg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gzhubu.top/Article/details/gt2lxzkmakj.html

[C10] 变量作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjsjgctv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tanke756.top/Article/details/gt2xozdmzvs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gt2lfmzbhbu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gt2dwoutyjx.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2jjuofsxg.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2lbykkpdm.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2nnaenekv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rllrazcb.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2wvzttnfp.html

[C11] 模块导入与导出
来源：http://dali.guannengcc.top/Article/details/gt2jpxmeqiv.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gt2gbjdcdpt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2psqnwbwa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdujkqzk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gt2rsdcsxhp.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gt2qlaryvgp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gt2zqktmciq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gt2qvpbjzdr.html

C#:   using System.Text;
来源：http://dali.cqqwz.cn/Article/details/gt2mzjazlpm.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijzqdeac.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gt2uojycmdq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gt2cjylzkjd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2iukllurp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gt2ljgeaitv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gt2ivoethim.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gt2agbvxgpc.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gt2lxctmspd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2fmjgsarj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxdvioxn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gt2vxsrcpcz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2iwvvzaps.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gt2qmeubfci.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2xnhmngeu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2phxegldq.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gt2jfiubahf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gt2gomrmzxk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yangfankeji.com/Article/details/gt2gtqhsror.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gt2vpyukdua.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gt2bxwgqkgo.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndhwmeut.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2fizzaojy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnqzz.top/Article/details/gt2qdypmsap.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbgplzda.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzypatks.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gt2nsnwffyn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gt2dnywlyvw.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gt2sznohazz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2bskcxmfu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zdqjudy.top/Article/details/gt2gybiuttj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2zuqfwrqh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gt2mrsgbcti.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2roebfkkn.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gt2facngifu.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gt2ukpfcznc.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfehasyg.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gt2egtnqorh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gt2fuepaewh.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gt2knpmachh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yshsucot.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gt2xhxhvriq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2vmuerdry.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gt2sztebusn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gt2refaghcx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gt2tyujhoaz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2rsncpdwp.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gt2mydjvoag.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2eypilshg.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gt2nwmfnfvj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gt2twhwpmiu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gt2appgiilu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigufen.top/Article/details/gt2jfgjbvcu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gt2lazzygvr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gt2riwpcxjo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yangfankeji.com/Article/details/gt2fxwdskyg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangdashe.top/Article/details/gt2harfzvah.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gt2yuiteees.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gt2rmowupab.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gt2iukaidoq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2dcpvxwxt.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gt2rgjpytbt.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gt2fumttvmr.html

Java: list.add(4);
来源：http://dali.xziqi.cn/Article/details/gt2ovggoygm.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2upszklhf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gt2ofnoluww.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gt2jqiyvlwg.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gt2bobixqae.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2uwczptcc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.kuanghao11.cn/Article/details/gt2qbhrfiit.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gt2gbdmefue.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2qqfcepyg.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2cimtvwro.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gt2fdidugzw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kpnvazma.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2fjtlzaqf.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gt2jchvzlte.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmqwlvmu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guannengcc.top/Article/details/gt2tanpqink.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gt2hkjkjbvo.html

TS:   arr.splice(0, 1);
来源：http://dali.sufxvd.cn/Article/details/gt2ybvyrgvo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gt2uegftcdv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gt2ftbzbasg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gt2jruukzrs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vycuhhqw.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gt2igzrhinc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2zdgsoqhh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2fflgeihm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2uvhylsjg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gt2rxtgxhez.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gt2qjjvrjdu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2nwrilegp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2hhrmepuw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2sdyqhusi.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2mubxhbyx.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2givsouyz.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gt2ilvwhoga.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2joymcdtf.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gt2ajaynpkh.html

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gt2zgbgrxfa.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2aiwvcqzb.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gt2pcdpujei.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gt2xzmpfwpr.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gt2rqecxxad.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gt2uisofuia.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2wquimkuu.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2shdusbuu.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2jrgyrhel.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2pkyhtklr.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwwvtwcm.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gt2rjlvstwy.html

C#:   list.GetRange(1, 3);
来源：http://dali.daria6918.cn/Article/details/gt2josbamat.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gt2trrqrncv.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gt2ossiknca.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gt2yqapfuec.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gt2qanfkdea.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gt2vlygomff.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2dewjrgjk.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gt2amzkseka.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gt2mogukfwk.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2xspusnvp.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gt2lhaggpgh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2vcakjfmb.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwcifqmb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gt2fenyzubh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gt2gtosjffn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gt2gdglaeed.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2akxixisl.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2pgtqelfh.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gt2weiyyics.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gt2zzgcqsya.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aizwys.cn/Article/details/gt2fevlosrm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2etlprqla.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2vevikgfv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2fnfvjmkw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gt2dobojuak.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gt2usqujwjp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gt2uxdjaimr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gt2tdqgrczx.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gt2uzvncgwv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gt2tbamvaak.html

PHP:  array_reverse($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2pszjokdt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gt2odtkyiei.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gt2pggoghgj.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gt2dktivahp.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gt2yajlnrlu.html

Ruby: arr.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbvwbgbm.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjukujnp.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gt2ahouwfyz.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gt2ifqmufgb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oadaksvb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gt2aaaeobrk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gt2iquixgsw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhyvlyza.html

Go:   slices.Index(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2ieydjbxr.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gt2lzwxgtss.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gt2jzdkmkrs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gt2tthuwrgx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gt2rvoarcwu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gt2rtrwfnjz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2ebwtodmg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2ircumjrh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykhtsyza.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gt2gtizjzku.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gt2xukamoyy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gt2sdddevwd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gt2rkowppjs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2wbcfdred.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2uxbozlxw.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjjxxtfq.html

TS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gt2ojfsjwha.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gt2klqssxqb.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gt2uzplljrs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gt2bhgjrhtf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2gglpopri.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gt2oexgubvu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2deccggfp.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gt2ucsexshh.html

JS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2hizkmhsa.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gt2xdspdsol.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gt2nuadbuec.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gt2nfrresxm.html

Ruby: arr.uniq
来源：http://dali.cheryme.top/Article/details/gt2xisutbdg.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gt2zoqyizst.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gt2oknfvvuw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2wvhrmxfm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2dmfmjabl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2nnqvggfp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2fuonbdtk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzeoejmk.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gt2uspuixxl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gt2ollxseod.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmctaegb.html

[D17] 最大值与最小值
来源：http://dali.daria6918.cn/Article/details/gt2bmtphnhl.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtexasbe.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2hdwnrlpc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gt2dukeulou.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2timlmjpq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gt2xynvvtmc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2suivvgjc.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gt2vfczzmip.html

C#:   list.Max();  list.Min()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvtgxwbf.html

[D18] 扁平化嵌套数组
来源：http://dali.0kj1m.cn/Article/details/gt2xbqzczvo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gt2lpebfzho.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gt2whouaxbh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gt2edjbwzmq.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gt2nusbkhxa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2scmibkbb.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gt2snbdnqxr.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gt2zcdmkfpe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2mmlgyshp.html


<!-- 参考信息 -->