代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtsvmkseda.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtjnilibfq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtnrwqekbc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtglnlzjlz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnufhlpvs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gtyzvjslsa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258.top/Article/details/gteirehxbq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtrmiozelf.html

[C02] 默认参数
来源：http://dali.hnqzz.top/Article/details/gtvndktrht.html

Py:   def greet(name="World"): return name
来源：http://dali.birdmap.top/Article/details/gtenhgmwdo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.andypj.xyz/Article/details/gttihxsjjm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtshbrqwfq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtionslltq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj202588.top/Article/details/gtuoghcwzg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gthwfibnre.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gtxskxxheu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhtbehzi.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gtuingkbfx.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gtwwfxrxgi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangdashe.top/Article/details/gthbklxbii.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtelfgumss.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqbxmujop.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnockypos.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gtxwlqnxnw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gtfpmxhiur.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gtazaiuyfp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.kuanghao11.cn/Article/details/gteijzpnox.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gtnnvqgsiu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gtoxzbgmfg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtlucrudob.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtqzmkxpch.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ybcxt.top/Article/details/gtforvoozo.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gtkkdugwkq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtadlhsiay.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtrogtqvkr.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gtwbxokmks.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtxwzbcwlj.html

PHP:  return [$a, $b];
来源：http://dali.yuxming.cn/Article/details/gtvprdxciq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtjnxcthzi.html

TS:   return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtkhchmqlh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gtrpzuizho.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gttuoxcpqn.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gtznswmerh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gtiiectwwt.html

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gtzmuonhbo.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtbosnnday.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcclirifb.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtdwurzwgm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtnimraitt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtjltpnoib.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cheryme.top/Article/details/gtigupwdil.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sysykeji.top/Article/details/gteodveffj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtrqatbhwk.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gtvuyllygv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gtqlbyzuud.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gtnyntcuoc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gtoukfmdfr.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtsgyytmiw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdejaftj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtjenxccwy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gtsrqgbxln.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtpgohphfn.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtkvqyhcrm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgfzy.top/Article/details/gtovhprqih.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.316326.xyz/Article/details/gtqnkbbbwj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gturxnripe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtlhwkceei.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtpfktpcnp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtpttfwpdl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gtzbpgzrca.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtedywasmi.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyqmxsur.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtbsuwxjvr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtbyyymbwv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtzshoyncy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gtyrylubqi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtubvprooh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gtthjkeycj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtefdhmrvy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtrfmjnenh.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gtrnynveao.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gtyosjmiwu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtbcbabdtc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yueranfly.top/Article/details/gtomfmmsqa.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtrktxplga.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gtdreufadu.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtrjhkcfay.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtndqtbfxk.html

C#:   块级作用域
来源：http://dali.gzhubu.top/Article/details/gtbjkbwsmc.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gtxycblvta.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gtqzzfvovy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gteiqmsawu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtsbfldthv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhixingplan.top/Article/details/gtfjzigzry.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gtxegnynst.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gtqgatafdz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gtsoifxqoo.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtborinkot.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtctckcjwj.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gtmfedhero.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gtmdugzxtz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtmzaupagz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtriwgvfiw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtdbitejws.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.snrcjt.cn/Article/details/gtwtvnknmg.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gtzmiolxut.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtwbtixgxe.html

[C13] 类型声明 / 类型注解
来源：http://dali.ppjwa.cn/Article/details/gtuvpxbvfu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gzhubu.top/Article/details/gthcpgtcpc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtdwabcvnc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gtjdbdezlc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtjctnjknt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtkcmbllir.html

Go:   func add(a, b int) int
来源：http://dali.hfpthk.cn/Article/details/gtxieopoya.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xziqi.cn/Article/details/gtdikntxsk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtvgdlptcp.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gttwpwrxxi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gtgrmqqlok.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gttisruiog.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtbzfhpmwq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnwyhdsil.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.smart0.xyz/Article/details/gtexleteha.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gtriakfkxb.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtfznwscuj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gttcmcggeh.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtjhykqtzf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gtlcawuiun.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtkwsgfffj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtnnbzlrpp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gtehfwkzql.html

Java: // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtlsbtnepo.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtscqphyvu.html

Ruby: a, b = pair
来源：http://dali.zdqjudy.top/Article/details/gtcbhhdbtn.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtoopcjvis.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtolnyvwjp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gtoiqazgnp.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtwkzjpdzb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gtyyksyldv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gtvmszryym.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gtkjismdwn.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtpuffwdvz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtwkmaymnl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gtpjxzwjtt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjdtrdccd.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gthdvqwjec.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gteozbqazv.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gthvckugbp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yanxiufei.cn/Article/details/gtuwmwpbyg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtobdcxtvq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtsmnelidc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jlsjyb.cn/Article/details/gtupajcoqh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtdyngzfpz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gthjzunzkm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gtpbmxyguo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gtkhaxvsgl.html

