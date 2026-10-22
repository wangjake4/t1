代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jianghu66.top/Article/details/gt2pelhzixp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gt2hpftgmhd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.316326.xyz/Article/details/gt2fprmmrgk.html

[B12] 跳出多层循环
来源：http://dali.iojbl.cn/Article/details/gt2yadkawei.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gt2sscchiaq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gt2rseehxuw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gt2lcbqnseq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gt2lvkoqbqq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2mgjqxycz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gt2yuupjaha.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gt2gdmuszzn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gogol.net.cn/Article/details/gt2aqlwpbys.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gt2vfngscdx.html

Py:   isinstance(x, (int, float))
来源：http://dali.yonumen.top/Article/details/gt2likyaowk.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gt2vasyhlpg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gt2cbgwynjd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2otkfxdda.html

Java: x instanceof Number
来源：http://dali.316326.xyz/Article/details/gt2kmatllmi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gt2pxwgjqrd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnqzz.top/Article/details/gt2xwkdreju.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gt2xwztyrbl.html

[B14] 判断值是否在集合内
来源：http://dali.yangfankeji.com/Article/details/gt2qtobmxxl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ersxhjyk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfgzxlyv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2wzaeprmn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2wbaeoxal.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2plermhoz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgfzy.top/Article/details/gt2tvfajtrj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gt2tnxzrovn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2xjxipmmv.html

[B15] 布尔运算与取反
来源：http://dali.jlsjyb.cn/Article/details/gt2ipjgggvm.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gt2fxlohkkb.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gt2hvcnhvpl.html

JS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2cyvjhyak.html

TS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2atbouioy.html

Java: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2brubheyp.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdkgpnbk.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2rsagaxud.html

C#:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2krglvynt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daria6918.cn/Article/details/gt2qahbuzdo.html

Py:   if not data: return
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxnorhgf.html

