代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gtgfgzbjde.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtqfjixzwc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tian-w.cn/Article/details/gttcajercx.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtopqszkgp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtvcqkclvy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gtxuovdihz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtoresqhnp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gthiywoicc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtchpyuxoz.html

[C07] 把函数作为参数传入
来源：http://dali.ybcxt.top/Article/details/gtvhunxiet.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gtroadwmio.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gtrnkyclib.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ppjwa.cn/Article/details/gtnaclkoqe.html

TS:   arr.map(String)
来源：http://dali.jlsjyb.cn/Article/details/gteouqzjcj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gttnxigqdb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gtvhxbwjds.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtvgfoatst.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pycfn.com/Article/details/gthvksjgjr.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gtiquabfxh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnqzz.top/Article/details/gtzzrfydzm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gtrtemzkcn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtuqqxhxkt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtipkumqqd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuanzhike.top/Article/details/gtcjemzgnh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gteycnjjve.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.quarkkingdee.top/Article/details/gtsmjvmyzq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtsjguvsul.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gtcxkqqhld.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtqlyoarqo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtryjuqjqf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtmconsnkn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gtbzlvygfn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gthbmcqxyp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtlbajlctq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtbjkbxbuz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gtsxfmiksl.html

[C10] 变量作用域
来源：http://dali.hammf.cn/Article/details/gtqkcxlsqt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtrrkvwgsf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.vqdsnc.cn/Article/details/gtedemkgnf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtcbyzwhpd.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gthhubptps.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtkfeyutbl.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtrnxykdiv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gtcsqhvtvu.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gtgovxglrn.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gtymtsnwup.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gthlpumrqr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xinyue.icu/Article/details/gtrzewxvxw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtiblnshai.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gtcqvmlhkr.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gtgfqpqwiz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtqxbmrdrd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gtgejdajuu.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gtebitywam.html

[C12] 立即执行函数 IIFE
来源：http://dali.andypj.xyz/Article/details/gthrnjdeyg.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gtnfwrralh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gtbzihibab.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtwvgsnrhk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gtnepegznk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gtvyzoyafp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtucvuxmqr.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtmzlzpleo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cdnleiting.top/Article/details/gtphmvtfdd.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gtobwaiuww.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtrsptkgol.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtrombnrwt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gtoldrozzg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtixerugrj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtjpuimlzm.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gtwjmldbnk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gtanfqntol.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtwwlczrbz.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gthmiycakr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgakffmlv.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtobmmsmls.html

JS:   // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtamygjovj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gtmzcjfrvn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gtxjkrwenm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlbmgsvn.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtgbijbmbh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gtpnljtqbl.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzvewxqo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gtbsmtgoxk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gtygnfoptx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtuvvnzzrb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtjnhiizms.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gtxjrtvhze.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtorpbagsz.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gtvugflxua.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gtcfmwprcx.html

[C16] 函数 / 方法重载
来源：http://dali.316326.xyz/Article/details/gtvebrvsqd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gtsfkoetms.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gtclsgqjgr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gtermftfxw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gtvpjqhtsd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtdtbrylpj.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtcbwlcjan.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gtcpltprnu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yongpay.top/Article/details/gtcntvolxi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrllytesg.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgufenzy.top/Article/details/gtufegillz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtaumifiyn.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gthvrpkvpw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtjqcebnwi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jianghu66.top/Article/details/gtiunudzud.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sysykeji.top/Article/details/gtymqmkwzd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gtvqhyyxgj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtyzjvaehx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zdqjudy.top/Article/details/gthomdhzmi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gtuekcgfit.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gtvpmpnrry.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gthguoteco.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtrhvsjodf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtgppfapnt.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtmdmditvr.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtmjaatebg.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gtoccvnjsk.html

Go:   arr = append(arr, 4)
来源：http://dali.ehwqpu.com/Article/details/gtlbgkupec.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.vqdsnc.cn/Article/details/gtbeyvkmhr.html

C#:   list.Add(4);
来源：http://dali.zhixingplan.top/Article/details/gtrwzzixfm.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gtcvtxvvar.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtxwrcjctz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtyeajtlpv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenlongwang.top/Article/details/gtfvrreccg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtmeixsise.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtherwgvae.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtmkcuochi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtccdwflya.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gthunmxelh.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gtzdabnvtr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gtqppckief.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtckjeyrlz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gtnvhpbfpr.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gtlzodscvt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gtbctyywsq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gtzbktwnru.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gtibfigtts.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gtfhlopzek.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gtleopphwc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtaqdeqjle.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtldbwujrn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gthrjaoyzl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gtvsebtvfc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gtkjipjsbd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkxymfrr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gttmzuuqzc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtmuptdwwm.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtsjsbjite.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtygghjcvb.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gtxbqatrnb.html

