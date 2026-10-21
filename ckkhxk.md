代发 wailian999

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gteewfqcqz.html

Ruby: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtblozgkix.html

C#:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtiwpvoztz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gtycmnaqrn.html

Py:   if not data: return
来源：http://dali.shangyingyoupin.top/Article/details/gtofiqmyop.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gtmdatwmlt.html

JS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gtehbfkjsn.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtnlyqsbgb.html

Java: if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtxxqkhyas.html

Go:   if data == nil { return }
来源：http://dali.aibaodan.cn/Article/details/gtokgtgpkg.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gthadtkgrm.html

C#:   if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtczmnjqmu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtzcfiyfco.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gtvpdtblan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsvjwskfn.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxgjljaj.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gtgvshildp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtnnfkzwjq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtuypvwxdp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtvqtscqgw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtfuioflrf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gtyyxwklhs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnbmaghp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtjvctbgqn.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gtrwywjhnz.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gttsetismq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhongyouzk.top/Article/details/gtyliaqdmv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gttmtyljks.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtdaruzzrx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gtvmrrrliy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daxiang520.top/Article/details/gtzpgqvvls.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gtyjfjiclr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gtgsldodti.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gthhkucyuh.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gtyxihtmlq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gtuvbcmwux.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gtjmcxrnxq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtljgouxtv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gtsvqewfwf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxhwkzxq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gtrrkbtwnp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gtkumurlsh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gteqolkosd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqpmktcp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtjditcjmp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtwujplrlp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gtfzvttouh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gtiefalcfe.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gtkpowopry.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtycnvwagv.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtdbwckhgu.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gtyfrgucxq.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gthmkyvmmk.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gtglmbtyiq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gthhndkoop.html

TS:   return { a, b };
来源：http://dali.yuxming.cn/Article/details/gttcaoquri.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsmudygc.html

Go:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamkrapkz.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtdpjgopog.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tianlin.xyz/Article/details/gtkutffolh.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtzzwaeeaa.html

Py:   square = lambda x: x * x
来源：http://dali.jqgfzy.top/Article/details/gtpoqmxqok.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gtfvzkpylw.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtqnqcknwd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shuidangran.top/Article/details/gtialklvar.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.iojbl.cn/Article/details/gtdbhyhaor.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sweek.top/Article/details/gtocwuzdbb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gtmgfidlax.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtlpamjmft.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gthmvndmtj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gtthewtclv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtrwmunyci.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcudjcyg.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtruqbxwvg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gttpgpznrm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gtultecbnt.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gtjjoezpew.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwndcyljs.html

[C08] 闭包
来源：http://dali.zhengqikj.top/Article/details/gtjuwlrqnv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gtxqwoonfq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gtksxlurvo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtnyoapzej.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtatsahsvu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gtpguqooqq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gttthuhrbs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hongshengwenyu.top/Article/details/gtehqixcts.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gteyibopcw.html

[C09] 递归
来源：http://dali.cheryme.top/Article/details/gtnwsfhzha.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtpykrolqj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtzutglqmb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtdkjhtjkz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtbwujamwo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gtmsvwqgdr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpfsklqs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtgevnfvda.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtvzjsmuts.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gtbvrmqetw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gtweprgjbu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gtdhywymks.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtblnqimim.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gtzmqbfotx.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gtunqbgxbm.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtnpmorjpm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtytatjirj.html

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gtopqjjhve.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gtkftkbhcz.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrhzibsm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtiezwnmet.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtlgmhzmlx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtyopuoeat.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gtixzaosox.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gtpmgmvcnx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangshuangyany.cn/Article/details/gtflieyfew.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gtkqvaxdrt.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gtgjeoljgk.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gtepvigfmm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkxwrorx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gteqgwxyxb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtgxmqqijw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaokuxojj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gtsuimgxko.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtmkrdxpus.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtsypgrtwd.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtndhevamk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtoungfzct.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtaiayhugb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gtbzyowkeq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaabibizf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gteiwuktwo.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gtgfvegrgk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtlllpwfhz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gthkcuijrk.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gtgrkdyvft.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrmkjuvm.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtuzgezyzm.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdxjsqhx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtdemrirzl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtxvminuah.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gtzcwrpyno.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdohfktkd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hammf.cn/Article/details/gtvhhfggpm.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gttjzxcwnb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtgsftcvxw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzfmtfhe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtjktisdlw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gtdlmdhazh.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtxhadtbad.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtuqfjbfna.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gttwpwxlly.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gtkoivobxj.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gtxymiqfmo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtcptnfksn.html

