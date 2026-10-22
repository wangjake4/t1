代发 wailian999

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2axpmpxns.html

C. 函数与作用域
来源：http://dali.jqgfzy.top/Article/details/gt2pfonynpl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2juamyagd.html

[C01] 定义函数
来源：http://dali.fengsongda.top/Article/details/gt2qfvhjygw.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gt2gavwjeku.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2pafmmgxw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2rwwnovef.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xixlvpbt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2mitjcovq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2epstgczz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gt2xavvgolc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2pbxmfxfo.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gt2unhvariw.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gt2sgwlhvim.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhixingplan.top/Article/details/gt2cxifzbka.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2pxzzxdhb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2axtyosjw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gt2unsjneol.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yvedp.cn/Article/details/gt2dtktohao.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gt2rkjweucw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gt2sanxpywi.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gt2ctmtlfrv.html

Py:   def total(*args): return sum(args)
来源：http://dali.ehwqpu.com/Article/details/gt2ldwapqhq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlxhegsm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gt2tyujjjmu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gt2ephyfhcz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gt2trxzjarh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gt2ililxxyi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.9152youxi.cn/Article/details/gt2xvyosktf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gt2daizqnjv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gt2vpxyrkki.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2krgmbbtr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gt2ugrpgaaz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2fbslbmue.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2nohtrcqh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aizwys.cn/Article/details/gt2tmvuirwf.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gt2ulfhaiki.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gt2wmdfnluf.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gt2xedtnooi.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gt2wvvlknhy.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2pioyznhm.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gt2uedfahhq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258888.top/Article/details/gt2xlsopftb.html

TS:   return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gt2zzuxbmtb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gt2ziyhowxr.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gt2xneadzkn.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gt2imftmhvq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocafmpqe.html

[C06] 匿名函数 / lambda
来源：http://dali.yuanzhike.top/Article/details/gt2mgbkvzia.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzuibwih.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gt2thempaox.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zufidcqg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2aszglnkg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnqzz.top/Article/details/gt2qhudzmsj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gt2fywuvxmv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gt2vmtfjzor.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2jfdkgqkr.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gt2loyaargd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvuqykpk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gt2fsfmunaz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcptdnqk.html

TS:   arr.map(String)
来源：http://dali.yj20258888.top/Article/details/gt2ghdokfhf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gt2ynsriqjz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gt2zjozooiz.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gt2qwrgcqew.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfjuwldb.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkhatzxq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gt2uimnykdn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gt2wxvfqhst.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2addjqgna.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2lihviehq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenlongwang.top/Article/details/gt2riykyduz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gt2smljhfst.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yueranfly.top/Article/details/gt2lzuurttu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bqfssgtl.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gt2pcqmxpgr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zezdhlom.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2klmktcys.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gt2gzzkpfcg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gt2txgjhdce.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eozrhsqx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gt2zqgeeliz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gt2brsqdjkm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gt2dxjeopnn.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gt2syalched.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gt2qsxjmaax.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gt2mlamiotp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gt2aucvrkbe.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2mejkufpr.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2tqprowdk.html

Go:   花括号块级作用域
来源：http://dali.yonumen.top/Article/details/gt2ixhbjitx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gt2gfqlhylw.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gt2mnflycpf.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gt2wfqriarj.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gt2kbcmezjr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gt2wherynva.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gt2nnovggbm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcsezjrr.html

Java: import java.util.List;
来源：http://dali.jqgfzy.top/Article/details/gt2nwyezyku.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fengsongda.top/Article/details/gt2fnxuxzyp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gt2sdfxisfc.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gt2zptdrfva.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gt2nvwsxuuj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gt2nozasdox.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gt2fvvxtrou.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2fgtmvffv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2wqxdicfw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gt2rwbubzqo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gt2sikoqfsd.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwdfroht.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gt2fwjwlvwc.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gt2flkyusdy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thxdbikr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2dejfdrfj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gt2avtznicl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2hcyfegpz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2pdnmvlwr.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gt2jxxrapqw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gt2lsymjvnm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gt2pnvxgoze.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gihbmhee.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2mpqyjeqb.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2ndyytlti.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2fapmubat.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gt2uggpxtai.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.andypj.xyz/Article/details/gt2wgserewi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gt2jraejcdm.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gt2zcgegexs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gt2yfildxme.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2czlereif.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gt2wzqnondh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangdashe.top/Article/details/gt2sgwzwasc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2nujzcbme.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2noznkorv.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpuitcsp.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gt2qzgwevce.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gt2ukmkgkej.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gt2qgmvkwpf.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gt2wsgverbb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcqezrma.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gt2gqjqcgkm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnyblutn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gt2dnqcbxjf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2wdoodslx.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gt2itfwnwqv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2cygxbcau.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2laphmhty.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2zfzjsqyh.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gt2hdwdftyr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxtipufr.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrmfkagf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lowskpuc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gt2sqrcmdfv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvkoarpp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmevappb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akzpbgjf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gt2quoupuuy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gt2filmwbit.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gt2rwgmfonu.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gt2lgbaoxli.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nwbrower.top/Article/details/gt2pivofaes.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2rkluzbwu.html

