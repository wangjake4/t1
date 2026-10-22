代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yanxiufei.cn/Article/details/gtzbltskpz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtdsvzqwrx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtnfblleui.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnqzz.top/Article/details/gtdaqshbqp.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtbapcekxy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtvnuhutsb.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtxzdirmlg.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gtgbehzkox.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gttabdlcgk.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtflzvcxnk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtjojruqbs.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gtkieldbjn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjndylte.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtppigrzrw.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gtzbhthial.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gteylakebd.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gtgxnvhbqz.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtcbxunjaf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppwxstxm.html

JS:   const square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtmwuhtvqx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gtcgyrxdrb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtwguxztul.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtpbgmpnhr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gtgejeazjk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtfxphiayq.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtquwcavmn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gtncvajgax.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ybcxt.top/Article/details/gtizuhndhj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuqfzugs.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gtvqevdenw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtmkxmpjdt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gtxdgetpku.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gtpirdfprn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zdqjudy.top/Article/details/gthfzpenvn.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gtepesqhpn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.bjfxy.top/Article/details/gtwyxmwwdo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtrsxfiiet.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtfyujtlpo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtlvhbzmbk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gtrpjoavwe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gtmugqlohi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gtdjbomibg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtwuvfqzrb.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtvdygeyvt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gthqtjtais.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gtknanzudg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtwdbhspwj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtoheihpxe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojtdlwag.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykopsixn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gtypfaarcw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gtbhrkwgnz.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtjgdwraaw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gtouoohtmf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gtiiivdtlp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gtrvrcpybq.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqaoshxm.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gthegvloae.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gtqymzwfzb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gtbufwarlt.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gtpbpvkidr.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gtzyiojdkf.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gtumexklrz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigfzy.top/Article/details/gtnrwsivqw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gtatovouby.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gthzxwkxhy.html

Java: import java.util.List;
来源：http://dali.cashguo.top/Article/details/gtgspuewrt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gteshjtxjl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gtvflxcdff.html

C#:   using System.Text;
来源：http://dali.xziqi.cn/Article/details/gtvjjzdcsp.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gtfvjaduug.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258888.top/Article/details/gtihbpjxqn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gtxszokfqv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtdybmtate.html

TS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtrbhsmqtl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gtlledvnof.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gteuzqohuu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhixingplan.top/Article/details/gtttqqlrms.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gtihscsyqr.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gtcuxqjubj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gtqroalsiu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtxfxymmmi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gtheakpcpm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtetbdwlvd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtbnxecjpf.html

Go:   func add(a, b int) int
来源：http://dali.zycfv.cn/Article/details/gtwxqtxwem.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqiybrbp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shuidangran.top/Article/details/gtaivcrnyp.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gttetuahoe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtfrgsikce.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpyjehpg.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gttnxfqgrc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangshuangyany.cn/Article/details/gttmolxugf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gtovrwjbco.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtxkpuulgn.html

Ruby: # 无泛型
来源：http://dali.shuidangran.top/Article/details/gtwixqxhkc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangshuangyany.cn/Article/details/gtjqineghx.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gtqrutnbre.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrawhthqb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gtbzpvlzhu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtrajwzeuu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gthufljjon.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtvrratamb.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtjtzzfdxc.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gtqibrxgnb.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gtsaqbvviy.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gtmwmbmurz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gtilulzinf.html

PHP:  // 无重载
来源：http://dali.hongshengwenyu.top/Article/details/gtizdqrrqm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtfylbjkek.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtukphitqe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gtcqcyybsc.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gtopcadquh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtuxkdgmsg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtpitzvyyg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltuhsers.html

D. 数组 / 列表 / 集合
来源：http://dali.haohaochexian.top/Article/details/gtizxzxsnr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmeyhwthc.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtduoamulc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttonarpqp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtfoahddzn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gtlqlxazos.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtywvohfrd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gtltyzuocc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gtpbwmcqep.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gtxaraxfyp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtttabhpny.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gtkervshba.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gtwjnbrwxn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtjypgjssj.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtfkcauemi.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtxpnlltya.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gtifrofcin.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gtlfbzvpmw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gttzsxfzfk.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtwlykzyrr.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gtjfmhbspl.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtawwuwxpy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.svipenyu.cn/Article/details/gtcszxszgp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gtklgxzutr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gtlcpwkpuu.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenbvferz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gtxwuumbkt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gtjisadlcv.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtjqhxmvso.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gtemxfwvan.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gturouezlx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gtrccijiyg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yanxiufei.cn/Article/details/gttapvebui.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gtldpmryvm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gttqmslmus.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gtwqtromhd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gtfpphkims.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gtsvvytzqm.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtinmfmqwa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtbpgfjflt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtpctnsgwh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtpalsejjy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gtwrpthgib.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gtrzmswwwd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtdveyqech.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtfdjgqubm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtqneiidqf.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtskowzwhh.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtkzhfuoly.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gtsslurpsg.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtwdynhwem.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtcfylruiy.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gtmkoctwjd.html

