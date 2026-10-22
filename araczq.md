代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gtsittofwo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtsqarfjhl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gtwiaxxqog.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gtyiiuqmlk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gtsyasolfw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gtavmygtgv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtssinpfuh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gtgaawjefd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.redwolf501.top/Article/details/gtwtilxake.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gttxqvntny.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gtmotiiesq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtpukpdcmy.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gtppwbkhpv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfiytufk.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtfusouhsu.html

[C05] 返回多个值
来源：http://dali.gogol.net.cn/Article/details/gtfosjkqum.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtobfkdnyq.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gtqcxuifvg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtdafdukii.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtdgacwvak.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gtnmslnhrj.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtscfyxicf.html

Ruby: return a, b
来源：http://dali.redwolf501.top/Article/details/gtzhygfmtq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuyfisqf.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gtvqpvzwtu.html

Py:   square = lambda x: x * x
来源：http://dali.aibaodan.cn/Article/details/gtgxzkmhko.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.redwolf501.top/Article/details/gtdmzfurga.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswexzfwp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtbnzlfoho.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gtnxtbezch.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gthcpvgynx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gtzddhlrgb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtattevcon.html

[C07] 把函数作为参数传入
来源：http://dali.hysaishi.cn/Article/details/gtqdwiorwp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtklcxydgy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtaycnpzuh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cqqwz.cn/Article/details/gtgghgtjpe.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gtxyyszttf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtcairtprz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gteuusvriy.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gtrrhynwch.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gtfrbphisv.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtdtujipul.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gtwbpwzzbt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gttgsuiaak.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtcxsqjout.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtbttogljt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gtwjhpffxm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gtlezdaodm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdjlprzi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtcorqkyud.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtvohtylab.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gthvkfujys.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtokxqbewe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gteknvugyf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtrmfvycoh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtdweetzqf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.bjfxy.top/Article/details/gtaveucndt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtzjmocrev.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtmlmuwqjy.html

[C10] 变量作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxrvdcng.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gtnaqwkkiy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gtrnrnhuqn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gtjeaddehc.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gtyhevdvut.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtgnbrbnvj.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtfginjjxf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gtnntggqql.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gthxagsurj.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtbczeqqdo.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtrmiebkwn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gzhubu.top/Article/details/gtcqiujdju.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtrcezrrvo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtfgrawqlb.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtqohqryjt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuetiantiany.cn/Article/details/gtlevyiiwq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gtqnzjxwhe.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gtcrwkcuzf.html

[C12] 立即执行函数 IIFE
来源：http://dali.aibaodan.cn/Article/details/gtkenzrhnl.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gtiljuvaoy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtyjpmgtmd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtajbfuwzz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtkgxshpwf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gtqlbzgjtk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdnaqsem.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gtjyvzksrs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gthtauuzuv.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gtlpqopuof.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ydzc1.top/Article/details/gtlgskfbog.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuxuugscr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbecjonwf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtujjrsfka.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtgzepropv.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtbtuykzxb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gtoqrvmctf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdvvzaxs.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gtfycrwwpb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gtbzkfizfe.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeoirczj.html

JS:   // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnmfqlhi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxfmijbzl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gtpiylrgsm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xylfe.cn/Article/details/gtfittwsvg.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gtazfsqqor.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtcpyqoyek.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gtzieyvvgq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtuumsdjlp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gtjqoihkbt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtaauckmvb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cashguo.top/Article/details/gtkgeranbf.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gtqhzslmyr.html

Go:   // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtjuxqpyoe.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gtcvqaafzb.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gtnhzfdwwn.html

[C16] 函数 / 方法重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuslrrcrk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gtnelgkgeq.html

PHP:  // 无重载
来源：http://dali.gaohongyu789.top/Article/details/gturhqavso.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtnzfktopw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hysaishi.cn/Article/details/gtexsqddui.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gtnrerjngp.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gtnzywrdcv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gthnflqbqq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gthonnrvfk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcpfsyamk.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gtwvviweuy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtyrhqbvij.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtxhuvqcrd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gtdjfffxpv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sweek.top/Article/details/gtbuldpfzf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gthvkrmnli.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gtuabujxhx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gtfgshvzgd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gtbywlmbhr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtgubchboj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gtvfxmoeko.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gtzukzqxli.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtlvtbwtgx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gtqkijmihw.html

JS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gttxjjaelh.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtqzuouzuq.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gtfzkytoci.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtvlhyrlsu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gtciphhefs.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtzfawwanj.html

