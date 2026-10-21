代发 wailian999

[C02] 默认参数
来源：http://dali.zhixingplan.top/Article/details/gtobxdflkg.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gtcsywqjyj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gtnsivredw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gttvgetaaw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtmohgcaon.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gtmbeonxuh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtednvvttr.html

Ruby: def greet(name = "World") = name
来源：http://dali.sufxvd.cn/Article/details/gtfpboqjjb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gtwpjcvzvv.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gtvjwubzcn.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigufen.top/Article/details/gtxedorenr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cashguo.top/Article/details/gtrzwynesq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtbhibixca.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtrcmknmfd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.meibo888.top/Article/details/gtylbgngbe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgfzy.top/Article/details/gtwndhpbfg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fzhhl.top/Article/details/gtkriczdfa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dianchejie.cn/Article/details/gtmmshxfsu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gthijsriky.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gtuqsaeukb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dashuyun.cn/Article/details/gtycnbtyvx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtbiohxgxx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yangfankeji.com/Article/details/gthklctdax.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.9152youxi.cn/Article/details/gtxgikrzjf.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvlclpwa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtxclmiumn.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtewwftylz.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gthptmetfh.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtxkwphpje.html

PHP:  return [$a, $b];
来源：http://dali.pengpengdd.cyou/Article/details/gtqpfpfmgs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtvwsaxzel.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtlsxrxbdy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gtgtgrykzx.html

Go:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtxnhortkb.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gtqmhnsaer.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.9152youxi.cn/Article/details/gtszqkwyax.html

[C06] 匿名函数 / lambda
来源：http://dali.cashguo.top/Article/details/gtugrdhgvy.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gtdicjtrgi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtiydaqqtp.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtkxfquere.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtdjcetjts.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtjwotvozy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gtydybbomi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gtcepyidvt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtreqpcmuw.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtddgkrrkr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hammf.cn/Article/details/gttkppmzit.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtydbpqlgh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gtfyruabys.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gtikgvmbst.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hfpthk.cn/Article/details/gtztwnfruk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gthhtcvvxr.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxinkj.top/Article/details/gtkznylooz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.smart0.xyz/Article/details/gtwisjlxos.html

[C08] 闭包
来源：http://dali.gogol.net.cn/Article/details/gtinjgbfeb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gtjepqpvun.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqlzlgfpf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtehilickn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtpkxazexe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gtfuvmdlhv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gtruikmopk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gtvtqmgdni.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtbxybucgd.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gtuehgeqav.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtsxmwsvlh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrxsphgyj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtkjtqibyk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtxezxizbv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gtohbmmety.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gtwugthrcw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtdnvrcatw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sxryk.cn/Article/details/gtbfswsfnt.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gtcqrjkqys.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgfzy.top/Article/details/gttduhzprg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskwxkdov.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gtnhhdimqz.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvfjhksc.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtnfkobutm.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtmqnfuoef.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gtkrouiozy.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtqkcbxjlk.html

[C11] 模块导入与导出
来源：http://dali.0kj1m.cn/Article/details/gtyadtvvbj.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gtwgxakvzd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gtjfgroauo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtzpmyffci.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gtojwgwszd.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gttuglfuhb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gtgjrvllvz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gtynvntsxk.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gtgboninzr.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gtkvzndopy.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gtefwmfzdc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gthwauifwu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtzhczdhqa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtyxxzrxbe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gtaeuuonmf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258.top/Article/details/gttcqtriyo.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gtutkgkvpi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtrlcgyiic.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gtljmnrubr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gtmwmjhonw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtjhhbeqlk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gtfwxjgqzr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtnlimlsyq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtmssnbsze.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gtlyegooic.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gtjtnaaenj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenlongwang.top/Article/details/gtexpthqpa.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gtbyuuyotc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.andypj.xyz/Article/details/gtfkqyjerd.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtycwaqppf.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtutxjtzfy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tanke756.top/Article/details/gttuapyfag.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gtzxhaxisb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gtofyvnczq.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtuzigwvuk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtpqjgtobx.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gtfohfycnc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtbknmypqf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gtgelrobav.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gthemgvnov.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtxbiuxxzg.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gteyvvwmis.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gtvczvnvhi.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtcuruvcfd.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gtyndahont.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtczuwfltu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gtbuoomujw.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gttjwbowmr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gtjbrvtbpo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gtxeosyqrm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gtkkndgbpw.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gtdngrouzy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yangfankeji.com/Article/details/gtqgxqzxlj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtrukahgly.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtryaucptq.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdtremun.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqrdxlrbs.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtwbclslob.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gthyotwwuf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtmglbqgwl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dianchejie.cn/Article/details/gtyatrgdae.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gtbjtnzrkp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gtbpshhzbm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gtzszlgtym.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwgmodbf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gtyudiwxfp.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gtfcwptsth.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gtcwkolfwg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtoofdiudx.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtruxpogvp.html

