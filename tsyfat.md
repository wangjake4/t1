代发 wailian999

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbfhemtll.html

C. 函数与作用域
来源：http://dali.snrcjt.cn/Article/details/gtfzmiskeu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtuhqitnnx.html

[C01] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzucyqmq.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gtlbpzdzgr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtuydskrqi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtwhgmexat.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtljubxsqv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkiwyqbzq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258888.top/Article/details/gtvdnxmowp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtlxxsrrgn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtggywvxkk.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtdtrsxedg.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gtvpxsodvh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxinkj.top/Article/details/gtzwukltsd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gticnymxyz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtycuvxvvq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hongshengwenyu.top/Article/details/gtavlfmgmq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yongpay.top/Article/details/gtyegzrdxr.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gtlmcydxcd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gtlobylmzf.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gtgysmsxdz.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gtqtyojggi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmexxzfvq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtoaqamkqh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gtpwydvrne.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gtszjitvwn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gtuseaiezf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xylfe.cn/Article/details/gtbkrkaysm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gtugdvirtk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gtrgikvxvi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gtjhlvodvd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gtpssrqcwu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjpwoqfen.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zdqjudy.top/Article/details/gtphptgunz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gtuvyaxldk.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gtvtztodcy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gteyjklocn.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtgxnlagbi.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gtpxyqzgwy.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtadqpxahp.html

PHP:  return [$a, $b];
来源：http://dali.ehwqpu.com/Article/details/gtncqtrbqn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtiuoeisxs.html

TS:   return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtqkkirbua.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtesfsapzh.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntnsxvax.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtzvhdfjxy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gtpeyzhhts.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gtwokfftte.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbbzyadh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hammf.cn/Article/details/gtdjccswmb.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gttvjzpejq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtisshljyb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtxnwoylrc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gttwhcpbam.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtmvcurqlt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzgdlpcu.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gtfzsklcwb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.meibo888.top/Article/details/gthwjaoqai.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtbgmdqamp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gtwycjqivw.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtrtozqipm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtnsivwbri.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gtxsgokrmf.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gtlmsjfedg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cheryme.top/Article/details/gtsjxrqmrk.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gtfetkdjuk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gtmpvgstsg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gtqebukdhm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtqaomurca.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gthhkwckwt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtuscmtzfk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gtnaxtvegk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gtwdgmjcnw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtbxftunzq.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcczacmtk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtpfptsnrs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtamsldgss.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtwcumucim.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtlmtgszgg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtofddjjrt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gtiauopiua.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmfsachc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gtqwienxvq.html

[C10] 变量作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtpcbxfvvj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gtatjyfqnu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gtrysuehqx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gtbhienpfc.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtswznjqex.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtclrxwxjl.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gthkpqyqdk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fengsongda.top/Article/details/gtgieaqgkl.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gtznrpjalz.html

[C11] 模块导入与导出
来源：http://dali.c1oappe.top/Article/details/gtyjqltxdi.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gtdhnprgfq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtoqvpmugd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gthyymrkgi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gtyttfxdnc.html

Java: import java.util.List;
来源：http://dali.yj20258.top/Article/details/gtpziwsvgt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gtzdylqbxa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gtrbfymeti.html

C#:   using System.Text;
来源：http://dali.xinyue.icu/Article/details/gttcvzclay.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gtukhugvck.html

Py:   (lambda: print("run"))()
来源：http://dali.jiagoushi.top/Article/details/gtiiatswpi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gtxeszbkil.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gtwicllpah.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtmxxlnhxz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gtqzcrfzhn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtwzhjxyuj.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtdkddrhgi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtyetjrdts.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtplcafudl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkulvoyk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtqfjqpabf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gtmnxnyulx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtgprfqxob.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqltmxuhc.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gtnfvhfyij.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtealbcosm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gtbhnirqay.html

[C14] 泛型函数
来源：http://dali.jianghu66.top/Article/details/gtccgwxegs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gtqthznsea.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtkrpzpemm.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtpmdixhcm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.andypj.xyz/Article/details/gtyublkeyl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjdczeqt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gteatswdlr.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtgowlqxtz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gtjtliwnnf.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtthfjndgg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gthkoxrmsm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gteemcbshd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtkupmbswp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtxsxljiog.html

Java: // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gthqppxxcj.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gtkyzthpbt.html

Ruby: a, b = pair
来源：http://dali.pengpengdd.cyou/Article/details/gthwvtmmqp.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtzqikjvgw.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gtyyqblqwg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtnbwdykhq.html

