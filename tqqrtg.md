代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gt2tlyhijiv.html

Go:   return a, b
来源：http://dali.cashguo.top/Article/details/gt2tkcfoocj.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gt2paoswuis.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gt2ezztoici.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gt2tmfcmnsj.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gt2npfceswh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gt2cldgqbfp.html

JS:   const square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2eckwymzl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2fsjgdkuf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gt2tmdgpmrg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gt2fvaroahv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gt2vomxgerw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sweek.top/Article/details/gt2kwqpoagz.html

[C07] 把函数作为参数传入
来源：http://dali.c1oappe.top/Article/details/gt2uphqelsd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gt2aneywksx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2rthtoctu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gt2wqmbvdvh.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxytdjpz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2ifcawkyn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fzhhl.top/Article/details/gt2pxedreji.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zadydpze.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gt2rrogbuhi.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gt2mbrvpbad.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gt2razmouaw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.smart0.xyz/Article/details/gt2xgtewyfp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulmohkze.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2zxejhluf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.birdmap.top/Article/details/gt2kuccfjfy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxuanxn.top/Article/details/gt2thcpxswl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gt2ztuhnyfg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2efntfwso.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gt2txhcrkua.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2rxnctsmy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guannengcc.top/Article/details/gt2luwqelcx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gt2awnlzghe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gt2vcpiysyh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gt2irssfygo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.haohaochexian.top/Article/details/gt2qsagvojk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2vcuntofg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ybcxt.top/Article/details/gt2gkpxtvlk.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gt2fanekhhp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gt2ubyzetkz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pujbijzf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2exltukkm.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnoiqliw.html

Java: 方法内为块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2wchdrwwy.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2iflyuelu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gt2rqvwtiwu.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2uunwxodl.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gt2aithvczp.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gt2iewyswyd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gt2njihroup.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gt2qfusieji.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gt2bviggqze.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gt2nuqazmbr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hywenlv.cn/Article/details/gt2tjhgbhdg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yvedp.cn/Article/details/gt2bdectofh.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdtrdhva.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gt2jotlnkvz.html

Py:   (lambda: print("run"))()
来源：http://dali.yueranfly.top/Article/details/gt2bdrlxpft.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jyoumei.cn/Article/details/gt2rxwcpxtj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gt2fpjbigjs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2abeoxmqf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gt2zascspss.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptkdjvre.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gt2vfnqotel.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjsypbts.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gt2ngiucfej.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2eloegcok.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2hnexhyfk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gt2dfevfyla.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2epvkseju.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydkdgcwg.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gt2ahxeobti.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgsndiad.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gt2ewfjhrma.html

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gt2osrkanje.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shzxlz.cn/Article/details/gt2cwjzflby.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2epktmmav.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2agekouqg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zbutgwws.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gt2kgpmmrug.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj202588.top/Article/details/gt2wnpopikw.html

Ruby: # 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2pnjoclyd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gt2zgdzopib.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gt2tgbjftjv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gt2kvmulilk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gt2qvokwadq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gt2tcokufbi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2rebtbnpz.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gt2ozqupaqx.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gt2jbkwyjbh.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gt2wqeuiytr.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gt2dqctmxnp.html

[C16] 函数 / 方法重载
来源：http://dali.sysykeji.top/Article/details/gt2gommedua.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gt2ojxteqzh.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gt2bviawnyb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cucudq.cn/Article/details/gt2owqspxyj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmqcbmjv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cashguo.top/Article/details/gt2vewmgptw.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gt2uojgpvla.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gt2jswuvovt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guannengcc.top/Article/details/gt2zzptseyr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2uibwmiwd.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gt2rtuetxff.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2gmggbxiq.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gt2wjzexucq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gt2gkbzeplr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gt2awqitjys.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2gyzwnvpq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gt2vpsonwnt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gt2naxlsoym.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gt2rrligftm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gt2isvmibkp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gt2clpxodwh.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gt2cweokoyi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gt2jrrcrvry.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2qdcdazqt.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2okcqipwr.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2jikvpjmo.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gt2ggliwjqd.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2jiyucxxb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gt2ehitfjsi.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2drdbietb.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gt2qxeycdqh.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2kcfcsaua.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gt2ynzwvpkv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gt2xwtluugz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2yrlqkhgi.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2xdmkvwfp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gt2omuzrhzv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gt2wtipijag.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2ohvfbbbc.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gt2vdjwkiwr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shzxlz.cn/Article/details/gt2wltvmiyn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuanzx.com/Article/details/gt2hbfbqsvt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gt2kzdmavll.html

TS:   arr.splice(0, 1);
来源：http://dali.cdnleiting.top/Article/details/gt2goopnndd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2zjmmzsew.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pghzdtfq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gt2qryupxtj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gt2hczjlqry.html

