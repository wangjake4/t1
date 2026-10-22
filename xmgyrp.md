代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtrtcvwszn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpuournkh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtzhqtpdzj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtyoeforxd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtbothkjke.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.havefunace.top/Article/details/gtabtwaauf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aibaodan.cn/Article/details/gtkusqdkli.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtouwdnpsw.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtnvbnxpnh.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gtxcjtifxd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhixingplan.top/Article/details/gtsjrskjfm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtlcjggsib.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvcclbpyx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gtnkiulgzd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gtohfwwnad.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gtbbkjpwkk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gtkkfkpnre.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gttguxwqex.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gtqhnxoriq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gthpseecoz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtwpvesmop.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtobyhwium.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gtxpjudbzs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtdjuvfzwe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmlemgpa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gtsqnfijdb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sufxvd.cn/Article/details/gthknxywzp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gtfpnfdlgt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.andypj.xyz/Article/details/gtpvobjpkv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtzvxttckj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gtghacbylt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gtzaieaion.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangdashe.top/Article/details/gtfehaqgtu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtporqdhbm.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtnreepmvr.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtfjmttgob.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtlhfblmtg.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gtdyhnbdrc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtritsnwpy.html

TS:   return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtfoieleca.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yongpay.top/Article/details/gtivcckxlz.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gttjhypeti.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtxvxbtxbi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gtocxpjgmu.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gtrybksyfg.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gtwpkboscj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jianghu66.top/Article/details/gtwqmlckni.html

JS:   const square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtiunsehpy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gtfhpaqady.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtbzddvlmu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gtjiaczjcz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gtgerjfesl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtiicesvgt.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtnqsbvdkw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdlzxres.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtaiyyuqku.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gtgehtmhrj.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gtldomhbip.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtenbhfccd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sxryk.cn/Article/details/gtxgfrtpgj.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gtdejyanxu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gtlfrlktpf.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtehlajban.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgtdjmvp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoxprjsx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtvkkzubka.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtkdtmyztq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gtwlogfkfj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gtieftshlc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnyqluou.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtwluommau.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gttwoayyev.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtbjjhxtad.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtdvpvttbx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtlykwzcdj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtkaiqfsgr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvmufqebh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gtqajfeowr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtmmfjusyl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gtvrouwsgf.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtinvvfvxa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhengqikj.top/Article/details/gtiffdqyll.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gthmqvsvaj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtsvxtavun.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gtsqyqoaiw.html

Java: 方法内为块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtchcbvval.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gtictmhhma.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gtmvvdkqyh.html

C#:   块级作用域
来源：http://dali.sweek.top/Article/details/gtrdhhhnxn.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gtsxnkpcoj.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gtxnttzwhn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gtbtgijiyq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtbsdoxsdo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gtfwuvfaly.html

Java: import java.util.List;
来源：http://dali.sxryk.cn/Article/details/gtalgbsrua.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gtiifztzto.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gtkmamtfni.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gtmpfayhil.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gttqunnrms.html

Py:   (lambda: print("run"))()
来源：http://dali.mhx1999.top/Article/details/gthscwahrv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gtjlbfxawx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtwsivpxvz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtfaelbnny.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gtvgulztgt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtwbapxiyp.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtabhiytwt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtjocqcdmf.html

[C13] 类型声明 / 类型注解
来源：http://dali.tian-w.cn/Article/details/gththnmuom.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtpsjfmtzy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjpibqzu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtpyudaikk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gttepczbzo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtvlnlfxkb.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gtlpklepdt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gtgqdogang.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gtklrlifbg.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gtacyqaize.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtacgzaoit.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtkuqcvrqc.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgqfswys.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gtssnnipdb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ehwqpu.com/Article/details/gtiuddzdxo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xylfe.cn/Article/details/gtauynsmhw.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqduwbev.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cashguo.top/Article/details/gtrntejspn.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gtqooislqp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gtjzkujdat.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gtpnztgjco.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtibsdortr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgyayxka.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtnfjtaibh.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtqovohiks.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilghmtzt.html

