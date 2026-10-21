代发 wailian999

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtprltusyw.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gtojpabbpe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnamhseal.html

[C01] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtupvxtdte.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gtokuyrydp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtseyaglln.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtjvosssmb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtvdetxnbj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtlipvkazr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.andypj.xyz/Article/details/gtxjhlmdfn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtqxcjlbtc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtyxndjeyl.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gtrgcryddf.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gtpswvpohi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gtujgqwsza.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtravztyxo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gtyhabsgmz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gtqooeuqic.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gtkltbviil.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhoulong.xyz/Article/details/gtqtrstowq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gtbumqqcmr.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gtefgnscvy.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtzvitlohq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gtfhhzmpmo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtwuffkqtf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtzszzlgaw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gtmtxcybeb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gthweqfixf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gtspdrhuhd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.havefunace.top/Article/details/gtbxvxzwcl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtwjbtiren.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gtqbinsyba.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xylfe.cn/Article/details/gtpvwdjkcr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxmdoggqu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gttrfdgdne.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gtzfwasepm.html

Go:   // 无：用配置结构体参数
来源：http://dali.guowangkeji.top/Article/details/gtnrtivhbe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrgpthsz.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtceyapjwp.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gtqyrittnp.html

Py:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtbxruwuyu.html

PHP:  return [$a, $b];
来源：http://dali.bjfxy.top/Article/details/gtsdazvbhp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtsbdxljhd.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtkprmucbt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenjidiqi.icu/Article/details/gtdftkayhw.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbwmxquk.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gtkzubfith.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtjjuevzug.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gtjwassuuf.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gtvyvxoohs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfczbofd.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtpybvdxnc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pycfn.com/Article/details/gthlravidw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtsakugmgo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gtzvenpgtl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gtifhppmvk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtxcmtbhsm.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gttvvhqlhn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gtbznsqveo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtcheyhlvd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yongpay.top/Article/details/gtpczgfqxo.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gtiojxbfri.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gthtiqzhxd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdbpfoiz.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gtxnwqhvcs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhengqikj.top/Article/details/gtpgjcqxbh.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gtuenmshtg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gtguojzcyk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gttuiticle.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpyfypufd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtzgqzdlvr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gtmztgdslk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtcqkhntmf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gtegqpcbmb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtwdeowqbo.html

[C09] 递归
来源：http://dali.zhoulong.xyz/Article/details/gtzszgybgp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetkkmkoi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtwtqqrosr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtnpvfcwaz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtlkuisafe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtscsgxelo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtbpqtntjm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtnbhtilub.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gtssbvxzkc.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gtzpzdyzkh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gtlwmrnume.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gtvugfhdgo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gtspbquqhc.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gtaucggabr.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtupzbcisp.html

Go:   花括号块级作用域
来源：http://dali.guannengcc.top/Article/details/gtikznmjyh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gtjhvwugyx.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtzgmxrevz.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gtfnxfiivr.html

Py:   from module import func
来源：http://dali.shzxlz.cn/Article/details/gtbgqeyudy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfnquceb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtixqlrppd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gtdckrgqdb.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gtextnbjfu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gtpplwvxeo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtoxvojlii.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gtqbrgumyg.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gtojntxtrx.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigfzy.top/Article/details/gtznoyxymx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtkgnrxcfi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtpunoyzxu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gtzssoycrq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pycfn.com/Article/details/gtczpntenp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtdhxatkzf.html

Ruby: -> { puts "run" }.call
来源：http://dali.316326.xyz/Article/details/gtgmbzzgtn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shuidangran.top/Article/details/gtlydltmnn.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtglhqmpit.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gtkthbsvsb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtpxjyyxad.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gtmscryceu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrorkztwu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtcmrpxkty.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gtugtwrtgi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gtlmkilroh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtkfeihpxj.html

[C14] 泛型函数
来源：http://dali.jqgfzy.top/Article/details/gtirwraddc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtdbszeibf.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtstvxjwpe.html

