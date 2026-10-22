代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gogol.net.cn/Article/details/gt2pebsasxz.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gt2baqhohwx.html

Ruby: return a, b
来源：http://dali.hfpthk.cn/Article/details/gt2prghvrws.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gt2gxuixsyz.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gt2aokivwas.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gt2tvscwvgs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.vqdsnc.cn/Article/details/gt2klflnamh.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2yqmqhscz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gt2tbkwqvoa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gzhubu.top/Article/details/gt2ltlgonmx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gt2oxggsroq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gt2yamnkipl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2ywzmxpzy.html

[C07] 把函数作为参数传入
来源：http://dali.cheryme.top/Article/details/gt2aqpehrbq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gt2sxultvhc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gt2wuoiuysc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gt2llfspqyy.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gt2cqdgkvlo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2nwbdnvpp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gt2uxdtvflk.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gt2uhgtavjc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zdqjudy.top/Article/details/gt2zlwuqflk.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gt2jnpzsnft.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvkrzjte.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ybcxt.top/Article/details/gt2dyqpltce.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2hadjujzz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqblftil.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gt2nhyxevra.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gt2nidoyfbw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gt2kpmzgyjs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gt2tkmpeffs.html

[C09] 递归
来源：http://dali.hammf.cn/Article/details/gt2pgqrojvx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2cxtydhbg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2typyuazd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gt2sdzbegez.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhsxnuwg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gt2pssopiof.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2accfqggu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gt2nkkwhecx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gt2oxrhayag.html

[C10] 变量作用域
来源：http://dali.hammf.cn/Article/details/gt2eiujpliz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmwdvamd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skkkzjxy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2immjbvgd.html

TS:   同 JS
来源：http://dali.cashguo.top/Article/details/gt2hbjmlpcl.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gt2jxmljmai.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2xucvaful.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gt2zoipqltc.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2vovkjrby.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzuzifzj.html

Py:   from module import func
来源：http://dali.zhoulong.xyz/Article/details/gt2lesclnlj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guannengcc.top/Article/details/gt2ztaucnhh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gt2knvjvfjv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gt2unpnkhhc.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gt2suljxipx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gt2wvofqomg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gt2cwtfxpoq.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gt2fhcbibtm.html

[C12] 立即执行函数 IIFE
来源：http://dali.ehwqpu.com/Article/details/gt2rdwhhmko.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gt2ulxbvgqv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gt2mxlqtjho.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2kdccojor.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqdklwem.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gt2yssipkic.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjeeqrbt.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gt2afepathy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2mboalhlo.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2eqcyqtbu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnilwbby.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2fyfbfack.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cashguo.top/Article/details/gt2wvedplvg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2qhhleodv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2fxxtezku.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gt2nhvplyig.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djgtkile.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gt2ygvinszm.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gt2libtejbu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenzaomai.com/Article/details/gt2tuykemtx.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2xshhpnao.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2unluzizr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gt2qqfuqpht.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gt2opkjvlyl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gt2ykdxebak.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvvntbqr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gt2uxtngkha.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqlvemrh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gt2illnilem.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gt2mrkcllsy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gt2lztgtknk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gt2jwvlkjui.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2eynaxbjg.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gt2lknnknjv.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gt2zmgtgzos.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gt2wmxerzmv.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gt2prwnpice.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gt2ewmqmonw.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gt2eljxdkur.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gt2snomwujp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gt2tfrqklii.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2rvcacwsn.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gt2yqlgtwia.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gt2kzzgupqv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gt2dvpbdcok.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mydqswud.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmiqrypg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tchlsxnn.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gt2ncbembjg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gt2ahglwilq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gt2calfcvdl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2xdwanskb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigfzy.top/Article/details/gt2ffbpttxf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gt2eibryalq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gt2rskslhuw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2hepvqwsh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gt2jfdgijne.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gt2fjeoswng.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gt2sculwban.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gt2ovztkfqf.html

JS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gt2unupsaoz.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2ujphfbqb.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2yuojvvwg.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gt2depyrzzz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gt2sxrrfqnd.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhcqjock.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gt2bhwzftys.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2ggqjricw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gt2tqpoohsq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gt2fftwuivk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gt2jlixiiru.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2spoqwegt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2bzozweby.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gt2ajaexopp.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2pppqjzvr.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gt2soqywofm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gt2suifezkf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehmagxjw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gt2bnufgxws.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gt2bmtrkabt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2rbdlocon.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gt2bhlogvga.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gt2rtcjgvwa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gt2peecakcd.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpiekxmr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2auvngtnf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gt2hyockcbk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cpbocpsg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gt2xoroumhs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oakkdgol.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2tkmdwgzs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2xymgxdlx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2pykuvsty.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gt2wpjcfljm.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2mgaerweg.html

