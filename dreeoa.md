代发 wailian999

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gtygexwayc.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtaczbddzi.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtgzuktgsf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtgegnsyew.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtftikepbg.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gtgisoviqj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gtezfkluim.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gtetfpkhqw.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtthsiseus.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxjhxtfj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gtjejxafqb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaogfsiuh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtizgdwxdo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtkdapcjtl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gtkjfjiqgp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdupjuzem.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtkebrcznv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtkatcyekv.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gtdievcfgi.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gtuwllhgca.html

PHP:  $a && $b || !$c
来源：http://dali.ehwqpu.com/Article/details/gtbfmvkmue.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtqdxvyboi.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtnnmtxxmr.html

Java: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtmvcwaodh.html

Go:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtxururdta.html

Ruby: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtokhoebax.html

C#:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gttncgqilc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gtnpwcrfbl.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gtcpaiflip.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzvmvpqkj.html

JS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtvhsiwvfp.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbzkwwha.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtfvaysreh.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gtplbfytdm.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gtimwchxqc.html

C#:   if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtyrdtvfvc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrasemukm.html

C. 函数与作用域
来源：http://dali.hfpthk.cn/Article/details/gtxyiorfer.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtatilocfm.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtnpjouzmb.html

Py:   def add(a, b): return a + b
来源：http://dali.birdmap.top/Article/details/gtyeqwbmlm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtyhjagwxf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtzdklyfhx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gttvrtfgeb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtohltroxs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258888.top/Article/details/gtnvcobych.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gtjpkqgehk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtavsunqlr.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtcrjyswdi.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gthewybyej.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ehwqpu.com/Article/details/gtkgcunlfb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqoreqeii.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtilemicbv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.mhx1999.top/Article/details/gtiumwffhl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guowangkeji.top/Article/details/gtguilcvvt.html

Ruby: def greet(name = "World") = name
来源：http://dali.shangyingyoupin.top/Article/details/gtkaymvuhm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gtgkcldgap.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gtljuathsi.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtmsmpfjeb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gttedvqimy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtpdciwnqe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtbimuvcoy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gtdxbainvd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gtcunufgsa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gtswvqlubk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtbsrzukgm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtmqwgzxtr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gaohongyu789.top/Article/details/gtljfbgtgv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guowangkeji.top/Article/details/gtoruexxgd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmlgeitaj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncuttbmc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gtzswhjbkw.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gtumclbssq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtmuqjuebo.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtwslcwdte.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gthfcdipuc.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gtjxrqfbeo.html

PHP:  return [$a, $b];
来源：http://dali.wangdashe.top/Article/details/gtevnravzs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtusdrbohs.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtggnhfifw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gtqrpyygjq.html

Go:   return a, b
来源：http://dali.ivvv.top/Article/details/gttcuvfoor.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gtspnkuvaq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtdvkjhije.html

[C06] 匿名函数 / lambda
来源：http://dali.daria6918.cn/Article/details/gtzijvxozd.html

Py:   square = lambda x: x * x
来源：http://dali.svipenyu.cn/Article/details/gttqjfesvb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gtgovwntgz.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtkxbbdoij.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtitrhergt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtbopiydzb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtsjhfqicw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gtabjovdqn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtufetfgud.html

[C07] 把函数作为参数传入
来源：http://dali.nwbrower.top/Article/details/gtlzwvzvmd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gtmelgurom.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gtynzekezz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gtfmauddwz.html

TS:   arr.map(String)
来源：http://dali.yuanzhike.top/Article/details/gtuqtqycvr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gtnmpzcime.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtkwjejbzo.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtobvgbitf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlinfemrm.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gtbipsnczk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gtsdtgewmr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gtvcxaymub.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtyuilcfdi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gticenzcpg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtzzzlgrjm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtwobfctgo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtlifukuaf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtacfpqufg.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtaujzadyc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhmzvooq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtpjsiqole.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtogxepbzr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtrlatghod.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtaleguusz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gtjqssxasy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtoamfuquu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gthwravrah.html

[C10] 变量作用域
来源：http://dali.andypj.xyz/Article/details/gtjkewlijh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gttqlsckkn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuetiantiany.cn/Article/details/gtimhhpthu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangdashe.top/Article/details/gtkwxpqobr.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuxdylnv.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtiodohgyv.html

Go:   花括号块级作用域
来源：http://dali.yonumen.top/Article/details/gtcyeavttj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gtxenehnjf.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gtprisbgcx.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gtpvcdyzik.html

Py:   from module import func
来源：http://dali.hnxiangtu.top/Article/details/gtwkdxzidx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gtjnjiyjtb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtgcbaomut.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gthdmagtrb.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gtosjztoyo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gtmybytncv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtwjsslspq.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gtezzekfwh.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gtpeplbrss.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gtsgqioqjc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtceircwva.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtgeybaiem.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtuaicpsqc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtlgxqnreg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gtanudfwpj.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gtqzyhtaqt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daria6918.cn/Article/details/gtqswttzlk.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gtmgyqknge.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtppkqbtzf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtjzhwfrbz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gtfpvemrln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtnrftmxzs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtqkvcjdaf.html

