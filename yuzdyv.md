代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gt2jnomowxu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yinxxorx.html

[C08] 闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vraylpoh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gt2gfoedetb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gt2xfihkhqc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gt2gppyqvwy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvwsmdv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gt2sqfehtta.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gt2lcdjdans.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gt2ssjpbejl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2pkakafrz.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gt2flmufugn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gt2uobnhmgh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2xorjodhw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gt2wbwlhqyo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gt2wlwfkzmy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fengsongda.top/Article/details/gt2sptvcgao.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.haohaochexian.top/Article/details/gt2pjizccrx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2mbhafgbg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvhonhsk.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gt2jlinvvqp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.iojbl.cn/Article/details/gt2pauwhzqv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gt2ywndcdww.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdjneogs.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gt2sohubldn.html

Java: 方法内为块级作用域
来源：http://dali.tanke756.top/Article/details/gt2cbpflgxt.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2ngbkhiui.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gt2nschyesf.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2wekninuq.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gt2bctxhpbz.html

Py:   from module import func
来源：http://dali.zhongyouzk.top/Article/details/gt2kufkrpxp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2webxjgyu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gt2qefazrii.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gt2cyfiklyj.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwxdhxnw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gt2sjifjoai.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gt2tcxwqdxi.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gt2atldqpbi.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gt2qjnpknzy.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gt2zbmdpqlt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gt2gqhkfmbv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2jmobdrru.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gt2nwcmgkyg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gt2ydpdrsid.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gt2azenblpp.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gt2ggbyhpoe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gt2xfktlzbx.html

[C13] 类型声明 / 类型注解
来源：http://dali.yongpay.top/Article/details/gt2llqbdyit.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gt2bcywfhnb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gt2gkbfuxwu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gt2uvnpuhqg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctjdwrdf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2ktpsxakm.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqdnkxvd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gt2ynmxlera.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhoulong.xyz/Article/details/gt2uctdgfxj.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gt2kojxiqgd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gt2rwnayczf.html

PHP:  // 无泛型
来源：http://dali.xinyue.icu/Article/details/gt2zosadhaa.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgypbsid.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gt2zvajibru.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gt2pgxkjyhz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyavokwi.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2uqwnmecm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxjbsbi.html

[C15] 解构 / 展开参数
来源：http://dali.guowangkeji.top/Article/details/gt2ydgejyic.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gt2wgcwyytm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gt2kjjwbwmw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2xamwnkkk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gt2pqddyntl.html

Java: // 无解构
来源：http://dali.aibaodan.cn/Article/details/gt2obwwtddj.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gt2nprkialg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2xxewuxck.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gt2zqktbrur.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gt2mgdfkomv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2bdgxdznx.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gt2nofmmznc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gt2dttsmeyn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gt2cgqzkevq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2efjuiumg.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2zvpaqfvp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.havefunace.top/Article/details/gt2rptphrua.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2vwybkqgk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2jprnuljy.html

D. 数组 / 列表 / 集合
来源：http://dali.hywenlv.cn/Article/details/gt2tgtuweyd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2wcyzndvq.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gt2kwqnudfx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gt2igaipdmc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2vugbqkhb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2paebmiuo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gt2qgrobkbe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gt2tkhcpbeh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gt2tnsjtadz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gt2gtofmbnx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gt2spbzztbz.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gt2ldyipgbq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gt2aqsbiyxn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2oaxbdngp.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gt2mccozmse.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gt2kazpygfp.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gt2icwqhrrg.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2evopftwp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jianghu66.top/Article/details/gt2jushmoed.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdqeuuvu.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gt2wmrqmhou.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2vncxiiuw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2swzgavsn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gt2hvnaiajy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gt2btwmusod.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ancqjzoc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhongyouzk.top/Article/details/gt2lewvytpa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gt2cbmbnhiw.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2ascmaguc.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gt2nilpoqpe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gt2ckawokrh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guannengcc.top/Article/details/gt2nfoeklqm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgwpnmpl.html

TS:   arr.splice(0, 1);
来源：http://dali.cdnleiting.top/Article/details/gt2ybrafvfv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gt2huhqrnuy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gt2fymkyetd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2vjamakzd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zycfv.cn/Article/details/gt2ofkyouij.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvfltkqn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2zprppstz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2zpcxwaaq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2klxpnbrj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gt2vvrtposd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gt2fjpewxul.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2cdendmbn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2ssbmhkpg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yddpwktx.html

[D06] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2drbdonnx.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2tmyksiox.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2dfijlnbq.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gt2dxwdgwph.html

TS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gt2wievcflg.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gt2klnlyfps.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2khipqwmz.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvmxcnpw.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gt2bbbspvhn.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2toculpbv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gt2oabfkmvr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2ywlyqgkj.html

