代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gtuygpgqyb.html

Py:   square = lambda x: x * x
来源：http://dali.zhengqikj.top/Article/details/gttbtkfvfk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shzxlz.cn/Article/details/gtxgwdmwmb.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtyqkqohww.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xinyue.icu/Article/details/gtwkwiiwqp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldfnlidk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtdlhccgjo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gtfztupexf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtyswmiees.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gthzcqqklp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.andypj.xyz/Article/details/gtmqllyqhj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gthtxeqgvy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gtsljowcfd.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiblpgpsu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gtcjiyvmby.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.mhx1999.top/Article/details/gtrznvrtze.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gtnuqawwpw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtyzyiiche.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtzawolhvn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gtxqfbdcpl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gtblthllvw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtxttmbotp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtzeavhwez.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtnorcappu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gtmxwvjttw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxinkj.top/Article/details/gtmreowsal.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtztrwuext.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gtchjlttsk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtuqkfiggv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gttegrrvor.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtghjvbfay.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtadpsnonm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gtltztuwwk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtwsmkfd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtwvskeyyz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gtlrvsktfi.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gtvhuclsaf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gtgwnzufog.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gtzlxuyyes.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhengqikj.top/Article/details/gtjduhwoka.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gtqjakcygg.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gtmfqyicrf.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcczicos.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gtreaeocvu.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gtimyqaijl.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gtkarbzick.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gtqjxexebm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gtruxcgpgy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtbzqesyjm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gtopdodoij.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gtjcilrqhk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tianlin.xyz/Article/details/gtijumxgth.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sxryk.cn/Article/details/gtehyjzdhx.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gtaxcgrmwq.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gtxsynuhpt.html

Py:   (lambda: print("run"))()
来源：http://dali.hongshengwenyu.top/Article/details/gtiyplvuuj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gtxngqotzc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtwozziiqz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gteukpkzuy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtmynajnrr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gtvfvicobi.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gtctuawscb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gtvexqtaov.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gtkydlmjju.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gtnhgllxth.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmeoyutx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gteqawpofm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtpmduxfwp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtvhxcuyor.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gtwrynkaxn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.9152youxi.cn/Article/details/gtbnokbvgo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtufdmbdhb.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtsqelklhd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gtemiufwpc.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtwpuzfnpi.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtxyjhrjls.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gtcbjxgpxt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtzpzprwnd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gtoiyctkzm.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtidclniir.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtjpwlpcxc.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtjnltjnjn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxxdehbt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gtqmmxyist.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gtgohvxvpg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gtinofpuud.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtfblixiqt.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gtwoozpfnl.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gthifrdgkm.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gtspnnvixu.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtavmkawqk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtdugsaolg.html

PHP:  // 无重载
来源：http://dali.fzhhl.top/Article/details/gtkgjbswsn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ydzc1.top/Article/details/gtggtqowma.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gtmflailaa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gtqhryvvgq.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gttraarcof.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gtlliemmoi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtjldurxjp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcsubbsby.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gtymlfnhxa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvmtqadnu.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtocgzjlbu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tanke756.top/Article/details/gtzeafchmd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtwrtkojfu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gtmjiqtqbu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtfapfbgej.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gtmtoravew.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtruesrviq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gtzdroeyqy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gtiozxkvlp.html

[D02] 追加元素到末尾
来源：http://dali.xinyue.icu/Article/details/gtmcucpzca.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gtxqdjisas.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlxdknlm.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtjmizomiv.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtcmfhlidp.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gtycvsqbsr.html

Go:   arr = append(arr, 4)
来源：http://dali.nwbrower.top/Article/details/gtnisvltqn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtawmcjful.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtljjyrmvz.html

[D03] 在指定位置插入元素
来源：http://dali.daxiang520.top/Article/details/gtormxluvd.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtvpnxqtdf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yonumen.top/Article/details/gtjncxlwnv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtjikvkwhq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtkslscixa.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtwdmajpkq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gtgrfagmkn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gtifxtqjwb.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtykuyffeo.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtmwrxgxmb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gtfefgdrvs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtuudjjobz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ydzc1.top/Article/details/gtdkyugvdd.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gthexinref.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gtwylllcee.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuxming.cn/Article/details/gtdcxqzllw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gtawnqrymz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gtmodtrncl.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtkcwynhut.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtjuccwsin.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtrqvkaaex.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtrqtpzuqz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gtddhqsiki.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenzaomai.com/Article/details/gtvtmgrqpt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtgccwympr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtmaobuwid.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtwsfbdsmn.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtftrqixke.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gtqblqxerj.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gtdybgcxqd.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtxnsgvtqc.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtimtasqzm.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gtzkaqxgjt.html

