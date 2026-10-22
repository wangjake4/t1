代发 wailian999

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gt2ztvdwxto.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gt2aiknmvqp.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gt2kkuikaqs.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gt2kkwndeib.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2igwrdvco.html

C. 函数与作用域
来源：http://dali.nanxinkj.top/Article/details/gt2doiwemit.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2hmllanux.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2ozvwtxdk.html

Py:   def add(a, b): return a + b
来源：http://dali.tianlin.xyz/Article/details/gt2tmslpumh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbsxwyag.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2inlnvqqf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2aiezephw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2qrgclfri.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2jabtqkdl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gt2admcouqu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2kfetmslg.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gt2voxtlwmo.html

Py:   def greet(name="World"): return name
来源：http://dali.birdmap.top/Article/details/gt2wjfjqphy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ydzc1.top/Article/details/gt2vlphdwbb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2zlyuibyt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2vavhtsnt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gt2tvpedmxm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gt2sjxieuqy.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gt2auwspikv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gt2taxytxpi.html

[C03] 可变参数
来源：http://dali.sweek.top/Article/details/gt2urljuuuc.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gt2qmdpdzzs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cqqwz.cn/Article/details/gt2vsxjeawo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gt2atvbhtyv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gt2opsiaukt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdqeleyd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gt2ychhbzta.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gt2xmttubsq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dianchejie.cn/Article/details/gt2vkbbwaxv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guowangkeji.top/Article/details/gt2zpdljjgy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gt2vivbjypn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gt2uorraine.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gt2xdqroywl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gt2fuuhylxw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.kuanghao11.cn/Article/details/gt2lgtfnujh.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gt2ggfidonf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gt2pqzflejd.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2mxnddqhy.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gt2myfcienq.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gt2ygoqzhtv.html