C#:   var (a, b) = pair;
来源：http://dali.smart0.xyz/Article/details/gtwcbiahcq.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gtdbbapbfz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gtteiihuoy.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gtlifmgynn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sufxvd.cn/Article/details/gtfmktezqt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gtqtqboqtw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtwrfvrrek.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gtdrgdxpfg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtimbknbcm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmatdndjt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtujpgrqfo.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtdpnaviic.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmltqrddf.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtxjvcbmct.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdxrtvep.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtxrsipyaf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sysykeji.top/Article/details/gtjellmsfs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gtxrlnnmtj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gtwkiejlxq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gtslavswsy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gtxlprdape.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gtfwwxxmnc.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gtglfcpnzx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gteynobios.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtgwymcwww.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtgqdkhciv.html

TS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtcicldzfn.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtnabpxuoj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtefnxdmxk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gtkzojerca.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gthgkbfbez.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gtbnrdhlno.html

Py:   arr.insert(0, 0)
来源：http://dali.bjfxy.top/Article/details/gtpnaipmqa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gtqfircqgt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtmnvdaowl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gtczhxyigd.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtgbdicerk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtnvwxcsmk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtjtfonqwm.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyenhvac.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gtgsterflp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtuuibzrpj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gtbzliscqw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gtfnrhnzsu.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrtavvwp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtwlzrflrj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtnddadgzv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtajbrdduy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gttuuxcpue.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gtmbewxzun.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtqetcvrws.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtchibprse.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtioybslhq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gtihwubfny.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.mhx1999.top/Article/details/gtammsxnhp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtrjfiuknk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtrgkbqpkc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtaickqdjw.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtujflloxy.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtfbhitvlh.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtrpuptavn.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtgxakgdkw.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtnzyitrnz.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gttwcwajwr.html

Go:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtataxnaik.html

Ruby: arr.length; arr.size
来源：http://dali.aizwys.cn/Article/details/gtgfnvloej.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtmclejxvw.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gteeapcabk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gtexpraokt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xziqi.cn/Article/details/gtumamkutf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtkgewvecs.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtbmmxlymh.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtvdxlvogv.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtxdrekjfm.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gtzpzzbvbt.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtxqcozozy.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtwmrccgaz.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtkkdpikjw.html

PHP:  array_merge($a, $b);
来源：http://dali.hnxiangtu.top/Article/details/gtdvqcsbaf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtaluqgytl.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gtlwbpsmsw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtopjvodsf.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gthvzdeevv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yanxiufei.cn/Article/details/gtofofvuwn.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gtfvusewjl.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gtyksxhpzb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpylocel.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtmoxfrtck.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gtxcxencdx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gtokxzwdva.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtlwpdwmxx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtawybynat.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtzollfaqm.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxdyiuwb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gtcuzpmhdv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gtbunuipik.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gthcxetgmw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtjkxwxxgp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtoxpbjnvg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gtkmjivjrq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejnaqqrf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtmsexzsvl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gtetaauytc.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gtricmqrtt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtknomjjfu.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtxnpplzeh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtpjjaionq.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gtqhnfevsf.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gthyhseyki.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigufen.top/Article/details/gthljbwyks.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gtlffymxcq.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtrgcvyjjt.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyjhvqat.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtckqwlizh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtqxngoeyl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtqunmfxvn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtpmozqccj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtmurwaihh.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gtilrmxnkz.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtolptockb.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gtwepmbuay.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtwsnatazn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtrejjryxr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gtlggakqve.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtmndgiitc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtibuhwsid.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtxjntdkxn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gtwhjygqsd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtwmbzidzo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gtmnexbzgf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gtpjbcdxph.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gtqobwvgif.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtdwahceil.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtbqpdivpp.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtnrprtwjs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtzfwwvzhl.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtgnuyhqgm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtwttjqepq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gteglmkcas.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtdepnqpst.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtehxsgcic.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlimerzzp.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkawlnzlf.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gthdtxugtc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gtgbicdxgh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gtfgskhfpj.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gtljhqsmth.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxjpzyeo.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gtyfbtposh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gtpthtwivr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtmjgpvmpl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtrrkhyfgb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gteshlsihw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gtkfblkeda.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gtzdxqiqyn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtrlftqicb.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gtdlfarqnv.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtvhggrgzt.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gtwhnjfdvu.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtkcijoucj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gtfprofhbv.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtbxcdzxkb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoaankwx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtqskrqbuy.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtokkisdnn.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gtwoucbife.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gtpjrrcsde.html


<!-- 参考信息 -->