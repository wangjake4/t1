代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtruhmjizq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtjscwfnuy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtdvrzepmg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtipuzitue.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtbmtwixgq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gtjeeqrhdl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gtnkgqnzbk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtdlpkgesb.html

[C02] 默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtrbaidfof.html

Py:   def greet(name="World"): return name
来源：http://dali.zhoulong.xyz/Article/details/gtkskolyge.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gtzsdmgohv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtsipduyjl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtvlpyocrv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gtmhmsaufr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gtnhngjlor.html

Ruby: def greet(name = "World") = name
来源：http://dali.quarkkingdee.top/Article/details/gtymggibhm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtaslglroe.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gtxuoithaw.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gtdfhlncla.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gtqlzogzmb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtgpfeyhbw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqchrwguw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258888.top/Article/details/gtwjthwydb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gttohhyvoe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gtwmiwdtye.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gzhubu.top/Article/details/gthkpjfkku.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gtbphyquzk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gttvmhjffb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cucudq.cn/Article/details/gtnvpdgbaf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtseujwcff.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gtolngkhnq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gtfrseetie.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gtkphncyly.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtzuqpfxss.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtrnkfpmdl.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtbombfhdg.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtolhmitrr.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gtdvkfiand.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtafxgwreo.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtdsipjvyz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.c1oappe.top/Article/details/gtufztjhjm.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gtenklhqoq.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gtzkrvtkwg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gtdsuvtxqs.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtuxgpezbe.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gtykohhtow.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.smart0.xyz/Article/details/gteyqjyndr.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtiwncggqc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtrpvblfhb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gttdfsxizo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpmqlexn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gzhubu.top/Article/details/gtjfshmtbq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtonmugsas.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gtwjngdjgt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gtxrkpkxiq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtzmifxkoj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gtiongaidk.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gtnjshuklb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gtnicnjutw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gtgajhmxka.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gtymxvhfjp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.quarkkingdee.top/Article/details/gtjvijfzms.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtlcktveec.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gaohongyu789.top/Article/details/gtwfdsmouk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gtusbtodrd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtsiasedaq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtbdihfide.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gtmpnghktx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakhjeowu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuanzhike.top/Article/details/gtpyplxmob.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtwzsxqxbv.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gtfgrgysgr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtbwfazbyw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgqcvyrjs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtjfpgvibu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gttzpecahf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtcrkdccsx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gtfasgbawk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtuuqdocyy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtoflaydjz.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gtwiuxfkbb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gtvhhfahxa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gtoiywhuxe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtnzfpkyka.html

TS:   同 JS
来源：http://dali.ivvv.top/Article/details/gthyhpjabx.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwoziyfb.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtvbvivtji.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtbttvnefb.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtnansphmg.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gtnzmsdrmg.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gtucokwpxq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sxryk.cn/Article/details/gtkdusuhhm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gttslctahn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gtfjjfktku.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gtqrsjrqpv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gtginfqhyz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtsvoqvjqc.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gtrgjyanig.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gtlsnecblh.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gtfjrhybha.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtilmauhfp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtoconnvjm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gthvfgzzps.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hywenlv.cn/Article/details/gtpgvbrbbg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtfbgjqorg.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gtbdwpnpki.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guannengcc.top/Article/details/gtfxcobfzz.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gthlzeladd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gtxhkvygzl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbiioyruy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkqcxqol.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtteshvbkw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtfehvzlfs.html

Go:   func add(a, b int) int
来源：http://dali.snrcjt.cn/Article/details/gttrosvmvo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gtxuqdeipi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtwralrtut.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfmodrel.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtntnrhjvv.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtkeqrzkjf.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtjjqlmsen.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigfzy.top/Article/details/gtqbljshwy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtpdpmvjzk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gtwpzvosyi.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtocwlodye.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gtlhblaqig.html

[C15] 解构 / 展开参数
来源：http://dali.yonumen.top/Article/details/gtwviwuhpu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gtzwcamhbw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gtzxgygrnp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtricdrzan.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtrslhiraz.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtomvqcwce.html

