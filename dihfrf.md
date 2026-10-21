代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gtyhikvfkm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtrshljyle.html

[B15] 布尔运算与取反
来源：http://dali.jyoumei.cn/Article/details/gtqsniodxm.html

Py:   a and b or not c
来源：http://dali.gogol.net.cn/Article/details/gtzniixapr.html

PHP:  $a && $b || !$c
来源：http://dali.quarkkingdee.top/Article/details/gtcyotpwtd.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtsbbbnhle.html

TS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtjgmerruh.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtszvkunui.html

Go:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtescafzsl.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtjgrdvyhc.html

C#:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepdujknc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tian-w.cn/Article/details/gtneallrdl.html

Py:   if not data: return
来源：http://dali.xinyue.icu/Article/details/gtvfqrzbfv.html

PHP:  if (!$data) { return; }
来源：http://dali.shangyingyoupin.top/Article/details/gtezldurbf.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtmaewngiz.html

TS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gthwctwhtj.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gtzxbrgtha.html

Go:   if data == nil { return }
来源：http://dali.fzhhl.top/Article/details/gtnpwfvdlx.html

Ruby: return if data.nil?
来源：http://dali.yvedp.cn/Article/details/gtoyytonyk.html

C#:   if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtjmoaodwi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkwipcnxf.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gtdfmwntvc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtroavozjb.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtwueckuqy.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtpczwjkkm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtvnqpyoay.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gttzgfiubt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtfexemopd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtcabjbojm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplhizgfa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtoblirscq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwnzzsqow.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gtucskjaaa.html

Py:   def greet(name="World"): return name
来源：http://dali.wangshuangyany.cn/Article/details/gtsxghkgwh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gogol.net.cn/Article/details/gtyltqzitq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtwkrsmjrd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtgnbfxwoa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmggbggg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtxajieokd.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gtxdyekcgs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtyadmodex.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gtwdtrxaji.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gtnfqvrcen.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gtsoqfgtdv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtgdjbfvdd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtgymhztww.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtpbqmsmmx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sxryk.cn/Article/details/gtjjmenozr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cheryme.top/Article/details/gtcjhzufid.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtbqetxigo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gteaivtzpf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hammf.cn/Article/details/gtxsubezib.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aibaodan.cn/Article/details/gtlwpjiepn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtxglsmksv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gthkohwkgd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gtqmcdartz.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gtsuhwuhek.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtxsjcjyjd.html

C#:   f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtnoyqjech.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtrovcnjjj.html

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtxnosbetf.html

PHP:  return [$a, $b];
来源：http://dali.sxryk.cn/Article/details/gtzfckybuj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtnjfrrasz.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gtbzjtoctl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gtljoxnclp.html

Go:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtsiadxdwv.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gtpfyuvgsb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.quarkkingdee.top/Article/details/gtysvnatir.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtlzhjkupj.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gthzpofdxg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenjidiqi.icu/Article/details/gtmgyqfxgi.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtytcugzgo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtmztvviti.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gtvhzxuokt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gtokfpvbrk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtzpxzxetc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtnyjzkcbl.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtbqtenkfi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tian-w.cn/Article/details/gtiyssbids.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gtwwvqscwh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gtnrbfhvnu.html

TS:   arr.map(String)
来源：http://dali.gzhubu.top/Article/details/gtiiegccxq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gtlubewlvi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gtfssbqkcj.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258.top/Article/details/gtvwzphyoc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gtnirhyxsj.html

[C08] 闭包
来源：http://dali.fengsongda.top/Article/details/gtofgttpgz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtlfrkurbp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsphajdc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtldbdelod.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtcmxlyphd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.vqdsnc.cn/Article/details/gtzxpxuwmt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gtahymjvei.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gtwiqbmbwr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtutdmagzm.html

[C09] 递归
来源：http://dali.dianchejie.cn/Article/details/gttfahkknt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtlojohsbz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtwjpqefwk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtbskytlyy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtqqadjjxv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtpuykwzoo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gtzwkrcldd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gttcoxncip.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gtagmxodtm.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gtrcgdzpsy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqttajcq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gtwroixvak.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gtnikwznrw.html

TS:   同 JS
来源：http://dali.xylfe.cn/Article/details/gtbixkpszt.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gttnrmunsj.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gtlmxrzszh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gtesiluvpl.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtozkytqqb.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gtzgettmjq.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gtizpuodgu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtsifpcymq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtzhrsgbld.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftcpwhlf.html

Java: import java.util.List;
来源：http://dali.xinyue.icu/Article/details/gtwsypxegz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jianghu66.top/Article/details/gtuptcocik.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gtvhihdbtl.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gtjvswlwqw.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gtasbokcyp.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gtghuhscyh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gtfchauxsh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtnztnpbfs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtypxuhimw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gtursxzhrw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gtujjajnwm.html

Ruby: -> { puts "run" }.call
来源：http://dali.birdmap.top/Article/details/gtivjaaczd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gtmctwnkph.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gtbphopbkz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gtyzvhrwnc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gteqvchjry.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gtktonmpcw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtrxaomgom.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtkbckmjbj.html

Go:   func add(a, b int) int
来源：http://dali.cashguo.top/Article/details/gtfmmdcuzz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gtifgntqya.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gtdkqyfyfo.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gtsrosugib.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gteukncyto.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtxrqbwhed.html

