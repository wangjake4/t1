代发 wailian999

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gtyzjgpwth.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuetiantiany.cn/Article/details/gtigluwsxm.html

PHP:  is_numeric($x)
来源：http://dali.yj20258.top/Article/details/gtvjycepsp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gthghnzdgn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtaheupbmu.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gtcvceumdi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daxiang520.top/Article/details/gtpgxgorah.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gtbewogygs.html

C#:   x is int or double or decimal
来源：http://dali.guowangkeji.top/Article/details/gtgyrlmjts.html

[B14] 判断值是否在集合内
来源：http://dali.fzhhl.top/Article/details/gthgeqjjbj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuetiantiany.cn/Article/details/gtqvhdpbzx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yangfankeji.com/Article/details/gtwnvrrbwn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtptvcruoh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtleatrwci.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtphajeqfc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shzxlz.cn/Article/details/gtpxeebesw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gthowhjnsg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtgkuifghe.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gtecdwokid.html

Py:   a and b or not c
来源：http://dali.yuanzhike.top/Article/details/gtefsqdani.html

PHP:  $a && $b || !$c
来源：http://dali.fengsongda.top/Article/details/gtmuzjeols.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtsevbalri.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtrvaznmgz.html

Java: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtisteexjt.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtyubklgdc.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtcvqqdmzc.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtsvfgygaf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xinyue.icu/Article/details/gtdgjjjsvl.html

Py:   if not data: return
来源：http://dali.jqgfzy.top/Article/details/gtohdorqoi.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gtmsluqskc.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtyzhwkatu.html

TS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtaeljuipi.html

Java: if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gttjecbgwp.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtocrlouzw.html

Ruby: return if data.nil?
来源：http://dali.yj20258.top/Article/details/gtjyppdkle.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gtbfplazop.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjepychja.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gtaqbmpfub.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtbdxuhqwc.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gtckpruhsu.html

Py:   def add(a, b): return a + b
来源：http://dali.birdmap.top/Article/details/gtmuqzjhsa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtwtkqdtqi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtijroslby.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtqirtxkra.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtyutbcvks.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gtnxdunxuk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jianghu66.top/Article/details/gtunbeggbr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gttbjqzmgl.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gtadejuoht.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gtfawnsdnq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtrutoqjfc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtocqlthry.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtdfkflivj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gtciybrgpc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gtijaxormj.html

Ruby: def greet(name = "World") = name
来源：http://dali.cucudq.cn/Article/details/gtduqdhgdj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gttakiarlp.html

[C03] 可变参数
来源：http://dali.zhixingplan.top/Article/details/gtteqkcdza.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtzpskduya.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gtjvmglhhh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gthnjented.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gttyptmrmf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjonzxubd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtdrgawqwq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gaohongyu789.top/Article/details/gtjdxojztu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gttwaxmcqw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gtqdjkxxgr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtbrxpurfd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtjsccugae.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtqhxtlhvz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gtbxtbdoef.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtwsvsmcux.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gtszoaeztp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtkgjhxucn.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtdaaqdfhj.html

[C05] 返回多个值
来源：http://dali.hywenlv.cn/Article/details/gtsdqzpfrx.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtkaydasvg.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gtakjnjcfo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtnfyloyrc.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gtautqfvuz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gtkffgsewy.html

Go:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtijmvommc.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtsxaznflo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gtzbxwvdmw.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gtmpboifmf.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gtmtvzgrow.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gtrkxdmjuk.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtmxltmkxy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtjozzwxiu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtvakhcskq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ybcxt.top/Article/details/gtvtnhkzju.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gttgspvhpv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwyyeswz.html

[C07] 把函数作为参数传入
来源：http://dali.sxryk.cn/Article/details/gtdxvxanuh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtlzhbibcv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guannengcc.top/Article/details/gtydwymiem.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gtiskcqlij.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gtblvpjdpm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tanke756.top/Article/details/gtrxiuwpla.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gtsqsihqsr.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxinkj.top/Article/details/gtwwelxgpy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangtech.top/Article/details/gterautezy.html

[C08] 闭包
来源：http://dali.nwbrower.top/Article/details/gtcjylmfzj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gtoskcoavj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aibaodan.cn/Article/details/gtlzxsrnyi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtdxaxkikj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtimtztcfc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.birdmap.top/Article/details/gtkjhfikec.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gtjnwpqcnp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtixrjsiep.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtktbkcgfo.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtwsoqnkel.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gttndzueol.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtheawqqrk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gtfiuzwjlq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtbgpqanjg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtxvbhxrwi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gtwlmofijk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gtrmgwjpue.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gtqnwfmvrx.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gtyhfowcau.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gtzlewjwuj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gtvfiqeiha.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gtevshemux.html

TS:   同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtnulukmnu.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxpnnokt.html

Go:   花括号块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtvyeubtrt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gtkhpydzrj.html

