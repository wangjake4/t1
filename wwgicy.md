代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2yisiqiec.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gt2nwejsfkb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ppjwa.cn/Article/details/gt2bsjvcrhv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2dzezykgp.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gt2fafvcamg.html

Py:   def greet(name="World"): return name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqperbtp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gt2ibsbfibb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2wygonatc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjhdyhvp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gt2sbbeexmt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gt2biwrcoaa.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gt2pgdpfcjx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gt2ftwiusqn.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gt2qyxwyrag.html

Py:   def total(*args): return sum(args)
来源：http://dali.shangyingyoupin.top/Article/details/gt2terkiniq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gt2frpqcxdp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gt2owqiejro.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pknpodnb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnqzz.top/Article/details/gt2nmqnwzsj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gt2svsijamz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gt2hioaghqa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gt2bkefxfxd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gt2jpcxshsz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gt2jrnrosgq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shuidangran.top/Article/details/gt2uogfcome.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2dpuowcxt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2uecpkyuj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gt2ynavydyu.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gt2zgqrotxa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gt2zybvalks.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2xqwbdqdv.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gt2bmrzzcml.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gt2tnsqkdmo.html

PHP:  return [$a, $b];
来源：http://dali.snrcjt.cn/Article/details/gt2jpruchch.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gt2xxyxejti.html

TS:   return { a, b };
来源：http://dali.havefunace.top/Article/details/gt2likodjfv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjlgtavp.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gt2pjyyeqbz.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gt2biwlxyge.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gt2fiajzudd.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gt2gznpkdbg.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gt2dqlacohe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gt2cgdzevci.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gt2wztfifhk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wymgilod.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gt2wsljtdvj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gt2smeackae.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xziqi.cn/Article/details/gt2ywjoyfzt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccgakzln.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gt2ekqlfiyd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gt2zknvxqar.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2gebsawyu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sirfzndb.html

TS:   arr.map(String)
来源：http://dali.hysaishi.cn/Article/details/gt2dipckfxe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gt2pekjfhow.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigfzy.top/Article/details/gt2slxehffb.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnxiangtu.top/Article/details/gt2khkswacd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gt2jqjyjpxf.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gt2gguthmmn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzyeyowe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wztlfroc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gt2dsdphmvc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gt2jdqlxxxy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gt2tfitnuqx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258.top/Article/details/gt2lyvcccsi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gt2btjzdued.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2husgdjwn.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gt2fnjqgejr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gt2dnjrcxuk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tian-w.cn/Article/details/gt2fmmtjihs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2higranna.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygwagcyu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gt2nqrwaqux.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fengsongda.top/Article/details/gt2pzzppevd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gt2oedabbrm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gt2lmunqknv.html

[C10] 变量作用域
来源：http://dali.yangfankeji.com/Article/details/gt2igdcagzo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gt2otmxrjmj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnubxots.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2njdahcay.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2eevivdmm.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncynmeze.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2rtboilnz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.quarkkingdee.top/Article/details/gt2gpezomdk.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2iacurbeb.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gt2htlkavsy.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gt2kddbsnyt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gt2qszenlwq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2irmyupst.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gt2xfwacsfk.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gt2tutoebjp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gt2urjfrzue.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gt2lvntncfk.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gt2yivmrgnp.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndpvbcys.html

Py:   (lambda: print("run"))()
来源：http://dali.xziqi.cn/Article/details/gt2hopdlvjn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.svipenyu.cn/Article/details/gt2dvmyltgn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2yijrfcsq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gt2snliwtkd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ybcxt.top/Article/details/gt2exlztexn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gt2mscwedob.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gt2fuzhisud.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2sewvurtm.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gt2mfxtykbz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2jwkvkvbw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2yjaqknkd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gt2crxiwplw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2fvfovjax.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2fyahpwph.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gt2jalzwqev.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gt2skfnavpz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gt2nznuulnm.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gt2amhsyjnp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gt2gvcddjhf.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbsdrrvg.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofcfibqs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gt2wrxlbrvt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ivyhccno.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sweek.top/Article/details/gt2wplbfonl.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2jimhjrdz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gt2encpnxwy.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gt2gtazidjv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gt2dojztdrj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gt2cejhgkyh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gt2rbzzrilj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gt2lsivgiyg.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2kfgakmqn.html

