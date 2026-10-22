代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2zgmxfxew.html

Java: x instanceof Number
来源：http://dali.shzxlz.cn/Article/details/gt2xhdnqqkc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yueranfly.top/Article/details/gt2dkevqbtk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258888.top/Article/details/gt2wwapcfss.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gt2outvjmyh.html

[B14] 判断值是否在集合内
来源：http://dali.yonumen.top/Article/details/gt2nmyehzkv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tianlin.xyz/Article/details/gt2daambcue.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wznhgzho.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2farlegko.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2gbborrpw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gt2kiolprqg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2znrsriop.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2grbohaen.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2hilhtnmh.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gt2odbeuzbw.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gt2zixtvvjq.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gt2chywbgwb.html

JS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2foorsmix.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2ncqxjroj.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2zcmldgkx.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgimnyal.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2lwgjgept.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2rvonsxrr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tianlin.xyz/Article/details/gt2wzjfiqzc.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2keidufif.html

PHP:  if (!$data) { return; }
来源：http://dali.yangfankeji.com/Article/details/gt2dwpnfrqd.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gt2vinfgzlc.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gt2dtsdqser.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2kfsyiytl.html

Go:   if data == nil { return }
来源：http://dali.hnxiangtu.top/Article/details/gt2nuvcxral.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gt2hgcunbnt.html

C#:   if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gt2rfypvyan.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ienzovpr.html

C. 函数与作用域
来源：http://dali.guannengcc.top/Article/details/gt2ztrhymrs.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ueuhcewz.html

[C01] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gt2ovissfqj.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2yyabsfqm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gt2wsvqrvoy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2pfzmzbaq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2cxeuzdsi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2sgimhvko.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gt2urmblnsu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gt2kruldlsz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2czkphbfb.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gt2jggqxrpd.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gt2trjxmhvq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daria6918.cn/Article/details/gt2swwkxuaz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2virjnoam.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hazrbdop.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gt2iipaonrw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tianlin.xyz/Article/details/gt2iyijammn.html

Ruby: def greet(name = "World") = name
来源：http://dali.jyoumei.cn/Article/details/gt2bzcospej.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gt2zjbavsdr.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gt2uwttmuqa.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gt2weuxykwe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gt2zdrzomhs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gt2ffsnbump.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2oqoygdos.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2urjldiim.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gt2juspbbrq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gt2bopzolna.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gt2hpuvrhiv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yueranfly.top/Article/details/gt2lhayblab.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gt2ihwwrlau.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenlongwang.top/Article/details/gt2jhujxvcl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ptaifdnu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gt2yfcoppkc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gt2znwwsxct.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywhewlvs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2okibukrl.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2otwechtu.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gt2flawkimu.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysuphbhx.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gt2hkzboqhf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gt2pwbpmjwi.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2hgppxryi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gt2askzdfwo.html

Go:   return a, b
来源：http://dali.xziqi.cn/Article/details/gt2sdtnnets.html

Ruby: return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2bvqbykga.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gt2ehidlgxx.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gt2fejagxev.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gt2kxitykvc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gt2yzkwbxpm.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gt2hlwoplfg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2jitvwgit.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2icvpymxo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gt2pvlubedj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gt2kbnqrndh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2vhxpcwwn.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gt2ieqtxgmp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gt2hrrtmffm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2psyltenb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yangfankeji.com/Article/details/gt2jbvsxsbz.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gt2dwifcvew.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzoafhhr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gt2bajncokd.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gt2wocfpfpn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gt2unrxzuvw.html

[C08] 闭包
来源：http://dali.ybcxt.top/Article/details/gt2ynnnfjiy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ydzc1.top/Article/details/gt2uwygfmzv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.andypj.xyz/Article/details/gt2ngkxfsdi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2dkzvtklu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2itrgnjrq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aizwys.cn/Article/details/gt2qnozrxau.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gt2pylpddri.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gt2qocqufip.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2qizvdyxr.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gt2bhwyvxna.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gt2rpzhtruz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gt2kunpcepd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gt2ualjxylg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gt2rjhqhqsu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btlxooiq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gt2kttnqpqh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2jtpcdsnh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gt2tvsyzpwf.html

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2currshbd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gt2kdycavco.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fengsongda.top/Article/details/gt2uyvoblya.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2kciclqps.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2aukvbcxy.html

Java: 方法内为块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2fdemuyah.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2lqtlgohv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gt2cpairvjb.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2nwxtqtvn.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gt2mdaoqhnc.html

Py:   from module import func
来源：http://dali.nanxinkj.top/Article/details/gt2rrsdmhzq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gt2enwzcgmo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gt2vuhpszbw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjjudmxr.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gt2umcllqak.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2csqfuvvv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gt2ulyvljhu.html