PHP:  if (!$data) { return; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wbnzqtle.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gt2qnbukinh.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gt2zphxqxrf.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gt2akhavrhq.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gt2janqilxg.html

Ruby: return if data.nil?
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfzpbcuf.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gt2saqctoit.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2xhswuaek.html

C. 函数与作用域
来源：http://dali.yangfankeji.com/Article/details/gt2utaicxjn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2zammuxxn.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2pwpozdzr.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigfzy.top/Article/details/gt2fyjodtpd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2wnjlboqv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2mpotnsgb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2btqqdtva.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2epmqvmiv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2kxqtpnub.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gt2ltbcvhad.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2ieoquhdq.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2dererumn.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gt2dqwoojxq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gt2eftkswcn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2txpnmanw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2hihigaal.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.c1oappe.top/Article/details/gt2mmjuwxap.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tianlin.xyz/Article/details/gt2wkarixho.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gt2qrftqcai.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gt2mjfvnqqa.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gt2liaomqub.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gt2gpvzqoxy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojrbidac.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gt2fphmhuec.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gt2jivxyada.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbjvurog.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gt2ffihxhgd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gt2imnlquyb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gt2haprwikr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gt2dcmqqlqe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gt2wwkuqoru.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gt2asnitmdy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2knzxrjzf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gt2shyrdgux.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gt2khwaspcg.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2blhwumpy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2xeolawgj.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gt2nixuqslk.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gt2uruoiefg.html

Py:   return a, b
来源：http://dali.ydzc1.top/Article/details/gt2udciedzc.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gt2spuvpcur.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gt2lrtsddkb.html

TS:   return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gt2lopykjpw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnxiangtu.top/Article/details/gt2vifpxqzu.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejnmhtlg.html

Ruby: return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmgpcnlr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gt2rhazsxuj.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2kyqwvzbb.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gt2oiuzrhod.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gt2olaizyds.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gt2ggzzoqxh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dimuiurg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2qpqgsbmv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gt2xciaftfd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpkccnva.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gt2husrxlgm.html

[C07] 把函数作为参数传入
来源：http://dali.chenzaomai.com/Article/details/gt2swbbflow.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gt2avxnyeda.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2uxvzjxmy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yueranfly.top/Article/details/gt2fpwlwsyc.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2jadnzezh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2yvxadrig.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gt2xjjmbkyj.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenzaomai.com/Article/details/gt2gscgroqh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.vqdsnc.cn/Article/details/gt2oqeqxzfj.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gt2hlfcbbvd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gt2jzkxfyzm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gt2jibrncfi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vlrhghrl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2slyjyjfb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gt2pbgsmpkm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgfzy.top/Article/details/gt2mxcupbkx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cqqwz.cn/Article/details/gt2qrbbjcia.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zedrlzrh.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gt2ljreclug.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gt2nvbaexjy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shuidangran.top/Article/details/gt2mchqdjmg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gt2pbwwuszn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gt2ngtbhsuc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gt2fubajvee.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gt2imeaouok.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2fppwammc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gt2jkbvodmd.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gt2twulhwhv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ehwqpu.com/Article/details/gt2fpwadxlb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gt2azzbaflo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2tqbacqve.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gt2metordqb.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gt2jsjppudn.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gt2yulmzuzj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gt2wpclrfle.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2escdvbqn.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gt2hxdnjdoa.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gt2kwftbvsj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxveglom.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gt2kzidrlmt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gotoacloud.top/Article/details/gt2ojnepqac.html

Java: import java.util.List;
来源：http://dali.yangfankeji.com/Article/details/gt2rmmjlwow.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2kekqlysl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.quarkkingdee.top/Article/details/gt2uxzsbawp.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gt2uglaiudm.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gt2uctvboqy.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gt2zcxegang.html

PHP:  (function () { echo "run"; })();
来源：http://dali.birdmap.top/Article/details/gt2ezjanyqm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gt2ygqiigez.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gt2uccecetq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxinkj.top/Article/details/gt2rrferkwl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gt2wufyqycd.html

Ruby: -> { puts "run" }.call
来源：http://dali.sxryk.cn/Article/details/gt2yodqxduq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2llwmajgk.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gt2rtqrgoqk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gt2szfdwmgn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbcpyoqs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gt2oqaxmhyg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2hzxvftyr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2bdxlhwyo.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gt2yahcghlk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gt2akfjelol.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gt2lgxpueti.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gt2wjowfwkn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gt2ucjbxrpk.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gt2jupfbqsu.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2nmssklbf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gt2bfoyidfx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gt2xiuedxfm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gt2zrohzbnk.html

Ruby: # 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2cvhrpomi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.snrcjt.cn/Article/details/gt2crqgjfrs.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdphwzzc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gt2gldfivkz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfpzhfff.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2syevuwsh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxxjwfgm.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gt2worahljl.html

Go:   // 无解构
来源：http://dali.dashuyun.cn/Article/details/gt2wlvdipmz.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gt2sxdljuqq.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gt2pdcnazvq.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gt2qqkowgzf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gt2uqalinrg.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gt2ohtvdcns.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tian-w.cn/Article/details/gt2wavevdba.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gt2kbpliimh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gt2iadgvask.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gt2qhcltrrp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yangfankeji.com/Article/details/gt2bzdsqoyl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2lnroiwer.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2shvidefz.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gt2zlqznenm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2zhpimamb.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gt2xzfnvevh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gt2egplkvon.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npadshjp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2ubzjcdck.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gt2sfqrreba.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gt2uguifpar.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ciemkcbp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.quarkkingdee.top/Article/details/gt2svtnauel.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gt2dyawolyq.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gt2ahmzwsxd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfitzgsr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gt2uskpngep.html

JS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gt2amvwmtsy.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gt2qcraabio.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gt2bbroafdn.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2ymdhregx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gt2wopwqxua.html

C#:   list.Add(4);
来源：http://dali.chenzaomai.com/Article/details/gt2dnigklzw.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gt2ittcyjrn.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gt2ltysbvxt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gt2woxkdtxy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gt2ebdbgjha.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2gmlhvpox.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2rqhkkafs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gt2igdskvvp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sysykeji.top/Article/details/gt2ktaxoxae.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2uapmugyy.html

[D04] 删除元素
来源：http://dali.jyoumei.cn/Article/details/gt2abenfrtz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwjbsim.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gt2cuwlocfo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgfzy.top/Article/details/gt2bsipxcbx.html

TS:   arr.splice(0, 1);
来源：http://dali.cheryme.top/Article/details/gt2athmkqsx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwfqmhgq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gt2nloipgtk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gt2ynmyleiu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.c1oappe.top/Article/details/gt2jbjwvsgt.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gt2rxrkoyej.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2dosmcnpj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2bdchhzqx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2rydghddj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gt2ddsckayd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcueryri.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2gzjyzvvn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2bjmcbiap.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2hbjaznye.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gt2ibvijnxh.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gt2dewxuelk.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2tkjpazvz.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gt2bzpthyob.html

TS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gt2wfdbebjc.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gt2paxnfaip.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2lcgytbko.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2hcbciijt.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzpuhzjl.html

[D07] 切片 / 取子数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2veayqzgs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gt2wywzlhaa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gt2vsejrfvo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2zhoozpso.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gt2vfcvrmws.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2cnvgaqaf.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gt2numaawgh.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuxoczwv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2llwinvvi.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gt2zadlpavj.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlenaqtf.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gt2baugicmb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gt2hybyatoz.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezqnalsq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gt2rqexhinh.html

Go:   append(a, b...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qeqqkyks.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cashguo.top/Article/details/gt2uqkdygjz.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2lduzwjih.html

[D09] 排序（升序）
来源：http://dali.yongpay.top/Article/details/gt2bqdmcbue.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2didmgjvh.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2imdwoajb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gt2kpvuniey.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gt2spvqnygk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gt2wfblvcfv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gt2fwsojzmj.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vliyohka.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gt2ksyqwina.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gt2hufibapo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gt2toinxjrh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bquhjpfi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2ughtkmfs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gt2ehnaagln.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpoyhmla.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gt2eahcmslm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gt2zgwfdiyj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gt2udtqqpgg.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2lawdmfqz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gt2bmguyekd.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2kukadlyc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqaxsuok.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2vujucyki.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gt2txdguwtd.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gt2npterykt.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gt2tkcbllvj.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gt2rzobwdtn.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gt2tazlqozu.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gt2pbzjdtox.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2jsicrsgp.html


<!-- 参考信息 -->