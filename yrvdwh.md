代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtjonircwg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtyavjjiau.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gtnpzrjmpx.html

Py:   a and b or not c
来源：http://dali.zhixingplan.top/Article/details/gthrkgokcw.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigfzy.top/Article/details/gtbdyznpqg.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtdrcmysin.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtbfoablkf.html

Java: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtovzhjbvc.html

Go:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtyklmtoar.html

Ruby: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtpwqdikoo.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtcjklwaym.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daria6918.cn/Article/details/gtdsejuxyw.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gtisalxtek.html

PHP:  if (!$data) { return; }
来源：http://dali.yj202588.top/Article/details/gtloskxbrp.html

JS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gttzczkyps.html

TS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtwyeeqkvp.html

Java: if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtexvmlliz.html

Go:   if data == nil { return }
来源：http://dali.yvedp.cn/Article/details/gtywssigfr.html

Ruby: return if data.nil?
来源：http://dali.yanxiufei.cn/Article/details/gtceesewbm.html

C#:   if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtffcscjgr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfxmrjqpb.html

C. 函数与作用域
来源：http://dali.hysaishi.cn/Article/details/gtztuinnau.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmtkufycu.html

[C01] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtharsalqj.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gttrcebbum.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtntxtrqtf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtcndxsbjr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtzsyikbuf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtydswexrs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gtwzqqgdrz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gteczhjvoq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtyzuegnrs.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtwfjvzlkt.html

Py:   def greet(name="World"): return name
来源：http://dali.cdnleiting.top/Article/details/gtmdtccxex.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtugcalgty.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtohllfopl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gteppenejc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gtevldolbj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhongyouzk.top/Article/details/gthdedaopw.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gtwhzxtrug.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtjalgmesi.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gtapeeihlb.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gtopuqrbuw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gtrdryjduk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtularnprn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtfnoznkcq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gtwtipimdu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gtxolpsjmd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhengqikj.top/Article/details/gtcjtfmpwk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gaohongyu789.top/Article/details/gtdyuhqoip.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cucudq.cn/Article/details/gtohuviuec.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gthglohaud.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gttyzzavnw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtydyhbhxq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daria6918.cn/Article/details/gtdobezxjt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gtfvqldgbk.html

Go:   // 无：用配置结构体参数
来源：http://dali.yvedp.cn/Article/details/gtymgaxotj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtfmcesipt.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gttdtcwtie.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gtujwjxpkl.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gtjsuorpwo.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gthgteyldm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtjtnyybtd.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtlusyazgp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhengqikj.top/Article/details/gtdczwxunz.html

Go:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtejyuymcy.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtucwxpqto.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtglqgrzah.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gttiildqkh.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gthyqbsfjj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gttwucgvpc.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtzzirfbam.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.havefunace.top/Article/details/gtefwoazml.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtttowvkoc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtyhjwocdt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fzhhl.top/Article/details/gtatcqxmsf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gteurcafps.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtfrintyyd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gotoacloud.top/Article/details/gtqscgiuyf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtcdnolyqa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xinyue.icu/Article/details/gtixriuosq.html

TS:   arr.map(String)
来源：http://dali.zhengqikj.top/Article/details/gtsxtqzbnv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtlmsyyyav.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gtvegdyexf.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtfohookil.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pengpengdd.cyou/Article/details/gtjaxdpzsq.html

[C08] 闭包
来源：http://dali.cqqwz.cn/Article/details/gtdtbcmlzu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pycfn.com/Article/details/gtvezlriru.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gtqhqjtwdq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtponywgbx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtwgsmpssg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yanxiufei.cn/Article/details/gtngzyypsj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gtatweyvpu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtothgrlum.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxutrlrr.html

[C09] 递归
来源：http://dali.tianlin.xyz/Article/details/gtoqgquuyr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtkjotobbq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtrpzdrgkq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gthjxvizfz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtswdtwyyb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gtedfaomqd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guowangkeji.top/Article/details/gtldldzjif.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gttgazqcmv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtkcrovpzi.html

[C10] 变量作用域
来源：http://dali.redwolf501.top/Article/details/gtispppmco.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gtfzammlqo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gtdvthzyxc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gtqbroqcek.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gtkrnubqwq.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtuyndfubx.html

Go:   花括号块级作用域
来源：http://dali.cucudq.cn/Article/details/gtveuhtkpi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijkzuhps.html

C#:   块级作用域
来源：http://dali.wangdashe.top/Article/details/gtonjyfuge.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcjxwmrx.html

Py:   from module import func
来源：http://dali.c1oappe.top/Article/details/gtxrgtayca.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkbbppfq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtohqhbrop.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xziqi.cn/Article/details/gtyqeucwnx.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gtqfmmeajv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gttiomptnw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangshuangyany.cn/Article/details/gtymtokcxw.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpiijgzc.html

