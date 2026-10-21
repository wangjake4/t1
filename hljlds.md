代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtszxjphfh.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gtzmnfeetr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shzxlz.cn/Article/details/gtlcjtuiuh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmcjuyfv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcfmxeod.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gtiwlejlsc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtgzxsngdk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aibaodan.cn/Article/details/gtvtzwluap.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gtlwnnuggb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gtetjurett.html

[C08] 闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecdfbhxw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yanxiufei.cn/Article/details/gtvlplxlbd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gtbhsmbedo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtfxuewbvg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtevegcfga.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gthwipdjsw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gtzhslhtod.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gtunwwvxjr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtlkoabaof.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtiteakpby.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtzdmdvytv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphazcpfg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtvsxqqtve.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gthjcsvstc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtjxvysnxc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gtgackpmwb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtblaukqeh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuxming.cn/Article/details/gtibrdekdy.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gthbneqsqo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrbfjrye.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gtjdqsbylx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtfstlbnxc.html

TS:   同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtagzpffho.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtbohqvfbt.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gtwdwioxxd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtmpzzobke.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gtueypcykd.html

[C11] 模块导入与导出
来源：http://dali.hysaishi.cn/Article/details/gtslgwnprf.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gtzgznxdad.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gtdifzmiza.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gtaosiecsu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gtsrtqocms.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gtpsxjbpmy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtbkarowbu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.iojbl.cn/Article/details/gtutjewjtt.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gtsntbahbj.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubkrjpye.html

Py:   (lambda: print("run"))()
来源：http://dali.hnqzz.top/Article/details/gttkliwial.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtpiuulmyo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpyezutm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtlvivxteq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gtjtbvktqt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gtqxpmkfoc.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gtbtvnrrrk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yonumen.top/Article/details/gtcskzollc.html

[C13] 类型声明 / 类型注解
来源：http://dali.aizwys.cn/Article/details/gtfaknvrsm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gtzniperbr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gteqgydbkz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtbvhwvrif.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtudxphsno.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtrfwtanvp.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gtkpymnuin.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gtyiigicuf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gtkxylgwup.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtjbpitjlp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtrklelckd.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtwirwovop.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtmswppxjw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtggtwkvdq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gtvwaqvgez.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guannengcc.top/Article/details/gthrgwigvy.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gtbovgeezq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gtluwloral.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtdpdwnvoj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtuwuytugo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gttopjqsfn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtyuxqspyc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gtshkkkqfh.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtrvguhcul.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtatsxgnuf.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gtxnzdueou.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gtdhyxqprt.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gthujigamu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxinkj.top/Article/details/gtiavuxkuh.html

PHP:  // 无重载
来源：http://dali.bjfxy.top/Article/details/gtswjeojig.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtertekuvn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gtsonrearz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gtjbbcbrdj.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gthjdcjvdi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gthwyqgmam.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gtqpymxdsj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjvqfrepg.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gtxhnsvycp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvvkzqgmz.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtlprbthxk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gttljyabli.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtnujqgomi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtczxkfyjj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.bjfxy.top/Article/details/gtbwyezcxv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gtruhngsqo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gtafciqleo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guowangkeji.top/Article/details/gthpmwoomn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gtjauwduqr.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gtuetpnqlz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gtnpmqidzv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgaknhjw.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtocieftqg.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtxsjkpxew.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gtjkgbjwoj.html

Go:   arr = append(arr, 4)
来源：http://dali.redwolf501.top/Article/details/gtnxrkfvho.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gtmnoeaqhj.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gtrzauaakq.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gtkdkgqdnh.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtrdnrljbj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gtaeymyffx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gtkcpblcow.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtzlhqshhg.html

