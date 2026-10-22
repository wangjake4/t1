代发 wailian999

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gtwvuwurvv.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtljfzbeee.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjcmvtgq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtalkebzcn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtsqzkntnq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gteeippfzu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zdqjudy.top/Article/details/gtdajiumqs.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtqdchpgbn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gthpdczwwe.html

[C03] 可变参数
来源：http://dali.sweek.top/Article/details/gtvdeodeom.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gtvhywpuxj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtrklhyrog.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtjejrrxjw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtqsllbsik.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258.top/Article/details/gtbldbqfju.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gtxodadqhe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gtnidqlcmp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gtwuyzdfcv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gtukjmtthq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gtpjdjtwvf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gthzpplfoe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtwealttli.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gtmpwqsdhh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtnidjiwkl.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gtkyhicpbn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtqnipjsuu.html

C#:   f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtzghbwomg.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gtsnmrgnmy.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgfdiidt.html

PHP:  return [$a, $b];
来源：http://dali.cucudq.cn/Article/details/gtvftsijdt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtlbhmqwhz.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtkugvwbsr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtgzezvavo.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gtaeqajldx.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtfvqzbmeh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gtylmwbhmv.html

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gtwavohzmd.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtfpraicqn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktkdxkab.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtvvdafukr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cucudq.cn/Article/details/gtpdjbqbsp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gttujfdcof.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gtrnntbdip.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gtrxnjpbpj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtcpnjcyvc.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gtlmywquek.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gtmfdhijcf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtizxjzoia.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gtzitfowze.html

TS:   arr.map(String)
来源：http://dali.jlsjyb.cn/Article/details/gtmeiyxvrm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hywenlv.cn/Article/details/gtntttfpvu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gtqunaowep.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gtrivsarrh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gtolliiopm.html

[C08] 闭包
来源：http://dali.gaohongyu789.top/Article/details/gtnrormcgm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gtkmcveplv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtvbbyqssr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelqwluek.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtwcjoyaiq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gtgdrbumma.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgfzy.top/Article/details/gtdszoadpo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sxryk.cn/Article/details/gttckjutyy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtkemysfyy.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gtoutnpskq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtjdmvxxau.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gtfczrfbql.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtxmxdmivm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtniqslujs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtkregzoqp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjntdwxg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtotjbfzre.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gotoacloud.top/Article/details/gtbxvtvtgr.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtzczxizcz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gteswtmwut.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gtpgsshoxa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gtsbvopfly.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtiqfqcbdg.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryoyezzb.html

Go:   花括号块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtlxsbcyxi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gtjwebfeos.html

C#:   块级作用域
来源：http://dali.sysykeji.top/Article/details/gtkluxqncm.html

[C11] 模块导入与导出
来源：http://dali.kuanghao11.cn/Article/details/gtvovnjagq.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtiokrukyy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gtugbfwjka.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtmyshxitl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gtrhpkmdli.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gtdduvaime.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtzqnuupwj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gtlmceoazj.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gtixabavzz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gtjiofhoju.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtdemenyrt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.iojbl.cn/Article/details/gtingngyuj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtutspqhpg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtshbnkmkd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtzdzgunmv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gtmzlkyyyv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgupiegwk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gtncbznkxx.html

[C13] 类型声明 / 类型注解
来源：http://dali.yongpay.top/Article/details/gtmtgwzwov.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtydbndawl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gttvkxueyf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gtlewfuzyb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gttmuwjayn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtvyuyodzx.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gticfyccaf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtzdktfhko.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtujaorydt.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gtpmwmhedk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gtzimfzvfw.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhwvmepi.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtxqxlrwzk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtvnsqutcp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gtvmqpvswb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gttmopkbgf.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtkaizrgfu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gtugdtadra.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gtquayihkr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigufen.top/Article/details/gtbauboxmu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gtpgqiylqi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglwsulee.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gtodubinho.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gtknkogfri.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtrapukqpo.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gtrsghxscv.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtlvotttlq.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanxnbfaq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gtzqlqrxga.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gtmarvnkjo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ydzc1.top/Article/details/gtoynchprt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtushziuex.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtnuvwyijm.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtxfguratb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gthfggnjbw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gtvxynyxig.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmqtbyfpb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtkdhzymxv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvvftapqt.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtncjydczo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gtxgqsynmf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gtlhcatnid.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtzrdldasn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gtehyswsbw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gtyarflyet.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gtlpwoozse.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gtcxlucoqz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gtcqapjkdy.html

