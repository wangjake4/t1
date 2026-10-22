代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gt2pnauhbtd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gt2ibviavuu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2vmlcwzlh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lexcyeke.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gt2yznzknyo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gt2emlpmkjy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2ctudjnut.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gt2whqcuuuz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gt2pyoilncs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gt2oytlqglg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gt2zuuowkjs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gt2ihfuwpfs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gt2ejckeime.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqozfgvm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hammf.cn/Article/details/gt2tsrcfqzo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gt2hgbzqtrl.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gt2ivhzycug.html

Py:   isinstance(x, (int, float))
来源：http://dali.yangfankeji.com/Article/details/gt2xxrcsibk.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gt2xfardqko.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gt2avdnyhhf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gt2vbtqiigd.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gt2nhcycsnm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shuidangran.top/Article/details/gt2slqkrwdq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenlongwang.top/Article/details/gt2aelrneek.html

C#:   x is int or double or decimal
来源：http://dali.sweek.top/Article/details/gt2dfxrqhih.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gt2sasumbqw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gt2bemhsksq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gt2tusbttoj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2bfpdhxwe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2yxolegsq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2jwayqmsz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2eligbmde.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sweek.top/Article/details/gt2jkdbnhgn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2ucausyrf.html

[B15] 布尔运算与取反
来源：http://dali.nanxinkj.top/Article/details/gt2dywkkojx.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gt2qfgapwbi.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gt2fylohikl.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyhnrtbi.html

TS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2xzhujhyk.html

Java: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqmpkuye.html

Go:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2mnlgvfrk.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2fwqlsquz.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzhyucfk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuanzx.com/Article/details/gt2xyrlkdbx.html

Py:   if not data: return
来源：http://dali.ydzc1.top/Article/details/gt2frfkzete.html

PHP:  if (!$data) { return; }
来源：http://dali.pycfn.com/Article/details/gt2geniwkyn.html

JS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gt2mdgkdivk.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2vspafqiv.html

Java: if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gt2mycsirmb.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gt2euxrbunt.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gt2menhghhj.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2ylsdzmjo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2fcdmyokg.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gt2btqbonyp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2qqoujcfk.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylsbziuj.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gt2kszevusf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fgeuekqy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2nvgprefo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ctehpoxz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2fdbikcot.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258888.top/Article/details/gt2dmwvbqkw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gt2wwxyagqf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2cehkqqzx.html

[C02] 默认参数
来源：http://dali.yanxiufei.cn/Article/details/gt2kyjvjzmn.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gt2jhyvxrqz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gt2jgxswnfn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbwcqdsh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnxbkfyg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gt2pmomljax.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gt2vsuhmlsd.html

Ruby: def greet(name = "World") = name
来源：http://dali.jianghu66.top/Article/details/gt2pxqybjjs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cashguo.top/Article/details/gt2giblzzav.html

[C03] 可变参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdtcelwz.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gt2jypjtyyu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhenzobf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2tlgnbvem.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gt2lpwasrre.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gt2emonighr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gt2ddmvkxbj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gt2hoqwlgwj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.havefunace.top/Article/details/gt2tocxbbjh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gt2ttqjxyxf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gt2bsksejxj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gt2sgirpiav.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gt2zzgikvzh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gt2yjnzinpg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gt2zkccvphu.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2liamfjqx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2iayrinvs.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gt2ydlbhglc.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gt2joqmaxms.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2znkdqbgp.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gt2ugzeynbk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2rjentxlh.html

TS:   return { a, b };
来源：http://dali.sysykeji.top/Article/details/gt2gcqejtef.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gt2odcsrgdo.html

Go:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gt2gafjinwf.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2csvdhfwe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gt2ozsyxvfu.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2iheykdqn.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gt2chzdvvhi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gt2lbbfqaay.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2anuelcmb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2nwasgnej.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2xpxykqlx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjlhgrvm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gt2qrmtuutz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2eeyasbqv.html

[C07] 把函数作为参数传入
来源：http://dali.meibo888.top/Article/details/gt2ebxlrwmp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gt2mnyakgxc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gt2pfzdnnyt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gt2loqfikuw.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebjwurff.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhrxbmjy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gt2wzxbnugw.html

Ruby: arr.map(&:upcase)
来源：http://dali.tian-w.cn/Article/details/gt2blmgmztl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gt2urttphru.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gt2oseelkhn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gt2texvybqy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gt2vwgydtsg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2tmrgwley.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gt2cwnqgnxz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gt2comeabex.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gt2qdcxuvzh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btpicxca.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gt2xaudvofy.html

[C09] 递归
来源：http://dali.fzhhl.top/Article/details/gt2xehgjqzn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2vnvjpdyo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gt2hsoaqdsd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2fbkaxtaf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gt2cxndjoka.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gt2tflkiaym.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sufxvd.cn/Article/details/gt2kzybrcjs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gt2zkdaeqzw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ydzc1.top/Article/details/gt2jgfpaize.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gt2ufcatwdb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shuidangran.top/Article/details/gt2huuynooh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gt2kpviwhqx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gt2szcknkkd.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2rgerlqtr.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2etyxbhkh.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2nadmgrli.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gt2dkljeklg.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvbuobvk.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gt2durrzgbd.html

