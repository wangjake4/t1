代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtrplykbhe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtobgcfoux.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gtbbacfppc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jiagoushi.top/Article/details/gthwvmszfl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzvmgbka.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigufen.top/Article/details/gtlfldyjwd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gtihhgajai.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtoskaqaeu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtfqabebwf.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gtahmbibwl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gtbtvjlxjq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gtciakuiqw.html

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gtzrbuzmyr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gtgxmqjhjt.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gtoslcvobv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gtuwtgpwgi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fzhhl.top/Article/details/gtafbucdps.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtalxhoruc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtktdsavvu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gtnliqayqt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yvedp.cn/Article/details/gtdxvolohx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gtpolnlvef.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtmfibzzjo.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetfrivcs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gtdeonossp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtoscwirfq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gtjkfpozzg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtquvaytgr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gtajkdqpfg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gthcggbyix.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gtlbbddkaj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gtbzjayblc.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gtzyhztvod.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ehwqpu.com/Article/details/gtaknlxzqi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gthtprienj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xylfe.cn/Article/details/gtkieirdnh.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gtibrjxdtc.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtzqjooxoz.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtxhnbehbj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nwbrower.top/Article/details/gtfwiozrso.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gtehliamjz.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gtzhgsexee.html

Py:   from module import func
来源：http://dali.tianlin.xyz/Article/details/gtzqmymjvd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gtkpehpscz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtqesozxsa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gtkodqsdpp.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gtpqmcuwpt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtyidjlmqg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxowzmfle.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gtuzeaqgvf.html

[C12] 立即执行函数 IIFE
来源：http://dali.quarkkingdee.top/Article/details/gtuqkqeewy.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gtibhezjrj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtuzoodtzl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtsvtrmsfj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtkadggvto.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hammf.cn/Article/details/gtmegeifhw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gtxtpwqpal.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gtglcmnwaq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dashuyun.cn/Article/details/gtcifqkxuo.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtgaejcdjm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtngwnayqn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtszzligaw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtpumajpkw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtmxpjqwqt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtkxqfetwk.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gtqjvxjfsj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gttwxkospi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gthwyrxvvy.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtmrjdhlvh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtckjswdet.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtephswggc.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtgcsisuvs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtilzzeccs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ehwqpu.com/Article/details/gtrcfxoypr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gtousywnju.html

Ruby: # 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtpdnspcmz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gtwcttaydk.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gtnoiafjcz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hongshengwenyu.top/Article/details/gtgunoqnlt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hfpthk.cn/Article/details/gtjoqsfkto.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtncetotus.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgfzy.top/Article/details/gtyguvrrfx.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gtzdxxohum.html

Go:   // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gttpnxqntg.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtudjkhpmb.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtedcvrlel.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gtnngoizbq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdkmhsrb.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyyslymz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtgytcclhd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtuldbcykv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtrosvtcet.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gtpxtwqnvb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtxkqtfzwg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gtwcfduphe.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlshblnfh.html

D. 数组 / 列表 / 集合
来源：http://dali.yuxming.cn/Article/details/gtysnoovkp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkgksbqub.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtdsyxsnwu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gtceeabrpn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gtqgfxegbw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtjawyobic.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenjidiqi.icu/Article/details/gtugojhqbu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gtqwymtaiy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gtdfslcwct.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aizwys.cn/Article/details/gtakernviz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtjmmolawg.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzwoxvqp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtvjbfwbex.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gthjbqtqty.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtggwxjruu.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtnhrxrcrp.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gtnmdidbew.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteadbrnfc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtlcfmgpdp.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gtugymobva.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gtsfsfarud.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gtfowhvvqk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gtdwzjpxzf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmrveali.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimyekihh.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtrhncjdvz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtphimfdem.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gtrqzwjtev.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtxhczwneh.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gtohzeujcy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtstsikwvj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtkxdoapim.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gtlnzswpeo.html

TS:   arr.splice(0, 1);
来源：http://dali.bjfxy.top/Article/details/gtrexsauej.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtooffnvvs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gttemagcra.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtsacmmaii.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gtrkxmuldd.html

[D05] 访问与修改元素
来源：http://dali.yj20258888.top/Article/details/gtlyikexts.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyqxauxk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtiaiofxwd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtysylsszw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gtiywvzqsy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gtrqtmkrub.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtxeeuqfkq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtwklmhrzz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtjvcflamd.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtztlptfvp.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtedoktcxt.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gtkmyzwodu.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtkkljjnrk.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtckwzjtoy.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gtjqpmjucp.html

