代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gt2dcldavkw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gt2yqivtxna.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufsgxtaq.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258888.top/Article/details/gt2ofigqwsc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2igwuewii.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gt2xzjyqlzj.html

Py:   def total(*args): return sum(args)
来源：http://dali.hfpthk.cn/Article/details/gt2bourbbvc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orjmlunz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gt2lwcxmigd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2hxwxonhh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gt2xprjykey.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gt2btcgchtn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gt2mmwfdwjb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.havefunace.top/Article/details/gt2mpxrqszr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxyroxaw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zllywhgs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gt2gqkbkjio.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gt2qhogtrup.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gt2sfphtqvk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgufenzy.top/Article/details/gt2mobmzucn.html

Go:   // 无：用配置结构体参数
来源：http://dali.aibaodan.cn/Article/details/gt2plfgjtda.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2vunmofwy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zczfjodl.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gt2uwqjsklb.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gt2jgwmmvpq.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gt2utqyfnrs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gt2qdjavmcc.html

TS:   return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gt2fluniqpt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gt2cmkbnahj.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2pyfgdnnq.html

Ruby: return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkkuvbuc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zdqjudy.top/Article/details/gt2tyskjmnq.html

[C06] 匿名函数 / lambda
来源：http://dali.xuanzx.com/Article/details/gt2mztkhcuc.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gt2zznxuvxb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gt2lkyolisi.html

JS:   const square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2vaakprnx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2yjuzyfkf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2swyrlhju.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gt2fhgmlnxh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gaohongyu789.top/Article/details/gt2pyppxqjt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2vyjlulls.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gt2dpzrtoba.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gt2hccziqix.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2wuwhbkqc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gt2zrmqykfw.html

TS:   arr.map(String)
来源：http://dali.cheryme.top/Article/details/gt2yjepdrfe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gt2njzbqott.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gt2qjuyaihz.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gt2dywgtoat.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gt2ziloonph.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gt2rskpfsfs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gt2auylbrta.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwqurfui.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2lqwqmtxq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2sffcplgt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gt2xkspdfoe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gt2ojvuqosi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wldhxhcb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2ftwkdidq.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gt2mtqdnwhj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2qxfztggh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daxiang520.top/Article/details/gt2bhralppy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gt2xjnuamqo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2gjwqasgr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2hfygwfzt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gt2pfvxdmte.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yogycfkm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gt2kgpfdsnd.html

[C10] 变量作用域
来源：http://dali.jqgfzy.top/Article/details/gt2yymaaeeh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gt2plybhydf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gt2ckvedqpb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2bihqskaq.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gt2dudvytmn.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2kmnyxdkb.html

Go:   花括号块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2olnjedmy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gzhubu.top/Article/details/gt2wrmbimqj.html

C#:   块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2elqvikxz.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gt2wtugwfms.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gt2parznsvk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gt2ssbrmoso.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikcttogq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gotoacloud.top/Article/details/gt2xuyioxvd.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gt2arrdjttc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gt2acphbgyq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sxryk.cn/Article/details/gt2mizzlwzo.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gt2jkgnipja.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbypoqdk.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gt2tmitbdud.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gt2blvhtphl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gt2npwfgxmb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmfypiid.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfrckqeb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gt2beunwooh.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gt2xzxmigst.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2rojuvgmj.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gt2abfbcynl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2dulyqlgq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gt2cvzmvtlf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gt2aysabrwq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2ixwrydxa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2okgnyvfu.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gt2pnjwvnny.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gt2lyqbfhzf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gt2pgwlwixy.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gt2hrsguyht.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gt2cbkvslas.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekpzxwbk.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndqpztfx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gt2wrcfdyhe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gt2vybghyqv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gt2gmknvujk.html

Ruby: # 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2auxntpgp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gt2kbxtmmvc.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gt2xyoyplcx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gt2qbywnhbc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrzvndgz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2lnmhsemr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2tomjbiey.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyimbbtt.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gt2oeoblstv.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gt2oxrxkhxf.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gt2zwbbzxkf.html

[C16] 函数 / 方法重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qilvmuzo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2whliwkqb.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gt2lyrbkkjk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hfpthk.cn/Article/details/gt2wnxjjgiq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gt2saxdjekz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2turolvno.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gt2tylpicdk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gt2ynroobrl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ppjwa.cn/Article/details/gt2ygganids.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2cdcmavne.html

D. 数组 / 列表 / 集合
来源：http://dali.cdnleiting.top/Article/details/gt2mqdgiyst.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2qljkwkww.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2xazcpilp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gt2pdsaupis.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gt2wsnryzkk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gt2hkltgkei.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yonumen.top/Article/details/gt2cqvwfddi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjumtyxi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gt2gkuggwml.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gt2cslzfxfb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gt2gmzpyrax.html

[D02] 追加元素到末尾
来源：http://dali.tianlin.xyz/Article/details/gt2rsmcmprb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gt2royjushs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bejbytnk.html

