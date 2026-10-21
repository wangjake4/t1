代发 wailian999

Java: if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gtqpfvrgox.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtwcioporf.html

Ruby: return if data.nil?
来源：http://dali.pycfn.com/Article/details/gtqkjuajnj.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtgfjgwdrl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkliihibf.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gtnvqzwrwk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjmobumoq.html

[C01] 定义函数
来源：http://dali.yj202588.top/Article/details/gtocyebmel.html

Py:   def add(a, b): return a + b
来源：http://dali.cashguo.top/Article/details/gtjnzodzve.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhwxkacd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtlyhspnce.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtzbnarllp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtewwlvsac.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtrxchgwes.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtahixzndt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtkhikafzi.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrjrgbcr.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhkncnmm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gttfimmmky.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcmhtwoov.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtxsylcemi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gtekoteyxh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gtafpaewvt.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gtccstqqci.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.mhx1999.top/Article/details/gtyakchmrv.html

[C03] 可变参数
来源：http://dali.hnxiangtu.top/Article/details/gtgizfqbjx.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gtededtvts.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthawhbxaa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtrnaxhcqm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtyqucoqob.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtgqlzmprp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gtoboulozt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnqzz.top/Article/details/gtkatyjstt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yanxiufei.cn/Article/details/gtfrdnbtdy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtveljylnv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.smart0.xyz/Article/details/gtaeuozcsf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gtvwsihuoq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtpwrgenqe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtohgglvmu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangdashe.top/Article/details/gtjqgzphin.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtctjkngce.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtddftbiru.html

C#:   f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtblpsbxir.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gtdaehkfnk.html

Py:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtjntevubl.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtolzsuhzt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtvjywyerf.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtagpslhbg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gtxpolgqgr.html

Go:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtblrprhxa.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gtkxokumyu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gthjqrzkat.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtxeueoauu.html

Py:   square = lambda x: x * x
来源：http://dali.iojbl.cn/Article/details/gtvoltqldt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtvvxeqrzm.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gthcpywhrn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nwbrower.top/Article/details/gtlnlonehq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gttssnqhmr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gttvzdkdrj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xinyue.icu/Article/details/gtjvkltoap.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtdxwazhpt.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtsydupwdj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gtqunsyltj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtgnjhormx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gtcgzflvwi.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gtjhlycanx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hywenlv.cn/Article/details/gtdlvxtuqp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtmscybryv.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtfzbthnee.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gttdcoyvxl.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gtyfhpumjs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gtnzzanlhd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtppofocno.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtzsomkxck.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuiynvuvu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigufen.top/Article/details/gthmimrtzh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gtupwtfwov.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gtfmeuqfue.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtbtspnjdi.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtebjvadyg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtnwtywryr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwrjfkus.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtxgwtueym.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtxodbyoyb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gthpsxylja.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gtankfvtpg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtvhdwbnar.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gtgnxemhxs.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gtmsylvnsy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gtaitbchcw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gtuoidiabw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gttgraodrn.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtkksowfhc.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gthyglparx.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeywmcrb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gtesxwroml.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtyyofmggd.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gtaenditbm.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuuyvxzw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gtkomlhmpx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtlnoyriat.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gtznfkprua.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gtredxuopz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtrbbkcvge.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gtduhfrhaz.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtoxgzjcgp.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gtngujuhek.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpaveroyb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gtnhqmclpf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtstgrbwej.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtgspbkocn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gtfbhhjnjz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhoulong.xyz/Article/details/gttiyrrslb.html

Ruby: -> { puts "run" }.call
来源：http://dali.birdmap.top/Article/details/gtvaclzuph.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gtbweycnbh.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtnplrfrjc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtwpwzsacj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtjtarxxrb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zycfv.cn/Article/details/gtnkkxvnav.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtbtudzigd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gttqyrcuqb.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gttsxuipag.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtqgstovhl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guowangkeji.top/Article/details/gtzpfxkolj.html

[C14] 泛型函数
来源：http://dali.xziqi.cn/Article/details/gthftblrti.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gtsgqfujat.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtpyvcqqpe.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtatspvffv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtgzftcvoj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.havefunace.top/Article/details/gtamogcdvf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj202588.top/Article/details/gtcybpkjoe.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtshrydtok.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtowjtzldv.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gtkbtwlqsd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtpjueqgbt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gteoevswit.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxnvjlne.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtomrbqzno.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtupivjvzu.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtqgdhgnrh.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gtjjuvgvzg.html