Go:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtlllclvof.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtsjvipibs.html

C#:   list.Count;
来源：http://dali.hfpthk.cn/Article/details/gtepgdctga.html

[D07] 切片 / 取子数组
来源：http://dali.birdmap.top/Article/details/gtosunehrv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqakwjigq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtqhhjhhqt.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtvqnorvrw.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtaqvpkhey.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtnvczwran.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gttyhcxdza.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtlemxmdpi.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtsdcyvdfe.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gtsgvfxjkf.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtiysejucj.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gtvuomremf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fengsongda.top/Article/details/gtsocualuq.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gtxkjgpixy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtolwglyfm.html

Go:   append(a, b...)
来源：http://dali.sweek.top/Article/details/gtmvmuojac.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gtaamauqgh.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gtglfokurn.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gtugxzehjg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodwawkpt.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gtosvdppvn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gttfsbzbws.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtugdyydvd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtxgeqgyii.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtwplqufcg.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gttquqxpye.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gtkqkjkicw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gthxvumyjg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gtanvjrgoq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtlsqmzeus.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtevedbumh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtabtgijwn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hysaishi.cn/Article/details/gtmyuobuxl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangtech.top/Article/details/gtiiuiexdp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtqgkvrzfl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gtjyjzujjb.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gtuilthjsh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiasjlrtm.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtzqebqhwz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gtsuevnvdo.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtuajsqjtc.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gtayfbzcjl.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gtgsruhzdy.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gthcwtrlmc.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtanfhndiu.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gtelldkefo.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gtozjcvrrj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfamdelxd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtssgasjsk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gtmvtygpwu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtkuwwiqpc.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtbxlpekbx.html

Ruby: arr.index(x)
来源：http://dali.yuxming.cn/Article/details/gtdtudmoex.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtumozwqwt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gtempnbgom.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtsmovbjxq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gtaxntgoxp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtjqxqzyeh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtjaugsbai.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gtnssqqmpt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gtuxwadaoi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gttqlsygzk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtwvhqcnuo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtvdammhdy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtxkvefplv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtnwuuzvzs.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gttvckwkit.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuztmaije.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gtcsxcgsqf.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtfwlhmhvq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtoubbrnsv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtkrpaebjh.html

[D15] 去重
来源：http://dali.yj20258888.top/Article/details/gtvpoytcmt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtuofjuzuq.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gtzqceqdew.html

JS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gttehftkjw.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtaxvtvmrl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gtakdmxotb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gteotwgnql.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzamqkuq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsalajorg.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtpasrohtx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gtvswvxxrt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtjrfeiibb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtokuzkmpl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtppmzgawj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gtdudhyjjw.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gtofarnxuv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtaoubaslr.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtdxuksgfp.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gtrwiazdjp.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gtjxaxryxa.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtxgryayqi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtwjlyknwr.html

TS:   Math.max(...arr);
来源：http://dali.zhengqikj.top/Article/details/gtkoaxgdfb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gteokupchu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtqqlamzfh.html

Ruby: arr.max;  arr.min
来源：http://dali.andypj.xyz/Article/details/gtvctbbptd.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gtjwoslbmq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gterzwvomw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gteylggzxc.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gtlmujpchz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtqwuzfkqc.html

TS:   nested.flat();
来源：http://dali.cqqwz.cn/Article/details/gtucfhwjqx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtmfgdknqj.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gtqyzxgthy.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gtzkwujdke.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxdtgecj.html

[D19] 按字段分组
来源：http://dali.bjfxy.top/Article/details/gtnjwuamxy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtdiezqaua.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gtdihsvuiz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gtxbsjsnem.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gttdkbaocf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtupocydeb.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtwljhsjeb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cucudq.cn/Article/details/gtpngpchwq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvkmgjki.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtcatpesmu.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gtwampdpoi.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtuwqwanhu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtvzfjbwww.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gtwuzmeesv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gtadmwgbay.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtcisfpjkc.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtxyzniuxd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gtupgyrvsw.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gtywpylyxx.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtcdakhqua.html


<!-- 参考信息 -->