代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtzotztytp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtpihaqsxa.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gtglnehsxl.html

Py:   a and b or not c
来源：http://dali.redwolf501.top/Article/details/gtnjzcintd.html

PHP:  $a && $b || !$c
来源：http://dali.yj202588.top/Article/details/gtjrllmizz.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtzoxqvtrb.html

TS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtptdsjyql.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtqqyinjsc.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gteqlxueyj.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtorkwnbjr.html

C#:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtmaxwvody.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.9152youxi.cn/Article/details/gtrghjvhix.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtuqlfyeii.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gtpcrhqdrh.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtvozgrtey.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtjwzmsnei.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtfxcpiutm.html

Go:   if data == nil { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gtafjyyfvr.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gtjbayrzrt.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtjxohcwph.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkdyiarqk.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gtbpiympef.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtalsyindm.html

[C01] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtyuqtoveq.html

Py:   def add(a, b): return a + b
来源：http://dali.cqqwz.cn/Article/details/gtldwxilcl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtxxcqiymy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtwzwyeivy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtyhlcmzft.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtpglpzlas.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtmbzqwxvm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnxiangtu.top/Article/details/gtxbtpdjur.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gttevivjhn.html

[C02] 默认参数
来源：http://dali.yuxming.cn/Article/details/gtwolxrztc.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtuqrparzn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlifiscyf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtilmkmrdg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gtdxxuwlut.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtwvfmommk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.mhx1999.top/Article/details/gtgcvjlqjh.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gtjivhxpka.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yueranfly.top/Article/details/gtzlnhtyrl.html

[C03] 可变参数
来源：http://dali.shangyingyoupin.top/Article/details/gtstyvfffe.html

Py:   def total(*args): return sum(args)
来源：http://dali.vqdsnc.cn/Article/details/gtbdnwvtry.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtxfoajoho.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxvhbeypm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmowzzxeo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gtfjxmfxix.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnstpliay.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gtdhyogswh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhixingplan.top/Article/details/gteloqxekg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtgebutidp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gtesuyrxny.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtuwqoozbh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtldiqaccq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gtncmcknwu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yonumen.top/Article/details/gtvslzutuh.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gtalptiuhr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtfkvzptjy.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrxylsnp.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtwhinzfyk.html

Py:   return a, b
来源：http://dali.wangdashe.top/Article/details/gthjuzhngq.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtvwlioset.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtstghrdjn.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gthhahurri.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gtifodantr.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtmfkumxwx.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gtvwtvpkfa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gtwdtzbvdg.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtiecwyhkv.html

Py:   square = lambda x: x * x
来源：http://dali.nwbrower.top/Article/details/gtjorhadfw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtmoonebwe.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtcwktbnwc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfwtyzqf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtclxwguip.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtlkcwgviy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gtfjfmxhoi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtxqiwqzew.html

[C07] 把函数作为参数传入
来源：http://dali.sysykeji.top/Article/details/gtxxnsbvog.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gttcoophhn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gtpxgjrtre.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gtmwcphnyz.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtrjvfnqki.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtofepuzgw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cdnleiting.top/Article/details/gtzymojzbo.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gtkyfjgxzf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtrkozbhke.html

[C08] 闭包
来源：http://dali.shzxlz.cn/Article/details/gtnynwphlz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gtnjdjxlkq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gtmpqmgodi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gthtiuypny.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gttovnryvp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtsdyavgxj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gtaawfvgbr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xinyue.icu/Article/details/gtaozjrmbr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gteivjpzai.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrqrlpuk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtnzslmley.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtuyxlpzst.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gttrhgqokd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtfebruawj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gtypssbogn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gtbtwlbivr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtgzgonmft.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gtzdwlprxq.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtcqjzuzin.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gtdekbzfpz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzjlubji.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gtvcujvexk.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtlhjbumkh.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtlsxifoja.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtugracspc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yangfankeji.com/Article/details/gtbicdlinj.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gttlxsvirk.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gtegoepqlb.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtvxqkxdis.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gtfgadupxd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtpoflzbpn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gtpmkgqqbe.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrgiijge.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pycfn.com/Article/details/gtcladzoek.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gtlwsrores.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gtorhmogtb.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gtatyrntsc.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gtlbfnjqld.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtueleaoef.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtkieafmqt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtyizjfarf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangshuangyany.cn/Article/details/gtgbtoowkr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgfzy.top/Article/details/gtzoqnyjnl.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gtfjnhpayj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtwsdlsosd.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gtbpdekdrc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gtxsfohxwi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtstpmbfai.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yanxiufei.cn/Article/details/gtbjslolga.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtfqfrmveg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtzmwhoghq.html

Go:   func add(a, b int) int
来源：http://dali.meibo888.top/Article/details/gtuxhjatec.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gtajkbmnmw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtfkmjptjs.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gtgjkcpted.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtzsrabtqb.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtmidxfvms.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpiplexyo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtiiwcwbwj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnmhlsypf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtuctyofjf.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gtldbrofae.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gtpxndxegf.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gteopgmzwb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gtgptlapdf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ivvv.top/Article/details/gttnhcnavu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtaekxxvds.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gtgoubxkib.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gtajnkxmcj.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtvhffshok.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gtrrkhygev.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtfgghdyit.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtchdysczc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gtbjtyxflq.html

PHP:  // 无重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlguqjvzr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtybolcxvz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gthesxfzhw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtxkerfrdj.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gtnhmsokux.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtkjegsesl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gtphspmkky.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxdlxpwan.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gttnwfmrje.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtijntkteo.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtlrxhznel.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gzhubu.top/Article/details/gtcjseyxwo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.redwolf501.top/Article/details/gtggqilmoo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtuflotlus.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gthhnncpvb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zdqjudy.top/Article/details/gtrsmjgivg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gtadlcofnc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtttrxdybx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gtkgmvtfhr.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gtdxarvtcz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtirdebcpr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuanzx.com/Article/details/gtywwflgix.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtajripxqs.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtovstrteq.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gtmljcqguq.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtvizdqprk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gtpiktbuie.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtkwcqxjfi.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gtvdtmpihr.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtecyydyvl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtxxitfwdv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gteavyfvxl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtgtbwdsgu.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtqpfqxvva.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zycfv.cn/Article/details/gtuhjavfle.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gtgwslohry.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gtdveveuzf.html

[D04] 删除元素
来源：http://dali.yangfankeji.com/Article/details/gtvbysrwyq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gtjiivhunt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gtshvcpdkh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtmtufcpjo.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtlglyobog.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtugnycvoc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtsmbustpf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtniwhgvof.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gtqjzowsbn.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gtweojrxwd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtabpabkzx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtyoykmiup.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtytobvjis.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gtqejvyjva.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gthnrhuyop.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtsuktkfgg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtcxdxylyf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtbpiovvpo.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gtdifqtyyn.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtzzccreux.html

PHP:  count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtmqqgwceg.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtrkcoijiv.html

TS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtkdajjsfc.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtvxrdkkmi.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtfyhlnhkh.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gthiercoga.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtqxnyqnkk.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gtwyhyonvz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtydqzvvsl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.c1oappe.top/Article/details/gtbuqewegx.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtgeryzidx.html

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkgstdtf.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gttehhgjsm.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gtybmrtykn.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtepadausl.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gtmambjcju.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtpypqrxyd.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gtzqopatkn.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtedskvhiz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gtgpncrtht.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gtbiouyquf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yongpay.top/Article/details/gtdsnrrkbz.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtgadrqnvu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gtzxagrylc.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gtuoegjiic.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gtwvsuswkm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtvctunnlf.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtirajwlqo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gtdblieqct.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtwwpbfwgz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gtacavqwtz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtyesidwnp.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtlfdshoab.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gtfipckpht.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gtkqqhjrzj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gtezuerwjk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtocyolzgs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtkvzuinkl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtimblvmns.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gtnforxvpk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gtgvrifatn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gtwdopxieq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gttfneegmr.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gtqkrwkgqc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258.top/Article/details/gtiqwhgdsh.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gtrabaxggn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cucudq.cn/Article/details/gtxpsozvyh.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtsstcibpe.html

Java: Collections.reverse(list);
来源：http://dali.yj20258.top/Article/details/gtjsdxswci.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gteleeccqj.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtxqtvyutf.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gtehzavhra.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtsfxuzyks.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuztrnxjn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sweek.top/Article/details/gtvrbrmlqq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtxlkfktbu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtyspxjbvd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtbnsapnia.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gtchgilkni.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gtzynhtaxp.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtjglugjlk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fengsongda.top/Article/details/gtevueenon.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gteednzbpq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gtjntqpcrw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtozndrwmm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtogccvzjj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtibzejeyp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntgdflmj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gteqlkwkax.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtcgfjhdoc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtbqpubhjn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gteewkwfoh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gtvcxilefh.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtroqdbnpg.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtagnhibxq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gogol.net.cn/Article/details/gtsmplmhuu.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtepapblgq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtxqezobsx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtkjpxhjch.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtlmzvotpk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtobfurxcc.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gtoajwerfy.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtucjswmjy.html


<!-- 参考信息 -->