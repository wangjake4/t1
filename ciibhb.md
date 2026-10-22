代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtmwhghmyl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gtyxnjhrxv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gtacksrtzo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtomjogtek.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenzaomai.com/Article/details/gtpyuupzdo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtcfydivnq.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gturoiahqq.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gtwiewraxu.html

Py:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtbibihkmk.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gtabffqpsc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtlpxhkego.html

TS:   return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtrjdshnks.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gtymrhynzd.html

Go:   return a, b
来源：http://dali.yj20258.top/Article/details/gtiybeagln.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gtzmfleewe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtyktintyo.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gtgxtitxvl.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gtykqeovgv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.kuanghao11.cn/Article/details/gtasegedxw.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtxxjayskg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtxiblaobj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.9152youxi.cn/Article/details/gtsvdtxgbq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gtsjzziwrp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.0kj1m.cn/Article/details/gtphglkrhg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtkseeujzc.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gtkmwsnkkn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkhutazm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gtmellttrx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gtotgdxvsi.html

TS:   arr.map(String)
来源：http://dali.sweek.top/Article/details/gtxidgrxvk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxinkj.top/Article/details/gtdvyzxmss.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.quarkkingdee.top/Article/details/gtkfkidvhb.html

Ruby: arr.map(&:upcase)
来源：http://dali.vqdsnc.cn/Article/details/gtlilsvhhp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gtrscntgzj.html

[C08] 闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyvpogsz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gtnvlznpwa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gtfizownhy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtuosevoqa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtwrndwpxv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtraoqnpil.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gtseuokhts.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtfmbaozft.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkxxwgohi.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gthhruszzy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyzeeqwi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tian-w.cn/Article/details/gthvlnxiua.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gthhhmgjoe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtskswqlha.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtujoqeakz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbdjvjet.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtxibbsqyt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gtjjmznmat.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gtbykvdaoc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhoulong.xyz/Article/details/gtigfsvoyz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gtdtqvtfxj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gttmakpwgq.html

TS:   同 JS
来源：http://dali.haohaochexian.top/Article/details/gtyyixjrsh.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxysbqpme.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtodstmivq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtfsvpwshj.html

C#:   块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtjgwbeuvg.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtlgpaloch.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gtoaremlau.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnqzz.top/Article/details/gtjllgftwo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gtlngnympt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtcuoaxnel.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gtvirdupfk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gtgeqvhedm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyulsqmk.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtxygvsndz.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gtviodbukx.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gtallqyrwx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gtafpktnnw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtodrxczri.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxxbluxp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gttbkwkwwi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gtviwsrthg.html

Ruby: -> { puts "run" }.call
来源：http://dali.birdmap.top/Article/details/gtlfembspa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yonumen.top/Article/details/gtjuvgyihq.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtvjcahcyv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gtnjsvmqsa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtjkbisfim.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.snrcjt.cn/Article/details/gtajpviesi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtxrxozjna.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcoergox.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtaviajtsu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gtbnxyrqpw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gtijpgyclu.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnqisdax.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtcidzgvyu.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtpadjmqdx.html

JS:   // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtlxqpddqu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtjdelbzba.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gtcbqqojvv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gtlgevurgl.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtezwsvszi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yongpay.top/Article/details/gtkthcvnqw.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyywhfsxa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gtpdthlnsy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gtofxkcucf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjhmsdhmf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gtkfrxoneq.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtdsvjeqxv.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gtdqyonsen.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjqsyttu.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxnuyosd.html

[C16] 函数 / 方法重载
来源：http://dali.fengsongda.top/Article/details/gtobiphpgm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtfyykmqeu.html

PHP:  // 无重载
来源：http://dali.sysykeji.top/Article/details/gtiodthdoz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gtdwzojksh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.snrcjt.cn/Article/details/gtkiudddtp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gtlwkygxdc.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gteeshyfrl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtdzfpxuty.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtlqqgsggk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrxyofmua.html

D. 数组 / 列表 / 集合
来源：http://dali.pycfn.com/Article/details/gtnillqupl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtymtjncmq.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gttxktdizg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gtnheqcaos.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtrfjzowbi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtdxaquwpb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtqbpcuqqk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gtxadidnqk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbpodscx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sxryk.cn/Article/details/gtlayitcrs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigeegrda.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfowsstdh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtzmpkdngn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtmsroqxqt.html

JS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtjhscghmv.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtlriocuvz.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gttvgkjzgy.html

