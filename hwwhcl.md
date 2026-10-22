代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gtfzewxpoz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtdaelcdwy.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gthzscpflf.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gtwztsovds.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtsbylcfpv.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtnkzdhumq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtcoupzqsw.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtxuhoulny.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgfzy.top/Article/details/gtaorqtvow.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtgxmbcizg.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gtzdpdwkqh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gtuelqadqd.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtmfelbewf.html

Py:   square = lambda x: x * x
来源：http://dali.xziqi.cn/Article/details/gtiidhjuwm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gtuxregzcd.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtyrozcjmw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtodakyhkf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtcokafwwd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtdnemolaz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daria6918.cn/Article/details/gtqywljkom.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtiaykgofm.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gthqqnhrdv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtglfyrokf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtkamzdbzz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gtalglymdi.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gtcmlxtwog.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtoidkgvsv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gtwernhvdm.html

Ruby: arr.map(&:upcase)
来源：http://dali.tian-w.cn/Article/details/gtbsegkzkq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gtmbzezari.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gtaikyntbm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gthrdpxubt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezurorur.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtajkatxoc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxozvdoa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvschgqea.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gtuutxmzit.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gthlfcrbhs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtklyaanqh.html

[C09] 递归
来源：http://dali.jqgufenzy.top/Article/details/gtfvzxlnwx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtkwpqheen.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtuhjykocu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtjtlkiprs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtaynmyoor.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gthpffxfst.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtbgycsuwu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtaeybcegz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtolwzvfha.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gtcikeovoo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gtabmxfzop.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gtgtpwwjfk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gtpbartuby.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gtachbackx.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtdichkrhy.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gttgnkbzjm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.316326.xyz/Article/details/gtwvduswkl.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtzrgzktvf.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaitqffc.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gtuhdcnris.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gthbpqetrr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gtybxofrqq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiuuedwq.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gtthrjubkv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gtnhfkjbox.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gteunitfft.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gtwsnwfbyt.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gtcpuuwsrf.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gtdyvshvan.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gtdyevepla.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfxvqhug.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gthiqaijpq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gtavkofumk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gttehickqn.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gtwlghmvwt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gtgsodwvtc.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gtaiihpcav.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gtxpvcwilp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtbhnilmzl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gthfkoesgt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtarkxmpga.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtqdvzqsbl.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gtvgzyucmp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtuxlqxazk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gtgptweyhj.html

[C14] 泛型函数
来源：http://dali.xziqi.cn/Article/details/gtdbkelxxy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gtpdcyzeqo.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtlzyvxeyw.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gtmgynqsmo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gtaskmadey.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyglssxba.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtoptnmvdg.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gtbcwsadyj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwtqfgap.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gtxcckjvjw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gtojjnfkwi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gtnrrvkdip.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtzqktybhh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtyaxfiqad.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtlswiryhm.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gtckocvbuk.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gtvrebmudu.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtbddambfs.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtpscwbafy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gteaihigde.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gtheiqqofj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gtnhbhovpj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtdpkmwfaw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtnueylgbc.html

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gtnqlwaobo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmeohomzf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xziqi.cn/Article/details/gtmwqmpsrf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtwwjasbqj.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gtlavydrkn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvbxobnsu.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gttjofgrex.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtcoulxrxf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtjnjqwbjh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gtencwrxaa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtgmgmuhsy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtgjgrcgdt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtgnmbgvir.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtohwqruyv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtovvbkzhf.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gtztthcwbe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gtorqqjgzj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtmxjqatbn.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtlngqkroq.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtjgxndjvo.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtjgoklpkg.html

Go:   arr = append(arr, 4)
来源：http://dali.meibo888.top/Article/details/gtuenycbhc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gtndwapqoy.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gtxxacjhbj.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258.top/Article/details/gtjfrycsjv.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtfzhjtukq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gtouezkugb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gtzktiptri.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gttjtdwpgx.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtnszgzkmg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gtoeqxnqmu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gtprwrxgzk.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtcqdgkxdk.html

