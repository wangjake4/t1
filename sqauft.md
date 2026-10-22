代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.daria6918.cn/Article/details/gtgqgqiylj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtmpdjtnbh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtwjcieqxl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gttoljdzsk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtaxqgfaxq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojmdjtiw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tianlin.xyz/Article/details/gtqbfvsbgf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gttuijtcug.html

[C02] 默认参数
来源：http://dali.sweek.top/Article/details/gtkvyjbgve.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gtwxtmesqr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gtinjqdbhk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gtklsrvyzv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gtddrvvehy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gthotxmsch.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gttfjawcdc.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gtgynxpcbv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gtagdxhapl.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtzushwxlv.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtzosyxxki.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtyfzokkyk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtvojakaph.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtggpfgeqq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtpcvncbkc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gtcaxyqcsm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yangfankeji.com/Article/details/gtnotsnxnw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenlongwang.top/Article/details/gtkxzrhjva.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hysaishi.cn/Article/details/gtauxmdjrl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gtqzlwnrwo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtoqwwthtl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gttckjmvbl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gtxhptbkvm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gtdjnlxowg.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gtkthrgldl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtzipmsfez.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtouoxdacu.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgwtzfsk.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtggmhlcxu.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gtakuecqve.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtiwowvgbk.html

TS:   return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtfmknnvml.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gtsaxomcev.html

Go:   return a, b
来源：http://dali.cashguo.top/Article/details/gtkqlgxajz.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtkmlmdupy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sysykeji.top/Article/details/gthvqrrgnj.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gttgwvkdba.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gthozxduns.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gtpazkbdhw.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtkppfnxoc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gteicpbecq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwomuktl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gtbexprkfr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258.top/Article/details/gtbzydgwet.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtysdmdadg.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnyayaap.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtislvqceg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtvfdvhjos.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigufen.top/Article/details/gtpoxwyjac.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtkfmgyuxw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtntauztwt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.0kj1m.cn/Article/details/gtvuswsjvi.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gthghvymqv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gthreremob.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gtgziigyjs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gtzqctrxpy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlrqnzlpe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtrigyumnx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtbezpnyif.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gthwsiyywh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtdzcktxxg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gtpeyskjnj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtwmtezfkh.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gtfpvfsonx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdyfmeld.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtnhxdlhnh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtigfeqalm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtivcyeubz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtqlsqtsju.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenlongwang.top/Article/details/gtuanuicgu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gtrrbddzrp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtzwacimef.html

[C10] 变量作用域
来源：http://dali.zdqjudy.top/Article/details/gtcxeqeftd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoiehzafl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtfgxrashm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gtsripmbrt.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtzordivui.html

Java: 方法内为块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtwhyokrux.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtdhudnoxw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gtnzpvmpkv.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gtmeevvkbd.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gtuhxnnuqb.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gtuhitjefl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtabgkueun.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gtlscmfxhi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtcgujwruj.html

Java: import java.util.List;
来源：http://dali.sysykeji.top/Article/details/gtddizojrl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gtehtedfxr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gtljpwgkbz.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gtsosgjgpg.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gtsyupwovb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gtolmcshrh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtnibkqiyh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gthovvuzju.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtcrypiwyk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gtltupmspx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gtbvsoybsn.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gttkxslwrv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gtuiwqqptm.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtfnvixutx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nwbrower.top/Article/details/gtoatdmauj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtduxhbjkj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigufen.top/Article/details/gtezwvmpkr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtlzhuxpym.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtapqjcsiq.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtidsvkeoz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gteknyehkc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gtxsdddpte.html

[C14] 泛型函数
来源：http://dali.shuidangran.top/Article/details/gtbhukljqc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gtkkatwuxs.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtxvnhdcft.html

JS:   // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtqgcbnkue.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gtoxayuhgl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtckhzrxlg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtsirmrzmt.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gtpmgvatca.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtzdwscdbw.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gtrmttcesb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gtaetmqdms.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gtzzxyldrb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtkrpeqaxn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sweek.top/Article/details/gtjduheyfr.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtsoubddgg.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtbapzonsz.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gtkcdpgriq.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtotzohuix.html

[C16] 函数 / 方法重载
来源：http://dali.daxiang520.top/Article/details/gtbsvhcqtq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gtkrnqmfrs.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gtvscsiqma.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigufen.top/Article/details/gtvqavmnfx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gtfyvjtywt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gtkzidqlnj.html