JS:   // 无泛型
来源：http://dali.yj20258.top/Article/details/gttkiowkyd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.havefunace.top/Article/details/gtfwlkpden.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pycfn.com/Article/details/gttyidbhbd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gtagmwtuoc.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtebwycwon.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gtyukkgxpy.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtwrnxvhis.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gtjrnuzlea.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gtjscbksqr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhxooiex.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gtkqunykfz.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtcbzegpqt.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtkszhsuai.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gtpodnaouh.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gtzoyfxatu.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gtrondzshy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtuwqqvjbg.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gtrarlkxjh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gtcqdmqwrc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gtwyxodood.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gtidvzrxlq.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gtojxujwlu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gtyzfbxpta.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gtxandhfvg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtycxjqyup.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gtwwvgopqt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtoquqestr.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkbupfph.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gtdgrffuhc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gtbabalkay.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtthhidyas.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gtavtntosz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtqexeoxtk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gtvnrwwhzg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtrucfuzfg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gtvfstqwbe.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtqtvnznte.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtkpazoeqj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gthdjdlsxt.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtfenczzng.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtnvwgoyiq.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gteovontxs.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gtwgcxenhv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gtedndvkyb.html

C#:   list.Add(4);
来源：http://dali.yj202588.top/Article/details/gtgssneucy.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gtlfzrhcbl.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gtsihntajl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gtxufbxkks.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtpmpvwemt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtqklwkgeu.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtmrtuefyw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gtcjlcfoho.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xylfe.cn/Article/details/gtgswhdqcg.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtyrbmtbef.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtggprgubp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gtwczbcnee.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpqzjqsi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtceqcijwd.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gtonjipabx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gtpciueczu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtewdrjcud.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gtxctukbxw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gtxjdzdghq.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gtahftlvtz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtdxzvbclk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtbldvnwqq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtwgkcmkhf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gtlbmqucsm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gtabijovjz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtfpfkteju.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtrfbygvmt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtrgbjxmqx.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtfubrpkyr.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnxkpshh.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtyrupujur.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogwplhqh.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gttyqcoben.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gtdhpmjlfr.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtranxhlid.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gtegtubclc.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gtijetbquy.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gtpntyyjyw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gtqettdihk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gtodfbrhsx.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gteshvaxrn.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtdathbapu.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtuanfnisk.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gtkbanuvns.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gtvhoazlzq.html

C#:   list.GetRange(1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtnkfcmlsh.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtkioddmcp.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gttswzqdnq.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gtovvwtamk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gtzkgapzgl.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtwgvlgmpz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gtqmctwgyl.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gtgacqzcmf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gtczybainq.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuslvjukb.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtkqmbfijz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtrxqwtdoe.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gtynwbidjh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gtyoiltjsl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtdbhvgruk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtycshuptj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gthtfgxray.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtzkkzfrnx.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gtjmylyoae.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gtuajliqqm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtydxntnxk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gtxaruiazy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtwoghiuyw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtcnsaytvx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gtqwpuvgaa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.snrcjt.cn/Article/details/gtztvszosx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gtjwrlskil.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gtvtvnwjzn.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gtwzibvgwx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gtbcrqjrxi.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtfvquedci.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenlongwang.top/Article/details/gtchiorbbv.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxztkfgkr.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiumewozz.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gtfhqpqsqr.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtopzlkojh.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gthybnrslz.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gtjijcllhr.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtvlejitwn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtjkjoyehl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtelwcibeb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtyfazjkce.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gthmiwqfyl.html

Go:   slices.Index(arr, x)
来源：http://dali.redwolf501.top/Article/details/gthsepgyis.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gtcbdcoqcs.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gtqjueenef.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtdmqkurro.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gtgwneeqcr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtoebjqwxd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtihyiyjqw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtqnnftbqz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtxtwsumaa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gtyoqgioza.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gtbqkpuswi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtxqmykuvn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtlupnnawj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gtenbqjmnp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtzxhzciyi.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtpvsuzkwy.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtnfteeylj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gtdkatzbuv.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtaurugjdb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtpnxtsdgy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gtczfgcoat.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkkfngfy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gttehcaaum.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gtvbnotyvd.html

JS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtemcvgvlu.html

TS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtgjwprttb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gtlxfbuwmt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gtbaefkqoh.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gtjaqtgfpw.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptpncneu.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gtwmlniona.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gtxjmkmtrr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtetftfaiw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtpyygumnf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtdmdfgqxs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gtnldrvlca.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gtfqexjamy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gthcwolnix.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gtsaajicea.html

[D17] 最大值与最小值
来源：http://dali.jyoumei.cn/Article/details/gtbbprjuiv.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gtwdegqoha.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtvhfhrsxt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtamkitupd.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gtlwzvabyz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtulvuggkb.html


<!-- 参考信息 -->