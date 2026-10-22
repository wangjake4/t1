代发 wailian999

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rniwnflk.html

Py:   isinstance(x, (int, float))
来源：http://dali.aizwys.cn/Article/details/gt2dpejxltc.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gt2tgadkskg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gt2ccctzmgg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gt2xmdgfqnd.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztpcgduc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gt2oidyfliw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gt2hbfppnbm.html

C#:   x is int or double or decimal
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhstview.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gt2mcnnhdls.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gt2gsvhuxuc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gt2hgdzatxd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpinuibq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2qwsvctwn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2gnigafot.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gogol.net.cn/Article/details/gt2owbedhaw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yueranfly.top/Article/details/gt2jvwzylgl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2uqqiwvsr.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gt2amujgcyg.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gt2wvafbcms.html

PHP:  $a && $b || !$c
来源：http://dali.haohaochexian.top/Article/details/gt2hqhglnjb.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2xhgzavlw.html

TS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2setkhdrl.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2jhxvvgtu.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2pavxvgwa.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2kuuzjtcw.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2haccwzcj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hfpthk.cn/Article/details/gt2tziggpab.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gt2bbgwakiz.html

PHP:  if (!$data) { return; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bkxribha.html

JS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gt2gfhojixb.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyfbawya.html

Java: if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gt2ikkkzvdq.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gt2mlrdfzvh.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gt2vwgqsgvs.html

C#:   if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gt2nsmmvuoa.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ltmwuamn.html

C. 函数与作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2yclufcfg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2svgzwxog.html

[C01] 定义函数
来源：http://dali.ybcxt.top/Article/details/gt2mqpociuh.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2hkhbrynj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gt2qzldvhez.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2nnmajjkn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2tqytrode.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2zzfqzfia.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2mmmcevlc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gt2hbjynxhx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2jtlpueqr.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gt2ayzorkhu.html

Py:   def greet(name="World"): return name
来源：http://dali.birdmap.top/Article/details/gt2jfxrautw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gt2xzkokjaw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2izczgsfh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2enovewdi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gt2lpwlxkja.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dianchejie.cn/Article/details/gt2dwnvzyfz.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gt2ukodreqq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gt2ocularxh.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gt2cojmmilf.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangdashe.top/Article/details/gt2xyhducfe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gt2wocegzjl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2pvmgwnuh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cijuqrqh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gt2vqwxppot.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shuidangran.top/Article/details/gt2vobzfvct.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gt2zumxnlcr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gt2lpzynnvy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gt2rirfkwkm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gt2hkmlzhta.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gt2jsdetguv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2qwxhtevp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gt2zpfxvybv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gt2whkgzqiu.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkwblled.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2vuqwsmqm.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2smgykoya.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gt2ruzdfonc.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2fgdacbmz.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gt2dxcgylxq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2zazonwze.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gt2xcrdqzmz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gt2mtsdxrek.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kxstkibr.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gt2jqqilfgn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxvrnihf.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhlhozko.html

Py:   square = lambda x: x * x
来源：http://dali.jlsjyb.cn/Article/details/gt2gjfeqhtc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gt2djuotjjw.html

JS:   const square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2cwzirdsa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2usjherdq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykgutgju.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pycfn.com/Article/details/gt2hmtrcmpq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.redwolf501.top/Article/details/gt2derlzhkb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2itfliiju.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gt2rrabizdc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gt2ihphpotx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2yetnagmw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gt2affxkfsi.html

TS:   arr.map(String)
来源：http://dali.hysaishi.cn/Article/details/gt2nyleglkk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2ksfrqhom.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gt2bpvbzcxz.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gt2ovbgskhk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gt2xhriplea.html

[C08] 闭包
来源：http://dali.hfpthk.cn/Article/details/gt2cetcuwze.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gt2ricriqru.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sxryk.cn/Article/details/gt2qgdmhdyj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gt2mouphtsk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2lxjsfalm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2upeycitg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gt2xioblzsx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbqwisat.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrjirgmf.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gt2psquxhqb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gt2cyruhqgx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2iaajcrgn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2kahnsxsx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gt2xyytgwbq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gt2wooxohqy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gt2xcwwxvyw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2ukfajgqs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msdnlvel.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gt2ojplmwpy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gt2rapreyfa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gt2umhgblda.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2lborfeza.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2eliomeqk.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2orcmbhsi.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2dgbnzkue.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gt2zauxaboh.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gt2xcsppvuf.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuywgvg.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gt2dhaoarxh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmxrkbbz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gt2yuxjfxvu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gt2tbvmxdtt.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gt2untrfbpo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ppjwa.cn/Article/details/gt2lnyojnsh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgtisnqe.html

C#:   using System.Text;
来源：http://dali.ivvv.top/Article/details/gt2qvxundnt.html

[C12] 立即执行函数 IIFE
来源：http://dali.sysykeji.top/Article/details/gt2kjbyavqk.html

Py:   (lambda: print("run"))()
来源：http://dali.aizwys.cn/Article/details/gt2dpfhzkzq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gt2klfxcivp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gt2efphwrbe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gt2lofshcku.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gt2huoxasbw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gt2cswtxyzm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gt2qfvwfcyi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rszrsqqu.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewiyqugb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gaohongyu789.top/Article/details/gt2manbfvot.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eyjobbtp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gt2xgkdujlc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2ttmncnyj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2cxozogvr.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gt2guandjkp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gt2qnyavfae.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ydzc1.top/Article/details/gt2xsjjixav.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gt2nvupauip.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gt2kxzayapb.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2wuakkaie.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2nihqbnbs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hfpthk.cn/Article/details/gt2ozdspnvh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gt2wesoxplf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gt2qbeocgnf.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2migfoxtf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gt2bctafmdq.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gt2csvgdkmu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cheryme.top/Article/details/gt2pshscdbe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gt2nyqrpsop.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2knqthsry.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gt2wurujqub.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwuyxrys.html

Go:   // 无解构
来源：http://dali.jinqigufen.top/Article/details/gt2icecttid.html

Ruby: a, b = pair
来源：http://dali.jqgfzy.top/Article/details/gt2oikfqvih.html

C#:   var (a, b) = pair;
来源：http://dali.chenlongwang.top/Article/details/gt2xbgiihss.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gt2rvzhrwpv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtfycszf.html

PHP:  // 无重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfghmpub.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gt2igdzngry.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gt2jogrszpr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ohzqipzp.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gt2peqifjdq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgqeixud.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2tfgmwuyu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhywrmdb.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gt2omxtxvkg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2divwadiq.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gt2vxuozwsb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gt2jvemacyo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gt2gvatsdlw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gt2cvcumvyf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gt2sekrugpp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cashguo.top/Article/details/gt2wthncmsg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgjdudw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gt2eglgjryb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gt2twftndir.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gt2abpmrzji.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gt2bqkzezjl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gt2xijkzktw.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gt2yxpzwgoc.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gt2ftqpcpqe.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2farbmmwf.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gt2cztzgrtv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gt2tenwjemv.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gt2jxhiuxjr.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngbsptvs.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2lufalqhu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gt2emzgzbtx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gt2szewylea.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2nwypmrvm.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2shndlkxa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gt2dblhmclw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.mhx1999.top/Article/details/gt2zaasutoa.html

C#:   list.Insert(0, 0);
来源：http://dali.gzhubu.top/Article/details/gt2oyhpyuna.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gt2nzuyvvyj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gogol.net.cn/Article/details/gt2bjwysfsy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2sslfstzz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gt2ejzmtfey.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gt2yntiqbag.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gt2zartmcnn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gt2wqtgltgz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gt2zwkdirss.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gt2umwdxjle.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gt2biffogig.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2xejvkfeb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2nhupncmy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkjjnkdz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2amwdawqj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gt2gwlrzzca.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gt2xnkzpxxy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2xheoojnu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbvolglf.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gt2xssmoues.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2uydnoxgj.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gt2jsokirvm.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gt2uqbfnzqv.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gt2dbltjqrc.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gt2msfdzgat.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2bunsuzym.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xyfajckv.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gt2jxdfpxkl.html

[D07] 切片 / 取子数组
来源：http://dali.meibo888.top/Article/details/gt2wwpagjrl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gt2fqfyypgi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gt2lytvptpv.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gt2wbsbzrmh.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2ejwzottt.html

Java: list.subList(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2oglsemnp.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gt2wmbdyxlw.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gt2sthzgvhd.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kchwuqeq.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gt2eenqhiej.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gt2scjpvmyy.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2phrzfwhl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gt2exirjdty.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gt2sigeaosw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twviobec.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gt2jvbvkupl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gt2jprlbhsv.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2rvxbzojh.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gt2zrwnrkrk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gpxwoqwb.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gt2wqwoqcom.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2nljaruka.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gt2wkrkelkv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gt2gqpqhcnh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2efrdziir.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwtoeokv.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gt2noaulswh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gt2bvvxxkin.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivtduuib.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gt2crxxzhif.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gt2xuqpdiqw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2vfclvbpv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gt2dcqwczsn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yanxiufei.cn/Article/details/gt2qwcpuvgh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gt2qnopsllf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gt2fkhglqeb.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gt2cirffibq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gt2gelyppki.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2nmhcmoks.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gt2uoysrjuj.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2reztuglk.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gt2udkqeacv.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gt2btvvhdsl.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gt2tymjuriw.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gt2zpwuduxl.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gt2ncgvmjzs.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gt2bvcvgvui.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2doldwdfk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2slvjemyy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2hmpytxgm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gt2xffdigrl.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qerqlarg.html

Ruby: arr.index(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnpoaikg.html

C#:   list.IndexOf(x);
来源：http://dali.tanke756.top/Article/details/gt2blvaaklp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnbmibah.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gt2waageevf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gt2ptfepstg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2wdcmazer.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kpaabwwj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2pszecnig.html


<!-- 参考信息 -->