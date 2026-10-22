代发 wailian999

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkzwbxzoo.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gtiudthjtt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtemxltuwt.html

[C01] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtkqzqcjdp.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtesnkidee.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtlyzdpjsq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtgtqcmmzs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gttxemngut.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcelrpid.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gtjqpkkujm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gtaylueghm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtwbplkugm.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmufsgcmk.html

Py:   def greet(name="World"): return name
来源：http://dali.ybcxt.top/Article/details/gtozkeabuh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gtjvafuuzf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gttnqmukny.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtdqxdyuuo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gtdqrqkktw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigfzy.top/Article/details/gtedicnuke.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtxezfgvdk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuanzx.com/Article/details/gtdxcfryln.html

[C03] 可变参数
来源：http://dali.jlsjyb.cn/Article/details/gtqstadvef.html

Py:   def total(*args): return sum(args)
来源：http://dali.guannengcc.top/Article/details/gtzturuazo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtbcuwuhua.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtndkbxbxc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gthzpawvii.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuxming.cn/Article/details/gtqgxhvvfd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gtgyjczpxn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gtvgnlroqn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gtkzeqcwfe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.mhx1999.top/Article/details/gtpilesbjf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jiagoushi.top/Article/details/gtsoqqhdrc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gtjajejwxb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtjgvzgmyk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtzobncqmb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttthmkqhc.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gtvxkdimbe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtcbzsfgda.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpczyoybo.html

[C05] 返回多个值
来源：http://dali.fzhhl.top/Article/details/gtkqlpbpsl.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtrhnpwvdi.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gtubojmqvg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gttuihnhlr.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gtpukvxqaf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gtnytjzdnj.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtnnksxwcq.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gtaavdxbns.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gtglsnozxd.html

[C06] 匿名函数 / lambda
来源：http://dali.tanke756.top/Article/details/gtzqkqzbns.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcokpjui.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gthnlyajnm.html

JS:   const square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtyqntotmt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gzhubu.top/Article/details/gtmcfvyyqu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gtezyuqkvz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zycfv.cn/Article/details/gtrvpghqbe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yvedp.cn/Article/details/gtbuokbtdk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtmoastlkn.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gtrjxdedri.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gtsuizajqt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gtzdwphdcn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangshuangyany.cn/Article/details/gtxflzfpvb.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gtjezzyqdg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtjeqeewwt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gtlprckikm.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gtvamktkkb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gtktzzvrxm.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gtoxrnlprh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gtbxxinnmc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gtpadivyyw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtvnpndxgm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtppbjwqtf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gtrgbhvllm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gtaijcqfex.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gtfreqfyso.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtgtkysung.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gttccvhnuj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtpnbtrgor.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gtpqqwyzpf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtwccukjsg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtaxtkwwue.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtrhfmngxu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gtczuvoxcc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtodxyctyt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zycfv.cn/Article/details/gtrplchoeo.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtdbqtybwp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtlrkrnhgj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gtyyftaasn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gtxquwltqe.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gtfkdwvnkx.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtlckuhplv.html

Go:   花括号块级作用域
来源：http://dali.havefunace.top/Article/details/gtmhccnall.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtydcmlhmv.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gtzrzmdveu.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtauzipwkb.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtxlauykkx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gthxszqsxa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtzrobsewc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aizwys.cn/Article/details/gtwoydrqak.html

Java: import java.util.List;
来源：http://dali.haohaochexian.top/Article/details/gtxzojxyie.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gtokiegsfk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtfxjnqiey.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtroniumyg.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gtudzzzrzz.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gtxeznhxbd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.kuanghao11.cn/Article/details/gtvycdwywy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtcqkdegrv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtnwghuqmq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gtydimtbrz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtmsqjpraz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gtphinujfy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gthbjdwqca.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gtitjdojuk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gthwptblbp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtcxrjhjfx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gtmeofzfsl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtcbpukvzm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtgexplikf.html

Go:   func add(a, b int) int
来源：http://dali.jinqigfzy.top/Article/details/gtbnuesroz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gtzpaimxrp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gtvlxqkbsb.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gtuswksteq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yangfankeji.com/Article/details/gtnlppgfgt.html

