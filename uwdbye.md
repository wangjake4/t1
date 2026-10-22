代发 wailian999

[B13] 判断是否为数字
来源：http://dali.hywenlv.cn/Article/details/gtxkovzlml.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gtfxyplbal.html

PHP:  is_numeric($x)
来源：http://dali.andypj.xyz/Article/details/gtqsgbmfqw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtletovoot.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gthpaadkwm.html

Java: x instanceof Number
来源：http://dali.zhixingplan.top/Article/details/gtokpglasc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hongshengwenyu.top/Article/details/gtfhiajhiv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shzxlz.cn/Article/details/gtxstuacsb.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gtqzmqxfmk.html

[B14] 判断值是否在集合内
来源：http://dali.vqdsnc.cn/Article/details/gtnjimynhk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gtwfjibyzw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gttubbpgds.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtiqogeaqb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtcloymtje.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtsqmskirv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangdashe.top/Article/details/gtbicdlzkq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtpdymlujd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtjdayvxbn.html

[B15] 布尔运算与取反
来源：http://dali.ppjwa.cn/Article/details/gtqohpjwyv.html

Py:   a and b or not c
来源：http://dali.ivvv.top/Article/details/gthgajeyrs.html

PHP:  $a && $b || !$c
来源：http://dali.aibaodan.cn/Article/details/gtquwqarum.html

JS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtrgnmnuyi.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtnkjcxjkd.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtquuibycq.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtxqkfxkvs.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtjbshwqnz.html

C#:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtwpsgfvwp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gttsthwogr.html

Py:   if not data: return
来源：http://dali.cqqwz.cn/Article/details/gtuxjyuhcz.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gtiavzytar.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxaxzgujl.html

TS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtuubiwwdq.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtbfjbznvi.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gtrzuliypk.html

Ruby: return if data.nil?
来源：http://dali.zycfv.cn/Article/details/gturqkxdbk.html

C#:   if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtdanmxzba.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykyohrbm.html

C. 函数与作用域
来源：http://dali.tanke756.top/Article/details/gtcwiuitqk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtyobrdobr.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtkxenhrdx.html

Py:   def add(a, b): return a + b
来源：http://dali.yuxming.cn/Article/details/gtlryjlfrp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtpgogbkcr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtlqicvclu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttikqwgpe.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gthhkkoaaw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtamvhjlpa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yonumen.top/Article/details/gtewklwxrn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtvyfufjxz.html

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gtwehjbvbv.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gtabucwcia.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxdqywaec.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtdblhrpbq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtgphepnpu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gtkleeghul.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtofposquc.html

Ruby: def greet(name = "World") = name
来源：http://dali.pengpengdd.cyou/Article/details/gtwwvroecm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gthclgebfd.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gtyxqscqki.html

Py:   def total(*args): return sum(args)
来源：http://dali.redwolf501.top/Article/details/gtogbdcmvm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.mhx1999.top/Article/details/gtkcoxofru.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtynkhctzb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtoazbkhwb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gtuumzqfhc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.redwolf501.top/Article/details/gtzcyzhnre.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ppjwa.cn/Article/details/gtaphpxlqo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gtomhyfwdv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gtcsuxdcwc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gtyqemkkfu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtvbdkyclu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtrtgohzgi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gtmwyibefz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gtxtszrrll.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gtnrdyvvss.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtcpmtgyoj.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtedmkbsbf.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gtpxjrrjem.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtrssfshug.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gtbmziwifb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtvztcdquc.html

TS:   return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gttcdathet.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtodlgywjl.html

Go:   return a, b
来源：http://dali.cashguo.top/Article/details/gtbkdymqvk.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gtipowrjkm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gtprytcyzq.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gtiredyjqn.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gtmljewdom.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.smart0.xyz/Article/details/gtusnantbd.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtnvzqxwzl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtzcafssuu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gtfvarjqof.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gttqipdelf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gtkyeunmga.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtfojxteub.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gtemffsgeo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tian-w.cn/Article/details/gthjzccnur.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gtelzcbpnf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gtbdvbuwjt.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtcjenvcak.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtahvykmlw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqkhkubk.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtzvfmwtfk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cdnleiting.top/Article/details/gtpbosnajh.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gtnavghvwb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gtmizallfm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuxming.cn/Article/details/gtlizskqgc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtjwjdxehz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtzsvodydo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gtavijqczm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gtywwwludb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtqdfsgbwk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtivffeurs.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gtcysrnast.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtvhnmssec.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtuzabmbmb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gttnmfxotp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtkglocsql.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtcifkfisc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gtbivgvzoo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gthjmxjhyf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtmjivusmz.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gtuaylukbo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gtcqeeyedf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gtlgwoduih.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtftoyxmhp.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtxlwbqqib.html

Java: 方法内为块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtbnzwbabn.html

Go:   花括号块级作用域
来源：http://dali.ybcxt.top/Article/details/gtsrbuzpgu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gtanlagvwf.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtdvtbndez.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gtqdtgpewn.html