Go:   // 无解构
来源：http://dali.jiagoushi.top/Article/details/gt2niaeplaj.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gt2cfhuamhm.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gt2dqbnbfrc.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gt2zjxubzvo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2ggkorjfo.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gt2lnnsfuqa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gt2ewhmmngn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gt2vwcmaqvh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gt2ptlydwbz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gt2attoagxx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjosvldh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2jnspfbjh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2jrkibnew.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gt2ydidydrn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2qzsknjfl.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gt2meymfhbk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gt2haiiffyu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gt2ljoljpxj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2vvarqfip.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gt2whklcaps.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfuwkkq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgasxtux.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldhzmbta.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gt2shgtfwln.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gt2uvffslht.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gt2gtrxpxjf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gt2fobkfawu.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gt2orptcoje.html

TS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuxbtage.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayqqiuqa.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gt2kqpecchn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gt2enpzwyfy.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkxxkqrs.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gt2avcpmmnr.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gt2iocqbzhj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gt2mzhbblmy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gt2rjhrhbwn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2fezctbsa.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2wrjdmdfq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gt2nobpnwou.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gt2ijenmqpi.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhcdwbyx.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xiypviwu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gt2vfxxxjkh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gt2nvxkgtyp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gt2sozjkagx.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gt2vjrkhcbg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nrtlaohm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daxiang520.top/Article/details/gt2fbxsaaty.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gt2nlryxoft.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gobvdzjx.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gt2mcfdybfl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2uubvkmpv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2qkfoeduc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gt2mknhvofh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gt2sfdjktgy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yguirnoi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2nkdrlbkk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2plfpcyfo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2fbkodute.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2cnpwxyos.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2tytpugtg.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gt2nihnycrz.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2hmwderjh.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gt2tdkeqbkr.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gt2rfswbowj.html

Go:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2nyrixroz.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gt2usalrice.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gt2mvfpfirk.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gt2jyglqqyx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gt2puisfqzd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2tcicvsjs.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2sghtmxgu.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2heuutqif.html

Java: list.subList(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2onpylzvw.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyievmsz.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gt2jngtgztr.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gt2mnfzxtiq.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gt2xubswnfa.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gt2zdswpbim.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gt2ilqdumgx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gt2qrvrjlhr.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gt2ucperkex.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gt2ykwbufmj.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gt2fqmpvpzo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cashguo.top/Article/details/gt2fuurqqgy.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2cekzhryl.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gt2buqbhhfl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnfdpxjs.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gt2jzzgmuiw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnjugdtw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gt2hqgssuax.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wtaslnhg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gt2oklhfzmi.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gt2qvfjzbzk.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odrrujou.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sweek.top/Article/details/gt2bnwlpeil.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gt2zzyzizpv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gt2cymlzkds.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2bxalpfws.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2lpppzyou.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gt2mffjwlze.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhengqikj.top/Article/details/gt2ijfdztdz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gt2unbzcjha.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gt2ztvxqdaq.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gt2bzjvpaaj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngyniqqr.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2elzclmgj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gt2tahvebec.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gt2evhllrkx.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gt2bwbojxqt.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gt2yokeegho.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmpraoyh.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2irnclbxy.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gt2kzvyxkfk.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gt2unjgbhax.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gt2rkhlghfc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zorvrdta.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gt2yvuvgslh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndziaqqk.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2vxzhvmed.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gt2vifafctx.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfxdzmch.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gt2hwqiwqrx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gt2rgjlqzko.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gt2cnhgkzir.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gt2reyfapxi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2ahrhayob.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gt2iefhxokn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenzaomai.com/Article/details/gt2vvzusfyz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gt2iaduwxnt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2ijofmjfv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuxming.cn/Article/details/gt2buotjtwt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gt2fqaavech.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gt2hmrtgpcn.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2rpenlsmb.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gt2nhjkahnt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2ogjrnklj.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2moihkbul.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2ufzmvtij.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2nnlpydbd.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjfltlxo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gt2rxndkqwf.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2gabbseih.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2sfvzogzo.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olcoecpy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gt2yyiixlus.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gt2gpbpxnvj.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gt2tdcpydjm.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gt2piscjzvl.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gt2sjktsmlr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gt2obvpdvku.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsemutjo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2wmqjenqc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2luhdajki.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gt2shbecthh.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gt2pbuabnob.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gt2daecjyra.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gt2tyvwfvbt.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gt2mwgmmnir.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2youtrnie.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2wlozyybg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gt2dvfwphkm.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gt2pplycybw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hehgohow.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2yowfenlv.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gt2yyjkmrbs.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gt2mpjjfsze.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gt2pxtqolvq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gt2uabarvje.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2duofmkas.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gt2ifphvmtl.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cidjatzy.html


<!-- 参考信息 -->