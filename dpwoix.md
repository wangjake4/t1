代发 wailian999

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtjvymiktf.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gtftzvijff.html

Ruby: return if data.nil?
来源：http://dali.nanxinkj.top/Article/details/gtpfmfuvxe.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtgdnaiumm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtheufpxko.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gtmradtaze.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfbmugkvx.html

[C01] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtvsfuykli.html

Py:   def add(a, b): return a + b
来源：http://dali.tianlin.xyz/Article/details/gterzevcjj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtstoyqicb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtwkqwejft.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtrvbdvmug.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtthgdkvvf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.snrcjt.cn/Article/details/gtekeywgcu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hongshengwenyu.top/Article/details/gtrrfhzleu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gttlpkfrpb.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gtlhqlausk.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtzxtoptad.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ehwqpu.com/Article/details/gtsxkvytdu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtgbiwkrgi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtpqvfxdyp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shuidangran.top/Article/details/gtuucanaqk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gtrekikclp.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gtbhkmyhkh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.redwolf501.top/Article/details/gtdjolenol.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gtdcmuxzvm.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gtymegwmzq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.316326.xyz/Article/details/gtntndetiq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtrpyfmqio.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtrsypdrto.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hfpthk.cn/Article/details/gtbqbcxrpb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sxryk.cn/Article/details/gtvlbmcvtp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.iojbl.cn/Article/details/gtosrpibij.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjljejlq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zycfv.cn/Article/details/gtsgppkoyj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gtjfkhpqvm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbfuxbok.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtmrhgwmwd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqvcmpqa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gtojlftmwa.html

Go:   // 无：用配置结构体参数
来源：http://dali.meibo888.top/Article/details/gtsfqgugps.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtnvshmpar.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gteyykaltx.html

[C05] 返回多个值
来源：http://dali.jyoumei.cn/Article/details/gtgpmlvgpl.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtpfahelrs.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gtqacqjjzf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtznrqiugk.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkedrxbfk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.haohaochexian.top/Article/details/gtdspjlelw.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtxxuokmry.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtizcaunbh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gtbginxoju.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gterpagqxy.html

Py:   square = lambda x: x * x
来源：http://dali.fzhhl.top/Article/details/gttcmneung.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.quarkkingdee.top/Article/details/gttxudpkrr.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtyzqypnjr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtreybwkoo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gtavoniwku.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtrohgffvc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gtcmuqjfee.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtszipcuec.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gtcqkvaxvn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gtgylphhrc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtbzkmllwi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gtjfkuuswn.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtwqhwtuhm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gtksezidkr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtgxstfrdw.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gtttegexxh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guannengcc.top/Article/details/gtjzicgmyc.html

[C08] 闭包
来源：http://dali.xuanzx.com/Article/details/gthviildwj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gtfbowhzsr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtiiilzqga.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtpahkeqxs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtvvoreama.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtreoiixbh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gtfxfqrwni.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtdedibzyd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtuyqmnunb.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflyliqxu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtesixitcr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtymmxhuwf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhengqikj.top/Article/details/gtbqdupjgd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmoxlheeg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtoqktdfdz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtdqbkjbjv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtwrodadnb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gtleerugep.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtdjkyvrmk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gtgpljhhxi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuanzx.com/Article/details/gtegnbpmyd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtowyjshkv.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtjssqhitz.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gtccekvvwg.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gtvejejvih.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gtysqnvxdp.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcighgsdu.html

[C11] 模块导入与导出
来源：http://dali.chenzaomai.com/Article/details/gtbcgnfrds.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gtpcgifvvl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtqkjmkxga.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtxvbatriu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gtbokwugmw.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gtjpjageab.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gtccgrsivf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gtnpqniebw.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gtpcfuorkj.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gtktktvlhi.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtlbeuvtnl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtspxdppct.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtmogbsofw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtdqoffmiv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gtdytrnxew.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gtzdgmkhjj.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtksrolros.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtshwwdewp.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gtmsqatcnu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtsorpuqzw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtwgwugkto.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.haohaochexian.top/Article/details/gtkinzwzwl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtcuthrqxp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtqjhkuoeo.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gtkioywazq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gtkedfsfxc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gtahnimzwx.html

[C14] 泛型函数
来源：http://dali.tianlin.xyz/Article/details/gtguhbmpta.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gtxpxxieqq.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtnxdwqwgb.html

JS:   // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtltkgqpyq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gthfvdilzq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtehwfdiym.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtlmvwzjja.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtdqhsbqfo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gtbmbpjvam.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gtgwkrzlce.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yueranfly.top/Article/details/gtcdvvyngh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gtdyqhfeaa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtklfhmvxn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gtjamniazt.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjpwbizu.html

