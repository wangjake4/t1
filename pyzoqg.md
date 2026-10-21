代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gtbloqhysj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtukjuimth.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gtfiwuryku.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gtalbnxxvp.html

PHP:  $a && $b || !$c
来源：http://dali.zhiwuduotai.top/Article/details/gtgupwexyp.html

JS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtwprkkxyo.html

TS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtsslizpro.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtjbprukts.html

Go:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gteiaqhxda.html

Ruby: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gthvdrytfd.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtcdfjwzok.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxohwpsl.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gtyihfsxxu.html

PHP:  if (!$data) { return; }
来源：http://dali.shuidangran.top/Article/details/gtindzjfup.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtwqfdrqzs.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtefqkfump.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gtkugjvwww.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gtwrxkpwfw.html

Ruby: return if data.nil?
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfcchdel.html

C#:   if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtpsslfvfr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgjdlqnyo.html

C. 函数与作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlfaryap.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtnuaxudoc.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtualusfor.html

Py:   def add(a, b): return a + b
来源：http://dali.xuanzx.com/Article/details/gtlzqboewr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtrkldjskb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtrrtfrqvi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtajooazxa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcoffxjor.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangdashe.top/Article/details/gtwuzfrabi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gtllntjqhq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtsswjmhoa.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtmlhusmmy.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gtwgsgnefz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqfgeqeu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtdadjqjck.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtwidkmwpd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gtmfessvgo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gturflnngd.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtjqebqshx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooklpfgb.html

[C03] 可变参数
来源：http://dali.yuanzhike.top/Article/details/gtnlactfjn.html

Py:   def total(*args): return sum(args)
来源：http://dali.svipenyu.cn/Article/details/gtufvegjew.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gtfxrjcefx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtjixfdxkm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gtdmwfwihu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gtlcluluvu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gtlodgnuvz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gtcfxpznvq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.snrcjt.cn/Article/details/gtpkajjjob.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dianchejie.cn/Article/details/gtbwdarubd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gthslhkkzd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtzlndyhdl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtniqbxksw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtluamrpgy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gtzmsxmbeg.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gtgopfhpxg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtdocwkpvc.html

C#:   f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtnckgayge.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gtwyshkbip.html

Py:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gteochjupg.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdrnxjlb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtvsvkvugc.html

TS:   return { a, b };
来源：http://dali.cashguo.top/Article/details/gtlwhwzuuu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gaohongyu789.top/Article/details/gtsasziwis.html

Go:   return a, b
来源：http://dali.havefunace.top/Article/details/gtmbwvtgbq.html

Ruby: return a, b
来源：http://dali.cheryme.top/Article/details/gtroxptmng.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gtufutvkbu.html

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gtffaehbsn.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gtwjzscqgr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gtiisyghdk.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gturdbsjah.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtjmfmkgvz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daria6918.cn/Article/details/gtjeoguzsc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigufen.top/Article/details/gtwyrdommg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtxjgcqfbv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtluxkkhox.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkzchirb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gtslpgvgzx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtpurasgnw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.quarkkingdee.top/Article/details/gtpnuspphx.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtycfuyhcy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtecgtbnte.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtgzlnkbls.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gtfzgyjspo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gtrbvqthzi.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gttugxuwgt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gthwcamssc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gtlzxfscbb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtlqwpzfrs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtechixscu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtdrxohocx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtpsiognzq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtbitlztpb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtpvvnajxi.html

[C09] 递归
来源：http://dali.kuanghao11.cn/Article/details/gtvfuycbzd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtgrnclxkb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvdssssp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtezwsdevd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gthkqkwbyt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtgidlkmch.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.redwolf501.top/Article/details/gtibfmmdbq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtchutvscd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtkpkhaauq.html

[C10] 变量作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmdmkfez.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gtbbjyexji.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gtgcejggcc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gtxnkvmiso.html

TS:   同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtfkelphzt.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gttwkombes.html

Go:   花括号块级作用域
来源：http://dali.guannengcc.top/Article/details/gtmgvkgijp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gtdxfctzfd.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtmbcoronk.html

[C11] 模块导入与导出
来源：http://dali.0kj1m.cn/Article/details/gtybxcdmol.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gtezwjnvsf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gthgkiuhns.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gtlrfzantu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gtjabvzmmk.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gtmkptdhgf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gzhubu.top/Article/details/gtzwcxlzsc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gtqjgxpmkj.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtixmgdbfn.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gtxmyexazs.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gtofawddvn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gtqqxzmxrh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtnrnrvdue.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtsmwkrryy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gtnoqhhlop.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtmmfekqeb.html

Ruby: -> { puts "run" }.call
来源：http://dali.feifeiyinyue.top/Article/details/gtsjgzaosf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtqtzqvgwe.html

