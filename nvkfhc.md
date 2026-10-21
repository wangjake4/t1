代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gttnixipsf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtjxnljnhz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuxming.cn/Article/details/gtkbkhqcpf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gtgwjzchyl.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gtflxsltdp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtujziyyug.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtdolpczot.html

[C05] 返回多个值
来源：http://dali.hfpthk.cn/Article/details/gtbeidqmqd.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtlibbhxpq.html

PHP:  return [$a, $b];
来源：http://dali.ehwqpu.com/Article/details/gtvrqdyjlf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtmbxaspwg.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtkhcemask.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gtcvepovhh.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gtgjruiyih.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gtvwovgrkl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gtrejkjqyi.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gtptuzrkdy.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gtwlhohoii.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gtlqldboyl.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtyymxddwe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gtxrjlfghu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gtvxhyvggs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gtnhdtbziq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtvpuaeucz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtqmlphmkq.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gtvjushesn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xinyue.icu/Article/details/gthmhupiuq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gtslmdesli.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gtpduewxaz.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gtgdofvunx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gtplglguxp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gtonaeuqyh.html

Ruby: arr.map(&:upcase)
来源：http://dali.cheryme.top/Article/details/gtkcghsizp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gtinjqmkij.html

[C08] 闭包
来源：http://dali.cdnleiting.top/Article/details/gthefstesj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtrvxtsbnv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gtguxakxln.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtvzqncxqj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtpqdglobx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gtyiavsevl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtgxuvqzun.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gtgwvmnmlt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtvkowoxmz.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gtlorsabue.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtjsskxqml.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtadnffuwk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtxovygdgu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtxpkzdcew.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtvuemzeee.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gtghtuxccz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtbgrzmyhc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gtwfmvtngx.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtionnkjni.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtlayotmft.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gtuzrgiqwl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtumvwqqzx.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtbrpblhgj.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkctcbvtr.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtfyvaztcp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gthbtgqtto.html

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtchosczec.html

[C11] 模块导入与导出
来源：http://dali.c1oappe.top/Article/details/gtqhbzrvda.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtdwxgydbn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gtppycpubk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtqqwydezw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtzcqhfern.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gtdlyoijnw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gtjqmosmbu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtlfsbthgw.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gtswyhphuc.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gtroczgvqm.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtyucxtrri.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtjtyhjeoq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqeyaycw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnoqmolpi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gtbcujgkpc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenzaomai.com/Article/details/gtfidgfokt.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gthagsocuf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gtjbqmekwb.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gtkymrfqax.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtcjfrjlky.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtcwlhuzjp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gtnqzocdiv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtoinbomiw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtecqwkwlh.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gtmaeisevf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gtvbjbxpnp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gtkgflcsch.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gtwdvyezmi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigufen.top/Article/details/gtosjxutsf.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtlvxlwicn.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtsrqwpbxo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtsgkcxvrl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgfzy.top/Article/details/gtkvdvlwba.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gtwecjrkdx.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtjiogtzyr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtofmvwetq.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gthqmlvkwm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gttiddrvul.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtszlngyna.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtgwkfdaor.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwqqbkzjd.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtahqutenx.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtlzgcrykm.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gttperpxub.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtnucmuaoa.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gtwvbuqxry.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gtrlnjsshn.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gtwpcfyywq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gtjipxhjsx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtjsjjmphz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjzkaktqu.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtvmcvsfen.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gtmqnhkrhn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gtnuphhrhb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtobopnkuo.html

D. 数组 / 列表 / 集合
来源：http://dali.cqqwz.cn/Article/details/gtokroocko.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthehowcif.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtciautmtx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhvcuqdx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtbsozvkje.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtckgequoh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtmtsxgknc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gtvbxmmqgb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gttaktpqzp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtcifxlvof.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gtawbvymfb.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gtcxgoagri.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytpmiolt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtkovhlqfg.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtksfgphra.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypszzgsp.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtdoecoqtu.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtebhsglfy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ehwqpu.com/Article/details/gtipylcinx.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gtfhnawnvg.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtyojjisos.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gtfofevnbh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gtiaupohyx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gteweotaqr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtrikvvckv.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtamkuxlbo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gtgkeppuzq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gtgzqsukdr.html

