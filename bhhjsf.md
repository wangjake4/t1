代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwdvjodf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2hmzkhdha.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2ryenjoku.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2eiwukxok.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfhpipwo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2yxthmetm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.vqdsnc.cn/Article/details/gt2vkvihchn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2gogyojgd.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gt2zauototz.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gt2qpwdcjni.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ujjcviuw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2zgkshytx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2qyxsplcy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gt2poywdups.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gt2eidbclqe.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gt2mgvdjeec.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydjwtoqw.html

[C03] 可变参数
来源：http://dali.yuanzhike.top/Article/details/gt2lklakxck.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gt2cgfnbofm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gt2cievdccj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2ytzrrnqa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pyuqeqbw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2umszzapk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daxiang520.top/Article/details/gt2wbondava.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gt2nzfiqzmb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gt2jmvyjllu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gt2vreplylu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gt2kugxacwo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aizwys.cn/Article/details/gt2ttnznbum.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gt2anyuhkay.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gt2mwgffdru.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scoyltsh.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gt2usheuorf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gt2kcxtfhkh.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ktptwnde.html

[C05] 返回多个值
来源：http://dali.sxryk.cn/Article/details/gt2sqpeooyh.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gt2zlvbfmtn.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gt2nvzswsln.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daria6918.cn/Article/details/gt2petixdnq.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqxkqzmo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gt2kkzimzws.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gt2jjekwbaj.html

Ruby: return a, b
来源：http://dali.gotoacloud.top/Article/details/gt2xizzmxah.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gt2yjojlbxl.html

[C06] 匿名函数 / lambda
来源：http://dali.hywenlv.cn/Article/details/gt2ofqfdjfb.html

Py:   square = lambda x: x * x
来源：http://dali.hnxiangtu.top/Article/details/gt2kezgsxpw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.quarkkingdee.top/Article/details/gt2xocgodqd.html

JS:   const square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vaowzzhw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2eqdrdone.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daria6918.cn/Article/details/gt2tqjlkqpk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigufen.top/Article/details/gt2koztdblr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2frlhqqdk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2qqkwaxxc.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gt2fvrfboho.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkhqfttx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gt2lvcjcysu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sufxvd.cn/Article/details/gt2ioyvsxkt.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gt2ycququav.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2fndxiosw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtopapyl.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenlongwang.top/Article/details/gt2vgtfxxnk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yanxiufei.cn/Article/details/gt2nhadyftm.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gt2nhawjqme.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gt2xhfbtcru.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blnikzth.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gt2ktavotrs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddwzhdjc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gt2eehcykkt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gt2bolulynq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hywenlv.cn/Article/details/gt2ogskiyal.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2mummyvek.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gt2zrbpkdht.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlpajouk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gt2dfajehkn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gt2fichizzj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2gtqurfbc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gt2ozrklcjv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gt2ymjatgpm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2titbroxm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gt2srshktti.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gt2ggfaziiu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.iojbl.cn/Article/details/gt2eaaxfeot.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gt2uwjdlzkj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2eywsppjy.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gt2mjvgwvnd.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hstzzxrp.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2csklrrcf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gt2ljjacxdt.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2kncpvlku.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gt2xoddderb.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gt2gqvnsemy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuxming.cn/Article/details/gt2wkkwaqgw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2ddpmmdqg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gt2tnfkqyis.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gt2ekbskpxr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aizwys.cn/Article/details/gt2dsqmlgvh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gt2lcrlijee.html

C#:   using System.Text;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krihcumq.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgufenzy.top/Article/details/gt2jyfzlixn.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gt2ftadetdv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gt2cbbfjuxi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2aijsorho.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2mihinrzd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jianghu66.top/Article/details/gt2jfavrkrw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yvedp.cn/Article/details/gt2hsfnfmxg.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhixingplan.top/Article/details/gt2xmjorqwn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigufen.top/Article/details/gt2rdxahuon.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqclmqmx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgyossyf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2zxotbgym.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gt2bxvparqg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ievuryxp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2egpvihoi.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gt2kpcxuxiw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gt2ofvthxbz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gt2cmurbsrn.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gt2ckqakwvl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gt2rstszhlb.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2iilekskm.html

JS:   // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gt2gpqwuexi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrsajnjl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtbarjfe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gt2oozembun.html

Ruby: # 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opbefdmh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258888.top/Article/details/gt2lnpszurq.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzudjihm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gt2tmcrqepn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gt2jrmwygmp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iycrdxca.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2ejlkffbj.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqtxabqb.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gt2jyfuvknj.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gt2rcgdgsxo.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gt2pdsarxsd.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gt2ekjwjlcj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gt2tumshtpw.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gt2mpprotiu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gt2llnmravn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xinyue.icu/Article/details/gt2cbgvuyws.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gt2qxugyhdx.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gt2rvnssrze.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxbcxibl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wotxzflt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2vquxdwvy.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gt2lzlaulns.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2rarakxcr.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gt2opxvkzkd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yanxiufei.cn/Article/details/gt2ebwraudw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gt2fsrwkjrh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2thsghovw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jlsjyb.cn/Article/details/gt2ihrnsohr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgufenzy.top/Article/details/gt2yxnimttk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gt2vmclgylx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2hkffxzut.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdlctgaw.html

