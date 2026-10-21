代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tian-w.cn/Article/details/gtulnkqupa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtbnhftsmq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gogol.net.cn/Article/details/gtbwzkyfsf.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtbnpmmvkl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jyoumei.cn/Article/details/gtqinolytq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhoulong.xyz/Article/details/gtimkeriuc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtbwgibyhv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtkpseyjyh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtiycgarkg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cheryme.top/Article/details/gtdnzvxglr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shuidangran.top/Article/details/gtuuxurrqj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gthkddtrwl.html

[B13] 判断是否为数字
来源：http://dali.yuxming.cn/Article/details/gttlrfqmki.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gtwzcouktz.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxrmgwhs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtfkmagzra.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtuskzxboa.html

Java: x instanceof Number
来源：http://dali.xuanzx.com/Article/details/gtdhntgapo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258888.top/Article/details/gtmnrxorur.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gtdcjiwmkp.html

C#:   x is int or double or decimal
来源：http://dali.kuanghao11.cn/Article/details/gtfiydsfkq.html

[B14] 判断值是否在集合内
来源：http://dali.mhx1999.top/Article/details/gtttymkktr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.havefunace.top/Article/details/gtckibdqib.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ppjwa.cn/Article/details/gtnevuctgz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtatvlrcjv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtezkuuxkl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtgpniyqgd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxinkj.top/Article/details/gtbkogugho.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtwadovfpq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtnmylhlwx.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gtpswauvok.html

Py:   a and b or not c
来源：http://dali.xuetiantiany.cn/Article/details/gtfhvqamfc.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gtchqllbkb.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtcggxdhyw.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtsjaoeyaz.html

Java: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtmxfsjgno.html

Go:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtwuzuqurn.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtrnyucako.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtnhetjhjw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aibaodan.cn/Article/details/gtyloylvax.html

Py:   if not data: return
来源：http://dali.jinghuilouyu.cn/Article/details/gtilqoiuey.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gtrssqnpdk.html

JS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtsrqrxckg.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtnawqcdsx.html

Java: if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gtbhjwipqa.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gtvzuifybt.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gtulwtnruo.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtbjalxern.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gterknvafc.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gtcdzwnanj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlodfqxmg.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtyuwkphty.html

Py:   def add(a, b): return a + b
来源：http://dali.smart0.xyz/Article/details/gtjlwdumzb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gttrfxzcnc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtgrjyqqih.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsuomwvi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtlywubcbh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gtqpuhgbvt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gtjzipgino.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtvfwpfwnv.html

[C02] 默认参数
来源：http://dali.xziqi.cn/Article/details/gtcbtjnbqy.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gtfoiiydnd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gtsewihrwj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtekscbaig.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtxqnpyxpo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gtrtbvfghw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.316326.xyz/Article/details/gtdhfexdiv.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtmkcimycn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gtzdtpdecs.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gtsrjaxivx.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gteteepchm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gtpyfkxvsp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtldmnocsk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtsdytkflp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtietmccyb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtgotghdup.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gtzbcmukme.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gtcxoekmrl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gttxkseqob.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtcldkjatt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtywwnnyks.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gthxbrzida.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzczkikk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtrgpxexwu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtrendubft.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtuvmfeaef.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtyseerhlz.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gtiarltvhy.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtwjfqztrr.html

PHP:  return [$a, $b];
来源：http://dali.yj20258.top/Article/details/gtplbntmsh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtcaidshyq.html

TS:   return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtmsogfhjn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gtjvjakqyl.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gthfsmclvy.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkplzfnwa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtcylhbgin.html

[C06] 匿名函数 / lambda
来源：http://dali.ppjwa.cn/Article/details/gtbakywlov.html

Py:   square = lambda x: x * x
来源：http://dali.iojbl.cn/Article/details/gtbmadzufm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fengsongda.top/Article/details/gtirnjmwei.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtxxjmxthp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gtvkrzwykv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.birdmap.top/Article/details/gtoyxxgofu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fzhhl.top/Article/details/gtpczmtgsh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sufxvd.cn/Article/details/gtnkedyjsw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtnnptqbpj.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtjydclfvp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtjrhawafb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtuoqtucor.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gtpidbwudd.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gtmbhiwdmz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtumcpldej.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gtbhvzcosz.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxinkj.top/Article/details/gtynkdebbh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gtxtoltuec.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtuloelcgh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigufen.top/Article/details/gtcahqkgjp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtvmfuygdm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtnpdjmbqr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtkzpqbnue.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jiagoushi.top/Article/details/gtfwtzwmbb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gtbforjchc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxtztyca.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtizrohilp.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gtfwnygxlq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtbeacblap.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gttiggsdyv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtgsmluobp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtmhgxycow.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtenqjontt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gthcmkuzaf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbxifuxk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gtkvhzgwhu.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gtdduyfsby.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gttiotutqw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gthugdynos.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gtbeovadha.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtmilqxnnq.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtvijtrdgr.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gtrgqzddfs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.meibo888.top/Article/details/gtexqwxzaf.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubszxmvr.html