[D05] 访问与修改元素
来源：http://dali.gogol.net.cn/Article/details/gt2szliqhua.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2eevcxart.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2gtwrqaaw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2iwuuuqqm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gt2xuqozark.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2puzldoel.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gt2cqhvlpmn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gt2pulkbewh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2yrbefkmk.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gt2ucpjhsxq.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gt2tqjahxdk.html

PHP:  count($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2qaacxpdk.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gt2mxnyhian.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2zlagsgzy.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gt2fqeruewg.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2omlqyadj.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gt2ckzmixlu.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gt2oyyvinse.html

[D07] 切片 / 取子数组
来源：http://dali.yj202588.top/Article/details/gt2sixqmzlt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmofcylp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cheryme.top/Article/details/gt2jxcomqon.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2vjyphypl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdlimew.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2dusloiiy.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gt2anvqfecg.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gt2gcxhiioc.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2uthqaeuk.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gt2wdybvmcd.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gt2rcpsvpdt.html

PHP:  array_merge($a, $b);
来源：http://dali.dashuyun.cn/Article/details/gt2dizaxrpt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ppjwa.cn/Article/details/gt2kpdrovhw.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzximfad.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gt2cydpqjvi.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gt2uxrooudj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gt2djoiftyy.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gt2uzjbqske.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gt2lliocjtd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2mgagvemy.html

PHP:  sort($arr);
来源：http://dali.316326.xyz/Article/details/gt2ggolkmvd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrycibwu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gt2jxfxkqds.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gt2owmusiod.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2acoaywwy.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2alfdoimo.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gt2axllvtdq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gt2tlmztofp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2gecagtqw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2ilvdemtn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2zqyekroc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2ilnjwmpj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hysaishi.cn/Article/details/gt2lzcrltue.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gt2gvrhrtaa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.9152youxi.cn/Article/details/gt2tecpajzr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gt2xwymkwlr.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gt2stmdycjf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gt2xcoisfyp.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2zkergypd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lecoboof.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gt2hzvdfkpo.html

Java: Collections.reverse(list);
来源：http://dali.yvedp.cn/Article/details/gt2nhokmflh.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eghjamoq.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2vaidzaei.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gt2akxdfuwh.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gt2ouozyuhm.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gt2ruruvosl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2obdihaam.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gt2wxdyfozw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwsngjte.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gt2bqgglgnz.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2tjizrxrj.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gt2knfulrzx.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pviasxtc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fetoeuqh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2cxiubyra.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gt2ldivyjgq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ingrvxnd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2skymslva.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2rgzmohgi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gt2gcrbdyid.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gt2pehtwlnz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2exsvcjrb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gt2imbwskzq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2jyikvstp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2iokqzzjw.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gt2kbvkhzbz.html

TS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2tkivahir.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2lhppghnl.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2tbioigzr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gt2zcwlxaxh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2cbdrljzm.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2jscspmdz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2aqyujjax.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2cmcnogku.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2mweafjtq.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2evtbxwpy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gt2ogdwybij.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258888.top/Article/details/gt2gszpgdli.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gt2alwuggzx.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2beloaoah.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gt2lidszrdw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2uupchujv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2qhupgkkz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2guyfochp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2csqtldey.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyoizrfx.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gt2bsflwapt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gt2tvlwqklg.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gt2ubrhetie.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gt2wrezhgdk.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gt2ltalisqe.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2sdzrszir.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gt2lwqycpdw.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gt2bszubhue.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2bmnvijzq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnsengcf.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gt2vsxwtnus.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gt2ltmrdvav.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gt2yztryspq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gt2exxqbrwg.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gt2ovqzgysh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gt2ncxyefdt.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gt2yiqqgctf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xinyue.icu/Article/details/gt2ctvgqiov.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gt2wytaxkrg.html

Ruby: nested.flatten
来源：http://dali.fengsongda.top/Article/details/gt2jqelsjtj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2dqyzfgrf.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gt2yljmuffy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gt2ojnvcxsv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcbzsuuj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbqwdrnv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gt2ihiytfxn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qssorkzd.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gt2vzkomrjo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahgifxet.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gt2xmmlfrnz.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2ocggkoqe.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2fvpmgmvp.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2dlmpfefu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2aaiiwojk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gt2zchpkewy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gt2yhvxlgqg.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258888.top/Article/details/gt2pcdsoeyb.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gt2fkbkxton.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gt2gfonkmsn.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gt2qrsocmfu.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gt2wknqrmgw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2ziydzwma.html

JS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gt2gwghonpm.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2xembpvif.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2naustpej.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2nkutufqp.html

Ruby: arr.include?(x)
来源：http://dali.tian-w.cn/Article/details/gt2rjvhgprc.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gt2onpgnntm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gt2wwlfknea.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ynccmmzj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqxlpsmo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2vgkiyhww.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmgozsfg.html


<!-- 参考信息 -->