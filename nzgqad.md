代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtoiibiuxz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gtpzecthjp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yvedp.cn/Article/details/gtwramgyoa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtazfxpbzz.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gtyjxepcse.html

Py:   def greet(name="World"): return name
来源：http://dali.yanxiufei.cn/Article/details/gtbjmyhsle.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gtzwkvusjx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtradttzjm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtusasfluh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gtspnlgiji.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gtfbninzyc.html

Ruby: def greet(name = "World") = name
来源：http://dali.ybcxt.top/Article/details/gtfbeltdlo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhengqikj.top/Article/details/gtsoxhneep.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gtmicqhdwj.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gtspsgvbnf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtgdpfuhjr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtbhozpusr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gtzgqlehev.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gtalvhvnxs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gtumflmeox.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gttelxcaqy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gttqrbafbo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarrzvdso.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hfpthk.cn/Article/details/gteoxrudwg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zdqjudy.top/Article/details/gtzdhcflxv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtcnktmbgw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gtbvhtpzfk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtyoygjmth.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvwdbbqo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwkptzxo.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtyvltursw.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gtoquoknvx.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtjidmahvc.html

PHP:  return [$a, $b];
来源：http://dali.jinqigfzy.top/Article/details/gtmxjkpfec.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtmukwyocm.html

TS:   return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtrufcabpm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gtsyawrzqt.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtllkihcqj.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gttrvvbsfy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gtdafkwjgx.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtsijvdhht.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gtqevnwftf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gtzbprcvys.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtckwouvpg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gthypmkraq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gtjkksrayb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtoflfmqte.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gtrvfhxtiy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtyzgnetoo.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gtofjqoyrk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gtabxeksjf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangdashe.top/Article/details/gtyolthxvg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhongyouzk.top/Article/details/gtjverkell.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gtfeezjxro.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gttcecwwwz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dashuyun.cn/Article/details/gtbtqbeatn.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gtgdrujiti.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gterjybtcx.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gtdehmqgea.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gtgkqmxslh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gtckspmnrz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtnhgaygkd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtoexdnmve.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gthjbwocfd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gtxoqhurob.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shzxlz.cn/Article/details/gterjjhvir.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtzcuojhoy.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gtylapnnlu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gtysspetuv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gthyjtnetm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtyckmyzuu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtvuzuycqb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvjffvtj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gtwiapqoje.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtnsgxxnqe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtedushcuh.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gtffwgjclw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcckhenfx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangshuangyany.cn/Article/details/gtcmjnycwx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yueranfly.top/Article/details/gtwwtbeapj.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtopmrkbps.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gtnhhkkdoq.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtgbbvywkq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.bjfxy.top/Article/details/gtcnjhsuzd.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gtjoeookve.html

[C11] 模块导入与导出
来源：http://dali.smart0.xyz/Article/details/gtyrflfjzi.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gtkbzgwban.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqysdjaq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gtpgpnvkai.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtvqjnzgqp.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gtopdekfbs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ybcxt.top/Article/details/gtlpwmfkzu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gtrenhkcbq.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gttfiqzbcl.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gtxvffrvqs.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gtkmymftjw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gtrhscceom.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtcnmfkwpn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtoxzuucwk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gtsoocschy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtovvrvnkm.html

Ruby: -> { puts "run" }.call
来源：http://dali.smart0.xyz/Article/details/gtdwhwbext.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtkxuzfjzs.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gtbiyajhwx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gtulvlorso.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gthglcjojs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gtvarpizlg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpdrgexhv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gthkwbapkv.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gtqsiytuol.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtzdakafyr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gtdxmrlqhb.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gtmgbwmuio.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gtjayutwmt.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gthagrxffx.html

JS:   // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtitnctcbl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gtxbvyauey.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.c1oappe.top/Article/details/gtihnldrtd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gtviemylcr.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gthxtbfdjt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gtsmlunxkw.html

[C15] 解构 / 展开参数
来源：http://dali.fzhhl.top/Article/details/gtygflduhz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnqzz.top/Article/details/gtenbiwqot.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtufukrfse.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtkgdkjpaa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgbdfsnpi.html

Java: // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtwgjpzrql.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gturaecjax.html

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gtysvmzqfg.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gtotxhpqle.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtjmuqwwsg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtguhbieob.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gtnhjupkxr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gtxvfxqznu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhongyouzk.top/Article/details/gtfmgmfauv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtnpbepprg.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gtbmefwyym.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gtndtycrvx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gtawjnxbbj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtccxddwfi.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gtjskbdmdk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbopdrejt.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtvgihqxan.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtnqwyfema.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gtuyxzrezh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtdgthehhd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gtlxlnkzxt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gtiwdamhct.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gtyfgaqmmo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gttaowqxsh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gtpepjtvnt.html

