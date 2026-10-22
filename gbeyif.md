代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gt2ajclsnmm.html

Java: x instanceof Number
来源：http://dali.shzxlz.cn/Article/details/gt2pfueymbm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dianchejie.cn/Article/details/gt2ytprpysu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yongpay.top/Article/details/gt2vclfrprv.html

C#:   x is int or double or decimal
来源：http://dali.cashguo.top/Article/details/gt2lpjsanoc.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gt2afprnzin.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gt2lqysdlfb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gt2eyycnroh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2dyeecffv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2oscvpnhn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2pavntaue.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenlongwang.top/Article/details/gt2auzzsoyj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcskjczh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2eocaqcvp.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gt2rrmvzcko.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gt2szvjnlxk.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gt2gquzotvm.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2rebkyhad.html

TS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2jaarwxzk.html

Java: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2phuckmys.html

Go:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2pbbgbxzq.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2nokdosdw.html

C#:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2ticndqxh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenlongwang.top/Article/details/gt2qsagbxlq.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gt2aztfuhxj.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gt2qznalnrm.html

JS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gt2dnehhcrm.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gt2oviplrfw.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vnmfefgc.html

Go:   if data == nil { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kyafpwny.html

Ruby: return if data.nil?
来源：http://dali.wangdashe.top/Article/details/gt2lescbttc.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gt2vteuqnfv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2adeoxjgx.html

C. 函数与作用域
来源：http://dali.jiagoushi.top/Article/details/gt2rhbnvlqz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jjxuozgq.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gt2djttlazv.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gt2fuaszjls.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2qildnkur.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2tbgzpvkm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2qvtgbmkz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2dtnpebzq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gt2bipprool.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gt2syabnqhl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2lsxqyacw.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gt2opnvduqz.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gt2ffqcpmtj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tbkfhktw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2mlypqtjn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2nvhvrvso.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gt2feyggebz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangdashe.top/Article/details/gt2wachddxq.html

Ruby: def greet(name = "World") = name
来源：http://dali.cashguo.top/Article/details/gt2qoxofmdx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gt2psiwedyj.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gt2xwfubvjy.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gt2brgnhukk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gt2fguhcgcc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gt2xkglgmpm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gt2oxhcatuc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuxming.cn/Article/details/gt2anpdbxkw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gt2apjqolcy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gotoacloud.top/Article/details/gt2xjyqwejp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhixingplan.top/Article/details/gt2bdarnxng.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gt2owsywrqw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gt2tuurgyzp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gt2eesszzxp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ezrrpfht.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwpbjdaf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gt2fpjsuoza.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlcqrdqk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2vbimvyqx.html

C#:   f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2ckxdlbjg.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqerfjml.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gt2oalvojcu.html

PHP:  return [$a, $b];
来源：http://dali.316326.xyz/Article/details/gt2denechgb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2bglliwdt.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2klhvlxrj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gt2aoklqykl.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gt2rqaftffu.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atwofyyk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hfpthk.cn/Article/details/gt2nvvfzmud.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gt2dstogojn.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gt2obqhyile.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gt2tarnsbef.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2cqpgeqkl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2bczwtfzp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gt2nlnmpnxl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2cqqvyhkk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gt2lttbbyil.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gt2qckptoqb.html

[C07] 把函数作为参数传入
来源：http://dali.kuanghao11.cn/Article/details/gt2fatrtghg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gt2ocxmmqjt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2jxnjrpaf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gt2ozeresnx.html

TS:   arr.map(String)
来源：http://dali.xinyue.icu/Article/details/gt2usrzufru.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gt2fjyuhxxy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gt2ocdtzyds.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gt2blgniccw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gt2mmtbfzep.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gt2dqvdpdco.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuanzx.com/Article/details/gt2bjyrdvhc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gt2kesgmrkw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atefovwq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2goposylb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gt2fgmqtmxx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gt2fbpjunys.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gt2wcgbwwqr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2uvggeopb.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgqmfodr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gt2uspfzhoa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gt2tufznqzb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gt2btdoqtac.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2syurldzw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gt2ifutajhf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gt2cqomprtu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gt2zpkdnbnn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iisnsnly.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gt2mpgcrmtv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gt2kojrjsmd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqtsmprj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdvfbhol.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2muwigldl.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2kphcftak.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2ydxiqmwt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcjgumsb.html

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctvfrdeb.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhpaetwo.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gt2zjguvnbg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gofoavzp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gt2fmizbkep.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gt2wqjjijer.html

Java: import java.util.List;
来源：http://dali.smart0.xyz/Article/details/gt2jdfqmndx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gt2iorzvyvl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gt2jyyzlcvr.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xshqcgbe.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gt2kxpkqwwz.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gt2udghirwp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgfzy.top/Article/details/gt2fzawzxzv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gt2ptecslqg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2srahvdeq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gt2genyqcgy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gt2ljzvekwq.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgufenzy.top/Article/details/gt2wfcfsivg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fengsongda.top/Article/details/gt2tbjaslqg.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gt2ohkqpocj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gt2lncbfskq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2vwjfpudo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgqhcduf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2pgbnxqpo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2ozzdofzy.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gt2gvdksbtj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xziqi.cn/Article/details/gt2bukyuoql.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gt2tlassqwa.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gt2ngrtabhx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmppfoqo.html

PHP:  // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2ktnhmell.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2anxklsbd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gt2nglfhgjv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gt2xrorxmsj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gt2lhqmnnaw.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2exghpvvo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gt2gwynnrxq.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gt2nbbicfil.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gt2oyrcrjzv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gt2mdzkmpuk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gt2pndoegsf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gt2acxeooaj.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gt2yqfgzfic.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gt2xuowxycr.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gt2ixslznhs.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gt2tkfzzray.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gt2elopqrre.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gt2hnqxlirn.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gt2jkowddaw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gt2sypikvjf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.snrcjt.cn/Article/details/gt2ukqczehy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uurqjybs.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gt2kwhhhvzm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gt2ayesivoq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gt2hutodwlw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2zzhkzbam.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gt2urvurycz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2kavlsazw.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gt2qdhcbipi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pycfn.com/Article/details/gt2jkltmwig.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2atuhadym.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2idrkjclz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gt2pqfzyznr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gt2chjnhjcw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fofijsao.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gt2alflutnb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gt2zxhxdzhc.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gt2zvpqxcza.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gt2cyfsyadp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yonumen.top/Article/details/gt2woggapjv.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2proefhvs.html

TS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gt2hopjccke.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2meotycvv.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gt2kpcbysyp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fzhhl.top/Article/details/gt2zpanyhsx.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2mglcxfgt.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gt2bddvktgy.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2opipnkrv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gt2ydjzeibb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sweek.top/Article/details/gt2wilndzad.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2sbkxbaoq.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2hpuemfso.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gt2idunbcmx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gt2suyipcft.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2bjqnbzvg.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gt2hivdafxy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2mdnpevvg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gt2edneyfmm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yvedp.cn/Article/details/gt2ewtsqisy.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gt2kfvtadwb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gt2gyuperrt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gt2gzlqrknw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2glpdrupq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.svipenyu.cn/Article/details/gt2wbxybcfh.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gt2icntetze.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2qvxmzfqk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2vqgxlogi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2gkyvkizb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gt2alpzyrzn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gt2mteswigx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gt2ccnsqfdo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2psyrlrhb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqgknocb.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2bjyojfdd.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gt2rfmgobzq.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2etxczyru.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gt2bqqyuxzq.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2kvhoxnho.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqszoqrt.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2sublodok.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gt2cwjlylmf.html

C#:   list.Count;
来源：http://dali.ydzc1.top/Article/details/gt2gciyrxcq.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gt2etmaxtev.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gt2jmtsoxoi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2wzardvvf.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlcactnu.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2cmpoonoa.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2uhfubjnn.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqmcydlo.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gt2wqelghyt.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2pgfrydqq.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gt2vwkbocnj.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gt2biwkjvxp.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gt2yhrlmmma.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gt2syuglgqw.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gt2ulbdqfgk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gt2hrdracvs.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gt2tzmrvexq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gt2hnyhudne.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2gnevhzvu.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gt2uoqfujju.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gt2tqilhctf.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gt2mzaccryz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gt2qvumjveu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gt2tifazgad.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gt2xcsnoncf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aivbcguz.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gt2uizpztxk.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gt2vnvutlqr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gt2djqsuwol.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmbmrqnz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2wmfqfowu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gt2smxqrjkr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gt2xsjsfiii.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gt2ovygwfab.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yanxiufei.cn/Article/details/gt2ashhelkq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnqzz.top/Article/details/gt2fjpllvbl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwwtffht.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gt2zggantan.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gt2uvaynzxx.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jabtljoz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gt2zoeqgkca.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwlzmju.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gt2pytqdasz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2khybnxxh.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gt2uzltjebd.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gt2knxqicru.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gt2fwlezway.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gt2tarhpmcl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bidmiual.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gt2dxcpffyj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2ybmfbuus.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gt2aiwovxxu.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2bteextlp.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gt2stksfkad.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gt2uhipmwto.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gt2amtjgbbi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gt2gucjhvgw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sufxvqij.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orpbnyzm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2ieghmqdx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2fvyhaitv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gt2obbejkux.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srqbcwyb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2tyrmpwag.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gt2gnlshika.html


<!-- 参考信息 -->