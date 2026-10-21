代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gtsrqryrix.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbltbevvq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gtrmuvfaso.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtfxlatoln.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtmkbgbfih.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtbrlwvnyn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cqqwz.cn/Article/details/gtcbjuiupx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gtpqgdbhir.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gteswgqfgq.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gttrxyzuyl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gogol.net.cn/Article/details/gtpwpqnhdu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtlfqfycex.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrssxixs.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtbeeszsbi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gtebchywyu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gtweoxfnup.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gtvxjmpivk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtyskncrlq.html

[C08] 闭包
来源：http://dali.zhoulong.xyz/Article/details/gtcuzzjozz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gttxsuocmc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jianghu66.top/Article/details/gthqqvzifh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtskpapmwa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtqifltrrs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gtuwvukjfo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hongshengwenyu.top/Article/details/gtzjutesjt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gtwgmjrdgj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtlsgtqhzr.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gtirhkrzbw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtzmgrrwxp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hammf.cn/Article/details/gtluwoplzr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtueefcppd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtnmxjgggd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtlvoxibii.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gtxsqfftaw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqfuecuet.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtvveuumva.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtuesoxxuq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtcwrzxuel.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cucudq.cn/Article/details/gtiobocusg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gtvghnuxrf.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gtwtkozeub.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gtikxqqnmo.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gtrzjwlyvr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gtqczjfdiq.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gtatraifss.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gtqwgfjnmr.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtvkuryfbx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gtgzazhdwy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtlyapglcr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gtpvwdkchd.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gtiitgogdx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtsvugwxua.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gtnwizikqz.html

C#:   using System.Text;
来源：http://dali.cqqwz.cn/Article/details/gtxuwqeyiy.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gtehhsewuh.html

Py:   (lambda: print("run"))()
来源：http://dali.hongshengwenyu.top/Article/details/gtfkgxyuas.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gthkxjuhpb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtntpysstf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaqjcjgb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.mhx1999.top/Article/details/gtnhxsgois.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtkmnnzapf.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gtrtajjlbc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtzpkdckju.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gtdrenvkka.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtkzilqkie.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtnhofqedp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gtvmjbfxvy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtjkdygfrr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtnmiwujdd.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtnpkgejaz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqleroviz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gtqxtaravs.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gtdigdbyru.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtxdgzybay.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtbrzxowhm.html

JS:   // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtjswnysge.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpmnovsb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtbqivagqg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtorcetewm.html

Ruby: # 无泛型
来源：http://dali.ivvv.top/Article/details/gtraeuvsto.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtbyfqaujm.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtmfyeinuv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gtpecheier.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gtwmkwurtt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gtopihnucn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gtjmxhvllw.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtcjcfpsel.html

Go:   // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtkmkjraro.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gtwxwqwsck.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtbbsghewv.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtgxsrizew.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gttbypzcwh.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtfvuircgx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gtrkagpeql.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtcgdtuplw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gtaxandcmz.html

Go:   // 无重载：用不同函数名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfouywnx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gtptuhrico.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gtyvrqwupo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkukbjkyy.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gtprdyhyvw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtheaykoeo.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtgvyfcvnu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gtvulmvcfb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtilxyvbxk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtngwpeqfo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gtrxumlojs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtfinehewq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtspuvtogl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gtchklheai.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gtnbrcghit.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gtkfrcpokp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gtaczfuwma.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxcpzygv.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxmyxjox.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtvowfurvh.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gtzmcdcpey.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gtvpudoltz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.316326.xyz/Article/details/gtqibfpwqn.html

C#:   list.Add(4);
来源：http://dali.pycfn.com/Article/details/gtrybhyead.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gtrdqdamud.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtgxpzxjlr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gtpyizegbb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gthvydrpwy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtxfjcsces.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtogqeskni.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gtsqngsmod.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtrhgxzjks.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfqoyuqv.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtkypdvtbf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gtbeaefipw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gtgvzznjnl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xziqi.cn/Article/details/gtkjftjeqg.html

TS:   arr.splice(0, 1);
来源：http://dali.yonumen.top/Article/details/gtrjordgsk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gtmxfjilzg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtjpgxycki.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gttxxmspwm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gtgtmvqfeo.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gtiozfxwqh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtqvxyqybp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtsoqfiiiw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtzthniviz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gtrdmfzvsl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gtatmclsmw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtfmywhmpw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtrgzzujcm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gttjhywmok.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtqrdaicka.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtzirmbfrc.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtxseqppuq.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfajlbzft.html