JS:   // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtrneoqqnj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtddfcrmpy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvaffilwe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xinyue.icu/Article/details/gthtokwhef.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtwulrehpe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtjrzljjdk.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtzfpndfco.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gtgjprlayr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gtebqbvhwu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtacspmjxo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtlphegvpf.html

Java: // 无解构
来源：http://dali.yonumen.top/Article/details/gtgjmqvlny.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbifgvnio.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gtndrxmeur.html

C#:   var (a, b) = pair;
来源：http://dali.xylfe.cn/Article/details/gtywtbutth.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtlgfgjlhg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtriovirid.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gtbqrnldgj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gttjmefukd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtqbvvmsir.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtrrhkzqig.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gtljkkzodh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gttcxwdztp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtiqkateuj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxsqtzfpx.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gtypcfexfz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtotrkfvco.html

[D01] 创建数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gtxfvyaqsa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.snrcjt.cn/Article/details/gtuxlnhklc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtwijrxvms.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gtuocjbjkf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjjeuanf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gotoacloud.top/Article/details/gthamfjiyg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gtchhajynv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gtyowjcgbv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gtrhemqleg.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gtribsdqhk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtvclidjnj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuanzx.com/Article/details/gtjhvcsixs.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtiqlwwqcs.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqninhdo.html

Java: list.add(4);
来源：http://dali.tianlin.xyz/Article/details/gtsqtiojbg.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtmyhuilre.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gtnoaxprjc.html

C#:   list.Add(4);
来源：http://dali.iojbl.cn/Article/details/gtweoberow.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtyqiawfok.html

Py:   arr.insert(0, 0)
来源：http://dali.fengsongda.top/Article/details/gtbpcidrsm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gtbsqbooqn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gthbkdsevu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gtzyphmiwe.html

Java: list.add(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtwvoiewfm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gtwfeiitpx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cqqwz.cn/Article/details/gtioaukwcx.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtrmhlyywg.html

[D04] 删除元素
来源：http://dali.pycfn.com/Article/details/gtwnugftiq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwojlbme.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttynesonf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtmavabqwq.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gtaylegatn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gtceusttiv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtmyjuqhpo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtqpokamjs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daxiang520.top/Article/details/gtewocdopn.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gtbfbhainu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtbznlvafd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijoeaddr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtjqngokxb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtkjplyjdx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gtcdsywpok.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtnoebwfud.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtkhonjllk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtoxckxzje.html

[D06] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtanwubifa.html

Py:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtxmkvgnfj.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtdhojfqrg.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdeilnxrr.html

TS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtnzubvrok.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtxbixiyvs.html

Go:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtohremtse.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvgghnir.html

C#:   list.Count;
来源：http://dali.ydzc1.top/Article/details/gtksjqurqm.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtsrfhjlwg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fengsongda.top/Article/details/gtnraoftop.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtfvpvapak.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtsqaeycph.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtmepzxxfb.html

Java: list.subList(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtnakjiejt.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gtxhjrptea.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gtahmmcuwo.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdreeicf.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gtrxpdokgk.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gtezguealy.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gtmuszprum.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.316326.xyz/Article/details/gtxwgiliim.html

TS:   [...a, ...b];
来源：http://dali.zycfv.cn/Article/details/gtmwgwneqm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gtugwkfqsm.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gtyfkptpzg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gtxixipwnu.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gthfltouyl.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gtbyeohgoa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtgdhzusxq.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gtuohxiukc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gtsllakgss.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gtdpjxcphk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gtpxmxnlfr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtznxzcplz.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtetuifabw.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtuwaolugv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gtdwcrudgz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gtesomqagn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gttjphwijx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtpaypidiy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtaqfuwnaz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gtdjbggjaq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtkqtrgujs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258888.top/Article/details/gtkoaeqkpb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gtaflnhlps.html

[D11] 反转数组
来源：http://dali.hywenlv.cn/Article/details/gtjjptkqry.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlsjvluu.html

PHP:  array_reverse($arr);
来源：http://dali.yuanzhike.top/Article/details/gtirltdwnm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtuneykpgs.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtqcxgmayn.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtguvabnlh.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtqzgfuofv.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gtixxcratf.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gtihpwjmrj.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gtjbmtanxb.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gtbmcxjidb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gtujmccmam.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtuyqjdaug.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtnbgxwtve.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gotoacloud.top/Article/details/gtpwnurjed.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtkidfgnae.html

Ruby: arr.index(x)
来源：http://dali.0kj1m.cn/Article/details/gtbybhmyub.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtltsqzyoo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhzmeyal.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtgyunjomy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hfpthk.cn/Article/details/gtictqlcvj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtbzpljfdd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtgqvjpfft.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaywokew.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtagrfwgsc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtkvuirlxg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizopelnf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gtfjfxwrhx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtbozsyjbi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtovyvthme.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtvnwsixho.html

TS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtsgrkrscf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtdbdujpsr.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtvijpcpaz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtxzgirtuq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtjyqkmezt.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gtmcobeniy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtgbdrujul.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gtaesxtesn.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtlnzgeunj.html


<!-- 参考信息 -->