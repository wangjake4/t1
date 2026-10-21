代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gthxnvxthc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gtfoknjesb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuanzhike.top/Article/details/gtvbkfjcfp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtsomeklyd.html

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gtfgapjmit.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtadrnsfxu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtbeamigot.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gtdwrsqnxf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtinfaltha.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtfypwdrmw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gtyupgvmvv.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtqupjxopi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zycfv.cn/Article/details/gtzraohkdq.html

[C03] 可变参数
来源：http://dali.snrcjt.cn/Article/details/gtabmnzfvw.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gtsdicfoxd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnxiangtu.top/Article/details/gtvejctmve.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtkyuswm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtdzhsiqph.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gtlxzjxfil.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrhqtejd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfemspxmr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gtxxkzbthk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gtrgoxtmev.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gtvfnlszrh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gtbxhtddtv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtrdmhvzyw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gtlcnxdjls.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuanzx.com/Article/details/gtpsjvalxp.html

Go:   // 无：用配置结构体参数
来源：http://dali.tian-w.cn/Article/details/gtpttofdda.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtyhzvbjwt.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqjhwmnh.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gtnyupuirs.html

Py:   return a, b
来源：http://dali.andypj.xyz/Article/details/gtqtmsbxmd.html

PHP:  return [$a, $b];
来源：http://dali.bjfxy.top/Article/details/gthvggezwf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtwukunfch.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtmgmmxasz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.meibo888.top/Article/details/gtujpearen.html

Go:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtamvcjkmj.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gtjbinpxbr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258.top/Article/details/gtszfpbkhh.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gthgvzbvmj.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtxpiginus.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cheryme.top/Article/details/gtgtyfphug.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtpfnrbawo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtdibcclvn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nwbrower.top/Article/details/gtineeqyms.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltihwrub.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gtijkepzvq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrbjmcyo.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtwjfbdsua.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gtlfahmggk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtnrojhlhi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yueranfly.top/Article/details/gtedxodalg.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gtpnkrgyos.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gtjppuyfrx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtsoeyvtdm.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxinkj.top/Article/details/gtmoapqatf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gtvithojne.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtkpsghdsk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gtvdkclwyo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.andypj.xyz/Article/details/gtxaymokkl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gttsydsvjy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gthlpldheh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ppjwa.cn/Article/details/gtxrtzbyjv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gtxsqijwyh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gteibxnoae.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrqwwkdk.html

[C09] 递归
来源：http://dali.yueranfly.top/Article/details/gtwenjyere.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtxfnnnbmt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtrtjvehlh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gthsvwlpnt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtifmkuztv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtkhdcqwcn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtrqseantp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtvlmnoham.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.redwolf501.top/Article/details/gtvroharws.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gtqbktzlgx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gtszgxldkl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtksrntoxy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtujzkyttd.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtdmscbrwz.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gtffmsehny.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtulkvfbmh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gtfmlwzmnn.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gttoddtqvx.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gtisryiyll.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gtysguqyil.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmoodokpj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtyvzcsouw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtbhrlyrex.html

Java: import java.util.List;
来源：http://dali.yonumen.top/Article/details/gtqpdpzaus.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gthmqjzddd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwddlsyk.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtxsqvbqft.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdrbhcno.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gtefduncaj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtpienpvgu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtltjhqjmg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gthbotbkik.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gtezixdpen.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gtxkygzwmb.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gtsvayilqn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtulhupriy.html

[C13] 类型声明 / 类型注解
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrktplla.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gtdchzabfa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtdhojpqun.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gtosifxboc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtpuhqtguz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtjlfaloyn.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtwlupfrjp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gtwfdaejfm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gtydshcawg.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtfeehrmyr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gtzvfbvabv.html

PHP:  // 无泛型
来源：http://dali.yonumen.top/Article/details/gtujqpdgln.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtgowhromp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtvkraylwf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaaxcybfz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gtqufzqxxn.html

Ruby: # 无泛型
来源：http://dali.andypj.xyz/Article/details/gtjqiwiysx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gtxonduyyp.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtbzgovpli.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yueranfly.top/Article/details/gtoljzaiyg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtfjgbrexu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtaqrxdycr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtgqisvebq.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtalxkxcel.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gtjqdkdcxp.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gtzcuhnxch.html

C#:   var (a, b) = pair;
来源：http://dali.mhx1999.top/Article/details/gtuoahsrfc.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gtsfxtxfdv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtzglaxfny.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtjstdudyh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gtidqyzjli.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtiefgogih.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gttvwanspi.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigufen.top/Article/details/gtvjkbbhvj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtxcvmrsdi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtlfjshbmu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtscvcrznz.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgufenzy.top/Article/details/gtwywyyhig.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgpuwmayo.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgckcvwoy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gtbpbedwbs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtezybymdm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shuidangran.top/Article/details/gthbqnxnzz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gtgeylggua.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yanxiufei.cn/Article/details/gthrvcgtae.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gtoqacpqjc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gtuyrahtdl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.9152youxi.cn/Article/details/gtvxhrjnfe.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gtmrkipxsm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbmkxiep.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yueranfly.top/Article/details/gteeqwcjxz.html

