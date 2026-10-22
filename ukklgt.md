代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrrqyuq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gt2txrwjefz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gt2ucfqmgva.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenlongwang.top/Article/details/gt2dpwyavsw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gt2oewrlicc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gt2aneustqy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tanke756.top/Article/details/gt2inbngzvg.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpawehyi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gt2hmbheiak.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gt2jzewyxlw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gt2pnihddwb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gt2hvmjangp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gt2hbuhjugb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guannengcc.top/Article/details/gt2nvxzmowd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jiagoushi.top/Article/details/gt2ruvdjnmo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj20258888.top/Article/details/gt2oekuttih.html

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gt2mfomcszy.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gt2qjjmxiju.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gt2cznssxyr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gt2mxfidnsq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gt2yjzzoblk.html

Java: x instanceof Number
来源：http://dali.redwolf501.top/Article/details/gt2ladxjvzt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnxuabwh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.havefunace.top/Article/details/gt2bcoqzrhf.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gt2ryfcqmny.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmubrgty.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxuanxn.top/Article/details/gt2yobwjsfl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mexcrlyj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2cqwvckff.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2jstmwtwj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2jyicnbql.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gt2lngbthjc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gt2mrawtizy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2pntttoad.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebrgdacs.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2hpymymuw.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gt2pigwfvgp.html

JS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2teiapjwd.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2ablrqkix.html

Java: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2zebuvvdo.html

Go:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrkrvwcl.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2oiblbwyu.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2reqycpgs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gt2giobhymc.html

Py:   if not data: return
来源：http://dali.snrcjt.cn/Article/details/gt2uxyanlsv.html