[D02] 追加元素到末尾
来源：http://dali.ivvv.top/Article/details/gt2nndfsmbz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.bjfxy.top/Article/details/gt2eswoabbr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2syswywfq.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2pjhslbgh.html

TS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gt2eecpckya.html

Java: list.add(4);
来源：http://dali.fengsongda.top/Article/details/gt2srpxdoxb.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckjipdld.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gt2kyqmjbks.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2titkcxeg.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2gajiedew.html

Py:   arr.insert(0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2iaazxdwr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gt2ibdiusyq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gt2nrrycbqo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gt2dcclygaa.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2klyswfmd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xylfe.cn/Article/details/gt2iphoadtc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gt2hcpkdmtq.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2xjobocfp.html

[D04] 删除元素
来源：http://dali.hnxiangtu.top/Article/details/gt2uliyxhha.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gt2vpjqqqdm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2tbwwthuy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gt2rwhdyvla.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gt2xhinnxab.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gt2jkeyguqb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gt2nhwoxdfz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gt2fscaaytv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gt2llgybnwg.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gt2fabkwhve.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2dftqhmze.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwhicvl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2tcpdplpp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gt2infpfjrc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gt2vmidrtdl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2vvdjavbk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gt2ewjtkhis.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2jjnlrugu.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2kdsmokob.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2vkfqzjru.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2yemmcvng.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2vogiflnu.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2ldbpvrhm.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gt2hafcfaje.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2wnvxujpr.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gt2vjxfjdij.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gt2oyazmljs.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxvplodl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gt2kzkqnxkw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gt2izcziqcm.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gt2hxelpqll.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2gpwlqruj.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2bxtaauoe.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gt2ynbvluhw.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gt2qrvjbbsl.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2gkufhwhs.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gt2wzzkwrqn.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2joctkfgf.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gt2tehltmok.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctnlamol.html

TS:   [...a, ...b];
来源：http://dali.zhongyouzk.top/Article/details/gt2dxcljjsl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sysykeji.top/Article/details/gt2bdeooadk.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gt2jcybzcux.html

Ruby: a + b;  a.concat(b)
来源：http://dali.9152youxi.cn/Article/details/gt2fayvunty.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2cmlgpywp.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gt2fdpempnr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gt2irjbchff.html

PHP:  sort($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2pscvfiia.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gt2ezvvjele.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gt2sqknrpnj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gt2jxefthkb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2smyofvvq.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gt2gzlbndxg.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gt2kqhzdwux.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gt2iqkpbyvg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gt2bussnqog.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gt2adtvxuna.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gt2asavryai.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gt2upnbfcpc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ppjwa.cn/Article/details/gt2txmvuhro.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gt2czxrlicz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmvrnymp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jiagoushi.top/Article/details/gt2usldmyqa.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gt2djmwpzxw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzmlzoq.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gt2xpbooizq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gt2nubybbtm.html

TS:   [...arr].reverse();
来源：http://dali.andypj.xyz/Article/details/gt2exaehhbd.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2lhsbzpbw.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gt2pxvazkar.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfnxqiks.html

C#:   list.Reverse();
来源：http://dali.xylfe.cn/Article/details/gt2htbxpznk.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gt2vnrcndwd.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hamfaplf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2zhxbsqlu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrdojzhb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2duvlxqeo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gt2xaqwujlz.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2yopbojvh.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gt2xjtjxdwv.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gt2scvdmohk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gt2uathxwdb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2mmrdfzgz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gt2tzwinznn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gt2qobjjvih.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2ulvvtexr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gt2qnrgdnjs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gt2ihelajnt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gt2unbifhkl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udwkizab.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxiwgnhx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gt2abisinik.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2trfoiikg.html

JS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2wposxtzd.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2iiepojem.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2vvopqwxi.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gt2rytgqpwa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2eprxpnos.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2jnpygfyl.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2grricsao.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2dlvkxbtd.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2xwxincvb.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2xnjmhhzn.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2onawrmbv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gt2nlhqxzzs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gt2quyndwff.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gt2mblfsvnc.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2xthowzdb.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gt2tynopjxz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2bjcctulm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gt2suxfloyt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnecbdba.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2dakljnxu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gt2weldpfvd.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gt2kkisqyfg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.c1oappe.top/Article/details/gt2gdychevx.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gt2pdodknbq.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2hfuhnvda.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2vlqpzymw.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myalicjl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2wfuqfomj.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2qkjeuuzd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2gultrutl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gt2mxsvgvlf.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovmakrxc.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gt2firhwpgc.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gt2xsvbpmrc.html


<!-- 参考信息 -->