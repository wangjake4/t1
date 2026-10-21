代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gtthdpzszm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gttaejpmip.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtgtitkunm.html

Py:   a and b or not c
来源：http://dali.9152youxi.cn/Article/details/gtogkghqzp.html

PHP:  $a && $b || !$c
来源：http://dali.wangdashe.top/Article/details/gtkjulqhhx.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtuywqpwrp.html

TS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtqparqnmi.html

Java: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrzkefwz.html

Go:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtnizsixab.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtnbkctzlo.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtmkocpozo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtoftkutcg.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gtkfxfpymd.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gtaepotlee.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtfgwgrgrj.html

TS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtopgecloe.html

Java: if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtdsspvxpp.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gtzobfijew.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gtkiidumdm.html

C#:   if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gtabakmraq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthdeywcfp.html

C. 函数与作用域
来源：http://dali.sweek.top/Article/details/gtjmgzjyut.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpksztffy.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtycuxcacg.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gtrhpwokdd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtbzbghmgg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtwiioxjuo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtomsiwbrb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtgqqzsqkm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gtpgdygwbl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gtkhzdpmpg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtxnfxgbnf.html

[C02] 默认参数
来源：http://dali.mhx1999.top/Article/details/gtsuzlhlet.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtnsiogxuh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.snrcjt.cn/Article/details/gtdzxghxkw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtigpghzen.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtmaurismr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.haohaochexian.top/Article/details/gtwjqbovue.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hywenlv.cn/Article/details/gtbwhquqfu.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gtyulwouod.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gtbxrbtbch.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gtuplrfjgq.html

Py:   def total(*args): return sum(args)
来源：http://dali.vqdsnc.cn/Article/details/gtxupabbgw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gtnvsrmggy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtuvkefzfq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtofivnmhz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gtoatdzcrb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhiwuduotai.top/Article/details/gtpmjnoodt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtweubjkfe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlshnkarg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gttpbqrvmj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gtjewifcja.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gtvvcrbfdf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtrixyymws.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtklfiotbb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.kuanghao11.cn/Article/details/gtpobjuqgc.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gtjpeqhdej.html

Ruby: f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtdmhmhlbs.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtxoxdbblt.html

[C05] 返回多个值
来源：http://dali.ppjwa.cn/Article/details/gtbtnutdti.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gtcanokzcx.html

PHP:  return [$a, $b];
来源：http://dali.zhoulong.xyz/Article/details/gtgskbpczk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cheryme.top/Article/details/gtfuzasgxb.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gtwsaqgpzq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hywenlv.cn/Article/details/gtcfejeght.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gtjddhvcnz.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gtkxfwkyxq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtvuxfcfsc.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gtleqrrvgg.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gtdgztncwp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtfqtntdrt.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtnccwrftx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwdaehae.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtualamfrk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgufenzy.top/Article/details/gtcxquisdm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gtrzctejaj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtqrureyqs.html

[C07] 把函数作为参数传入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcfjyffd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sufxvd.cn/Article/details/gtpvcdecxl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtpmcsrgjo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gtgdkknhar.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gtjpowalmo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gtkwaicafw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yangfankeji.com/Article/details/gtfcoyptgu.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirwkqdiz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gtgnvdrrat.html

[C08] 闭包
来源：http://dali.hnxiangtu.top/Article/details/gtfzchoccq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gtwzuieyub.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtpwqcoaub.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtcpytswwg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtihaxulbw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gtnmgisefq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gtktnngbkg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gttjegzbym.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtxumwykko.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gtbvzjcgyq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtmnqkijwf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcxjgclhi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtppriibck.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtnkrgskyg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtnmfxymft.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gtfvhtfmnp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtqpbtiowc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.0kj1m.cn/Article/details/gtdetezvli.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gtyoztjqgl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtoiaoyxoy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyenfzea.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gtjwawnczj.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtfmfoclmu.html

Java: 方法内为块级作用域
来源：http://dali.nwbrower.top/Article/details/gtitiafvis.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gthlcsuqmg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtuithnsct.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtdmtyinms.html

[C11] 模块导入与导出
来源：http://dali.sufxvd.cn/Article/details/gtcwpvtvoa.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gtqkebsrrw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gtyzbzfizd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gtrbyjkmie.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gtiktswchd.html

Java: import java.util.List;
来源：http://dali.gogol.net.cn/Article/details/gtdlpkbars.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuanzx.com/Article/details/gtanaldatn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gtvgnuwtgb.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gtnyjocnyd.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtzmgbihby.html

