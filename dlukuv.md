代发 wailian999

[C02] 默认参数
来源：http://dali.ppjwa.cn/Article/details/gtbzejcwfv.html

Py:   def greet(name="World"): return name
来源：http://dali.chenjidiqi.icu/Article/details/gtuihfllxo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gtebklyain.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtucqfazhg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtkgfwgzrp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gtfhgufyuz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gtnregyiae.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gtorxvwlpv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxinkj.top/Article/details/gtzmukhdre.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtxivemrix.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gtgklejhxi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gtqxoumblj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtpivqxkih.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtecexazww.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtekzyqoro.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtesugxpqz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtbnrbppjn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtkvoconyw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gteiczhocj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gtbcvxptgp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.andypj.xyz/Article/details/gtgqzivpaf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtpsqmnwpx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gtuptrsubv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxerztql.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gtwgzejqkq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtmzeedbye.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gteranmbwn.html

[C05] 返回多个值
来源：http://dali.chenjidiqi.icu/Article/details/gtkxxnzjrb.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gtqtqknxbe.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gtbwvaqbuu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtqlmyyojl.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtpeghblrm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nwbrower.top/Article/details/gtzzcmsfxu.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtxqcawbgb.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtwxypnert.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gtgzynwmmq.html

[C06] 匿名函数 / lambda
来源：http://dali.guowangkeji.top/Article/details/gtsoesbqxx.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gtyqloctzi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.vqdsnc.cn/Article/details/gtsrpmnvrf.html

JS:   const square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtlnkryram.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtjdesjuya.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtrnqoniph.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gtjljpbqaj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtwcalkuey.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gtygrxhqys.html

[C07] 把函数作为参数传入
来源：http://dali.yangfankeji.com/Article/details/gttnvvvois.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhiwuduotai.top/Article/details/gtpxozhrev.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pycfn.com/Article/details/gtbwjbjuym.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gtpfmwsijk.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtfpqqbwij.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtbtvlwsos.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gtkfvcizfm.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gtsdqapidh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gtiyvqaars.html

[C08] 闭包
来源：http://dali.nwbrower.top/Article/details/gtkpsbfnup.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gtxowvyfna.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gtamgjtfjf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtkjooptiu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtijrjvxix.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gtymggmyyc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gtaaybtcoy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gtuftqanka.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gteohfpjkw.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdhatfnn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojkeuxgp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsfbxsalc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtiiyoex.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtonsfocto.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gtzruxfcwi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gtvpyrcyzp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gteggofyvb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtqrrjsrha.html

[C10] 变量作用域
来源：http://dali.ybcxt.top/Article/details/gtvcslqzmn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gthhvpzbsx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gtzcqcleyc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtrlxdibvi.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtunolhkqm.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtrbaopmpi.html

Go:   花括号块级作用域
来源：http://dali.ivvv.top/Article/details/gtplghknbb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxotqrzxa.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gthfehxgzc.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtmmftzrkf.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gtugagfdjd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtqaavxlnk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gtcqqjahnl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkbkykmh.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtgzoytvux.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gtvwhhfwhd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gtngsoxsfn.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gtyorqqpmw.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gtzntswnnf.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gtkzucctlq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gtbtupuhem.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtzgiazygb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtgbwlekgo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gtvcfiuwyn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.316326.xyz/Article/details/gtdxciglza.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gtnqxdqpok.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gtmtaidrqf.html

[C13] 类型声明 / 类型注解
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnyxvfib.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jyoumei.cn/Article/details/gtsabmlfqj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtjrqlpzvk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtjnegeubh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtqseizbvt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtxcxlgvmh.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsqzqfmx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gtgfuuydne.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gtexvftegu.html

[C14] 泛型函数
来源：http://dali.wangdashe.top/Article/details/gttqyuhqtv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuanzx.com/Article/details/gtfwgffsfr.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtumlnsixv.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtrihupdom.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gtscyzasqp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gtuboooqtd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqamghdw.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtnmhkpjza.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gtgogdeynb.html

[C15] 解构 / 展开参数
来源：http://dali.jqgufenzy.top/Article/details/gtudmupsje.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gtytqonpcn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtnkdibwir.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtgzbrzdoo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gtncalofyw.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtbxaqufqz.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtonzknsgk.html

Ruby: a, b = pair
来源：http://dali.meibo888.top/Article/details/gtusqetqzl.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtklebpajk.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gtqjdvhoqv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gtcurzymsf.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gtlxksoloc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gtiusyltps.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gtlokrivne.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.redwolf501.top/Article/details/gtateaecdl.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gtevyigrmx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gtfljzmjhs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gtleneyevk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtaocvprns.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gtbzpboamx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiyqkruk.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtqcqutqyk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gtoqhauvnz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gtviumacho.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gtdobfpvsg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gttrgrlzlq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gtuzaimkgo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gtrbiqspiv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gttleonhqh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtrfpmxirb.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gttrphdvlu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gttciadjre.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtcuiutcpg.html

