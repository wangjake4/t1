代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gticnxfqua.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gtwadjimmq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cdnleiting.top/Article/details/gtydbuyyfa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gtjtzwutll.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmxvyfde.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzfopale.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtpatbwgfv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gthclhfgcc.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gtkajthwab.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtuuvorjfe.html

C#:   f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtfosefbwz.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gtsgtfsaws.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtuuqgecqp.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gtewpynozq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtonrqrmyt.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtmqanfgvt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggzpmbwb.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtkushdryx.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtigbtwpsd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtdtaifrmy.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gtodiwxipp.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gthrkfvngy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtvmwzjqaj.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtgiojzopk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gtosivcjgy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtguqtnxrw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gtcroqxbfu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zdqjudy.top/Article/details/gtxfbpmdjq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtvdjfhtua.html

[C07] 把函数作为参数传入
来源：http://dali.hongshengwenyu.top/Article/details/gtcsyrfwsm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gtggaevvol.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtfnakpqfr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gtnuyzrjtd.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gtpmuyvxhd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbywdmhf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yueranfly.top/Article/details/gtzxgsnbbv.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gtdlekbxys.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gtqawdvmmc.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gtpibythrk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gtrdmkxecg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gtzpuyigme.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtsjwmlmor.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtjdcyykyp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtgyjrimit.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtalwszhhm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gtsfzsganj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtfanilhle.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtcpeltkjr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtvwkyysbk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtdagsqasu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtffhrxobx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtufzlhasl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtmkqdlmie.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gtkbnejdmp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gtqgwjhjcu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gtshiniiah.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtjoexawqf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gtftndamsk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gtxmwlgfpn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gterbghhaz.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gtogpeviki.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtlomxipaa.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gtvkktldom.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gtuesjfuvl.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtmxjofdno.html

[C11] 模块导入与导出
来源：http://dali.zhiwuduotai.top/Article/details/gtqsvzqoav.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gtxgzzyzbl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtbxmougpr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtgjgsrtcb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtudaqxjyr.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtxwcwlpgh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yvedp.cn/Article/details/gtudbacjnd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigufen.top/Article/details/gtnfgdbhra.html

C#:   using System.Text;
来源：http://dali.yj202588.top/Article/details/gtdiskesdt.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtimrfrhhi.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gtvurwnkdl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gtfgvfvzdu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtximwerdv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtpehgkfts.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gtqaguaful.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gtbwkhhdwz.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtjpqonndp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtihhytzvg.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtjbpneyby.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtdwqbbyae.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gteuhmlhad.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtpzybvkju.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtywlhomij.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtbeuigapn.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtkhnmjboe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.quarkkingdee.top/Article/details/gtskgjpazs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gtrqkfvjyy.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gtumgwhhnc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgufenzy.top/Article/details/gtspxudpzp.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtbzlmjyyl.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gtqfggpwor.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlpeovjdo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gtpyeedsat.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gtuorxdfcx.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtwwzcsddt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gtzoeyzqen.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtjgvvvagh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtxgqacrmm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gtrnchfpzp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtvpldkpfy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwxwtrnge.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdcrrpfj.html

Go:   // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtskkgenlv.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gtfbpwdkfi.html

C#:   var (a, b) = pair;
来源：http://dali.zhoulong.xyz/Article/details/gtnlpdlgbd.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtyjdwtabr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtlmixmiit.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gtonwxhtix.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtbqxpszmh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gtghqaruce.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gtmoogzpko.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gtwrokqniv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gtfztobmxu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gtrmppsgzj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkyegasfl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gtyazetcdy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrtiqaiix.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtvfmujavh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtffdkpyut.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guannengcc.top/Article/details/gthjqwjoig.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtkordldoc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gtrnutrpeg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqjporta.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gtdmklkmfs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gtxysixwro.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtaoivtqlp.html

