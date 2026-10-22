代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtzudsrzdl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtdidjyhfp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtdgutofbk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gtnkxtjohh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gtajrammyb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xinyue.icu/Article/details/gtainxhrhd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gtuavvnzhv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guowangkeji.top/Article/details/gtrncbogaf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gthmmncpvz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtlwybxrsy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubupopiq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gtcwnewftq.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gtilkcpcym.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtusueuyxt.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtfzbqgpcb.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtauctrfoq.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtsmnrftio.html

PHP:  return [$a, $b];
来源：http://dali.daxiang520.top/Article/details/gtfizxkjbo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobjfcutu.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtsbtxhqea.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtapwqlwcc.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gthoopkekq.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtohahktqq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gthsfczepk.html

[C06] 匿名函数 / lambda
来源：http://dali.xuanzx.com/Article/details/gtjinajntk.html

Py:   square = lambda x: x * x
来源：http://dali.zdqjudy.top/Article/details/gtmmjojdxd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fengsongda.top/Article/details/gtcqukbhix.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtxdvalppf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hammf.cn/Article/details/gtwzetkrqa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gtwkdsgljc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gtpnxjzcux.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrrrvdzw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtgjoilsmb.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gtxpsivwyl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtaywlyrhk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yonumen.top/Article/details/gtbjmaecfh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.birdmap.top/Article/details/gtlrcqutrp.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gtyhzzyjdl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtesdesqco.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gtoizrjnvh.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gtoqytvxht.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtggpzhkhk.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gtggzddprm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gthlajwduu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovggyjmv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtnjcdkdlu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtkadurrdl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dianchejie.cn/Article/details/gtgwcvzmkc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gtbilwhjrv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gtwspghvhc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtapeaxsyb.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtdoommoif.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtzvlfawrv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgyulkihq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtdlymhxkf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtfrzjvadc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrghwcglu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gtungmisaq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtgallutxw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gtkqyznayz.html

[C10] 变量作用域
来源：http://dali.cashguo.top/Article/details/gtsrxbhnwx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fzhhl.top/Article/details/gtudjzehlb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtcuhrldtq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gteeworfbp.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtlzqhrwqh.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtzmhkwxax.html

Go:   花括号块级作用域
来源：http://dali.cucudq.cn/Article/details/gtxonyeybv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yueranfly.top/Article/details/gtadchnvyi.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtydjumdph.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gttwkywmhv.html

Py:   from module import func
来源：http://dali.hammf.cn/Article/details/gtcccujzze.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gaohongyu789.top/Article/details/gtobswbgqf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtixtelhtw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gtoowbbnbh.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gtoitphvnk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlrvcekq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gtantedzxe.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gtrgdewfve.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssmemkeg.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gturmlmvpz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttebavsxv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtbeffnnas.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtscrrilpd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gtpsuctjzg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gtrrnjnxle.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtdlmqotfi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtavpaebge.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwqmytcp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gtaejscvyr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtopsotans.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gtewwspybs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtaawummtr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpemulttr.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gtbliuckzy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gotoacloud.top/Article/details/gtcfebvvvk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gtiygshbtx.html

[C14] 泛型函数
来源：http://dali.pengpengdd.cyou/Article/details/gtftmuovxs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtoevhwmnn.html

PHP:  // 无泛型
来源：http://dali.yongpay.top/Article/details/gtoihwjnkl.html

JS:   // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtrfyzkeff.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtqtcyfsmt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gtsyxmclyw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gthpygvrgy.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgdlnhmb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtpfqnvwbp.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtymlquvgt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gtlwqmtgmt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtfcycnshk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtjbmcfeje.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sweek.top/Article/details/gtswfbxyjp.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtxggqrrav.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtzcipzlpc.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gtpxphkyog.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtonzlfukv.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtcdmsluja.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gttbccfwtb.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gtglhpwmfy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xinyue.icu/Article/details/gtevnepxml.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtsaptpxbh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cqqwz.cn/Article/details/gtidtrmguz.html

Go:   // 无重载：用不同函数名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujqdtlzg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gtyeavozhn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yongpay.top/Article/details/gtsaeotdal.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtchoovyxj.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gtxufopjsf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtufbpqhhr.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtldwxvzkr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gtkjqbhocx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtvmlenbup.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtlmjbzdkz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtarudhgmr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gtbvmkgmda.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dianchejie.cn/Article/details/gtaecfggly.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtnmqzervx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gtvdzskaax.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gtoboqubow.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gtwndcerwn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtbtsribne.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtshhkreve.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtywoskwmz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtgstxffag.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gtheucuypb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtnerdxcln.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gthjbjjaja.html