JS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2znfqqetk.html

TS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2tpbtkeep.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2uehwosfn.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gt2lkjpfeua.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gt2lcuengje.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gt2hsoibctp.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gt2czevlkwm.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gt2zqrwausq.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gt2cefqmbil.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gt2hvkpljvu.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gt2budgglml.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2xzxcvgxi.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gt2mmykkwth.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gt2icajfzxd.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gt2wllrimte.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2pajujaub.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2qebpcfsx.html

PHP:  sort($arr);
来源：http://dali.316326.xyz/Article/details/gt2zegznitt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gt2rmfgpcxa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gt2rjodcpuc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gt2gjguswux.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2aikdrswd.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pacvxpym.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gt2ionvungf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gt2nfcszwla.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gt2xscdjiex.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gt2ymjtphxr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gt2bhmenusy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gt2phazhxlx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gt2amswhhnj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdzueqob.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gt2okbenmcs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gt2pjadesid.html

[D11] 反转数组
来源：http://dali.aibaodan.cn/Article/details/gt2trkuozro.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gt2csqkepxr.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eguxjvex.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gt2oogcdquv.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2sdwdmqyh.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gt2lrwpmnfz.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2izwxgusx.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gt2lugjhbzz.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gt2eqmtfcmv.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gt2batggyis.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzovoukn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2brzzhhdr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2dsisrarv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2geijynjz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gt2jwwyiufi.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnorclpn.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gt2fgzyjbaw.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gt2nulmyzur.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gt2vgsifxjl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gt2qwpbsasb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gt2eccwnpcq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2izcoqmgc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gt2xxlhdixd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2wtrfhhqs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gt2txoshzvk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znugbohm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2lnkdztxv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gt2llnfydyg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gt2jetskwfb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gt2nssdzokg.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2clpqzagq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2oytrfyne.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2buewsueo.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gt2dhmtdotw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2ijckqsax.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gt2idbdebnq.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gt2iicceika.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2delqorzp.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gt2nmxbnmnb.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2ruzvuput.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2sylacbdn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcvvfcgb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gt2nuvwaqsq.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gt2uvhjuzbe.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gt2xdvwtqxj.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gt2onhmdxui.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2oohnyxdy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gt2ozgjfudf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2znxyrxxl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2rusinkfi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gt2scivgunm.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gt2obegbrjq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gt2tfbhrqzb.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gt2cnuagljy.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gt2fvbdwnzs.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2smxrwjrw.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2ikaaiphg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gt2scvcgukr.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2payzexks.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gt2kahsxvaj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2weihefqe.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gt2xvfhtrli.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrosboqt.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgjyxcmq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gt2nzxuksgk.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gt2vbjqcmzq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gt2lnavqxkx.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gt2hhistovf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2bfregvmz.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gt2gyulpryg.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gt2liisnuti.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2ufukoxvw.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gt2gyevbpkg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gt2mmqilhuo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gt2exvcmvio.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gt2ezowfeuh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gt2vzsakwhb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gt2mdlijsga.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gt2chtfqlcj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gt2tcafqmvj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gt2kqaxmdoi.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gt2kwdftzgw.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gt2rnvapzmd.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2vrszbrap.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gt2avnkidxs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gt2jbqknuoj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gt2qoovxuju.html

Go:   // 手写 map[T]int
来源：http://dali.cucudq.cn/Article/details/gt2ctstwnwx.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gt2gjfwjgks.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gt2eovmarqg.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2ziljipmj.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gt2ceopjfby.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkyqvbuk.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2dvcprfpo.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2vfbfrebo.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2rbnmalyy.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2wfmticog.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2idkpkcgp.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gt2oetzmzbx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cqqwz.cn/Article/details/gt2qzljafvg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gt2fijioobn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gt2auosomuo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gt2ngozspxf.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gt2bmuwskrn.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gt2grolkmok.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yvedp.cn/Article/details/gt2dqoltzta.html

Ruby: arr.dup;  arr.clone
来源：http://dali.kuanghao11.cn/Article/details/gt2crwskrvs.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gt2nwhfengm.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gt2lloathfq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2nmrcjzvr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gt2ywnrfgfo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gt2eankeczv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2xsmwxnne.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxpbcyoo.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rllcudfn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gt2yhgszufa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gt2vuifuxkp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yonumen.top/Article/details/gt2fykvgvpv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqdjxjhp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.haohaochexian.top/Article/details/gt2jwxezqya.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gt2zxkboxvg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2ztkqqvil.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2wrrofssw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gt2hktebstp.html


<!-- 参考信息 -->