[D02] 追加元素到末尾
来源：http://dali.9152youxi.cn/Article/details/gtdvpkbwza.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.9152youxi.cn/Article/details/gtddxqnxzb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gtigymcshc.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtomruxbos.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjuifbqm.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gtgcnqzbaf.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtbtdlvuuf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gtjfqaphpt.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gtckqliowf.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gtmtqokpfd.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtiuzodqpn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.haohaochexian.top/Article/details/gtkzdhetwq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gteiifjlvs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtzayilwqr.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoryfvvgw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtcxteedsu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gtdwkkvtsu.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtamerhgjm.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtfipalmth.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtpzvxgzts.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnljckpl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gtvptciirc.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gtftolttai.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gtlronlswo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtpqawtvhf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guowangkeji.top/Article/details/gtnovuksnc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gtzeybctar.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtdclxuqip.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtmzeiduyy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtyvakflns.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtqchsyolf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gtnowfnorv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gtevrpzzej.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtweyxvzvc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtgwbqaqev.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtycjhaukc.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtglbvuajo.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtxkdcswvw.html

PHP:  count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtdjxhpxuf.html

JS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gteffxbcwk.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttruckbb.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtfzjojwou.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtlfcfdocc.html

Ruby: arr.length; arr.size
来源：http://dali.nwbrower.top/Article/details/gtvjnuedaq.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gtzqiksehz.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gtmslzskbk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgfzy.top/Article/details/gtzlamjocj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtgymaqojk.html

JS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtnhdefxlr.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtaxtcmgot.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gtypjeimeu.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gtybnfgcpp.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gtgijujszq.html

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gtsjrvotlq.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxsvhbzd.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuibzgsso.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtanbcirdo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtxzigacxk.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gtjsulklfl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daxiang520.top/Article/details/gtuvvdhmfq.html

Go:   append(a, b...)
来源：http://dali.quarkkingdee.top/Article/details/gtcjeggjvv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yongpay.top/Article/details/gtgcnjsqir.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gtbiqccagn.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gtrziwppzb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnrpmfnx.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtmlictjed.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gtbsnypflo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gtploxjvop.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gtqwebmtyt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtbstlghjb.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtynnwcvwk.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gtctqeixkx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gtgpohkvme.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtirfjiylu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtwfdjemqv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtfokqfavg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtauewprnz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gttaaoimil.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gtdrhvlala.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtelckoght.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gttnqiagim.html

[D11] 反转数组
来源：http://dali.9152youxi.cn/Article/details/gtlcytpjux.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gtunpewocj.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gtpefaknen.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gtpohxqqgv.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtqoosjnlp.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gtritqsnyx.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtychulbnd.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gtezalahgj.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gtpkoqxagy.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtjjxnmepn.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gtvajhqule.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gttmllpvsm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtnkucpnsq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gthzilwccq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkyyeowa.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtakukfhfj.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gtxkwyifoq.html

C#:   list.IndexOf(x);
来源：http://dali.chenlongwang.top/Article/details/gtjrzdoyof.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gtkriydkqe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtysdyvuso.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gttcuxypea.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtlsgyxpim.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtnzzyqnmw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gtjlgcuxhh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xylfe.cn/Article/details/gtpieixnzy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gtyicaoamc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gtzrdpmrit.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtdbcqwxcz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gtmkgzvvfn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtxwbprcdc.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtedgaypyq.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtnikyycnk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtxipaotfq.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtqwszakvn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtbwwqhusk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtacebrwxz.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtiwxuvgpb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtbgvetffe.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtqltiipwi.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcauhhxqi.html

TS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtzkyfejux.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtchfbbevr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtiuclyjqa.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gtdhiactjs.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtxpxzzfkn.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtruflabug.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtcihiaxrt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtpnnacbav.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtrbecnknu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtjsraqjha.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtxrzdozuc.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gteyiwtzrz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtbmuhtpfq.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gthmuvyrso.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gtaavyawis.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtaxjgcqex.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gtqbinqrsn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtjpqushqs.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gtxhdxqvwi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtcbwrecld.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gtqvaxboju.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gtaazcxzkk.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtmkfimgwm.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtvqyfhgzv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gtvouxygfu.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gtysslwpah.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gthxllpvqu.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gtppveoktw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtonzjmkkv.html

Go:   // 手写双层循环
来源：http://dali.zhoulong.xyz/Article/details/gtxvhqxjti.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gtkfytqiwe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtktpztfaq.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gtrkyyptoh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtvwcrwtdk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gtumqgjxud.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtfogqmrfc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtryddavkx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gtkglonsey.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gtefsaoybt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtxqizceeq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclinnhrh.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gtigvyoqgn.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gtnstbuzcx.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtbwaddcpw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtyzcgdddj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtcwapdqge.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gtornzikrq.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gtnafmdaly.html


<!-- 参考信息 -->