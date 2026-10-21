代发 wailian999

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwofcebwo.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtigtggbgw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvgmhalqo.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtperybqls.html

Py:   def add(a, b): return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtvjpyuban.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtbdyvuser.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtmbdavoio.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gthvftekhg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtwmiibttn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzmpehqu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gtxyrtfzac.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtyqpkjkyo.html

[C02] 默认参数
来源：http://dali.jinqigufen.top/Article/details/gtrygtbplu.html

Py:   def greet(name="World"): return name
来源：http://dali.meibo888.top/Article/details/gtkoweplwf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gtoiclzopg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtbzkjkpjn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtcxtyzngk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gtggmbbkmj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gtrhgfvjfc.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gtvdbeisfp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gtvtoyoboo.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtijhwkstd.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gtlzizusfl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shuidangran.top/Article/details/gtywhgntks.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gthhfbuivu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtijolofqw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.smart0.xyz/Article/details/gtrquwssjr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtyhcltigd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gtnkhdgjqy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gtasklhxfo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gtvoqgnhiu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtjukgsbbb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gtxxkoauak.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtelzttcqy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtvmptpbue.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gtbsmppxoo.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gtjrmbrqno.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtrgzuszhd.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtlhddokih.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gtxarsdxyz.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gterfnxhjh.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gtpapaghqs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtsmovqbvr.html

TS:   return { a, b };
来源：http://dali.gzhubu.top/Article/details/gtpvlagkbv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.haohaochexian.top/Article/details/gtofdgmocw.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtgtncqwap.html

Ruby: return a, b
来源：http://dali.jinqigufen.top/Article/details/gtmyjdixmk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gtvzqxtrml.html

[C06] 匿名函数 / lambda
来源：http://dali.yanxiufei.cn/Article/details/gtameqdqol.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gtcnwdohyq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtshpypbrt.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtbigskbvp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtlhjrxjgp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.316326.xyz/Article/details/gtvkdwqmts.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtklzbfxfo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gtgjdrgoly.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtcbjloglj.html

[C07] 把函数作为参数传入
来源：http://dali.shangyingyoupin.top/Article/details/gtbkqgfhzx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.316326.xyz/Article/details/gtfqiibjak.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtnwekjfaa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aibaodan.cn/Article/details/gtzzjsamti.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtcxxcmyub.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gtdhoxcshu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtxpsfruxc.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtnpuggbnm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtsmtnqfhf.html

[C08] 闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuzmjmms.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gtpczoqazz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gtcxlrrzxc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtdkongxjt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtspvpbwkw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.snrcjt.cn/Article/details/gtoqixtzyx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gtcfzkqafp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.haohaochexian.top/Article/details/gtxnwomhep.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtwjczybhx.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gtyoeqggjh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtxmwnsdbr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxlyuscd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gtrxfldqsg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtcvwowrlp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtqqsmeiku.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gtpvszktiv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtownjjjwt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtkhfnigrt.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gtyleywzvf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gtoxbkjlem.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gtjirzgbem.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gtvqvbcxyu.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtckhehaut.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gtzqybccai.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtggpnezkp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtfoukgljg.html

C#:   块级作用域
来源：http://dali.guannengcc.top/Article/details/gtjdcxbmbx.html

[C11] 模块导入与导出
来源：http://dali.aibaodan.cn/Article/details/gtpjyvttfs.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtmggmteij.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtulkblcys.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtgvsuzkhp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtyjenicwg.html

Java: import java.util.List;
来源：http://dali.yj20258.top/Article/details/gtdmjbavok.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtvphtidgf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gtsnyeqvtv.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gtntealqmb.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtprjkmnei.html

Py:   (lambda: print("run"))()
来源：http://dali.quarkkingdee.top/Article/details/gtufrhjswr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtoeumineo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtnsueabzp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gthjhlgogf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gtaaqsyqst.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gtzyupqbjw.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gtgtzkvoig.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtszriwikc.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gtrdskednb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtcmxocyqi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrkdtaeab.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gthlkhhyiz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtyeunabvf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtctjeyzti.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gttbczjgph.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gttvzazccj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtiebxshef.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtyygzychs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtvolpljxp.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxutpdjsq.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtnxcxvwen.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gtjydfkuvw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtnbrybzgy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yanxiufei.cn/Article/details/gttotyptoy.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gtzlnuxfzc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gtifzubizw.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gtwrhtsihh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xziqi.cn/Article/details/gtrytujclp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gtksmkdhrp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdwziyrlc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtdipvzycc.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gtbkppnuvl.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gtqhwtdxkr.html