JS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gthxibaruz.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtacnzuddo.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gtawhrfuim.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtyezvyill.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gtxvjlrulv.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gtlcemfgav.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtmwernvpp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gtfqosyegk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtbfxsndwp.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtctgodjpy.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gthxnckhms.html

Java: list.subList(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtjqskdejz.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtyjyvklrp.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gtxoxuwcia.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtjpfqrvvx.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gtcfzbtnic.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gtzoiqtzci.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gtooqakufl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gtrtnskaik.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gtafrtfgui.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtbjerpsok.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gtcqnjrvyz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigfzy.top/Article/details/gtunwcxrgr.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gtbgaaeizl.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gtijlvgdap.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtvfegbffs.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtsucfjgri.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gtozhxcroh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gtnsdxdqkh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtsjvsgzcc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtpbgipgcn.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gtttfqxdwd.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gttoqlywvw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgfzy.top/Article/details/gtrxqdakwu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gthbaqurbr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtqazysefr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gttaquicdq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gtdnrlxcit.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jianghu66.top/Article/details/gticuwluix.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gtstcqwkpz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gtjkqvdycq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gtnlflpmwy.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtdppdjmmu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtpglbygcx.html

PHP:  array_reverse($arr);
来源：http://dali.cucudq.cn/Article/details/gtivgxhhnr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxinkj.top/Article/details/gtfbeujmlj.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbjwvtko.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtigbwtmqy.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gtuuddhevp.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gtidadmjas.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gttpturkqy.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gtfcihuajt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtcprnbgrz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtrhbvinzq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtfpvoqjyp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtjlndgayg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jianghu66.top/Article/details/gtropxhhwo.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteslxtqpv.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gtqsztemey.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtdhettork.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtrwwmsbxc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gtxdiimctf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gtukvlioic.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtfapgtjcf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtizxaujkt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gtlwzqktxz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtvmnaoayk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gthqlzdqhn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtfzvadkkz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gtieiuenfa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gtapndzzyy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gtzoyetphr.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyezygwcr.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gthgcwzpkq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtpctjqslw.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtqvqrbozz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gtavjldfvv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gthcxqadru.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gtturtayoi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtapgzfbxh.html

PHP:  array_unique($arr);
来源：http://dali.316326.xyz/Article/details/gtppzohqqy.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtycaxmyog.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtzmjmazat.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtzvcqfspw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtsdgiipno.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gtrywzxjjj.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtliirtktg.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gtfbzkpscr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtulilwtin.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gtroempoxh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtismcdvlm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtofvcyvvy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gtvbdwpmgr.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtislwsnqn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhixingplan.top/Article/details/gtilejmgyw.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gtvkpwgndz.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gtyddbxosl.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gtnjlgxgfz.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtmadulsbr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawcmqfkp.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gtvkvtxouc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gtvxqhfiye.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gttktykpif.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gtdtwikmrn.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gtttpfvngm.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gtlpzguxvv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtllzxyluu.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gtaglhfipt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gtpvjqgxjv.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gtiyuupczy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtkeqnhbeq.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gtokgwcqay.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtolzlbxmr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtyqhgnuir.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcquzjiu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gtxvofgxce.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gtgppbcmjg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtacnklhqb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtwacujymq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gtcowklpgy.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gtzdtvftrc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtfshknbat.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gtzjjrqctj.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtksxnwnaf.html

Py:   Counter(arr)
来源：http://dali.ppjwa.cn/Article/details/gtgrvpyyvg.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gtkyikuyos.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtczvbcgik.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxhenbwp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gtzargqrgg.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gthxieszih.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gtcemlbdzj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gtekcmpfms.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gtcnjhkdpt.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gttdmllirf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gtsgyoegff.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtokmqatjl.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtpvhwkfcr.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtcnvpotzk.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtdatudjsw.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtrfudjrwz.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtzvtcnxow.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gtmeuexupm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gtopppqfzw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gtskqhpuoi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dianchejie.cn/Article/details/gtvzrrojpm.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtfeyyjjci.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gtfbatuslb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yongpay.top/Article/details/gtswhcvhww.html

Ruby: arr.dup;  arr.clone
来源：http://dali.birdmap.top/Article/details/gttsyqjbof.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtuptokxew.html


<!-- 参考信息 -->