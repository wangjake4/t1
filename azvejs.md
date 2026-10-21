代发 wailian999

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gthsnurchg.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gtvpjvxrvp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gtovggtqjj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtvurxtato.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtlygicnii.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nwbrower.top/Article/details/gtnfdamizw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yangfankeji.com/Article/details/gtqzusvfjh.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtdawefqeq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtdfvqyxwu.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gtlnjjpyoo.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gtjwhyobma.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gtsrnyidzu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gtmcciovcs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gtdpxknrgp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gtpvwebccp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtnpawfzvd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkuywexz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigufen.top/Article/details/gtfoavqdia.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gtbmvfqgzq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthassuxmo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtnymxmiot.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtdopkddsv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtntluvosx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gtgwtpjfeb.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gtjrxysztr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtijpjnkvb.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtyiptaxsr.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtsxeevnfr.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gtmqrdyusk.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtglsahjcu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukdybodg.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtvjijzgvj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gtdpgmjomi.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtqaidfzod.html

Ruby: return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtnknkjfsd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gtkqdiwycw.html

[C06] 匿名函数 / lambda
来源：http://dali.gogol.net.cn/Article/details/gtdbastkdg.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtukodxvud.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtyfssspbf.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtslwdscjp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gtgudyzkct.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtzxxigxxr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtdjtljydy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gtkfiilfmt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtgmrflaln.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gtublpdydz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuetiantiany.cn/Article/details/gtirohnrpb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtkmtqdktt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gtmdyyojzx.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtqkkwmeot.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigfzy.top/Article/details/gthpgnbljh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.smart0.xyz/Article/details/gtqlfttsae.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gttrghxiav.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtfgprdfab.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gtrgebsast.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtgobpjsvr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nwbrower.top/Article/details/gtbwhtdwyg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoapaanx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtnjixfier.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gtrwckwbqc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtgvfwpfoh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gtyapzmkqq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglmbhurh.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtujawjlrh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtflnqkaid.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnrivriht.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtgezfvfrk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtvgsxukdg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtikifsxjm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gtqcgfueag.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gtnsqpjtoz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.0kj1m.cn/Article/details/gtvvyhxhgb.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gtqmrjlntu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gtksfnzaqn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtymvbazad.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gtejjhagvg.html

TS:   同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtbqjsruhd.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbqnuoxf.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtfmggrvwv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gteajriubo.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gthcwhwgyv.html

[C11] 模块导入与导出
来源：http://dali.gzhubu.top/Article/details/gtfbvtlarn.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtjeyadhsc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gtpjpbkghw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gtxlnnnule.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gtyzlsirds.html

Java: import java.util.List;
来源：http://dali.zhoulong.xyz/Article/details/gtkdvfyysr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gtdmbhgxzm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gtsqicywvi.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gtcbghmgmu.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gtezwhrrqo.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gthusnyftg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsmqdqdd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtzzqymdhw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gtnkfqkdto.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gtpthucszh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gtagvvsytn.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gtepyyvmtu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gttrncexpy.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gturfvsfno.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gtfnnorznj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtdyrnvuwe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqrjilul.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtaumuyatd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtjlruyooj.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gtwuccklwk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtfildybrb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gtiukuuksa.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gtrtlhyxot.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gtwsajgrcd.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtwpvhsdyk.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtpxsrabkf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gtcfkaqmcy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.c1oappe.top/Article/details/gtoipfyfek.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtspkbyfff.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtamrwqckk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gtcshdamft.html

[C15] 解构 / 展开参数
来源：http://dali.feifeiyinyue.top/Article/details/gtpqvvtxxt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gtruztbgud.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gttngdhwsa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbcmfcyb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gtqfragwcm.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gtkotukrpd.html

Go:   // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtpcpnjzfl.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxawqojz.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtgtopkkei.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gtgeefnlkt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtxaetfxme.html

PHP:  // 无重载
来源：http://dali.fzhhl.top/Article/details/gtjscpqmsj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gtrgkhnwhl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gtjkzkclut.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gtmkupgezm.html

Go:   // 无重载：用不同函数名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqfncqpe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gtmczptohh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gtltitchgi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqgvxdbpk.html

