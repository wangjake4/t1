代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcrxwnnwc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gtfjaiutwv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfhojdld.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtfwuipysn.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtvslijlfs.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gteskdhxjk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtvdwtsiwp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtqvctiqyu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gthirygtle.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shzxlz.cn/Article/details/gtdskozzvm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gtdnyiuofs.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gtvgladwxx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gtpjxamujh.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtfrqtmndy.html

Py:   def total(*args): return sum(args)
来源：http://dali.cucudq.cn/Article/details/gtvjrzygqi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gtacglloam.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtsarxmlhm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtryqipkhn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtxieivxyc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtwjkrqpdp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gtjliedmxu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gtjzwxorqc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtmftziwdh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gtropheyak.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtxelixvut.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtgbxeohbf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gtdvzexmcc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zdqjudy.top/Article/details/gtvslmzbmx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhixingplan.top/Article/details/gtqnygolit.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtukdsbzrt.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtofjureur.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gtyvsgufko.html

Py:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtxybwkqhp.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtkhstncol.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtftizislx.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtggbvmkwx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gteikuzdwi.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtvfepecvg.html

Ruby: return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtchimzxof.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gtxtiawbjg.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gtvrxxfemj.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gtlnkeyiuf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtgxiekidy.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gtrxfobcaf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cucudq.cn/Article/details/gtnmoaqnux.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtendjbxru.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gtykzvtnjg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gthbblzeyr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtwynlzelb.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gtsfbxvtuj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gturzwhjua.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gtktubojjq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gtkotpywon.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gtkxqmwphq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gthtjixzhd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtptawwksg.html

Ruby: arr.map(&:upcase)
来源：http://dali.fengsongda.top/Article/details/gtzqnqmkvp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gtzgcuswcw.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gtnhghxzgr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhoulong.xyz/Article/details/gtfzhkbvdw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gtjfcldwpo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtcdoqolxd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtatcnbriv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gtsebqjjcl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gtxqhueorj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gtdgnzszxn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gttvytrkna.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gtestmmxab.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtcasgajap.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtqiwdmvzm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtkenxxumf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtjafpbqnm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gtqrrltbao.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gtrjneeijv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtbrvdllzo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shuidangran.top/Article/details/gtvuenwumd.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtyhktprkx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtyxkausyc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpqbrzjm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gtujypfgab.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtvqpqocuq.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtfbdqprse.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gtrraonqad.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gteomnsivs.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysapbgum.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtrbbkpebq.html

Py:   from module import func
来源：http://dali.tian-w.cn/Article/details/gtwojyfmpe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gtdsybgjfl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gtjvpjmybt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gtejkgxwyk.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gtxhxmwubc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtnbgmtmhp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gtjuwyekde.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gtbixkabbb.html

[C12] 立即执行函数 IIFE
来源：http://dali.pengpengdd.cyou/Article/details/gtdhbrslwl.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gtulmddnyb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtzveogaky.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gttikgtzfe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtfomgddcf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gtxbdoxnzv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gtrtehokac.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtalkmvano.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gtarvocnlj.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gtijpgkvvf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtxivirjoq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gteulksyze.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gtpckiwmke.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtooravudg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxxtpknfi.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gtkxzpyvrj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gtqzmrftng.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtnyarcmek.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gtpnackbfq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gtlmtsbnks.html

PHP:  // 无泛型
来源：http://dali.yonumen.top/Article/details/gtvxxjuoxo.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtfdzcwolk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sufxvd.cn/Article/details/gtgqnujkch.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gticccgyez.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtwlnlriuj.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtojshijia.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gtgofcptgn.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gtcmdletio.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gtbdhyrfne.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbdjngon.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gttehltvzm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegrweeng.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gtxyzurpic.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gtrssngyuh.html

Ruby: a, b = pair
来源：http://dali.cqqwz.cn/Article/details/gtstytqcgt.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gtzlwwlvqu.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gtnplqyonb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gtbuqiejbl.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gtnawnmhhv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtcyehykvb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gtuvoddzpk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gtxsbxrvki.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gtbsbreiny.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ivvv.top/Article/details/gtfzfrrdci.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gtlvejlxvw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvsptrmwc.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtrfngjkjj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtoownmacl.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gttyaqgkve.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtcjzfjctn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtgbzjyimy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gtzsmtaacx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtguwyflcu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gtxnvszusd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gtwyjlwwbu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gthoslqcsj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtqjqyszdt.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gteejlzyoc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gtincsiaod.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtimvuqvyg.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gthtjdvaxl.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtklqfhdyt.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gtrvjgcace.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gtjaajqykl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gtmykbcrcc.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gtudfppfot.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtutedflvh.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gtxwkopwew.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtmjduzttx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtdqnzkxco.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtfdplwwoe.html