Go:   // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbmqvjsn.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gtdlcmqezc.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gtzeaobvdc.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgepesjsq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigfzy.top/Article/details/gttowfpnts.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gtkuqcjjyy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gtpdquqabn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cashguo.top/Article/details/gtlbdcthbr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gtasqapywj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gtfxcyoils.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gtsuayhceu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtkwqlwxpa.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtckmtmgxe.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxzwqznl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmrktwvhu.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtizyqyjpk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fengsongda.top/Article/details/gtouyzmdan.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gtcvnqdwna.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtzaywdzau.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gtbuatgmjj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gogol.net.cn/Article/details/gtpqxjljgs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shzxlz.cn/Article/details/gtgesyndwp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqonuzedh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gtnezhhjtv.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gtewlsdsch.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtyouuyvar.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gtvrhiwkyn.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gteqwmcwhz.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtzwrqsjdv.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtpzailmhq.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtoyvmoodl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gtfcphpews.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gtmsubfanu.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtyvmdidwn.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtultrioni.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gtitoahovu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gtmdxjhduw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtknwomfbb.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtvbbntseb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gtxkpymzdj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gtvspfzblu.html

C#:   list.Insert(0, 0);
来源：http://dali.cashguo.top/Article/details/gtqozeqgns.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtdyrciiap.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gtmcfprmgm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gtqzblride.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtxzlkaukh.html

TS:   arr.splice(0, 1);
来源：http://dali.cdnleiting.top/Article/details/gtwsbgdopr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmemsnxfg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.meibo888.top/Article/details/gtltlxhips.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gtkprmoftw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtwkoepwed.html

[D05] 访问与修改元素
来源：http://dali.wangshuangyany.cn/Article/details/gtvkbqzmah.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtiflmefau.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtplgtyqqu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtezsmsbxa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtgzslediz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtmmejcpym.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtvzliavjm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpdlccfu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtsfhicqwl.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gtbqyfjmwo.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtysgnfqxy.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtoruurdsg.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gthzuzzusx.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtrppxwzqi.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gtpvpesqii.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtrbmzoxmw.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gtkyztfaag.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gtynmdeuij.html

[D07] 切片 / 取子数组
来源：http://dali.ydzc1.top/Article/details/gtqqqfcqkj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gtczfbbueh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gtltopqeem.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtfdujoqou.html

TS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gttxowhakj.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gtuuhuvabl.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gtxxmisaqy.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gtqzbcenlq.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtykksdobn.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gttgjxdadu.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtuouagemo.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gtwuuznhlr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtdjpdzeiw.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtxkbusqtq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtgeazgpae.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gtmdrsznlk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqobxueu.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtwqgfaqma.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gtilxjwsmm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtzfiwehyn.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtnzqzurac.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtaqsslwyh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtfvcifbae.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gtcmqljsqe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtuuynuqju.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtgvmdvjxo.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gtogeyiipk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhiwuduotai.top/Article/details/gtmcwwtsem.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtvacsaaov.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtkqkipqqm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymrrcvoz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtrsccltwl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gtiuupotse.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gtzbgejnkw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gtrjahcldy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gtoxcvrwnu.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gtszwrdliv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gtqowwqmau.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigufen.top/Article/details/gtjxgplaqw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gtqekyoruy.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtxuqwtpdh.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gtlgvdpsmr.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gtolakblqz.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gtsbrqemko.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtpijvzpdp.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gtvxmwhitg.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gtsywuyvvl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtjuqzlevx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gthzzoldjk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtvfyjymzp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtwmwakyas.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtxengikjv.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gtfibmwfaa.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtyswqneuc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gthpogmgfh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtvbxserku.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtwpmortgp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gttwxjxoya.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtyyavgadb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gttvdjcqil.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgeugkoe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ppjwa.cn/Article/details/gtyqqblwkn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gtaabusakp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gtvgdrdaab.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtoelhgdpp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gtkcezmqjn.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlmvprxal.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtpjystnki.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtifrirekj.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtnyumisbw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtblyftzxc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtmwnpymku.html

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gtwmplwvdb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwgzvsjt.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gtffzvffff.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtvaiabwjv.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtclctcznj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gthowtjpme.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gtrcoumnnx.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gtsrmewjxj.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtydfuycnb.html

[D16] 求和与平均值
来源：http://dali.0kj1m.cn/Article/details/gtpozyloqy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gtnlduzptj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gtjskuqnbw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtindtrpay.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtaqlmktmx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gtaxxlacfa.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkqnjxpm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gtrhvzmthe.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gtjdhmqvue.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtbgdhjfio.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtsynodgix.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gtwdlucdss.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gtwnhmzedv.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gtnoktakua.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtctzaltrb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtqqgkpcvj.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gthgohkhlf.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gthtjwsjfl.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gthimfhlmg.html


<!-- 参考信息 -->