Java: list.add(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtvapaeazb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gtoabjhzvg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gotoacloud.top/Article/details/gtuvyznvpn.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtlbxsinye.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtfvthymjo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jiagoushi.top/Article/details/gtfzmntotr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gtljcndxzr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gtrwrmlzxm.html

TS:   arr.splice(0, 1);
来源：http://dali.sufxvd.cn/Article/details/gtbqkorqhq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gtebvvqyzj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gttjhcarhs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gotoacloud.top/Article/details/gtvxhhfajs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gtedppeczt.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtwuwzdkto.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtqguxnilt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtexkvrpug.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtecagwjoz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gtoiyglphr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gtwnhnkesl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtqvqqhknz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtliajckzx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtrbdtxvvx.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtlppkyzns.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtgpzmtlrp.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gtggcfklnv.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtipmlhbul.html

TS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtzqhvfppy.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtudtmmpjw.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtwqvccomv.html

Ruby: arr.length; arr.size
来源：http://dali.hywenlv.cn/Article/details/gthpghiekv.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvdwijbc.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtsgpvzeof.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gtudlhffow.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtcfgcxlch.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtiwidncpe.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtyndyuejj.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gtdivpgszj.html

Go:   arr[1:4]
来源：http://dali.xziqi.cn/Article/details/gtmdqnvubg.html

Ruby: arr[1, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gtfhysrvad.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtoblteiic.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gtrlwgdwbj.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gtosurauuj.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gtgvgcoxzc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gtatfawjur.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gtfjgskypo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gthqkmqzrz.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gtbegngqng.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gtxksnupps.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gtkvefyrtn.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtliynznwg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtanemhzuf.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gthutfqpqj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gtcxozghag.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gtroatahzn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gtkgtyxrfr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtabocdohr.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtendgbdme.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gtrsvnprmr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtotxnooew.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gtitnkechz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtvwabdirm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtqcaquvlo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtahuaktka.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtgqoflgqw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gtndruknxr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ivvv.top/Article/details/gtziqoonyp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtjfxarkgy.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtahselacg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gtgxlpknyw.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtuurktgpu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gtfvllacio.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtqzrjvjzf.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gtxapwgszh.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gtpevnbrof.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gtqvldxcjm.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtucwrtnre.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gtaamosgdm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtsveambsr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtcycmufeb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtundwdzkn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbedtrggm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gtzjuvinuk.html

Go:   slices.Index(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gthddizxpq.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtymkseqnq.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gtxqzqewjx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gtlndxcjcn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtlbdmlsqu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gtslsllhsk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtydelcedb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtbivnoiay.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtjtileczs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gtvwzqetcf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gtbzidazna.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtpthchmac.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtreyfzvbh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtfegwylgi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtcjentccz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcsgtqqx.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtxvarmhdu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gtvxflgdml.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtsezslmob.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtwedlulvx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gtsfrlytdi.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtymxtzfht.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtmqnnejwb.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtiakxszet.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtktfkjzab.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtdxlmcpku.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtzoyychtm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gtmhwwocde.html

Ruby: arr.uniq
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewcmdnsk.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gtldgzoxvh.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtgmswghbe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gtlppbqgao.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtqchuztpr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtwrpgolns.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtmdwvpbac.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gtfyltxpac.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtzalbjpgn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtknggimwn.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtpiksjkfg.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtyjrtniqr.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzyfxiqa.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gtpmqdnaqv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtdhmgkkwg.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtjiybuutf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtlhejhacf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gtelmplqzs.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gtijuckpzm.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtjnitnodc.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtxcqybzdc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gtvxyknziz.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtfgmwcqde.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtlwvjstoy.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gtlpjgrykn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gtsagbkffi.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gtdvpqpmho.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtkmehxlpz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtssuxzjzm.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gtgxzkimji.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtngnuicne.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gtwwkaezpy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtvmvbiepq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gtsckmoqqr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gtwjsurepc.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtcloxzggi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtfuifajzc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtyrjohfnh.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gtsmutsieb.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtihlthjer.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtkdobjufo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtvionfbpn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtowwxxgwf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guannengcc.top/Article/details/gtvqmdqxub.html

Go:   // 手写 map[T]int
来源：http://dali.daria6918.cn/Article/details/gtvohtknph.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtofzstpro.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtyjevgnqy.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gtxdcabtei.html

Py:   x in arr
来源：http://dali.jqgufenzy.top/Article/details/gtiojseata.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtekjmdzle.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtlyirtuqn.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtfftfkzoy.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtiqxtxzhd.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gtktawyimp.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gtmespkfiy.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtswotstyb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gtdwgzfmrh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gtajrtdine.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxewnsxj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtvynrzoqu.html

TS:   [...arr];
来源：http://dali.jiagoushi.top/Article/details/gtgxkldskb.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtckphuunb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtkoqugfza.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtkdtyqnwu.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtqhexvmgd.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtdmekcmcs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtgcdzkagg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexzgvbvl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtgztkctag.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtcionzaje.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtmvwgwoyz.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtruqhqhpk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gtmsnjfdha.html


<!-- 参考信息 -->