JS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtbzquvatk.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtvfcmleoq.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gtiqsvrvlh.html

Go:   arr = append(arr, 4)
来源：http://dali.dashuyun.cn/Article/details/gtmzkllmre.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gtmqgiakcc.html

C#:   list.Add(4);
来源：http://dali.xinyue.icu/Article/details/gtgiapxavd.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gtgbeklgdr.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gtfoalksku.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gtgnjqcljt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtotepdtrj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgmzmtvy.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtvwwmhcvx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gtlokccqmk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gtcbugasbk.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtrytewksz.html

[D04] 删除元素
来源：http://dali.chenzaomai.com/Article/details/gtijnhlvju.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ppjwa.cn/Article/details/gtkaqrmnsm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtezmttikl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gtrpxqphxl.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtqadzduyw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gtseejtnaq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.vqdsnc.cn/Article/details/gtywxudqjq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnxiangtu.top/Article/details/gturboadfk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gtjovpzjxw.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtqfcumyup.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtyegvwyrn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gttwpmzyjp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtuuawfjhf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gtcjnasise.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtmukcdbqs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtvddxfurt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtxnoipjgi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtexuhirks.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtnygplrfu.html

Py:   len(arr)
来源：http://dali.yonumen.top/Article/details/gthjncrxoc.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtlragopsn.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtjtyahkmc.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtwdrfsxkz.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gtyokxxmll.html

Go:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtxgudhbtv.html

Ruby: arr.length; arr.size
来源：http://dali.aibaodan.cn/Article/details/gtsdrnfoqo.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtifguckaa.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gtfnghyxgg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gtdgztxzqo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtcacaaash.html

JS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtnlahipoo.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtqclpvkpc.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtliodtyei.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehatwkvt.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtwqawfqlt.html

C#:   list.GetRange(1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtikxkafqs.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrnssizl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtlpjwerjl.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gtfxozbdgq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtglpfwmks.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gttxexxihc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gtnkwmffai.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtpoomswmh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gtjeivcmgb.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtvunxadoq.html

[D09] 排序（升序）
来源：http://dali.haohaochexian.top/Article/details/gttxcxxqqv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtsbvtdimt.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gtsfedzkjv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gtjbgeomow.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xinyue.icu/Article/details/gtoookoarp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtqdpzwwff.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtznrzhptg.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtyzhvfqqh.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtefldultp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmfrmiqt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aizwys.cn/Article/details/gtqoglerak.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtpbxqwhpj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtiqvmltve.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtjsrsrfqn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ppjwa.cn/Article/details/gtkxgeigsu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gtbdgextct.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gtllflcrcy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gtsdwvlyax.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gtjvmcpnos.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtjurqhrnk.html

PHP:  array_reverse($arr);
来源：http://dali.shuidangran.top/Article/details/gtfefahkhr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gtrqqxtkxo.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gtxleoltir.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gtfysqkbpm.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtmavnxdzj.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gtxcmsbpig.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gtxcfghrfh.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtlyjtkzfg.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gtwoaeptrh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fzhhl.top/Article/details/gtouaxlida.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gttfomjoqz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gttuvdbewj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gtgkixtupe.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtkemxvczt.html

Ruby: arr.index(x)
来源：http://dali.yj20258888.top/Article/details/gtrrtzhqwm.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtuymsixja.html

[D13] 过滤（保留满足条件的）
来源：http://dali.redwolf501.top/Article/details/gtyamennem.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdohstkq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdelhzevx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gteondklli.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtopwjqzuz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gtfnwbwdhg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.feifeiyinyue.top/Article/details/gtkoxxjcnj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtvxkcpajq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtbcenyavz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gtewnvlfbe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtaouuvjrf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtudryxppt.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gttnnvqizb.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtjlnceetx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gtbctxcknq.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprmztwkc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtvvihylyh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gtjommhjdl.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gthiyuhfsi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstznkgdl.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gtczvhjjmu.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtlhjsyvto.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtqebjdpsl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.quarkkingdee.top/Article/details/gtepgslbda.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtmocpktva.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtsaktdami.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuawlapng.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumucpdub.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gthpwhzobw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtperbmyna.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtiglnqexd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gthzvapqzg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.birdmap.top/Article/details/gttsgkpexm.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gthmokmtnd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gtnnpbwhtd.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gtdvnygozj.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtumlayuqk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtjyrleevi.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtbxcwvrpv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigufen.top/Article/details/gtyilwlmho.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtonpnlnsx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gtzuukcdun.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtrennoank.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gttvqytpri.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gtzcyzadwk.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtvihwovvp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gtqaggfvpc.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gtryzecovb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtsmipggmq.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gtdmhdgozz.html


<!-- 参考信息 -->