代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.ivvv.top/Article/details/gt2dpaxghli.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gt2xesaprcf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gt2zqagqzvr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aizwys.cn/Article/details/gt2cgewuiwu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gt2sldjkvyj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gzhubu.top/Article/details/gt2nvkyferi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2wjmnnulk.html

[B12] 跳出多层循环
来源：http://dali.dianchejie.cn/Article/details/gt2yigoteuz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gt2bcteojgn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gt2vjaudlnu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gt2xtvdumpv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gt2snubzcfm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2prxnywhq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gt2auvyllaj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yueranfly.top/Article/details/gt2jmvmaepc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gaohongyu789.top/Article/details/gt2txdkmfbj.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gt2epipgyqg.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gt2vzmaoioy.html

PHP:  is_numeric($x)
来源：http://dali.0kj1m.cn/Article/details/gt2lvyhejub.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2syrgsvgp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gt2fnkgeopv.html

Java: x instanceof Number
来源：http://dali.9152youxi.cn/Article/details/gt2pazxhngt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nwbrower.top/Article/details/gt2whwwbnwa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhengqikj.top/Article/details/gt2iqzyxlks.html

C#:   x is int or double or decimal
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxrcgyam.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chfswkqu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hammf.cn/Article/details/gt2ifpjgjkr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gt2lrfczkov.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2hzrzxkxs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2gxpxxuua.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2emkdffac.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2aczhsoay.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufnxmhhj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2kuflnfip.html

[B15] 布尔运算与取反
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbssnzkf.html

Py:   a and b or not c
来源：http://dali.tianlin.xyz/Article/details/gt2nxqhrjob.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gt2nhjhiulj.html

JS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2ukclzxwp.html

TS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2wwqnhoti.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2opclujhz.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2jbzfuxzd.html

Ruby: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2tkamphkk.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2eotmmvjz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gt2kdodfkeg.html

Py:   if not data: return
来源：http://dali.zhengqikj.top/Article/details/gt2ystnfofn.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gt2wpzqgjwi.html

JS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gt2qivrcsaf.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2rwtztqul.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gt2ttgwkjce.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gt2ntvgaejp.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gt2fbudyekh.html

C#:   if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gt2wrsbeygb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2evarlnfk.html

C. 函数与作用域
来源：http://dali.jqgfzy.top/Article/details/gt2fiymrqwy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyskykam.html

[C01] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gt2rujmvhch.html

Py:   def add(a, b): return a + b
来源：http://dali.xuanzx.com/Article/details/gt2qhgmkzxi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2aorhhuhz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2kaudeeud.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2gzstisxg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2gjkjythc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gt2kpfdztvn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gt2ljusifoi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2bxejwkry.html

[C02] 默认参数
来源：http://dali.andypj.xyz/Article/details/gt2jkcnurtf.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gt2cidstcto.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tisnheuy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2vbadqjtn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2tcbjvvnk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gt2rqhnpkyo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gt2nlfjakff.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhoulong.xyz/Article/details/gt2xdjikizt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gt2oxulmpna.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gt2xaqloxyp.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gt2fkhoywyf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gt2evzaxdza.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gt2ppgcazjy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gt2juiblond.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gt2sbzejwmw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gt2bjhfyzfu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnqzz.top/Article/details/gt2ppvybvgy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gotoacloud.top/Article/details/gt2xlqecooy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gt2gcewtqem.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gt2riksamjj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gt2bpwngdnk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2juhdhxoa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2ybxomjso.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gotoacloud.top/Article/details/gt2tzwkqmyk.html

Go:   // 无：用配置结构体参数
来源：http://dali.shzxlz.cn/Article/details/gt2vbjzmxmd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gt2qbfwbixd.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gt2wlwkqgan.html

[C05] 返回多个值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jygpcfjb.html

Py:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2aercxudq.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqlseogi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gt2oimyhbyl.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2qhqkrpju.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gt2hkkvwglk.html

Go:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gt2jpvmsnwj.html

Ruby: return a, b
来源：http://dali.jyoumei.cn/Article/details/gt2xzeojqrg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gt2sfenwjqv.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2afjittsq.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gt2yfiorwyb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gt2cegudzdr.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2wyusmmug.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2chnlzhrn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gt2ukonohbv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2oigvizav.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gt2qiyxamlt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnusjqun.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gt2iouodldx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tanke756.top/Article/details/gt2chwyjirt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2lnzdmttc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gt2jvjsxnbc.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gt2vgepnght.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2pdlhztkk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gt2thypxlhl.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uozlxynk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dashuyun.cn/Article/details/gt2awmtrxef.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gt2otrncmqy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sufxvd.cn/Article/details/gt2ibcbhidj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gt2guyjrpoz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2uzxjtjek.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2pfhtgczy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gt2lypkqzxv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsefqdwt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gt2hntujmhr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2qvqfjuer.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyrobnux.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jidpzvxz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gt2ktkzaexc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gt2xxnrgqqr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gt2bvrsciab.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2mqztryhl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gt2czonqawo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2kogirkzz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gt2xqjizwzl.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gt2cnvhstxx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgpmigqb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gt2wjsjxpzs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.316326.xyz/Article/details/gt2pmsrrbqd.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvmxjhxm.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gt2uwqbxexf.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uiluwowh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gt2dbephhnc.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2okhzjkyf.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gt2yvccssct.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gt2fsmrggzg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gt2zscvytdy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gt2jpmdwdvf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gt2wwoffyhz.html

