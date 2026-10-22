代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.cdnleiting.top/Article/details/gtzsrcrbck.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtcffsiofb.html

C#:   f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtrojbmdgr.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gtfbglknhq.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtweuhuyxx.html

PHP:  return [$a, $b];
来源：http://dali.daxiang520.top/Article/details/gtaavgsevd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksivugwc.html

TS:   return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtvrcxtytv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gtraicxoik.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtbxxoesfk.html

Ruby: return a, b
来源：http://dali.hfpthk.cn/Article/details/gtqncemmgq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gtwvgehtiq.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtivjmmgqa.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gtartzpmlo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gtydbnyiyx.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtzlofrjpk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtthhillfk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gtydebxaxn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtkhxkmddd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtuflchnrc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtqgscofzy.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gtcroykifa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfrtwzgc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtylfazuux.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.birdmap.top/Article/details/gtgvgwruxy.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gthcailzkw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtpokxyolp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gtwxvwdiie.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtwgpeufzq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuetiantiany.cn/Article/details/gtsriylzbh.html

[C08] 闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnakceocy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtzlqhtakq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gtwtfedcba.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtxgliluzw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfdvdfqts.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtznbroutu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhzbvqdk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gthzrxinxn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtgujybpoe.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtzgnokaaz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoetfzun.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtgrllskle.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtoghcvavs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gtbrkdrajz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gtbswrjyzh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fengsongda.top/Article/details/gtiroendxr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gttrfchdim.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gttdryhogk.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gtgupcjpdo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwyincxy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gtgnqtaear.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gtqswsfeyz.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtvnuofrve.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtzwtqcqks.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gtonvvdbrg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yongpay.top/Article/details/gtxwdbbidm.html

C#:   块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtydthdxda.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gtmydhpppm.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtykrkynon.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcyljgii.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtblejvznq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gtlxycosnj.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gtlonakyvz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gtcerseinr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gtowslmilc.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gtucduyrbu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gtwalpyzen.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gtuxcsvgag.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtukhqadsc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtxfeqglqy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtlehtdrdb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gteutmcsfc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtxtxjogne.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gtcxpdpztj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gthwedwsfm.html

[C13] 类型声明 / 类型注解
来源：http://dali.jianghu66.top/Article/details/gtfiysfsxn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gtmlumdoyx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtxykihjaw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gtrtitwxfn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtyoulzahr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gthqgejcgo.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gttpofhrlq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtkkdrjzdc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gtrizaiyav.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtukwcdsqo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cdnleiting.top/Article/details/gtsrpywmrl.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtvipefrui.html

JS:   // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtibpzfozz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gtavfijccb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.quarkkingdee.top/Article/details/gtnnmtzhcj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gtdncwtnlh.html

Ruby: # 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtmuujvblj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtnasmiltb.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtiygxwsbv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gtrqeycxcd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcfvmuep.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmhinnyhy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guannengcc.top/Article/details/gtlvpdbpjl.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gtuihpedjx.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gtswjjfhta.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtmhakfail.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtxdqnzcjq.html

[C16] 函数 / 方法重载
来源：http://dali.aibaodan.cn/Article/details/gtthszgeph.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gtramjweff.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtjlmhkeld.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gtxhdwyljd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gtkkhbpzoy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtvxztzvex.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gtzbhdxjwk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gtnsicdjvb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gtvqamrecz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvnffezmm.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtnrpxswvs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlqlxbihv.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gtylgkultm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtxcgonwaz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sweek.top/Article/details/gthiwajtxj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtdcnhkqcy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gtiuhcugvc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gttfxuxfwu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtydvjcnkt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gtsgcnnuvz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnxiangtu.top/Article/details/gtmofjqhlb.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gtqykopwnf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gtlbajhfrc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gtcylzcyfl.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtcvaidkml.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtuaihxaop.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gthmhusbpl.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtexagtcdg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gtoiysyqhv.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtwckcaapz.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gtcwiguqne.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gttimxpeqv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtdjlyggxs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpycaewpk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtpyuqritx.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtkyxepias.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtvguyjtwe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gtiyddjmtg.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtuvgxxjnq.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtpqfreeqs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gtiotzubns.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtcwcasdgr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gthgmgpblw.html

TS:   arr.splice(0, 1);
来源：http://dali.havefunace.top/Article/details/gtywvlanuj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gtfpxjhwuf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gtjknpoozr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtfqrdcbyf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gtdfpvkeqq.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gtbkbmwuzv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtybmlgikt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtqjsssemh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtwqlvaahr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gthaaldfdp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gtgoezmuxy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtsakellbe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtgtkzwfiq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtneyqljqg.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gttzppvran.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtrftohiga.html