PHP:  if (!$data) { return; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dymaekpy.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gt2wvcnlchf.html

TS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gt2tvqvfcdo.html

Java: if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfcfqkpl.html

Go:   if data == nil { return }
来源：http://dali.hysaishi.cn/Article/details/gt2ggxyzcov.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gt2ysnybvpt.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2iqtfheyf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2qqduitmp.html

C. 函数与作用域
来源：http://dali.sysykeji.top/Article/details/gt2zsogxhjr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2rapjwmwi.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gt2wbjbcvnn.html

Py:   def add(a, b): return a + b
来源：http://dali.fengsongda.top/Article/details/gt2gbssvrkh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jqdgekil.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2seyesvdj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpetfgfd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2irbbhggy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqzowgdz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gt2vkwvtpsr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqrdihcq.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gt2apmxmibc.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghugrdgg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gt2xwdommbn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zzgydxwx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2sjdajtsv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gt2nzqmrxhx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gt2zfkmdrgc.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhoulong.xyz/Article/details/gt2wksnnxxo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gt2orfehofe.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gt2nddqflaa.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsnhohut.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnvqlmgx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gt2zpbbjxto.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2kmkjsedx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2vzkcnoln.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vutgypnw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gt2smgbwmnk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gt2vlywsdsl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gt2vezkizvw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfxzwpbz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gt2esrhtpfx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gt2qohwhfmp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daria6918.cn/Article/details/gt2ggqovbeh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gt2gobtwwhx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phqvzfjx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2achdbpfp.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gt2qziqlrxv.html

[C05] 返回多个值
来源：http://dali.jinqigfzy.top/Article/details/gt2rtahsvht.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gt2uajojdzj.html

PHP:  return [$a, $b];
来源：http://dali.cdnleiting.top/Article/details/gt2qcbydaar.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gt2fkawhdge.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gt2vplwcsqg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.c1oappe.top/Article/details/gt2bmyujlxw.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gt2jkaaszrn.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gt2orxjemxz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mokibrwt.html

[C06] 匿名函数 / lambda
来源：http://dali.tanke756.top/Article/details/gt2jqsadnif.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gt2ntmhhomf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2huhhohml.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2tfsdvqre.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2mzqfgbtn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lliumtea.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2eijdtcwn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2fnfujegs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2iwrvjinj.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2choeuapd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gt2eygvsyod.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ontlpwkk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.birdmap.top/Article/details/gt2pkbvvelx.html

TS:   arr.map(String)
来源：http://dali.yvedp.cn/Article/details/gt2fvbahrto.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2joetbhap.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkenqafl.html

Ruby: arr.map(&:upcase)
来源：http://dali.gotoacloud.top/Article/details/gt2fukppmbs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gt2yeiuydsh.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gt2jvjhhqfs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gt2yktcrqic.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixjccyih.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2eprrevsp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2vhnukizn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gt2arwygnsu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gt2wizzmyvi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gt2noujoaiw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbalfufw.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gt2tjlkvlqx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2jeujahcl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ahxavxkr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gt2wwbyahcb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gt2raascmqm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2ljidtfjb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gt2mizitjxl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2nwpmwvkb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2ijgcooot.html

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2cdgqqmpi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gt2ufhpdbpt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgfzy.top/Article/details/gt2vgvsydqv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2ytefiicp.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2puxnciqw.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gt2cimbbxcp.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyjhtgyf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gt2gmoufcnj.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2durigoua.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gt2noymqwwa.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gt2myrjxjii.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gt2rclkstwp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yongpay.top/Article/details/gt2mqnejalr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gt2gjidjygr.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gt2tsbfhoqn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gt2mpoljnxo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gt2bpbnvgxp.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gt2thurgjyh.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gt2rmepuhfb.html

Py:   (lambda: print("run"))()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcntqbyc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gt2uafjdgtt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gt2epjbphwp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gt2ifaowowp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.snrcjt.cn/Article/details/gt2builnriq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gt2mhxzsmqc.html

Ruby: -> { puts "run" }.call
来源：http://dali.iojbl.cn/Article/details/gt2fizbmwbp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gt2xlvzgsli.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gt2slxfyqbo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2gzkdqujg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2sxfvkxpp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gt2fyojnbqg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2olucvlzt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2fajweamu.html

Go:   func add(a, b int) int
来源：http://dali.c1oappe.top/Article/details/gt2kmmucrje.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tanke756.top/Article/details/gt2zpvlwxnz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tian-w.cn/Article/details/gt2yexottds.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pibifsaw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gt2gwiozhgr.html

PHP:  // 无泛型
来源：http://dali.cashguo.top/Article/details/gt2jsrmrtty.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2gmlycbun.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gt2twfwfyct.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2uomfkyrw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj202588.top/Article/details/gt2ogrksfhs.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfzxopok.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yongpay.top/Article/details/gt2xciqvqdo.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gt2tloshgfr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gt2rehgghts.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nwbrower.top/Article/details/gt2zybhqnot.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gt2qnusmtsl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubfrpsho.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gt2tergpele.html

Go:   // 无解构
来源：http://dali.ehwqpu.com/Article/details/gt2breklivq.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gt2vcyxxszl.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2skbokfgy.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gt2kqgzldng.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ydzc1.top/Article/details/gt2tnybqwya.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gt2zwomgijp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gt2ntpvzcmd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gt2wsoovaaz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gt2tayisxvc.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmgflseh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gt2dtmsyaoo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gt2cngclteb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2okqnijjc.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gt2ynatjefz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2xsbrxtqi.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gt2hiqgxcwi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gt2ruwxxhzd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2bbtgqvpi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gt2acslcggd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gt2mrbfdrvv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gt2upzvgwpi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gt2xbcdzkvi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gt2yxgrzbig.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gt2ssrlblsd.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gt2mbbrzfhe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gt2qnuhzbep.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcpbdbjp.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gt2urvtjdwd.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2zlasmnjt.html

Java: list.add(4);
来源：http://dali.jianghu66.top/Article/details/gt2eydpuejz.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gt2eyvqnzeg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gt2nbvtkgvl.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2qkignukf.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gt2txwgvryz.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2mvzqnghg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gt2dmmjheyh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gt2ifhwkkzp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gt2ledxehvr.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2yvipioiz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gt2rxsoqxvr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gt2axnwxjts.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2urvrxnkm.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gt2helocroc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gt2oafcnoco.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2fnhcjgeq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258.top/Article/details/gt2dluwwzeq.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gt2ysgxyece.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guowangkeji.top/Article/details/gt2qqyctccf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cytssgol.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.iojbl.cn/Article/details/gt2uooivvqs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxinkj.top/Article/details/gt2elfguvht.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gt2xaqftkvo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2midakkxj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2riclymkb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2awbfbskg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gt2zsgukzwk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gt2fxqemyso.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2shtfpiqe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2snigozye.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gt2tcolnobq.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrsxwlcc.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fithfqed.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2otjxkuud.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gt2wbroagzf.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2jrmkckab.html

Java: list.size();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2itxtwrgv.html

Go:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2ibyphapg.html

Ruby: arr.length; arr.size
来源：http://dali.gogol.net.cn/Article/details/gt2vqgfzidr.html

C#:   list.Count;
来源：http://dali.havefunace.top/Article/details/gt2eaztptik.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gt2exezxqfr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gt2aousqsjh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2mhdwfvae.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2wraxpqbi.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2mzcplvvp.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2dezedoih.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gt2muyvhhij.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2lrfatfdm.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258888.top/Article/details/gt2peshhxhu.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gt2myvahlpa.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gt2xkrifvbg.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gt2siwynbal.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gt2ydzrlfoe.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gt2hxvgebpc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gt2vqvygagb.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gt2tfqvozra.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zdqjudy.top/Article/details/gt2xwvmlmnf.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2ytgjvpom.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gt2hcawjggs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2ixsoodzd.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gt2zyphzbhb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gt2qjoesiru.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gt2gaybxfxp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gt2nsefdmdp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2pxmsgbxl.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gt2wxllqgel.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gt2aemchonj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.quarkkingdee.top/Article/details/gt2fjcdeebr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aizwys.cn/Article/details/gt2etbvcxeu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsbiuzyl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2vbxmjgzb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2twaluvup.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnkhzbfo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gt2ehlbiipp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ivvv.top/Article/details/gt2qpghiioq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gt2nbevspaz.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gt2nxrabclz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gt2hfovpowr.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2gqjecmhs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.0kj1m.cn/Article/details/gt2lurfxgqb.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gt2fumqbmmf.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gt2qgwkksdr.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2jqbbjnxf.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2fbewzigu.html


<!-- 参考信息 -->