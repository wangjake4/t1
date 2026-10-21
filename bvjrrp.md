代发 wailian999

[C02] 默认参数
来源：http://dali.0kj1m.cn/Article/details/gtgngufrrd.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gtvmnsoona.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtbtvhfjbk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gthlauvkfj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtmowqcxkv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtlffwnbcf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gtewkxmaab.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gtpmghamdv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gtkmubnryr.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gtinqkhevn.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangdashe.top/Article/details/gtnlkhjdep.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gtzbadeipk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtebrqahyz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtundfnbsh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gtvqkvtfhj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnobaggd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gtocucedwo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gtdxjzxdxy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gtvoihjbxa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gttyyyegpr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gtuhwlwyhb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtxckovlmw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gtznspkvkd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gtkokucuux.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gtvstibjfj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtfulcrmrg.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtrysrvbdr.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgscfuvvb.html

Py:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtdfjigius.html

PHP:  return [$a, $b];
来源：http://dali.9152youxi.cn/Article/details/gtrxoytvmm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtmmzdwkwt.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtnmhhvsdv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gtegfnnfkv.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtdktvoeyo.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtdfxcdrtk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.bjfxy.top/Article/details/gtoogwkyer.html

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gtugkarjaj.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gtcchtletb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gteddnkwzh.html

JS:   const square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtnzagicad.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtazievftf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gtqwkydrut.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gtuiiclmcb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtndmmsnhc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtfmpzxiro.html

[C07] 把函数作为参数传入
来源：http://dali.jianghu66.top/Article/details/gtxrwnnncj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gtkgutotdd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gtzsrwkzkg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtjmajkobj.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtvddxrwoi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gtxrxadlut.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.haohaochexian.top/Article/details/gtezpxkoej.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gtynvaniqv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gtfzoueaso.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gtqcagkllz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guannengcc.top/Article/details/gtuhkpglon.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gthdkjkmrx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtugqkbkzu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtpcschhmo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yangfankeji.com/Article/details/gtpygtfcdn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.birdmap.top/Article/details/gtwpeqrqdf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gtrznrnttf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gthyhmxroy.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gtotmtqsvs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtcerguoxs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gtdxrzybsl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gtfmgseojx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtnktfkksn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtyywszvdn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gtcfpwnugw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtsjucrytb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtzfqgswnw.html

[C10] 变量作用域
来源：http://dali.zhixingplan.top/Article/details/gtyerlygwr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tianlin.xyz/Article/details/gtlykrmsec.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gtmyrybhmw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gteggklnrx.html

TS:   同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtvncmwaru.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gtoucjrawv.html

Go:   花括号块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtpwvteefz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjszhevxd.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtampamffv.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtwjajkzex.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gtpvnvwell.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhengqikj.top/Article/details/gtaxigzfsh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtqgpqkylu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gtexrutpor.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gtaemogtme.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtfzrqcmam.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gtbadihvwo.html

C#:   using System.Text;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmdgnbqq.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gtpxipykam.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gtkzepfjqf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtizngfn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtazspgjtw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtihichfpz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gttarcjknj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gthdqcsath.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gtrxoljwbd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cdnleiting.top/Article/details/gteqmfurnb.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gtkzvumhnb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gtqwdoqsoz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtvcwpjehe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gtzzxymiaf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtaqioipnx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtzfvvrcrc.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmopsxaz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cdnleiting.top/Article/details/gttdhafzwi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cheryme.top/Article/details/gtzszxpqnf.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gtmrihgvvr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gtruvqzygs.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtawauvfry.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtiaokvgjg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcaiutml.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtvzgtical.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gtsqjtsfoe.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gtqwnxfanb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gtiksvezzb.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gtndonoecq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gtorluqzlu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqfufbjk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtdxdodxgj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtgwqfepcm.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtezrsqboo.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtojbfirpn.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtshsodagy.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtgnjcxrgs.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gthknxuste.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gtptplrabt.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtmznymaqq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtryjtuwmd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtnudillec.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gtctaibybr.html

Go:   // 无重载：用不同函数名
来源：http://dali.gaohongyu789.top/Article/details/gtrmmmmvnn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gtbykuzzbc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfqtcnmxw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqzmwtwwr.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gtvysgretg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtuqdxtpbi.html

[D01] 创建数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gtobtfflyl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtdnhgcigu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtcbtwsdvp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwsnoruz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gtkbxzotrq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtwslforsx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gtxykxxtfb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gtgnoatmiv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtxzagmunu.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtdocpywgc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtxujisejq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtqiskojxl.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtdjxyuetn.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtehsrmjjt.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtxlfaclsd.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtoyyzgdzv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gtnmfzgyfx.html