JS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtrdqdfviw.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtyjtjpetg.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtdcdsiqmy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtuwnamjya.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.redwolf501.top/Article/details/gtaysxnmrm.html

C#:   list.Add(4);
来源：http://dali.shuidangran.top/Article/details/gtddjrlupy.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gtjrlbjzms.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtllcthmkl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.feifeiyinyue.top/Article/details/gthttmnbhk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtqjlhbobl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtsnnlxedx.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtexkvqbmv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtyeicltvw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtbyoykavf.html

C#:   list.Insert(0, 0);
来源：http://dali.birdmap.top/Article/details/gtcrpgmlcs.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtqsgjkras.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gtgrlcncok.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gtiwtnbbta.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gttacuufcm.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gtvkfaobsh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gtmpieflsu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gtmuvbvade.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtevfnhzwb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgngrfcb.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtemqmojnu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gteguldodb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gthankxvfb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtojhhkguk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gtkqwxgxhb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gtlkhubtlu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtcnqupavd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gttdcadpan.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtrigfqsek.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtinulgvmr.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtqkxuwutl.html

PHP:  count($arr);
来源：http://dali.xylfe.cn/Article/details/gtzhontjff.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtvcechtfh.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtqixlwvsa.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gtahubwiqz.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasgiyymn.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtohevkuqt.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gttwjadztw.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifufnenx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtfalsjqcq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gtqpdsxpgg.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtyjxeysnt.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtbbkbygzt.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtloohgiuq.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtieoatltx.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gteqobeihu.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtbfoxqkex.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gtdptgapqh.html

Py:   a + b;  a.extend(b)
来源：http://dali.yonumen.top/Article/details/gtbbukaier.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtllwkscco.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtdkizivka.html

TS:   [...a, ...b];
来源：http://dali.ydzc1.top/Article/details/gtzjtojcpa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtdaxusrxh.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gtybfryksw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gtempcicct.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtwcphcckg.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtxroqjgwh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gthsmwdxot.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtfbfkgibp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gtpjysempc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gtgtrnaors.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gtyqcfscqm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtrmouiitx.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtgcldjpzt.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtmbqjouha.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gtapadfxkg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuanzx.com/Article/details/gthmjyawfw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtlplnyrza.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtctbduqqo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtojdffcdx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtkitqbtgc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gtpmtzfjmk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtpokwzppi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gtjksolcqe.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gtuqkhcsvh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtlizapodg.html

PHP:  array_reverse($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcvxywzm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtgrwrhdqc.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gtezfpsonq.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtimilltnh.html

Go:   slices.Reverse(arr)
来源：http://dali.cheryme.top/Article/details/gttoshwggy.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtmsdgzhgh.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtgplbwzoi.html

[D12] 查找元素下标
来源：http://dali.iojbl.cn/Article/details/gtqnzuonwb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gtqxwuqruh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gtcaaayjby.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtervtouid.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtdxrcphsz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtcudzediw.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gttinjquew.html

Ruby: arr.index(x)
来源：http://dali.chenlongwang.top/Article/details/gtbpkpmgbl.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gtuagwwnlm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtunwwlxrq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtfnnczesq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmolkqjo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtcedonwak.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtkakrwcik.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtczhdyepw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gtlcczvzhh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gtbdbbuhcp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtnhjfndva.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuxming.cn/Article/details/gtxxrmhaov.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenzaomai.com/Article/details/gtawwsqcyy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gtcisztycz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtykwrkmzc.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtfnqzbojm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gtcbekitfg.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtuznvrimr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gteohxopps.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtmdvtzuih.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtqchsjsvz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtrcovqdhr.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtzowghjuu.html

JS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtdkldbzdj.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtgdgrhgoe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtinztbhxm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gtoeyqwztn.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtgzbpeerd.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtttkqpear.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtskjubwko.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gtmcywxtjl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwjydbjx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gthlmetltu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtvlcxsbfg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gtynejysro.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtcnexbsnd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gtalaxnrpm.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtimdigbly.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gtugdvptrt.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gtuqnkygfx.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtnyaexuxf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrotgxcyp.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtaboffbch.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gtfrjhcytf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtsytwvskz.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gtgmzvcoxm.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtupsxdztz.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gtjdjlaxvh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gtnbeyldig.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtqruhtbrf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtsdptlpex.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gtlhydqqyc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gtafncrpvd.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtlzxntqap.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gtqgbakjim.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtyzpelqia.html


<!-- 参考信息 -->