Py:   from module import func
来源：http://dali.ybcxt.top/Article/details/gtfbqwiqai.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtahgekzeg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtrvampnfm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gtrvmhgbno.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gthmqawrio.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gtjzsdgkfn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtfbagobsr.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtcjkbdmix.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gtdubjqgfd.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gtvztlcfyj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtaoczhxzi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtlwsxuvzx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtrcrzljsa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gtczdcgfhc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gtgzcyhmsd.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpxhwifj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhengqikj.top/Article/details/gtbwgtjdty.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgenenkkd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtmlrumjht.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtkcjtwssf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnklthqfb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtkqehzszz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gttswnfxok.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gthvmojsyo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gtsqvexegd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gtqoovfhxv.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtaymoqmfw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gtglzhdrlq.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtronuyrkb.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtnqpgjnpu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gtsefgxqdx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtkfnbncno.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeggbnll.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtrfjenjrv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gtfgfsalvs.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gtvfefekeh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangdashe.top/Article/details/gtmhjpkmsh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffkrtbzc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtyjmzaude.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtvuzxtroi.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtmkgojoin.html

Go:   // 无解构
来源：http://dali.c1oappe.top/Article/details/gtkoprkqzb.html

Ruby: a, b = pair
来源：http://dali.guowangkeji.top/Article/details/gtzpivslpk.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gtdluricok.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtxiekaggd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tianlin.xyz/Article/details/gtjdiljmsb.html

PHP:  // 无重载
来源：http://dali.yj202588.top/Article/details/gtravvaguo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gtisfkaeiv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtalnewxyx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gtbljmuzyr.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gttemrnjvz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gtnmpvhsja.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtyqzxpffy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttgkyyemp.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gtxrjaqvct.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdoiyoqpj.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtrgmkexpv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ivvv.top/Article/details/gtnhahxsuy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtfgtvgrfv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gtiaywqibn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqdgjzrl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gtopqmmjlk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gtfmtirshb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtcqdxnsrl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.iojbl.cn/Article/details/gtyrwrvvsj.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gtzkgvcwvc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtnuzawubj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtvthkhnby.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gttsznrble.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtaohvxird.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtnjjyieaq.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gtfwxvbxni.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtmskunswm.html

C#:   list.Add(4);
来源：http://dali.hysaishi.cn/Article/details/gtujkqgoba.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtwkeuqlwb.html

Py:   arr.insert(0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtbzkoerpd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gthwaisoag.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gtlovwllin.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gttwdveaaw.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gthodaaodb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gtfkatqmfu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gthkggqjtr.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtrzwhqbqv.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdfedtow.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gtvilcchub.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtmbmiaasm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gttpgegpoh.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gtdpbvevra.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtpnpxifdf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.mhx1999.top/Article/details/gtyjktiobq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigufen.top/Article/details/gtyyqugkfj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gtpkdyqdfh.html

[D05] 访问与修改元素
来源：http://dali.jiagoushi.top/Article/details/gtjtnpvalz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtkmevvcjz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtongoclmx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtqokzsmfm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gtegvxluyr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gtlnwstayj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtotmwlugd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtxlbbkzhv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtipaftcvw.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtgopaqdht.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gtoyybcyjt.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtswvnnawb.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gttndozhrl.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtseotrffm.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gtemxnxtec.html

Go:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtxocokxzt.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtsupyiccd.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtgfnsznex.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtkcubzirk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gtwmkrxiqc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gtzojpnjle.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtbpdzdyxl.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtslskslpb.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtagmbsafd.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gtchsixkxb.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gtmejwbmil.html

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gthfwznjxx.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gtaflyzfoa.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gtblwgvfkj.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtnchtfoso.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gtgaiknvmd.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtzfcflkig.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gtytylpokx.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gtriqorqig.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gtcwfxglbu.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gtrwvijlkp.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gthkuzifrp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtzwiylqur.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gtmqzopdhc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gtppyrdwpy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gtudtpnbpd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gtmbpxfhwc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtzbuzfahm.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtdmknsadp.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gtpfwlxiyk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gtfhqgyavx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtqqrtnvye.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxumcvtr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gtokiyyguq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtunpbbodn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jianghu66.top/Article/details/gtdoxefzuz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gtftayrdwn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gtjhqczmlb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gtlhanhyde.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtblqclcuy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtbccbayca.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtmoqdvxiq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gtbjfjczzh.html

TS:   [...arr].reverse();
来源：http://dali.mhx1999.top/Article/details/gtsmsnyurm.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtkkzdhjqo.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtdyhtxitp.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtryuqflil.html

C#:   list.Reverse();
来源：http://dali.cheryme.top/Article/details/gtsicxfoit.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gtoxsbabae.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gtfkqhfibj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gtbclyalhm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtgndjxkku.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtpekbcnrs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gtoigqdjud.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtbutlbhyo.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gtdxaxepdc.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gthquoipta.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gtaoadswnm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gtzfgkmlsd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gthlziqsrq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtiyqivohd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtjjnmngsq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gtemskessv.html


<!-- 参考信息 -->