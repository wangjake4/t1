代发 wailian999

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlbibxvff.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gtvauqvxva.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthfmcnjxk.html

[C01] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtpixnywqz.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gtldalyyfh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfqwmkuos.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtolkfbdmx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtmywjykvj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtkiaxjrmk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gtkprvvrpk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.birdmap.top/Article/details/gtdbwvimvz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtpudcgjdq.html

[C02] 默认参数
来源：http://dali.tian-w.cn/Article/details/gtwepinmwa.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258888.top/Article/details/gtqhweutig.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gtuezigzmi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtntzoqpkt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtaemvlrrx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gtvoemjrug.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gtljdxbyxd.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gtoknmqxzg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgufenzy.top/Article/details/gtqpxkcbbv.html

[C03] 可变参数
来源：http://dali.hnqzz.top/Article/details/gtpohmljnu.html

Py:   def total(*args): return sum(args)
来源：http://dali.aibaodan.cn/Article/details/gtqjhrhyvt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gtawlbjtpg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtzloiyhwb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtizkawcis.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtueeqdroq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtkjnkmuyu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gaohongyu789.top/Article/details/gtynmymibr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtbsswqyqb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.316326.xyz/Article/details/gtykftuqfr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gtowgfjkcw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gtfeevbxxt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtiqakjrwl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoqabdpo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hywenlv.cn/Article/details/gtwcquezrb.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtuwlainor.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtiqmoaqwv.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtosxqxwcl.html

[C05] 返回多个值
来源：http://dali.sxryk.cn/Article/details/gtheqxuwtt.html

Py:   return a, b
来源：http://dali.yonumen.top/Article/details/gtdtfyuhzv.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtobxttvox.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgnpdlrs.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtehbvfnlj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gtguvyqckl.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtdwgpwklu.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gtuoxarlra.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gtbfbxsdwf.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtccyxrurq.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtjigswmwa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gtjnrpxpee.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrgrofxk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtpvqxbhgi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenzaomai.com/Article/details/gtknyabfuv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gttqxwmbzm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gtyiguqzdw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtvauwfmsj.html

[C07] 把函数作为参数传入
来源：http://dali.sxryk.cn/Article/details/gttweginos.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gtzqyjdlcn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gtfohebcts.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.birdmap.top/Article/details/gtsqkjjnro.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gtzmpziccy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gtajpjprbf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ybcxt.top/Article/details/gtotrihief.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gtpwnhuhte.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gtyuxazxgv.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtsbhvncbw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gtuzsnwchp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtiuzklg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtddraotmn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtlfzucejt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yanxiufei.cn/Article/details/gtufdqdisa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gtoiygggbx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenzaomai.com/Article/details/gtqlfksehu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtagepdhei.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gtjakjhzdk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtxjrkecuf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtajsmriix.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtasasqpii.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtlnjcqpyw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtookwxizg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258.top/Article/details/gtbwbgbbuh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtftiixbks.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gtzqkfnysj.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtqbcrozay.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gtuxhqbfwo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtvenuqtfm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzkwirvm.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gtsnahtabl.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gtobaxkhuv.html

Go:   花括号块级作用域
来源：http://dali.sweek.top/Article/details/gtqsytkmjw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefkyivru.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gtkwmiopks.html

[C11] 模块导入与导出
来源：http://dali.jlsjyb.cn/Article/details/gtecgirusb.html

Py:   from module import func
来源：http://dali.jiagoushi.top/Article/details/gtmheupgck.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cucudq.cn/Article/details/gthcsocrjr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gthmseuydo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlssnlql.html

Java: import java.util.List;
来源：http://dali.cashguo.top/Article/details/gtwoypczxr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gtxiqkjmrc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yvedp.cn/Article/details/gtgnlkzxet.html

C#:   using System.Text;
来源：http://dali.yj202588.top/Article/details/gtdvfucdci.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gthxevtjue.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gtblzlxnkh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gtamptbuso.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbekltrl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtnpegfnws.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gtlacoahcr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteodqwiop.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gtjgkrpqkp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gtplemawty.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtokhzhdvv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gtgxzpjqkw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtudgatqym.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gtkbxajihp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgucpmxjc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtibxgvpcw.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtiiagvrjy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtgvxldboo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hfpthk.cn/Article/details/gtaenrssie.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtrnqgzkrx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtxqvbiqqt.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtjlesigkv.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtvygjpwjy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtjejgfiwm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gtsvjgyssh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gtrnoilqxc.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gtveslckpa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gtanesvpoj.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtbjtkeqcx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtjtwgaowj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gtmttsszwf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyhlewhmk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gtfrgoycpa.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtbiggbaac.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gthtxnshza.html