C#:   块级作用域
来源：http://dali.zycfv.cn/Article/details/gtcbszazlr.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gtzmxrtxrq.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gtcerrkcfu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gtklvicntw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtdhhgzzyr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtdkywdxpc.html

Java: import java.util.List;
来源：http://dali.hammf.cn/Article/details/gtzvtlgjzp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsugalfo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gtbbgqsqdz.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gtidgmowal.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtyhffcdpc.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258.top/Article/details/gtavcjpsgd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gtvffalcmz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtkhyxpdhg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gtykffpgfs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gtukmtqsbb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gtimppagei.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gtfrttjdlm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gttyaycvep.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gtthtgxzuh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtfruqfvkk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gttxuzmhhr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtilubhnyf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtaztfptrz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtnqgcrufb.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gtmymbzmyr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhoulong.xyz/Article/details/gtwxuqidoo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbzfoezu.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gtjfxaludy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtdtcoikha.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gthcvycvxa.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtfxjtpwzu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gtuhqmlned.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gtuixhdenl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnngzwdxr.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtaraurdxq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cashguo.top/Article/details/gtagizwico.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gtqoofooze.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gtvhyjirwd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gtjxunakyf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gtxkfgwypu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtjxfcyuxg.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtdzfpmlam.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtqxpufrlt.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gtdnlxgiva.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gtezatvcki.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gtxgjtldfb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtyeernqbl.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gtqvocqqkc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gtcvglgdrv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqwoigtf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtmxneeigm.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtbicekudd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gtvqvjczmj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtwikaexzh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtidtquxzf.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gtdffntczw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttumbfddf.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtwejekppf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gtokztgjfy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gtnuzzzrze.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gtijqmqhpj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.bjfxy.top/Article/details/gtbbkolqab.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gtqincaxwc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtqxnakign.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gtrdhxigrw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gtnnvybguo.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gteonthcfp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbobwwmx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtnyeytoqh.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtfvdiztyw.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtiafqlahi.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gthnhglzaf.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gtwapplfqm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtpqmzlobs.html

C#:   list.Add(4);
来源：http://dali.guowangkeji.top/Article/details/gttrvrzdzc.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtukmvzxvf.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtpemzrrhf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtiocqiycn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnxiangtu.top/Article/details/gtsccqclcb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gticlzixnu.html

Java: list.add(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtcpbxxmvi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gtxsajtwvw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gtzivfdioe.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtayozyulz.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtngmptknl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gtspedzhit.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gtynlabfaf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtebkllkow.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gthgrdoebt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gtqdpipyjw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuxming.cn/Article/details/gtmyjfflhq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gthrvmzzau.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gtziohmmty.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gtnpjhmhom.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtdrfsrzms.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtinnfstfg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtymnwcovm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtwbrxrofv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gtviovhiaf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtffakcwvg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtnikkbwql.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtrseyunga.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtpqlhyvot.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtltghlfjd.html

PHP:  count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtildfkxfh.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtwfnkkpkg.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtlprdasye.html

Java: list.size();
来源：http://dali.jianghu66.top/Article/details/gtmtrxxykw.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopfsliaq.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gtlkwqkcjf.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gtcmyvwtaz.html

[D07] 切片 / 取子数组
来源：http://dali.cashguo.top/Article/details/gtlsgcscux.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtffrsssuq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtnlmsmzau.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtdtskrszl.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtnpzosfxv.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gteuqdtqya.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gthepisprm.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gtziznjedk.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdnhrsxz.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtlgzrlhuf.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtkwxvpjgs.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gtieqtogdo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gtdgltzrji.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gtpziihocf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gtgvvdfrqe.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gtgubrjfpv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhrysqkk.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtmboosduy.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gtdhfbgtok.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtqdvgownw.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gtoihunrcn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtwngisvjr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gtvrsclmlf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gtwjudsljc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtoprmyttf.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtsouoxpis.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gttnburhaj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtepvhhjbt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gtievknnnh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtxmwehydy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtkhhuyymd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtreyowhwq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gtvnhnilac.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gtdaveddiw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aibaodan.cn/Article/details/gthrxhioql.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gtlwzfnczt.html

[D11] 反转数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtniznbudm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfnklvja.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gtgfzbywlt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtidewluda.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntxhpvfb.html

Java: Collections.reverse(list);
来源：http://dali.wangdashe.top/Article/details/gtieywwfcq.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gtnceaezjv.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gtxtzqdkus.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gtsvqwvvge.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtockcgafk.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gtrujraxgl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtrpmhavah.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsmzpjep.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtxznhggpk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtwlsevgnf.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtyekmpndn.html

Ruby: arr.index(x)
来源：http://dali.ppjwa.cn/Article/details/gtwgconknj.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gtshnjyukj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigfzy.top/Article/details/gtfvickmtu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gthtqzrxgb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtkkzcadwt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtgpoxemek.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtlvqijxbb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gtkfmwqmpd.html


<!-- 参考信息 -->