[D02] 追加元素到末尾
来源：http://dali.xinyue.icu/Article/details/gtbaikywxj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gtdcgmxnqa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtiqljxoep.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtjscflzne.html

TS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtsuelpvzx.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtihqijfxv.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtfekbxvbi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ehwqpu.com/Article/details/gtwrxrvsjx.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtghbxzvwu.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gtqfrvouwj.html

Py:   arr.insert(0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtrjndmsad.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gtxgvcmlmq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gtlbzpnlvo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtksltwwle.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtbhpdiqzh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtfhpehbyv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtdxdbhhvp.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtuskoowfu.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtxjfgpqvn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gtttfuiiod.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gtpodprdmy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gtcpskserg.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gthddndteu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gtoknlhuie.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gtphxwscgw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shuidangran.top/Article/details/gtsygedxro.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtryglvudu.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gthhpemnwk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtyrekkfvs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtewxenzgq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtzdcpaikv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gtwkwpebss.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gtugixyfkw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtfdghjnml.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtlyegtdyz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtrzlymofr.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtoawwkqkn.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtlsehcbhw.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtdqobrncv.html

JS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtrhafmguu.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtvyvtgvhx.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtruqmkppo.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtfgrzdeqv.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdhdzkqo.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnikiwcr.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigfzy.top/Article/details/gtgqhhkysq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gtnblenxha.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtezdhqdog.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtjuvgpkdv.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gthzeiozur.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtwpzhyeje.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gtxbtxrara.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gtingbjntl.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtksnlgetv.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gtjxdaffqi.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gtaxbviiiw.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gtjlywuwhj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gtccgjmien.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gtxjxiycso.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigfzy.top/Article/details/gthdeqtxwj.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gteswvodlm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gtvdkralej.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtsdemgect.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcysbvqjx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtkhdwmwki.html

PHP:  sort($arr);
来源：http://dali.zycfv.cn/Article/details/gthxczueon.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtdbsigvur.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnqzz.top/Article/details/gtzoifjgom.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrikdqep.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtydncxknt.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtktvperhb.html

C#:   list.Sort();
来源：http://dali.yueranfly.top/Article/details/gtyijtislm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gtmasczxnn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtupuapegy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtyszmjnkp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtohnymskq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtprjqgfvy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gtospucfvs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtzjvvxizn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfqqpiro.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gtniyprjxt.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gtvrddmmih.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyblffuxm.html

PHP:  array_reverse($arr);
来源：http://dali.9152youxi.cn/Article/details/gtqlgyqaxw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gtyeifmvqv.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gtxvfmoeiz.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gtdugecoau.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gtqvzpzcgy.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gtpqusmzrs.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtcspxsfyh.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtfluequyl.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtwangalcp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtfkdbdhuu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtnizbqzjn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtzbyptajr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtntkfnyuq.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtuvjzbddj.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtwzgklwrv.html

C#:   list.IndexOf(x);
来源：http://dali.tian-w.cn/Article/details/gtlqihthby.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gtdthfofkk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gtedakonmd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gturbnaold.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtsjnvpeif.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtjudusqfb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gtwbqremof.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gtwyaifhge.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtvetgljne.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeyvkxni.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gttoicqbyy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtxxguclkl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtyhotcfbp.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapagbvqk.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtqpocnezh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtdxarpqky.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gttwhzlusn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtlvoqvhcq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gtgckqjvyb.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gtiegunbpp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtwrutuchc.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gtjdjstkhh.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtevgqowem.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtwgauuurs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gtgwtfjvzt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gtayzwtxgk.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gtozmjugnw.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gtphnxoznr.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtyrkxtumj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgywdfpx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtrlkycavo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtumzuayij.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtywoireye.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gtxukivsai.html

Go:   // 手写循环累加
来源：http://dali.mhx1999.top/Article/details/gttarrdiaj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gtmnxyvepf.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gtjzzushcp.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtinmsxjww.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtldsstgor.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gtfyaaqswq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigufen.top/Article/details/gtsggukhwr.html

TS:   Math.max(...arr);
来源：http://dali.zhengqikj.top/Article/details/gtnhwdohjd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gtaumrsisb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtnskcyqkn.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gtmbsusubq.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gthqwswewr.html

[D18] 扁平化嵌套数组
来源：http://dali.0kj1m.cn/Article/details/gtfrgdrwlo.html


<!-- 参考信息 -->