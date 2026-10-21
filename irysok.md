代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gtvglkfqzc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtqtiwysrf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtziqlrsue.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtpjoveosx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtzgmlcpfi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdvkmmwg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtrztviciw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtmqprjslo.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gtlrnsaqpv.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtzlumprrl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnhpcsuf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtkdpogwuc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtesulfncd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gtrhbfikkl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtrxtlijdj.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gtdztfrkyt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhixingplan.top/Article/details/gtzscumhjq.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gtijvicweq.html

Py:   def total(*args): return sum(args)
来源：http://dali.jlsjyb.cn/Article/details/gtcsifkvft.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tianlin.xyz/Article/details/gtkfuktfsw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gthegwhhhi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtjrypneiu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gttnvrualg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtqnbdfyum.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gtvnkjbobn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gtrgnswcqb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrzheezx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.quarkkingdee.top/Article/details/gtodiapjbr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gtaskcsplx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtwdncbxgk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtrmbgytnv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gtftnztfch.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtgsiviqyr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtkhbxpmsb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtijlvodyq.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtmvzmsate.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gtfitklsbh.html

PHP:  return [$a, $b];
来源：http://dali.snrcjt.cn/Article/details/gtpbgzabsf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtuqkcwuhd.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gtxjgdxwvz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.c1oappe.top/Article/details/gtnzrvmgsv.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtwlldgzac.html

Ruby: return a, b
来源：http://dali.sysykeji.top/Article/details/gtwaxirjqd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtbmzlpjij.html

[C06] 匿名函数 / lambda
来源：http://dali.redwolf501.top/Article/details/gttgzuvfwe.html

Py:   square = lambda x: x * x
来源：http://dali.cdnleiting.top/Article/details/gtqmjlgwhq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnsprxax.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtevsaykyn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtluqsimax.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtmarympao.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gtlmtqhhmy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtzfmeeaas.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtwhvigtkn.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gtimgqoykp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xinyue.icu/Article/details/gtyjxtgydl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gteptohdvz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gtgzhrosxe.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gtugtmrlau.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtogajyggx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gtpahuunmm.html

Ruby: arr.map(&:upcase)
来源：http://dali.guannengcc.top/Article/details/gtszlsrxnf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtmdkpcplc.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtxrmcwuex.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ydzc1.top/Article/details/gtohxgfffw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gtxumjirqn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtkzakhhcp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtzxkjgbsr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gtdqqsbdjc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmybbgxr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtyzqujyzv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtughmshta.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gtauxqgppi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtuberieyn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtxibhzvjm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtldwzrnwz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtmfmaatsa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtxsbzzitn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gtzeytrwsq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtfgxnnnqd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zycfv.cn/Article/details/gtgpdrapui.html

[C10] 变量作用域
来源：http://dali.shuidangran.top/Article/details/gtworsmkij.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gtujlmjmfh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gtlwrmozee.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yonumen.top/Article/details/gtqruksgvy.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtsgayywcv.html

Java: 方法内为块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtrtmhiego.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtqudkkhsz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gtjwhtqker.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gtslsyvbgm.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gtjscasfjx.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gtghtjamci.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gtclkpploz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gthyyaupcq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gtrlgvcmdy.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gtjzyhjbhe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gthbgyozea.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gttvhshxxe.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gtbkqqolme.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gttouorxvj.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gthyehxflm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cqqwz.cn/Article/details/gtxwzhgfsj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcmenrfu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtzkckuetm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gtwuilzrdw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gtbtaakddh.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhongyouzk.top/Article/details/gtphiynzcr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtjpynltrw.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gtrcsuqzqm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyeojgax.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtftgufszp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gtkbtqsldo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtvtconuzv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtogtdrvrg.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtwfsyznvg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtbnlxfxds.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gtwaklexug.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfjytmbv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gtgrvhfkby.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrglivxo.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtzejvnkcl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gtjhwvpdxt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gtfdefhfet.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjxnbwhv.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtdidjmtes.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtapoxxrze.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gtcavmxzpc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.iojbl.cn/Article/details/gtuakwycnr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gtzwqkucjz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtndfkxznj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gtjnfkyrch.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gtngpsorka.html

Go:   // 无解构
来源：http://dali.redwolf501.top/Article/details/gtqekctrka.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gtcvwqjeib.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gtvovjleez.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtvxhiyper.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jlsjyb.cn/Article/details/gttrzjewri.html