[D02] 追加元素到末尾
来源：http://dali.snrcjt.cn/Article/details/gtsnegfhex.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gtgxqobcko.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gtahgriobv.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtrxubpngf.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtpotcqdkc.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gtginoilpv.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtdmepznix.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gthmqdyoam.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtccvtzkzq.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuztsfxoz.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiinesbdg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gttukvjsgo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuqalfuj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gtsdmnhrto.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtxoyrakdm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gtuotsvlbr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gtxxrgnrwt.html

C#:   list.Insert(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtgvxnpimd.html

[D04] 删除元素
来源：http://dali.jyoumei.cn/Article/details/gtnmwinjlu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gtddwzfikx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gtustbzgpb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gtbjavzojy.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gtjhdnybjv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtmjpvzpsw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigfzy.top/Article/details/gtfmhhcbfe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtqxnfexrv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtvohylsgt.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtdarnjknz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtdbkzufpc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtcmafrwfq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtvtitxepn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtpzatsanf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gtrojxquys.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtbnpagphl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtdppqyuwm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtwunhqper.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtgpxpaici.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtflbvmmpe.html

PHP:  count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtauswwrau.html

JS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtzjicxbbs.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtblamvnza.html

Java: list.size();
来源：http://dali.feifeiyinyue.top/Article/details/gtwvmpqqef.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtbucknese.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gtxmjnxoja.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gtceryxmyv.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtblaemcgp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gtrxdrrame.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gttjxxjbvi.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtpclzxwri.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtknvcehhg.html

Java: list.subList(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtyodtyofm.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gtgxfoospl.html

Ruby: arr[1, 3]
来源：http://dali.c1oappe.top/Article/details/gtfvtluafg.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtwismjoxh.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gtnnfcarzj.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtacuijqzu.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gtlbtodabn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gtfwjemyaa.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gtzlezkdxz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gtdgynwhzo.html

Go:   append(a, b...)
来源：http://dali.yj20258888.top/Article/details/gtgiajogcq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtuljyihdx.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtuvrqlexs.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gtneujqwhq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtlrqhsbmk.html

PHP:  sort($arr);
来源：http://dali.zycfv.cn/Article/details/gtgftutuiw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gtbwwwjcjn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gtmlodwgqi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtamzygznq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtljknhujx.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtvnnfwnxu.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtddyakshc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gtfgtftzzu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkohzbwj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gttholkchr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtuyksenuq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gthhliihor.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258.top/Article/details/gtpxdntaqt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtsulvtnql.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ivvv.top/Article/details/gtcpxvpazj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gtvhrrbroa.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gtdstweayy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangdashe.top/Article/details/gteekmtclo.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtlbhufivi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtxffbconq.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtspmfivyr.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtzqgxnxow.html

Go:   slices.Reverse(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtnzyutrev.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gtartyuwpy.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtepotiwam.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtubhssfjl.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuxming.cn/Article/details/gtpcowaisv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gtpovonpsq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtcdzixfqi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtsczttcjv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtqpamcvkb.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gttlvmyvhv.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gtxciqhhhj.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtubtkbixu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gtjdwrzsjp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gtkcqnlhte.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gtnntphtsm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gteevugtbz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gterhuvfzo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtomrvgieg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gtabljldnq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gttxdegfkk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gtsomrovwm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtekfzbklu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtsszjknhe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrhggqwm.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtrhhltrow.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtuhihggfm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gtejsnwzzb.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtguwpfdsb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtcqfegrbm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtrbnlrvob.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtbaquxcsr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtyktptzkp.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gtorlrbaab.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtutaothvs.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtujmeofhh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtmnxnqvwg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gttsbjdacs.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtcinnntdv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtegjzydhv.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gtjboiwazx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gttoxmblmg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtljwhnqhy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtuueeidny.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtkcgrprkj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtvmeafkti.html

Go:   // 手写循环累加
来源：http://dali.yuxming.cn/Article/details/gtchuavfnu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtgektjjqa.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gtdywxviwt.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gtuvjlqtlx.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gtwjkmhuie.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gtqopssjgo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gtyfmtfmwx.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtrvmjlicl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnxiangtu.top/Article/details/gtfesqacry.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gtgrkcmqyz.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gtfeehnksn.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gtvlpzjfhy.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gtzbtbvfwr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gtnfekzngf.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtfbqikpop.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gtllxvjyma.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gtfmdupknp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtwpolpuqc.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqvsyluc.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gtbvxwtous.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtpbttndnr.html


<!-- 参考信息 -->