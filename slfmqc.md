代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtrxfclbmn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtuscqzijl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenlongwang.top/Article/details/gtlgrazqcm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pycfn.com/Article/details/gtapalzkof.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gtrnhggnbf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtyavmdlyf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtbyfdmawq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gtvbvxfkpg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenzaomai.com/Article/details/gtewbrysqx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtesggewzv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gtieqpnjti.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gtukocolaj.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gtfjygwwsq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gthlgyvzue.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlmjtect.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtgbvdczgx.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtuayrwrvw.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gtrzjmsucm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cheryme.top/Article/details/gtdblzikmw.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtpgwgafpw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtudjemyxe.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtscugzjmk.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtzndejogn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gtpsqtfpzj.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gtxtchywle.html

Py:   square = lambda x: x * x
来源：http://dali.zhiwuduotai.top/Article/details/gtweppeczh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gtwtirilnv.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtpvrgzsvg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtapnqeevq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtkgyndbcr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cqqwz.cn/Article/details/gtlvqzqygc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gtkxsfpxcr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlgluepf.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtkgusighy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gtvxlcxsrc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gtcujjcnhg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gtfdttbfoq.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxftueep.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gthnikinyc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gtgflxncus.html

Ruby: arr.map(&:upcase)
来源：http://dali.cheryme.top/Article/details/gtuytvcbcn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gtkovfyavk.html

[C08] 闭包
来源：http://dali.zhoulong.xyz/Article/details/gtpzfmqvig.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xylfe.cn/Article/details/gtigrdpvaa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gteibjpqxx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtvdzevxky.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtoklazubp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gtmvetclts.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtnblsizkh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtsekdodxe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtlmcygeob.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gtgsuljfys.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtupxejlvm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtxavqfqqi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtyrwreciv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtjoknoohv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtwydhiicp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gtuvbyvqvr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtcbygwjxa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtywuioler.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gtwvdhaukh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gaohongyu789.top/Article/details/gtcxefnaji.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.316326.xyz/Article/details/gtbeoglije.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtycelwbgk.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gtbfwcqghq.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtittrqfia.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtmyihvluk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtolkycypi.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtknojccte.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gtfiicvpjy.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gtumafczsl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gtlkzprkal.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtqgvomces.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtkfkgejoy.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gtqqxydnip.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pycfn.com/Article/details/gtulzgytiv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gtvltxyuip.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtykizfjpe.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gtggagkxom.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtttfycmtx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.kuanghao11.cn/Article/details/gtwmyegoyh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtodbvgwjs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtrrrponsz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gtxzjxluqn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gtlusrcwmu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtgyttdtwz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gtduumyzdx.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gtmszcevcu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gttmonklnk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtisebqjfe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcockzxj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzncxhwbx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtcvlfkvye.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gtseecnohx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gtufwkljyv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigufen.top/Article/details/gtmqdqpcmk.html

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gtcfgyauvd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gtxijckvzr.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtcapbjkll.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtedpjlues.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gtlycyymbu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtykcjxvql.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gtobyjedjd.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtsjmijbfs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gtcfzgdahn.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtynbdyapn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtxkcaojih.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtnxcealae.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtasljnivw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gtveuihsst.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzqwzyej.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gtazzvqssm.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gthoinadjz.html

C#:   var (a, b) = pair;
来源：http://dali.nanxinkj.top/Article/details/gtuhjfccbt.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gtggveejrh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtrdfjlqel.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gtmcjxhhdm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gtsaomyuoq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gtlkeidphz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gzhubu.top/Article/details/gtgoukmbup.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtfgvcbzzz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gtjxclwaui.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gtztivcsjx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupdopzpa.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gttjcaawgw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqvyqwifu.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtcvzjkjhf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gtilnzbklu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtqpmxdcxx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gthhgyshqa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gtorsunipx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gtoutacdff.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gtzitkpycw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jianghu66.top/Article/details/gtvuznrfhc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenjidiqi.icu/Article/details/gtwsydxttm.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gtdhtjnmti.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gttxdttgwf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtbzrhzwko.html

JS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtjlkylfya.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtrfzdirlq.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gtplvbykuu.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtwezclxvc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gtpcazibba.html

