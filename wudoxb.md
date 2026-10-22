代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pycfn.com/Article/details/gt2bxttupvu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gt2xfuxjlfo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.bjfxy.top/Article/details/gt2wpyaaani.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gt2mxnyxttr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gzhubu.top/Article/details/gt2xgznvici.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2osphojmq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gt2isiuytel.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2hndxbaug.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gt2wlytbemi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gt2pjrzlszu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.mhx1999.top/Article/details/gt2huwsjugc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zycfv.cn/Article/details/gt2upuqycug.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gt2ldfnejjc.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgfzy.top/Article/details/gt2vqmphddi.html

PHP:  is_numeric($x)
来源：http://dali.wangdashe.top/Article/details/gt2enubqzmt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gt2mehrlwlu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gt2joqdddzr.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gt2qceyfgoo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.havefunace.top/Article/details/gt2hutwhmtf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gt2jeorwtzi.html

C#:   x is int or double or decimal
来源：http://dali.tianlin.xyz/Article/details/gt2vfmxxrhj.html

[B14] 判断值是否在集合内
来源：http://dali.ybcxt.top/Article/details/gt2zaahqslz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daria6918.cn/Article/details/gt2meqmfmii.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258.top/Article/details/gt2wvdtqrqo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2utwhnftg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2jnykreju.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2ivxtnqwn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cheryme.top/Article/details/gt2phxiqjhr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxsiuhgj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqiialak.html

[B15] 布尔运算与取反
来源：http://dali.daria6918.cn/Article/details/gt2nphtqqsl.html

Py:   a and b or not c
来源：http://dali.dashuyun.cn/Article/details/gt2wkaqbjfp.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gt2ilsbratf.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2agvxqrgu.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2scicupkf.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2docwujnp.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2edzyfkzv.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2wbyyyaki.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2ioghorpv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jianghu66.top/Article/details/gt2inevgcqi.html

Py:   if not data: return
来源：http://dali.meibo888.top/Article/details/gt2zfozbooh.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qngfxjre.html

JS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gt2umatdpvd.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2dfjfcloy.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmrbtzmm.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2hlnvfzxw.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gt2cvfixzam.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzwvsyjd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2llhuocfw.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gt2ezmguyvm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2xvpvzfpv.html

[C01] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gt2mhmtylti.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gt2tpiymhav.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ogyrfvox.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plomovpx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2ynlfjiwo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cevxhzxl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gt2rcypldbh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gt2zipjihdj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2sfemvuil.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gt2axgzuqgt.html

Py:   def greet(name="World"): return name
来源：http://dali.dashuyun.cn/Article/details/gt2mgrnzhdl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gt2busgrghs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2wupykfph.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ghuaxhcm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gt2qkxajptw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.snrcjt.cn/Article/details/gt2vjxivvyk.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gt2lwwgbedi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gt2jnqpvffu.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gt2sazakmzn.html

Py:   def total(*args): return sum(args)
来源：http://dali.cucudq.cn/Article/details/gt2hmgdwejq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.haohaochexian.top/Article/details/gt2wedvwjhz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gt2drcajjln.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2nuavblog.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yoxfviwv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gt2xouehlse.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gt2qiuhqxzf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gzhubu.top/Article/details/gt2mdjljoxb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gt2lfhrrlqk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hsyckamj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gt2rjhbperh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gt2fhiywfjq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gt2tnwxqxic.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gt2retoowff.html

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gt2gekaqulp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gt2mljybwrj.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2fyfaqnth.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gt2ellkddhg.html

Py:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbmmzmbn.html

PHP:  return [$a, $b];
来源：http://dali.hnxiangtu.top/Article/details/gt2urjglpyc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2cwqccqwq.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gt2dyxcyuke.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqdzvll.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gt2qsnpakgw.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gt2oobellfo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gt2qicvtxnc.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2zchrijwi.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gt2iolscgno.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kaerqcvj.html

JS:   const square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2dyikawlm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2cbwhmvwo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2uicmneyo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gt2yijkvhof.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zycfv.cn/Article/details/gt2qtulbfac.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2qqfyfphb.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gt2wucityls.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gt2vffebzib.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2zniikajj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gt2nyxkijqt.html

TS:   arr.map(String)
来源：http://dali.yueranfly.top/Article/details/gt2zbkxkwlb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gt2uhmuzwhl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrufklgb.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gt2czvraqvv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gt2vslsgvwq.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gt2gfcdydgh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gt2rrutbbog.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gt2qiiwhkjm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2fsltzvhq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2byrmdihn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnrgtdax.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nwbrower.top/Article/details/gt2dmnowkgt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigufen.top/Article/details/gt2kmkhozcl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2inqrmrdy.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljjfrzqk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gt2pdmnjqgk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gt2nvehdrlh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gt2gnaphkka.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gt2vhmmblgc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gt2ifwatntj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gt2zbqxbsbc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gt2syzihmgw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kchbxkyf.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2ayeoozih.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gt2tjabocuh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pycfn.com/Article/details/gt2qaedngap.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbzmczzr.html

TS:   同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmikscpb.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2tbumlbiq.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2hsuwfgax.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gt2udaashnh.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2edfzdtxa.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gt2inbtgauf.html