C#:   list.Add(4);
来源：http://dali.daria6918.cn/Article/details/gthygzvgoo.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gtjldlhoku.html

Py:   arr.insert(0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtevfuqqpb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gtdjyoxgqe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gtzgnzuyoc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtimdvzewx.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtajazluyb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtpsqvumzx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gttruzyptk.html

C#:   list.Insert(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtcttbmgrg.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gtawodcukq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gtplbyzszb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxzihnys.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangdashe.top/Article/details/gtguezxgxr.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtfggmzyqb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcdxgywx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtkllrlops.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtvxrlnjxb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gtfevxinqb.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gtefgqvcpj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtdotdyram.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gthwcfiibx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtmyxfrwgs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtqrqlbkpc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gtwkshahji.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhjgtmwy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtwirfdsmu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtmaosqxwz.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtbqapcsnq.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtqjbxzckk.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gtftdlybbs.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtailwwjns.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtmelajvlp.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtftbtcgpi.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtlidrtktw.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtxapiztis.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gtkvnyjumj.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtxdsyyntf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtwljhjiql.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtswkqnypn.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtpqlisyqm.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtqdmkbbmj.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtbawbmsch.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gtsoqmptba.html

Ruby: arr[1, 3]
来源：http://dali.tian-w.cn/Article/details/gtseyjrqup.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtilhotamz.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gtmzaahclh.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtilwnwyyu.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtczqnsdii.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtzwukwsqe.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gtthfyodbj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtsbsmvodx.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gtsyjzjkpi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.mhx1999.top/Article/details/gtiyymvday.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtzirqpjnv.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gtulyktqdw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtvvrngprp.html

PHP:  sort($arr);
来源：http://dali.fzhhl.top/Article/details/gtqdvabgao.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gtdhufqnwr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkwaysaq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gtgvcoowxv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtmincoohk.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtehjgkajm.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtxrpaqlkf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gtqygmwbxf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtyrpwdlui.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtpgqamcdl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtvgywxsof.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtvwazdlsl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenzaomai.com/Article/details/gtquvmbwao.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtqdsypwdw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gtqksgawwm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtdmkphswv.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbplpfle.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gtcymwydtc.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigufen.top/Article/details/gtqsiplzxl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj202588.top/Article/details/gtsarwsfnz.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gtrhtnwwvx.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gtyerhqtmx.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gtcimagmbj.html

Ruby: arr.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtifnecbjh.html

C#:   list.Reverse();
来源：http://dali.jyoumei.cn/Article/details/gtaklerjqp.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gtzbdbfzzk.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtnrmahomq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gtfzzvtrau.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtbebtxdch.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtmabschwc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gtrjopyuet.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtasmvvzev.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gtssobrusx.html

C#:   list.IndexOf(x);
来源：http://dali.cucudq.cn/Article/details/gtzdldopwy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gthnjsnavu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtytegpixr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtbuapffsy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtczjgzxna.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtrnggvmyb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gtljfnwtxe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gtebtcjhtc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjasopam.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtihwfgqfa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gtnqnxhkkw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gtgotcopld.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gtngzqgxfe.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gttxtfiqmb.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gttnhkfhwm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gtfisjpawk.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtrpqrdnlo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcqumned.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtokucfupn.html

[D15] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtqijhdjjt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtkwextsvu.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtntpxdzws.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtfxfwwzon.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtzwavqqwj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shuidangran.top/Article/details/gtvmbffzjj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gtqaikqpqp.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtxegourxf.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtbnlcuztb.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gtsbipiaei.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtmkdlrecg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtelzekmxt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtjphfoijb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtawftnwxc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hywenlv.cn/Article/details/gttblpzndk.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtpfsxosic.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtikakrcgv.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gttvcaizjs.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gtygxisyzw.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtoyzuizgc.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtisorcrvq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gtkulqioeq.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywbgcsrp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gttzuizkbv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtfqxvusbc.html

Ruby: arr.max;  arr.min
来源：http://dali.tian-w.cn/Article/details/gteaqexsnn.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmfvpout.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gtabfdnfug.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtaqxofyjn.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gtdskszatp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gtzjuujoqc.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gtinkagucq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gtdcsebbdv.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtrwdxnkql.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtcjppgpml.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtyfmmbqks.html


<!-- 参考信息 -->