[D04] 删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiofxyaol.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtyknxiavh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gtwpohaykw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gtgnllyxoq.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gttyawupzo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtffohchpx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtgvktlkhr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gtivhwpjhn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gtqxyubawr.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gtrrjhcmqh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtllllxset.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtpzirwzqf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtixxkeyob.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gturargqop.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvfncjfc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtfgmyphzg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtzmwjltjw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtbxqtpzuz.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtnmwkzhox.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gthciuwiyi.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtmttyxfnx.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtikogrjbb.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtxcpimcmb.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtxafabtgo.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtfdadwljo.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtiblkozya.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gtxaqemhxc.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gtxdvfelum.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gtrhspvplj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258.top/Article/details/gtpzpipalq.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtvtburdol.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnemmvrpl.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gtpvzdrjle.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gtpbetgekn.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtalfebwmf.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtijqtnzgg.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gtxdcisyls.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtekypbely.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gtipmssepz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gthnygakqa.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gtkhkdaevz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gtzlztxzgv.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtxsowkrcm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtjkcmurzp.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gtskxxxhnd.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gtxuzunfcg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtazyrktwv.html

PHP:  sort($arr);
来源：http://dali.dianchejie.cn/Article/details/gtvuzeznlp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gtornwmsss.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gthwcljfdi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gtkdnbnnbl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtzzxkxqlr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtcomjonea.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gtjukxhnyu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gttzaxaroz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gtaogxfyqp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtgvrwavjj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtudobtijo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtwmehundj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gtsrjkkfgq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gtosshizgn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigufen.top/Article/details/gtseqcwirw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgufenzy.top/Article/details/gtjfhrfwbu.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gtsxdcdjhl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gtstgqqivh.html

PHP:  array_reverse($arr);
来源：http://dali.yuanzhike.top/Article/details/gtuoqsyzhd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.redwolf501.top/Article/details/gtlivtnsfp.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtzalevkky.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gtoycxsnvf.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtajrnxvpb.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gtonwnryuc.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gttlbgfqim.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gtzglfwprk.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtcrvwjcen.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtxfapiaxf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtzhfpialp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtdjwxqvzp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gtpchqqhmz.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtdtebuibv.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gtihurikdc.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gtvurtdaam.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gtvwgjxcli.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sysykeji.top/Article/details/gtxrplzylp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvboypekf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtxzouguof.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtvkfltzsb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzmxrhyq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gtmbxlltxf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gtzchdfqzz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gthbmjpyxj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gtlhmjrwxy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gtxqimqeiq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtyiqeetdp.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtokylpxkf.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtrhnpzvqx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gttuvrpoov.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtdggcarlb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtjkgxlxwy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtpomudjso.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gtoulsmxzt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtpsxonifo.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gtbofynrsc.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtkdiugpit.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gthcirzhcb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gtdadfcjgv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gtiieeqmuo.html

Ruby: arr.uniq
来源：http://dali.nanxinkj.top/Article/details/gtaplqxhqq.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gttyccauxs.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gtcittvwnf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtinywavss.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtzguxnkrc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtkyqkoxhf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtfyqodkvt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gtbivurisv.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gttzfvnoxa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtkhjzdefz.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtppkkqzqa.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtiioctzqi.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gtwuytkowb.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gteyhheply.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gtaesptttf.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtgbqykmrv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtwohttfti.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtgrbzojld.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gtvmewohut.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gtnjrqbxjj.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gtonqxmdxp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gtfdopwgin.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gthzkfoyrw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gtaerxutpk.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gtvhskrtez.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gtuhlnrjah.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtryjbvevk.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtfugkryun.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtvrbbfwva.html

[D19] 按字段分组
来源：http://dali.chenzaomai.com/Article/details/gtmserjzrl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gtetkkgfvs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hfpthk.cn/Article/details/gtiombfmcl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gthmfyjjmi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtktiowakz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gtfanelocf.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gteprnfbou.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtbszuujwc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gtitzkcoro.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gtmfpblkun.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gtjoqzpqog.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gtwgumkkvy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtqfgbbyqy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtmsomajfh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtcfvobiva.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gtcshwapgf.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gtafemmmnx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtjdiysbew.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtypdyuqqu.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gtndqxorrz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gtyeymogjo.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtlxdlzlgj.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtpxzkdkkk.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtouzjzvpx.html


<!-- 参考信息 -->