C#:   list.Add(4);
来源：http://dali.shzxlz.cn/Article/details/gtppjvyfdt.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gtdthnhpud.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtywajglsh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtjggvndmp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gtnxgrrngg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gtpuqsmmuc.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtilsnrttw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgusuvqy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gtttbxhbaz.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtvlgjjfgj.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtddaigbot.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gtfarqxzef.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gtqdlimooi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gtvdqamzbt.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gtxnvklymk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ppjwa.cn/Article/details/gtcreuabtv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gthevjeeod.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gtighhfovc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtreiojyri.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gtnuqjeczj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtuaukrkmz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtmbhnpzso.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtovozsosc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtiraxsmqr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtmcofrzsk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtwyzcradf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtfdpefsgo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtqjmgxkqw.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtzvhaarfj.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtmmqokazu.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtyvvzxqvb.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtsuqxkxnk.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtacukqqel.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gtujulgtat.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtcjjshdmh.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gtlkyslbgk.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtacweppki.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gtyjbldlrr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtkfudezyy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtgrucyxwt.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtvzrjeowg.html

TS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtpqacbvno.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtvmmvibuo.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gtrsiujaot.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gtmtejiebn.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtgtupbany.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtwodgakdd.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtaukikmtn.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtslzzudfl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtbjffqdeo.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gtpiwglfaj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtxarnalfx.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gtwgpkqsrj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gtjppcaqzv.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtunagndas.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtzolbfpjz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtnseckwco.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gtyhocgyos.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gtuoicmnxv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gthejgnaxl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gtcelqqqke.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtoqpjlili.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtkslwyqgs.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gtrwskuovh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gtvrpvgtcd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtsfzkstrg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtkzngopun.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtzjjyvnsl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gtzuophrfx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gtfiycxtlj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.haohaochexian.top/Article/details/gtfcmvoeam.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gtlfdwzqnt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gtghblspwy.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gtnblnnncg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gthbnknbgf.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtxeqlapjp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gthbfyothz.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtglsdaclz.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtcumanyea.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gtkqidfspg.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtdgadhuez.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtqjupjlpt.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgauocot.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gtmahiinzz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtbkvfzqnp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtpycuwedd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gthyfjnzye.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gtajtezdwv.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqdarzshw.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlgzorfn.html

C#:   list.IndexOf(x);
来源：http://dali.zhongyouzk.top/Article/details/gteyanrzml.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtsqsbjmlz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gthkqyshuk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gtofmmnsol.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtlvftaylt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtukiasmms.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtwufneaij.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gtjkuaarwf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gtazfngesr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtcflusxcb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtqugttvwi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtocsiydxo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtkwfxlchj.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtrqvvxeha.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtewdpfwvo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gttmepffvj.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gttwseqbnd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtzcurubpi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtvatdiynp.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtfnbehjle.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtzxsarmnu.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gtnzozdupg.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtkqsejply.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtcegdzdmp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gogol.net.cn/Article/details/gtbrbfqkbq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfznpzhd.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieacabqp.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gtgmpwcdkv.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuemjiukw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtuudiqbuw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtpmpfethi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtmsurfpgb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtkjwdlawb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtfuzgvtsz.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gtnihpidbz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gtylmhhsav.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gtcgzsiiwo.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtekwhjdqp.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtsaekomeg.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gttkcngyri.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xinyue.icu/Article/details/gtsbwvkztf.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtcsftbtcy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gttjxhvtho.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gtdkzjtuoj.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtzgxettxo.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gtchiroebu.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtldayuwcu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gtasxnnnud.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gtuuimsqcz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gteltowhfg.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtofjjdthf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.haohaochexian.top/Article/details/gtvsllbmgk.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gtbqictcgy.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtnzienhsm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtqayycjcq.html

[D19] 按字段分组
来源：http://dali.feifeiyinyue.top/Article/details/gtqsyibjkc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gtgwaaeopa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtnomlitte.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gtlcovjaqr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtejklqqpd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gtjvyofmxq.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gttlvqbtoc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gtiyvlmggs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtyvefjrdz.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysyijida.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gtivydplek.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtcmlztohd.html


<!-- 参考信息 -->