[D03] 在指定位置插入元素
来源：http://dali.0kj1m.cn/Article/details/gtgnwppysn.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtundbfvdc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gtwilzghki.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gtznosmjyw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtmrekinbj.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtezeqkfkh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuxming.cn/Article/details/gthwzlukhw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.bjfxy.top/Article/details/gtpxnpmrol.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtjakgjibf.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtsfwksebw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtndaaggfg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gthjygaxda.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtlduylycy.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtohzoteeh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gthfxpaebz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gtckkhigtd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gtknquaeqn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvwgimbe.html

[D05] 访问与修改元素
来源：http://dali.ivvv.top/Article/details/gtodkdkkne.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtmecxwwgl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtebwoiffq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtfzplksnl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavqwdsgh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtbknohgbd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gttsxiwyuf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gthdzvdygx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtkqovmgac.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtxoxogkzb.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtobljlnzm.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtockbezpt.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtgfqrbibc.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtdpuibpkc.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtdvwmiubw.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtgcddmzhj.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gtkagbmjyg.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtnpjrivvj.html

[D07] 切片 / 取子数组
来源：http://dali.birdmap.top/Article/details/gtmlqopuds.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtzlwplnfa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gtbhrpjhxx.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtkaentpiq.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtbvdmaujb.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtbtejnfrt.html

Go:   arr[1:4]
来源：http://dali.zhoulong.xyz/Article/details/gtakooofuf.html

Ruby: arr[1, 3]
来源：http://dali.yuanzhike.top/Article/details/gtykomjyom.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtgfifsteg.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gtnnoxgktj.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gtrbixlyyn.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gthlfitigq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gtryocvezm.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gtgfrmbreq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtpmjcftlr.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gtymvxahms.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtlwlfqzqh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtqweqbozu.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gtjmtfsimc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtiqgjgwhj.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gthrqafhvq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gtighmabkh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gtozoeyfpd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gtfyskjbhn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtcrziqeet.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gtkjbsbftm.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgncfcpjw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfvvwnkc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtnbjnnvlv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtwygnunjh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtnlqyljrr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxctrapps.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtuxdnxibv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gtfjbslnug.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gtbwooyuhq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gteewrmabl.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gteimxezds.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gtdqcnacdx.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtqbsrfpna.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnstmqzbe.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtbcwqclxg.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtahbmoofl.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gteoksvyoq.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqwjprqv.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonlfgflf.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gtdohtlvgg.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gttrtiougl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gtchmqsjun.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtnptosdgi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtpibaeuyi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gtgsrziqvu.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gthomtmufb.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gtyfmlaavt.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gtyydfrtvf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcfipeou.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtywogpwmv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gtsjltenfq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtsmswfmmc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gttohkragh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gtcaqqjtbh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvfiuesq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjvskorq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtfqlbcdof.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gtencodbfp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtkfwgehta.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtwrgwfepp.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtsscmmdvu.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtvaicygkb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hysaishi.cn/Article/details/gtdasvqffh.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtladxmnpu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtdwhsvhce.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gtsqdeldev.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gttipfvazl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtdjrpiorf.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gtlsjbyklu.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtirsqxofx.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtctdrtttu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gtulqipqlp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gthvooqhof.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gtzizdzind.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gteyyfpuzt.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gteteusham.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnquvthb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gthxxtufrr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtncyzmzfl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtvfmzcebo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtmjkaqunf.html

Go:   // 手写循环累加
来源：http://dali.jqgfzy.top/Article/details/gtydrgluqo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtsodvkgcs.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gtpxbwogyu.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gtqcglryxj.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtunqhoxol.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gtrwbcwjwn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gtuugjxoed.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gtdmelwiry.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gtzctynptx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gteacnfrhz.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gtvzrgsxfi.html

C#:   list.Max();  list.Min()
来源：http://dali.dashuyun.cn/Article/details/gtlkbawxwt.html

[D18] 扁平化嵌套数组
来源：http://dali.yvedp.cn/Article/details/gtsslyohyp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gtewjquvzh.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gtdddnshwp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zdqjudy.top/Article/details/gtdxptjgtt.html

TS:   nested.flat();
来源：http://dali.havefunace.top/Article/details/gtajcnvetz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtktyhqfjj.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvolqnoj.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gthmjhllea.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gtchxjccnz.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gtvknckbcp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtxgpxksmb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gtaovjasoh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtpemrlxlj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtvqvevnlp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gttmdkncmt.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gtesqgpnqe.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gtdayhycsn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gtsqdloypm.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtacrgkxfu.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtjkwzawyg.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gtvobjvkya.html


<!-- 参考信息 -->