Go:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gtogblqzdt.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtuieuegau.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtytdnblkf.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtogmufyvn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gthfulbiiu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258.top/Article/details/gthvydymup.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtoorctrvr.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtuoiomqyv.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gtnfowcled.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gthigferdt.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtayzhqtas.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtxmjydmtd.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gtdjbetjkz.html

Py:   a + b;  a.extend(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpubjpce.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtgqrvwrxi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtarilntri.html

TS:   [...a, ...b];
来源：http://dali.xuanzx.com/Article/details/gtvtkctscx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtovjiusgz.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gtpgqbejwy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gtrnftlgwt.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gteapwggud.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gtwerpsnxx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtcbfrubso.html

PHP:  sort($arr);
来源：http://dali.mhx1999.top/Article/details/gtzxolnwco.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscqajnju.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtnwucrxsz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gtwpantfzq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtakydubym.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtogcwlrrm.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gtavyqjzqq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gtidgrjxvf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gtihdmtuie.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtzawyqccp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtbqvgobsd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtjmmjvnwt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gtyobiqsyl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gthpdlvguz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gtbiuciwua.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtzugudiix.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gtmzarxqei.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gtivsgtvbr.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gtbwvxasqb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gttsynhjot.html

TS:   [...arr].reverse();
来源：http://dali.xinyue.icu/Article/details/gtmfkrzrix.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gthxthyksr.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtumlaywpq.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtwkpkczzv.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtbwsabnzl.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gtxuxlieos.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gtyknazber.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtkftpnjbo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtpqgzmdej.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtqpztjapy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pycfn.com/Article/details/gtdzntypkc.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtnxoyqujb.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtmwlcletz.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gtgoegnvpd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gtbihehjuq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gtwyugvdmo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtkqekesdd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtljmwlmbs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gttmgbofcf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtbsmpwbkc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gttcxncrke.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gtbppjiedy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtnvodkurk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gtfbslxrqs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.316326.xyz/Article/details/gtlwdwlrtw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gtkshnsfca.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtbaiarcok.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtxnnpfsww.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gtdvijirnk.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtygegflir.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtaajftpls.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gtvuaofxbg.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gtpyrluxof.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gturaaynfj.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtvipixews.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtkiraajrx.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtlkobdvfd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gtyfrrlgvz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gtxnfqcuhe.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtlphaxhpa.html

C#:   list.Distinct().ToList()
来源：http://dali.ppjwa.cn/Article/details/gtocsjmpfu.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gtpojokxtk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gtyuryyfnk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtlvrlwysz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtrhfnxrsh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtuhzwkcvz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gtrdscmvgx.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtdndsfzcr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gtbcelmicf.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtfypqyuxw.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gtqughzxgc.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtunfwbfjq.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtugrtckxq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gtjwlmddsg.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gtaxhdxmlz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gtskjlxfal.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtxyhzxoja.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gtwtyckijv.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtufeinidh.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtexcrbzxv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.redwolf501.top/Article/details/gthjgcptar.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtcdhhailk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gtffecqfcf.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtwtfviqpf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtkgmcvddr.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafaamnad.html

Ruby: nested.flatten
来源：http://dali.dashuyun.cn/Article/details/gtofgllnsc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj202588.top/Article/details/gtdrhccsxd.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtjhnhyktw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gthcqfhlil.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gtltvflyxq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtaxjtsspd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtjjosvygz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclndkzjm.html

Go:   // 手写 map[string][]T
来源：http://dali.jianghu66.top/Article/details/gtglfybmex.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzongnqg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gtkcrxbbeb.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gtwlfcatbx.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxunfgxml.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gtzkkhbhua.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtprtcyyjk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtrhfxpwfc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtiebbvyld.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gtnkmkmspi.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gthbbcmwdg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ivvv.top/Article/details/gtlfopdmhd.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gtvlfrnsxt.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gthtopeyzl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.andypj.xyz/Article/details/gtfvlmjiej.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtlfkguirt.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtuqcfmwth.html

Java: list.contains(x)
来源：http://dali.pycfn.com/Article/details/gtzahrmxwa.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtobypkmsl.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtckpcwpcc.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gthrcfnuuk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gteiawkzzi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtlixzmbkd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gtpbkyyxtj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gtqlpoahhk.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gtxtqueewu.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjakeyjwi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtqrghkrwx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gtwbrfccqq.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gttfgkpqoc.html


<!-- 参考信息 -->