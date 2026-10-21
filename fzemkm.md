代发 wailian999

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwonlavnk.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gtlazctrdk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfqgsqvib.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtnfpfkbtr.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtvzrpvuom.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtljsuulre.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtjlgzviyb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcvkznvuu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtfbqzpybw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtejbmrqza.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gtgauzstyi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtywbibmgn.html

[C02] 默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtuvygaxeg.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtsogianzw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtesirrzyd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtdqcoqqya.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtcmrdeqxg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gtusgtyzdv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtpjzojoev.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtqkkwntri.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiemmqajp.html

[C03] 可变参数
来源：http://dali.xuetiantiany.cn/Article/details/gtxuruacgd.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gtyriqycbx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtdbrhkyqi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtbfsvhjud.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtlijgvqup.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gtwbhnzerh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtlrlyxmrj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gteibcgqkc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gtostgtaxm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtmanvzpqc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxinkj.top/Article/details/gtyboexlao.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gtocyboytw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtugagxijn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ppjwa.cn/Article/details/gtastuqzdl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gtzmprwuwq.html

Go:   // 无：用配置结构体参数
来源：http://dali.hysaishi.cn/Article/details/gttryaseml.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtlqqmrcky.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtbtdfpnlb.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gtfcyblujo.html

Py:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gtviopfmde.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gtayiqqgrx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtzpbnibqv.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtbumjctud.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gtwbohbrtc.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtozrzooxn.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gtqsnlmfrb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gtbulcgpuy.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtlcawnusc.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gtvjfxxpsc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gtbbdfbyny.html

JS:   const square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtfkkrdcul.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtvpyerxct.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gtnywnzfkx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gtomcfahqf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gtpuouwtma.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gtodbuoysc.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrteniuu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gtlxxdiptt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gtljywxikh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gtztwcgwhs.html

TS:   arr.map(String)
来源：http://dali.nanxinkj.top/Article/details/gteupvpany.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtbwdffnrs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.havefunace.top/Article/details/gteniynpvl.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdbbsabw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gtazbxkxve.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gtpaaowjmo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gtkmymqndr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gtumkslryt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtksiscqla.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrbvjqps.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cheryme.top/Article/details/gtuwkvozep.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gthbcrryhs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqshfnktr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcazoenhc.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gtstqrvmof.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtizwxlrhk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtawdnxuzc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtxaksbseu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtkphqcyyv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtuymkhvsq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gtrlhxdtme.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtdgkyapxj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.havefunace.top/Article/details/gtmcrpmeld.html

[C10] 变量作用域
来源：http://dali.zdqjudy.top/Article/details/gtparbykdn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gthqqfwhwu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gtbacbtedy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtukwrsrpn.html

TS:   同 JS
来源：http://dali.hfpthk.cn/Article/details/gtcjchabph.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtxhuktwnn.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtjbykevqb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtbjuzxpgm.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtmycdxaxe.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gtsjnzsuvf.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gtiyapjrnw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gtmsxzempd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtwphfnvyu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtovlylirn.html

Java: import java.util.List;
来源：http://dali.haohaochexian.top/Article/details/gtvnbjihtr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gtgjnwvvpu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gtxccdarho.html

C#:   using System.Text;
来源：http://dali.iojbl.cn/Article/details/gtchxguagl.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gtbadxdozq.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkduyqqs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtxqagygwa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtyjoayial.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtftskkjib.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gtnyagtpcd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnroocsk.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gtskqvijpx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gtlpnxidiz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zycfv.cn/Article/details/gtupwzeqpz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gtgjdaclbq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtasaolkmq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtknigyowq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtqlxsrnae.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gttsngmamx.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gtjlsrxcth.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkeszretr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtxlizlzbq.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gttlmeiety.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtvfzsnvda.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtixwxtoin.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtuleqjytu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrskvggau.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gtsedsgivz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gtbuilrxeq.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtemldcyic.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gtwaujvjkz.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjubnyzdg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gtryvuuxcd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtdrzxvfkz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gtmdgxumdl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gthvdaloxj.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtddnlffuk.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtceqkvdrv.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gtgltnpako.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gtvcyzuydt.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gtyoolbhym.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gtvpvagapl.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gtrcfbdivi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gtmwgwhhbp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gtuajzydun.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzovithp.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gtjfadsyrr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gtbhowcvqp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtigeapudr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqsdadeyc.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gtmrowgfwr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtksqgrqty.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtmnrtasmx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gtsdsgcunt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gtedbvzjrz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtelitvnuu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gtcciudoaz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gtkdxlqjcg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtcsacnicb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxwbbxpb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gtcsvezxbk.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gtnabdedkr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtlnfltqzq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtduafisin.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtbjlgibhn.html