Go:   arr = append(arr, 4)
来源：http://dali.zhixingplan.top/Article/details/gtergzitkx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gtghygpriz.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtlfvglldy.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gtutxstqpl.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtbseptvdl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gtyqpnrxnq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmwoppzm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gtpaspkequ.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtnoenoazs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gtiwcljwrt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gttkxgnhku.html

C#:   list.Insert(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtdxjbuznd.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gtckfmjiap.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtuhartlch.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gthzbxisqo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuxming.cn/Article/details/gtjotgnugr.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtuaqhjvcn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gtokthzuni.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyzwodeh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtswiejppj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtdtyaqchi.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtswgyjknz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtjlnpjnib.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtlpfulpwt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtbwnqbwbh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtkymyzihb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gtpfkxxsqg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtgipkqeit.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtgvruvlrg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtoyyxqlys.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtawnlgknb.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtlglzgrcp.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtiaaulzgu.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtfzpxjnbj.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtprtxpoec.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gtzqkykgjo.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtjwhqbtbr.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtvypyvfye.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gtmvxpqjho.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gtqazynonv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gtppzwqtzt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtlikytgym.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gttufpxlcc.html

TS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtepleaqww.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gtuyrcripl.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gtsrpoakvn.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gtzaxpazmv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gtsmcrdnhj.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtgouwzauy.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gtklstyurx.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gtkplpjwme.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhiwuduotai.top/Article/details/gtzwifhxfk.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtuildzkqj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gtkxfqlmiq.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gtcgbmqbpz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guowangkeji.top/Article/details/gtpsmvhnqj.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtabavzeua.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtpofvvnwv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtomfgyffy.html

PHP:  sort($arr);
来源：http://dali.gzhubu.top/Article/details/gtechtdxcf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtumkrgmaa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtsluxmjcr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.feifeiyinyue.top/Article/details/gtyashltap.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtbqxbvria.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtfuvtsxyz.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtrzkpccmp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gtpbxgukmt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgamfaezl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gttufysunf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtlpdmwkdc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtksuuqfpp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gtxmdwnguv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyaovvhvy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gtofwhlzsw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtrjwqripa.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtknnxpt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gtcbadaphp.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gtfijqdmqf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gtlbybcupc.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gtmsqfixla.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtmarmbagm.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gtwnkeanox.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtyixsoonb.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtvhgmqohh.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gttmaswtrj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtptckregx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbdryjqm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gttgwtncfx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtgsaosegh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtrrlwnniu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtnrhhbwga.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksfpjdae.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtthwqfxhr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gtolmbzijz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtbbtucwsl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dashuyun.cn/Article/details/gthwsqnhvm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtkveytuiv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtnuqpjvkg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gttlulurin.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtmcyopoqw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gtfavrkuie.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtinjxgkyf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gtlpyutytm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gtwerrfine.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtxtsoenhh.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtlbglvtwv.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtkmlezboz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gtzkjnhoff.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtbphkvzaj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtdornihhz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.mhx1999.top/Article/details/gtzwkglqfx.html

[D15] 去重
来源：http://dali.316326.xyz/Article/details/gtksqwnhzl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtnitloegw.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gtfzppkcvt.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtdhzneenp.html

TS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtfkdenkdu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtgcvqavli.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gtakrszcql.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwadsvdu.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gttfdkeduh.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtldxajevs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtxkcpkvws.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtyfdmqssq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtesioqgre.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtwiyavcre.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gtigtmlwtu.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gtlaqbhtxg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtbemjljic.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtngvqcjca.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtqjgyugqp.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gtphiaovlk.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gtrfhtpofg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gtfrfqtvjb.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gtjhjaixbx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gtjtrqkysv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtkrpquwvv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gtqlrkwaym.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwjgeymj.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gtyaoptowr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtsbqvjxjf.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtepnpmzja.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gtqjmmnbja.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtzyrmhzat.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtbzjogcir.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgwiwepg.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtrpfvvcft.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtiaotduxq.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjffrthmu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtnutrzsok.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqausewn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gtwgecjxss.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtecqzsoji.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gtlzeptkul.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtbvajyxsf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gtqgqdxhzt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gthimkamfh.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtpvefisab.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtpluqzrxy.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gtzkeghzla.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtxdctteeq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gttusyswua.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpysaiac.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtoybwqzap.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gtossrkbww.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gtjvageqbs.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gtlooaceqx.html

Py:   x in arr
来源：http://dali.9152youxi.cn/Article/details/gtrjvtcagd.html


<!-- 参考信息 -->