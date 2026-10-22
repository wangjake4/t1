代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkaemvkjo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnqzz.top/Article/details/gtcwkjhfbs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvxmsyhm.html

[B12] 跳出多层循环
来源：http://dali.cdnleiting.top/Article/details/gtegizyyum.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xinyue.icu/Article/details/gtqgmpwloj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtspanildg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtvqcwbndx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtdcohhvfu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtzbyccioi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gaohongyu789.top/Article/details/gtqzcbvrta.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tanke756.top/Article/details/gtqttkxebb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gtsbwgqyfq.html

[B13] 判断是否为数字
来源：http://dali.zhoulong.xyz/Article/details/gthxdnmybp.html

Py:   isinstance(x, (int, float))
来源：http://dali.tian-w.cn/Article/details/gtyttkllnk.html

PHP:  is_numeric($x)
来源：http://dali.zycfv.cn/Article/details/gtcdsxjady.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gtosbwuwyz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtczgbfmvj.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gtwrpxsnyq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuesjqwr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.havefunace.top/Article/details/gttswqjoyd.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gtyyozzgno.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258888.top/Article/details/gtjgyxmgkt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hammf.cn/Article/details/gtigqysyob.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.mhx1999.top/Article/details/gtyclzjqzm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtmdjrimyu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gteveeyewr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtqzadrupf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gtfgbhlsak.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gtnzpfpjsm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtigtvenws.html

[B15] 布尔运算与取反
来源：http://dali.hysaishi.cn/Article/details/gtuizgatyg.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gtdyyamdbf.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gtafakmwax.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtdumhcjix.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtuezvvanr.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtjwkyixna.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtskrfrwch.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtdhzvqvgc.html

C#:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtmjlkiuai.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtzakwpvwe.html

Py:   if not data: return
来源：http://dali.shangyingyoupin.top/Article/details/gtzmfkfhpn.html

PHP:  if (!$data) { return; }
来源：http://dali.gzhubu.top/Article/details/gtqhwfmznk.html

JS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gtcrpmpqmk.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtgdltmlgi.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtjibrcbgs.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gtxhxmazjo.html

Ruby: return if data.nil?
来源：http://dali.xziqi.cn/Article/details/gtqubviryd.html

C#:   if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtmgvmaphs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtndfjaqkv.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtmpowmtri.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtirafjbeq.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gthipokzvp.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gtrzezevvh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtoycpkskd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtyzrmgcou.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtkwmcieeg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwqmhbkq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gtwpelobxa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gttibscdiq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtjjfrsrvz.html

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gtfksfvnzk.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtglljrdug.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtjfxoyiwy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivyqtpyb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtmizzveja.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gtiietsswe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gtoaeyyoef.html

Ruby: def greet(name = "World") = name
来源：http://dali.ybcxt.top/Article/details/gtlmbmbqye.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gtiivutdbp.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gtsvmhjcqh.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtgpuqdvzp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhengqikj.top/Article/details/gtzbucodwc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtszytrubp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gthatfeouc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gtponunkfq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.feifeiyinyue.top/Article/details/gtfaksjonj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtwrmumsqd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.birdmap.top/Article/details/gtmpljltmh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gtyhkizxnz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtdzbnypug.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gticmoueon.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtesoysmhw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gtmrzcklns.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtdeukgakf.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenlongwang.top/Article/details/gtnddrmjqr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtztmkojdu.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gttxovpqbh.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtamhzidho.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gtnvfmaopu.html

PHP:  return [$a, $b];
来源：http://dali.wangdashe.top/Article/details/gtarztqtae.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtobgihywb.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtvqamuyhj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gthyzlnrkx.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gthwrzgruk.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gtivmipiwn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtphcphwtf.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtsfommxzw.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gtbcxtxyda.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gttzzodbvh.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtxeoecpaw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.havefunace.top/Article/details/gtujfodudm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtjmavlmko.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gzhubu.top/Article/details/gtefnytger.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gtwpbvptuk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtvemahkau.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gtxwmcquxn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gtkuqpszyp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtrszqnqvp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ppjwa.cn/Article/details/gtybgrgjkc.html

TS:   arr.map(String)
来源：http://dali.sweek.top/Article/details/gtftwxgcud.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gtnvaloaof.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sweek.top/Article/details/gtipuzcddz.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnxiangtu.top/Article/details/gtkgeduhcj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.bjfxy.top/Article/details/gtrwnzpqve.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gthyjbpvhq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigfzy.top/Article/details/gtdoqissen.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtejkdnkmj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gttaevpvqr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtdnxcveic.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gtiqxzarbs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtymwecqdx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jlsjyb.cn/Article/details/gtcmbpgmej.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtxpvzgvry.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gtkutaguvk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtsnxgwiom.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gttsskdnbk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtqbzopuyi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtjestxoxx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtsixuvetk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gtgjxpuhxo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtowliyhtp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtfowcolwk.html

[C10] 变量作用域
来源：http://dali.tianlin.xyz/Article/details/gtyihvbfms.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahwkzjvd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gtcddbgdlp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gtaojypbuo.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwyqnmoi.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtwhaidhxo.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtlglyslma.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gthlakyroo.html