Go:   // 无重载：用不同函数名
来源：http://dali.sxryk.cn/Article/details/gtciooflfh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yangfankeji.com/Article/details/gtzpjyucib.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gtynfuplig.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthqmhcabc.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtwrhjbxxa.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsldovgja.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtksjzphud.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgzreqtx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonzmzpkn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtsxtksecj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gttyrxyeav.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtyyctunyo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gtzfdogwjn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gtxnrlzgov.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gtkblezngr.html

[D02] 追加元素到末尾
来源：http://dali.zhiwuduotai.top/Article/details/gtnwyzifoh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtmlucoztz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtmzvvcvwc.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtvzeeenjl.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtuqpzpxtd.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknpagcwv.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtrtvdppnt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtuxwixrfk.html

C#:   list.Add(4);
来源：http://dali.chenzaomai.com/Article/details/gtajvlhcfg.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtugpdpmyd.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtulhjsrue.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gtnchdfvtz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gtrrxifkyo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtzutnxffb.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtvmkuilpj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gtxmruqrom.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtpisjdbmh.html

C#:   list.Insert(0, 0);
来源：http://dali.yj202588.top/Article/details/gtudlvrtgq.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gtpdoqqdak.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtafcxlotg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gtiojxkgdt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yueranfly.top/Article/details/gtponqzjid.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtaotoaumn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.kuanghao11.cn/Article/details/gtwuqdsgyt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sxryk.cn/Article/details/gtivdkgacj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258.top/Article/details/gteiqdtcjk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrerjrrtm.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gtfockaely.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtwivbxfnd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtgstoocwn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtkqgqwykv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gtqdkcregl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gttvvbhpen.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtqbhhtgsf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtoppszsvc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtkojzplie.html

[D06] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtthamwcxa.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtoxjsxqhn.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gtpukxgcrl.html

JS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtsknvcirs.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtilztxksc.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtitwwvsyg.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtmzlgekgm.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtxatechug.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gtzohkyeec.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gtapqizsyj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gtmzyjqusj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouyegzqo.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtoagkuazz.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtxyrfybdg.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gtqiflueqm.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gttczhtwln.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtestmhseq.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258.top/Article/details/gtkujchbmz.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtperjfidu.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gthgavowdh.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gtsdtmzrxo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gthxawabcv.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gtqvwqpyhh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.smart0.xyz/Article/details/gtpfedzmpg.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gttxdpsxhj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtprbncuay.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtmkcjsmju.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gtggefuyln.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtftzwfflz.html

PHP:  sort($arr);
来源：http://dali.zycfv.cn/Article/details/gtlugyozln.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtjewmtvgj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gtxqtsqyea.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttydzrzgd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtionxwgej.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtkpuzacsq.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gtutwivzag.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuanzhike.top/Article/details/gtdppigasx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gtthgfozlj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtyqwkshla.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxepfgqj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtxjjdyajx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gtdsuhwroj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gtrbbiezvw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gtnouqlvbn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gtomacgkki.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gtthwizjbw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gtwbmjxpgu.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtvfozthwl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gtirbpywcv.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gtekxgziwv.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gttjgggumo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gtiyzdbzvn.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gtzvoybjbp.html

C#:   list.Reverse();
来源：http://dali.cheryme.top/Article/details/gtiduwqlec.html

[D12] 查找元素下标
来源：http://dali.cqqwz.cn/Article/details/gtpbprhrbn.html

Py:   arr.index(x);  x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtsvkxhsdb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtsltkzxcz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtommegzxe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gttprnvjxg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gtwvleiwov.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybdgndcw.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gteocyypkj.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gtctzzqpld.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gtmubxpweb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtztcdpdaz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gtmamrhtmj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtcshhwfqy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtvmmaivvt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gtcfzvcdms.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gtdqqhyysi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gtxqlffiyo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtazlikxsi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gtqhvlnuze.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtmrzncgyy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gtofneuqol.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtcgtxewcl.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtlbhebafr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gtzsrouqfd.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtloeffyyd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtuyijvrmb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gtrvszwhbn.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtlscgvjvt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtrlthetta.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtoqusrfwy.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtzseburfj.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtkxamhddv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gtmfemrvws.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gtkmeawdmi.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtxewuzegp.html

C#:   list.Distinct().ToList()
来源：http://dali.aibaodan.cn/Article/details/gtcmvjbnyu.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gtcwwytqho.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtleeonygs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyuqabzy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gtgydqcvcx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtzxmuaehf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtrhapyfwm.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwpbzhjd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxflifgz.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gtktwvjkmt.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gtrregpwje.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gttvagwrau.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtnnyssyjj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gtgqkaflsf.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gtwpnvlqzg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtdfojfqmr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtfrzgxpzn.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gtzmetkbmd.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtlwvehrcp.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtkwgrazlv.html


<!-- 参考信息 -->