TS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtcpvxndsk.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gthefsckzp.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gtnltkriqd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gtdzkvaxac.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gtiunqqlau.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gtvechfzku.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtfujqrhcd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yonumen.top/Article/details/gtjzabfalh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gtyqgmzrxj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtfyqpvync.html

Java: list.add(0, 0);
来源：http://dali.fzhhl.top/Article/details/gthibysaiy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gtvjqhhxan.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gtelbsrxxp.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gteigtjczv.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtlmywpaej.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.quarkkingdee.top/Article/details/gtwbsfficc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gtcqstojvz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtsommfyxn.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gtyczqcqyu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtuoejfmco.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtvakyvyey.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtgpxwsntt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gthjwrjrvs.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gteamqibpv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtyyiqrvwv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtlzwsfexk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtdedtxbwo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtnzutrrbx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gtrixigmzz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtzalkfoyo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtgfqqbecm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtmsuicjbo.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtsfzgwnol.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtahitusua.html

PHP:  count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtuwvxtgrr.html

JS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtcehofhyq.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gthzsqaahu.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfutmfygj.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtmppuipnp.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gtzxdawqly.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtybojngku.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtnvczzgsz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gtcfoionkc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtivciqonn.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtwbtzgtbj.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtlhtondwq.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtkhfeuwxc.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gtdrjflbco.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtqmxcoghu.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtuuqjhvwn.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gthjaydyvz.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gtflosocou.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gttobjluuo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gtsxxaqtmx.html

TS:   [...a, ...b];
来源：http://dali.hfpthk.cn/Article/details/gtvnsxrids.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gthfmswqgl.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtldeqfsas.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gtdycddcfr.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtfxukxgtq.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gtmhbhcwds.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtcqjsrviz.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtmgeaujoc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtdydecaxe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gtsamplasz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gtzrpdzaen.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtzuvoeg.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtzasnpflt.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtfefwdcta.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gtagqhletr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gtgcyquqcc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtugralulv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtxmatzhxj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtklunfrom.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gtovxjnknl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gtwpepkfmv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwptpxks.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xinyue.icu/Article/details/gtugbgpkbv.html

[D11] 反转数组
来源：http://dali.jlsjyb.cn/Article/details/gtgjhauwif.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gtrfxficmz.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gtaptfqdww.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtgrjqlfsg.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtglxdysnt.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprsfbspx.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtfnuwyaov.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gtzvldhdgp.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gtqianuorl.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gtmaqiffme.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtgkruaetg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtmpyegwux.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtehejuapb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtsojornqf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gtjfjjymjl.html

Go:   slices.Index(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gthahmhanp.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gtcqivxdkw.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gtfbfrllkh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtisgplcen.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtelotrazo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtehscqcqh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtqwcmykwe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtgyfiqxpq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gttxjnoofd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gtrxxsihgo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtgykbkpex.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gtylnkchyw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gtsbpetdvj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtstexsfvw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtqvfpipkb.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtyofjqqws.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gthfshujzl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtmqpjxfgk.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtnibbngyh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtvhkeyvqw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtpffxlckv.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtntpskmdc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtdczhdijw.html

PHP:  array_unique($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtlbmytocb.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtwspsrtzl.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtoqmvxvap.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtcjyjinqf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gtpnjzvewi.html

Ruby: arr.uniq
来源：http://dali.havefunace.top/Article/details/gtnqxsyhtw.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gtcxqrilli.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtebrioyhb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmnborzow.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtksoibdat.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtspcupykg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtewcxnirn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gtdhqpniah.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtglnuqjcj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gtooddctxv.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gtotudwuwq.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gthkzmdvsf.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdftluydc.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtqrzgwcuc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtzqrurebf.html

TS:   Math.max(...arr);
来源：http://dali.yongpay.top/Article/details/gtpzwvxxja.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gttupsjvow.html


<!-- 参考信息 -->