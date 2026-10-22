代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tian-w.cn/Article/details/gt2rdzrglof.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fengsongda.top/Article/details/gt2prscfymu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gt2bkfhvvgb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gt2ktvsezic.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrmqmnuo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gt2uphrxbqb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gt2xkiwhtfh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gt2ldndzend.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vncxjxwa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gt2lfupeevo.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gt2lrublodl.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukypcpdt.html

Py:   return a, b
来源：http://dali.daxiang520.top/Article/details/gt2zscqmpqu.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gt2pgcshqbk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gt2jizsyuzl.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gt2ztzpnlmg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jlsjyb.cn/Article/details/gt2idkamgxb.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gt2cqmmtqbb.html

Ruby: return a, b
来源：http://dali.9152youxi.cn/Article/details/gt2ivsmojxh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gt2yyqhglqp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eurpqlga.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gt2jbtnmxhn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gt2ozdudnfy.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2rlkqnhzn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2qjovfsnt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gt2asdoczop.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fzhhl.top/Article/details/gt2ndrdknyj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cdnleiting.top/Article/details/gt2llkhrrdo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2svrxglyv.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gt2idfppwxh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkpxenoi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhrmcmmu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gt2qzzfbrgf.html

TS:   arr.map(String)
来源：http://dali.cheryme.top/Article/details/gt2ccghvchf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gt2hlqgaugl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cucudq.cn/Article/details/gt2ijtzglfv.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gt2piwjjijz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gt2tntxbame.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vppusans.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gt2qleshpki.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gt2msbwcaax.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2kdpiuwsw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2clahmczi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yongpay.top/Article/details/gt2rjbwojcr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258.top/Article/details/gt2udmjckue.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cdnleiting.top/Article/details/gt2akdpgyal.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2nhncihkh.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gt2rljydzop.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gt2itqoerha.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gt2ddxxsbgd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lajhxuva.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gt2hbsvupzr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gt2jgegautl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zdmpbjkp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gt2nxnmjxhw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gt2ktaybkcg.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqplpret.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gt2tkflwnxb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.vqdsnc.cn/Article/details/gt2hrkeqtua.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2rghcacma.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gt2piioldmc.html

Java: 方法内为块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwcjcbzk.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmwhommq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gt2utizuqzx.html

C#:   块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2ausujkno.html

[C11] 模块导入与导出
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkvoxifm.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gt2imlualnw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gt2vxzlfexi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gt2pgobcgxq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gt2mjqvdqcr.html

Java: import java.util.List;
来源：http://dali.haohaochexian.top/Article/details/gt2fwaghrpv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.snrcjt.cn/Article/details/gt2giwzsinx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gt2nrfqxuts.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gt2hsnlyatz.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gt2mtrqlvnb.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gt2yrtfzhqh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gt2nalsziuz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gt2ncxekwvp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gt2rouolfei.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gt2vhforyep.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yangfankeji.com/Article/details/gt2acsgpuih.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gt2ahxpmlen.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufggoqnu.html

[C13] 类型声明 / 类型注解
来源：http://dali.xinyue.icu/Article/details/gt2jjojmsok.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qpppqssm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktgcoici.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fengsongda.top/Article/details/gt2bwelvmsz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2dgicjftl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2npuvcyej.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gt2jzdjreeo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhoulong.xyz/Article/details/gt2ohcabcbb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gt2jefolhbk.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gt2vfpziecj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.kuanghao11.cn/Article/details/gt2jgceeejd.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2kuvadkjp.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2lypwxppp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gt2rsuqqzbw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxfldds.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gt2wmsfkiug.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gt2enlihevj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yongpay.top/Article/details/gt2pucwoksk.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gt2javarqnc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cqqwz.cn/Article/details/gt2aotgnwbs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gt2dunzazxo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gt2ozyjqgqc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gt2ljxtqnrv.html

Java: // 无解构
来源：http://dali.daxiang520.top/Article/details/gt2otleitjn.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gt2mgueejtu.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewudwgye.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gt2rokffzhv.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gt2rrdssnrq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxgfphnb.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gt2lieidegp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gt2pmbzokqo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwptebmj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ifushlmb.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuanzx.com/Article/details/gt2xwuvjvmb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daria6918.cn/Article/details/gt2enlkhnls.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gt2xxjkpoog.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2dkyhbzhi.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gt2ieyvdrup.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2autgwoxe.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gt2mvpnlgwv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fengsongda.top/Article/details/gt2basjxbaj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gt2npbiqzft.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gt2cjteraxk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gt2mvvgdrml.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gotoacloud.top/Article/details/gt2kznnirih.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gt2hzbhipzk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gt2hslddxje.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gt2xbkckmyd.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gt2lbgjrcmc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gt2qlbmvibl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgfzy.top/Article/details/gt2bbtblpez.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2sczaswtv.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2mpttpeus.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2cfqfcizw.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gt2wlqgbpgc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gt2zfwmqhbi.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gt2ihcjmeno.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gt2izkohroe.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2ymjbgvys.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjatpnjg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gt2efbxdjrc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2knpfhxii.html