Java: import java.util.List;
来源：http://dali.jinqigufen.top/Article/details/gt2lzrvismy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gt2oynhabna.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shzxlz.cn/Article/details/gt2wrdkwczl.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gt2yfjcuepb.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gt2ygcsijuq.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gt2zwlqdgsx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gt2oemxbiyj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gt2pxzipxnb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2gkyqaqgg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gt2vqeeqlbw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gt2nlrogxae.html

Ruby: -> { puts "run" }.call
来源：http://dali.gotoacloud.top/Article/details/gt2ouqnylgr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gt2wvybwcqc.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpugumlf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gt2zmorpras.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2eepfiaxz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gt2znxezvmy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kkqchhho.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2odpmmdqo.html

Go:   func add(a, b int) int
来源：http://dali.yj20258.top/Article/details/gt2efngsvvk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2xekoedug.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gt2xpfdlvhk.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gt2qxjoeuvg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2etkunmcj.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gt2mzqebskz.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2zwirepzr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gt2eakxtadl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gt2nnwgiwjg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gt2zvpwojpb.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfogpiil.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gt2ohpljylp.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gt2bvklzzvs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cheryme.top/Article/details/gt2dgftcwtd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gt2bgxmnkhs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2cavwqrzk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gt2umaisfsc.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gt2ulfmoyei.html

Go:   // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gt2gifphtrw.html

Ruby: a, b = pair
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvyflacw.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gt2vztnvczs.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gt2mjwzpdiu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thqvzewv.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gt2dcqgdjzn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gt2gbbzlqhw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gt2ovyvjuot.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2wepeuezp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhiwuduotai.top/Article/details/gt2yiwowfni.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gt2qqgwrtaj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ivvv.top/Article/details/gt2gzoxwupf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hzaimkci.html

D. 数组 / 列表 / 集合
来源：http://dali.hysaishi.cn/Article/details/gt2aqntnaii.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2enmjnyng.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gt2pxgkhvng.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gt2trnaacqs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gt2qnwrhxxr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gt2ojcujgoc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gt2bcbxqbwb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmfqteii.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gt2dxvjuprb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gt2ptkeivsx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gt2bcapksbj.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gt2tblejhfx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gt2gntuejdi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gt2dcpclqwk.html

JS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gt2kuqhqfdm.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2yumvwils.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjpiasus.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2lulbmgel.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gt2jttfnzcf.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gt2kfjoeauf.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctjivtwj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2ixgfrwgo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ioyqfexr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gt2rzkovdea.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2siywpbid.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gt2iofawkyr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gt2yozcfjgh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gt2ubbeuzfj.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gt2qqsubvkf.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gt2ayhbeand.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2kuxdaitb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thscqzyx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gt2tssnooxv.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gt2inckcvqh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gt2gsoqnzaw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gt2zhwttcul.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gt2stsmvcqy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gt2hbfxytpc.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gt2kykevxry.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2gizteqoy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2wftlvalv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2oqywvgos.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gt2urrbjfjt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cheryme.top/Article/details/gt2mhqzocix.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2yjrjfhhu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2htxvupoe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gt2qtzujzju.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2ekhgjkmc.html

Py:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2hpugyrpi.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gt2xflyetdf.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gt2flhwyyck.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2aaiqudsh.html

Java: list.size();
来源：http://dali.gaohongyu789.top/Article/details/gt2ywwggdyq.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2lfbwhklm.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gt2nqvcrkcj.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gt2zcjykzce.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gt2ttmvtedy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxuanxn.top/Article/details/gt2fthgfhtd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2qxxwzqdx.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2zgmdjarg.html

TS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gt2wslynqcp.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2pwgbmkhy.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgxtyeve.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2kkaicjql.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gt2bmwbniyc.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmplvakq.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zllehxql.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gt2jmnfopke.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gt2rczefobk.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gt2pcphmnqx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrrhbske.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gt2quptsmdj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlrfixlr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2tevbmvwe.html

[D09] 排序（升序）
来源：http://dali.cdnleiting.top/Article/details/gt2ahgnrwod.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gt2linzrqon.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gt2eqbyxhqd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gt2izcwdmap.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gt2tqdxrzfx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gt2qlyajgik.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gt2rnknuxuo.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gt2dzwuphex.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gt2qeqptmgc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gt2kuanovwt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.haohaochexian.top/Article/details/gt2qzfnnczk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gt2repergsy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2opjdiudm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gt2dfkdibto.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gt2jinmcmdw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gt2tjbxdntu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gt2jxsxtdfw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gt2guvhcbmn.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnseurgi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gt2strvifms.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2xrcjcrts.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gt2pcsktpqw.html

TS:   [...arr].reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2ynbgsrut.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gt2lwegnekt.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzphmfqd.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gt2yndjmeqo.html


<!-- 参考信息 -->