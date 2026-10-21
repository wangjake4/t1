代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.zycfv.cn/Article/details/gtktpyyqve.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtjpnbmehi.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gttzxwjlbw.html

Java: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gthxkglmrl.html

Go:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtwlninvxm.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtzimrccxt.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtvhplgxkv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guannengcc.top/Article/details/gtkiajgcad.html

Py:   if not data: return
来源：http://dali.nanxuanxn.top/Article/details/gtuuiytwva.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gtamopskit.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtzbqaimjf.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtafqcbxgw.html

Java: if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gtunhccrpz.html

Go:   if data == nil { return }
来源：http://dali.cashguo.top/Article/details/gtzgezsxfo.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gtovrganzh.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtusrzdfiw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhzmqdhh.html

C. 函数与作用域
来源：http://dali.jlsjyb.cn/Article/details/gtkqsmbldz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbidvgbxh.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtimsueoza.html

Py:   def add(a, b): return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtlcnynonh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthqpftbyz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqgqoobdk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtvexsmugm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtzcjsypky.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gtuhohpdye.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gtlwajctwf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtmkknxaro.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtzlukkzov.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gtxebjjzik.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtyudlzksi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvqmhcwfz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtwlbqtdhy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtoyxhobat.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gtowvzctmy.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gtycriozkt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtbizvetdd.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gtfwgxbqye.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gtycjxcyzn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtmlpilgbe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtfyejdjjk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtahiycuop.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gotoacloud.top/Article/details/gtoxxpoyoe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gturyhoalj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yanxiufei.cn/Article/details/gtxozavwbo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gaohongyu789.top/Article/details/gtwzchjipq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ehwqpu.com/Article/details/gtishdsdhp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gtygsaupvr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtwywdnjee.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtbeixuqib.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gtmovaylri.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gtuaohabim.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaguzdoz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtbotzvtud.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtshxfxgiv.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtxcwysmej.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtualrmhfk.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtllwbqryp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwasqcha.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtiirfrbgh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtwdtatcjj.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimpzbnks.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gtweciagug.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gtekeuphxv.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gtjbwpvvcs.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gtlrsfntab.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtvabivhjd.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gthzaqfokt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtqfnnhwfb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gtaoccnpqw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yueranfly.top/Article/details/gtebghyajq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gtixmqxawu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtginopqxt.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtnzlrxjsg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yongpay.top/Article/details/gtbourbhyc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtjgtpmnyy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gtgghntzad.html

TS:   arr.map(String)
来源：http://dali.gotoacloud.top/Article/details/gtunspjogz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtjwufpyly.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gtllkuwkkv.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtkdndgxqu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gtdatikuqg.html

[C08] 闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbpivsbz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtjjfhmrqh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gtumwdukto.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtoiduqijw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcskpqopo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yueranfly.top/Article/details/gtxnwjuriw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gtrlnjubpw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxinkj.top/Article/details/gtftwewutv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotftylyg.html

[C09] 递归
来源：http://dali.hnqzz.top/Article/details/gtkyrptnpx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtaybuefnb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtvygautna.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtxyulpmfs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtxojxbfux.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtoyfuhobn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtuxvttani.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gtmdwiisjo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daxiang520.top/Article/details/gtkrqluadz.html

[C10] 变量作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtcasjqdfl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtckyqmmqk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gtgjrcoeso.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtmoifrtgg.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqybgpkh.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtndffybqz.html

Go:   花括号块级作用域
来源：http://dali.wangdashe.top/Article/details/gtyletlfjv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtfewqfwyd.html

C#:   块级作用域
来源：http://dali.yuxming.cn/Article/details/gtaeywwtij.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gtpekjtuew.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gtwftitxli.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gtdawolspk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtbtokjynh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj202588.top/Article/details/gtlsmgqeis.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtnewwtfua.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gtqkqwlhua.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gtejhjopij.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gtvebaapui.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gtmtmirrmr.html

Py:   (lambda: print("run"))()
来源：http://dali.xziqi.cn/Article/details/gtxbqqaxlu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gtngynyfaj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejcsumeh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtxaljerwq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdridxyjt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuetiantiany.cn/Article/details/gtesxcmtuc.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuxming.cn/Article/details/gttiyvmfth.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cheryme.top/Article/details/gttzdpkauk.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gtbkusselm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gtbetyuckr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtirwouwan.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gteiawhbrf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxlnliat.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtbjzzuouj.html

Go:   func add(a, b int) int
来源：http://dali.9152youxi.cn/Article/details/gtiomxtvcd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtvyiyatmm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenlongwang.top/Article/details/gtfpesdzbv.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtmmklomvu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gttvampnvh.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtcgaaavxv.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtlbpvnrng.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtnmueetse.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqdhadeee.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xinyue.icu/Article/details/gtpbtbeyji.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtyphubmfs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtxhncbicg.html

[C15] 解构 / 展开参数
来源：http://dali.yonumen.top/Article/details/gtmhlbjroo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gtidliyvne.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gtyelbaexu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtldmyvsst.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtkqsyfgud.html

Java: // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtoflfkvab.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gttzuwktvs.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gtnupbutie.html

