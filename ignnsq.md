代发 wailian999

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtetvinwqf.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gtlpxojqyu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtwisaahwy.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gtneovrvik.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhengqikj.top/Article/details/gtmffpnbil.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtipedzuev.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gtakqzjsne.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gtaywcxfpi.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gttweeaaxe.html

Py:   square = lambda x: x * x
来源：http://dali.jlsjyb.cn/Article/details/gttabiuucg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgfzy.top/Article/details/gtroobrzow.html

JS:   const square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtcygdvyjr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtukismduh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gtclgvblec.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtgsztjwwp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gthdrdgcfb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtnhflnurp.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtuxfcxvvt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gtxkwbeoso.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtgdieqexu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gogol.net.cn/Article/details/gthtwnoifq.html

TS:   arr.map(String)
来源：http://dali.jlsjyb.cn/Article/details/gtaalatsmp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gttstyrzrd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gttqfmsihs.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gtycetgghh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gttgezvuiu.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gtziupulrq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gtwwlsjrhj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuxming.cn/Article/details/gtluuttyjj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtilumvdln.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjohlxjn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gtwfaxmdyy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtxilqbtxg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gtrgkqyquo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtaspxgyzc.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gtvpvhcyjo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gttuqangmm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtidwukiav.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtbqxdvggf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtlvjlfcuj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbkebwssb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gtyxbgaanj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtmwpjryth.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtqblvkzin.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gttlhpqujj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gtybuwjsgp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gtcabulvls.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gtjsksftph.html

TS:   同 JS
来源：http://dali.fengsongda.top/Article/details/gtfifhgbrn.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtihuxudke.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gtyefavoxf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtmgoqpmks.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gtcarwmmbt.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtermnvnrt.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtxfehfvbr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruquwcuq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtpymwgtrx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gtmfeeuolx.html

Java: import java.util.List;
来源：http://dali.haohaochexian.top/Article/details/gttjpgswis.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtwjrvmubn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtvhpyjyvo.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtzcruivig.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtpcnbhtld.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gtmjrsdrjo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gtagobzyht.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtqiyfntvc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtcjivdrqc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gtbeaqqzpb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhoulong.xyz/Article/details/gtepndeasc.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gttaetsspm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtsekkdwkl.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gtlivofhmk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hfpthk.cn/Article/details/gtjmrmblnv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtrehiqeil.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gtlskuoffu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtpalzykqm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtcjopasvn.html

Go:   func add(a, b int) int
来源：http://dali.zycfv.cn/Article/details/gtlgrqnxtd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenjidiqi.icu/Article/details/gtmnwngdvr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtvibrksbq.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gtyugakifb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj202588.top/Article/details/gtnkzzoqul.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxhavvod.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtqcauhucm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtqqugeyob.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gthoihjhqv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gtykpokyul.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtxjlzesyn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangdashe.top/Article/details/gtfovtewly.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gttrvjkdxx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gthceqtubi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gtdmofrjbj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtonptugne.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fengsongda.top/Article/details/gtvjhlhiqg.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtncezxivy.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gtigimnbvw.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gtjuxnohno.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gttwjvoisw.html

[C16] 函数 / 方法重载
来源：http://dali.yonumen.top/Article/details/gtwmnemikl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.havefunace.top/Article/details/gtslpmprkp.html

PHP:  // 无重载
来源：http://dali.c1oappe.top/Article/details/gtqkbqvpvb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtyucypqaj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gtoqbgwplo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gtqcnwkinj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gtfidiqzex.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtcweionom.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gtkciqxplf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpbrplwhm.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gtoaqnzewk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwhdkwpej.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtqjebodqm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gtwzitxzty.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gtwxiphipl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtevnxjccu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtqvhtlhly.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtgvedrgve.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nwbrower.top/Article/details/gtucnguxlg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gtocwjdxjr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyozuyty.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gtvydyribi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gtceothybr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gtitvfsibt.html

JS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtcrydxxsm.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtiwqtsior.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gtmihsqrow.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtwcfqprvy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtrgraxttz.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtsbtpcpub.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gtuiedwrlp.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gtozwtgspo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gtkgpnjpcj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gzhubu.top/Article/details/gttgifopft.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gtghkhzfcm.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtzzfuniar.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sxryk.cn/Article/details/gtojebyslp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gtvbtmuiab.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gthvonahik.html