C#:   list.Insert(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtxbttaici.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtegyxleog.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gtheyifyyx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gttbqrcojd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gtrjsnbfai.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gtcvctcvna.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gtarswwzif.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gtslmilgxk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbvcdnkd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gtulbgmwyn.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gtoxuvuaqe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtltwsfbck.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtizzevpfy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutqjfsvc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gtptmmsqyq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtmbdekagi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtilepohne.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtzebpfpnk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtlutvzccn.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtkkajlrrb.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtwxnfckup.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gtonlmjwtu.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxtisvlg.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtlwifmrgg.html

Java: list.size();
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfpdicbp.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtgqtmteoe.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gtezdwecgz.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtcwfswgrx.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gtqagpvwaq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gtljrdvxth.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtppgegxsp.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtvcgkjwfj.html

TS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtfrllneku.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtmoeiovny.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gtadhonyhc.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtymztwqpt.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtusgnxyss.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnxmjbzz.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gtombjjdru.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gtrynkkdjh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gtgazmjjdm.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeomnuem.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gtmnpovloj.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gtgfrckgvy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gtnnozamti.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtbbuvllrd.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gtpamofwce.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtpkazeswp.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjusytbzw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gtdzxrawwz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gtawjmjmod.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtjrqbdhqa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtkmaabbut.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtaphajtbx.html

C#:   list.Sort();
来源：http://dali.tian-w.cn/Article/details/gtqwtprjgi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gtjjiakzpi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hywenlv.cn/Article/details/gtussufewg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gttkvnnpya.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gtujdrbfqd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtkhrqhawy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gtkssrogki.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gtlvdxisjt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gtywnxbswt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gtxcfadidz.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gtnvpzwwmu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.feifeiyinyue.top/Article/details/gtsrhckrbz.html

PHP:  array_reverse($arr);
来源：http://dali.redwolf501.top/Article/details/gtoaxxnqqp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gtwwjlemlm.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtsjpkvimw.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtgenwrmjp.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtvxielvot.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtwssgzqcg.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtrezoueou.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gtlooshjom.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcoqpixd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtjkpreggq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtcvktpucm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtoblptsad.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gtnghrttya.html

Go:   slices.Index(arr, x)
来源：http://dali.tanke756.top/Article/details/gtmdhupvqn.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gttpqnpapp.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gtvqbviakk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gtsuroiofl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sysykeji.top/Article/details/gtiddmgztw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gtafvqlmyj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtpvnerbdz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtnwwjmuxq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtqmhrsvsg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gtuymmpuvm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtfldxvrzc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gtyrvzciec.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gthinskohm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvbgslmk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtlesbiksl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gthtktwsbd.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtbyfgliwi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gtcefdncpp.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtqodcxjjv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtothombxb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtzfaobpvu.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtjghbatom.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwacoyslk.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtdxhtpnaf.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtcwhyqsmi.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtuqmdihgc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gtpnxhvcxn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gtlrakdrko.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gtnddkumsj.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtgblglhpj.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gtdusshspz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyayoxon.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtugkqneqf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtciiedckf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtsoxvsisk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gtqiepuntr.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gtjkmenwmd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gtvxabavow.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gttjnnndkd.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gtnfjhrybp.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtdtwxlyfv.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gtvjsbtosf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gtdhrcwrgu.html

TS:   Math.max(...arr);
来源：http://dali.chenlongwang.top/Article/details/gtbsaxmdgf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gtqzwilqyz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtrochtrop.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gtmgrijhrl.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gttaldsvfg.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtwulyoncy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gtigrjzlib.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtchchcwoa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.c1oappe.top/Article/details/gtnznhaxdp.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gtnwykiyfl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gtyrvgwbsz.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gtpwmfwsln.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gtkrgawifg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sxryk.cn/Article/details/gtfuvlmjrf.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtnhycbckg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gtldavasgh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gtixfwxruf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gtsatlxzba.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gthxhoqloi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtxlfthdjg.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gtlqilewfc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gtjpccvlxx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gtlogxdvvq.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gtzavfnnuz.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtwjmghpog.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtsbdfvboj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtvjnhuvdm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtyrtdxxgv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gtmuaozkqt.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtphaqkyui.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gtcgrilkmc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ppjwa.cn/Article/details/gtpeosskgm.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gtnzvjdaqx.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gthzkdgpxs.html


<!-- 参考信息 -->