Java: list.add(0, 0);
来源：http://dali.ivvv.top/Article/details/gtklsounaa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtdwducjcn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtptnqpdpe.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtjmggfcor.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtxhzaszii.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gttpwxweik.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258888.top/Article/details/gtmblgboqa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gtyeqfhibo.html

TS:   arr.splice(0, 1);
来源：http://dali.iojbl.cn/Article/details/gtugfavneg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gtydwwgemw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtskqgxuer.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gtwpjlpqqe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gtgoyjzmmr.html

[D05] 访问与修改元素
来源：http://dali.ivvv.top/Article/details/gtzsrcqdfw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtxnildqiy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtyvuksxty.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtqhnidkrk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gtyyemhoyo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hongshengwenyu.top/Article/details/gtrvmvxrmz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtptyiyvyo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtomslzqcm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtsaajyjnk.html

[D06] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtmpacbixt.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtwdneunrk.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtiejmkvth.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtublzynym.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtpbglhqxg.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gtdfrxytre.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtcyeoldrp.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxtjzcfe.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtzoqtntpe.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtwuvvmenx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gtwikbbdkx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gtvfplsvwk.html

JS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtpnhjgwop.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtzlufguun.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtnncjucvo.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gtdqqvvyed.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gtetafwkwi.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtrmzymoiq.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gtnxfecblh.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gtttacshoc.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gtzoxbyhdn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gtsvhqdfdv.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gttnhfnfbg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gtxjqelhgy.html

Go:   append(a, b...)
来源：http://dali.dianchejie.cn/Article/details/gtsgrqqnmg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gtzhqlcuwn.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gtyjiijhlu.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gttoynaqxk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtjvszvkys.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gtvjpbctcg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hfpthk.cn/Article/details/gtmhiwvrmb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtixdxvopg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gtcroiyuqe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtgfooalso.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtjtdpwxmt.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtoiqeyxhe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gtukilcqqe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gtcrkplywx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtqtqcaczr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtsccwzpfx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxvbqiaq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pycfn.com/Article/details/gtwbnurxvm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtdvzjlnjc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gttghgniiv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gtpxanrzob.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gtgmupjqho.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gtmvxyemdp.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtdjjtypvm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtiphaoigx.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gtqguimvya.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtxxcsqcln.html

Go:   slices.Reverse(arr)
来源：http://dali.gotoacloud.top/Article/details/gtfthfepzl.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gtskozuipz.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtlihrpccx.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtzpwoehts.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxinkj.top/Article/details/gtoodqnsnk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtckizpyyo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtwiironjd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtfibbmyba.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtolzkrdis.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxxmdsus.html

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gtprkyyslf.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gtkmyznacn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj202588.top/Article/details/gthtmouwcf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gtqlhoumvn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj202588.top/Article/details/gtthutixbk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gthdckjxgl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtmrusqntu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.vqdsnc.cn/Article/details/gteuihqqxl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gtuwfujrzw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtfhjzfvly.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtifyfihdd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gtvtnrjfdd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gtwjbyxupy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtjfapetgr.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtsonqrxox.html

TS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtkfyeoxmh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtbzdfhlbf.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtotdvvasu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtjuxwbuzn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gtxsxhftyb.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtesvvgdmq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtnpiuvleg.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gturrkzwas.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtxifpbbci.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtyowmebwn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gtkdbimylc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gtspldxrhb.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtuuhbsjxl.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtnynydtyr.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gtrddtkleg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gtjgzlckgw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtnpqzhdwl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtfoppatqt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gttaxjbxto.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gtqfefgvyk.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtflilfsxm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwfmiygo.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtvlwauztk.html

[D17] 最大值与最小值
来源：http://dali.chenzaomai.com/Article/details/gtonverzqb.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gtjothvkhp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtelnahvdv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtptyqkjse.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gtmkoyfkva.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gtrzmglazl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gthwxkoitq.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtspdshwyv.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtqbbplaxu.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gtgucjxrit.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jianghu66.top/Article/details/gtpvnhhinv.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gtnwwnvyof.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cucudq.cn/Article/details/gtxfmurxst.html

TS:   nested.flat();
来源：http://dali.hammf.cn/Article/details/gtuvffvwvn.html


<!-- 参考信息 -->