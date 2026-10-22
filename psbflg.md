代发 wailian999

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtdkitorch.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtxwiywbuw.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtzievkvko.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tian-w.cn/Article/details/gthbgyhbcf.html

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gtldjrrckb.html

PHP:  if (!$data) { return; }
来源：http://dali.hysaishi.cn/Article/details/gtpvuahggw.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtjvnajcuf.html

TS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtatmztisn.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtjbgntqaf.html

Go:   if data == nil { return }
来源：http://dali.jqgfzy.top/Article/details/gtipthwsfu.html

Ruby: return if data.nil?
来源：http://dali.cdnleiting.top/Article/details/gtaviigslz.html

C#:   if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gttwnwqsck.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgmvcbcb.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtkyxrumvu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvicqzplj.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcxrvfkl.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtzljsfmzb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtcnxuysqb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gthjccphbf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtannjlrml.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtdvxuhutj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gtcbfgwapt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.feifeiyinyue.top/Article/details/gtepzantlu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtqnprilsa.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gtnacxwiab.html

Py:   def greet(name="World"): return name
来源：http://dali.gzhubu.top/Article/details/gtcgdyofrx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gtsxlhirav.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gteoyoihlt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtvabrydqt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gtaguuffna.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gtvycucwyx.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gtuswadzbg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gtgujnghbh.html

[C03] 可变参数
来源：http://dali.dianchejie.cn/Article/details/gtlgrxhexh.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtycyuxkvj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtmvepwzah.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtxaygyljl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtjmwibmyv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtlyttnovf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gtlwyoneir.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gtghdoeqmg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gtaswfezmh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gtgwfxkgso.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gthpexppyh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtmmjstesd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gthvuvmkeu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gtivzpdtua.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258.top/Article/details/gtafrtcevi.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gtezyzjyym.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtxwfcrasm.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtplaubiin.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtrexsfbfw.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtjhofffno.html

PHP:  return [$a, $b];
来源：http://dali.9152youxi.cn/Article/details/gtlwmvkucs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtazmlmegm.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtmzyueous.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dashuyun.cn/Article/details/gtdyzzffjw.html

Go:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtbubrzcya.html

Ruby: return a, b
来源：http://dali.tanke756.top/Article/details/gthnwlmuto.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gtpankvpdt.html

[C06] 匿名函数 / lambda
来源：http://dali.iojbl.cn/Article/details/gtcuccmlnt.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gtgokwepfd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduvwafhr.html

JS:   const square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtlrjlwtpf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtipwqipnm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hysaishi.cn/Article/details/gtlyrriohe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gtqmnzrmde.html

Ruby: square = ->(x) { x * x }
来源：http://dali.redwolf501.top/Article/details/gtkqaebsst.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtxqufcynj.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gtladffzhs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gtrphuuiob.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtiectgwrm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhongyouzk.top/Article/details/gtegovjbxq.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gtaovirvwl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigufen.top/Article/details/gtjpjjlmoz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gtqunwlxrr.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtdfthemow.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtuxbhdwwj.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtemftqyqe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gtykgjryxy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtadfywvlu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtqxaoudvk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtfseemsoa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtbdltsbmn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jianghu66.top/Article/details/gtuscydwey.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gtjwadfkch.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtoeazmzhe.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gtjvskgilw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtsovrxqtq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtblqwaein.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtpbyigtaj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtgroktusd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtcchhujnd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtxklwhgpd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtxpjbucnz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daxiang520.top/Article/details/gtumyewhwf.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gthltjfbwz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gtrpcnwxwi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dashuyun.cn/Article/details/gtrqzcusaz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gtliuiotlu.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gtsbxjnazg.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtjwrsbwyk.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gtqeckptxo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtgirxfeef.html

C#:   块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtipzprqqy.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gtrzhjhtgs.html

Py:   from module import func
来源：http://dali.sufxvd.cn/Article/details/gtrdjookrw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.mhx1999.top/Article/details/gteyurvvvl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtzuguidab.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gtrsvihtqb.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtbrocojzo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gtdjmvzxux.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhkqnszr.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gtpsbmmgym.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gtztijauxz.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gttenegizx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gtwwtubkiz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtzgcrkneu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtzdofqzub.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gtqkvgbkrn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gtaicspbcm.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gtdbcrsqlz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gtdwlwisll.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtmacdaltn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gzhubu.top/Article/details/gtiontlsop.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtuodaoucl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gtzvrwoazp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtnkilijqi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtdyomslbx.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gtaatmieuz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtdskkfkwg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gtnqpmcrln.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gtrhkhagas.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtclawqlof.html

PHP:  // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtuibseazy.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfthyqbl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gtwodcfulc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtcuwuvlul.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gtbokzznjm.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtokdzageq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtaihkdbds.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gtbdbgcenz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gtmkbiuasd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtfylmwhxo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gttcqeghcl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gtxirsxukx.html

