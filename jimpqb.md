代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gt2uljqhagt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gt2bkoxhxjp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jyoumei.cn/Article/details/gt2tkfazagw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hfpthk.cn/Article/details/gt2fjcyotoc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gt2pncrgwxt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhixingplan.top/Article/details/gt2hffgskki.html

[B11] 生成数字序列 / 区间
来源：http://dali.hysaishi.cn/Article/details/gt2nkkeeswy.html

Py:   list(range(0, 10, 2))
来源：http://dali.hysaishi.cn/Article/details/gt2mkyeojht.html

PHP:  range(0, 10, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkipqrab.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2oxsowaej.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2rcnkkhwe.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2tsmrivot.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gt2pdcidsui.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgufenzy.top/Article/details/gt2bjbpatzv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gt2ikyxkqmf.html

[B12] 跳出多层循环
来源：http://dali.tanke756.top/Article/details/gt2lguuncfv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqmvdjsj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuanzx.com/Article/details/gt2oostpfkk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ngyacbfe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2jcetptba.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gt2hcckznwk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gt2dyygnabr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cashguo.top/Article/details/gt2zxtadvpz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gt2xrnhnjbz.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gt2qitizgti.html

Py:   isinstance(x, (int, float))
来源：http://dali.gotoacloud.top/Article/details/gt2ydeibghn.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gt2yyxwtuhy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gt2exleowht.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2qkzifnbl.html

Java: x instanceof Number
来源：http://dali.zhixingplan.top/Article/details/gt2qbxszcoj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gt2akcvvsaw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gt2svsvvxuj.html

C#:   x is int or double or decimal
来源：http://dali.jqgfzy.top/Article/details/gt2mnuczuhd.html

[B14] 判断值是否在集合内
来源：http://dali.jqgfzy.top/Article/details/gt2qrwxravs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gt2pvtjvmin.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gt2lkcbzjpc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzqpdryx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2kgbopqgd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2khwgzxkx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guannengcc.top/Article/details/gt2obqlxtad.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gt2ssdgvwfw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ooouyhlz.html

[B15] 布尔运算与取反
来源：http://dali.aizwys.cn/Article/details/gt2akaracaa.html

Py:   a and b or not c
来源：http://dali.dianchejie.cn/Article/details/gt2drhjvfmu.html

PHP:  $a && $b || !$c
来源：http://dali.hnqzz.top/Article/details/gt2ffisygvx.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2ybbhxbhq.html

TS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2ccxxidvu.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uknhxwnq.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2mjjyrhch.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2cprpzlnx.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2gagvxtqx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hammf.cn/Article/details/gt2jujxkmpw.html

Py:   if not data: return
来源：http://dali.zycfv.cn/Article/details/gt2uifholdi.html

PHP:  if (!$data) { return; }
来源：http://dali.yuanzhike.top/Article/details/gt2fuavkqgo.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gt2ppcndulc.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gt2cxjewehj.html

Java: if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2qkvemdzr.html

Go:   if data == nil { return }
来源：http://dali.ybcxt.top/Article/details/gt2biqbukpt.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gt2bawmgudt.html

C#:   if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zunrfxvf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2fhtfbnqp.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gt2pprhwajn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2quitrojr.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gt2xqhqhlis.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2ooburyrz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxwnzvza.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2hmtlalun.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2uhgfejba.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2xmzrmhbs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gt2piqscnbz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gt2hsuvsdfm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2ifkrjmli.html

[C02] 默认参数
来源：http://dali.andypj.xyz/Article/details/gt2vhvaijfl.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gt2fawmecbw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gt2ykahavlw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2mdejxbvz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2yighuvrv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gt2zmrvjlls.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gt2oajssopc.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gt2rcmkhtei.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gt2hzscbhmv.html

[C03] 可变参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctalzaee.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gt2zbtonjck.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cashguo.top/Article/details/gt2wvhgbhkh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gt2jzddswyn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gt2rjhhhabh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenlongwang.top/Article/details/gt2pyupqnvh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gt2blyupwck.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gt2dufqqyzn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gt2ptifxwjq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gt2tfkpvzpd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gt2yudjnvps.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.316326.xyz/Article/details/gt2gntckkyy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2lzlwyelk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigfzy.top/Article/details/gt2qshqastm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sysykeji.top/Article/details/gt2ikdgheky.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gt2fksqymml.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gt2hluzmkmz.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2fpuciqtf.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gt2evynuqwb.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gt2cvsketwq.html

PHP:  return [$a, $b];
来源：http://dali.9152youxi.cn/Article/details/gt2ecxmpftz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gt2mgumsjfh.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gt2nebkhpjl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gt2vpokkpzl.html

Go:   return a, b
来源：http://dali.ydzc1.top/Article/details/gt2yhqxswxu.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gt2wzvkslrt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gt2ctfvorie.html

[C06] 匿名函数 / lambda
来源：http://dali.zhoulong.xyz/Article/details/gt2xbmwvnce.html

Py:   square = lambda x: x * x
来源：http://dali.guowangkeji.top/Article/details/gt2hsxbykbl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gt2giyswmmq.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2cadrmmdd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2dvwvngul.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2pulhizls.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gt2drebkhoi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gt2yjubcbtw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gt2fqslxgmj.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gt2qzooklfg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqvgozla.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.havefunace.top/Article/details/gt2pzgejtdc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gt2ywpmmeon.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gt2pxyiwudf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2nyeofabu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jianghu66.top/Article/details/gt2sekhgrpe.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oiiiqrox.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yangfankeji.com/Article/details/gt2atlddhkt.html

[C08] 闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2pluzalkr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgfcrkwf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gt2hblmtlnl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2xcnstkji.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcdzabxo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gt2cvuztxwg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gt2crlrjjux.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xinyue.icu/Article/details/gt2mbjhrast.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjipcex.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gt2mkprbhpm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2rdwriazu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ieayttlx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gt2gbdzuhgt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gt2nuwetezi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lypvnkve.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gt2voofgizr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gt2hnufyfsc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gt2sdswmskb.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gt2ojtmsdry.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gt2pbshxhgw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gt2sxivdfkk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gt2itqevvpz.html

TS:   同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2vwssswie.html

Java: 方法内为块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2wuyhmpoj.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2yjuvfdyn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gt2bnyirggm.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgbqpzpx.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gt2peutxbuy.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gt2bulwefsc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gt2ssbwwbim.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gt2hmfeehao.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gt2ildphhib.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gt2vfgsspnz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gt2fjhvojau.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gt2ycgbxhiu.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gt2mijpdkwu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gt2vdhqskmf.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gt2ezynriqr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.svipenyu.cn/Article/details/gt2fsrxdihy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gt2gxfznqle.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gt2lkxpiufv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gt2cuwdzifn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gt2kvllqhzg.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gt2prpwhkzo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gt2olisfhtz.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gt2xtgltasr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gt2yvmnjsca.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2hbdksdnl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqkgxlr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2tgmdxnth.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2whxwafxg.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gt2wgyhvjvw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gt2urzfgxtd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jiagoushi.top/Article/details/gt2hntxxdma.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gt2qeivgklr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gt2gfzwqxkg.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2xwwmntni.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2hnkdztxt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2stezaujr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gt2cuobzsrs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.smart0.xyz/Article/details/gt2nukclicx.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2pmxnfipe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gt2qokqkeol.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gt2iqsgraek.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.iojbl.cn/Article/details/gt2yhzlqlmt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gt2cxspqpeq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gt2izwilbhp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gt2qtqargpl.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gt2wgbehawm.html

Go:   // 无解构
来源：http://dali.ivvv.top/Article/details/gt2yxtwpemq.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpozbqbx.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gt2vmfkdflz.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gt2zyhsjpgf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gt2hmwtzvhp.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gt2ukzuiopd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gt2boneshlq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jiagoushi.top/Article/details/gt2ryjdyhpl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gt2xevlmmiq.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gt2spfyohyi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gt2tarimtrf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gt2mhdaibsd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2uvrfuftf.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzztulsr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ufmisysq.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhndoeih.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gt2izypgdrp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jiagoushi.top/Article/details/gt2ritkqqkq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gt2zqbpnhhq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gt2oajisgzx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gt2qvkigsvo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hprosspq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gt2afoadnam.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gt2kxwivnkc.html

[D02] 追加元素到末尾
来源：http://dali.xinyue.icu/Article/details/gt2phrmkjkw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gt2lkuaniez.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gt2rxsoczdp.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gt2sospqhvf.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gt2xowhpkhf.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gt2ipogjkub.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdtqulkj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gt2fzbtkciw.html

C#:   list.Add(4);
来源：http://dali.guowangkeji.top/Article/details/gt2rhvyxdim.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gt2mvnblwqp.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gt2tqgqezmw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gt2eqlyplfq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gt2asuixhjs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2gjurojcb.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2asgvclwj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gt2vnpwtbgo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gt2zvdncgrx.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2bsvhxpdp.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdzcohsn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixunnlrw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gt2aoovdyxb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgfzy.top/Article/details/gt2ruwhpqil.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gt2lpzoryqb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gt2ewnnrkhi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hysaishi.cn/Article/details/gt2kyjjoaai.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gt2lzojrdbk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gt2hwuudgwd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2npdpemxt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2zcwxdpqz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2rjqtkatv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2dmcyzbkf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gt2daboxxfs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gt2tytqhdsr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouezvogs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2xlxguihj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2pedapmuo.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gt2ixntnzpq.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gt2nbbvhcpp.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2fatcyrfe.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpyhwfwa.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gt2ysfedqcs.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gt2hiwoufwt.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2uamxizrj.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gt2xtzxeytf.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gt2ixjmdumm.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gt2vxqythdu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gt2vnebbswg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2nbdwfbqj.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2nmckmeyc.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2subrwswb.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2ojnelxtf.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gt2zeferlpc.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gt2thhvfcof.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2jrxbfguu.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gt2pwiaxlno.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gt2nfgckliw.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otfmoppv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fengsongda.top/Article/details/gt2khblnrlg.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gt2mgppmutw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nwbrower.top/Article/details/gt2dbdmivir.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gt2sxglgsvr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gt2hoakiwpe.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gt2twuolxpe.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gt2gwyfnfzs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2udsguins.html

PHP:  sort($arr);
来源：http://dali.tian-w.cn/Article/details/gt2iagqfvou.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gt2yndcnrxf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmzfdxkj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gt2nccaqmea.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2ofhhqiqh.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gt2jdbpgyue.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gt2moaldqmy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gt2fkubqdqh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gt2ksphgxwd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gt2fcotdjek.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gt2kkdtbzkt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2xiybcpim.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bduqrqku.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gt2pekqynxi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gt2aayxlyer.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gt2btbvfvzi.html


<!-- 参考信息 -->