Py:   (lambda: print("run"))()
来源：http://dali.shangyingyoupin.top/Article/details/gtmlnpewtu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gtliyxwshz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtwvpmvude.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtfepenoom.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gtknxthjnh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258.top/Article/details/gtnuidbhko.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gttxkwvadk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gtzkwnlaaj.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtacocmsos.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtjhwxrctf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtpzbncqyt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gtgigkuwev.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtwbqoygtk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjghnyrrg.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gteccwmjri.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gtlmvbawgk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ydzc1.top/Article/details/gtxetngmcv.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gteiolajyf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtftofmkes.html

PHP:  // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtpcaaimqf.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gtcpfosvwe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gtwxchzymz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gtdydwlmrw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gtdlcittcp.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtgkzjdgzq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhengqikj.top/Article/details/gtmfccmvcp.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtkgxkrtdc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gtbobprleo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gtovszcoyu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmbbhmott.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gtsepwrtwn.html

Java: // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrhjejcr.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtenbmmbco.html

Ruby: a, b = pair
来源：http://dali.tian-w.cn/Article/details/gtzrmxzbjg.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtmhgbogcq.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gtsmaxwdoo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gtslonzyfb.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gtckghxdbv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtvepjlcia.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtmtxqhirr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gtaestjvis.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gtsljkiehu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gtfovieevm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gtpiyhfrqk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgxniwcuw.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtpffpkoqn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtoydvjccg.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtkpvsxjgb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gtsowwtxka.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtpsdapldp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtjgknipmh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gtqqjskyrx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gthxezshkf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtbszwczhd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gtbkpmtgla.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtpyuzbwkp.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gtlfnviqqi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtemknwgyf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtjbtuerfs.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtmeuvargy.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtwozywutu.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gtnnsoocxn.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgfzy.top/Article/details/gtzkhqudxs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtpbqgudah.html

C#:   list.Add(4);
来源：http://dali.yongpay.top/Article/details/gthadihlla.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gtwnmdsaos.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gtvhwswnge.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtongqrxhi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtyklsfuvv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ybcxt.top/Article/details/gtklscstxj.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtqnonjktb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gtllfsicho.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtbnzebawm.html

C#:   list.Insert(0, 0);
来源：http://dali.birdmap.top/Article/details/gtpiqxovoq.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtxbvvfeei.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258.top/Article/details/gthfrdllzk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gttajudskg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyplnyhd.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gtbcudgnvf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gthnnvkyci.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtunuycfwn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgvflopw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gtwpwnieus.html

[D05] 访问与修改元素
来源：http://dali.vqdsnc.cn/Article/details/gtpqlnpadc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtfnrcnzgo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtzxjuplxf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtlhfnyolr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.bjfxy.top/Article/details/gtychpseph.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gtyalogfpe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtfhdowlrp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscknuovb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtbwyybart.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtkchhvlwp.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtmxrysvcd.html

PHP:  count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtcfasvlcs.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtczwqlbiu.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gthpuieujy.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtueffdfke.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtekyklftq.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gticewezab.html

C#:   list.Count;
来源：http://dali.zhoulong.xyz/Article/details/gtyhmotqrl.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gtqovzlckr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gtxelnhwgr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtxwbcjhhi.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtcpggypwr.html

TS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtoaqkueth.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gtsfobkrws.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtljfoqeul.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gtcmetjjch.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gtogyilxmu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtrgfmzkqj.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gtqjgkvbob.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtsfddeflf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gtvshdvmue.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gtkguxfroi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gtbotvcudi.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gtshlotjll.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gtdrqrfppv.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtfzccnden.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gteprgzzia.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtlqdbydyo.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gtfaqlwizz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gtynhrpbgd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtddngugsm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtcffqcvik.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtjljuyrtv.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtylzwobvc.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gtqiekozwe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gthqjshtig.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gtyfhpznci.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gtxmbnosqx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtufiwynyo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtyojregpa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gtmpefhlne.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtrzmpqhjx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtvpqzqxqe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtozcnuoom.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtiosebsjj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtombvvqbz.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtxgkzekzm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtamvshmuv.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtbizmpvus.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gttuigoaru.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gtkmxwoeul.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtdwehqxkz.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gtlsuwqhsj.html

[D12] 查找元素下标
来源：http://dali.iojbl.cn/Article/details/gtqivdaqwq.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gtxraymtyg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gtgfqgjeqq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtrjhvqnfj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtentjkdbk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gtakclveel.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtmjhygqdv.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtwofjunsh.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gtjhujvjci.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtytoglxfj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygvgzrzf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gtpnzjtblc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtunaetrme.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gttebdyayk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gticlikubb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gthagiqyvt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtgkbueczv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gtxlnpxxyb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gtptfhwubi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtoftgbxjj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtxcvixbre.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtxkimfcfx.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtdfahfgkv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gtdqwlxsnl.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gtjjsddeqd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtuyknakhw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtflrrtntl.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmenbwwas.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtzbchpmgs.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gtszioblje.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtnwfaihhc.html


<!-- 参考信息 -->