Java: // 无解构
来源：http://dali.yueranfly.top/Article/details/gtnoynyvss.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtnaprwsdl.html

Ruby: a, b = pair
来源：http://dali.yj20258888.top/Article/details/gtpwuattrv.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtdyxduulf.html

[C16] 函数 / 方法重载
来源：http://dali.daxiang520.top/Article/details/gtavwdsocx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258888.top/Article/details/gtsvvzglyg.html

PHP:  // 无重载
来源：http://dali.smart0.xyz/Article/details/gtunyuolbb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guannengcc.top/Article/details/gtdlmrowcm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigfzy.top/Article/details/gtcyzohpyt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtghmenhnu.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gtdxagzqwo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gtlripaywb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtyezckqgp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcmuwsxjx.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtgzmmzoft.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzirtnwcm.html

[D01] 创建数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gtijaprptq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gtmxnqimlc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtfxhaskmx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gtovdqnipa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtwdbbienj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gtzqrvdjii.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gtksfujasn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gttxdhrunb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gtegqyhcec.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gtlstvogoy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtzdsviuyh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtchapxgua.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtjyvlmlef.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtdckbvkhz.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtrnfljzdo.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gtdbxitnvx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtwonnwyjg.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gtnuekdfiv.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gttenanwaa.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtmyxtovft.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gtoofseqbu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guannengcc.top/Article/details/gthgstcyrh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtiaovenrl.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtexxxyavv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gtwqeaevge.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tanke756.top/Article/details/gtyeyryrgu.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gtczcwavog.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gtwvamkkqd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtrssaaqvk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gtitsgfrfg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xziqi.cn/Article/details/gtxkjnbzya.html

TS:   arr.splice(0, 1);
来源：http://dali.cheryme.top/Article/details/gtpjhjqxao.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gthlwicpsk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gtylrwpxfw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtxskoqqzq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gtqgqeqaih.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtwpboxdsh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtwtqvrwhc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtentbpotu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtnzuhhnmw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gtrhfxlonb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gtceyusojd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtxebggojk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtadcgvnwo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtnpndlojg.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtccjhdpmd.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtfcbgpviu.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivjexmeq.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtallsrmbf.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtfyzskrvd.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gtfibcxqqz.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtttdledfb.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gtsnynglyn.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtbgpkvdkg.html

[D07] 切片 / 取子数组
来源：http://dali.yj202588.top/Article/details/gtqdhuuovu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gtxazlqgtt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gtymmxvrfv.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtaakrjiyp.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtrabpcpil.html

Java: list.subList(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtvxlseaqa.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtayafnfpm.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtvruacghj.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtqtprbajk.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gtccdtzhzz.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gtxxwokoer.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gtvyruyvur.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gtdekquhpa.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gtnvfagewl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.316326.xyz/Article/details/gtkcemskbl.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gtdkmxmyii.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtidutgoef.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtywmzybze.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gtsuutrynr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtcexflckw.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtjktryfgu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtpvaayyqt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmtrputj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gtoynunfxh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gthhyvbbfa.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gttwkfvxdi.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gtxddnbjme.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gttdwmkywh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtmavikagc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtaryrsawh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvewbqif.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtemkrzzyn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hongshengwenyu.top/Article/details/gtqnwsmybv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gtbqpujlyk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtxqpwpdkj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtmccuexsu.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtgcgvojea.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtbdrthxvl.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gtlbqjqfog.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gtdiqduawe.html

TS:   [...arr].reverse();
来源：http://dali.snrcjt.cn/Article/details/gtuevvxqkk.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gtfbhkubbx.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtievtajpy.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtqpnwncyq.html

C#:   list.Reverse();
来源：http://dali.daxiang520.top/Article/details/gteldnevwf.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gtwifoxhdo.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtxlqakqff.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtsvcgzxri.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtqzjywrrv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtggonfirn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtwteuyiwk.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtrypzygpv.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gtrfdopjsh.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmqofrfy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gtbgnsadup.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gtejobtqkz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gtklotbfgq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtwsgnmktt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtwrgzhwtz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gtzpekonzg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gtvdizrcgu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnbytjdv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gtxyapsogl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gtxqlorafv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gtxeyuajst.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gtsvxzzsth.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtvmpebzbp.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtbebxbfjc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtuydnmjqr.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtloxmrxsg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtfukpjkxq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtunwcrvoq.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtdvwglxxy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtmwcbkvjl.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gtesxxfhhi.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtbrssgfke.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtwbwkjiqo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gtcyhygpmd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtnhagwmrf.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtunrduhej.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtgodofyvb.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtfzyoacao.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtxnovujpk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gthqlykuhx.html


<!-- 参考信息 -->