代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtnexhqujc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtxvoypjti.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gteurpzalr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gtjikhkdan.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gtsqtgylev.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsixdkas.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrclsxjr.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtzccndhwv.html

Py:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtpxkajbkt.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtbokgbyuw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yonumen.top/Article/details/gtjghvvqvh.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtvufzjowz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gtxghsdrpg.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtsaaimrzt.html

Ruby: return a, b
来源：http://dali.hysaishi.cn/Article/details/gtytudfphu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzqoktry.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gtrncmvkwo.html

Py:   square = lambda x: x * x
来源：http://dali.xuanzx.com/Article/details/gtmdreowvn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtrpbmjbgy.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gttyfqfprj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangdashe.top/Article/details/gtdemuaesb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gtslwlcsjw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gthlgxqylc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gtejwmkyyg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtvuyqsgex.html

[C07] 把函数作为参数传入
来源：http://dali.guannengcc.top/Article/details/gtcfgjraeo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gtmpdiqjdr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtlrhewnlx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gthxidpyva.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtpsgjwrjh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtcsiawqef.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.svipenyu.cn/Article/details/gtufjaryfg.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gtpiklsqtg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gtmqnngnft.html

[C08] 闭包
来源：http://dali.aibaodan.cn/Article/details/gtlvovrkxx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrbkydte.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gtzoazxohm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtebnawcov.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtufkihqdn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gtnqeiltob.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangdashe.top/Article/details/gtdwiifagn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqglytolk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvfzcjueo.html

[C09] 递归
来源：http://dali.zdqjudy.top/Article/details/gtxpoxvkyz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvrlycrsq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtychbgykp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtxkqfdcor.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gttemynfvu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtzwgfigde.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gtfscjnagf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtbawmwkhk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtopawzqwg.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtaatxaojr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gtixpuhfwc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aibaodan.cn/Article/details/gtfcscenbz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.haohaochexian.top/Article/details/gttisbmwoo.html

TS:   同 JS
来源：http://dali.jyoumei.cn/Article/details/gtwqdjcxop.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtalkfytyn.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gtzsioqjaj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtacvoegmn.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gtznmwphdp.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gtayidbsbj.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gtebbtozix.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gtdaqjnvrp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtglusmhza.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gtaazzinwe.html

Java: import java.util.List;
来源：http://dali.svipenyu.cn/Article/details/gtvdubbwla.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gtmpqcpygc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gthdwcwfbk.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gtmzkmdcuf.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtjvatjcmo.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gtmubgdhbc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenzaomai.com/Article/details/gtdszkanys.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtnmxmrlcu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtkgnnwxvs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gtojbgqkgd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtiicxhazc.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gtodaaiihw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gtsejptfsq.html

[C13] 类型声明 / 类型注解
来源：http://dali.sxryk.cn/Article/details/gtafsrrpmd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtmdizlwcx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtnfqulmky.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtturhtquc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtyvvbavec.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtmfhneoeq.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcjmoeii.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gtglfmhnri.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gtlfioqhjb.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtydvebssw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtjtfemmnp.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gtlkbfnufb.html

JS:   // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtwdlgsrft.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cheryme.top/Article/details/gtzbvglcnx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtgpatcqek.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jlsjyb.cn/Article/details/gtadrsfmfv.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gtmbyzwuso.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fengsongda.top/Article/details/gtgyybznmh.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtohurgbgk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtzvbiawjw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gtqiepbgyy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtcawerbsf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gtacvbvqcf.html

Java: // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtgouhaygs.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtcynimfrw.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gtvwplkteo.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gtzvaohiaj.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gtwidijyjm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtjrbpizvp.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gtgcjqbfhn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ydzc1.top/Article/details/gtjstmzlba.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daria6918.cn/Article/details/gtbgaunrmr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwtninwz.html

Go:   // 无重载：用不同函数名
来源：http://dali.mhx1999.top/Article/details/gtgofiyjcz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gtlaquemtb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gtodanbuiy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwkycpqql.html

D. 数组 / 列表 / 集合
来源：http://dali.sysykeji.top/Article/details/gtbithrdss.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gterkoyyio.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtmsyawqqz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtqzxizxfs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtbzwqafzc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtboixhfsi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gthntaxiiy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtwrvfrnba.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnzphido.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gthwfffdut.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gtfbhogylv.html

[D02] 追加元素到末尾
来源：http://dali.yanxiufei.cn/Article/details/gtlrpmkpfy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuxming.cn/Article/details/gtahcddqfb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtaobntban.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtlihqwtdc.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtkntrhhgr.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gtmowfntng.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtteozilnx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gtvczcxbso.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtbjyuivze.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gtcozjsyjr.html