D. 数组 / 列表 / 集合
来源：http://dali.svipenyu.cn/Article/details/gtqmckngsz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdqziarhg.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtcpzmhrhv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gtxdlirffu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtpzzrnvns.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtuuwdrwcb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gtyubvaoba.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjyfgbja.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gtodfsjyps.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gtufgbvfrz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gtkwpxlnpa.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtklznuacg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gtnitxjxjm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.meibo888.top/Article/details/gtqzatzncn.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtwmqujqjq.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtuurusuac.html

Java: list.add(4);
来源：http://dali.chenzaomai.com/Article/details/gtrxokiryx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtxzckctji.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkdwrytg.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gtsmsxcbxv.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gtejsnlete.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtwunqjnmv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gtnnzmdnqm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gttytizhsu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gtsfrrpnad.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gtxjipzihc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gtphumknmg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtraqeebad.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtklikrzyv.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtbugmyewp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtvrwmcwjd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gtqcgunkkw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gtybwcpjkx.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtjzxpibvv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtqjgrxgqw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gtxgjhqtbn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtkqmkscxz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gtthtkzfym.html

[D05] 访问与修改元素
来源：http://dali.jiagoushi.top/Article/details/gttozncleh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtfkyuwddy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtzcklzcwc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtjmvojlrn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gtmdhftahh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtmnefshci.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtfwdwxtsy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtcbahwnfe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtdhzoitca.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtzarwusyx.html

Py:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtewlvdrse.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtgposxnzw.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtzzcuftqc.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtxucvdknh.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gtdxxkyzwz.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtotmwcfhq.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gtspuqdaty.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gtjyxrqalg.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gtsohkkivy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pengpengdd.cyou/Article/details/gtedxfqzbi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtfipklvmq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtjqqtjdtp.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtntxpesai.html

Java: list.subList(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtumwqrqqw.html

Go:   arr[1:4]
来源：http://dali.xziqi.cn/Article/details/gthkydytay.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gtivkwotxc.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuanzx.com/Article/details/gtpvscxazm.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gtnkxeqydd.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtnchjbnal.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gtmtluxjwd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gtdqlmfgqb.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtiyzrklyx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtyljrxwpg.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gtvhvuuwyu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gtygvwrxde.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtnyksmdjb.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtzyvpketz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtpgkelcyf.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtdgisedjs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gtauminste.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gtopvwyigx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gtupbnrnfd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtgijazkwd.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtqhcckrpk.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtykxbbllw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gthjifnbop.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gtbnwffpew.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtmqybfwxl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtbafkyivv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtpvcrkeig.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gtizzrvect.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gttegxfnfj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtffrpsrbq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtyrbchwkv.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gttqrvqxki.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gtinxbkmmm.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gteurhzazz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gtkaficqfq.html

TS:   [...arr].reverse();
来源：http://dali.andypj.xyz/Article/details/gtidamenpu.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtxhfjuhdi.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gttfcgwwrr.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gttstqzube.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtngqnxwjl.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpccgrimb.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gtfijcggow.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbtcgsqh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtnddfcriv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtmalmrnlk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gtagkspavx.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtjqwgzgpp.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gtdxfxmtfu.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gtmvsaqufr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gthnasfskz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gteikulqog.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gtxuplghbj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtmiqnbhde.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtqnhknlyn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtobimlghr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtjovqyumd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gtbhcxpnkq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gthhyyxtfr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtuhkabchf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtlkddsyez.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtunhlbkcg.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtqjsjjjvw.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtprwdttes.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbejyzjir.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtatqkqaka.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtezoxaexp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtnujsiuwb.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gtyokrzoca.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtzyjedslf.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtufvzvtbw.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtqcxxpieu.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtbxtbtntg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtxlcajbzm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtqnzkqlil.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gtdbxnbvoi.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtnudlhwmu.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtnfuxdyee.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtickjjlhl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gtegzzbhgn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtrlwfducl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtpjwogwdh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gtyuutatuz.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gtibwgppgy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gtvtnwbwtv.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gtwfbcyntt.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gtcwjqjqfj.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtlmevcrie.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtizoywmjk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtyugbscku.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gtowbonaro.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtlyerpcno.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gtxylscjcw.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gtreitgmlj.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gthfysnjwj.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtqueffdeu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtufftturq.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtpzctsgre.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtopuchruw.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvrmtqcx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gtpsjzfgxp.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gtnfgwzcim.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gtjbrhvgiv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtgqweomif.html


<!-- 参考信息 -->