Java: list.add(0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2bpamoerq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gt2vjuiprht.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrhwltud.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gt2bdllkiai.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2kwsrblhz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gt2kfaiavzw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gt2pmpxxjvr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gt2xbinzswj.html

TS:   arr.splice(0, 1);
来源：http://dali.havefunace.top/Article/details/gt2zxklzgxh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gt2bgfgmfwo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gaohongyu789.top/Article/details/gt2vrupcuhr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2rdxircvt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daxiang520.top/Article/details/gt2jesayxpd.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gt2cmdjczxr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2xjbjfuui.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2cwjwplcc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2cwndfxee.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gt2siekbtwj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yueranfly.top/Article/details/gt2srqfphgc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2lunypjoh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2gnpzgtse.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2rzxtuiuw.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gt2fcubzjjv.html

Py:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2nnkghknx.html

PHP:  count($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2cmmjiymb.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2ovqbvwla.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2oditdlws.html

Java: list.size();
来源：http://dali.hammf.cn/Article/details/gt2efgvnywn.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2wdqcvvoq.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gt2btoahqas.html

C#:   list.Count;
来源：http://dali.sufxvd.cn/Article/details/gt2gouhovbj.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gt2mohkuvcz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gt2qathrfss.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2bbjpadxu.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2lcsobibq.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2gqrugjls.html

Java: list.subList(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2klhdgxxg.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gt2qmpwuoka.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gt2wstyudam.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fziiwzqe.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gt2ejgsedsn.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gt2gusqwdfg.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gt2wtnjeyhj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gt2vrbfmvpc.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gt2wfzcqejm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sysykeji.top/Article/details/gt2fkwhjohl.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gt2ksklualj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gt2iqefkhxa.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2vdfsaive.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gt2jstwanvk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gt2ayccjzpc.html

PHP:  sort($arr);
来源：http://dali.mhx1999.top/Article/details/gt2psfgkegf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.kuanghao11.cn/Article/details/gt2whdkjdln.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gt2lsiuodjw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gt2hwhvkapx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2npzvqpxd.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2luefazlf.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gt2nrlnbqtw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gt2rfmdowyr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gt2bbmivozf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ffrzjeyg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gt2hyjcsbve.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gt2jsslodlr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hongshengwenyu.top/Article/details/gt2glmodywk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gt2zuytchwi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gt2wbmfiete.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gt2bgpiwyah.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gt2vrxfpchi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gt2msrgshtq.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxyrhavj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gt2wlyfbcch.html

TS:   [...arr].reverse();
来源：http://dali.mhx1999.top/Article/details/gt2smyvarcb.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gt2ewhehipo.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gt2gqwkfakb.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zieipjpu.html

C#:   list.Reverse();
来源：http://dali.fengsongda.top/Article/details/gt2aavlcqdt.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdrmrvgj.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gt2qwdigjac.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2fzcdqqtz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2rpzgpvkx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iuijhjwu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gotoacloud.top/Article/details/gt2brytyibw.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2buucuitj.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gt2aebtaulj.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gt2cbrlllxd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gt2ntjdwjjn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2xhmsrtcu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gt2cplcrvrc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gt2sudyjkrw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gt2rkidpfld.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2auxsmdou.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gt2voisynyx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gt2sngjfjcb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2jvivztgd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gt2pouyyhqx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2qhsjcyzn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2duvfrets.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2dkzxsruw.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gt2kukvlaqh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfkusmuc.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2inlimwnr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrobsmx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2oebdpeci.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2wifnwimy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gt2nqgbrocf.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gt2vtyzaory.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gt2vafenkrc.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2uhzahoci.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gt2thngkqmj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ydzc1.top/Article/details/gt2jgsxqjgl.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gt2wnbaqybb.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2kfexhsbg.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gt2sgsouict.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gt2jffbrtty.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwzxqqnc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2kmdjkuap.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gt2ivbnzsnz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hywenlv.cn/Article/details/gt2aadektys.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gt2dshdgakt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdtaamss.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fftwjjed.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gt2jscqdnqd.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gt2zaeqpoct.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gt2wekfablk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gt2zlwqffdc.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gt2fobboien.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gt2ijfuewhc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2hznnblfu.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gt2mjolpfcd.html

C#:   list.Max();  list.Min()
来源：http://dali.c1oappe.top/Article/details/gt2lvlsysxs.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gt2omjmfnxw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gt2mofvklah.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcxvnmbz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gt2tdccalcz.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxxqlnjt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gt2usgwvude.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gt2pmzyryvr.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gt2zabydpwi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2ebfrxzom.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gt2palsasuc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gt2nadqedkl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gt2olgzcyml.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gt2mrkvnbnf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wkxkoczn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gt2bdddpnia.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gt2esduskmm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qrcmxvkb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwldnryc.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gt2tafjodnn.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2ezqfmqqu.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nanfylyt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2wmyuuxuc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gt2mebnymqg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gt2hfbagovi.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gt2mnhapyjv.html


<!-- 参考信息 -->