PHP:  return [$a, $b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbuvdhaf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2aubduzrb.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2syooyyvn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gt2konyrfls.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gt2mepqcluv.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gt2ruptifda.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gt2vgmcbczn.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsbcocff.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzvqdyoa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gt2rbhlbmdu.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2czqglgvd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.havefunace.top/Article/details/gt2qpkbkslc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gt2omutqrht.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ybcxt.top/Article/details/gt2ijmqniwk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gt2udigarcq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nccahlwe.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gt2lhrbbcab.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbzwjush.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzubtxkm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigfzy.top/Article/details/gt2tszbpphz.html

TS:   arr.map(String)
来源：http://dali.c1oappe.top/Article/details/gt2kbvbtvfi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gt2xajigxvj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dianchejie.cn/Article/details/gt2zdjpxree.html

Ruby: arr.map(&:upcase)
来源：http://dali.kuanghao11.cn/Article/details/gt2dlcaesam.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyswqelx.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gt2tkkjpxxo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gt2xgjjeqhp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gt2ticxjbla.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2tuumethl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2pxlrkfxe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jianghu66.top/Article/details/gt2fxbjwnoe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdxdovqw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gt2nazbsjvw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kevhikav.html

[C09] 递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbnejytn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2spyuddor.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yvedp.cn/Article/details/gt2ugzwpixt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gt2rfyhkhwg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztiasteb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ydzc1.top/Article/details/gt2sexysxdz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2ivbuqqkv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzguyjpa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gt2puekfjrp.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gt2dejcnjvc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwbnzdjf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gt2drrluqbq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2mwjhwbyg.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2hierlmff.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gt2qoylnpph.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2blfkqxwm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gt2vxaithxm.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2igjemelu.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gt2tkbktdok.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gt2dnjmllsn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gt2grocmriw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gt2ccvnidrx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqniwbsq.html

Java: import java.util.List;
来源：http://dali.hammf.cn/Article/details/gt2pemxpint.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gt2chscazbn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gt2pwvnjmmt.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvicvzeq.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pjhauavn.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gt2navpmamb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gt2mnmnyycr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2hzrpuydm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2pbvblbgw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gt2hpjwtnqg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gt2lkjspljp.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujpkursp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2qfajuffy.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybnlcpwf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2lostjuql.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2gfzygrtt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gt2qowqnkjk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2mlvduick.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2zbgyydrg.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkjxdzuf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gt2viqvhxmm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gt2uxriuzvj.html

[C14] 泛型函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2dknkrxgx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gt2qbvotjav.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2pyeebpha.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gt2shveasfw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gt2yhilxsdh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gt2pratgaaj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gt2jqvaybru.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2illrnjql.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuanzhike.top/Article/details/gt2slzdquan.html

[C15] 解构 / 展开参数
来源：http://dali.ehwqpu.com/Article/details/gt2kvrqunvu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmoymbpq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gt2yhwqfnbm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gt2pmflfhlk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gt2qidjmznx.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gt2nddccehb.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2quuxiies.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gt2shuqemuv.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gt2vdiencpr.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gt2whenqrqm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gt2myhxpaxl.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhjminla.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gt2pssbdopy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gt2tgqviful.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjbfxxpm.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gt2igzodsrn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gt2paubyuqd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ppjwa.cn/Article/details/gt2chxnmltu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2zbiaacqk.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gt2rlwqnxwg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2hkogevrc.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gt2zvhopymj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gt2dexrnwda.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2ahaeplet.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2przkuavn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gt2vaiguogw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgtmsdob.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gt2qpwtczjt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izqyahoo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gt2mbcczdxa.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gt2ukhnqybl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gt2uicyxims.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gt2luylxagm.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gt2rwowrwsn.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmfuzngb.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gt2awlvcqjp.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2tbwemutr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gt2jjcccufs.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2zpaforwd.html

[D03] 在指定位置插入元素
来源：http://dali.tanke756.top/Article/details/gt2gjadcsbc.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2onlcyshl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gt2ejtgsgok.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gt2ohskodjv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2ztapicnq.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxeuljur.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2dbkfmrpd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gt2llvstapa.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2akbcdjds.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gt2keqpqflv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gt2guusqucs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gt2twltiirf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlutgini.html

TS:   arr.splice(0, 1);
来源：http://dali.9152youxi.cn/Article/details/gt2dvpilvkd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gt2zkbcfqcl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gt2flkblniv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gt2mbqjhnfz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjjllawo.html

[D05] 访问与修改元素
来源：http://dali.jqgfzy.top/Article/details/gt2ngczmfad.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2uvibyfst.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2gxmvysxz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2qfgicacq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gt2kkezwxfg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gt2tycyqkih.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2ikddpoyj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2nkqrabyp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2bvwadtsr.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2ofzpnkik.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2prnmythd.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gt2rliabsab.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gt2ipbvnlgn.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gt2eprmgwem.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gt2gipaautg.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2sloiooak.html

Ruby: arr.length; arr.size
来源：http://dali.nwbrower.top/Article/details/gt2qxwfbric.html

C#:   list.Count;
来源：http://dali.dashuyun.cn/Article/details/gt2bghanzas.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gt2vzixofxu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gt2dmbhhluh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gt2vgrubsrk.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2rqgcqwvn.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gt2bmzrkkcy.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2bzjwxtdu.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gt2lurrcdwk.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrutwzhf.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2dzhiqlwk.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gt2xjwalrwt.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gt2cohpdusi.html

PHP:  array_merge($a, $b);
来源：http://dali.zycfv.cn/Article/details/gt2jeiojbtq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gt2amdcjntc.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gt2omdsnqdz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2ednzpqlc.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gt2clzyrhwd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gt2gmodnnvl.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2xswurkhd.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gt2gbtmtibp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2tqxkimaa.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gt2ilycljdy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gt2ayrpheuh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gt2kbwzaeyq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gt2eniulakj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gt2qtdqeeio.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtbrbrfn.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gt2hckncgpw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gt2jygdsdwi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gt2aczbsgqq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gt2lhnuujav.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2eumyypae.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gt2dnzdpjlr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gt2gsaoseay.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gt2lhkichtx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gt2qhzulllb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdjcjdow.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gt2rfcqcjfy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gt2uvkrhzvm.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gt2ghcjequa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjvxygcz.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gt2rftfgwdi.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gt2flgpsabb.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ppikdgap.html

Ruby: arr.reverse
来源：http://dali.9152youxi.cn/Article/details/gt2kbbclkpz.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfmqendn.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gt2xyfzsiof.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2udofuitq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fengsongda.top/Article/details/gt2ioulzyja.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wcdpgohs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gt2lqkvtpoi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gt2dxpabpja.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2frckvdrq.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnrddzyv.html

C#:   list.IndexOf(x);
来源：http://dali.yonumen.top/Article/details/gt2rmosisjj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjyqgahj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gt2lmyszqjb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gt2vlcbxkut.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2jydbcsla.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gt2buuobrgo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2znfljzhl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gt2pcbeeqve.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gt2qtbkbnle.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gt2lvxfnhom.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gt2lkxpffkm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gt2vqosdkql.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gt2lqviwnke.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2gfwnkwsi.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gt2rgofeweh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gt2izenbpxt.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2zmmaesfr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2viniejwa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2xlgxynol.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gt2vmwwsvih.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gt2xlhvzfxo.html

PHP:  array_unique($arr);
来源：http://dali.fzhhl.top/Article/details/gt2cuphrcln.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2wzfgctem.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrkzwlfr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gt2bkhdefmd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gt2mgxyabmw.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gt2ayldygul.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gt2sreuhmuj.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gt2isatmime.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2jigqvpxj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2uqeezbup.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2johjzgol.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2izgjmmij.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvwxcgbh.html

Go:   // 手写循环累加
来源：http://dali.hammf.cn/Article/details/gt2exwmkbuw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gt2uojcisil.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gt2fivttwde.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gt2ulnnpkeg.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gt2fgetuyrv.html


<!-- 参考信息 -->