Py:   arr.insert(0, 0)
来源：http://dali.tian-w.cn/Article/details/gtkbajtupk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gtxqlsikwc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gtvwgtpsaw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtufmlahqo.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtbafiikje.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yongpay.top/Article/details/gtjylopkpc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gtfbtlojwx.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gtzkzqgeyf.html

[D04] 删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtizuhgbch.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtgfhyxgsu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gtjgtybdyj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gtbhrzovis.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtnzbneejf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zycfv.cn/Article/details/gtaqetrhxo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtpdpzlkph.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvesckxz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gtynrvhnml.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtriadewdo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtzdlthpzc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtjkycqtda.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtwrprkzhx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gtcioanbfm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutsidelj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtkfjhofac.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtxvwitktp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtkjhfsnal.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtqnhrmepm.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtlvbafbqm.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gttpvtzceg.html

JS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtbtqzoryy.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtgyrygbmv.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtyyykfoan.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtfewdxfwv.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtgzjxgfrv.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gtjtamjjgc.html

[D07] 切片 / 取子数组
来源：http://dali.nanxuanxn.top/Article/details/gtnmndlcsm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xinyue.icu/Article/details/gtoutrifhq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gthelruupm.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtvpzzbiez.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtawqnbeuo.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtctjxrfqd.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gtkzmjihkx.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtktvuvhpk.html

C#:   list.GetRange(1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtxpttumbm.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtwjttkooy.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gtsrjnxqbl.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gtxpsscntc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gtolylwinm.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gtcxamstln.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtgwwksakp.html

Go:   append(a, b...)
来源：http://dali.cucudq.cn/Article/details/gtdfjakdnb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtdlykwwzk.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gtwtcsepnc.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gtncigdfnz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtwmfjcfgj.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtxbhqittu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gtfacoilut.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtqkaiuhsz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtrwtvpqxw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtlaruzfda.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtwuprouub.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuplfpky.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gtrsoslimu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xylfe.cn/Article/details/gtwlplxtqd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtgzmipxgu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtvbegojcv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtabsfhuuo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gtlndycfqt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gotoacloud.top/Article/details/gtzdqclpqo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gtrobledrx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gtbsicfgoz.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gtlrhszuib.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtmfmviheb.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtyiiluhmn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gtplyymoqz.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtgbtgcuhz.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gtwofbpplp.html

Go:   slices.Reverse(arr)
来源：http://dali.daria6918.cn/Article/details/gtzuxcbcsd.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gthpmlenhs.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gtproxxdio.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrcxjenb.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gtrlqardfx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtjzuhuzvw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtbeukbqnj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtjevdjopr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtxtdbhtye.html

Go:   slices.Index(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtpmkedogg.html

Ruby: arr.index(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtxumyqmtj.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gtstriafjj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtxgdogvcp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gtxvsbqspp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gtvankpqov.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtoplhbsdp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtglgvhlkh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yonumen.top/Article/details/gtvtbeqvri.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gtreenajzu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtygbkxbwd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtwruorepg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gtfasllklv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkulvfvba.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtokaodnjw.html

JS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtliyatmiw.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtefqxucwx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtqxtrkbbq.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtqrpzkfpo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtwuryhdwd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gttfoyalxj.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gtbgokpzwa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtskvjxezp.html

PHP:  array_unique($arr);
来源：http://dali.fengsongda.top/Article/details/gtcobpesjb.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtnqapzuma.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtmytpngab.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gtgnxvokzz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gtrajyybgr.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gtxcbnngip.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtowflcebp.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtypxfstzm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtspirkyoe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtoqtfaesn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtvrlorery.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtxbhumhfv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtnntuagcm.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gtnhkahcgg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtkheyyfsa.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gtocmhzcdw.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gttflnjsze.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtugufhcgn.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtemeitzvc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gttekxkunh.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitquvutf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtrugbtkjy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtkhtfmpqk.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtjisqsupc.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gtzieajjrn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtwrbpkhzu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gtvbbkufeb.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gthljlklez.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gtbydpfxed.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtxfiapcyo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtockgdnxm.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gtjbwxbizw.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gtinpiyixr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtkbkpjlsg.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gtnvmhfjlz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtnnoewqac.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jianghu66.top/Article/details/gtdtkdqjfg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtnvwjsqqj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtqkuvqffb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gthsqfigyc.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtrrivodjv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gtciwvmrmw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xylfe.cn/Article/details/gtyqqutcqg.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtirdvkpxd.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gtemvxkwul.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gtfmpaydrr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbijnpfor.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtcxyolfxc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtfrksqtqt.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gtimovekez.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gtjalpstnc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gtnbvhgobc.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtovyvkava.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtuwjstjvz.html


<!-- 参考信息 -->