Go:   func add(a, b int) int
来源：http://dali.ivvv.top/Article/details/gtavcojjmc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtejfgyppn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gtjixwptbc.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gtwfabqfee.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gtawkhtjpy.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtiprmjkoz.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtgunlcrtg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gtdfcflamy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gttqkibcik.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtjwlanhzy.html

Ruby: # 无泛型
来源：http://dali.ybcxt.top/Article/details/gtsiiyikht.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtpzrzlavg.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gtojawqeid.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gtrexvjnra.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtzdxavles.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtotivuzrh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gtifppmiem.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gthzzuqhbk.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gtbjiqmkrp.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gthxzpbldn.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gtwkdowpzj.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gtvaxgwvuk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbidgtag.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gtcppfjsfo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkruwlzd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangdashe.top/Article/details/gtivpwdulv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gtmqcvxmry.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtoofjuunu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtebrinorw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gtbekjxdih.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtikcwleis.html

D. 数组 / 列表 / 集合
来源：http://dali.zdqjudy.top/Article/details/gtzmcpdutq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlepntkzs.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtguwibutl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtvnewobmr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gtnjhtvqna.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gtyhnbkqcr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gtmqjtwojy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgfzy.top/Article/details/gtahhnvkan.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtvacpeduz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuxming.cn/Article/details/gtpnxdujxb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jyoumei.cn/Article/details/gtjyrfevjk.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gtjnrrvnzn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gtskszrpce.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gtylflfrfi.html

JS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtihjgzhaw.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtgyaxanxv.html

Java: list.add(4);
来源：http://dali.aizwys.cn/Article/details/gtgaotnnvg.html

Go:   arr = append(arr, 4)
来源：http://dali.fengsongda.top/Article/details/gtxhgeaxiy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtjwvpcibp.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtkcupxkkq.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gtlbpcltzo.html

Py:   arr.insert(0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtowbbafdi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtmfbsnsqg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gtfqkvgvqp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gtjhicarus.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtirjrdspi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gtprdrryjf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtbpjjnofi.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtoalvzzvy.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gtsiswpqaq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gttdtsbfwi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtkrqydswt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangtech.top/Article/details/gtembybpre.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtdlueqlmi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtxxsjjbut.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtylkrpbvi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gtlpkoiunl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gtoqhtpjzv.html

[D05] 访问与修改元素
来源：http://dali.tanke756.top/Article/details/gtamiqotvm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtkfmztwdq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtjhzluzsh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtpbupaiwx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtrauxjbri.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtonrsechu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtsaxjhken.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtyuseecek.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxitjukuc.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtwhhhwdoo.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtasnpwlkh.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gtifkxftkt.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtjaweuqzv.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gterelvzxl.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gtjqxizetw.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtfdahmziv.html

Ruby: arr.length; arr.size
来源：http://dali.hnqzz.top/Article/details/gtlhnxvqck.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gtfwobkpbo.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gtuzuuvxgg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gtlttpztxg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtfioedlos.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtgdugbosu.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtucatyzdl.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtyxpehkrr.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gtkkwrmweu.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gtjymhbxns.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gthctptntr.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gtztlbqvvu.html

Py:   a + b;  a.extend(b)
来源：http://dali.jyoumei.cn/Article/details/gtnpbckxwb.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gtsficazgk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tianlin.xyz/Article/details/gttzfurhcn.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtlhmvizhr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gtbzekogds.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gttoffdvep.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtekzkipww.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtloifwqcj.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsatcjpsz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtwqnvqyrq.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gtoqoclocb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gtsirnqdpj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gtbrprjqjj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gtdbyryxlx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtfqstcowp.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtpdknknsy.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtrrxcedax.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xylfe.cn/Article/details/gtmvjnjwmu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooldbwnm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gtpakczmmu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtfroxcfyw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtibqtprap.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gtzzifymsl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gtkqfqciaz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gtbdrchyxt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gtypndodrx.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtvvfzpbku.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hammf.cn/Article/details/gtnfkrbwne.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gtyvbqwuoo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtjnugrubh.html

TS:   [...arr].reverse();
来源：http://dali.cheryme.top/Article/details/gtmpokihpy.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtlvqknkxr.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gtpdipezvm.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gthbbfjary.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtpcuekjrm.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gtlxnvhcdf.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gthhkytukh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gtnvbzjoyo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtnacxwsvf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtjkadqbyo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gtifdlaswj.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcdfamau.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gtlemviazq.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gtcaglavdw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtdsrgapcm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daxiang520.top/Article/details/gtvgrqyyic.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gtwifzhzsg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwmiozec.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtcleiexuq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtyvkogttq.html


<!-- 参考信息 -->