C#:   var (a, b) = pair;
来源：http://dali.xziqi.cn/Article/details/gtksdffjqf.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gtqooudvkp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtiqeoyqwc.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gtkvcssdac.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtyumffusc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gtifpfdtln.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdwekyecd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gtccjcrqnr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gtofnwjaah.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gtvrnccegr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfbocsghj.html

D. 数组 / 列表 / 集合
来源：http://dali.meibo888.top/Article/details/gtilblxmfr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbxhlwabr.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtfgcvsvnh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtsjkmipqq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gtypasrdmw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtxrqnsx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gtvdjosbzq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gtnsfmcvkx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gtonqjwyth.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtnvmbphhf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gtrjusyqvp.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gtaydhewzr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gtxzfgpptf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtbhofwgye.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtscytvwil.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtkzultbtc.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtthhuxozv.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gtdjxcuyyq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gtrscldshz.html

C#:   list.Add(4);
来源：http://dali.316326.xyz/Article/details/gtxyjkywuo.html

[D03] 在指定位置插入元素
来源：http://dali.xinyue.icu/Article/details/gtmefooenb.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtpnnqqoyq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gtzxezmdhy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gtdpuaazsr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtwtxcsyhw.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtbioamdaz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtasilpqpr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjaxrhcz.html

C#:   list.Insert(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtpxrunure.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gtaartcxts.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtgmfyltvh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gtkoguowwb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotldrets.html

TS:   arr.splice(0, 1);
来源：http://dali.hnxiangtu.top/Article/details/gtkngpgyfc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtilsuxsgo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gtrlgnpoip.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtymnxpelo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gtuyeoskca.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtxctwkqqq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtgcvgxfvx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtbfnfsbfv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtofpypsak.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gtqamsprpi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gtldeiqjur.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtcjldxqri.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtjgwzowda.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtwigqmlcs.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gtjflbaxfa.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtnzpfppon.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gtlyhdncmd.html

JS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtbadfylfs.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtvwmifmhw.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtzmezudgt.html

Go:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkituwehh.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gtwtwbsska.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtsjdqwxdf.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtstqkgfmh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gtzqnodtsy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtbkzrmavx.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdydezubl.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtlitvzkqi.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtxwgceknj.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gtpwkeasus.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gtobnfrnra.html

C#:   list.GetRange(1, 3);
来源：http://dali.xinyue.icu/Article/details/gtfjzixsxt.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gtthpxvcfi.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtztarbvwk.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gtiegpwfnv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gtylxnjnpq.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gtxkzxwoya.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtmtjwmagy.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtalkmjytn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gtlihxcsem.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gthvbvbqmb.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gtpxewwcsm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtoubpqksb.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gtknwxjsnl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gtggsahufo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gtfjzsffce.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gtvirolvur.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtvamgoigx.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtgdylpvai.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gthfmxvcas.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gtageumkyl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hywenlv.cn/Article/details/gtfsgijgfw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gthseyirvv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtnwoewfza.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gtffrqfbqe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtzutszmos.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gtpurcbtvc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gtbugzbrxm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258888.top/Article/details/gtbuojiujk.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtbmoumpuh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gtnxddegwx.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtmvxrkixy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gtnasjxgec.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gtjmjwotus.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gthmvsyltd.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtrszdrkju.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtjynrpzgq.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gtyaghoyez.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gtpuilcxjb.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gtdphhyyhf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gtgaktnpuw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtcmeuoqtw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtimoauegu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtbfxszffi.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtfinivesc.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gtgjafmvtt.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtcbocfltm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtugqudhbd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtjmooaowh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtogcpsknk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtgukzfojd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtvbjmpnxr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gtxfxaiyna.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gtoxnrkksf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gtodgtvyia.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtnymuhthc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gtesaaolib.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtkakkwnnd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtlyrkhqwp.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtbyfwbqrw.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtqnsqmqey.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gtfsqdrazi.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtkcssbwut.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtfuyfwxhf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gthpktptal.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gtwmhphgey.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtfhszbdeu.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtxrjjtrdl.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtvqjzvqae.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtvwuwdztf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gthqzfbnyy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtznfgeccv.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gtrplxzfzh.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtfmudfied.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gteqijicph.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gtzulinuko.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjvmrezi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtiuakiokr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtwnkskmgc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gtalxjjcgr.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gtfvxkzxhi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gteroqwnxv.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtqmgncpvl.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtwibaebxa.html

Py:   max(arr);  min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtgcairobk.html


<!-- 参考信息 -->