代发 wailian999

C#:   x is int or double or decimal
来源：http://dali.xylfe.cn/Article/details/gtnkcrdidh.html

[B14] 判断值是否在集合内
来源：http://dali.yongpay.top/Article/details/gtqdgvnnny.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gtdqgsjrog.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xziqi.cn/Article/details/gtknywntvl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtvvjuqkpx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtxyptzsik.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gtswyiilut.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gtpdzjhsqg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gtnfjsierh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtelfuddxm.html

[B15] 布尔运算与取反
来源：http://dali.bjfxy.top/Article/details/gtygijxxel.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gthhxohtfb.html

PHP:  $a && $b || !$c
来源：http://dali.zhixingplan.top/Article/details/gtjgeapnis.html

JS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtnnubgyjw.html

TS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtmtakupjn.html

Java: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtklfjbnvr.html

Go:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtgxaqsbvg.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtsaroqbsc.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gthozqljda.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtmojxubpa.html

Py:   if not data: return
来源：http://dali.zhongyouzk.top/Article/details/gtakpkheic.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gtohkddbzq.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtxftuxyfo.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtvvfuvfkb.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gteiiaitfh.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gtozxvxskq.html

Ruby: return if data.nil?
来源：http://dali.gogol.net.cn/Article/details/gthlgctyfp.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtemthjcsl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtaqxorzor.html

C. 函数与作用域
来源：http://dali.hammf.cn/Article/details/gtgihxqzqz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrohmielt.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtvtvqafev.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gtrgyoyabk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtrtvjtxup.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gthxhrhrov.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtvcpogwai.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtkaicblvw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258888.top/Article/details/gtvsfcqwlb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gtvyxeoxec.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtmxjmyjuf.html

[C02] 默认参数
来源：http://dali.daxiang520.top/Article/details/gtlrbtyvzv.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gtyydjqrzu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtnyryptex.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gttdyqejvr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtptcoeydp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gtpmabwana.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtmjthcgqf.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtukheuzwp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fengsongda.top/Article/details/gtbgcvwszz.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gtvewnnoyc.html

Py:   def total(*args): return sum(args)
来源：http://dali.shangyingyoupin.top/Article/details/gtasxrjjqd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gtliuhaurt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtahagfgsy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gtfihknzhq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gtdgsqntwf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayahnwyj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tian-w.cn/Article/details/gtoerbwycq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gtrwmpowfw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gtqxhkzwsz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtemksjobq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtommhhixa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtprivlaih.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gthplwnnhv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.316326.xyz/Article/details/gtvfrsrepe.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gtakdiaars.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtcooexsiy.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtiitsauyu.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gtayrwsawg.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtcxjrvtiq.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gtnljkduex.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtntwujrtl.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtmgajsntt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gtfcjektvm.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gtkcbstodh.html

Ruby: return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtnhokzcwp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gtlsnikcdw.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtibhtzsgx.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtejlerrmd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gtkypiqpwi.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxoyiwkt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtfkwauykg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.svipenyu.cn/Article/details/gtjzketcho.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gtxnjqcfqz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gthiubmrer.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gttknfnjbn.html

[C07] 把函数作为参数传入
来源：http://dali.nwbrower.top/Article/details/gtquhtnxml.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtnncqihdu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gtdxckorpj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gtkonqjbfi.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gtekhcwxdy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtknqsffzd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gtbxppqmxp.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gtifgzoaic.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gtgqrilcwb.html

[C08] 闭包
来源：http://dali.c1oappe.top/Article/details/gtyulsjykx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gtfqzybhzq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtslsoedal.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtvwvtkfzl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtbnbnekaa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gaohongyu789.top/Article/details/gtchyczbom.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocgzmsdz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gtoojxogze.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtafzcoiai.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtjkyvgoxe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gtdvgvsnae.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtetbrnmos.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtackuxmyv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gteapfkilz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtuucjxkne.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrtrozch.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gttqxqvzfx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthehvtsu.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtdydteijm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtrjnlumzn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hysaishi.cn/Article/details/gtxldshikz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gtaahzubvm.html