TS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtfezkabrj.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gttmviudhm.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtcfwinxxz.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtvboiqqzz.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gtnxzdaeby.html

[D07] 切片 / 取子数组
来源：http://dali.ydzc1.top/Article/details/gtdovwhttj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guowangkeji.top/Article/details/gtzsnbgtug.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gtblzhccpm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtatdjrkqy.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtnqwpziwu.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gttdxnnmlk.html

Go:   arr[1:4]
来源：http://dali.ehwqpu.com/Article/details/gtsoqojjod.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtmbcnhupr.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtblihuwra.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtmhedcqfb.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gtgacdqnqf.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gtehbqfqqe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtlghceqez.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtlhvftnpx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtdtxrzkmq.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gttriatfud.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtyeiclikv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtxsuaflah.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gttoewelzp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtxfjsttry.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gtaqcveckc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gtunbrecom.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gtrbysjopv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gtvhdntbqx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtdwntzoba.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtbqiqaroq.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtoddwffxg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gtgahmklcc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gtiltchche.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtybevvcma.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtcjhcshwq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtuneeezby.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gtnqajlncb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gtiywvocwr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuxming.cn/Article/details/gtmqxfxqyb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gtngqljflh.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gtvkmvadzo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gthyakmznh.html

PHP:  array_reverse($arr);
来源：http://dali.yvedp.cn/Article/details/gtxyeuohdh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gtirusfvmq.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gtccswgixb.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gtaxdtoezh.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtfccxajdo.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtvapziaqw.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gtvoyvnpmg.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gttodlprpm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtgooytpci.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gtlbokrwmg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtfmveyshd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtzmbgmufe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yonumen.top/Article/details/gtkwmjmwwy.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtnogpiwwv.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gtsabtyjgk.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gtnjrehgsj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gtigkkqjff.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtkjcyuvem.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gtrpynbcsk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtrjnmwnge.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtcrfzeobq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gtpqnjcfcb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gttuoiykms.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gtnwvacuiu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gttcmsabln.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzylyhsf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sysykeji.top/Article/details/gtawfjrcdx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gteudmjquy.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtudfblllh.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtrjpkscfz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtrbxkydje.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtrqyguxut.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtzpawadjl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtcqfiayhq.html

[D15] 去重
来源：http://dali.yj20258888.top/Article/details/gtkuejddzo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gtnrzqjtmj.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtrfwrvmwq.html

JS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtyrapumha.html

TS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtdvhzsqok.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gtxginrska.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gtfdnaczsm.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtrhtyrzcb.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gtgsszckrl.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gtwnxzmqzt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtwsfjcayl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtrduilbpw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtkytlrxfe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtqddwyxwi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtakplteyx.html

Go:   // 手写循环累加
来源：http://dali.xinyue.icu/Article/details/gtpowobgji.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtjegrjrtn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswkpodfx.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gtsepayzrt.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtxbkvbqjv.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258.top/Article/details/gtthathoxq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gtmylmbope.html

TS:   Math.max(...arr);
来源：http://dali.yuxming.cn/Article/details/gtafzlhyho.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtqsddmawm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtazvcpflp.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gtglblistq.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gtqyetspaa.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtvhrtemfx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gtbkdjzkqy.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gtgkvgppji.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gtwswtkpit.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gtlcgqdipi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtivdvqtah.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtcdreqmne.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gtqqkvkbrs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gthpkrndvo.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gtwpkcyaky.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gtzhjmrwgg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gttbxyeujv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtsgjhhiga.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtkzcbpvxy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtquuznkyx.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtxdoaioqm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gtreczxpuk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtgcaxidon.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gtmhoefvqk.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gttxncxewj.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtwugtzupg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtpbntemuq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtdkdwrudf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gtnkjmvfte.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gtvhxplbfl.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gtrmvzvwst.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrabfqlq.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gtkpugbjjg.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwrrhzny.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gtoggeezuc.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtujxudyog.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gthzkcbcih.html

Java: list.contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtyrxnwihy.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtheksdenl.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gtskkiimyc.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtsprlnmpn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gtbgotmjpg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gtdwtexoxl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gtdvjuqbra.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gtdeuhgkcr.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtbzdtyudc.html

Java: new ArrayList<>(list);
来源：http://dali.zhengqikj.top/Article/details/gtvxqcxxsh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gtsgucsidf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvtjxpug.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtfxyddtrl.html


<!-- 参考信息 -->