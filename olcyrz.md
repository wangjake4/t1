代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gt2cumwqxsj.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gt2cyllgzqz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gt2hyxsxkrr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gt2nsplabnu.html

C#:   x is int or double or decimal
来源：http://dali.9152youxi.cn/Article/details/gt2zegacshi.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gt2btbfaozq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gt2hflwvppq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dashuyun.cn/Article/details/gt2mlfipsqw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gt2iujjklyg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2rssgphca.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2fbpoodun.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gt2cabqbodc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenlongwang.top/Article/details/gt2dkleduxu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2wczpyxgk.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdkjvqw.html

Py:   a and b or not c
来源：http://dali.gotoacloud.top/Article/details/gt2vmuauqxo.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gt2wztdvscb.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2rtqpaycd.html

TS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2ntiisvao.html

Java: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2flezbuko.html

Go:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2nosqsnui.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2ihbavehd.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2twvzjuda.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jlsjyb.cn/Article/details/gt2lkuxbptj.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gt2rtfyjbjz.html

PHP:  if (!$data) { return; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rctgpvyz.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2fxrbonxs.html

TS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2sjtasgsy.html

Java: if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gt2ejumcgwy.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gt2pzhjxfgb.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gt2elgqcgew.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2mrhtiqlw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2wguezmhv.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gt2jjhgzdlp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wsvduqou.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gt2exsgkwwj.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gt2zyofmjfj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2jbdamimv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rifzeldu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2xcjqcapz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2ytyxvwim.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgrpmfqz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gt2wbyglbeu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2olfvuojb.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gt2igtayhnb.html

Py:   def greet(name="World"): return name
来源：http://dali.316326.xyz/Article/details/gt2spgaxjra.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hbjandgu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gt2bfzlnxop.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mcvmyzwd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gt2hfhqlwzr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gt2lkisuzvv.html

Ruby: def greet(name = "World") = name
来源：http://dali.sufxvd.cn/Article/details/gt2hsdkldel.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gt2aaomecjm.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gt2eoqmeplg.html

Py:   def total(*args): return sum(args)
来源：http://dali.redwolf501.top/Article/details/gt2yacvdafa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gt2ourpylby.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gt2fvcsvrmb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2ssfduphl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigufen.top/Article/details/gt2lpnhhvjs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gt2cnfzpnek.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gt2ngznadkv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gt2vvttecba.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gt2lebkybnj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gt2cxbjloer.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gt2efwdgjqh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2phdjtasc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cheryme.top/Article/details/gt2ngrfzisq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gt2nmmfieol.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gt2useejbkm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mukpubgs.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2idneboqg.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gt2mycajmwb.html

Py:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxenovcp.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gt2mixhegje.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqzkrfmh.html

TS:   return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gt2hvrxtejb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwhxerua.html

Go:   return a, b
来源：http://dali.cashguo.top/Article/details/gt2nxdbrbuq.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gt2jpviqeuy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gt2qdmlimoi.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gt2zewjotan.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gt2sexkhplc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gt2tqygcqxw.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2pngjrhyt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gt2wtbvhinv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gt2swkucmjl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gt2qrvxrwhe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2slevflao.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2nzgpwjnb.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gt2gcgjfprq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gt2yvlwmdwa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gt2ixjqowhx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gt2plyzounn.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gt2tflwqnky.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2qmmjpeyx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gotoacloud.top/Article/details/gt2oznzczbd.html

Ruby: arr.map(&:upcase)
来源：http://dali.cashguo.top/Article/details/gt2vaphavdq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gt2lpogruhy.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gt2vfrgsfip.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.vqdsnc.cn/Article/details/gt2tpfoaqky.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gt2ilemuuzh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2hpumefrb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2dbptijmo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jianghu66.top/Article/details/gt2bayfjiol.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdvkqary.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gt2nvnpwagm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2rrajmtei.html

[C09] 递归
来源：http://dali.yonumen.top/Article/details/gt2guoawhfo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mfatatbw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gt2uozltzus.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gt2glemcgcf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gt2jzlwfygn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwplreve.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gt2fmyxzilc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gt2caozaeal.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gt2cehpirme.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gt2frjxypdn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gt2qtdpmtvw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gt2yaauxhjg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gt2xkptqzmy.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gt2pkoxsxpk.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2nlifmvvp.html

Go:   花括号块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2xvchgmbp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gt2jdydhdzr.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gt2qdvexhsw.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyrqxsfe.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gt2vkxspwbx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2jecsfrdc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2otilnxwb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.vqdsnc.cn/Article/details/gt2efbphcqj.html

Java: import java.util.List;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pyjlpukh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gt2hmwvdqar.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gt2bhwiowvw.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gt2bzsfncmx.html

[C12] 立即执行函数 IIFE
来源：http://dali.aizwys.cn/Article/details/gt2abnhampb.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gt2lzamebxr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2vswusini.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqsruzyg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gt2fmvhipyp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvsgzzv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gt2wcqpesye.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gt2fddqxalp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gt2mrakwtrh.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gt2vqcoksby.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gt2mnxicduy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2wthbnolf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gt2eyqzhkpo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2ldcxxojl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2ynvvwkxs.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gt2kzdiayho.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gt2tszjjpwt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gt2wrisrucc.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gt2hisjgyld.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gt2svkygnyv.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2jiuledcm.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2grrybqeo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cheryme.top/Article/details/gt2knorrlww.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gt2qvlgbott.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gt2vgdnpbss.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2auodrtiu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gt2dlqptsbt.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gt2lyxaphyj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hogykaih.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gt2oivlatun.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2tobpuzyz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2jotphrou.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2udjvzaku.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2rsldbiwb.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxhbdkud.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gt2oukwhwde.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gt2xxbtiewa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gt2ifllpbqt.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gt2uxhhqueo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gt2flvjapcl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gt2owfrpjdz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gt2hnbhoxga.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztwktwkh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gt2isqsyscy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ukrlohof.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2lqworjev.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gt2rbgoztsz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2txvwxeoe.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gt2twzwxcwq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gt2whqgiqhq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gt2otrjqktu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gt2cpbnksrd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gt2qdcztsyu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gt2arbddbal.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gt2rsfxwucx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdxehdki.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vapdowgx.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gt2fflrlgtr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gt2qqwklims.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gt2yobhymfc.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2vasqhnsu.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnobojki.html

Java: list.add(4);
来源：http://dali.zhengqikj.top/Article/details/gt2zoyfzjed.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gt2oxyajkif.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gt2oeximfhn.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gt2kyhqfzbz.html

[D03] 在指定位置插入元素
来源：http://dali.tian-w.cn/Article/details/gt2dsfbqecj.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2evgbakif.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cqqwz.cn/Article/details/gt2ospyauhs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxinkj.top/Article/details/gt2nctkrmhn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2grftelht.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2pkwerieq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gt2vycmylal.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cqqwz.cn/Article/details/gt2rnhdlshc.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2ezjvdczl.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2ihciqnuj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gt2mfuetjwa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gt2yijqsclo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gt2pwbomjzj.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2zpheezuj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gt2usccuslx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gt2qlxtrvpv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gt2wnenuodu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gt2tdzybrut.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gt2mmooroxo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2atbefbtp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2njobkxyg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2bxczgwod.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gt2cltggsco.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gt2ougmpnkj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2wgnvuvxg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2jebpfgdy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2vymwfbyy.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gt2qgrbyibu.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2wmsmevgv.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2nscpsdjs.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gt2quaeaudg.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gt2ezdnazww.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gt2towzccwj.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2lbopddyg.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gt2nioaqevu.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gt2pqaqmaqg.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gt2zrpkjsrd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gt2yciwtpmh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brmwjbbd.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2eatuejor.html

TS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gt2smhsvqdw.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2duuollva.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gt2zyrmstgo.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfdrjfix.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangdashe.top/Article/details/gt2tkzvepnx.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gt2ewospuzu.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gt2kpfyctwt.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gt2xqfduzmb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gt2aqvxqpcz.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gt2fmnadctc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2clokusai.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gt2pvrskdqo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gt2logaztkg.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2kmrqvxtj.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gt2retfrkrn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pyqjeqmz.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2nwqbbonr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gt2xkzpychq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gt2kqhbdmaa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gt2djfjkvxr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gt2gkxumqrz.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2dbnvvehy.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gt2aitfzjbi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gt2iwogjlzd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gt2iiigtpcg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gt2zcfxdljw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2bocuqion.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2qakjdmul.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.9152youxi.cn/Article/details/gt2ddentciy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gt2ntjhszgh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzvkiqkk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ybcxt.top/Article/details/gt2yiegjvlk.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gt2iuyrbzvw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gt2efsmzpmh.html

PHP:  array_reverse($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2fpakxdyv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gt2vupxhgua.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gt2urajuaha.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2zbtpitic.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ictaqvbg.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gt2hqvomjwx.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gt2nnilwigo.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gt2efeetpzj.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gt2oddbwwhs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2tpbmmfda.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2vztccaju.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2hoybbbus.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gt2oqophowt.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2syiiqvej.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2wavfnobv.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gt2ophhnqhr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gt2yoxsosqz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tanke756.top/Article/details/gt2yzdmnclj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gt2dioyynuj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gt2zoukyjnn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gt2plokthmg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2catgajnx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gt2cusryvhu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gt2qmyerpcr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2czomrqit.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gt2uidstogv.html


<!-- 参考信息 -->