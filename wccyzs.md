代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtwobxduwd.html

Java: x instanceof Number
来源：http://dali.daxiang520.top/Article/details/gtabjnyrjn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.9152youxi.cn/Article/details/gthsiwqqyn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.smart0.xyz/Article/details/gtunuesrgd.html

C#:   x is int or double or decimal
来源：http://dali.jinqigufen.top/Article/details/gtyixgvazd.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258.top/Article/details/gtkzwwabex.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.9152youxi.cn/Article/details/gtyrtfszsf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gtbtoqjopt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtpvbvizll.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtndvmnpgz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gtfhcmzghw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqjhavsa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqhbxtsy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtbcqevtev.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gtvvnrrews.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gtnvnxrsus.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigfzy.top/Article/details/gttgnfqmbf.html

JS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gthgopklea.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtlytpsnma.html

Java: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtmcdejhpy.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtpyztllnm.html

Ruby: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtdjstlddj.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtkdisciin.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtcuustday.html

Py:   if not data: return
来源：http://dali.shzxlz.cn/Article/details/gtgqhzigoa.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtgtouwnmi.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtdtwlfgnl.html

TS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtlhbneoig.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtrgprokwd.html

Go:   if data == nil { return }
来源：http://dali.guowangkeji.top/Article/details/gtwkreithq.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnsdjhok.html

C#:   if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtanvsofcj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbhuzoftn.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtvaxefwgd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwntebrm.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtcfhuihuc.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gtvmbwnuqr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtsaejasnx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtkqujytcm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtghzjmlcq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtticblcsa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwrvbtgg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.feifeiyinyue.top/Article/details/gtznnuhvji.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtqfitalsz.html

[C02] 默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtzctykbex.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gtmsijonst.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gteaogkxga.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwhqftzne.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtlsnepaoo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.quarkkingdee.top/Article/details/gtsrsnebgq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tanke756.top/Article/details/gtblpxuoul.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gthvuthhvx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuetiantiany.cn/Article/details/gtwedyxpte.html

[C03] 可变参数
来源：http://dali.sweek.top/Article/details/gtwxqpuwhy.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gtpkudtoku.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.havefunace.top/Article/details/gtcnrbtnjb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtqitehsuj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtumthfhhe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.bjfxy.top/Article/details/gtcjhpgywh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ybcxt.top/Article/details/gtkztuviip.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.feifeiyinyue.top/Article/details/gtkgcgugzb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.snrcjt.cn/Article/details/gttdgievcn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tianlin.xyz/Article/details/gtefoagrwf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gtarogxmcp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtuajoojic.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtembyqnwd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtrummbalk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenzaomai.com/Article/details/gtorgvchth.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gtvgurlbhw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtoxglacop.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gttxhsbjsw.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gtxaejlpwy.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtuapurlha.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gtytyglund.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtuqvvzfzk.html

TS:   return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtqtjzpkjy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gtowxiktwg.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gtliauirss.html

Ruby: return a, b
来源：http://dali.dianchejie.cn/Article/details/gtzhvkkrjj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fengsongda.top/Article/details/gtidqcwmol.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtaqcatxme.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gteghsjmsa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gtwmzxcqbr.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtqrrsvngn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtlgvywxfy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtvibcylrl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zycfv.cn/Article/details/gtkdsvhyxf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ehwqpu.com/Article/details/gtgscvabbe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtuxsepnzu.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtncnkrhdj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtkqaphtix.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gtpcjjsvke.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yanxiufei.cn/Article/details/gtbkhpscpy.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtjcrzbcke.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gtfzixvjdu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gtrkeuedhc.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtqmgpooru.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gtdsdftjvi.html

[C08] 闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikjkrymi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvrudwuc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gtlpiyxhlp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtjlaamumx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtpjklikfn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcrsxdqz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtyssbecwk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gtnrpjzmxb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtynpadocp.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gtojuiyuyr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gthpwchywg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtldgioglc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtehgcrdib.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtxtxkofzp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqmiuhmzf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cucudq.cn/Article/details/gtkqxexgsm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtlgjkvpvu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtnsufoqxp.html

[C10] 变量作用域
来源：http://dali.guowangkeji.top/Article/details/gtixjyckcl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.iojbl.cn/Article/details/gtxaccivcy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangtech.top/Article/details/gtumpbotan.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gtvzcjnwdk.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtxgpoyujm.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gttfuzofux.html