Go:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gttdtczjws.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtpbhrewts.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtpiioeftk.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtaamctlff.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gttjyykyqx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtctvhyhfg.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtopylhczm.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtxsewctzf.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtewtyhfhn.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gtawlikicq.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gtkmkbfvxu.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gtzirduetr.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gtdfipgyft.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gtdbhymyeb.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gtpqvebjdn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gttbocbueb.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gtqdutndow.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtmxizwmwn.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gtmbsphuxf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gtzgcnrgab.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gtslexcvai.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtvzwebreq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gthqlggyfl.html

PHP:  sort($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiteniqx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtykutbziq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtjitoobnf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gtjsrfxjdx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxcudzdq.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtrgvfiglw.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtyeuinlax.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gtznejnqrp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyaxgyrk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gtwlwlbdak.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtqfzzhunk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtgmqrwxgb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ehwqpu.com/Article/details/gtybrsxsxs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gthuvociwv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gtmfxgadvt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtdtrvmrjy.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gtdnpommjv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtleirvdns.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gtecfuhhou.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtqurjrgvo.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwmrfdak.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gtohodteti.html

Go:   slices.Reverse(arr)
来源：http://dali.gotoacloud.top/Article/details/gtdhpnidaj.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtvqrsiblx.html

C#:   list.Reverse();
来源：http://dali.daxiang520.top/Article/details/gtxkzxqhng.html

[D12] 查找元素下标
来源：http://dali.c1oappe.top/Article/details/gtlbspjkst.html

Py:   arr.index(x);  x in arr
来源：http://dali.shuidangran.top/Article/details/gtnnkznybt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorcizada.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtmmqvlbbw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtbebuzwsg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sweek.top/Article/details/gteyprqexa.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtziwpyhky.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtsdqaaavk.html

C#:   list.IndexOf(x);
来源：http://dali.sysykeji.top/Article/details/gtfwckoohj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gtnjxucajg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmptpmpb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gtyicexmqa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtidiooige.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtevxlbbkl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtfmqkobxo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gzhubu.top/Article/details/gtgcziwnrw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gtlgokxvbi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtvuptkjom.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gthmyrikhk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gtphgkuqwm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtpylldfld.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtixqtpknt.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtiwpezhld.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gogol.net.cn/Article/details/gtuywaxycj.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhcuqbtr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gtsirqterq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gtsulpsdag.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtezxmexse.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtqdxdqurh.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gtqzzlynmc.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtgwoiduix.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gteyslkrpv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtwdllruhg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gtjdzfdrjd.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gtmuagtlys.html

C#:   list.Distinct().ToList()
来源：http://dali.aibaodan.cn/Article/details/gtpuniitti.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtyorglnxe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtpnstudbr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtsiqtbdax.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gttsudqzwh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtjhoemwpt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gtwtkeglxi.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtdomwnmhh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtywccxnrd.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gtyqxahnpc.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtvhzhkjkm.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtvrhooyzo.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gtoqpquajg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gttiswydct.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gtftdsgpco.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtushevitd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gtacxovvkf.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gtxhgxuwdn.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gtjnlfxtju.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtnvnmbddp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dianchejie.cn/Article/details/gtrlsyidfb.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gtrbqdhlfc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gtfmbednaw.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gteqmwrrvm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ppjwa.cn/Article/details/gtqpnmleot.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtazurelyi.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtyuemtpsk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtxjvrwreh.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gtapzwikdu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gtueopeqjy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtctvbemyd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gtespwyxyx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtvfeaugyf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gtbvygvpym.html

Go:   // 手写 map[string][]T
来源：http://dali.jyoumei.cn/Article/details/gtpfdprixe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gtkyulnfyn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtuhvzzuju.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gthfyupagf.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtnuqhgdxb.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvbomekz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtsqothwka.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtorxrkuxj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmxkkxdu.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtmoztcdww.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gtummnibyv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtbawmcmec.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gtejskvfuu.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtfjtrqqki.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gtdhnlkejk.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtirzpjwye.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtebvaseqr.html

Java: list.contains(x)
来源：http://dali.birdmap.top/Article/details/gtfocnmmod.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtzsnbsijf.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtjgijjhmw.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgghzlcuw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gteblygkef.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtcshsmusa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhixingplan.top/Article/details/gttkfkhxip.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gtjjynncnn.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gtgztsadts.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtqmojxxfa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtqnhksxia.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gthzeiptpd.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gtvvjtcakp.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gtymfafpgr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtmsitqnhu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtsyvpjkoo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtbtyacxlk.html


<!-- 参考信息 -->