TS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gteptlqpwl.html

Java: list.add(4);
来源：http://dali.sysykeji.top/Article/details/gtogwegdnp.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyervhgm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.svipenyu.cn/Article/details/gtxbclzmgy.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gttnzwrlpg.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtfpixarcf.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gtwctmxumu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtejzyckfz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gtfawrqjgh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gthhtvlttm.html

Java: list.add(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdylulsm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gthumaxkem.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gtprznsbfx.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtlrtqqcgc.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtcsfxfvkl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gtgcaornbe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gtsccpkuzr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.quarkkingdee.top/Article/details/gtovunearb.html

TS:   arr.splice(0, 1);
来源：http://dali.cdnleiting.top/Article/details/gtnnyfdpuw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gtaseeivqo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtfrugyixb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gtybgtvgxp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gtaypgqokz.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtcxpqlbru.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtefbeuiqd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtguzgbhdw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtxewlpqci.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gthbsvbmai.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daria6918.cn/Article/details/gtftctqbnw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtcplqalxb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtbmsuaknw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtjbaimewu.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gthvrahujq.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtjdkbzjlo.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtrduxmdrg.html

JS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtaelutvjw.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtvlrzzzof.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gtntooqbbq.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtxhdtqssg.html

Ruby: arr.length; arr.size
来源：http://dali.yonumen.top/Article/details/gtwglqveme.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gteafqlkon.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gtlifcvtdl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gtgcsjflls.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtshhrmzqf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gteuzxbjlt.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtoxsyflrl.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtznxqznqw.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gtfkezegiy.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakjxjash.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gtyfswvdoj.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gtxgcjcawk.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gtlbgycigt.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtmxuyburc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtiqjzaweq.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtfowjapky.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtqxybodbo.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gtmwojtcgv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.andypj.xyz/Article/details/gtgiwzvnwi.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtrdileqyn.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gtokckperq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtfrlnophh.html

PHP:  sort($arr);
来源：http://dali.guannengcc.top/Article/details/gtzlbmapiy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gogol.net.cn/Article/details/gtizflydxt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gtpvkelpcz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gtqpknklyo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gteqyrjert.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtkkculjsw.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gthjjudegp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmfgohiz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gttqmtmghx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gtsfynukmz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtpcghouzq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtvrbpuysp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gthltpiwxk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gttxocqdme.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gtsvcxfdtp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsgmxagi.html

[D11] 反转数组
来源：http://dali.mhx1999.top/Article/details/gttzlmazwx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtydeehuhx.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtiqtcrgjh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqofigrn.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtcnevjazi.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gthzrwqaiq.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gtsxxhiyye.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gttjlwukso.html

C#:   list.Reverse();
来源：http://dali.daxiang520.top/Article/details/gtwyrqftps.html

[D12] 查找元素下标
来源：http://dali.316326.xyz/Article/details/gtdvuobhnd.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gtqyztbumw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtnzvnrvsn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtmmxlwnjg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtrzvdxkpi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gtaxquocqr.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gthqluonsn.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gttkwhaplt.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gtleblttfk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gtzffouizr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gtqvpqbmle.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.havefunace.top/Article/details/gtyfyrpbuh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtzhyiwpzj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtbndbpihf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gtrklucmnt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gtztkzdlao.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gtrrzjstyj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtiwxhyjxn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gtwkerkoas.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gtwyowhniu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gthxjqtsdp.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtcegaulbj.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtztpohwwu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gtyxlqgvbc.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtedpioete.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gthsmaeyhp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtxehswxge.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtmwndqtqm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtpfdfbnjs.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gtzstdjzkr.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtpnqoebyp.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtlzmfpduk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzsjmmvc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gtlbtxowtp.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gtcsnzlfic.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtoazsrlfb.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtowabifvk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtylxaijyn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xziqi.cn/Article/details/gtzijhyjyr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtnytdsovq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtykjgdsgq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gtztjohacx.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtarannaji.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtlwykflci.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gtvtrruybc.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gtaayvkjqk.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtkuwfjguv.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtcpuyuczu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gtldnjnkkt.html

TS:   Math.max(...arr);
来源：http://dali.aizwys.cn/Article/details/gtrihswlwm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtubdkijix.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gthrozqamv.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gtdccygxfh.html

C#:   list.Max();  list.Min()
来源：http://dali.cashguo.top/Article/details/gtklrkcccv.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gtimdmtszu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gtqadepvsu.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtcwqdihmk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gtqpzpkxxa.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpharkaip.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gthqklgmvc.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtqayirjbn.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gtleevtjqy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtqjffnspt.html


<!-- 参考信息 -->