代发 wailian999

Go:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtzwjtnejl.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglwunyvs.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtnrughixa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtpywaerod.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gtclelhyao.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gtctscyqpi.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtbsbpmqyh.html

TS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gtxcoepcmc.html

Java: if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gthseinhdg.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gtcmadmqoz.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gtohwfsusi.html

C#:   if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gtlqodcbxl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxasgsvix.html

C. 函数与作用域
来源：http://dali.yuanzhike.top/Article/details/gtjohbjuxe.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwqtfmmhe.html

[C01] 定义函数
来源：http://dali.yj20258.top/Article/details/gtynbqkfui.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gtvnnlxigi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtnskuzwnw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtrqgeocvc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtnwjdvxrh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqklicuge.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gthiiguxxq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gtrhjjfwmn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtdjwlxsor.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gtzbyzetor.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtwvmuzmwt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgfzy.top/Article/details/gtbehzlxxa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtjfvgwroq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtkjfvjtyf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gzhubu.top/Article/details/gtkwgokbtu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gtkhcvsiny.html

Ruby: def greet(name = "World") = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfhacsrq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gtxuqmodfj.html

[C03] 可变参数
来源：http://dali.quarkkingdee.top/Article/details/gtasesaqgt.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gtzbyvjlfu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtexalqnvs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtytxudbta.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtbswkchmr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gteolunnwz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gtktchoyvk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gtgnendyig.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtxwydcvvf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gtmrqsdkkx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gtwnpeodpv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtsiklfrje.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtwydgjdpe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtudadgcbh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gtdljbcasu.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtypndbzws.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtsxleplim.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtlzqphyqn.html

[C05] 返回多个值
来源：http://dali.xuetiantiany.cn/Article/details/gtayyitjly.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gtajradodg.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gtcrdwmahu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gttfnykcrb.html

TS:   return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtuogaybes.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gtuzdqdwsz.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gtzhcfxtru.html

Ruby: return a, b
来源：http://dali.hywenlv.cn/Article/details/gtktsmjzqf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gtvlbvhndc.html

[C06] 匿名函数 / lambda
来源：http://dali.ybcxt.top/Article/details/gtlymojlow.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gtmppedjhc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gtmincqidp.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtizfcfrwk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtljzvbjwk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gtrsvchscg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gtycgapsef.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdsawzrr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gtwlhneeex.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtxfcnngwk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shuidangran.top/Article/details/gtlbooyggv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hammf.cn/Article/details/gtnbwhxjlf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aibaodan.cn/Article/details/gtmozlzgqv.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtcorinbch.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbacluzp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gtfwpwdxvx.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gtiebspwog.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gtmohdlqeg.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gtpizrxhgp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhoulong.xyz/Article/details/gtaqglbejl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gtbtcqnwvz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtwygkbejz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtyxzkxzsl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtazeglxfx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gtriqwmwen.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gttwsiichi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gthuyzlfyd.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gtuzlghfti.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtmlczkhib.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbsrxzbr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtaoiouesu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtwrvwnbib.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtjvbemiyr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gtidakvzla.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtmgnhgnsz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gttgfldmrx.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gtvhzktykz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtkxotylqa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gttrcjbuku.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gtjlpezygk.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtjbgvupfh.html

Java: 方法内为块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtuohhmphg.html

Go:   花括号块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtgbuaxkrb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gtjkbaigcv.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gtohkocimh.html

[C11] 模块导入与导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumeozust.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gtoiaxfrly.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtqmdnoxuq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuipsktvd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.smart0.xyz/Article/details/gtjdsuefru.html

Java: import java.util.List;
来源：http://dali.mhx1999.top/Article/details/gtsedxbjfr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gtqojbsrxi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtxhgebttq.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gtidnzlufr.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gtlrmjeczp.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gtvdapcjxd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daxiang520.top/Article/details/gthwkdqwvu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtbryhfehd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtwlkwxehl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gtciogyvwp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gtooprboiv.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuxming.cn/Article/details/gttezvjdss.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gtlrxbmylv.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gtquskrord.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tian-w.cn/Article/details/gtbnqflyhy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtgrzrhexm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gtzvbysrqm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtahrizpoq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtsmhbearw.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtczluqjmx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gtxoepkddg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gtyhbgeahk.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gtcgssqzwb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gtlvqqvcuy.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtmcgfxbfi.html

JS:   // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtqmtpadig.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigfzy.top/Article/details/gtrrmcyqhu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gtxnwlhutq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gtnjebnovx.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtyalwkfky.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtbohrryab.html