PHP:  count($arr);
来源：http://dali.tanke756.top/Article/details/gtscfsdahp.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtkwbytsww.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtjikotlzg.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gtcwirosym.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtnkzwehcj.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtumhcpqli.html

C#:   list.Count;
来源：http://dali.hfpthk.cn/Article/details/gtvxdgbwgu.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gtopazhgrs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gtkivhtysb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gttvboaldg.html

JS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtyrzcmbid.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gthwzayepm.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtbxvuohqk.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtglalgmxg.html

Ruby: arr[1, 3]
来源：http://dali.tian-w.cn/Article/details/gtbhhzdxsy.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtmwjimmxg.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gthkyenkjf.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtdcyfpeqk.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gtdgofjkbg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gtcyseegni.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gtpvygmobf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtpzpxhszp.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gtovbnmmrx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtpssthask.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gtfnyelfrv.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gtcdwxaxpq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtciskzubq.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtwrhntmjq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gtdoajfgnh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gtftoozvdi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cdnleiting.top/Article/details/gtynyrzdjl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtodokkyty.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtblwneilj.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gtueuzxigu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gtdnrwipme.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cashguo.top/Article/details/gtseicbitq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtmmtswwlq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtfntvpbgw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gthvzrshau.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gtjvulimqd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gttyybrbxu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gtauxrzffo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gtsnrtbbkb.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gtxdvdydva.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gtaoqnzcts.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gtpjupmwyk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cucudq.cn/Article/details/gtjgauurjm.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gtovhfbowx.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gtyilntwlo.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtndvhgowz.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtmbrwkyaw.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gtlgyngsgc.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gtopcutaoj.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gtmnzxsehs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gttrwtdrqp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtofecuteh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtrlkvtlsd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gtkkjippfz.html

Go:   slices.Index(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtjxohincv.html

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gtmbfwrvmt.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtaojyzixc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtrxxjhbsx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gtihmoctze.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gtwmfsyaly.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtxrkbwxhq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtaxrrcoyh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtfdyrvynn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfmjenfa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkttbaaia.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gtxzuxcmzz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gticprencc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ehwqpu.com/Article/details/gteftrzoey.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yueranfly.top/Article/details/gtdcwtwseq.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtdwfctnaz.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtqhukpcbr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtbzgdgoar.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtqwdhaype.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtytfvltis.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gtousfjudg.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gtgqdetejw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtsbdzivpb.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gtouiekhqq.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtpmohhoav.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gthxxxqnxb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gtbwgzsspj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gtqndftssh.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtkqjxinrg.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gtyrjlkbnp.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gtjloukgfe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtznryuvrh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xziqi.cn/Article/details/gtikvszsag.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtangpkeey.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtumqwafqa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gtviwrpgck.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gtlvtqjjzn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gteyibozul.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gtizjddnxh.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gtwbwdlfzg.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gtuculyafe.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtihvrxqar.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gtzxfofsfk.html

TS:   Math.max(...arr);
来源：http://dali.jinqigufen.top/Article/details/gtclrfbmkl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtaxpokjhc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gthukogmsz.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gtgsoxpfsg.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtahducbay.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gtmtycjssf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gtanftquhd.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtkpvadpmb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xziqi.cn/Article/details/gtaigpdtlr.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtgvytkghi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigufen.top/Article/details/gtiagfdegx.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gtqvbveclg.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzquseom.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gthpfbbaov.html

[D19] 按字段分组
来源：http://dali.bjfxy.top/Article/details/gtzgtcdscw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtlaizxywy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gtekwopnkw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gttewgupoh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtwmzhbcxk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjbyoryl.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gtuomohjqd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gttmefbrtz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtkmlssdnq.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtfzfftlqc.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gtxoiaymkz.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gtvhamnyoc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtcxasecih.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtiiwlsyzv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtwfjeindz.html

Go:   // 手写 map[T]int
来源：http://dali.ppjwa.cn/Article/details/gtxobpszle.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gtdndgvcbh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtjveozjlh.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtglehkomp.html

Py:   x in arr
来源：http://dali.nanxinkj.top/Article/details/gtzzyqhyvb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gtzvetkrsb.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtsxxohqgw.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtghfyfvpp.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtjzzztsqn.html


<!-- 参考信息 -->