Py:   from module import func
来源：http://dali.cqqwz.cn/Article/details/gt2lgxkkelv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gt2kgejnrls.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gt2prttloyb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gt2vksmuzfl.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gt2enqcbeia.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gt2vgpbslvg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gt2cioeesmu.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gt2nhynxrbg.html

[C12] 立即执行函数 IIFE
来源：http://dali.andypj.xyz/Article/details/gt2aqchqxli.html

Py:   (lambda: print("run"))()
来源：http://dali.hammf.cn/Article/details/gt2ljbnnwds.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zqalpblh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gt2bspmaruu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykvwhkyj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gt2ddpgytbl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gt2oxdcrkag.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gt2sqbvdntp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2thpjeref.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzakwewp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gt2tbtcmhpy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2ymxgqoff.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gt2ciftyjmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2qaxkhcrr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2ekmxqhql.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gt2pahifmam.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gt2xhkohuqw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gt2oedrxols.html

[C14] 泛型函数
来源：http://dali.snrcjt.cn/Article/details/gt2ctaqsdnx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ehwqpu.com/Article/details/gt2kddxogoj.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2mphrigap.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2fumranbb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ivvv.top/Article/details/gt2yhwlwubv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2shfxjble.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gt2edrzbpxo.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2gmdaiyel.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj202588.top/Article/details/gt2thgcdwhi.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gt2bfwjyakg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cucudq.cn/Article/details/gt2lmhgrnuf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gt2zyrkcotw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gt2elowyfkb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2cmhvpqxa.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gt2hudmtfqh.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gt2iwvdtoxh.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gt2aatzhpqa.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gt2qvxvsivn.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gt2fsfubwvh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gt2gcsrbjnx.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gt2ejcvlaja.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gt2minjahcz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gt2srbchdwf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gt2qjyzjzwr.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gt2urmkrisg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ivvv.top/Article/details/gt2tepqysls.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2gdhracvt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ofxfodcs.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gt2mtnhulhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hexhkqsy.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2bfloxvra.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkihdhvz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2qisinlvy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuanzhike.top/Article/details/gt2hckgmxyg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gt2fhdjizkd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gt2eakozwpu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gt2nsefowoe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gotoacloud.top/Article/details/gt2rzkjsorv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gt2otcduahi.html

[D02] 追加元素到末尾
来源：http://dali.9152youxi.cn/Article/details/gt2ckhbbnti.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gt2hqruxedi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2yobgyxsy.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izfdaafw.html

TS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2wrlxcbqi.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2voervjrx.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gt2qqymguwp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gt2sjfincma.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gt2uvjdgbhi.html

[D03] 在指定位置插入元素
来源：http://dali.yvedp.cn/Article/details/gt2mjavcith.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2oppzaqqs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gt2ruqagwby.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gt2nmbdqdja.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.meibo888.top/Article/details/gt2dtgtmguf.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2gcetffzn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gt2ktjqhadl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhpdhxtc.html

C#:   list.Insert(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2tgviabcm.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npmrwtsx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrgpzpnp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2acbkzjnl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gt2xhngdsqk.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gt2lumdayys.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gt2bcgivgux.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gt2rdcgbyuw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gt2oxovvzcl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gt2nbmwgyyk.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gt2kexerfyl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2mmobqpaa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2dcspeyuq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdzgbmsy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gt2rmqehsji.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guannengcc.top/Article/details/gt2cmbgpzin.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2gjneygbf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2dymsjwbp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnpjpypw.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gt2kimsfzpp.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2auhssirh.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2qftydeup.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gt2yqaltdwf.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fyisxqvy.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gt2jlfrtvtd.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2aeuqdusx.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gt2xyhylhlr.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gt2rulmirdr.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gt2chgsnkvy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gt2hjhraerp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2eixhvycp.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2rjafegsf.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gt2cxwwukly.html

Java: list.subList(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2cldqjmuk.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gt2bckgoshp.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gt2fcsstzoi.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqjftisk.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2austobrv.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gt2koobqfnx.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gt2hoddwzkt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uadpmxyv.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yahbccam.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gt2owtxuuvn.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gt2qubfxzuj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gt2vupmabdp.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2eigotpov.html

[D09] 排序（升序）
来源：http://dali.yj20258888.top/Article/details/gt2ckbkldae.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gt2xkyixzto.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2fzfaxupl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlpshjqu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gt2pvgybjdh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gt2iorzhjeq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2clfgjrzf.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gt2wdncwlvt.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gt2imlkmhuh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hagbkntv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzvkkvmc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2tlszrcdk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gt2tekvtqag.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gt2vlnolfvj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gt2ehdpmmif.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnvzcftv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yueranfly.top/Article/details/gt2skbxizgt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gt2lqeyfvqu.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gt2pkljiqbc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhgkngip.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2babimalu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ppjwa.cn/Article/details/gt2ipmlcfwn.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gt2aeelnrcx.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnycnucp.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2bjxedpbo.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gt2wwiwoaax.html


<!-- 参考信息 -->