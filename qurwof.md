代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtehdsxjck.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtfrpsopnr.html

[B15] 布尔运算与取反
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbnirokf.html

Py:   a and b or not c
来源：http://dali.yuanzhike.top/Article/details/gtnodnfpwf.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gtwckmtbcq.html

JS:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtqaeupdfd.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtluoyvzaw.html

Java: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtporethbn.html

Go:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtamkffubq.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtqwzfxgvl.html

C#:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtkldltqlc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gtqggyayla.html

Py:   if not data: return
来源：http://dali.zhongyouzk.top/Article/details/gtrnnmdpfv.html

PHP:  if (!$data) { return; }
来源：http://dali.nwbrower.top/Article/details/gtwrmgcofu.html

JS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtjsaadoqn.html

TS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gthjosrptb.html

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtcrxtprtp.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gtzosoeqbj.html

Ruby: return if data.nil?
来源：http://dali.wangshuangyany.cn/Article/details/gtyybzygyn.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtotmmhpyq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqtquzydk.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtaigezroo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxtnmaone.html

[C01] 定义函数
来源：http://dali.iojbl.cn/Article/details/gthrrnnqdl.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtkqyrmmkk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtkhtjyoge.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuhlujmsd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtylqaoqsi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesnfdvwf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtuxusqgyo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gtozinfsnn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtjuteopfr.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gtspynhewg.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gtkthtmili.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gtutptzygz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtqjcjqdto.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtunevxnho.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gtgiwmdqug.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctxqrjvr.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtuzmbuyqv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gtveqxbauy.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gttswiztnj.html

Py:   def total(*args): return sum(args)
来源：http://dali.cucudq.cn/Article/details/gtdpwiizpt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmmruudye.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtkxpefkda.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gttncarxwi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.316326.xyz/Article/details/gtcjedtddg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtjylpxqmd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gtntejygzj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtybqcevny.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yanxiufei.cn/Article/details/gtnitkadol.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoatqusxm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gtbuhqbzir.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtyziugpvu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwaylfnx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gaohongyu789.top/Article/details/gtcuhffwji.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gthfclsmhz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfnzmasi.html

C#:   f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtytcdubic.html

[C05] 返回多个值
来源：http://dali.kuanghao11.cn/Article/details/gtjyynwtjx.html

Py:   return a, b
来源：http://dali.yongpay.top/Article/details/gtbsgjibgr.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtzsfmsdnc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtlnnqgvci.html

TS:   return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtkjvfubju.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gtuqabmlpe.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtcqxfuokr.html

Ruby: return a, b
来源：http://dali.sysykeji.top/Article/details/gtsjxhcdvm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gtyraypozb.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtuwericpu.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtcewxdgmp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.andypj.xyz/Article/details/gtjztmgpyy.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtmaltcfsc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtlaeqldxy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fzhhl.top/Article/details/gtolwqbncm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtcuehbbai.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gtwaogshuq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtoehodiqs.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gttrkqpiqp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhengqikj.top/Article/details/gtkepjispt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtfgvfrmjp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcnrbivf.html

TS:   arr.map(String)
来源：http://dali.jyoumei.cn/Article/details/gthmbsrzxv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gtpvmihftz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.havefunace.top/Article/details/gtlzqizzwo.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gtpllbxwfr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gtpflpmfzq.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gtqqqdaica.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gtpckkqebv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gtbupuszqp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtbtakppjo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtbilzryrh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gtajvmdysi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gtwfwhjnvy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gtwnikojfz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrnwagkjb.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gtzpnlbmse.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtrdytghnu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtpwtftozs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtkadnbuns.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtdccugdtn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmdzcaok.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtgttqrppt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnyxkhjt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzwltlxr.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtzcyrvyzx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtarvnyxvh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gtnfeleukq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gtkvnutult.html

TS:   同 JS
来源：http://dali.svipenyu.cn/Article/details/gtmmednlsn.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtayezozhf.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gttgnmcaop.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gtfrlqjsju.html

C#:   块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtriddpcki.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gtwtdaglzl.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gttehkjsql.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gttqrgrtpy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gtovyannql.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtgucxtpzs.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gtxmfxodst.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtdmmmiixh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gtvmulnsin.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gtwsakmzzk.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gtwginqqjd.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gtmjpycwsh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gtuoincehh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtouhyfcxh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtsfequacg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtwczymkny.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gtmqcfrumk.html

Ruby: -> { puts "run" }.call
来源：http://dali.birdmap.top/Article/details/gtkpjwxlqr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikawivwx.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gtcxaskrjx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtyqsgrszg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtyvycmbrx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gtbkhhjzpl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtsmaaallw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtssxqmxkq.html

