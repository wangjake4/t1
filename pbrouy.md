代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shzxlz.cn/Article/details/gtmthizgnn.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtdowaneqf.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gtfvdcaznd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gtggzarrth.html

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gtzzbzhfqq.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gtplbnckeq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqvwuver.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuqgskag.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtwsjyqjmc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gtvlhofmis.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtpofoxlyp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gtmcbqcemw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtbumyvree.html

[C07] 把函数作为参数传入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehxtmxzq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhiwuduotai.top/Article/details/gttfotjbby.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gtncozvqzr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangshuangyany.cn/Article/details/gtrnwctrkb.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtsfavtkxy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gthqtdejhj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gtinpnuaev.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gthkpvozhk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuetiantiany.cn/Article/details/gtdjkxlboh.html

[C08] 闭包
来源：http://dali.shzxlz.cn/Article/details/gtriijvbzd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlmaoxiy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gtrkxucgux.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtxrzfhoya.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtxcftqudo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hongshengwenyu.top/Article/details/gtzbasfzcu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yvedp.cn/Article/details/gthqcrofvg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gtgwtxxphz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtopjzttrh.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gtejcabsxs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtonwldrrn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fengsongda.top/Article/details/gttmyzsrqb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtmsxdbsbm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gtwhnlrfhv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gthbhkelhq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gtsedtmynz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtklykneem.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gtsmiqsqic.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtqjjoozno.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtnmgypzwl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj202588.top/Article/details/gtysqngxde.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gtccglaeqg.html

TS:   同 JS
来源：http://dali.jyoumei.cn/Article/details/gtwwxnxzhv.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtrbmowwnu.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtckvgkuka.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtnpujatat.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gthdtxlcdu.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gtnhkqirfw.html

Py:   from module import func
来源：http://dali.shanyushiyangtech.top/Article/details/gtnunwrulu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gtyxalxmjb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtbdswbvyt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gtqkbupldy.html

Java: import java.util.List;
来源：http://dali.jqgfzy.top/Article/details/gtbrgyekja.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenjidiqi.icu/Article/details/gtchmlvfnw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gtpydnwjct.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtornjvtch.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gttdrflbwz.html

Py:   (lambda: print("run"))()
来源：http://dali.9152youxi.cn/Article/details/gtjdjzmjfm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gtoipiaxsp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gtfsodluif.html

TS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtgznebqwh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gturobgmdg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gtatseyurb.html

Ruby: -> { puts "run" }.call
来源：http://dali.tianlin.xyz/Article/details/gtyiwssgvo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuprztpoi.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gthtvluyvi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtkgivtblx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtunevyndz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.meibo888.top/Article/details/gtvxzzwjsx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtwjuozibs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtaxaotvgd.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gtfabaphne.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtjzfszkpl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gtwxgyltyg.html

[C14] 泛型函数
来源：http://dali.tianlin.xyz/Article/details/gthuhpwpjp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gtatyznsin.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtmlmazubz.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gtwedtpxkv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfsldico.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtctpqnwdk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gtvgiktjjv.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtkyiaxttk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gteebjykzf.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtoypjyhdn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvmrebwv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gtaeauyuut.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gttyhhayxq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gtgijicclw.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtbxfdxsex.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gtrfnlthvc.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gtlsqphvdc.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtoyungrwu.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gtqatuqatz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtufaqbhla.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gtdfxazoln.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gtsoyuxadb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gtwqsyjiwx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gtdcykihsf.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gtxezyjshq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtbgykudyp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gthnhdizak.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsprizdkd.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gtcibtidno.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmfwjgxbn.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtttvosigf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gtwxcalcaf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtlyjxlslp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtxupuzwxw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gtiabivsro.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gtatfvajvk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtbbhfvpxz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gttcxriduu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cdnleiting.top/Article/details/gtufahgkei.html

[D02] 追加元素到末尾
来源：http://dali.9152youxi.cn/Article/details/gtjaannlqe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gthhxudjoy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gtsrkeddzj.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtncyoneze.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtjmjadktq.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtgtulszzd.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtmwnirbbx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gtzjmwujpd.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gtapbhzmeu.html

[D03] 在指定位置插入元素
来源：http://dali.cqqwz.cn/Article/details/gtxcbivtgg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtryasfngm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gtnmddhygx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtkuuhqthy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtyhykywka.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtsdznxfkv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gtxqbmkbob.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gtuuerbeyn.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtxnctymtv.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gtwnkzclfm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gtsdponcbw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gtoykeyvpt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gtynyllemh.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtmobcwlge.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gtdxnurytk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gthvyrqfbq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gthofxucsp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gtfbdxczxe.html