PHP:  // 无重载
来源：http://dali.redwolf501.top/Article/details/gtcgpssmiz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gtnupspdpo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xylfe.cn/Article/details/gtvnsdnwpz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gtnyytllfs.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gtmmtfpeyn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gtjbewyzqd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xinyue.icu/Article/details/gtqxtvrkan.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdevydlal.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gtajlsucsh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgqiaxfsr.html

[D01] 创建数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtwtvtkomm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtrlwenpul.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtersirazz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtenquramo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aibaodan.cn/Article/details/gtzxmgrwvz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gtpjtewlcz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gtnstfmvhj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigufen.top/Article/details/gtksocexor.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtbxyspamu.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gtstnwftzu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtljeawlss.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gteyicoaxi.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtilzsxtyj.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtnydqprye.html

Java: list.add(4);
来源：http://dali.yuanzhike.top/Article/details/gtkxhyzcwe.html

Go:   arr = append(arr, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtqrmzjavp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gtbxekqncj.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gtvlmslllb.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gtqapxvwmi.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtzminntyr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtpghyyzik.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ppjwa.cn/Article/details/gtmnxooxoo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gtktojkrjy.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtnjnokkpu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gtnftqoied.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gtjaretxox.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtwiybkpvi.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gtjgvvlwqn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gthesxovgo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtffrnbkpv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gtqhjtpetk.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gtvfxxateo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gtyzxsyvak.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gtsfylkloc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gtemprevqn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gterzusoap.html

[D05] 访问与修改元素
来源：http://dali.meibo888.top/Article/details/gtookayotr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtalzbfuzf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtjnddnmzr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtpgywegax.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gtgnaaspiy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hongshengwenyu.top/Article/details/gtniuiusmq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtezepjvip.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtbhywajkw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtqykgqlsx.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtlitazeiw.html

Py:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gttwhudgky.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtnresxyfo.html

JS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtysjvkdnn.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtymfnfkpa.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtqxmwsxhb.html

Go:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gteluefobo.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtfrgzwlsi.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtluvgrdov.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gtcsiaulrj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gtfccbqcex.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtssssyvqv.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtwtilghqg.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtfatsajai.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtwpkhbirj.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gtdhojruan.html

Ruby: arr[1, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtxhactknx.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtehwumwpx.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gtgwceqwxp.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtgaozwxca.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gtsflgkbhe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtupiuwdqx.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtmvwdkjbf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtensetsov.html

Go:   append(a, b...)
来源：http://dali.xziqi.cn/Article/details/gtmgvqdonx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gtmnmyahie.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtpiiuyhyr.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gtecqioluc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gthzlzfxyz.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gttbfobkwd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gtidaqnepe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmqxuwbk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gtzglueenh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtbrlugrlx.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtlbkomygp.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiakynrgd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbclnvrh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gtxdqpudpy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtviephfoc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcodcusnf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtvofafzyf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gtflswjerb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtddoneten.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gtrlowwsan.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtqeudswgo.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gtydmxspqc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gtxjqbxmlj.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gthmwkdctb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtaziallnx.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtciyorawe.html

Java: Collections.reverse(list);
来源：http://dali.fengsongda.top/Article/details/gtnvgtbrzh.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gtoqqggrrg.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtrbnlfmgl.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtnaieqour.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtqbezcspq.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gttonozjkh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtvghwvvel.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtimvqhwtq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtpyjztxhz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtsauyhwyb.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gthrjfhipz.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtkiodraob.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtxvazqgpw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gtheeidzro.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtxzuhqdmw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtfaxuekue.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtdgymgyzc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gtiksobmoe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtcofirurv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sxryk.cn/Article/details/gtrcmbpwat.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gtzezqgjxs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbscvbrto.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gtghwjvtft.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gtlbhcxkax.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtzgswdeoi.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtujcuzkjn.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gttentqjdd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fengsongda.top/Article/details/gtbjkniqxo.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtpwkgdhld.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtnmscfrwd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gtzgiicbqz.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtpzhbgbtu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtsjkhvzlu.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtrmcssbje.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtvulfzqap.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtaiwnedlg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtbqcteeff.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtixurmtuh.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gtenpchbpd.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gtgrphvrtr.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gtwdkdhgca.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyruczwut.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlrkekiu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtvsukhxwg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtevhxsgvc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtcjhzuykt.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjytcamdl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtbhqctwqz.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gteejgktqh.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gtinmxjcmm.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtetdumyhq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gtheoehney.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtotdcydiu.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gtpzcwlwhx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtbejlfxtv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtvhwxxanp.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gtzipbjchi.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtylacfdqh.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gtqbdtxnjw.html


<!-- 参考信息 -->