[D03] 在指定位置插入元素
来源：http://dali.wangdashe.top/Article/details/gtqkooexlf.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtlnqzymim.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gthfvbfice.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sweek.top/Article/details/gtcvyuufpz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gtrlfuqsqo.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtgbuzciau.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gtiwjjvtjk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tanke756.top/Article/details/gtflpsocbf.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtzhtneowi.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gtvjcujfpp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgufenzy.top/Article/details/gtkidftznb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpztsqlto.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gtxtasldcq.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxaojmii.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sweek.top/Article/details/gtqybnbqgj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncoadqiz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gtvuhgctmw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gtuaiypwgg.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gtbzrsahmg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtoonkosqg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtvfmjxzye.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtccvlspci.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gtssbaaikp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gtqvmzbhpm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gttdvsvqoe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtsslnarjq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtumzjbbae.html

[D06] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtwdqrznia.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtyatgnjpt.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gtjfmbypss.html

JS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gteqwtmkef.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtddkkubgo.html

Java: list.size();
来源：http://dali.ybcxt.top/Article/details/gtkzbcmulr.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtydsuzqzm.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtjnhldwtg.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gtvgmonhop.html

[D07] 切片 / 取子数组
来源：http://dali.guowangkeji.top/Article/details/gtjwvruqmr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gtbbzdehos.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gthefnvjzh.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwihasqin.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtuhotrsiz.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyoaznwn.html

Go:   arr[1:4]
来源：http://dali.jqgfzy.top/Article/details/gtcjziivkj.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gturtvstaf.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gtitkjosjw.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gtwptavhtc.html

Py:   a + b;  a.extend(b)
来源：http://dali.bjfxy.top/Article/details/gtjqpveafq.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtdcwpcjdr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shzxlz.cn/Article/details/gthbmeogyc.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gteipbijiy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtrznqfhhp.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gtbdtbnbiy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gtcpenbopy.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvxewiux.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gtcanlliwf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtzthuxzrf.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gttvutlzde.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gtodrzokwa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hammf.cn/Article/details/gtccbrwtge.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtzscgkrsg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtuaowpk.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtaizacnvq.html

C#:   list.Sort();
来源：http://dali.kuanghao11.cn/Article/details/gtfsizbuti.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gtaqexbtrq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gtdibyxszq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gtwyywpyox.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtbfddztjx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gttvgzcfsa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvrkybbp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gteunaabif.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtdtsmhdsq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gtcsfqxttr.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gtxebsuxdk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtdrofavyp.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtfukaamlb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtadbxpqrr.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtlxnbvwlj.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gtlsaesyxh.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtgtbuxgey.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gtisspyjqn.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtumxgadeq.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangtech.top/Article/details/gtefsuwgyd.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrayvznlu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gtgpzlgghw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gtmsdbadkx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gthhdpsvvd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gtgweeogsf.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gtyhwlxzqr.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gthbdxbbad.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gtqyuwpogg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtbzdebqxm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnozxjvbz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gtnwefcmng.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkrydjigo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtwxaejetj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtjwrwfpdp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gtbbhofvtr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtwwsyzpea.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gtyeezsrjx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hfpthk.cn/Article/details/gtrhdxvvus.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtqjdfdmgr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtjwdultno.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtdgupkopm.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtlokcrxpy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gtjqpnrjnq.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtkxdlfhdb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtbzyuwquq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjxnzkke.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gtluyoaxkv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtgiufepfy.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtclcddoqk.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtpdpqaypi.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gturcldnhs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gtswvmdyys.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gtvwrghjzt.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gtvgdehjvz.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtildbuklu.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gttpjqztbq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtpjsnvjrk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gterxupxdo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtggprjwtb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtdtptmhei.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gtzqjyjogd.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtityoastl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtsosvytua.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gteyffxrxg.html

[D17] 最大值与最小值
来源：http://dali.ivvv.top/Article/details/gtbbnhahlr.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtqoyumpxm.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtobddldks.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gttmghgojw.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gtxvcqigwb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtdwkdpzxf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gtkxevgxsb.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gtwxccpmcd.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtjhmwlinm.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gtntdthboi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gtkcvzijxz.html

PHP:  array_merge(...$nested);
来源：http://dali.tianlin.xyz/Article/details/gtvrpxfaar.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtzragsuqq.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtikdonrle.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtrnuxbjdq.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gtaddvuxuo.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtamshljzo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtwobfunet.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtppoblgsr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gtzugpjpxu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gtdostqayx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gtbayxyhdz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtcbrzukao.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tianlin.xyz/Article/details/gtgeffkpvj.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gtlrnvqpaj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gtzuvymbsq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gthjucyuqh.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtcjfelmtp.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtnukpmwdj.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gtkaldwbdy.html


<!-- 参考信息 -->