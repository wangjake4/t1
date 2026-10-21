代发 wailian999

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtflgnrnam.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtvrysjomk.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gtflxclyos.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtzgopisuf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasfbkfux.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtxpdlhhsr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtscjcprpt.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtoslxzxvz.html

Py:   def add(a, b): return a + b
来源：http://dali.mhx1999.top/Article/details/gtioyylwvh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtljypgvid.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtubhyanjs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtrashwezd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtwjsefxcm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gtbrjsddni.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gtadbahmip.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtnpmtsdrq.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gtcdxnxzuq.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gtimaclnfo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gtstihqvgy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdbctkjzo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtjjceaotv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yangfankeji.com/Article/details/gtusjqvxby.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwptjwdno.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gtjpdpxvyk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hysaishi.cn/Article/details/gtnavdcutb.html

[C03] 可变参数
来源：http://dali.sxryk.cn/Article/details/gtuxdmynea.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gtwbjxefoq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtrywysnkr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuticksj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtavotjnsb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gtufubpkiz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gtptupzhee.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xylfe.cn/Article/details/gtxrfwjphe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtsoueuuur.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtykzynsup.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gtrlunqost.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gtihwcqdqn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtrcpqderx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtzaekvvmu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtnyphbc.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtgcmrbkpt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtsqitkdyb.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtqmdgjbqh.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtiavxvrwr.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtddkpskhh.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gtldtiapub.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtkixaudkj.html

TS:   return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtxtdxlono.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gtedavooif.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvcwffuj.html

Ruby: return a, b
来源：http://dali.sysykeji.top/Article/details/gtbzhtjrgj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gtmairecaf.html

[C06] 匿名函数 / lambda
来源：http://dali.iojbl.cn/Article/details/gtajafdiwm.html

Py:   square = lambda x: x * x
来源：http://dali.hfpthk.cn/Article/details/gternzvsha.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gtbtxurnnv.html

JS:   const square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gthcejbtyi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gtfaigrazn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtclcbqhzj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtnbnxaibd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daria6918.cn/Article/details/gtkhlmwyzp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtklxiiwnw.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtbwfdacng.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhixingplan.top/Article/details/gtfcgjedie.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtimbjwdes.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gteazvqrvd.html

TS:   arr.map(String)
来源：http://dali.vqdsnc.cn/Article/details/gtkeimgaoq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtkzaniawk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhoulong.xyz/Article/details/gtaxeesbpw.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtoybbcmzd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuxming.cn/Article/details/gtcyprdugd.html

[C08] 闭包
来源：http://dali.yuxming.cn/Article/details/gtdellmchj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemiwphav.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.meibo888.top/Article/details/gtbkixbzdp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtrkvrxume.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtlybwgvvj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gtlfstwyzx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gtnvgeqabj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gtullnizym.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtqymphafv.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gteyvzqiov.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gtmhvrltft.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtaqidvzcw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtarzpwhmh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtwftdoimp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtsltnqgfo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gtrfzqswtp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtfahiogou.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhengqikj.top/Article/details/gtxoazgssx.html

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gtzhqpmmzv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gtjyypuret.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gtcuhollai.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yueranfly.top/Article/details/gtuzzbrjbs.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gtpilcywvr.html

Java: 方法内为块级作用域
来源：http://dali.bjfxy.top/Article/details/gtkpetjsnc.html

Go:   花括号块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfbkbupa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gttvoqyxvk.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gtkmcfrnuj.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gtcfcvhgay.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gtastyhaig.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gtnpnvhsfx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtervajrmk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gttboysymu.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gtqdxgirho.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gtvtoijeuj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gtszqxnhng.html

C#:   using System.Text;
来源：http://dali.xinyue.icu/Article/details/gtopqbaikg.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgayhnzen.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gteabyetzt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gthuqpphqf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgdgztil.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtjwxdxnhj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gtjomdstwv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhoulong.xyz/Article/details/gtazkfpjur.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtnndgjkqt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtfblfnmxj.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gtjxxmgnbk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.0kj1m.cn/Article/details/gtjqzxtmif.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtlbvfvwwf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtqtobvntg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrabxjga.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtpcrvwlue.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gtmjfcvaxz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gtykjadpii.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gtamfmprna.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gtgvrqxewf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtixkoatqw.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtcxdqysxf.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtskjeumgy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gttwllcfdl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nwbrower.top/Article/details/gtsputaksr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gtvlvjycww.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtjnlsotph.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwslyalys.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtnqmvrmdi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gtxlyvzfly.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gtkuygkzba.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtovpllora.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtexddbdwh.html