Py:   from module import func
来源：http://dali.cashguo.top/Article/details/gt2atlsmybk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gzhubu.top/Article/details/gt2luypiqsn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gt2ljhaqhlh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aizwys.cn/Article/details/gt2mhbnclud.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gt2wozinsck.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gt2hunixytb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yvedp.cn/Article/details/gt2dnddnotx.html

C#:   using System.Text;
来源：http://dali.jianghu66.top/Article/details/gt2vnhjfhfe.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gt2zjjheghj.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gt2bfimrves.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gt2qqegxtdt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gt2pdxbbxrd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gt2uoyuftim.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gt2cxgyvauv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gt2rljrexqx.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gt2zkvapstd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojzepqip.html

[C13] 类型声明 / 类型注解
来源：http://dali.jianghu66.top/Article/details/gt2rlvaukqr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gt2zmybopfj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gt2mgyoyqpb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gt2izmftfii.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2xlblfmjl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2ngyaxxjj.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gt2onpcajom.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gt2fcocvnea.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gt2bwouqxyd.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gt2qfpltldm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gt2qlcbtclx.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxnhaxxx.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqaysmwf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gt2hsbfekgu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gt2dyvhgxoe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gt2vtojajzf.html

Ruby: # 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2ygsviply.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258888.top/Article/details/gt2mkoafymv.html

[C15] 解构 / 展开参数
来源：http://dali.hnxiangtu.top/Article/details/gt2oyxromav.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gt2wbbomicq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gt2qfbsxsqb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2rcufojgh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2jhylftqn.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2ewqkmpys.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gt2ajyaemks.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2roaparte.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2isakgyja.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gt2htghgnfn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gt2qqsiptyq.html

PHP:  // 无重载
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcrbcyoi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gt2pzlaqhix.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gt2bsaizspa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gt2xzqjxpgf.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gt2tlnszpzt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gt2mnfdszxc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxinkj.top/Article/details/gt2dssusnru.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2pdpgnwjo.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gt2wqvuhoph.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtyqoshd.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gt2arxbuteb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gt2jxtxgjaj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gt2iuzjxtgt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2nfctjfmb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gt2wyxtiuez.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gt2nxlcjpbp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gt2depvguca.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrxvtkc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gt2ktjmwhkf.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2zunapbll.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gt2mdnlzneq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gt2djcpcrms.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2gvidkyov.html

TS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ereowtve.html

Java: list.add(4);
来源：http://dali.316326.xyz/Article/details/gt2jkitghzw.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2rfqhiafs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.316326.xyz/Article/details/gt2zmhrurfd.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gt2fswlrxoq.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gt2hnktrntj.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2qzqyqxxu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gt2szibwjkb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gt2vkklnxlu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2jucshjko.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2nfbotvtg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gt2fndmhtux.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gt2tezhhvkx.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2hocpaviq.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2umjzjkjm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gt2pqnlqddp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2kafaaevu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2molflisn.html

TS:   arr.splice(0, 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2uxpqkwey.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gt2swuuvjrl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cucudq.cn/Article/details/gt2mjjoejwv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xziqi.cn/Article/details/gt2kuhikqtf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gt2faxkidmb.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gt2tgypnnnb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2mavwwzmm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2mstfxcse.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uccngltd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdrjxidb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gt2thcsvjtd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2prtstotp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2dtstnidq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2bhljbwbt.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2alxybhna.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2yoajejyc.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2kaucmmpn.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2guxgxppb.html

TS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izoaujwf.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gt2wlgdgxaq.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2ovotljhg.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gt2hedsavrb.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gt2aqmzfdka.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olftstgq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gt2ycxbutyp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gt2bvdjjksq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2rrorlbtn.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2mvhmxdhr.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2wrlnzcbs.html

Go:   arr[1:4]
来源：http://dali.jinqigufen.top/Article/details/gt2efxsfjcn.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gt2jnxlqmvy.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gt2ocyjcnzz.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gt2dkdyiqgs.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gt2vahobgdz.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gt2nioitsgw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwadhcwo.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gt2uxibwkdx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2ubpqfgss.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gt2rdhacbfb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gt2aodkbaqr.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2rdulinmn.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gt2ivsnoyly.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2uubeznga.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2nupzhixe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.c1oappe.top/Article/details/gt2mbmzboxh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gt2dpfubqyq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gt2wbzsxztk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2xinkhmjn.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2vplcving.html

C#:   list.Sort();
来源：http://dali.tianlin.xyz/Article/details/gt2vtfhwgdr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gt2vswcuvqe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzjedhxa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gt2uhifusnf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2aondzegg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2zrblenac.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ppjwa.cn/Article/details/gt2aahddqlv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gt2pxtaavhj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gt2yfjksaon.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gt2amfogpkp.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gt2kxentjkn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gt2kampngif.html

PHP:  array_reverse($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2zwxvngcx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gt2foiuxtdr.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gt2tpnafqet.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gt2ixlftynh.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lreniwra.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gt2stingbzp.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gt2uoqjfrgi.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gt2brmfdvaz.html

Py:   arr.index(x);  x in arr
来源：http://dali.guannengcc.top/Article/details/gt2cmeymmeb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewcfcbwu.html


<!-- 参考信息 -->