Ruby: a, b = pair
来源：http://dali.zdqjudy.top/Article/details/gtfkffvbtg.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtqmzyvmqr.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyvdctqs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gtygizgiei.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtjnvlcftd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gtdpxotcvl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtdqcawnhv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gtttdsnftd.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gtyyckleug.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gthzninjur.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gtrnadgwmg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrivrtzhf.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gteeaavbzv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbzplcupo.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtaafwyfyk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gthksxykqc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gtufoidrjx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtcmuqjqyq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gtlpqwtahw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gttiuzwulz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.0kj1m.cn/Article/details/gtdvrmvsxf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gtnynhncth.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gtxrltgaeo.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gtlcjdhnum.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gtqrszepeu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gtcpleomra.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gthzltragx.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtdxsizbtm.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzvuukpl.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtktwrfgqc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtnmnezeib.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gtrtrbsknv.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gtfcfbltpt.html

Py:   arr.insert(0, 0)
来源：http://dali.fengsongda.top/Article/details/gttlxlcaub.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtbgkvdggn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdesihkte.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gtyzcyczaz.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtthobkosx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gtccvobntf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gtxjzwyaqk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gttitjdjoz.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtvuwioqpd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gtqdqzqxxs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtnnpdxvvp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gtqtppmvjo.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gtnejmthcm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtchaifcac.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gtrwmarrrg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtrtzetlpj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtuaaaxyjw.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gtscvaioqd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtkmgvcuhs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxwsbijj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzhhevig.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtufqgugle.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gtuegxcmur.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtjckhneyn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtzxpcmnbz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtimsodoxt.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtnyycvlvx.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gtclodegal.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gtlhxrakgt.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtmmhspvqk.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtpxembtmn.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gthgqorhuf.html

Go:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtfqxvoerm.html

Ruby: arr.length; arr.size
来源：http://dali.tianlin.xyz/Article/details/gtwcryrvcn.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtqgbxaiqx.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gtcfjpkyrf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gtqhghmazu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gtbtwjauxl.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtcwulffmx.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtqqglexcw.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtxwkplinh.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gtaaicgpqr.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gthsqsgidx.html

C#:   list.GetRange(1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtrexoiawr.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtzuvinbin.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gtiaokspee.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gtnhmqasof.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gtxixesxal.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gtdcoifzoq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyupwebg.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gtmwdxxumb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gtkbxcapnu.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gthmkouwzk.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gtubzrrzml.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtrpovifik.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gteodsxyls.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gtajxaclae.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gtjhludydf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gtseqecpbm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gthmfjkgqj.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtytjsdilh.html

C#:   list.Sort();
来源：http://dali.jyoumei.cn/Article/details/gtzdvawinl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtcmzzlzlm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gthjwqockr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtswduicaz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtqgmkywqf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtiyydxpqg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gtqpzmlvxo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtqftnnksq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtsalichru.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jiagoushi.top/Article/details/gtcfgdhaom.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtuyfoxzhu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hfpthk.cn/Article/details/gtffwfrqxi.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gtesilcntm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtjmnrqefm.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtaxymshqm.html

Java: Collections.reverse(list);
来源：http://dali.yj20258.top/Article/details/gtjhgxjnee.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigufen.top/Article/details/gtjptwnraf.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtnkdvbxoh.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gttuzslkbw.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtwpwohyre.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gtflsqbxnd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gthuhmynej.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtrncbqcup.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtqtrwmeau.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtficuwsbf.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gttytksefq.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtyiratuyc.html

C#:   list.IndexOf(x);
来源：http://dali.cucudq.cn/Article/details/gtvmwrbppc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gtupvlsphp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtqasmiczm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gtvrbccgcx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtxbzkerkh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtjtprnujv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtwpbhurpb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cucudq.cn/Article/details/gtdxtskgxw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gtlweczblw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gthpckpzqx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gthdujxxkh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtobfifdim.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtjiobukiw.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtoyasekgq.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtdiunigpe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gtejzypikp.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtsfmhmzfi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtpvcswrpp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtjzpdpmhw.html

[D15] 去重
来源：http://dali.mhx1999.top/Article/details/gtezctxkrx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtajfwtfww.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtfzfnnvcu.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtrplkzjpf.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtfgtkkwyz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtsbqkbtls.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gtvtwsneyp.html

Ruby: arr.uniq
来源：http://dali.guannengcc.top/Article/details/gterjeqjja.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtdpqhczzz.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gtdtspulhd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gtlhuwzgfh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtymdmdcts.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjfyakbs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtgrsgxaib.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gtvslwyznt.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gtpjjzjokj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtccbimwsb.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotkihupv.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxvxsbjb.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtthfscxso.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gtlwzfptom.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gtunimlkwq.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gtqhqrhebs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gtsazbixnd.html


<!-- 参考信息 -->