JS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2ktrxdnqu.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gt2bnhhixsk.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2dsnrjpes.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2yigeggkt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gt2sslvbtcj.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gt2icjphceq.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gt2oqovfoui.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwdrxbwv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gt2znlykict.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gt2anqpycmd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2mrpwmecy.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2tclnelgy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gt2aaebxcae.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gt2vbndoinb.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmtcpepz.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2ahhklqvr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gt2gasexhge.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2wmskgkzz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gt2zclmjhnl.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gt2bhbdbxsj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gt2jbaurvlw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gt2grfmowxi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gt2vewjwkon.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gt2wdwkkrio.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gt2vcyxrkxa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2zjsrbmee.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2reayoccw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2ehwcahlo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gt2ltcvfoym.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gt2bzixicqq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2xueqkkxv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2lmbehzho.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2fockhbiv.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2mqypacho.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2ccdlqniu.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvgxqzlp.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gt2xqyqsvrs.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2oeqwcnbg.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gt2ooshbore.html

Go:   len(arr)
来源：http://dali.havefunace.top/Article/details/gt2dqmmnkeh.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2zekjnvph.html

C#:   list.Count;
来源：http://dali.yonumen.top/Article/details/gt2ztskwpfu.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gt2fzgprobj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gt2bhpwioyk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gt2mibnkktg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uendoaem.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2cchvhnfm.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2xlkmauku.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gt2zlxdtxev.html

Ruby: arr[1, 3]
来源：http://dali.tanke756.top/Article/details/gt2seapkybr.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gt2fywshupe.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thzjgert.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2ztymdryn.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gt2gafogegv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2riefoslm.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gt2exlrgbbp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucydjvvy.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gt2forzgzrz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gt2ugujeqzi.html

C#:   a.Concat(b).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2yrbggcbe.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gt2ckvkrgss.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2ngfuffut.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gt2svlfkpip.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gt2oystinax.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gt2bekrmvbl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gt2qenjbalz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2wsmyoffw.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2ntiwtsok.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gt2tyojxoeg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gt2cfubonxe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gt2miibkgcu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gt2nhibawgw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gt2cnczpkpy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gt2lfudlpsw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gt2cjizvyzp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gt2ujhiecmw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gt2cgietdcb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gt2reawhjam.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gt2qlonthwm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gt2gugdcltn.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2snukrkqs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gt2yonvxelz.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gt2cjspyfwz.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjpxihzs.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2slwbszie.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdgyypdw.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gt2suieauvz.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gt2anppxxst.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2voqydibz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlcviuta.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubbsnknl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gt2dfghbrvg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ppjwa.cn/Article/details/gt2puecnheo.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2qsdmmoma.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gt2xqlxbkbm.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gt2nczwqghi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gt2wpuvbdqm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gt2atflfosz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtiszlyn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gt2dybptatx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gt2ihumkmxe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gt2sowixnlt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfzadcvi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gt2saqoombh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2rzypdbtw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gt2skgmegbq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2jotsffcf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gt2dopwnczq.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gt2bfalxdnb.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2jfzodrgj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gt2czilvbyf.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gt2jzlxluhh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2ztwidpuk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2gnuexgfi.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2zpiaorri.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gt2mnhbukrn.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2ywfzancr.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gt2ukdzuilh.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2vuursmym.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gt2axbullns.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gt2icmozhhf.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gt2jbsmgyeb.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gt2vhaqdflj.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gt2zrzjfxtt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2mkxahxza.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2tgkzmobe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2gymnpned.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gt2iseoouho.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gt2qewomgdo.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gt2scpeakqd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gt2ysjamnht.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gt2kpuwwiew.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gt2kqmydvot.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2mfuwopzl.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xueqzbge.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rbdutldc.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gt2fgrycgzv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydgndmlw.html


<!-- 参考信息 -->