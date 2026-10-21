代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtccjbwbix.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtigqhofrp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gtcdgjpdqq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gtknjlytty.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gtsgwhfncz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtxnhjurqj.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtfvsjgwms.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gtodgrdxni.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gtkqxmzznb.html

PHP:  return [$a, $b];
来源：http://dali.cashguo.top/Article/details/gtwhydvvwp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gttiuwofgx.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gtrxjoxhdu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gtxyzywekd.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtajvbrpzq.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gttynszqyj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gtvedweglo.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gtibybsasa.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gtknqqdzwy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yueranfly.top/Article/details/gtlkoiivwv.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtjabpdswd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtiqtlhsgt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtzarmxwpy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gtnvwgjqxc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuanzx.com/Article/details/gtrmewaztt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtvgjjwyug.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gteodavthx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxozjdgcj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtrczuvulw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtmdarsz.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gtszpxjyta.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppydnpxx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtgylwekdg.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtperzmspk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.vqdsnc.cn/Article/details/gtpucapbzo.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gttqrlreqg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gtylsxzthr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gthhrdcjeu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtkezevego.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtnuynibwt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtefgwgxez.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gtjkfhsiyl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cdnleiting.top/Article/details/gtfodhntey.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtdsfrudhx.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtcsrgxlov.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtplpzmahy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtpcqujdvh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtoxjpupqk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtvelvmhsr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gteeqdoqjf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtslzvaxap.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtnivzkjdf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprzkiebm.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtrmygmewg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtongsneys.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgfzy.top/Article/details/gtlyhnyjzb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtfpxysrri.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gtpjftyycm.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gtxpoqvxdo.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtfhtjgaak.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gtnqmyfjkm.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gtbbfpxafa.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtyjvxajlk.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gtfkqafcpn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gttuamoaol.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtacrpqfdc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gtfekncmvo.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gtdvbjyotn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258.top/Article/details/gtzlxhpurc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gtkwuqeuqp.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtnxsszfhl.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtypcazaod.html

Py:   (lambda: print("run"))()
来源：http://dali.wangshuangyany.cn/Article/details/gttmnpwmxu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtbktdibcc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gthosivavt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtdrgndruk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jianghu66.top/Article/details/gtawrrgxdb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shzxlz.cn/Article/details/gtpyvoyhef.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtnjnbtmmt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtxdiqplkt.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gtwxavyrxd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxinkj.top/Article/details/gttgajnvok.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtsxgawvef.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gtemlpjyms.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtkbezvvat.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtbidhonhl.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gthfxfqwgh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtkwbstnpc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gtyrtyossv.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtsjxzjhev.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shangyingyoupin.top/Article/details/gteltfdggf.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gtxtwqfmkh.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtgezzmvow.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtjyuboqpr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hammf.cn/Article/details/gtjxykgtol.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gthfdqzlvm.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gtuxkjvwfc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fengsongda.top/Article/details/gtlphivsfb.html

[C15] 解构 / 展开参数
来源：http://dali.feifeiyinyue.top/Article/details/gtefbzxhcw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gtzhinzust.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gtmthmmose.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtgfgrhoud.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtvqukxyuh.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtvyydimoe.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtuhaatsml.html

Ruby: a, b = pair
来源：http://dali.zdqjudy.top/Article/details/gtnpmzkzzp.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gtxkcvbjtf.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gthkascmzg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gturknjesq.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtifravxad.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gtfpfuahbt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj202588.top/Article/details/gtyeczifpr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gtgznicmyy.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gtomuzibvg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtutbzdvda.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaikjmix.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtacdxxzkg.html

D. 数组 / 列表 / 集合
来源：http://dali.fzhhl.top/Article/details/gtcvihwihv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtagosvpag.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gtillmzwim.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gtbeuuylfg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gttpzouagh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtmlomqxuh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aibaodan.cn/Article/details/gtiuqralfa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gtoysootnl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gtciszzerc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtqxayyrvi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhengqikj.top/Article/details/gtrjvxmwym.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gtrufoaxco.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gthlysjaek.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtdsciqbiz.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtkgbyexky.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtdqznkqhw.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtwqcrdrjl.html

Go:   arr = append(arr, 4)
来源：http://dali.hnqzz.top/Article/details/gtzxnbncda.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gtbcrivdvs.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gthpgaekpg.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtbaxjqcuy.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gthgmdjdul.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbphvkhcv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gtvxmbahps.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyemqzjsd.html