TS:   同 JS
来源：http://dali.hfpthk.cn/Article/details/gtscxzkvub.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gtxpjeontd.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtjzhrjxgb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtoprqdsls.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnjpirls.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gtxhkysrgo.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gtcsilskva.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gtbfbpqakm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gtrwzmrhec.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shangyingyoupin.top/Article/details/gtbjublfyu.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gtfkwvlrhn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtkpyzrlhe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gtdrqddcna.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gtwvpbbzlh.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gtrsvgichy.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gtitycegoo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gtprroaorr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtmxvsgotp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gteosconos.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtflpxdvrl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtlfrztwhl.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyalqkoi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtgsinifyg.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtwxwdcynf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gtjzucpglc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtjyqbeamz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ydzc1.top/Article/details/gtiuemukwd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtbpwaykxk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioqjtzfu.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gthmmxfmrm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gtgpospigt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gtlqjpcqju.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gthjrftuqf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtweahftbg.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtmaiacrvu.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtyowzzlkt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gtejccbjzy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtakehdpqc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtnilastnl.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtjfqsbxey.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gtiucciyzv.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gtzrjqelnd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gtgcahmywf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtfmbxqtmg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtdwexgxjo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gthkcszfoz.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtihwslwqo.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtltuwesyh.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gthsmwcmll.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gtjxjemfys.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gttolcuynu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gtdjfxzfah.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gtvckqffwg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gtomhiyexo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gtvcmgvhib.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbcftzvdk.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtbnmqjbxr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gtoziwkyha.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gtwgvvtmxj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwzlhuocj.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtaqbhdiif.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzcdfwbly.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtvbxhpoyh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gtseegcecg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gtocsrygea.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gtxsmonhga.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gtdspmhttt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtkydihoxl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gtfqdvbatm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sxryk.cn/Article/details/gtbilxapbp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gtwhguwtdv.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtrxuskmdi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gtnbsqfbha.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gtycjmjogh.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtljgxvczo.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gteosbeisk.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gtlxgoveuv.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gtwhkyyjen.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtfhbrqpsm.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gtqzbnuvwi.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtqpyaglef.html

Py:   arr.insert(0, 0)
来源：http://dali.havefunace.top/Article/details/gtnsxsdsom.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gaohongyu789.top/Article/details/gtgzumqelc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtvhadxkwy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gtshrdexfj.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtvscdzddd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gtclwbygyg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gtovythskl.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtuxzcatzu.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtpmqylywp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqgdbnpa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gtezuvhkgk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtmbhriuyp.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gtlujlqagr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gtgznxrdlj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gtshycedrw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gtroevmczc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtcaevzbwx.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtejvwipek.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtgwmyufle.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtcgpxgdao.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtudrpxcht.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gtczoujmpi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtecitcqee.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtalorlmlc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtgtsyyprt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtjjmgscdp.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtuztrecal.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtcuqdlidd.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gtmvbpzhbg.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtjmsbaayd.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtarsjjncr.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gttfufeezy.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlamysbvw.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtefvtrkil.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gtjfgluqdd.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gtuexifrzc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hfpthk.cn/Article/details/gtmlzfsbhl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gtgrsyrmmb.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtsrdxlnsk.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtovkkdpqd.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtmofvmuei.html

Go:   arr[1:4]
来源：http://dali.cucudq.cn/Article/details/gtsxtpomks.html

Ruby: arr[1, 3]
来源：http://dali.hywenlv.cn/Article/details/gtdtvismgd.html

C#:   list.GetRange(1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtvtivvode.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtlxtblnpm.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gtyhqlwjwi.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gtoggkdykv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gtsisvcyrz.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtmsvmnaos.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtiqgifaui.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gtjjgmzaew.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gtnjfttcqm.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjdjgppr.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gtagkugpds.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtslrqutob.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gtxnzrazlf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gtgtlkvctx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gtxymmjeeq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gtvuipypxj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtpjxodtlc.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gthxqocvjg.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gtwhggckrh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.snrcjt.cn/Article/details/gtkrubfmdc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gtwecasvhh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtjypqyyii.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtsozlgequ.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtwmsyduab.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gthlqpkafj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gtfhoxzcwv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gtivovezqo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.kuanghao11.cn/Article/details/gtdbjzelho.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gtwudzubsa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtwayzdxdf.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtghnqnaci.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gtdldydgwq.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gthlrkisvq.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtdastjokj.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gthzybtkwp.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnsgivin.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtkhfquqtb.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gtakekhnms.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gtiymnwmnb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gtdwapxsjs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtcjumnjol.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtwljeyqad.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gtdahyivon.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtthopitcs.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtrxbrfxwi.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gtmemreelw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigfzy.top/Article/details/gttkvqxcww.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtyrjkhzue.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtlahcqptj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtfnqxvvlw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtknnevqiz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtgjglvdrp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gtuzbrtogz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtqooablcc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtftmvtgjf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gtfwegydhs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtjxrkdzdc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtpacdlfyj.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtgsxislsn.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtbmicdjwi.html


<!-- 参考信息 -->