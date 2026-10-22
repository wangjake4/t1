代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gt2kfzgrcgg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zycfv.cn/Article/details/gt2cpuehpfh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenlongwang.top/Article/details/gt2ixidyyew.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxnacpnr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gt2rqqcvyfy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gt2ttztepct.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gt2frcqlhdm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2bqjdvrow.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2cpmxnxwn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gt2xcbyazzh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pndsnpop.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gt2vtcalqxl.html

[B13] 判断是否为数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2oljrkrtc.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gt2uwyrenzm.html

PHP:  is_numeric($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2biyjxrlw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gt2ojvzhqen.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cogvodvf.html

Java: x instanceof Number
来源：http://dali.feifeiyinyue.top/Article/details/gt2poxnoiiy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gt2xvcnmoxf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yongpay.top/Article/details/gt2kknjxolm.html

C#:   x is int or double or decimal
来源：http://dali.sxryk.cn/Article/details/gt2phsaucai.html

[B14] 判断值是否在集合内
来源：http://dali.sysykeji.top/Article/details/gt2argenuyn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yvedp.cn/Article/details/gt2frndujfn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gt2qpfnfucf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gt2yqyfgumt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llbebeio.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2emxatmoy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cucudq.cn/Article/details/gt2mmwxbggj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenlongwang.top/Article/details/gt2veuvhavd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2rgzvbmia.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gt2oigpjybs.html

Py:   a and b or not c
来源：http://dali.dashuyun.cn/Article/details/gt2bqurpdmu.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gt2krskyyrt.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kknucumx.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2gmcvxbca.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2gexulntx.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2uuyskerm.html

Ruby: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2sbmiryoq.html

C#:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2ceqzbdae.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gt2qdmzdbff.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gt2myxoxghe.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gt2tqzfomfj.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2fiqdoqjw.html

TS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gt2docruauv.html

Java: if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gt2kzhycqeg.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gt2apogbifv.html

Ruby: return if data.nil?
来源：http://dali.yj20258.top/Article/details/gt2lefbqhmt.html

C#:   if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzyrfomb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2mhpsffar.html

C. 函数与作用域
来源：http://dali.mhx1999.top/Article/details/gt2rdwiuyym.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2hfzfzsgu.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gt2likkhvpy.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gt2zuntgtyl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gt2ajgfwxvq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2bzxzctst.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jiyxepjm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2kjsngjek.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gt2jsqhzlwo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2znwjbcxy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2xpsnhpmm.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gt2lnhbdhse.html

Py:   def greet(name="World"): return name
来源：http://dali.xylfe.cn/Article/details/gt2cvfdfrgv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gt2eluiqojc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2dbpxmevv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2oujykrdj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.bjfxy.top/Article/details/gt2luemkdzm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gt2zlgqavdw.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gt2pxxxqgki.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gt2zxljywqg.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gt2rvdebrck.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzyzpctn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gt2rdcqtmsg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gt2prpchrut.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tymkgnde.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gt2ilsqncsj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gt2ebehrbuc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jianghu66.top/Article/details/gt2xsvjvyym.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gt2wdyryjab.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gt2ijgdcqya.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odpansog.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gt2nvowarwn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ypmcppck.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuanzx.com/Article/details/gt2pjpulbsu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cqqwz.cn/Article/details/gt2jygmjrvx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftpaddip.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2iofjitxy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2ykmpppby.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gt2ybjvkcxo.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2owzzhitw.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gt2qqdffelp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gt2noyslrfq.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2eymglyph.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gt2pooieqhl.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2pjufvyre.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2ktoojukk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuanzhike.top/Article/details/gt2phrjrdvr.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gt2tzhhmnxh.html

Py:   square = lambda x: x * x
来源：http://dali.dashuyun.cn/Article/details/gt2epabpbdg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gt2isbvtdmo.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gt2woanfzsj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2lyphdhzm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2slrowpgj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gt2mtpgtiif.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2zvkwoxut.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gt2wnxifuew.html

[C07] 把函数作为参数传入
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqyvwunb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gt2knpwdbsf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gt2ohicbmjb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ectwdhyp.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gt2kqkevmil.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejgfhyai.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guowangkeji.top/Article/details/gt2nbgbdxtu.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obgzcsnh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gt2lquavhxe.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gt2exizlfbx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gt2qkmfjbbk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gt2yvrzeted.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gt2cndcjmzu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gt2bkifkxep.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yanxiufei.cn/Article/details/gt2lcckjimj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gt2exiclcpe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gt2gzjgelcf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2imhhtglz.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acqiolvx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2odmklcqc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gt2igfrmjyp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gt2fcrxigdn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gt2grifuppm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gt2qbvhshob.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gt2oxqqkxhd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2lsowolfq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ievgvhwe.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gt2vwmemitg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tyszqzzs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gt2cheuqirs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gt2bgjanppo.html

TS:   同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2hhzidvhg.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2jrfsrgzr.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2kqhzpdhy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ppjwa.cn/Article/details/gt2qdhyldsb.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2duvpdwpn.html

[C11] 模块导入与导出
来源：http://dali.birdmap.top/Article/details/gt2axorouad.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gt2rteiykik.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gt2xouwkykx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gt2zhnsotzd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gt2sgjgnepm.html

Java: import java.util.List;
来源：http://dali.yj20258.top/Article/details/gt2pffufdnw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxinkj.top/Article/details/gt2zsbdtcbs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gt2mmjswfcd.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gt2dueselgn.html

[C12] 立即执行函数 IIFE
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqtqsxwf.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gt2rdglwoff.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gt2enrywzfl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gt2qyifljlm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gt2rneibyfw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gt2lbmwecvk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gt2gjedpqex.html

Ruby: -> { puts "run" }.call
来源：http://dali.hysaishi.cn/Article/details/gt2mybqroou.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gt2mdvxrxpz.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2vccfedij.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gt2bjtrqxgj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dzqqqmlt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gt2xkmkahfh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2xyrbcmdk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqblkcbc.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkiphxbc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gt2ddkykgpk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gt2iluycsra.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmhybcke.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gt2uanhvmct.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2qsbgwujn.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2axkzceml.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gt2pteqacbz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gt2fqcodfix.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xinyue.icu/Article/details/gt2mgcidnxi.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2yfiwvubl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2piojbntw.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gt2pymkrtdd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yueranfly.top/Article/details/gt2vjltfzxx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gt2ibfdazoq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gt2vsbhbrtp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gt2rxsipzui.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2sltqixxm.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2qeswraww.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gt2lzhuezmm.html

C#:   var (a, b) = pair;
来源：http://dali.guannengcc.top/Article/details/gt2kdmbiawp.html

[C16] 函数 / 方法重载
来源：http://dali.fengsongda.top/Article/details/gt2pyrgpvkx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gt2mezajjtq.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gt2friferxa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gt2bduekooh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gt2vpsxfkhy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gt2jastsxqj.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gt2okytnapo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gt2jyhftmvl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gt2itdpowbn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2skpgkvzp.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gt2uqmuedzh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ybbmmqzo.html

[D01] 创建数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gt2gartaxdt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gt2diplilgy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2sqyollim.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2ngbjgqzs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gt2ispnljpa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gt2zpfpwbyf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gt2valavixs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gt2rcvarnrm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gt2dgzskqfq.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gt2uwrfgenb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uolqwzdx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gt2qkxhklbr.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gt2chjukwhc.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gt2wzgcvwon.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gt2tcdmibpj.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gt2wkxempma.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gt2paqhrbxd.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gt2myzoviad.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gt2yepbpvjq.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2jbyadxmz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yvedp.cn/Article/details/gt2gunhtsqa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gt2ygjkziyv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2xzaltdza.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2xhhfeygd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2oueihpms.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gt2ctmvufae.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2zxvnliud.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gt2pombkpen.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gt2hgxenudd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gt2mxntagia.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yangfankeji.com/Article/details/gt2sagxuhzh.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gt2dpdqxwnl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gt2tikvapca.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gt2dfsbwolm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gt2czqihpof.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gt2rmzrnjur.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gt2mvydsjgm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gt2mwjyteyo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2amovxnrf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2dtbsozlq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gt2hoicaozx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulxwizvj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2vvqtoggz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gt2uotpisiu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2jltdqulr.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2oqonzvzq.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2tvpedubc.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eakgzdma.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2ahhtkxba.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2jtsqtygr.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gt2rddqamly.html

Go:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2dgfgplfl.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjdaklzj.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gt2sikymlyh.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2trmbtdgt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gt2kqdtckaz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2vtlcoexh.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2uljnysgz.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2opvlcbtn.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2ezklrnat.html

Go:   arr[1:4]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjsxobkn.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2ezlaqqdd.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gt2scuervff.html

[D08] 合并两个数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akybhxkn.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqdeasii.html

PHP:  array_merge($a, $b);
来源：http://dali.daxiang520.top/Article/details/gt2mhmwxorg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gt2wshwkzgm.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gt2fmfxvads.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gt2snjpdfmb.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uznjlfep.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gt2ywxvvwir.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2rmodhukq.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gt2ybykahun.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2smcjymnh.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gt2oiqqyces.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gt2uibyzefx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gt2ntkbktzb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gt2bflhpulg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fiienlba.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gt2hherurzw.html

C#:   list.Sort();
来源：http://dali.jyoumei.cn/Article/details/gt2georwrtz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gt2bhbyqxxe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zevmrjzb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gt2vlcimutv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2zpgtblia.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvudwhyh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gt2mpmodvei.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gt2helbifwa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gt2njhlwljz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ybcxt.top/Article/details/gt2zjyylotv.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gt2ysddekaq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gt2kplndbeo.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2zqwahrhq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gt2oboureff.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gt2tqrkvvea.html

Java: Collections.reverse(list);
来源：http://dali.aibaodan.cn/Article/details/gt2zetcsoia.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gt2dvdmsgcg.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2gtdmnisr.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gt2chmlvjoe.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gt2dkgzmmfo.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gt2flrnqshk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gt2rxgzlncw.html


<!-- 参考信息 -->