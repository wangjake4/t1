代发 wailian999

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthacrddbt.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gtmijqfsfn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcszbtwvu.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtcwxdydrp.html

Py:   def add(a, b): return a + b
来源：http://dali.zhixingplan.top/Article/details/gtlvcnahkw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtxukrfauq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtwgmreffj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtatmfhwqx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtubmzhikm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gtvfxjziyu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gtqwsygqbk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtsjnzmiup.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gtwwhbcjbt.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gtnzradpai.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gtdzpmjmil.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtyeyihuoo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtqplfegvo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gtxkokenxo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xziqi.cn/Article/details/gtqhgwfivj.html

Ruby: def greet(name = "World") = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiuyztoy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.redwolf501.top/Article/details/gtlqnbcjcv.html

[C03] 可变参数
来源：http://dali.jqgfzy.top/Article/details/gtbykoqvox.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gtaeupxowv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtknldqzzt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtbqqmymwl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtqifhoyxb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.iojbl.cn/Article/details/gtckgmskvv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.iojbl.cn/Article/details/gtqouhetig.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gtndqrlrbb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.svipenyu.cn/Article/details/gtcocryfok.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyuaefsb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gtjjtklnlc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtwukuiqja.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtzyylvgan.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtmzwrxtyn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ydzc1.top/Article/details/gtdjhryonp.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtifijiqgy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtvhqhzodq.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtlcmfsnpd.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gtqzllrekp.html

Py:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtfoibvlxq.html

PHP:  return [$a, $b];
来源：http://dali.yongpay.top/Article/details/gtyweoxkqs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtfxmdyjhz.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gtlcgffmxg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxbziawm.html

Go:   return a, b
来源：http://dali.andypj.xyz/Article/details/gtwawchuej.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gtnncuyyzj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gtxnplgcmx.html

[C06] 匿名函数 / lambda
来源：http://dali.cdnleiting.top/Article/details/gtwmmhccdv.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gtdtirnhvw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gtvpguchlf.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtnkvvtkyk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtwxsjqjqk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtvflnhqbw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gzhubu.top/Article/details/gthavhejve.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gtsgznrgke.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtiygzdezh.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gtkhsbblqs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gtgnaltujr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtmivcfonk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gtgynvgwoe.html

TS:   arr.map(String)
来源：http://dali.smart0.xyz/Article/details/gtacxntgxc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gttfxjnpyg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gtziqjpiit.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gttqvlwlub.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtnrotldyz.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gtuetilsre.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gthbgtbxpq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtvxtznrcw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtykeoeavg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtkhnsvlht.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sufxvd.cn/Article/details/gtvcigyrzc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtdplkixeh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gtbgufotcw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtqqqnztpw.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtebnurgfw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkglulcc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtgbgjmgfz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtsxgkwndt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnnzaejf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtldbvcdua.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pycfn.com/Article/details/gtkrslahke.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtiyascqnp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gttdkwcbqd.html

[C10] 变量作用域
来源：http://dali.ybcxt.top/Article/details/gtxxstfbxq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gtusnpaqka.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gtvcmeufqi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gtnomdilpa.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gtmuhuiodt.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtrzfpvrkj.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtsunhlskq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtwxdgojri.html

C#:   块级作用域
来源：http://dali.yuxming.cn/Article/details/gtbsgpeqen.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gtwyvantep.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gtrgjxjpzp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gtojfxlwyt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtqvatkifj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gtiibnrwvv.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtexbvebrp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtbxookjyv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtedczxceh.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gtekcfwtvg.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gtevgsphjj.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gtqyrovpzn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shangyingyoupin.top/Article/details/gtxkxyatig.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtbveaswdb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gteuoykndw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dianchejie.cn/Article/details/gtjnwqqpvi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gtwnzjymzz.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtawxrwpll.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrkojfku.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gtsydpqumi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtoodwvokg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtlchtbyqt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gtklzxnxjp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtkmruisxu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtamztugql.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gtznoqaiqm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhxiukvo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gtxdqpcvqz.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gtxqufhaau.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gtqlqjuyhp.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtqnvgfgjg.html

