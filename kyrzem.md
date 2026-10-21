代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.yangfankeji.com/Article/details/gtpgsksnii.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtxgerflta.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gtmtbekufo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gtnpelcaot.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jianghu66.top/Article/details/gtuagecevk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gtohkfrqbe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gtubedotcx.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gtcxyjxqvu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangshuangyany.cn/Article/details/gtgfrdyfen.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuanzhike.top/Article/details/gtteveihlq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtawkfmwrr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtwujvmgsw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtrcguafhp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtahalabgy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gtztdkxkiz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gtmfbykrft.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gtrlcogpqt.html

Py:   isinstance(x, (int, float))
来源：http://dali.cheryme.top/Article/details/gtjwjxbwfw.html

PHP:  is_numeric($x)
来源：http://dali.snrcjt.cn/Article/details/gtcqzojgvu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gtywpbmkby.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtwcncxxpj.html

Java: x instanceof Number
来源：http://dali.guannengcc.top/Article/details/gtvatynnok.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhongyouzk.top/Article/details/gtgydgmanb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgufenzy.top/Article/details/gtyixmjyfv.html

C#:   x is int or double or decimal
来源：http://dali.ybcxt.top/Article/details/gtefmslzur.html

[B14] 判断值是否在集合内
来源：http://dali.zhengqikj.top/Article/details/gtqzdzrhbo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gtdcmtayqt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sweek.top/Article/details/gtcknfwpqo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtopfvuicp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtszdqccee.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtdcginclr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnybzwimi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sweek.top/Article/details/gtawgupmuw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtjddduwjb.html

[B15] 布尔运算与取反
来源：http://dali.hywenlv.cn/Article/details/gteehzpomo.html

Py:   a and b or not c
来源：http://dali.9152youxi.cn/Article/details/gtkmrwzbqx.html

PHP:  $a && $b || !$c
来源：http://dali.xuanzx.com/Article/details/gtgixmodil.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtbhdtmpuh.html

TS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtlnjqrirc.html

Java: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtkzypzvds.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtmpudcllg.html

Ruby: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtgxctjlbd.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtgvukgwyi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gtyggyszdn.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gtgdhnqkus.html

PHP:  if (!$data) { return; }
来源：http://dali.havefunace.top/Article/details/gtumxrtwra.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtfckzmiji.html

TS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gthzkfuhev.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtxjmxccmd.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gtlutjbmsk.html

Ruby: return if data.nil?
来源：http://dali.ybcxt.top/Article/details/gtidhpxksp.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtsjcgwsxe.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrdnfgcre.html

C. 函数与作用域
来源：http://dali.guannengcc.top/Article/details/gtdnmdbxat.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfflfscyh.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtogveorpu.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtdqodzcoe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtbicakwqx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtrlrvtucq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtqpzpwahx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtfndlpvql.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gtfspbaclp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gtwwqfldwp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtfgvljwyo.html

[C02] 默认参数
来源：http://dali.pycfn.com/Article/details/gtoeoymfpv.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtlosuzxzo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhengqikj.top/Article/details/gtllhikqwi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gttzfsunek.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtigudisqf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gtvjroypci.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtcfqqfzry.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gtcrjqufby.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gtarqxmjku.html

[C03] 可变参数
来源：http://dali.dianchejie.cn/Article/details/gtpskubslc.html

Py:   def total(*args): return sum(args)
来源：http://dali.9152youxi.cn/Article/details/gtabxssqyh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gtgjgmedka.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtybzdeguk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gtqtplujhi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtwadponjh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.snrcjt.cn/Article/details/gtggreecql.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtjmcjguzb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hammf.cn/Article/details/gtnfdzozbd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gtvagcqjzf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gticuovfxw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtawprjsro.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaeumxqd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtpodxncof.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sysykeji.top/Article/details/gtqgooivoy.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gtjbcbgzxt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtivwtbzvf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtakweppru.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gtqjqkzqgx.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtdfosuafy.html

PHP:  return [$a, $b];
来源：http://dali.hywenlv.cn/Article/details/gttzwbnhwa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtabtqdwdv.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvjnbtuz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gtyvrbkgbe.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtizqnpkgz.html

Ruby: return a, b
来源：http://dali.mhx1999.top/Article/details/gtziojhqrx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gtgjdkjkgk.html

[C06] 匿名函数 / lambda
来源：http://dali.hywenlv.cn/Article/details/gtzoremsmm.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gtvlnawovp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gtqbgaerrd.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtzqomutxy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtcspfzjbn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gtsatuyasb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gtjianhrud.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gtzrdtzwfo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtxvkuchmj.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gtybvoiwid.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxinkj.top/Article/details/gtgksstofi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.havefunace.top/Article/details/gtdarvjhwr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gtnqumuine.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gttdacauej.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtewhwmfxv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fzhhl.top/Article/details/gtydvlbldq.html

Ruby: arr.map(&:upcase)
来源：http://dali.jlsjyb.cn/Article/details/gtexntchtf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtvvecudlz.html

[C08] 闭包
来源：http://dali.xuetiantiany.cn/Article/details/gtqqfjrjvr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gtywzpttkm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xylfe.cn/Article/details/gtuqpupisk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtkshyveqs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtagrktmgc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhixingplan.top/Article/details/gtjetegmvw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtorjwznil.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gtuixmlawo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwordvhgp.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gtxggkypli.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtvronujcg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gttdsgiimz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtzhxmsdfb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtiehzcuyu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtjirmgjzl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gaohongyu789.top/Article/details/gtlxavopwf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtlttrdnxl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tian-w.cn/Article/details/gtkjwwqnuf.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gtbmxxltsg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gtfnylbrsx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gthqozswii.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gtoxqwxcpu.html