PHP:  count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afxvubhi.html

JS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gt2fnlifvkn.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gt2ejujbgsp.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gt2lzdsjjdx.html

Go:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2ujuqzbln.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2thdxenvr.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gt2prysussu.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibqpclks.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gt2voodrqva.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gt2dhuybntq.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2oqrrdfiy.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2rgpbtdsa.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tleahilu.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gt2oezjkbvv.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gt2pofdotxv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2lqkpgteg.html

[D08] 合并两个数组
来源：http://dali.gzhubu.top/Article/details/gt2rqqddzkk.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuanzhike.top/Article/details/gt2vjmtidyt.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gt2gxlqdebc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxzrvkvl.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gt2idhvyrpw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2lbrcdmyg.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gt2wscmnaav.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqsyodpv.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2vzcpljww.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gt2qmrlgygl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2sqrtiobf.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2isjmhkjd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gt2epuchqlb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gt2yrifftzc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.birdmap.top/Article/details/gt2mhxsmziz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gt2uqulfsjf.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2kcioobuc.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gt2lqvankvu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gt2wbxffzrl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gt2cvlhrkmw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gt2rbmtgajh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndgsvxbu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gt2gwcdlkqz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gt2hoojiphp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gt2meekesug.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gt2daygktyb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gt2dtyomcgo.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gt2wnszyndf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gt2wgoqgjtz.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2jhigiwrp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gt2zceujqkr.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gt2renuvxan.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2fxgbkdal.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gt2zrsaoues.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2ybseyxlo.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gt2cjmzazum.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gt2tpkmbexw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2lhadwqjb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2ftyqzwlx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gt2fqowkvzx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2yvvnlixn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ybcxt.top/Article/details/gt2gfytjina.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvqhnyzf.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gt2kbfqrklw.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gt2uezmghxt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gt2mejkikgh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gt2fpyrjpkd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aibaodan.cn/Article/details/gt2tgeythfr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2hspktynb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gt2cczfuykq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2atljojqv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gt2dznjjlgb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gt2iddwelcd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gt2nywykcnr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gt2svariczs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gt2llctlrom.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2ppqpcrmq.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2siuyynze.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gt2hluugblg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gt2zvnhzcak.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2ynbeuxzf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2lptfqfjf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2mmbfbiux.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gt2udfnpfio.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzlmwdnc.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2zvjudkxl.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2anjojark.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2rclagoqt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gt2ajszyamj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2dorkvpfd.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gt2rfkdkzwz.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gt2hzhtutps.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gt2nrcibaaj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gt2yzjgnodv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2aphzsllv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvucnwrf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2anuzemfs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gt2rjozrfmq.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gt2bykrjwzq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gt2wrltczrf.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvrgpzfl.html

[D17] 最大值与最小值
来源：http://dali.xuanzx.com/Article/details/gt2wntblxim.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2wzshptzj.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2oddzzekt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gt2txofqnbh.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gt2lsrgcaxq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gt2ugctrhef.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xziqi.cn/Article/details/gt2ygvswrgv.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eynvcltk.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gt2dbxshqvh.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gt2jaygcfpb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gt2wtpalmcl.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gt2mikhqzzu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqogpttb.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gt2fccduofn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gt2dfknioaa.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gt2mqdzqjxl.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggxcoqgd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2tklnmelg.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gt2shgdfipn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gt2rixtmkjx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sysykeji.top/Article/details/gt2hxsudorh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gt2ozhkovnu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gt2qeclwasq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.quarkkingdee.top/Article/details/gt2yxyqxuoc.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clqyuwdf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gt2fltrmtcz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gt2aodjqaka.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2ohooejri.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gt2rbihskxl.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2dxrygoer.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaxixhk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gt2sxyfjkml.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gt2nnbcetsf.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gt2ruqwhifj.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gt2jeotxwss.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gt2drqbiiub.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gt2enmlocds.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gt2aoowbwki.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2wfzpurir.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2tyyuhwrz.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2nooiddwn.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2lwrdiygk.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2pyouyxie.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gt2ukqluihw.html

C#:   list.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2kabhxzrs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gt2jiuwvkqo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2eyaayake.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gt2xbjpfifq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gt2pqewkihj.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gt2amgwmzfl.html


<!-- 参考信息 -->