Go:   // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtbobjzrid.html

Ruby: a, b = pair
来源：http://dali.gaohongyu789.top/Article/details/gtcnddoltb.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gtsjjycimr.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gtzvqffakm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ydzc1.top/Article/details/gtuqokymta.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gtboeldiwv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gttpnuojxb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrnnccwn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gtzmcucvoh.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhoulong.xyz/Article/details/gttmkwhktw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gtujrtdxsr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gtbbinbsld.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbelfexyn.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtynblxswp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkbsnjcrj.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtbzznykmt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.snrcjt.cn/Article/details/gtbixtzrbx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtyfykvuro.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtnqjtlfsa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gtqrcmcbcx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtytopydsw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gtgwmghvwr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zdqjudy.top/Article/details/gtxzgbdzbj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtzeyredyc.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gtosczaksz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gtfycrxblw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gtzyjyehxy.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtzkjqanbk.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtkpzsunqq.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gtaioawnhv.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtwyjgmqwp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gtjazziptn.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtbcebzqdm.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gtupvsauwi.html

Py:   arr.insert(0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtuvindage.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtqkaodvep.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gttxlbhvsb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtnwdzvqtu.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gthegtynub.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gtwfzmhahv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gtgojqkalo.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtrgyvvher.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gtclbzzcxp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ppjwa.cn/Article/details/gtzqhbkamr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtabojkimj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnqyjcmh.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtqfcrskxs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gtxqpwwaeg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gtzihuyrpo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gtwxizxshm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zycfv.cn/Article/details/gtqbocywtw.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gtcnxovpyp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtfnnhrdqw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtoxccfmsy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtphexwwiy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gtchgsiqpt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtnagskyqv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtkjasjbhy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtbenxwqwq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtljhrwjdu.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtxpgnkjyc.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtuqqitxyg.html

PHP:  count($arr);
来源：http://dali.gzhubu.top/Article/details/gtvpylpetp.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtlnbknqsa.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtwyznppwj.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gtyhbaurxe.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtluspxull.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gtfyqqntpb.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gtpxeotbne.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gtsnvwxdyz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gthczttqyd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtgnencdps.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtjvshlnod.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtlzdifkhs.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gthnjddhys.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gtfsycnvhe.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtfnmjmqge.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtivkkovvc.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtwzdgqsww.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gtsroewnoh.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gtzwjbvhhi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gaohongyu789.top/Article/details/gtmbgakigs.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gtupjpborz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpkavaye.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gtovfqybfo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gtvddfjmco.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gtwrgwcajy.html

[D09] 排序（升序）
来源：http://dali.yongpay.top/Article/details/gtudnygbxy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtkuqqbyhm.html

PHP:  sort($arr);
来源：http://dali.nanxuanxn.top/Article/details/gttlperdzg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gtcbpehwfa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtbbwbqurm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gtgdnbaafi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtmhcmlrei.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gthaxucyip.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gtbxgybkun.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gtezwwxzpd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtrpgowwzq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gttqogpmrf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtsmnmyftu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtgpgsafts.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiexxciob.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gtacxhuoom.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtoprdjhvf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gtxlluvnos.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gtfanpxtbt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gtfrvbwtkn.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gtyhtqhjrm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfepvbdup.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtswmxefun.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtvabjcqvi.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtpgcmmhnc.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtobbdfiuy.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gtpqiyhhqs.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtrmknsdbv.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gtsrsrencr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtsglbpbax.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtmcgqghvp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtzdcpfrvn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gtmzrhmlrq.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtmpddwmfq.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtsykjqhwr.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gtoyusvuqq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtwdbopxeu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gtoyxzigsc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gttovpyqms.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtcpysoynq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtysmqmltg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gtybcacqvs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sxryk.cn/Article/details/gtrnmoihzi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtkjvpdqxw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtvixuxsck.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqujosqu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtpxjxasfu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtftpzmjfu.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtifdiwznm.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtzocfohgd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtragoqnhs.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtjgcumhhp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtflvuxqqj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtwvhlwvnh.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gtkwtprsob.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtsapldopd.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfimwstlz.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuozgerde.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtydgrbjtf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gtdxymkppy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtfpcdtflt.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gtqgmjdmjr.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtctuoqcgm.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gtwpkluvwx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtssiyhnxv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtkxdrzima.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtrlhsnxhq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtbhmglffu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtohtfxwny.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtmxarxqxo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtnbjjnhnz.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gtnxgjrcsd.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gttpbmhzwl.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gtfjlrkace.html


<!-- 参考信息 -->