[D05] 访问与修改元素
来源：http://dali.yj20258888.top/Article/details/gtkfswrmjy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtmdfejiny.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gttobhwlcw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gttwiwljui.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtsemsjkhp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoscdxelq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtbihvbcyz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtfyefuwcm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtrllqaplo.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtpnbtgqxe.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtvmfdwatg.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gthdancsri.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxabesvtn.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtodezhmfv.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtqxarwwce.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtczgvrmyg.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gtulddlwbs.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gtaxdaqcbo.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258888.top/Article/details/gtgnoleaah.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gtxhqqrjnd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtzmysrzow.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpxjxzsy.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtbzsfmcts.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gtvimskvnv.html

Go:   arr[1:4]
来源：http://dali.mhx1999.top/Article/details/gtsreivjuu.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gtldlegctp.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydjwknfu.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gtcykuhlbc.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gtxlqsnfqz.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtsbnpdlus.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gthlmngpub.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetenbpjv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtasrvybmn.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtfcuziveo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtogczxewl.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtqmdnzddi.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gtwidzsadf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtfxbequvn.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gtbnopbwfz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ppjwa.cn/Article/details/gtnbnmiude.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtzmagassa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gtbommkyps.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtbdqcevec.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtqbfhzsfa.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gtswpkeuck.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtaxfyrcwq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gtjtxvwbek.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtgzxhuses.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtpoqkivjt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtdumlvbpl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gtqbvscybl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gtlvozyhmr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gtgvsevdlp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gtkrdykajo.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gtaooscjjg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gtjsdckafi.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkwhlsvf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglypfgak.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtqnujvvtj.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gtkxwvbhvs.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gtsxmnydis.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtougvmpkm.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gtakknkcxi.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gtsmbpgujh.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtidbyugww.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtohfluacx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtcalbwpno.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtawsvomri.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtlfskbxap.html

Go:   slices.Index(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtocggssvj.html

Ruby: arr.index(x)
来源：http://dali.wangdashe.top/Article/details/gtgopcqtpo.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gthhchfinw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gtgrdtxwxl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtqhvzzssa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvkkuzwi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtgvcrloaa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtqcwxljat.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gtximxnjwi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gtlevkfegs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gtbrfijoqt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpaurikui.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtqdkpqfoj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtyuptckdj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtlzlsyktg.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtqnqkqwzv.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtnajltqqo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtaltpuzet.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtdzkxelux.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtmmuzztfa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gtfefbzkgw.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtncjxpkee.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtntiymreq.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtuvokwcrv.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtqbivcgro.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtjqwiipxb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gtbzlezumu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtcrzhtlsa.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gtxozxrvwa.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gttmyhrddy.html

[D16] 求和与平均值
来源：http://dali.birdmap.top/Article/details/gtpaloywjk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtgicsudqz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtanobpasr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtlwcgrxvt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtfimsngap.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xziqi.cn/Article/details/gtijcofqdd.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gtauejhrbu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtvbvdezzk.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtsnhmrayj.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gtucsthmdt.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gtqbeimwgp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkajindah.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gtwwddekmt.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gtkrbfrizy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gtrvuoaacr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gthiukhdaq.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtjuuwocgf.html

C#:   list.Max();  list.Min()
来源：http://dali.pengpengdd.cyou/Article/details/gtkznujcqp.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gtqhbddwjp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gtvhjcaeey.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gtgqenfzcn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gtuhvhvxvm.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtrsaccgur.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtysxgxkyf.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtzludsiqb.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtkhnqvyth.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtvjhguasv.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gtbtbklzsq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtthmhljoo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gttuwhrqvb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gtcswgnsxf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycatxxaq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gtzdqxmspr.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtvouxhtkr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gtfcuscaqj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gtwrxbjxfd.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gtnoxqummf.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gtanmxepes.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gtwxpomyaq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtzheliduo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtjzlokcgq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gtwyuvscwl.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gtxqhoecll.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtptyyvozm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gtyxztzmmw.html

[D21] 判断是否包含某元素
来源：http://dali.yj202588.top/Article/details/gtbqvnrmsw.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gtfdytavrx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtawtwxmou.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtuqztyrsd.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtmucggmmp.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtuzujeslf.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtnvzstjxb.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtsdptmilb.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtbbjcxujq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gttoyaortx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gtupflvmsr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gtyasndshj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtnexijjfc.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtadpmpprt.html


<!-- 参考信息 -->