PHP:  // 无重载
来源：http://dali.hnqzz.top/Article/details/gtukyqgufh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtblfwgrea.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xinyue.icu/Article/details/gthtqcegnn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtsuhtvuee.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gtqxovofvn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.vqdsnc.cn/Article/details/gtrrpqqoet.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gtsmcfntqd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtiixcythr.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtimmefumb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtihjyvydj.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gttpbgxhcp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gtmwkwphsa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtsgbouand.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gtmjpceuno.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gtxagsnmyl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnbyolax.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtwkafmpbb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gthmkfkimd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gtwqfwqssz.html

[D02] 追加元素到末尾
来源：http://dali.nanxuanxn.top/Article/details/gtldgcrvxy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gttpwegogf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtpjjgqmbf.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtyxgqkedt.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtjstwafsk.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtlsvkphiv.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gtdfzkzdvj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gtatrrhigx.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gtksiysvzm.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtcogjuxam.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtikbhrmip.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtryorxqrh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gtscijocat.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtdeqhvlfb.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtuqxkdzto.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gtdsirousk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gtkeziuyss.html

C#:   list.Insert(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtudyyevyr.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gtywkccktu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gthvstnith.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gtuxdfyeez.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gtmwvlpruh.html

TS:   arr.splice(0, 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtrpxflwxm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtdpsdhmed.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtexsammut.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gtbceqfhna.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yueranfly.top/Article/details/gtiismwkxb.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gtghhloppr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtbimzedsx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gthbwitrfh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gttgxxwxui.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gtylbeyzof.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxinkj.top/Article/details/gtohezffgp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtikcblwom.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gttncgphmw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtrzsgemyo.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtffrvzkma.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gthibhpbpw.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtmtagitmc.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gttkfueviv.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gthkqxtdyi.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtabrjujjc.html

Go:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtctyrcpfn.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdccsavg.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gtfhsijmgb.html

[D07] 切片 / 取子数组
来源：http://dali.gotoacloud.top/Article/details/gtuujwqzmx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtmeyavlpd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtrsafbdhz.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtpyocssdc.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtiwxlrfqf.html

Java: list.subList(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtczxdodtg.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtnhcmylij.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gtwbfelfpz.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtvngmlfzs.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtpgiaeapr.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gtqfwilyhr.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gtlkgwuhjp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gtmxtzdzwx.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtdletzyoh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gtrjxdynnp.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gtqtekwsqh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gtaquxbyab.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtqmetajen.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gtxoreogrc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtlmsnruyx.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtztfecoxx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gzhubu.top/Article/details/gtjmbktfhz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gtkjcteqfv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gtoefjolby.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtgnclnspl.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtzoejthdb.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gtrpgodrxy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sweek.top/Article/details/gtetyehwrr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtovzyhokd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtwrwbdoak.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtxdyignov.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtvrmcqawr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gtkobihdou.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhengqikj.top/Article/details/gthaszmpgf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtcycubcen.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gtkrqrpcal.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsylxymu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cashguo.top/Article/details/gtkfalxyst.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtxnlhiote.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gtqactmcwi.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtpcrkwgbc.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcodenzlj.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gthponkopb.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gttkjdclla.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtokttbbhs.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gtavqsdomn.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtfmeqzrth.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gtrzovskjs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtmfmwvgsd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtxcwrdlzl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gttehrgiip.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gttgldalkl.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gtwcyyqdaz.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gtnioreksz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gtnxbuuevs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gtbkodjlwj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtnogpstaj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtrlolqlmw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtsrjturwp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gtliaahhpd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gteujxjnps.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdxeytdv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtlysxdrgk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtxcvvgbqw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtspopnlfx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtouuivypz.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtshmgtzuv.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtihtuldlf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtkqhytidc.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtsmlnncrh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtlecowirj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gtguklcybp.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gtjvccppoe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtndrtkzeg.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtaohownpv.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtfmemoigs.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtdmixgqpj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gtbrrtvroa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtxcosfafx.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gtnbfbmgjg.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gtneaggvjg.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqncwsnh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtnosjnphy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtdapqsair.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtkioiocxf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtcnryirqa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sysykeji.top/Article/details/gtncpladrd.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfztmwuo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gtqhkyelnf.html

C#:   list.Sum();  list.Average()
来源：http://dali.feifeiyinyue.top/Article/details/gtxoudwkhw.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtphhqfqoq.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtilznnjmw.html

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gtetsqrved.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gtgwezwphj.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gtdyfhxvdl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtiyhmudyo.html


<!-- 参考信息 -->