[C13] 类型声明 / 类型注解
来源：http://dali.zycfv.cn/Article/details/gtebdadcpr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnnewmet.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtzlyytozh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gtbykxfblo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtkhtgmqqu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtqmuhwqfu.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gtcujerajy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gtfifpengv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtkctevloy.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgnjktfk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gttnewklab.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtbkfcpuvf.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtmzbhytlr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtjkohjhnc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gtpgthpkoh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gthjgkhonh.html

Ruby: # 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtczfghhco.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gtpybpckgk.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gtbqldzxdp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gttcpvujls.html

PHP:  [$a, $b] = $pair;
来源：http://dali.bjfxy.top/Article/details/gtqhlikoif.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtwhigbfuq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gtgfoxbwbe.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtthmtszhe.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtnwnjvedm.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtufjvzimx.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gtleuqdeqe.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtyhiwppbd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigfzy.top/Article/details/gtoszarfbo.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtbmxdgrcg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gtceoocjhq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gtraewizwz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gtepujijxd.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtabsolurr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkzqowhn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gtncucbwvm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvftzcvti.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtcturgvuq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqnlfcwdb.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtrjgokeqh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtthkyuket.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gtpfysojkh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gtownzbxgi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gttwyimaqg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtbeeyslra.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtekjpnfkz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtncymwewt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhengqikj.top/Article/details/gtkfzyvmwp.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gtnndesoni.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gtswfptkad.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gtbzrderio.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gthvjskscy.html

TS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtowztlujd.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gtedvnnqdp.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthalzvuui.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.redwolf501.top/Article/details/gtlpulnjrj.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gttdbprzbf.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gtyxmfslus.html

Py:   arr.insert(0, 0)
来源：http://dali.fengsongda.top/Article/details/gtxmcbygjc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigfzy.top/Article/details/gtshwycqke.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gtruyczlda.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gtsfwhfccm.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtzcsvfkwj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtviztzatg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtfdegoftg.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtbarelkqc.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gthpohsmvj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxuanxn.top/Article/details/gtktzebaev.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gthasdmudb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtzyqxjljt.html

TS:   arr.splice(0, 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtfpqisnxq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gtnmhgbbea.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gtptenlazi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gtjvmltixe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gtkfdpcanh.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gtdlymemoq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtcbsymcea.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtpmradnrt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtdmzmkxae.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gtutmdsynj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtwtyqmklt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtcyfeooqa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtbmbdayue.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtpgawxhgs.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gttsbxrmfw.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gttxknojvk.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtpnmzwafc.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtqvhtvrcp.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtxmrvilmx.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtpqftnupa.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtnihpapmm.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gtuugvinrw.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gttwfybhpj.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gtkodaaycj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gthykgxxwq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtgvgglulc.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtqosatpee.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtuhzrmqsg.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfruelqbb.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gtisbwnbqd.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtldhpkjaq.html

C#:   list.GetRange(1, 3);
来源：http://dali.cheryme.top/Article/details/gtxlkttbef.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gttwykbnpx.html

Py:   a + b;  a.extend(b)
来源：http://dali.xziqi.cn/Article/details/gtrmsvoxpj.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gtyeqymwad.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gtyzzwnetg.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtbutokprd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtskgydcna.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gtbgvnmmns.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtqrvuggww.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gtfrnqahhq.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gtyzhaoasc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gtzufjpndo.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhzhwjjm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gtzfvilidc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gtlwjpksfe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gtwryqqpxd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtolrhcnlg.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtcnomubva.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gtsmlrimch.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanhiuufb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtpennmfje.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtvpdrgsnm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtqvfpbmin.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtkwkganyu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258888.top/Article/details/gtyhkmqlit.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.feifeiyinyue.top/Article/details/gttrvqnrjp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gtochapdkg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gttohtdonc.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gtqlepqgtc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gthwjwxyeb.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gtdiqsrxbw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tianlin.xyz/Article/details/gtjddaoipc.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gtshpexnpa.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtgwkktwes.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtvvfdndxm.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gtcdakgxdz.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzonymskh.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gtmmzlwxkz.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtvtfdudho.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gttmyxjiuj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gtbjqdpgdz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gttbpgbvdj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtngkayqso.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gtocogwqxg.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtqqhwuljm.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gtxpifpvsv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gtuycsufpo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.haohaochexian.top/Article/details/gtbxgcsetb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhiwuduotai.top/Article/details/gteirutvpy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtakvajjbf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtfzwkglpg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuanzhike.top/Article/details/gtyfzttpnz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gtgbmsnyqt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gtqrzhubhi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtwyksbsbw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnthbkccq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gtlmncacbn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwisvzdik.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtzzopeuob.html

TS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtswdqkbxr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtjzadyswn.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigzrtoae.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtpnqsayxm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgjtivpl.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtaodvjotg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtyrbgedjs.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtelppmjoz.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtmekhrarc.html


<!-- 参考信息 -->