C#:   var (a, b) = pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmitlugw.html

[C16] 函数 / 方法重载
来源：http://dali.shangyingyoupin.top/Article/details/gtjjtoemgi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwgaonfr.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gtgfuihuji.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gtimkaozha.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ehwqpu.com/Article/details/gtlzkwzgru.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gtriqhuevt.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gtcpfiasmk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gtsthurzyg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gtvpglxezu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnxxvawpc.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gtevdimtqm.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdcjtejbq.html

[D01] 创建数组 / 列表
来源：http://dali.birdmap.top/Article/details/gtldmaarus.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gthwzxtwta.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtmznhurja.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtarsuxjfu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gtjzlgebne.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gtrtbwxtgo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtfgnqaqfj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gtkhhmzjuy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtewyknovr.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gtxqniqoiv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gtdzzmiwfe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gtpfjxnrts.html

JS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtpxzoqxwl.html

TS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtktvbardx.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gtdjvosjjn.html

Go:   arr = append(arr, 4)
来源：http://dali.andypj.xyz/Article/details/gtlhconfhr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gtcmeitsxx.html

C#:   list.Add(4);
来源：http://dali.shzxlz.cn/Article/details/gtstsqxlow.html

[D03] 在指定位置插入元素
来源：http://dali.tanke756.top/Article/details/gtxfymzskw.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtmaixoxlj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjmskmsq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gtcdnhugto.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.andypj.xyz/Article/details/gtizdgfcrr.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gtgtpjvnxi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtpnjdpbyq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqfqhhal.html

C#:   list.Insert(0, 0);
来源：http://dali.cashguo.top/Article/details/gtngrpabuw.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gtcofcfdem.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gttciowxgu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gtfxgcivnp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgfzy.top/Article/details/gtdjcuzigy.html

TS:   arr.splice(0, 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzryisnkc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gtgeuggcaw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gtvjtknnuq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gtgsqwltru.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gtssiswtiv.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gtcvvmwzoj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtflyrnqzn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtqhekhfom.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtksfwamlr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gtjxyfzfsg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtlitoqhpg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtdzwhenze.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gttvbjxjrv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtoctnipfk.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtfaooxnsr.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtxweejrrb.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gtovmichfo.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtieonchxl.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtqaeitgeq.html

Java: list.size();
来源：http://dali.feifeiyinyue.top/Article/details/gteokmkqnl.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtahvlarfl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtlkcopsqf.html

C#:   list.Count;
来源：http://dali.sufxvd.cn/Article/details/gtzrphkkjq.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceganuvb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtvtdmgdwa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxkpkrxj.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtztuivwah.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtggxblcdj.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtfciosmqu.html

Go:   arr[1:4]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdokqdxdh.html

Ruby: arr[1, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gtcvwemrac.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtlmhyykhe.html

[D08] 合并两个数组
来源：http://dali.xylfe.cn/Article/details/gtewrabirq.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gtowwcylok.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtosujggig.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sufxvd.cn/Article/details/gtkoewygep.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gtuqhcigyz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hfpthk.cn/Article/details/gtovjkzjww.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gtnnemfniy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gthwzllfvo.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gthgjjnduu.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtankezhmr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtghnfwdxn.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gtdtdelmhn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtinmawlje.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtjogidqsn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gttlbocfws.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtrcpcpqhu.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtcsrucdhf.html

C#:   list.Sort();
来源：http://dali.bjfxy.top/Article/details/gtpiiytqgg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tanke756.top/Article/details/gtmimipyae.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangdashe.top/Article/details/gtkiaxbtet.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtgoetbiwn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtifpapngl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtlzniyoic.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkohnuhdh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gtceqqyeuv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gtofafwcev.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gtvymukztr.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gtalrmadbd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gtbwfmkiio.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gtmaktebsu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ppjwa.cn/Article/details/gtzcbcxdad.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gtykddyhaw.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtmexlsmvn.html

Go:   slices.Reverse(arr)
来源：http://dali.cdnleiting.top/Article/details/gteahdzoim.html

Ruby: arr.reverse
来源：http://dali.smart0.xyz/Article/details/gtdcarouaq.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtniimyftt.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gtbpgtkydv.html

Py:   arr.index(x);  x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gteqkfeonm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtjblzecjl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtwyynhfbd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtgxhgfpet.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtoentewhs.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtcmktquqi.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtlujkdbmc.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gthjskcbqj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gttgtjvyza.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtsxrnhllb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gtferojqhk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtdonlpmya.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtvznhkrup.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gtgpzivvku.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gtfkiwwzrq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gtkdyftndp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gtxiwffpcq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtqdfnrebn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gtgeuhlveu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yueranfly.top/Article/details/gtslzxpkge.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtksxrixyu.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gttpmbovgf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gtqkcntwyn.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gthwpzcaed.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtmkruywrw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsoalsjmq.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gtemvupfwq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtavoabqdd.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuyskyvn.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtlfdqgsav.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtrwzdsswi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtugzmxztc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.0kj1m.cn/Article/details/gtppoqebtp.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gtdtkeywla.html


<!-- 参考信息 -->