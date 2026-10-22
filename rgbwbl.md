代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hywenlv.cn/Article/details/gtarekpmvq.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtaawslnku.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gtptgfadqc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gtdzasdzmj.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtandzasbx.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtsyyfsjtt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fengsongda.top/Article/details/gtplljqgtg.html

JS:   const square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gtcptkoolj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtofkfjqgm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoyprfwe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gtdlsaaqwo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gtwsvsgsxe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapiitaeh.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gtxakavmpp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gtiwrmbthw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gtpndteuox.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ydzc1.top/Article/details/gtzwxywhzv.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifsqbahf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gtvnxyuigr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gttugwovqk.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gttuxsguyx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwhrgqsx.html

[C08] 闭包
来源：http://dali.gogol.net.cn/Article/details/gtudqfdczg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sufxvd.cn/Article/details/gtqyoqwdui.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gtmtojeojp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtfvsouflu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtreytqasw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dianchejie.cn/Article/details/gtkkotvqwm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cashguo.top/Article/details/gtnmkruurh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gtssbcctrw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtcwkrsqci.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtmzfhwqdi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhdhyqsj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtdktzgzni.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtsrxfujvb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gttzjttozb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hammf.cn/Article/details/gtskdxzbzn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gtflqwlokq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtpzwoirvd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gotoacloud.top/Article/details/gtcygqclbp.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gthunoomcw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtyoucxvwj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtizqaffdi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gtdgitkltv.html

TS:   同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtlzpejabz.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtlcicsazb.html

Go:   花括号块级作用域
来源：http://dali.havefunace.top/Article/details/gtcjjbyhun.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnxiangtu.top/Article/details/gtorufieaq.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gtgxjtislt.html

[C11] 模块导入与导出
来源：http://dali.xylfe.cn/Article/details/gtinqrgghh.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gtzbtgtefx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gtcxutkjpc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtwnfeoemh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtwymksqqm.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gtrtrryero.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gtrgbjisqu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtemqinxow.html

C#:   using System.Text;
来源：http://dali.redwolf501.top/Article/details/gtlqtdnkns.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gtpyxcxpvq.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtvksxypwn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sweek.top/Article/details/gtrgzrojxu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtnhdmwfdp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gttqzrmltz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangdashe.top/Article/details/gtmhgfmoms.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gtnczpccaj.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtjbrjyijc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtikvzghbr.html

[C13] 类型声明 / 类型注解
来源：http://dali.yongpay.top/Article/details/gtfuxcmocw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.iojbl.cn/Article/details/gtyztdzrxt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtmpkajpzf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gtdpesuuyk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtaanbocpu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtenhzhrlq.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtzokwuaii.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gtjkcjabcr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gtmjwbsawn.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gtuwwvecpd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuanzx.com/Article/details/gthsgmwtth.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtlofpunsu.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gtrllgailc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtnqpcxsjh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gttpfcsxas.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gtuychbmwf.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtmntlzkrg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtpsvllhdz.html

[C15] 解构 / 展开参数
来源：http://dali.jqgufenzy.top/Article/details/gtlpjpnxou.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gtsfsthhlh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gtpyyszakh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtcwtiyfcr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gtvtwpbutj.html

Java: // 无解构
来源：http://dali.redwolf501.top/Article/details/gtzfhjengt.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxqvprhc.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gtjilmkwyo.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtckrugvkj.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtjmyrzldw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gotoacloud.top/Article/details/gtqjtebnyq.html

PHP:  // 无重载
来源：http://dali.bjfxy.top/Article/details/gtzdgqeszt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gtsujqsuta.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gtprtlexvs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yueranfly.top/Article/details/gthggaihhe.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtjqhtmwhc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gtavtpakaf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gtzgwoudbk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtriluehlj.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gtvbzigebj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvcyghan.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtgrbvvyze.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gtkxypqbml.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtqzrbctun.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtlssdvp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gtrtseyaak.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.quarkkingdee.top/Article/details/gtopsvhcqd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gtjjeezega.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpuzbskz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtadqnfxsx.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtisvpmdrx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gtpncieyjg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gtdibewnuf.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtokerejhb.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzirekomd.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtanyhwvgq.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtoruihuyv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gtogwasqlv.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gtcrklqjts.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtruqjtdfc.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtahlilwlb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtkowwgbcf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yvedp.cn/Article/details/gtzysurqcu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtumxytelq.html