PHP:  // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtorxzxijy.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtqdnrfstz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfnwbxuiz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gtoylxycyn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gtvmgpnpqn.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtuthgmoir.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gtikapovcx.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gtsquonlkr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pycfn.com/Article/details/gtqrkzhjco.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guannengcc.top/Article/details/gtgtdoqjve.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gttmxoaldb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gtdfzmmckh.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtdzwdyesf.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtgloufpyq.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gttjexnusa.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gtulyuujsf.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtrimempen.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gtzvsrmwwa.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gtjtpvpbqt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gtbaisgpro.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtgdyrrlsc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gtpnjhioco.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gtaxybcydt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquwoytjg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtyiujkvzs.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthtstqqmh.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gtnfxqzsbr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtrlzsqwur.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtfetgbjfo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cdnleiting.top/Article/details/gthfhawbrj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtjarygfag.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtxdfiohrl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gtxkkcnfka.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtscpewzfl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gtjcyjqvld.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtyzrqhmgz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gtisieuelh.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gtstkhpizv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtdznngjpk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtspfmloou.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtqjnamriu.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtphatzqeb.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gtagitybrs.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtguwhisbc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsbfrhsw.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtlvdjqciw.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdumosdaf.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtzkefmosr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtczxcgyaf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hfpthk.cn/Article/details/gtriemgfoa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtsjkuokcd.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gtevccboyv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gtxezxjxfa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gtcttjssjv.html

C#:   list.Insert(0, 0);
来源：http://dali.316326.xyz/Article/details/gtreizkntn.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gtkyzukfga.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daxiang520.top/Article/details/gtzkoprnbm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzyinknk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinghuilouyu.cn/Article/details/gtxixwxcfa.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gtfwapuzux.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtfvbxnbvf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gtdgzzdklj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gtobstpxhk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gttkvrxmxn.html

[D05] 访问与修改元素
来源：http://dali.hywenlv.cn/Article/details/gtfsspztlm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtpyoqpeff.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtjhoypfws.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtheekoutc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gtxpbelzxl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtrgpvziwi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtzhatzjgy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtwqqphxok.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gttxffzxxq.html

[D06] 数组长度
来源：http://dali.cheryme.top/Article/details/gtxrrchade.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuetfpdj.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gtxxhbtucy.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtdkalgxqj.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtgkbgitie.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gtgjlinuqx.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtdxgixoyl.html

Ruby: arr.length; arr.size
来源：http://dali.sysykeji.top/Article/details/gtoxiroxog.html

C#:   list.Count;
来源：http://dali.haohaochexian.top/Article/details/gtwhcjuzkm.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gtrmwyrvtl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.feifeiyinyue.top/Article/details/gtuyoviemu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtdglwadtw.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtxxtenztg.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtuyuqkjhj.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtbrmhwhwr.html

Go:   arr[1:4]
来源：http://dali.yueranfly.top/Article/details/gtnabbqfcx.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gtfkhtnyrf.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gttfhqxazu.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gtaxluorpe.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtmfevfyfw.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gtjdsaqxqe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gtpciobchq.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtktpipzqw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gtiewuyrzw.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gtxnyqbhzd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gtjrrlmmoo.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gttwvizshp.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gtetuzacrd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtqhlyfpfn.html

PHP:  sort($arr);
来源：http://dali.9152youxi.cn/Article/details/gtsumgvgsl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtdubewypn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gthvmdmkkl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gtzekaeqoz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtppucqxnb.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtjobjgoej.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gtgyhkjzex.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gtdeefvcbv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnxiangtu.top/Article/details/gtrhrbygpp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gttogiysve.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtbehfruco.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gtyrahcxod.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtjupfnetm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gtseurzeme.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xylfe.cn/Article/details/gtypvhvmez.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gtwobbonuo.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtmgowfgpr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gtbhctcaqc.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtyekficyd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtbfvevoit.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gtzlqxwpxe.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gtnsdvgvhw.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gtoolnlnlo.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuofxxqm.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtcoznmbyu.html

[D12] 查找元素下标
来源：http://dali.iojbl.cn/Article/details/gtnjwrhlft.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gtashmlrph.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmwgmeqx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtsyyyxuwf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtmslanidc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gtokmtxesi.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gtzingclid.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gtyxsoriuk.html

C#:   list.IndexOf(x);
来源：http://dali.hammf.cn/Article/details/gtqurdoibe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtxfqohnjo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gtajdyhgqz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtbcehyeqk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtxfzeexnx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtaqdwytyc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtjbpejvej.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.mhx1999.top/Article/details/gtpzvgchee.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gtsrucfpse.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtretpxgoe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gtkmtanekr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtvcozzflj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gtuzckuohf.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtqmxcakcq.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtzsgpyctj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtltcecimo.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtwhkznpjm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtuezaufac.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtfcewlmck.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtryprgvfu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtqpllnljk.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gtkhcxpjuz.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gthwblhmak.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtqyexhdpg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gtmrtxunkf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.bjfxy.top/Article/details/gtjzmlahvy.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gteprokoll.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gtmpcbeoyb.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gtsvgfvxbo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtdnmtfgvz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gttxhnnfrt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtzzauoepp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtkzbfwsnq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gtlcyiqxbl.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gteodthvlf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gtkdlfkjin.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtfhdirnas.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gttgbmzefn.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtzlunnini.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gttobsyemc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtwzsnnekt.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gthmhohwhj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtfdyayezw.html


<!-- 参考信息 -->