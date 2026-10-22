代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtyvbfxdik.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtvkydkvgq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagvzwxaz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtlugpgdlf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtpdpoufxf.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gtuqxpnwmx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gtszevtnxc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtewlytsmh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gzhubu.top/Article/details/gtqbnvobsz.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gtuwcukpon.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gtaexmdydu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhiwuduotai.top/Article/details/gtsmygnoid.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gtyvkhcmge.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gttanpvdue.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtgttnvagj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gthhsiuqgi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gtmbmdmnon.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtzebxgajh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrwjhayi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.redwolf501.top/Article/details/gterbvpehe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cheryme.top/Article/details/gtqhtcicwx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.redwolf501.top/Article/details/gtomivntyx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtjrrljlgi.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtsmhrqrem.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtyuajzihv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gtxriyvqbs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtrykaytlw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtymsuawsu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtmhpsdddq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hongshengwenyu.top/Article/details/gtclprfodu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzurfvzo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gtgjypvwws.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gtximbkcru.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zycfv.cn/Article/details/gtnpgdokcp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gtxdpvwrmq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtvxofjmic.html

TS:   同 JS
来源：http://dali.dashuyun.cn/Article/details/gtyclacerr.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gtqnexwzhk.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gtxgrblxei.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gtsonvdirt.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gthcxdkypg.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gtkedywrul.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gtjsnhmxbq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gtcitlrtek.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gtrolhlqkb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gtmdxhsccl.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gtfofzmlpj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gtjubuubor.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gtlheicxtd.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtyyrfvlhx.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gtgtrvnuhg.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigfzy.top/Article/details/gtemqjpdmj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gtnohmdoqt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtezdgliuk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtrqvdycmd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gthpyvgolf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gtzrbirano.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gtawtyygpd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gtwvtjdqqi.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gthequajsg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gtdtqwadde.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtgxexjwor.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtrzhjcydc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtlkohyjlx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtrqmyfrgs.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gtemqmllsb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.quarkkingdee.top/Article/details/gtsahzcecn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtkcpeebtz.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtitripygu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gtkbhbjltf.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gteluwsxfn.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gtrpscilsb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gtiphxoqsi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gtzecdvckh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtkjqpmqve.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtysdeqafc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtilmuzsdy.html

[C15] 解构 / 展开参数
来源：http://dali.havefunace.top/Article/details/gtcuaqvaph.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gtqpucqzzt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtlsdxwyqb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxxdofsld.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aibaodan.cn/Article/details/gtxxlysxkr.html

Java: // 无解构
来源：http://dali.daxiang520.top/Article/details/gtvitjhldk.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gtqyjvwdrc.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gtivtcrhql.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtjzhesvjd.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gtmghjfirv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gtxowipath.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gtfpjgudgl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gtlegxdpyd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbjeemjc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxryeefn.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gtqyvckkng.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gtvglabrbc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnlpstih.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttbjsywod.html

D. 数组 / 列表 / 集合
来源：http://dali.snrcjt.cn/Article/details/gtuagbzemw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtcvdblghy.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtcmugokdi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gtobuptzmc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtembtdijo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtmzhjajpl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gtkxzmmnhw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gtcyjpuled.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gtvusdxhjm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gtauuomzbq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gtbrmrzvdt.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtmipmfpnc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtfflsclvq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtoirtxlxl.html

JS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtoanwuulg.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtdvozugxm.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gtctuqdtrt.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gtjksdvjpx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtqrnunsfn.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtexatgiaz.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gtelvqkezf.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtsywysyqd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gtqcyceequ.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gtepqegofm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtpqsujnhs.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtvxqtqoxa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gtxmrnzyvl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjxzfufn.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtongzxxsx.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtgcogfwen.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtmxkhwfxh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtichmsxrm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gtqfgamoqn.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gttmijwvqs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gtpnhrejqx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtzyhlurll.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtaduwayda.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gtanesmrmi.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtcdqwhrxd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqlfarox.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunhfityb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtrxagczll.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yvedp.cn/Article/details/gtrylbfkln.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gteuqphzaa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtgckujhtn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtytuayslz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolqchgyv.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gtadbxbicj.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtwrshggkh.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtrtwmdotm.html

JS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gtmtwubnxd.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtghfocobc.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtyiuorvdj.html