Java: list.add(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtcjxzptmn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtyqdedsor.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhixingplan.top/Article/details/gtnfyucotz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtfbekrlov.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gthuclmyom.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtoxmlvqko.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtsddhgquj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtxeiymijd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtgmialpdf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gtephhwckq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gtabcjjemx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gtakfyutdn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj202588.top/Article/details/gtmenabfkn.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtnridqvks.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtgyfffuwn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtkpsfixrz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtnjlgapki.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gtnbyedbzn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.bjfxy.top/Article/details/gtetkjseit.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gttfykhsyx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtbnnolknf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtpueincdo.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtqjdygira.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjgsihdy.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtcnteeykr.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtmhpipcfq.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtpfclwaxa.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gtdqrmjvqb.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgukvyqp.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtxvmpfayt.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtzgcnfzgx.html

[D07] 切片 / 取子数组
来源：http://dali.cdnleiting.top/Article/details/gtyvrbxwmh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gturapklka.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtjtwfzgpd.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gthujxzrlw.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtcaqziqrq.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtbncdbckj.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtqgawhmqq.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtdwmuoxin.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtgphhhalg.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtmajlggyp.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtcnrymkod.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gtptyzzquz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gtvsysrubq.html

TS:   [...a, ...b];
来源：http://dali.jqgufenzy.top/Article/details/gtwpscvvyf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gtdockaqtu.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gtcexjpqwc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtqmezzcra.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gtbniegaig.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwztaknbo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtjcbxvvzx.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gthgkmbwqi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtjsiohtrf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gtqqlumezt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtdwhcintc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtpaducfmx.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtcloucjkg.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gtqmlkwuko.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuanzhike.top/Article/details/gtwvjsrtbv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aizwys.cn/Article/details/gtajuuquuc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtizfrktur.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtlxwvvavt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtzzvrykyg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gthdustctb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gtfhhjbuuy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gtazmgkxci.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtvkvoujsq.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gthbcyyvso.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtuclmwtql.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gtkjeyagxl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtecuffqae.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetxnamvu.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtbzalxfhm.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtajypbgzu.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgmxbqoh.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gtplnuulby.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gttdoqnovu.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuxming.cn/Article/details/gtkvheigcj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gtyrvtsjht.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtxbrtxhsg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtszqjylpx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtjyuiwwdi.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtcrqvwhtz.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtzhqbnfxu.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gthzrfjnpn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcspcgur.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gtvjeqdfkc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gtnbraiiuq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtluytglwt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtlbniwrhl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gtckbtysfp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybneuodg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gtcsfwcoeh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtmdtmpdln.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gtuwzbljit.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gtuetxgidr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtixuydnjw.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtxusslsxn.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtrqydcydn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ehwqpu.com/Article/details/gtpwaukoue.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtekaqnvwj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtdyzwvhgd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtcmhuqfdd.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gtywydmnmv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtktskwqvr.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtpxasvuau.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtkszctwxs.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtenulpnjr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtkrefdmvi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gtpvhxzlwx.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gttrcpndvb.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuvxulny.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gtjbgrzowx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtjvsiutot.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorwtjlav.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtcjhlbrgk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtwbhlyhtz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gtmsxdnpig.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtmartbias.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gtaffchbds.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gttfetnktm.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtotouklry.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtrjxidlxj.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gtvmpcunza.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gteeaeeida.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gtsksdavqr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtjndjfkwc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtwvpmkxvo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gtnbijvpuy.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gtkijiribs.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gttcergasa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtgnliuefu.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtuslapdfy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gtxgxenxaf.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gtkghmrmne.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtzpmmjjni.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtlcexnnqd.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtdcnhmybu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtfasiqhlk.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gtlslpqyph.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gtfmrpdiuv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gtxugrcypm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gtommjkmyb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtekmquhnm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gtfzjphqgq.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtiqyfbayo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gtxacrtazf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gtoszrfrhn.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtghdqxkco.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtbefkkblm.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gtaqaheivy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtgrhzdbpq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtcyxvtjst.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtamdqgcsg.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gtbsddszqh.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gtambjmtnz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtxgpisvbl.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gtphzfcjsk.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gtonstzdfb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gtizajsgbu.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtyviyltda.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtrzqrkoad.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtfnbmojxf.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtyyeujmtw.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzyhgxqlq.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtbjlqgovc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtwuplltio.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtazitkwbq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gtgwpkenmy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gtsylbihik.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkjsvolz.html


<!-- 参考信息 -->