C#:   块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtizszzhfl.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gttptnxzhe.html

Py:   from module import func
来源：http://dali.iojbl.cn/Article/details/gtissnykgi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihswdqqv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gtgfpnbfen.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258888.top/Article/details/gtagmegwdk.html

Java: import java.util.List;
来源：http://dali.pengpengdd.cyou/Article/details/gtadssyxmt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jyoumei.cn/Article/details/gtlilvzshk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gthbykdojb.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtrxaupqno.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gtemefgvdt.html

Py:   (lambda: print("run"))()
来源：http://dali.snrcjt.cn/Article/details/gtxtanorra.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gtdntygelu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtrtbyjhfc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtpawmvcrq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gtghmtwcne.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtqlyttqfs.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gthlruckeb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.9152youxi.cn/Article/details/gtgcbcarxf.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtfsrfpspz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtlmoflosi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gthhawwjki.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gtnledbstn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtmwpqzitj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtyjfluwgr.html

Go:   func add(a, b int) int
来源：http://dali.c1oappe.top/Article/details/gtsyeadxvi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gtwenypaoz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gtzkuvdyly.html

[C14] 泛型函数
来源：http://dali.wangdashe.top/Article/details/gtdumcnptx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtleronxvg.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtpwkzafgo.html

JS:   // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtbffnjfhw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gtkhnbvykj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gtooemsrng.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqcawksn.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gtmjdpwxii.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gtwfosqmvu.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gtpysvpgyd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gtmbythdtc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtptlmlxzf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtzgkvzjey.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gtfulcrbqy.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtfxmxflyu.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtjdfbzgkl.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gtogsemdgm.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtpsssiahw.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtlhqflxnr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gtrgnrifpo.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gtjzryhyko.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guowangkeji.top/Article/details/gtjntyrljb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtjyvmhivx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtsmiplksg.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gtecumdcnf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gtqytytmuf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtuksqrmwv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtokulligt.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gtcjuowhiu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdjtzfmvd.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gteljfpoch.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtmjtpobsb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gtsimnpzwn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gtuqiloesl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gtvxxhiuns.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgfzy.top/Article/details/gtimgnpcbm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gtqzkzjtwb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gtvsawslug.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gteyxyyfox.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gtxfzvxktd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gtzdnimwct.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtbjmmmeob.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtmcktacvi.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtsjsbrlfi.html

Java: list.add(4);
来源：http://dali.9152youxi.cn/Article/details/gtkrnavwog.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gtnkvhkfsd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gtmvtowkxq.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gtzugidmfq.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gtcrrtrgpk.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtjdffkarl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gtggphicbj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtyedhpbax.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtgcrwgjpw.html

Java: list.add(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gthfhnsexj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gtdczjziev.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gtuwtvrmgk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzfnefnu.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gtmpclheoh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtxknavijb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gtsvosvypd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gtyhsitbmy.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gtvcctnviz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ppjwa.cn/Article/details/gtapqnwrhm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gtcyqvpshn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzppfqrfa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cqqwz.cn/Article/details/gtrcixjeym.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gthwyklrpd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtuuhmxjsy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtrznflmee.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtlfxfxfst.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gtcuaejksc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gtgzbgiaok.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtjfyjfscu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtyeruyyyp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtmsykvzjg.html

[D06] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtuzbqvolh.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtpgjbvdud.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtqcowactj.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtjualctgr.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtzzmimfxt.html

Java: list.size();
来源：http://dali.c1oappe.top/Article/details/gtuiaevmbc.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtaobuuzwt.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtjbdcqxzf.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtcmuswmdk.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtovblalzg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gtzliwvrbm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtkxclgnwb.html

JS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtgxewzgab.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmdikghz.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gtynhcvjuj.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gtgafllwtw.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtyjfwncvv.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gtlndmanmq.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gtdlblizda.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gttucbntak.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gtcrmsufco.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtuzesogrk.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gtjbbovejc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenlongwang.top/Article/details/gtvqibfebj.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtarikwywx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtqoczwuvd.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtnoiclqch.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gteqehaiet.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtscusksto.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gtrfmomznu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtkkvaettj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gtgyqnmezm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtkifwckpx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtlhkfpluf.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtydcqzeeu.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtekhtddve.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.redwolf501.top/Article/details/gtxzhhtxth.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.bjfxy.top/Article/details/gtuwiucfpn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtiqiqijmc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmabhhxre.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtpijdlooy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gtirvxlbxb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gtgsunejpm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gtnqszxpha.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gtccnwxbku.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gtavfoonju.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtgkzadwst.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gtraverypv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.0kj1m.cn/Article/details/gtkrpntpsc.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gtpjzyyspk.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gtrajkcdjz.html

Go:   slices.Reverse(arr)
来源：http://dali.cheryme.top/Article/details/gtfuycaqvo.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtnoepsgdu.html

C#:   list.Reverse();
来源：http://dali.zhixingplan.top/Article/details/gtfvbdpvyo.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gtfddiyink.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gtklrbwfku.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gthelqgxki.html


<!-- 参考信息 -->