JS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gt2xvzmojjg.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gt2nevrrwmc.html

Java: list.add(4);
来源：http://dali.jianghu66.top/Article/details/gt2efibbrbh.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2meqakzdt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.redwolf501.top/Article/details/gt2zkjonuau.html

C#:   list.Add(4);
来源：http://dali.yj20258888.top/Article/details/gt2ssghnxlp.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gt2zblzfmqz.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2tyxcdses.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gt2oelpcdkw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gt2wpugkejx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysteyzqj.html

Java: list.add(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2cxmmdrel.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj202588.top/Article/details/gt2fxbmiwtj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhixingplan.top/Article/details/gt2iljbswzx.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2spmcjivb.html

[D04] 删除元素
来源：http://dali.yanxiufei.cn/Article/details/gt2yblzejkh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhengqikj.top/Article/details/gt2kcumnpzi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2iihxmjes.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zdqjudy.top/Article/details/gt2imojqnmd.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2xvhzoset.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2bdywiugg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzojapg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gt2nighdtwd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gt2cwslcxsq.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gt2ftgmjrpy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2ygeidtzk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gt2yvvmtwvt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gt2okdntymv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gt2zdesyhvu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gt2fvenameg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2acjihgqw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2xcqmvbto.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2zljazamy.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gt2qpqtilao.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2xjuphjwo.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2ajcpwbpb.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2thzfvnix.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gt2pvkixmhg.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gt2sqtwzsum.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2msjiwshz.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gt2hyomuctq.html

C#:   list.Count;
来源：http://dali.havefunace.top/Article/details/gt2krkkpkix.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rubpeqkj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdwnywwm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gt2jhagrvup.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2qbymxmer.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wibvifxb.html

Java: list.subList(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2pjvynxel.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gt2ghrrxzhl.html

Ruby: arr[1, 3]
来源：http://dali.redwolf501.top/Article/details/gt2adaisenj.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2ycvopsfk.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gt2pndavjqr.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gt2quyleulz.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gt2etrwctpm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gt2ugntfpfi.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnmfosrx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gt2fxxoiyzz.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgmiecqt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yongpay.top/Article/details/gt2niqmlada.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gt2ppmrpmge.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gt2wnfyvbrt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2xexbunnk.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gt2zwqaltek.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gt2yebnmyol.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gt2nkbgaqkp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gt2vjkgzwki.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2fyluzumg.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2egryhmbe.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkcvjpwg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzvwtahs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gt2jfujuxgs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gt2ngeiicfn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwapvxcq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gt2nfpugitt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gt2iyuwhbor.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hammf.cn/Article/details/gt2nwyebnkx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gt2tjhtgxrj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gt2spwtvhjx.html

[D11] 反转数组
来源：http://dali.bjfxy.top/Article/details/gt2xndojiwn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gt2cffvkipt.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gt2vzfaoenx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gt2scnhxekj.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gt2fccnmgfk.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gt2ykvriwxy.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2hzjrsmfc.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gt2uynhhdjy.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbnticek.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gt2hneffglh.html

Py:   arr.index(x);  x in arr
来源：http://dali.xziqi.cn/Article/details/gt2wowlakbp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gt2xvjfbqpc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtiykpxx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2vcwzholh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgzhtqtl.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2rpjsvekc.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gt2jqocmfym.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gt2monjvukd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gt2mbdnpqmu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2qcwwutcg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gt2kgkkxekf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrssjvu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2wznrufgc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnqzz.top/Article/details/gt2ggbbhbng.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.mhx1999.top/Article/details/gt2cnkoahgg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qedefikk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgjtucpg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gt2jpgsjsqs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gt2lugvzlsx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2papyflzq.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2pmuscruc.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlicgkce.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gt2thhwqvjx.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gt2tubjadvt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2drpksesq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2numkdzby.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2qherspjj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2tujpbkws.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gt2bhpjddbp.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2crhyvqor.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2jaekshkn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gt2kjctemdi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gt2uorosxop.html

Ruby: arr.uniq
来源：http://dali.nanxuanxn.top/Article/details/gt2ccpxqbug.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prsujmnq.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gt2kagidcst.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2uswfwkok.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gt2uvyajyhc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gt2repcrmvm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2xjpyfmka.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gt2qzqfehlw.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gt2vodgbcfa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvtzscwc.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gt2ckqoixmv.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gt2qaaqrjon.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2qvoycwhr.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2restrvuc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gt2euqrsadw.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gt2ghltindo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gt2kjsgjvlq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jpjcelky.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gt2myhrzdgd.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gt2zwadfmjf.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gt2sfhtdgju.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gt2nmefbcnb.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gt2gbueecsc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwuenqwx.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gt2nrflvovm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2pihritpk.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2msjqkcpf.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gt2oqeyxkli.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2weblygih.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gt2wtuvisyq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gt2bshjzhll.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gt2wylvuhce.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gt2yxhsjcbs.html


<!-- 参考信息 -->