[C12] 立即执行函数 IIFE
来源：http://dali.xylfe.cn/Article/details/gtalvrvtqi.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gtaqbitfxu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtxpwsjiyg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtustqrocq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtzdnenzbh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuvladcv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gtkqvlckcc.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtgybfjimh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gtlacrbdvu.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncqanmht.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtgzlpspbk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtvuconfvv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gtbfvdikia.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtvprkdhds.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtthjzhhya.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gtiakhauqp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gturmqbkxd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gtvoleoivf.html

[C14] 泛型函数
来源：http://dali.wangdashe.top/Article/details/gtzojnkbcn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gturtgjkak.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gtpuqgbobb.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtidxbgwsm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuanzx.com/Article/details/gtemqnkdrs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gtrfdtylil.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gtxncnligc.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtwxfdamck.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gtiytecyzk.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gtichtjsqi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gtrudzqotr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gtmojlisfg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtyuqdqevk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gtzddsyktm.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtkcocbkul.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtwsxzbdme.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtmmakbbyp.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gtlcfahjmf.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gtowdkmdbx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gtbsempltz.html

PHP:  // 无重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfxdaeuy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gtxnyqwrmt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gtwsnhrwmk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gtwpqamimx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gtznmgybbk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gtjfvqqade.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gtdvdovkpi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtinvljjyz.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtbfmtpwov.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gteibujhnm.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtvciqgdmw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gtdnfnszse.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtkqvuwtha.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtgzkeezpw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shangyingyoupin.top/Article/details/gtojfpylla.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtbddytroy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuetiantiany.cn/Article/details/gtenhbobwj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtmsrxllqf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtaynadmmx.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitypkaan.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gtpmeshhhe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gtwnbueghb.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtkjfzmlme.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gthtpppzdn.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gtknsxqfxk.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gtqppohhad.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtmdrbyaae.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtgqvufnxj.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gtsdrcszkb.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtqqgbgiee.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtasxdylgd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gtndymnaho.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtpysqzfag.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtrhcpdxmf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtsiygiwvx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkznykwbo.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtaclvfcah.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtvbzujwrh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtebxrrwvw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ivvv.top/Article/details/gtyupvhmsb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtboazokol.html

TS:   arr.splice(0, 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtmzvuyokn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gttjlyrtee.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuxming.cn/Article/details/gtpelqstwe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gtbwiipbvk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gtvjwqaeuk.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtolatmbzh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtznjwyhno.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtueipgkvk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtsqcbadoa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.birdmap.top/Article/details/gtqytytajh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtpnmqvnbk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gttbdcdgdv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtcbeqowib.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtitkoulfq.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gtniouhvzz.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtvxgnvmuq.html

PHP:  count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtydtqefsi.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtnbgqgmwm.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtwarvkbhg.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gtfsgfuebl.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtgtzcpnyf.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtarhbcylc.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gtbxypynmd.html

[D07] 切片 / 取子数组
来源：http://dali.cashguo.top/Article/details/gtlnoyxqet.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtnpmbzfvz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtudslawmg.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqrsothq.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtelpvogdk.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtxoehwqeq.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gtbovsgohy.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtiajumsyj.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtucoqmawd.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gtlxmscaeq.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gtwfjntbcd.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gtlmnhhmsj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gtnvmeotjg.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtkccaqtwj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gtljrbvzwn.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtxhapfbcu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtssgpycte.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtvntncsof.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtciicksbk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtmfhhakfs.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gtqwfrfdfg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtgctkraxd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtrikqqsas.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gtteynlobg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnttnyew.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtbsoivsvy.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gtpifbwyhl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gtyybprhct.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jianghu66.top/Article/details/gtzmyvwesn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gtdvbvdfpq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtytfhamvp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtmeffkgsg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gtxwazkcvm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gtnvpjfdoz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpurfgqoj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdemyfebq.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gteqcdelpj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gtwzzaoqjd.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmotvxgq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtccfwkwul.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gtmqpqqrzv.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gtnlglzsgq.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtoecvjdaa.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gthbspcxve.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtjmodnqjo.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgobubzyt.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtifpsocnx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtwmtzjjrh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtuanvrums.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtubmpbbhl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gtmeegragb.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtktncdfsn.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtrncdybri.html

C#:   list.IndexOf(x);
来源：http://dali.hongshengwenyu.top/Article/details/gtrvprkffk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gtyqblsbvy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gtisdopzir.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gtocsbjhgs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtzmgyijsc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gttfyinbmd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdksyvykq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gtszgbscjh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanoeykdh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtrydroxea.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gtoquekvkl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtgeozpdcr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtvxpeqtgk.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtsqowuruc.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtuidxnhjk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtzgwsubcb.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtkkadubla.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtaqewzjxg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtsavpsfvn.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gttoclbter.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtqhogzvnk.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gtdrsujrdy.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtxnstnolc.html


<!-- 参考信息 -->