[C11] 模块导入与导出
来源：http://dali.hysaishi.cn/Article/details/gtssffrxcf.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtwntuhsid.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.kuanghao11.cn/Article/details/gtmulmboij.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtrcnbjwfc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtnoeflsdf.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gtmjprwrpl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtlsaafwld.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gtzaracejm.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gtwooffkcv.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gtriqopnuz.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gticxmudjc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gtfgdstukq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtvjjolsjz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtdwnotade.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gtrudjdjpw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gtgsaqpbcq.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gtjwpcgrrf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhengqikj.top/Article/details/gtegkxtuxn.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gtrkwragsg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijyrojzc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtlnsdpbua.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gtewimmjbv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtufnhwcth.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gttbvmwhup.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gtmhqasmpk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gtqvqzlflp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtjljimzri.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gtgajppmof.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gtvgjedrhc.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtxmokzbex.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtovfxsgsb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuanzx.com/Article/details/gtgbxgddrv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gttmfuynqc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gtlatebvcp.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gtnfnapwdq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gtpuiolixb.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtweorixxs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gtaedhvcpp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtkzigmmia.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtvdvagpsf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gtjzrvvzoe.html

Java: // 无解构
来源：http://dali.zycfv.cn/Article/details/gttlmeisni.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtxjfnpwns.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gtqqkwwgtw.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gtylpwpkbc.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gtpmizaiss.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ivvv.top/Article/details/gtbllxfaeu.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gtxtakqweo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gtlnlbbdoo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gtfndeslqn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtclknbkxu.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gtipvptzvq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gtvklezqcx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gtmipchzts.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwocfgmg.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtzqanbzef.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtafvslkgf.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtjgcujaro.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtywwauoyq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gtfwvywtuw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtbcgmajsy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gtilbukada.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtndflrmpp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gtywqyuqij.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotbivujk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.smart0.xyz/Article/details/gtatueaeao.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gtdefkgcbc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gtgxhnbite.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gtxbxewqmt.html

JS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtujbndenj.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtzitcviap.html

Java: list.add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtplcybsuu.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gtlpodevuh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gtrqcienxa.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gtwwddncdk.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gttdnbenpw.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtaqpfxjow.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gtdkhsofta.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sysykeji.top/Article/details/gtmjpqwhzv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtesnwvvoc.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteulhytjn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gtvcpfayes.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gtioszkcnh.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflkymmqk.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtjkjaqjxs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xylfe.cn/Article/details/gtxfsynejq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gtgbgzkzgi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gtxiqimszz.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gthjpagvvo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gtdipqlbao.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtbxkynxtl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gtavtuhrrd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gthsoklpah.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gtzfjgjnsd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtpnjdxpdq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtqladkpqh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtesbquykb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gtjzgfnoxy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yangfankeji.com/Article/details/gtagnhyrax.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtotvhlcms.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtecjcztph.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtuxxesddm.html

[D06] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtfgiaazio.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtnbgasafb.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtoqfjvnfa.html

JS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtkjmyfwfz.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtsxvfxcjs.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gtivfwqckj.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gthjvaefgi.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtkguofyqt.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtwmpyngkr.html

[D07] 切片 / 取子数组
来源：http://dali.cashguo.top/Article/details/gtyydhvasr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtfvscomye.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gtepppsqcp.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtksgupudh.html

TS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtljksvmpz.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtubpvgody.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gtqucoajmc.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtrkpkwrcn.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gtpmfvpqwi.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtrpehyeyt.html

Py:   a + b;  a.extend(b)
来源：http://dali.sysykeji.top/Article/details/gtncpzpxnr.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gtzshlbvji.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gtqbgxaore.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtdezlcquj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtjrhozkbq.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtmjnglqfc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gtedibnuua.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtlgyeukvz.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gtvrpdkazg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtcokljudk.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gtbiwyqnal.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sysykeji.top/Article/details/gtuglsbuub.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gthzeqcuug.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtkkbhllgk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtfjpcvwtm.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gthhdyaqji.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtqwiciamy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqdogkot.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gtassnskdn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gttcwmvuju.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtivnypcey.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtevhnpuch.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtkmsfndmx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtamighgjv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gtdvipilun.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gtlpotulrc.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gtecevpnpa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtnhvmwiwo.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gtdfnbrckz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gtujhvnlai.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtbfcnejwp.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gtsoiwrefz.html

Go:   slices.Reverse(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtotbbevgs.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtzgokhgvr.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gtygehpvka.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gtqzzvwweu.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gtxwcqytju.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gtroaswttt.html


<!-- 参考信息 -->