JS:   // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtscoszthg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtghwciaqv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gtzspsmcuf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gtwsrhkewh.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtpdjeqads.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gtfbsyctwa.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gtyvjkwcmp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gtouvciqrg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gtmwzpsowi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gteznlmrih.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gtvfqbjquc.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxvryuaa.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gtdmqwvfom.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gtfbvveysi.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtbsqbmecs.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtgkyclzpd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gtupombvah.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gtfrwbijcz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gzhubu.top/Article/details/gtxxgwjwkt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtlvkshvjk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtvpjpyieo.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gtulthbihu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gthrtuyuuc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gtpbdhkxar.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdtoaigdk.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gtzsxuclai.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtsplmvloh.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtzndffumz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gtoezqxrpu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gtwdmmhnun.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gtemejgpdn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwawmrdf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtlxdwfxqr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkytfktv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtnkmolsdd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gtygewkhtx.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtcinqwqct.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtckqdgsxt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuanzx.com/Article/details/gtopcofwab.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtixeqazkx.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtddftsgbp.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtdyayhcll.html

Go:   arr = append(arr, 4)
来源：http://dali.nwbrower.top/Article/details/gtoorbyszj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gtstctivrb.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtqpdlsjhf.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gtttdfstmd.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtlkyzhbop.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gtomirxwfj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxuanxn.top/Article/details/gtrwqjqmvu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gthjmlodkz.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gtkxcryqoa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gtlzufravo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gttlrpbwoo.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtrgdyzzkd.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gtkbzoimni.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteokpiizf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gthfuefuqb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gttncdfyzy.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gtlxpcrege.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gtffnyspco.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtmgyvbfqx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtkfbyynhf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gtzydaerzf.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gtruggeuhp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtmotgxxdz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtpikuvojx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtbpvagrcj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtvtfqmnuf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtkaytudpb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtytnrzvsm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtqutjseqt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtijnsdafd.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtweibbbrc.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtvfvnrcxt.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtemhmpcte.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtfdgrceei.html

TS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtsfzucelp.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gtbkxbzows.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtqgfrlecg.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtlkjbpkqv.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gtbxfazlrk.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gtasgyopjn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gttmqczctn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtpwuvsfcm.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtiqtzdbiz.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtqyjsyyip.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtzqkoweae.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gtixnvbfeg.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gthnmmuuwo.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtgutzbksy.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gtladrfiep.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtxlienoqb.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gtcfoxoyiy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtwwoeqorb.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gtqwsnaqgx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtxsrtzmtw.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gtbbzhrddh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gtgwviezpu.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtzeyggsod.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gtphkcabgc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtudwnzhtx.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtshiqalpw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gtfmrfwplc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj202588.top/Article/details/gtdxsmgjor.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gtgvuztkdo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtqttvugbt.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtomohbbqz.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gtwlriysml.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gtgmwaebwo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gtcoqdilmh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtemrlhway.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtyojwwvsw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtqxohlprl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuanzhike.top/Article/details/gtnbnjvawa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gtzbwhujff.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gtkggckxeb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gtskllwxlj.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gtialevhgd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gtkbmztlst.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtasgmesrr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gtaowwppsr.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gtgckdcqwm.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtogyhscrp.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtvowyubrj.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gttmeetgfu.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gtpovuoncc.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtabvojavr.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtqucnvalz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtstzrlhtm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtfxomrdvf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtoliozsyl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqccuavub.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtwexiuvks.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtxkqsmnth.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtfpvnaiwg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtxoradewf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gtficfncki.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gtbiyywlcd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtunjsmcdy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtslrwhpea.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gtbulojndy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtwtbckkvj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtnwpvlqkw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gttecwftwj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gtufsqjjhu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gtirujotla.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtdcnjvlal.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtheufgllb.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtjkhuvagq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gtxfdumafq.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtogoedhbo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtxhyafzlp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gtsovaaxpw.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gthnswaxap.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtxvawjvcs.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtyzbafwfu.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtaffgyhoc.html

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtuiaowfgr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gtavjwebdg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtiiwxhbfg.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfuxvtgc.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gtllmgmhce.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gtilcnxflj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtztgqiqik.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtjumzkwxr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtapesjbeh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtkhbmkkwl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gtvjunodji.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gtpzoiwnoz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gtimfpfdxg.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtxwqfxmyy.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlypusdm.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtzekgeerx.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gtlbqydtic.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtfsomeyyk.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gtykizkeji.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gtgbcjqxfb.html


<!-- 参考信息 -->