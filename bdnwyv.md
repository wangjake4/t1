代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gt2cxkctcku.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gt2upzelhig.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gt2zoxxtgso.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gt2znrlsmfl.html

PHP:  range(0, 10, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hduttzki.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2kqojwhvc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bshwetni.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2efsszzhx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuetiantiany.cn/Article/details/gt2feyucjwd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj202588.top/Article/details/gt2mumsabls.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gt2dexqldiv.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gt2vqoewjbe.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yangfankeji.com/Article/details/gt2gzzorzkg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gt2dzfqqwbv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gt2eadonffz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gt2rxgykdty.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gttbvyvz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kykkjwff.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gt2drlabads.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gt2qlofsstg.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gt2xkajcdou.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gt2cwbasrnq.html

PHP:  is_numeric($x)
来源：http://dali.sufxvd.cn/Article/details/gt2cxvvwlyr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gt2oaifoqoj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brhagufq.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gt2tlswvhlk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gt2nvsluvas.html

Ruby: x.is_a?(Numeric)
来源：http://dali.andypj.xyz/Article/details/gt2glfybwgw.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gt2xsjfhajb.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gt2ehqxtaud.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pengpengdd.cyou/Article/details/gt2psyaccbr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gt2zthkaopq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2reoftorg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2pocddjtt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2wtzcyljo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srjwtdmt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2gosrurdz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2ljdqoqvq.html

[B15] 布尔运算与取反
来源：http://dali.jiagoushi.top/Article/details/gt2vytiudtw.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqnuyxwc.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gt2vwgquzic.html

JS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2svmfabpp.html

TS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2sljyyryi.html

Java: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnkpqgls.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2nsysybud.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2yusqrcht.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2smwdccfv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2zuwokmzr.html

Py:   if not data: return
来源：http://dali.snrcjt.cn/Article/details/gt2nwxhmuxo.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jqhecsju.html

JS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2dxvvgoib.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbedobhj.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrwxfkey.html

Go:   if data == nil { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2emxnatdh.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gt2hewncygw.html

C#:   if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gt2dtqkcbft.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2macrhhmk.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gt2iovnpmrc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfylnubm.html

[C01] 定义函数
来源：http://dali.yuxming.cn/Article/details/gt2zrlzqtul.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gt2xmfaxugb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2kzczzmdb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqyefhkc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2ujihmuuc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjmijdpo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guannengcc.top/Article/details/gt2lieetojr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2msmvjtps.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2kxyneern.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gt2zblfwnms.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gt2qarkkrcg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258888.top/Article/details/gt2nxklxzrf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhzlvchi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inerzjrv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shzxlz.cn/Article/details/gt2niuhyrub.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.redwolf501.top/Article/details/gt2occbdvot.html

Ruby: def greet(name = "World") = name
来源：http://dali.yanxiufei.cn/Article/details/gt2ttdhzoia.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gt2nceisxbt.html

[C03] 可变参数
来源：http://dali.zdqjudy.top/Article/details/gt2rmihyksu.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gt2ntxjlsol.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2otrojwxx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acwddpdy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yfzaxxzz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gt2dnkecrjn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gt2krlqlhfe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.iojbl.cn/Article/details/gt2eicmohdy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gt2fzasoltd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gt2gdyznjge.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkzuqfjf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gt2ltszeyqh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvmfgxab.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxinkj.top/Article/details/gt2kczbqnib.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cucudq.cn/Article/details/gt2ouktvwbv.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gt2ejcmmbfa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gt2ezgmhuzn.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2thtxybow.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gt2jsjtbctd.html

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2pabnqmpu.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gt2pptzwpdp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258888.top/Article/details/gt2mooynzlu.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gt2lzlncswa.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gt2ezidxiir.html

Go:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2dydbnzbp.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2tbuwudov.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqjavjzn.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iboijbuq.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gt2kecwjclv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gt2eoutttfy.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2helwtsob.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tdfjozfq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zotibgki.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.svipenyu.cn/Article/details/gt2yrsmojzu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gt2zdbyxrim.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2efgqpert.html

[C07] 把函数作为参数传入
来源：http://dali.quarkkingdee.top/Article/details/gt2fuynuwen.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gt2qcimlsea.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sweek.top/Article/details/gt2wudurtzo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigfzy.top/Article/details/gt2kpljjuxi.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gt2ijiofdmx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daxiang520.top/Article/details/gt2vtwostfb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gt2sfbggetq.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenzaomai.com/Article/details/gt2nfovpibh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdzesnk.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gt2bqyqcjyy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sxryk.cn/Article/details/gt2igqplxyh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gt2isfnbsya.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2dgmnutti.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2auisgpkg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gt2ldisltls.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gt2ztfsstiq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gt2safdqxwl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gt2brrdqtgo.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gt2fzfhslqf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gt2auhcvhbv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shuidangran.top/Article/details/gt2cxwaucuf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gt2wkzkmmtu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gt2jrxawjao.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gt2hubmobdq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.smart0.xyz/Article/details/gt2ahskzmdt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmhsulxp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.redwolf501.top/Article/details/gt2lmwokait.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gt2ubjphucu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gt2tqkdfckj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynoqqcys.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gt2awawdqwh.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2ncstvjoe.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2obxxdcwt.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gt2thtktzsf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gt2vceqzabj.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2hswwvzds.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmtqgpap.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gt2mypjhadm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gt2qsnoslni.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gt2uprdtokj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gt2jksnojdf.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfgxmfhg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gt2ftkqbslh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gt2uggeastw.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gt2mnwrcirm.html

[C12] 立即执行函数 IIFE
来源：http://dali.fzhhl.top/Article/details/gt2vsxssbfe.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gt2njihsqjl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gt2mwzickat.html

JS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gt2zskjpzmu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2qbknivgj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gt2siyipgiy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmxwudqa.html

Ruby: -> { puts "run" }.call
来源：http://dali.smart0.xyz/Article/details/gt2mxhzdzmc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2wvnwkxym.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gt2wpoowlek.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxinkj.top/Article/details/gt2scakoaoi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2pulnrmyg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gt2knqvydww.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bjsljhoc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2uftbnaqa.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gt2obpnnsxm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gt2xkzlfkun.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gt2uwaezczg.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gt2otubycau.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvrertmz.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2vmofwamj.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2ezkumisu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gt2jbvlvjev.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gt2fctlrdpb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gt2slxsmdrb.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfqblxzu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gt2qjcoxnzb.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gt2glmvfqek.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gt2xoaeydmh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gt2byuefzyd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ujwevnyc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shuidangran.top/Article/details/gt2tdefywir.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gt2vhhfdqce.html

Go:   // 无解构
来源：http://dali.chenzaomai.com/Article/details/gt2uaplbkck.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gt2ikplodep.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gt2daycpslm.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gt2yxrxnywr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gt2grqttnyf.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gt2jazaqscg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gt2zmqjhmoy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gt2lceplvmv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gt2yqtxxunf.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gt2baymttug.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gt2fzvcybro.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ekdrtbze.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2cisjewco.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gt2hccnloxg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2yyweosrp.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gt2ogvswuxj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrywggua.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gt2ryjbxgsg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2pstogzqb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yvedp.cn/Article/details/gt2qnhoqtkk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gt2dypxrhja.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtvklntf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gt2npiffnyy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gt2ainbtjkp.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gt2nkeknhlm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gt2ynvflocu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2lanfrkcr.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2fhichxmk.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2jxvcbmff.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gt2gurckajp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsdkpelz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gt2ejxezavf.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gt2lwlvswii.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjjsakie.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gt2vryjafnv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gt2iunppzwq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gt2smfigcav.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2tgowkebu.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qoiksglk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gt2fqcmuvlq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tianlin.xyz/Article/details/gt2jnutfsza.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkiqkxoo.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2ivfdixny.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gt2leapgrmi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnqzz.top/Article/details/gt2cetspbdc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gt2kqathohk.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gt2eqqnmpni.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gt2cnqlsugi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gt2xokjuvup.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjsilwpm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gt2rhtlnpof.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gt2xwtucjab.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2zpenchpq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2suqypaxv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2qaovlqdv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gt2yjffyflk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvjoeuiz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2ewnfltsa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2ecuvawhl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gt2yzyrujsv.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gt2vynaaakf.html

Py:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2rwkybmad.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fijsdurs.html

JS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gt2ujtckshh.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txmzyugz.html

Java: list.size();
来源：http://dali.tanke756.top/Article/details/gt2lpvwgzdu.html

Go:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tebodiif.html

Ruby: arr.length; arr.size
来源：http://dali.yonumen.top/Article/details/gt2zuqoukbd.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gt2yuvibcgk.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gt2qrknflsw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gt2xnlwuqfm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gt2gymhaxsh.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2tnsfxqfi.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2mubnzufe.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2tssnsdtl.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gt2kfmmckia.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gt2wcvtgmmz.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2zgqloevj.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gt2qgtyvqox.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gt2hbspokke.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdfwrnxu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gt2zuvvwsgs.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gt2mmzygssa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gt2jfyyuuuq.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gt2wbtbqojr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gt2clzzskxs.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2yncunudl.html

[D09] 排序（升序）
来源：http://dali.yongpay.top/Article/details/gt2iuvzowmv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gt2zpacdzdh.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2szdngqsw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gt2qooggrqr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avntxndd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nuaphezx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnoixglw.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gt2ytsulpkw.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gt2lkyohyzk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.vqdsnc.cn/Article/details/gt2ryzfxvmg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpqizizu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gt2bnveixig.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqpixidi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gt2syneghky.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gt2gnrhrllg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gt2doyznigf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.mhx1999.top/Article/details/gt2pawtqnal.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gt2gvkaiylf.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqiwysmj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gt2wwygbmjt.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2ajuuiool.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hysaishi.cn/Article/details/gt2issuofhi.html


<!-- 参考信息 -->