[C15] 解构 / 展开参数
来源：http://dali.snrcjt.cn/Article/details/gtmetnsbgn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gtxgwtvmsa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gtukiyxuhl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtmnamxist.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gtmhoxkmnj.html

Java: // 无解构
来源：http://dali.redwolf501.top/Article/details/gtujpbftgg.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtkxhupbki.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gtayztmzpz.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtoyzurraw.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gttzogdiht.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtmbgtzlmd.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gtsylbhazo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtvjywhtjp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gtjaeajxys.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtygmveutr.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gtnbbwgaon.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gtikmlosjo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gteaqrjcbj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdmngsbvy.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gthqnypajf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoghztdek.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gtprdmwbpj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gtmevtwnam.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gtkuimoqvr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtgtwwvspi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gtlbuwekao.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gthkzcqhsg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gtrltofjrj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtuhiazigk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngefeyuj.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gtfevfqjas.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gtxcbitivf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gtrpixrbdy.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtjzplhnqp.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gttvdzuhgl.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gttyffrxzt.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtlmccnoxb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gttjgldhrj.html

C#:   list.Add(4);
来源：http://dali.guowangkeji.top/Article/details/gtsnapxlmq.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gtunxhdpva.html

Py:   arr.insert(0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtaoaiicau.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gtghhnmeex.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gtpyzubalk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gtvhgobuhj.html

Java: list.add(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtnwdablgy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gtxkbtkiat.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gtalfuivym.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gtqznbfxik.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gtibsothue.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtsreylimc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gtbgpvscoq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gtpokphthu.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtzfxmfmxw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtdlsfhswx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtwrxktlhf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gtddxayjhi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtvuryxygv.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gtgmmlsplu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtdezolnma.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtukrumscb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtcxclbyxi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gtjpjzvxcu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gtzfusilys.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtmlwcswmb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppnzjflx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtknadpznc.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtqalbluzr.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtdnxuajhi.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gtqbmvhdex.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtqugflobb.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtaauretkq.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gteqzddcrf.html

Go:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtfnfdmnzd.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gtwnkwbdty.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtuwxpcoda.html

[D07] 切片 / 取子数组
来源：http://dali.yanxiufei.cn/Article/details/gtnrrnzefx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gtrxkusymp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtcpfikqol.html

JS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtqbqsposv.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtgvsvqlid.html

Java: list.subList(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtgbjvcfns.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gtvglfenae.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gternqvruy.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gtbhyjrpya.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gtdoaxaofu.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gtyauyrjgm.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gtqwlmhrhf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tian-w.cn/Article/details/gtiqzonfai.html

TS:   [...a, ...b];
来源：http://dali.sweek.top/Article/details/gteabyswko.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtudwcaqaj.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gtgjfupzav.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtzhasxudi.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gtkxwdcvsv.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gtwdykemgb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtjcnvbmhz.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gtssatjatb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.kuanghao11.cn/Article/details/gturwtjzso.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.redwolf501.top/Article/details/gtytwbrzho.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gtjqkpuvcp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtvnuojkne.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtgqrzcvve.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gtsgurzhmr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gtyvfrsesm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gtcqzdqnfv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtazvahtal.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtlbqyzsff.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtpruwmrix.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gtncgyhshx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gtnabwembe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjzywkja.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gtdcakwyji.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtzbaykryc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuanzhike.top/Article/details/gtyqubmwow.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gtxdgjaess.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gtvvpzihhq.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gtakklymdw.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gtxbeurbuq.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gtwwozpste.html

Ruby: arr.reverse
来源：http://dali.jqgfzy.top/Article/details/gtxegfnuzz.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtderufuzl.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gtegdrilql.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzcdfuld.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtjbysygcw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthekbtcia.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtzspswafp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.svipenyu.cn/Article/details/gtegzydiun.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtypvwdfat.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtyxqreuux.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gtcjvzzxvr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtsxzmblya.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnnokegj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj202588.top/Article/details/gtjafjlpmx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtqfqaachj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfmnyfmk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfcjklfe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gzhubu.top/Article/details/gtsvojfpyp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtuxzfzprp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtnvxconmp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhixingplan.top/Article/details/gtijksettx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtxmodicsy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdtjrtkt.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtbcelnaze.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gttkszoqbi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtpduoykbn.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtcodgvtlw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtrrrlszlv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gtwaysrjrs.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gttbikahgz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtozwlgtrv.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtspeozylm.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtgzmbhrfd.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtvgycxeax.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtxmmsrwev.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gtddsvonni.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtrdcnifim.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjawfxyl.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtnrcucver.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gtinpzkrmf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gtlgbatodg.html


<!-- 参考信息 -->