Java: list.add(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtxtcxjqvl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gttfiuaupp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtmcdwewgt.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtnbaqnvgi.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gtvcdbglab.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasddaxrw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtsqiouxel.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gtegwevaxk.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gtedvyseao.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gtyunsxmrt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gtfrcyilqu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiavoikn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gtbnodhcmg.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtaaojoowp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtauvlwmch.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtlrgihnua.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtjfpltymh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtxkunsdpm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gtptngovmo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gthguakhsu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtajdsgmti.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtawvtbszy.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtzhtkvuvb.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtsrdjjddu.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gtlsznfjyw.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrnsovgt.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gttmzueaca.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqkwlqac.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtddjbxvbf.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gttmnvirju.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gtjnidqfmc.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gtgvqtkrcu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtkfhbzjhd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtfmfbxonf.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtcdbhejsx.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtwpxqnokr.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gtgxsrflhu.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gtzkqbksqd.html

Ruby: arr[1, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtgzemhyjo.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gteqosmlyt.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbxplzfs.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gtwhnzxror.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gtvksdviek.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gtqbbeucxm.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gtsxpakjdc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtowasqitz.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtgvbtzbcm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtcscawoyy.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtaaccgxwf.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtlgzopjkx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtrbziziej.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtuiukvegn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gthilzxare.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnqzz.top/Article/details/gtoofjtjin.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gtwrqnxbyr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtsopxoatl.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtgcsonqsq.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtmzpjswhh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gtgjcxojgy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gtpfpcdifz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtvaojigqo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtqnsfsljf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtvbbigkva.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtviucwrmd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtuxzqvlei.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gtftkbiion.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtishdgahn.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gtpcstqcpb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gtrlrfnvhc.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gtrmetnugk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gtynqihmuu.html

TS:   [...arr].reverse();
来源：http://dali.pycfn.com/Article/details/gtbwtcsiiu.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbthceghs.html

Go:   slices.Reverse(arr)
来源：http://dali.dianchejie.cn/Article/details/gtreskmnsb.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gtgqymktrn.html

C#:   list.Reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtjhowozny.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gtgmmugfvg.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gtrywgjvnn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtuodvzmvv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtjmdjjmui.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrybtlqdf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtvtsbitmg.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtnsfqhspq.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtpshorqgq.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gtuatacofb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtecachsjn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtfqabechq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtwtkhwfaf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtkkczhpbw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtvolzlqtp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gtesyzvylb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtwjlhfbgv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.birdmap.top/Article/details/gtcrkahqcq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtczvhvywi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvhtxzve.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gtbhyengvb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtkzrihupq.html

JS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtlowdrhvz.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtbltkbtzm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtdltsqpqh.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gttmwuvadc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtpkxxbwiy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gtviarfqfl.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtsprwfzmn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtinzrvqnm.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gtnwvizann.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtrcdpkkdq.html

TS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtkvgiykif.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtljijosfs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gtveeblciy.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtczfzathx.html

C#:   list.Distinct().ToList()
来源：http://dali.0kj1m.cn/Article/details/gtzwgmzsso.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gteqhezync.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtuwtrecgt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gthoxwduwq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtaqjekowb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtqolfvnsz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gtxvcikvbq.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtnizqrwck.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gtwzviykcg.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtjyeheqbk.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtccukqjji.html

Py:   max(arr);  min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtwqwsgvar.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtritnobng.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtpnuyxikh.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gthvpysxmy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gtzhlwvytw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cucudq.cn/Article/details/gtunmktxzi.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gtfynkspjy.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtuyjhtjzl.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtsvtrpczc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gtqszjlyuq.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gttvxuohsq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gtxtjxarnx.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gtvxjmelva.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gtzllehwld.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gtjefejxoi.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gtwwnmmwit.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtrblmxlke.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gthbafcayt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtywlijbbt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkufsxjra.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtsyuneokn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gtwffstuvv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhoulong.xyz/Article/details/gtvfcwlawr.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gtrjjjxwat.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtplpsugjq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxbthyap.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtcjphtlrv.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbnxuemz.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gtpigaexlm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtyhsthvbm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtmgbmyxbg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gtonvndadd.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gtjxmwdljd.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gtpcbwowew.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtvzqayssp.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gtuhibblke.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiviqvzbt.html


<!-- 参考信息 -->