Go:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtteflldek.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyitpxnbl.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gtjvccynsz.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gtubapzkzq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtokhgpuuq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtovbvbjov.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqigkhimu.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtegummugs.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtkcwmoakc.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gthpjontwz.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtmksgpepu.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gtdpgcqjss.html

[D08] 合并两个数组
来源：http://dali.fzhhl.top/Article/details/gtxxyusdnk.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gtlrzlrejd.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtnshrnclw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gtafugydex.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gtnjivrgmt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gtqxujjusq.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gtqnwqkolb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gtvmfpacaa.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gtmugltorj.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtdkshenfl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtyhtzncea.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpfuesqs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shzxlz.cn/Article/details/gtiljbahmf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gtmsncevfa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtmsjevovd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtmxdjoyuk.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtzdgkbzpq.html

C#:   list.Sort();
来源：http://dali.tianlin.xyz/Article/details/gtmnjomiod.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtgirakzpd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gtruatcddf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gtyacwgwem.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtazvpecrr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtyfwrvsal.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gtdbiywhso.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gttltxpiuu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtksasufzm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtmagdnmny.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gtodooowxh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtqkhsgamb.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gtloivtejj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gtwannfkek.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gtnkrsdszy.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gttbzklijl.html

Go:   slices.Reverse(arr)
来源：http://dali.dianchejie.cn/Article/details/gthcfpgkhz.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtqcqsiqhf.html

C#:   list.Reverse();
来源：http://dali.jinqigufen.top/Article/details/gtfssayigb.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gtwzbmdfyq.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtdshpandd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtcuftwvmj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtrhndzatt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtbalbfzbh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gtybtqckbq.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gteduztamv.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gtyaljaytq.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtvcsxmrpz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gtlglafgxa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gtlmysyjrb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gtwjdozeqs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswptepge.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtxosuxnfw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtpeyiyyvs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtwhqozsvs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtdyxqvmou.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtnkzvlqkg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gtryosfxoz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gtifnsawcf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ybcxt.top/Article/details/gtcojleqcv.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtsxvjithl.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtswtshxlg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtwvfvuwsr.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtnuvwdxtk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtlxzaqbkx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hfpthk.cn/Article/details/gttzsjmqkp.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtdgbikupu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtjepvcstp.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlxzsrox.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gttdxbzelk.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtzvviujnk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtnmwgpfme.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gtarlaidas.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gtgpgmsens.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqhxtmvs.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gtzousenua.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtrvzqszfp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtdtenaopj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtgxitiihu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtwgertstn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gtywyhfabh.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gtjruffzba.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtrrzepmeg.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gteehzuopc.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gtijddcgls.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtwvbezzci.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gtovqfodby.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gtwszqhvpo.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gtvboleumr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtucqkding.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtqkcfmwly.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtiyrcdqgk.html

C#:   list.Max();  list.Min()
来源：http://dali.cashguo.top/Article/details/gtdtyivxnk.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gthtcnnuog.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gtfafppiiu.html

PHP:  array_merge(...$nested);
来源：http://dali.9152youxi.cn/Article/details/gtdjknsviu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtbxzxaeav.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gtjpddwokp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gtbskudcdh.html

Go:   // 手写双层循环
来源：http://dali.hfpthk.cn/Article/details/gttdzoogam.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gtbtggimiz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtgrzjortl.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtjfyaqwiv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtbxmtjbho.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtpjfdkprh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmrjlthv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtcwfklnyl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gtynkkhjmc.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtwevpnbhj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guannengcc.top/Article/details/gtlczrllbk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gtjsarrcnb.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gtcicawjgg.html

Py:   Counter(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifqeusbl.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtgqhipsdw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtybllqhxc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gthqpsmvdr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtudrhhrro.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtzkwwnlgr.html

Ruby: arr.tally
来源：http://dali.fzhhl.top/Article/details/gtkqxglhuw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtuibllhqw.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtyifcibfq.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoprjpkxp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtjrulyzbe.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtxfzxfzcu.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtbuvvmoui.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtputopmzp.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtvzpzbwea.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gtjsenmeot.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtidpdluiu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gtgirkpucl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gtgvksavdb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gtgnxdxzuh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtqkewdhqd.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gtdibaqbnz.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtztpcckeb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gthikhfpxt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gterrjuxta.html

C#:   new List<int>(list);
来源：http://dali.yangfankeji.com/Article/details/gtsqwsnlyy.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gtmplsuxyf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gtqdscvzhn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtbkhdestr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtgwbhnybb.html


<!-- 参考信息 -->