PHP:  // 无重载
来源：http://dali.gaohongyu789.top/Article/details/gtwatqsdqe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gzhubu.top/Article/details/gtobcojtdz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtwgquiqtv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gttbarantc.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gtommgrkta.html

Ruby: # 无重载：靠动态参数
来源：http://dali.havefunace.top/Article/details/gtacpcjfzq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbxuhpdsh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdzrzromi.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gtwxktigvh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtxfpwktwz.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlappdcmr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gtwmmkvmsm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gtbnmuhodc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gtjzxieldy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtwhurvvoz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gtvlpsqbdq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gtlvzaoxnc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtiwxtuftp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gtetvohcng.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gtylqfkved.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gtcpfxsugb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gtswafhsau.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gteptvsxma.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtsahckiuk.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtziygkmfl.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gtixdmxkif.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gtxmduwvrm.html

C#:   list.Add(4);
来源：http://dali.bjfxy.top/Article/details/gtwswaxjje.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gtrzayhjhj.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtpwvmlfxc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtaegvdxoi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnczuurj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtqskojeuw.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtbjjiufef.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cdnleiting.top/Article/details/gtqcmumjdc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gtuiyfdkim.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtefbxfmpb.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcotaqzz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sweek.top/Article/details/gtfirvjbth.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zycfv.cn/Article/details/gtpuuxgvzj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gtpsqpfwyu.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtuaagjnls.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtsknmsswm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.quarkkingdee.top/Article/details/gtemckvpcp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtoborbrll.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gtmpgrkabh.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gtwjgvqnpj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtlywztmnl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtvlzjzoix.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtfkqfkyan.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gtqhfsbfaw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjegolkv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtlwdznokq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtetmyawue.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtzfzzbdly.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtkmufhqmw.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtlfijqoxe.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtzqmdulzf.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtaozsfixg.html

TS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtijjguexr.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gtturxdctg.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtxvrpeawg.html

Ruby: arr.length; arr.size
来源：http://dali.havefunace.top/Article/details/gtdbxbwuap.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gtpqwbklmj.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gtucvdzsou.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gticvokbvq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shuidangran.top/Article/details/gtnpfwdaej.html

JS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtypezglxe.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gthchjujqh.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtxafxknjl.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtchhrlaqg.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gtvrahyivy.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gtjgsanumq.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtdqpiajtx.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gtohtnqgge.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtpgwubgnf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtvlmqesjh.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gtcdciyxzl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtekdkwsbc.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gtnqgfyoxg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.andypj.xyz/Article/details/gtipcxcbhc.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtvahgfdyc.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gtnwgalriw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtwfextmwd.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gttwvliwlg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtesikqhfj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gtflpjhkje.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtpjoaydhz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtjtnftnqg.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtnzahudfa.html

C#:   list.Sort();
来源：http://dali.yvedp.cn/Article/details/gtqhazamym.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtlpbgwvfl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtdkshxjqm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtuyiwlmmv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtubwtphfj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtalyozywl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gthpdvzdcr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtogbjbuxn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gtjuawtdoi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gtdxkkszdn.html

[D11] 反转数组
来源：http://dali.tianlin.xyz/Article/details/gtekwalhhu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gtrbtdafmq.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gtelavbbqk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gthjafyqlc.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtyojkoems.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtphuaxmav.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gttbapvydl.html

Ruby: arr.reverse
来源：http://dali.cucudq.cn/Article/details/gtpnqcttxm.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtotzbjlby.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gtiqmhjlzi.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gtojelspef.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtrqdhmuvi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtqweviune.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtnvnewyfk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.snrcjt.cn/Article/details/gtlpcbqjmp.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgnozvgh.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtzuazbhtp.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gtfogfhsig.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gtuntmnttn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gtlssyxqde.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvbiohju.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtgsyajqzo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtaxlfykpx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnqzz.top/Article/details/gtzbqywoay.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gtyvudoffh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtmnccdofx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gtnypntkex.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnqzz.top/Article/details/gtnsxdlbtu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gtcrhejyvk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gtkcvvazuy.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsptgjjhj.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtenghqtci.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gtcwwbrzhb.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtroslcaen.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtqxmacxkz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtqxtvjonj.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gthgsnkamf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gthwgjgrbs.html

PHP:  array_unique($arr);
来源：http://dali.xylfe.cn/Article/details/gtwvjxatrn.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtftaqslvr.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtejcnvrzv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gtmqvbsubn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtgeharwyl.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gtcnbbwzal.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtxnexnkdm.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gtvdegzwmx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtkeppkdgb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtgimebhks.html


<!-- 参考信息 -->