TS:   同 JS
来源：http://dali.ivvv.top/Article/details/gtfopggxbu.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtokpjmrth.html

Go:   花括号块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtqdimsjct.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gzhubu.top/Article/details/gtygucwuhn.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gtrdtjtlna.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtztpizgww.html

Py:   from module import func
来源：http://dali.yvedp.cn/Article/details/gtsklaahgu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.meibo888.top/Article/details/gtdhpuycbz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gttlcomrvo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjuuagiq.html

Java: import java.util.List;
来源：http://dali.yj20258888.top/Article/details/gtidvctncw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cashguo.top/Article/details/gtvogzvzrq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gtfwddcwqn.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gttvhbzgug.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gttraoglss.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtxlrbpsjk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtrovguvhd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtvtrekpck.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gttgtnnuwd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aizwys.cn/Article/details/gteltplsvr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sysykeji.top/Article/details/gtnrzmqopa.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gtixbehpyo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsktlstxy.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtrsaycuzw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtpbgoboxl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtxumcqtcy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gtnqgcfvdq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gttjryvxgk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtsbqyefpj.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gtlvazbuzj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gtrvedeknt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcmsgquh.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjtuaojc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gtsjrfbwzu.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtqczkiypl.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtecoxhodv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gtcpajvwjv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gtbixzsjer.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtrwgrnl.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gthuacfkgi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gtlgndrinm.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtbdrvipff.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gthohaikfm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtveqibwfo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtufdhwunq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtmahflaqm.html

Java: // 无解构
来源：http://dali.yonumen.top/Article/details/gtotfebjtz.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtuvfbrlkz.html

Ruby: a, b = pair
来源：http://dali.kuanghao11.cn/Article/details/gtnkgbcnja.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtmqdlxgqj.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gtgygsgovm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtlkoekawj.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtxhozlbye.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gtpnlbqfub.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gteceeywhs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsznayiej.html

Go:   // 无重载：用不同函数名
来源：http://dali.jyoumei.cn/Article/details/gtrpajbajy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtpaskhdwg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gtprketixn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthrcgmwqi.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gtfiawzoto.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdjxuwbzq.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixyfquop.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gthxlhumzh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtwpwgixxt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtoxakywbj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gtiasmkgcx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtvphzawze.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gtmasawtad.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gtwtjsuyaa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gtzovkellf.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtsdkgoebl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gtjudemtwp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gtzhsndsby.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtzyaitaur.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtridzytfm.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gtbhxsdpsd.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtuqnqwhyl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtccnwxlid.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gttmaoqvam.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gtpmlzthze.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtzhpppkvb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gtojzyhfuq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gtklfozdod.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gtyburidcm.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtoxfkumju.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtvhxnfwop.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtykpfedgt.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtjclrgpvt.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gtthzrqdqm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gtgmwgagcm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gtphycvbip.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cucudq.cn/Article/details/gtmyrgzghm.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gtmglkubem.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gtvwbsmwwr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuxming.cn/Article/details/gtatfouofi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gtuiqikuyw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gtnmoajyeo.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfbuucgm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gttpoikzls.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtszhquhgk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtjidfdrzk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtvahmnuol.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.feifeiyinyue.top/Article/details/gtcuplpdkt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtekywtuwd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtovfwjruo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtjdfjujxm.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtdguobldp.html

Py:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtwlojqmco.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gtikqsgplh.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtdqftzbqm.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtsbcbgdmc.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtgkeoyhta.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtovrhzwhc.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gtjsmmzseb.html

C#:   list.Count;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmlrkkze.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtvehxjdfy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gtnvbrvqfu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gtmchabpvl.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdkkmhzk.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtopuexfbg.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtdhiakjck.html

Go:   arr[1:4]
来源：http://dali.xziqi.cn/Article/details/gtrxwfxuwu.html

Ruby: arr[1, 3]
来源：http://dali.hnqzz.top/Article/details/gtldietbzp.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtwqfvxrog.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gtewskgowp.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gtopgizfim.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gtxtaanoqk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tianlin.xyz/Article/details/gtxuevqtsv.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gtikbjgwgs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtpvlccljg.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtrtzzlwjh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtkleboekr.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gtcfxwomta.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gtsfdcjgcg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtenvedama.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtkxeorbdn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtywwqhqbs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gtxhlmremf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gtjwelspxn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gthsgqlqnf.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gttjkqqhap.html

C#:   list.Sort();
来源：http://dali.kuanghao11.cn/Article/details/gtnxluxapq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gtudsnujzn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yongpay.top/Article/details/gtrfdtbhgo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtubohvvvv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtfczkcibu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtsututnim.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gtvnkpgwnb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtqlaxeusb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtjszztqyo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gtoemqaphi.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gthtlsnebr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtesjlixrp.html

PHP:  array_reverse($arr);
来源：http://dali.aizwys.cn/Article/details/gtsetoirxy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gthoomydej.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gtykqmodpc.html

Java: Collections.reverse(list);
来源：http://dali.yvedp.cn/Article/details/gtlkuxdhvr.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtkhxderyx.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gtazufkrwx.html


<!-- 参考信息 -->