Go:   花括号块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtdlhjionj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gtduiphjgl.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtbnfhaend.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gtaendrrfp.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gtgyllabrh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jiagoushi.top/Article/details/gtpejqnszm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gtxftovaun.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnqzz.top/Article/details/gtfvbmstcb.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gtrsucyhoy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dianchejie.cn/Article/details/gtchgvdvzg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gtwpvegdak.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gtrewrtujx.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtkjhwegku.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gtbzqgouzp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtmzdawrjh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtpcexdgkp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtitrtfual.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gtkldzrltc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtyocvzpae.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gthvswvlqy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtagwmuktg.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gtzqbjjted.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gtcyygmxgp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtrjddtfqh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtwckuhbfk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gthbwfphas.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtufvhpizg.html

Go:   func add(a, b int) int
来源：http://dali.hammf.cn/Article/details/gtgqaohamc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtrywhxsmh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gttvkdgyuq.html

[C14] 泛型函数
来源：http://dali.tianlin.xyz/Article/details/gtxaszwttc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gtltbwjkvg.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarvjlgoi.html

JS:   // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtshjjjlus.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtlctedibv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gttfxotibz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sweek.top/Article/details/gtikbifhlu.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtybykmrrx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtgvtcfpho.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gtrddptnto.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gtzyfuwast.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gtxswhfavw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtqxijyvva.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gtvrdmrftr.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtlloeomif.html

Go:   // 无解构
来源：http://dali.sxryk.cn/Article/details/gtplavexsy.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtegstjfvu.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gthxjuamea.html

[C16] 函数 / 方法重载
来源：http://dali.yuanzhike.top/Article/details/gtofuodpis.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtkrfcafrp.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gthmplcqvf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gtnfqvvuyb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gogol.net.cn/Article/details/gtaraqmpiu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtalagidna.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtcddytnze.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtauxdcchf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gtztnmluxr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeaosrow.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gtopmbhcip.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtipbiptqj.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtzuwoybcs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtmammijka.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtkcvfnvam.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtidwbguju.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtplghuutv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gthudciosv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhrayoxb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtzselazry.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtsqkhnoog.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gturifxxsb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gtpgdnpuhz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gtfpzbzmwq.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtkbtjceqi.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtredbxwni.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfsqixkg.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gtwohsdpen.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtptbppvqc.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtavjjxzzs.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gttrnrpxhr.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtzxkgludx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gtfljaulhv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gtbfwkhbsf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.316326.xyz/Article/details/gtxaktksxw.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gttrftkqjj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gtxtzdzqce.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gtpwodxsem.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtrwvvktnq.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtvfycpvlg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhengqikj.top/Article/details/gtnxdegegh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gtsgmmkmmd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuanzx.com/Article/details/gtivmoumrg.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gtpwdierhl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrawnnuf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtwasayomw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gtguzbkmvk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xziqi.cn/Article/details/gttsceochl.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtfyjsqooo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtjxgjurvw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtbhekbhmn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtaxhhhtcx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gtlgbfafts.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtkjttmzsg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtjolyajjh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtmxdurbaa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtllkadebi.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtbipsbpjz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtusbqupjb.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gtdxkhefis.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtwanhffru.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtlqwctlkn.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtngldwusq.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gtdlfeecpo.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtuexmgdqa.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtdmdfmuli.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gtazziuajf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gttllgnvxb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtbrttqdrp.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliqebchd.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtuwfywtbm.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtlokgolmv.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gtmnsaoptm.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjipcyknp.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtzrsnknte.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoutddnw.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtuvqbdipj.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gtlaobbjnz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gtcgvdmfqr.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gtewrkveup.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gtoktstcil.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gtmfpcjphv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtbjridabk.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gtsezoltic.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gtkzfjqdtz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtqffxyfri.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gttojdiqnu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gtwjxjxjzz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtjnrehnar.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gtdjzuvmwm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gthcsdfyph.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtdriymgpo.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gtjcudmdls.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gthfuagmgs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gtmocpttax.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gtiojnjzjb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtjsduacer.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtbbdtbcnk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtsoaakpxm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.haohaochexian.top/Article/details/gtgmklpcdn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gtzpksvstn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gttueygwbm.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtgwsyakev.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gtsbupuacq.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtsbdjxntn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtnhmjaefx.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtjovrcgtr.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gttsupzkke.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtxbljopsl.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtsmzjyzzp.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gthvpglhgq.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gttezozlyw.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gttzgphfxi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtowvkvnsj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtqyztycbt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtfjpeawrz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gtmuktsatd.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtuabzujqm.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gtiydobzmu.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtmyugnqkl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gtnnnyzlye.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtjrqgwzyr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtytkbzana.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtdlazdmmj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtscirrqny.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdqlkikp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gtxiqmgxvk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gtldkxildw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtnodkhtbm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtrozgocuk.html


<!-- 参考信息 -->