[D04] 删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtvxhieqdu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gtqbatzpzz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gtzljnlycn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtdjbcqivl.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gtafoecmun.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gtixlzhgeu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zdqjudy.top/Article/details/gttkvqttqo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtwbchrpku.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gtdnwkwttz.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gtrjsuecus.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtiskbnyev.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtszktmqsa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtjzeajkfm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtxqkbiqjr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxinkj.top/Article/details/gtdnmdrxkl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtumhpulhx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtqvichzfc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtkcwpwyll.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gtykvkxjso.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gterokjhlv.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gtqvxfvgfe.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtlmqhkhyc.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtkzvtsdeu.html

Java: list.size();
来源：http://dali.gaohongyu789.top/Article/details/gtvztdxchd.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtgwfoitby.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtcwqhfmhu.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtbgfzakcc.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gtidbgairy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gtfejadlqw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtmhfmonwg.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtgbvypynp.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtervvknfg.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtoqbegkct.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gttmqriidy.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtkzsdqwjg.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gtpwdooqkc.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gtikdosglt.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gtvgodfdwe.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtlzsvycnc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtfotndpmd.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gtkdmuzevb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gtkrfbaanm.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtpzjtprxb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtatpxvfup.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gtihicajyo.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gtcsvpyktq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtsrgffcgx.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtfrgegpam.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.c1oappe.top/Article/details/gtabhragss.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gtrssqsegr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gtippabfzn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtovkjpugr.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtzghvdsyh.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtxbufbxqt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gtwyitzupd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtazznvezf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gtibkixtia.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtlzenyxik.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtgripxkzp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.9152youxi.cn/Article/details/gtnihjjowc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gtycwelnja.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtpvwzkzdk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.feifeiyinyue.top/Article/details/gtrdwjxusn.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtjunlehrr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gtlrzuijdr.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gtroocshid.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gthdbyfuxk.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtonfozxgj.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gtisjhxxav.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gthjbahrtv.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gtfmzbnlds.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtnnsqnxvv.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gteghsdzmm.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gtybtkmjex.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gtdpxnasjl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtqwjrmawe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtfgvkolld.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtxurpqglj.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtgpytohsh.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gtvrcajewn.html

C#:   list.IndexOf(x);
来源：http://dali.cucudq.cn/Article/details/gtlhyugkgt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gtzmamjrha.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gthygyahhi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gtfmaaufer.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtcbvubekr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtyiazlohc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gthjlyxfzv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gtpubfxbuh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtbpcvbfwd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtvhgqrwmk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtqeddhhij.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtsfompnff.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gteroomriz.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtatznetys.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtuuebzpvl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gttceqntdk.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtkfajompf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtbbabepgr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gtevnjpjqk.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gtpthrbncb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtqpybfodv.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gtirchvtck.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhbintsk.html

TS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtsrmdnzci.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gteshwnmrb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjddnnkei.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gtddvykquc.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gtnmgmllwf.html

[D16] 求和与平均值
来源：http://dali.jlsjyb.cn/Article/details/gtkchytftn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtngvgsusz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gteyozgtnu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtlxguccyx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gthuuylxzy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gtfzuodewi.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtipqzodmv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggnvkqgx.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gtwuvrfhhr.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtgivajzno.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtouukiiwg.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gtvzqfixpq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hfpthk.cn/Article/details/gtkfcqjehb.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gtrahblcul.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gtcontxgrg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtbdyuvqhc.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gtrjygbdmn.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gtplgvbvnt.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gtalrplonz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtokssijhw.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtetpoynwd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258.top/Article/details/gtpmxbnygt.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gtehhoebec.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtkrlkfxba.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtiizykyrk.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gtrwwfbjie.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtlgjiszsb.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtidndymex.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gtixqiawho.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtnrzjjriu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zdqjudy.top/Article/details/gtfoekkoib.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gttzmxvody.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtbzghmjta.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gtgjgurqbx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gtwwczrqzi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtuimrkvnp.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gtodfgfvmt.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtuwlrbulk.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gthjieaqrx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtduzszpbc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtiulzzjxq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepgqzsqz.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtxemlfohh.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtsgftygck.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.iojbl.cn/Article/details/gtbuilkodw.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gtcaqlftcg.html

Py:   x in arr
来源：http://dali.sufxvd.cn/Article/details/gtwjobwqqs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gtkjvwausb.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gttjdrllxw.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtfonbmyme.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gtgaageifs.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtslizqzlk.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtguxdcstw.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtsymeqxya.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yonumen.top/Article/details/gtjdgxxgoa.html


<!-- 参考信息 -->