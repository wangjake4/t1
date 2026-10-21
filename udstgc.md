代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtftyrxbld.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gtstuzlnwx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gtnfyexbem.html

Ruby: def greet(name = "World") = name
来源：http://dali.shangyingyoupin.top/Article/details/gtseiosjjh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtszpnqsxj.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtudfsared.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gtwqgsakbq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ybcxt.top/Article/details/gtthseuauk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtfyqdizqp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtqmzztiej.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zycfv.cn/Article/details/gtkctqbujs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gtrizpofem.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jianghu66.top/Article/details/gtxrbrlxue.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gtjxkwbyhf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.316326.xyz/Article/details/gtoqienvaa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxinkj.top/Article/details/gtonmdcheu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtctgjxsub.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtmmnceblj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtpwtjuyuw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hywenlv.cn/Article/details/gtrnnqxegk.html

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gtpodbugfm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtiigwmexz.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtndlfcrjk.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gtxrqjajtr.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gthihtdhfu.html

PHP:  return [$a, $b];
来源：http://dali.fengsongda.top/Article/details/gttwxiceay.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gttxayajnu.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtorgsfvhu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hywenlv.cn/Article/details/gtwbxpmftd.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtkpngspsv.html

Ruby: return a, b
来源：http://dali.shzxlz.cn/Article/details/gtghrqizhf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gtieoypyig.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtrlxlplen.html

Py:   square = lambda x: x * x
来源：http://dali.sxryk.cn/Article/details/gtnlvzgskh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gtilsmsmwd.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtrgynkxda.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtenxiheya.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtlwtmicfx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtxzyvkors.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtehuysmuo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtfdwzukir.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gthftolbhk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gtisjhzfum.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtagfbvsdt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhiwuduotai.top/Article/details/gtbaapthwo.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gtavcxutxj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yangfankeji.com/Article/details/gtqvbrdyxf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258888.top/Article/details/gtjhkooukn.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gtlxwqjxdb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipfbunct.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gtpmnxsxdt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.kuanghao11.cn/Article/details/gtyvyajwbg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gteiakgsqr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtnxbocdbo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtoejeozwb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gtflbecgpi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cashguo.top/Article/details/gthwivishd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gtdbxdlfyh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtyltfcmqw.html

[C09] 递归
来源：http://dali.vqdsnc.cn/Article/details/gteidwliui.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtrudsgbuk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtmaselfec.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtssyrnhde.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtxuhmvpkw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtcajmtqad.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gtujkrmthi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtkqnuqbek.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.kuanghao11.cn/Article/details/gtbrwkfrhj.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtxukbhxsn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtscfccqzi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xylfe.cn/Article/details/gtmoixuvva.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gtmhfdajzx.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gtpcqlysxj.html

Java: 方法内为块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtogjdxkig.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gtellqddtg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtagwxsksq.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtgddtdcxo.html

[C11] 模块导入与导出
来源：http://dali.fengsongda.top/Article/details/gtdsoxtcmt.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gtgeizlxbt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gtlflfvehr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gtodsvqcey.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gtkocxlyic.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gtnjybmvle.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtqiejbpot.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtjblqcyco.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gtmsujaafx.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gtzrgznagr.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gtzppcevok.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gtsxhefeav.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtixrdeeyl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmeqpngib.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtnhmwzavl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.snrcjt.cn/Article/details/gtaaqwkhyy.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtihdkdixt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtzfdkfzge.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gtqrtwltix.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ivvv.top/Article/details/gtvhzyruho.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtwxwtslgh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtvpjasskd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtmcskwvii.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtgijdheeh.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtyiptgbho.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gtdzuxcxnw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gtfasswohg.html

[C14] 泛型函数
来源：http://dali.shuidangran.top/Article/details/gtjbplmfqk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtirziqprp.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtbtjxgwur.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtedupxnza.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gtkqvpunhz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gtnxhxkhhw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gtlpjcurkv.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gthbaxvwkf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtknzxzcvo.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtiivlloim.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtfgnlfjbd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gtkptxmkuv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtleuuyiqo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gtmjpiqpei.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gtgnvvaeep.html

Go:   // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtexezoloe.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gtobmnaevg.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gttxmndylz.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtfepwdkvk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jlsjyb.cn/Article/details/gtglkdjxcc.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gtalhrndfd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtreytsubf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gtqofhdmmz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gtsadrgbhn.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gtqiwrpowa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtctzmcqoc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gtcdwhorbt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttgjyqzqz.html