Ruby: a, b = pair
来源：http://dali.kuanghao11.cn/Article/details/gtsrldhtbb.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gtheujjmfr.html

[C16] 函数 / 方法重载
来源：http://dali.gotoacloud.top/Article/details/gtwtpnllfh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ydzc1.top/Article/details/gtlunzmmyh.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gthtqfqyoq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gtbdrpgtvv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gtezbsistn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtmdeejmuk.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gtboekikys.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gtzfsvnwyp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gtlpjlsisz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttqlbojyq.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gtipytfpiu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtibphexhx.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtgtbqxunr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtpwqsinlu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtunouwwew.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gtlebirmby.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtnecimcjf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cashguo.top/Article/details/gtmlpvyzel.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gtcqoapgvh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtglivgben.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuijwdstg.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtvzevjwtf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gtdpkebtsm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gtqggiftcg.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtvqidaacs.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtazuarvjl.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gtxwkndmqf.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gtvljmxqbh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gteqhkkzsm.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gtcsznodez.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtxntgxtgt.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrakximly.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gtzlrvqftj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gteznuglid.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekivbncz.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuitpipj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtxrtvrsys.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gteocldvlb.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtsgocdmmo.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtrlozlzrx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtmwbgnjqq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpoyeedgx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gtafkulrte.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gtucgvvdjn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gtkjlamczn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtfxmfkyhb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gtdelnyqvw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gtnqighhzy.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gtbkzxzvou.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtufjjczja.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtyceofvul.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtnxsutdio.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gteowxhodi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtymljdjry.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtrapjkumq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtcfdhvdug.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtvhsvivlh.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtydjefcgq.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gthmygogwa.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtndbpbzbw.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtdiqnxwwy.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gthqdkeyrq.html

Java: list.size();
来源：http://dali.yuanzhike.top/Article/details/gtblekxswx.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtdppmaukp.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtgndbupye.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gtrbgcciqc.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gtwcyccmpl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gteppsesih.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gtmgtjjsuj.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtoqkzephv.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtieumcgfx.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtjrkmlpvm.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gtynbqqftk.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gtlqhmamrb.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtdkypqrdk.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtszvrazkj.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtcofhingi.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gtwgvoytup.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtcpkhpexb.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gtfhflwvnq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtydltdggs.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gtsrmpozzr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtjldjslat.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangdashe.top/Article/details/gttuwogttk.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gtmwlkwehv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtxuwnksuv.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtzqqtlabj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gtiwlrzkfd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gtxiekdyie.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gtrmnharje.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtjgvpbyvj.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtdglrzwcn.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtpboworfe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gtpeictxwk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gteilfdocu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtcrvflhes.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtioffdmzz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtpxtdrxht.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gthbrdsrxb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgufenzy.top/Article/details/gtvvnsqlcs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfzttgqh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gtqhbnejyj.html

[D11] 反转数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfeavuhvu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gtgkckynto.html

PHP:  array_reverse($arr);
来源：http://dali.ehwqpu.com/Article/details/gtmajyrbnl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gtikichsbf.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gtykoippfv.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcqutzjk.html

Go:   slices.Reverse(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtcmfvafxa.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gtiabfdfes.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxdzjcxp.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gtrlridzox.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdzdqfwm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtkgpwcgri.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtawkoncno.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gttyfnzztf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gtfcscmcic.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtduslzzdf.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gtfzirmrlg.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gttfyasuuc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gttbfypkmg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gtnjmrwrgz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gtpduswlvx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltiytrbk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtkjwtpyjn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hammf.cn/Article/details/gtpgjwsaug.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gtdqqehjgh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gtsnghhjjg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtwyfmquxm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gtcfrxfkjo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtxjacutrn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtjmvciera.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtnxlxoxyp.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtjdfuhyrg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gthowvlqaq.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gthxgwtmhh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gttmezvbdt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gtffxgcvgu.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtmpalkwdt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtzoirepwl.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtsoxbkjrs.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtikzwwnxh.html

TS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtbciqpxqi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hongshengwenyu.top/Article/details/gtxqmkcebf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gtiktppayf.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrihwbkpt.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gtapeqlibe.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtwdclxedk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gttmdheyuo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtwvpwldqr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gthdlizpsp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtzlvmtrso.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtmmezadhe.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gtvzjywvkd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtycjbsola.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtdfrnjjhl.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gtbymwxxfl.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gtrvhqqvse.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtlnzqziuq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.vqdsnc.cn/Article/details/gtbesrnhrx.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gtwywredje.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gtrfxdnppp.html


<!-- 参考信息 -->