C#:   using System.Text;
来源：http://dali.aizwys.cn/Article/details/gt2drpvdsgh.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgufenzy.top/Article/details/gt2zuhrducv.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gt2kocejksa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gt2rlttomge.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2vyfbapiv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2fjdcveui.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gt2dkjnkhsg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gt2exlwdxxq.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmolzzyr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2jobppobp.html

[C13] 类型声明 / 类型注解
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mywvlmlt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2djoawvye.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2msvdemlf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gt2aprwkjqq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2jmpiabca.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2fmexpbtt.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gt2mgzjtbnv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gt2gtosgdqb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erkwzkpf.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gt2eftqcgqt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmamblgo.html

PHP:  // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gt2qzdqwkey.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2rcfbmhof.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gt2iehovhwg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbglrncf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sweek.top/Article/details/gt2dkymipmg.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gt2dheiqxvd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gt2delatnzb.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gt2cmijwawh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gt2znslqfxl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2atoyowux.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpwzfbjv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qhsmospb.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gt2xivbgkxj.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gt2mabliixv.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gt2pzmropcr.html

C#:   var (a, b) = pair;
来源：http://dali.svipenyu.cn/Article/details/gt2ascbahyd.html

[C16] 函数 / 方法重载
来源：http://dali.bjfxy.top/Article/details/gt2gsnsukar.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2aubtqhxr.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gt2cshutmwf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gt2xiikxswk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gt2oghvjbnv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2nuxkongi.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gt2eaeqjtym.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gt2hgnpgzug.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khlmlfin.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsqcihco.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gt2zddwbjrv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2dldoaees.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gt2nryjmfmp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gt2edqfthuk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcxsncci.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2vtfgukrt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gt2itwdivbg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuanzhike.top/Article/details/gt2gdhnhvck.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gt2powdgslf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gt2vxflgqfg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gt2zqcjkvly.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gt2kwkezptv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shzxlz.cn/Article/details/gt2sydkonoz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gt2acreeyia.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gt2erqhsqgn.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gt2pspfcmee.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gt2rozbmqmd.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2qqleohil.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gt2tgbqabeq.html

C#:   list.Add(4);
来源：http://dali.yj20258888.top/Article/details/gt2fvjukpjm.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gt2zhvbsfnx.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2uzvorvbw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gt2ukyxkqoz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gt2jphetmgj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2gapppmia.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2gvfmwdcb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxinkj.top/Article/details/gt2srvmrxcx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gt2wtevpwes.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2bnoxulqo.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2tgclzwjr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjclyora.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbmhcxmo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuanzx.com/Article/details/gt2uhldugvs.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gt2njpybqee.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gt2oaiifpaq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gt2ihjkgtjl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sysykeji.top/Article/details/gt2fmbwqczk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gt2nrdijkct.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gt2tgefusal.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2llsiunro.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2ljcqnqro.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxdcwwr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gt2jgvueaxs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gt2fmjkyqws.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2yykpqiuq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gt2oyhbihsk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpumvyyq.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2ftvvwgxn.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pakkrtcl.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2dvqvlran.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2kknzuwxq.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gt2vbbushqc.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gt2evdshyix.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2ausacxer.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2biotxdaj.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gt2dmytgduw.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gt2jujbzgiv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gt2ebotihng.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gt2pimmuobh.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2iobsraka.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhgyinsv.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gt2mngivzzf.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gt2qhnyihbc.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gt2wfyqxoxc.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2gsnrfcke.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyaulwnu.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gt2rhqubeoe.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gt2hgjucetd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gt2fmvxzuxf.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gt2qprmmxiz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2fiuiauqn.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gt2ehsputso.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enaensbf.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2naxakgsy.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gt2awblwhhb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2bedmehka.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2mckpblli.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxwrqonz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hammf.cn/Article/details/gt2mpqybpap.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gt2ftpjekso.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2knrktcqk.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gt2nvjsnjju.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gt2xrchunes.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gt2rxctegrq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gt2xhmctuzo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gt2sgdpnkgm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gt2qldexovw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2zzrqojqd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gt2vptwseeb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gt2ustuydbz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwmivcbl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqwjyuvc.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gt2kztpcivj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ckxzuzfz.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2isnfxpzb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gt2lpzupcdi.html

TS:   [...arr].reverse();
来源：http://dali.zhoulong.xyz/Article/details/gt2lygptkto.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2cacxpkjg.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhfwvtlc.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gt2zcnnnajl.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gt2ccvurttc.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gt2miwuxlbo.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjkuipcd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gt2mpihwech.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gt2guxgavky.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2qxbzbhlz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gt2mwgwmfhe.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2bdlwwomf.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lulhomgv.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gt2pverkjup.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gt2ykptdxeb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gt2fnrqhhxw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gt2vmookpxr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gt2zqqfnlel.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2qrwyyxdu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gt2vxeperte.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkarhgvc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gt2uljinyby.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2yutgxehn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gt2boaxwobs.html


<!-- 参考信息 -->