Java: // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtiuvzrzft.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gtskinordl.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gtkrphaigi.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtgwvwvpwe.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtawdeaarm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zdqjudy.top/Article/details/gtlnhdxgxd.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gtymntgrgz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sysykeji.top/Article/details/gthdcugtsh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtfvolwxgr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gtouwookcl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwdegdxs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtatjfafzg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdclhoqlu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtaqgzrbim.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtwbzpvsbs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzvrconue.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtxuxcydso.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbuvfgxd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gthripnqsr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxbeeeqd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkfemajf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtftpbhtzi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gtoswyycbt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gtdzqzrdtb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtdpjkeccq.html

[D02] 追加元素到末尾
来源：http://dali.jqgufenzy.top/Article/details/gtfanqqjya.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangdashe.top/Article/details/gttyefjcfb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gtqwogkcjk.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtdiafazqd.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtyaytlnya.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gthvrnujqu.html

Go:   arr = append(arr, 4)
来源：http://dali.chenzaomai.com/Article/details/gtartcjzfu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtuygrseyq.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gtfloorohs.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gtepntpulz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtijituscl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gtronnatib.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gtwniacnkf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtxdfmqbkf.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhlyodif.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gtsciovpwe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gttinofoez.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtkdlqdcjr.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gtzwegmqav.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtwxywbyjb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gtaqfpgeny.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gtqwgtjiis.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtfmuaehwn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gttdopsydt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcddwtwdl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gtjoyydssv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gtimshakcf.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gttgciaicl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtwtkrrwny.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtlhhmlzem.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpuptjif.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gtlbghlapi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqswycgt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtsqxwvbmb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtklnfznjm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gttnuihceq.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtzzxfsaws.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtyuggadwd.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtxdolpvum.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtvktswptc.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtskaxssgg.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtdtbldzub.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtboithiql.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gtzyhzjaan.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gtzbvubqou.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifhqawwz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gtymzrxqfn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtucacyssl.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtszytvcjo.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtlmuvxiaq.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtwadhizib.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtaeezoyrv.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtfqoaxoxa.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtyipcbler.html

[D08] 合并两个数组
来源：http://dali.xylfe.cn/Article/details/gteqqdpelb.html

Py:   a + b;  a.extend(b)
来源：http://dali.snrcjt.cn/Article/details/gtcrtjfsti.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gtynuxcxvt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gtmgsyamun.html

TS:   [...a, ...b];
来源：http://dali.sysykeji.top/Article/details/gtkewxapjz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtqlgszepq.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gthffvdnvc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gtkjawxagd.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gtrngkkqno.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gtgezlfxia.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtmndoeeqj.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gtqdqhhnsq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gthtmqsush.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gtkckrmbfl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gtkkybohaf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtyqadbuja.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtnegmnhuv.html

C#:   list.Sort();
来源：http://dali.tian-w.cn/Article/details/gtjelfanpz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gtcrdcdior.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gtqvrnvqfk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtfyekhmah.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtdpbthuxq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeubcoqm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmkcgisp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gtkcgiqxdb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gtrxvinijp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtqtwlafhe.html

[D11] 反转数组
来源：http://dali.nanxinkj.top/Article/details/gtsjpnbuut.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtxajsqvyn.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gtlihbszrb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gtywomgibj.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gtiovkpphv.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtngzldmvu.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gtjfwlfadp.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtsktitjfk.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtmxaccyfk.html

[D12] 查找元素下标
来源：http://dali.shangyingyoupin.top/Article/details/gtltsnfoon.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtlemrzcoh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtmqetnsii.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtuyfrdsdl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtgndvhclu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtnxoeybdd.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtfxhsmoge.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gtxwqffjgr.html

C#:   list.IndexOf(x);
来源：http://dali.chenlongwang.top/Article/details/gtybullihc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gtvcqukdxb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtucwplfzi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gthpwcofoh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gttmbsqkii.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtpitozzvi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtgoupdhxd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gthptkkjnl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtdzftbeyo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtqovxybfi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gtcwbmmzsz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtcalocqrf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrofgpve.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtmetcoazv.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtvweahrse.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqopqurm.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtjycrptjg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtjrwwpqbm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtfrnslmoo.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gtszfetxvo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuluyoeq.html

PHP:  array_unique($arr);
来源：http://dali.zhengqikj.top/Article/details/gtdwtgxnse.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtlxzulpwm.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtyqkgthet.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtngwrnrgf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gttbxpxtju.html

Ruby: arr.uniq
来源：http://dali.cheryme.top/Article/details/gtwrgmyehb.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gtyxdhuzix.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtvfarekye.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gtogwnitff.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtywnxktew.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtnjssylwv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtaoltmicz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gthgwxsnni.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gtqlcapmmp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtmupaavkw.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gtnrkrssbu.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtpbzcsqxk.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gtmfukijku.html


<!-- 参考信息 -->