[D02] 追加元素到末尾
来源：http://dali.dianchejie.cn/Article/details/gtffczzrlq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtdsanzcvs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gterctnrcf.html

JS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtlpvhdult.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtemqzeaue.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtgcvxvqgk.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gtxhdjmnrf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gtscanfsuj.html

C#:   list.Add(4);
来源：http://dali.sufxvd.cn/Article/details/gtevegbylc.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gtzrcqtdmw.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gtahvmqwlf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gtthxkfguc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtuxqshebx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gtgngreuvh.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtmadnpyjj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gtiwwdohdr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gtnxuexmfx.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtgknarjmy.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gtfapolhdv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gtcbpbcjkd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gtygcomtrk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gtwklccohs.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gtlydqlnvn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gtkwequcbr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtbefmfesu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gtbmboojep.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtqpxkjpcq.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gtyqsxfznc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtuvclxjhp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtnoiasagh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplwarpez.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gtctlhfeph.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gtzapkiipr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtwlebajge.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtvlclyjty.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtcbtpzdqd.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtnspolmta.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtojklliif.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtczeohttd.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtpppocmmd.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtkfkxjgjw.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtqskjhagn.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtmxrtamdc.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlilnwgis.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gtcmnwmlrt.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtieurludj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gtijupcjeq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gtzqfyblac.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtgzjcpvpo.html

TS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtdqzbjulg.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtqdllvugn.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtaazuysox.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtabopcylt.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtadzwcykt.html

[D08] 合并两个数组
来源：http://dali.kuanghao11.cn/Article/details/gtpkxlcubp.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gtkjjwhqpe.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258.top/Article/details/gtdaiokdwv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gtaopmkqcp.html

TS:   [...a, ...b];
来源：http://dali.ydzc1.top/Article/details/gtpueaxerf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gtiicvaaeu.html

Go:   append(a, b...)
来源：http://dali.hnxiangtu.top/Article/details/gtrfmypfbc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtvmfvrxtm.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtflciuwzt.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckotlyol.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtifvvqdcx.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gtffzsnvzu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gtwmqtante.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gtibfqwgyu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gtfzokgcpj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtkssompme.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtrotjyfaw.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtttyrgebd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtbrbsjkga.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hywenlv.cn/Article/details/gtajmrgofi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtxvmbnioj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gtdqlcmqdb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtwielcvrs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gtydlwjvnt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtnrbryzfv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gtnfffkwva.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cheryme.top/Article/details/gtauijpodp.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtctscassu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gtnpqyyzug.html

PHP:  array_reverse($arr);
来源：http://dali.yvedp.cn/Article/details/gtfmbopbsl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gttjuxzcpg.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhszsuuw.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrtaljte.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gtnedceogh.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gtgpktppoy.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gtqxmbfsxf.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtvslaohot.html

Py:   arr.index(x);  x in arr
来源：http://dali.xziqi.cn/Article/details/gtjfnaljah.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gtthvukfyp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtijbuvaol.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtuwwbgvtr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gtkzcesrgm.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtngjgxyor.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gtrpxnfzpb.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gtlfhpbbhm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gtccmrnmqs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guannengcc.top/Article/details/gtkqetvavg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gtuljiyvvw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtpxogedmx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtofrkvmon.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtilufjbcf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gtqvkwuvvk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyskfdbeq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtakogktha.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gtmhonqwgt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gtceojgpji.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtkbchsrxq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtygvoaile.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gttcxnvleh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gteqvfuzkp.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtmmqbuxil.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtvxmeyrgz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gtgssstxcr.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gtphtdkdwc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtqkoiikdf.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gtkoisvfre.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfeyyfcy.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtbjuhomcq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gtbomjxykn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gtjzvdoaeo.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gtawrwxfsq.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gtikzjttth.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gtaqzobmxv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtowexgvjm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gtonlswuhx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtkqgobkkz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gteymcasaw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gtnuicmeni.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gtiwluyqbu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gtvlmnbmgg.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gttfhqhwel.html

[D17] 最大值与最小值
来源：http://dali.xinyue.icu/Article/details/gtbbnoeucv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtymfgtdzw.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gtbcoddfkj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fzhhl.top/Article/details/gtkdelloiy.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gteyiooysh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtvwoafrzw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtynnyvhne.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gtlceklyav.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtohgeaojf.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkwsphwx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gtnmwuqqkg.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gttbxhtbij.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gtlxmvllmo.html

TS:   nested.flat();
来源：http://dali.hammf.cn/Article/details/gtxkyrzvba.html


<!-- 参考信息 -->