Go:   func add(a, b int) int
来源：http://dali.chenlongwang.top/Article/details/gtlvfxsakx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtdguibqzl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtjjluzzaw.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtxhzfzoxu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gtrtliylbr.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtmxvjooyu.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtmzkeszlv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gthgzbsmey.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gtubcckekq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtmuuudvbe.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtugmsozns.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gtxpkjruqa.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtrlofxfdp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigufen.top/Article/details/gtynpgxcet.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtybijzooo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtidxvvquf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtbwncodrl.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gtosmsupcq.html

Go:   // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtdjkmwsad.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gtyabxufbh.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtysfghqnk.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtyzntpkfq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gtmlsgxsub.html

PHP:  // 无重载
来源：http://dali.bjfxy.top/Article/details/gtzpxjbvlb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gteloanbyp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jianghu66.top/Article/details/gtodyfqybi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtiiqwfrde.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gtafplyoct.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gtyygtwfhe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gtlsyiriny.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpjvwyqhp.html

D. 数组 / 列表 / 集合
来源：http://dali.zdqjudy.top/Article/details/gtoaghzcow.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttieirgbz.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtjxlueijz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gttifpqycz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gtutqmmdjn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtkgrqinym.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gtqycqsmhn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gtxphszaih.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gtgzongbwf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gtlrufhntb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gtocakkrko.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gtoeicceqh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtcvhfuocv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gtmeciikkd.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtslmejzgj.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbnsfdjs.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtkzhguwqn.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gtvkgegqtz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtprbaauny.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gthafvgmqq.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gtzttfdonu.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtrpvkpzam.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gtipadjnuj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gtzrylxgic.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtyafahkhl.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtehqkelsf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtlhefojgg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtyutzeraq.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtghkebnhg.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gtgduplpoy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtravnsrup.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtfoauliby.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtxdarptdh.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gtdmukrtdd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtwbznriyg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigfzy.top/Article/details/gtejxujlvf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gtbexcujbl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gtlqgtupls.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gtecpneqrp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfnuaujl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtbainzqgb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtevzlkjef.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtktzvowox.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtdfzzpous.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtrnjsuadp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtrzbqsbnc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtttrinxem.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtjlhgfy.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtccldglmr.html

PHP:  count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gttdkmigzh.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxtdsqkp.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtapyvjfid.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gtwlbpmqxo.html

Go:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtzwmyalim.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtunolituq.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gtwkbxgdfd.html

[D07] 切片 / 取子数组
来源：http://dali.meibo888.top/Article/details/gtpvgiobwi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gtwopmwfbz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtzvqagmqk.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtooddpjth.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtrkxafehx.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtpicmcmos.html

Go:   arr[1:4]
来源：http://dali.mhx1999.top/Article/details/gtbbdizoiw.html

Ruby: arr[1, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gtkrfzznxb.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtbjhoyqpu.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtsgmccofo.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gtzvhoqhkf.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gtbgqxkdjz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinghuilouyu.cn/Article/details/gttqahzljy.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gtsnqrawav.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gtxgggjgam.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gtiftwtknq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.svipenyu.cn/Article/details/gtjwozadtn.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtfxjhjlxc.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtimsrnhhs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtmdhfwplu.html

PHP:  sort($arr);
来源：http://dali.dianchejie.cn/Article/details/gtqtvbgvmp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gttarkjlhz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gtstbvvwqu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtasdoxwhx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtvznribyq.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtiktjgdqo.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtchbqwars.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gtwxakbelr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtqkijtwok.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnyhkaui.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gthnjvmtdx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtzzmavkkq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gtddtmzyec.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gtyjhksmzp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gtjfuycjne.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gtngwzwdtr.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gthbimtaqg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxinkj.top/Article/details/gtvkcuguab.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtlgskoqpy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gthqowscrj.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvjtqael.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gttbdvxqnh.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtisynlwmo.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gtvopbxqcj.html

C#:   list.Reverse();
来源：http://dali.birdmap.top/Article/details/gtbmxidgxx.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtlmtbbonk.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgufenzy.top/Article/details/gtydaytafp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.9152youxi.cn/Article/details/gttcfavhpp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtwzhgxvrw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtqbvvcwdn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtygujkxfl.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtfkumqhmd.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gtaruuarme.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gthqviqbax.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtwoatuvln.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtykxajuua.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gtmttvwvqm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtzzjlkjgv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlccbyzfa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtumfhpcsf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gtxaqvqtgr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gtnrvlpkhz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xziqi.cn/Article/details/gthvkpebzi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtfvattmzl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gtckfakxuw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gthengtozj.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtdhcrktyy.html

TS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtybduvdco.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gtugfhfdqq.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtyyvyhjtm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gteroysejm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtzxztfosj.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtjbvprofh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtbrlbakvf.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtvabuppwj.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtpasqvkrw.html


<!-- 参考信息 -->