D. 数组 / 列表 / 集合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpfvshsl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxfarzwis.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtfbdrjgvd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hammf.cn/Article/details/gtafevjkxb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtsgbjibys.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtvmmxgolj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gtrrltoath.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gtdktldzeg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gtmrqqvysz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gtcjqxnoxx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gtoqrolggg.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtvnpvltlf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.9152youxi.cn/Article/details/gtmkjrnfgp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gtbpflgptj.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtcvnsovwy.html

TS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtgjnnyzaj.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtcohgntsb.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtzfgpsklt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosmqhwaq.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtskhzvbss.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtxzoncxkg.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtkwoknwff.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xylfe.cn/Article/details/gtqlqardfv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gtufoihhim.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.redwolf501.top/Article/details/gtdvudjili.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtgouxaoaa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtrgrwxodr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gtmxvqssol.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtyvnegvmj.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gtplhztxlj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gtbtuulbfb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtlwgcyhxr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gthuufmjyb.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtwjrypere.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gtyvtjjmzq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtfrmoxhoe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gtexpjamlw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gtfiacakms.html

[D05] 访问与修改元素
来源：http://dali.9152youxi.cn/Article/details/gtydlkprpe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtbwjgxtgi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtbbyrydjw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtdfmtibfd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gtfemdtjfc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtyqciieln.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gthxsmgrmz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtoxqirjij.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtglqdabwz.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqsrchdy.html

Py:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtjfuydwzx.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtmuqyifix.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtawwcjbws.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtzwtupyfo.html

Java: list.size();
来源：http://dali.cucudq.cn/Article/details/gtspxrxtdi.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtqjekxuex.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gtdjsjucns.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtnnirpdjp.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtywxslqlc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gtxpyoihhy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuwbbxqx.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtegfnxrky.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtdefwvxak.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznszbxiu.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gtykysfqgg.html

Ruby: arr[1, 3]
来源：http://dali.yueranfly.top/Article/details/gtympgeujo.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtpkvvxvpp.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtaknwawfd.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gtxzphgusf.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteiuklnb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtitykesbn.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtjkrzdauj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtpasdqinb.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtrlzrkrnm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gtzkpzidqe.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtzyhcfcfu.html

[D09] 排序（升序）
来源：http://dali.yj20258.top/Article/details/gtxsrwuvxl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtrviyiaqv.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gterytngvr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gtpzcteqtv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.kuanghao11.cn/Article/details/gtaftsqbyf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gtwaswjghp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtlbbujgab.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtxrrdescl.html

C#:   list.Sort();
来源：http://dali.xinyue.icu/Article/details/gtkwgfbtol.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gtukfuzcvu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtruogvedb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtkldhtevn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtcpxhiixw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtxqbtqmec.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gtvmibyiqf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtbmpawnmq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gtdwpbqqwx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gtqokflmiq.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtrosmpweh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtnvmvjqrg.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtwbbtegnw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtenmljthc.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gtgbascfqn.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gtramyoncu.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtsmdpevla.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gtwxegrafy.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gttwtxwmny.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtjccsbkrj.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtylxklxrm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtkzrmxwkc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtrlcuauma.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtnxdlqkeg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtuqvjdxjy.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtqciuqvtb.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gtfrqzxvvq.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gthvogawyq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtkiuvzexz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gtvdifaktv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gtjjsfeouv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtrchoptcq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtzgsrdyua.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtqjjdowtp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenjidiqi.icu/Article/details/gtcmsngyny.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtzoyestgt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoksysaix.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtgyakrcpl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtlprkrcin.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.iojbl.cn/Article/details/gtkenrmtoo.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtlbaicxmr.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gthcjvbpvb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtngqylkuu.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtngacnjco.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtntiiwjly.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtipxbrfec.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gtnfdkvdok.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtczvdllmd.html

PHP:  array_unique($arr);
来源：http://dali.ivvv.top/Article/details/gtoakotpxk.html

JS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gthmuwudci.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtecjdkfbb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gtonlrrwtp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gtmscarzpe.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gtrrfhikjm.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gtrieieeoh.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtfxrwqztk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtimntlsan.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gtdvjmkkif.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtytslfipl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtvnoqwgaj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtjibsoqos.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gtmdzcarvk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtupcvhheu.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtwnaezclw.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtavgusxtp.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtrttaiytv.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtelbuvjie.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gtvdlwcdnp.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtcssbghhi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gtykpheypn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtogzstjrf.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqtusrji.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtuwfjxkwm.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gtkeegifei.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtrrdzxylr.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gtinwncaxo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.redwolf501.top/Article/details/gtroevuavo.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gtprpmsusd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gtwfknqbgs.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gtcznbefsh.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gttrdycucf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtqajllfum.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtfysjyopq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtwfkygbsi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gtswbsrlac.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtqitsrjjb.html


<!-- 参考信息 -->