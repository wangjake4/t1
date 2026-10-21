代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtsudaaeau.html

Py:   square = lambda x: x * x
来源：http://dali.redwolf501.top/Article/details/gteeoyodrp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gtxhynvilf.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtqpmesfgi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtbeksvzuu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hammf.cn/Article/details/gtngzorguo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gteotlwssh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cdnleiting.top/Article/details/gtdtxauvyu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjanclrho.html

[C07] 把函数作为参数传入
来源：http://dali.yanxiufei.cn/Article/details/gtjbnokcqu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gtrgogcfvk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtflsfuitj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gtockiwukw.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gtfumotogk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtltybugue.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtbxfrlepq.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gtctiypbpt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gtpvptgtup.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtqqhbjqfj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gtuvxbennx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fzhhl.top/Article/details/gtbdyypibe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtaqluzhih.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtzyjrgvtk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gtqchjtmei.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nwbrower.top/Article/details/gtdfyaccun.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shzxlz.cn/Article/details/gtwbvvkvxz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtgfqguznf.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtntewgazs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gtxgrzdjqg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtxycrnuhl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtqpbgzvat.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gthiodwtuo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtgebconsg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gtbdwppkcy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtzpxkgrkj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtmzjylysq.html

[C10] 变量作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gttttxamhc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gtktvqgila.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gtepyltjzr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtbmghdnoh.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gtpualcmzz.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtsdzqtkah.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtkvsftchg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gtqubimvnh.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gtkrshskoa.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtxvoyqqhy.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtungmcemm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gtteomlbhr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gtvlpoknhh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.mhx1999.top/Article/details/gtjkpvltnk.html

Java: import java.util.List;
来源：http://dali.yonumen.top/Article/details/gtmtqqckjt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtpjcmmmon.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijucmjpx.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gtjaresltu.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihgtixzr.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtekyzcusd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gtqfhuhwkd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtcamsmjce.html

TS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gthuaxqihk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hammf.cn/Article/details/gtnxbwvsph.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewyushcq.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwimqcfm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhengqikj.top/Article/details/gtkygpodsr.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gthgermfho.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gtjrajpugx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtjukgavnt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtvcxphgew.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtytqubkfu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtmewxtywq.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtnlzmneut.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtwmemqdjx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gtknkoiltw.html

[C14] 泛型函数
来源：http://dali.quarkkingdee.top/Article/details/gtbsbjjbzn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtnqzrbwgk.html

PHP:  // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtonubbfoe.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gtfsaizwou.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtstecccyi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gtzpiusxug.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gtfrvfwwfh.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtiglkwmna.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuanzhike.top/Article/details/gtilyrpmgo.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gtakpyibxt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gtzwksmzfa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtnsqtenyh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtevbirqba.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gtmlfqyqul.html

Java: // 无解构
来源：http://dali.yueranfly.top/Article/details/gtpwaefodl.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtvjbdekij.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtndlohhhh.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtrttzmcwq.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtavykbdiu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtogxmonkf.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gtuoahdkso.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtiesxvxgm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gtunpsynrv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvmzrsuoz.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtwnihyjms.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gtnwnehhmt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gtscyspyvs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtawowydze.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gtfungejot.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtniyubikq.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtypvbocyj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gtacbevonr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtasdkybwh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtiuorfyim.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zycfv.cn/Article/details/gtxmhuudjy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gtggxukkrg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtnsgkfsws.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gtzglrfiuy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtxzezcvem.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtnclihwom.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangdashe.top/Article/details/gtiqtmezqx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gtbsfkrtxx.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtxhcizohb.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtmzhguwhk.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gtghhtwhss.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gtnrcliqyb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtmzjfbseb.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtosmzoejj.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gtbnoglvcl.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtlbfmonpo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.feifeiyinyue.top/Article/details/gtoeqicghb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtyckvtuam.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtxdalumfe.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtgdgjucls.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtadeggzzu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jiagoushi.top/Article/details/gtzglzrcxy.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtndzwaxia.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtiarccnvc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gtadsyrpvd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtwjxnqqoa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hfpthk.cn/Article/details/gtwjcvurkd.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gtrubqxkdw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gtwohuxiwi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gtfthnpqzt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtwsumcsdw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gtiqmhkjpb.html

[D05] 访问与修改元素
来源：http://dali.snrcjt.cn/Article/details/gtjrwbpslh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtybjmqewt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtaqukrqjs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtwhsbmaqo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gtvwmphomn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gtkkcryemg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtcdsgqfft.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtcsxfauxr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtjfbdtbzw.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtmlfgkomx.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtelyrtlkc.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrunomoj.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtgvslnniu.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtfoofpgpz.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtdpezvfjv.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtcpawycyn.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gtecninzgi.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtjnntoqvz.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtnbrchjwl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gtirduonwh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gtfqonvqfj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtyfadosfv.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtnwqawsqx.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtvpddbxtb.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gtgnviezmd.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtepczzg.html

C#:   list.GetRange(1, 3);
来源：http://dali.birdmap.top/Article/details/gtmosoeqro.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtvbnwoqvl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gtjsyotuyj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gtwadgzxsf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gtiqpamdxn.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gtlynypcyb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gtattgthob.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gtemwdguzf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gtprzsuldf.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gttpnxxaxp.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gtonchkrle.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtziehthnc.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtssyditkx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gtexjaawxm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gtnvmqeoxw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gtdssheldh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtusbglece.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtadwlsbla.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gtxahrsyds.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtmxygkxcl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gthhsesgha.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtkudhgirl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtyqirusik.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtcqhldsuw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtljvuolpf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gtrcziytej.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefygqpgr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtnlzpwoqy.html

[D11] 反转数组
来源：http://dali.yj20258.top/Article/details/gtejybjoas.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gtolcvkgyw.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gtahbfjwvm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gtbdeuzpsz.html

TS:   [...arr].reverse();
来源：http://dali.sysykeji.top/Article/details/gtnyncnbdn.html

Java: Collections.reverse(list);
来源：http://dali.nanxinkj.top/Article/details/gteebhndhm.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtiwwkxmkx.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtqjjmbbqe.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtazxtussx.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnrsmpyy.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gtdoabayzg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtqeixltck.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtfyqfxreq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gteplboekd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gtiqkuhvju.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gtcvslwoiy.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gtsgjidzni.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gteobmkgka.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtcrgoutkr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gtgjzolaqa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gtkkjuonzh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtsgymdmei.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtktxtkwdi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gtslwihqoe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gtbcgsvtkb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtxuwlqzov.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtojllojda.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gthxmqvhou.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtayujgsqz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gzhubu.top/Article/details/gtkfzzzaik.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtyaigkqnz.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtdgpvjgor.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtzytayely.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtzhfxpfyn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtxsmiyvut.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtsdtdgqqn.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gthxnpvvmc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtlfwseokz.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gtsqhbjiul.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtyhkngbey.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtrkivdzki.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gtrpofqbkc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtzkpbnipb.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gtrrkkirxi.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gtcuitxpvf.html

[D16] 求和与平均值
来源：http://dali.mhx1999.top/Article/details/gtmmchdlmt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtigoaogsu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gtgimcjsnc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtzjaicynn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtpbejmmmj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gtffrdjljl.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gtzwksabrp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.andypj.xyz/Article/details/gtunqhfabo.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gtbkynfewn.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gtdfogmrpx.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtilkijsuo.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gteyykzxix.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gttlrhbpbw.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gthovutkih.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gtxfbbkjvv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtvjjfoavc.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gtoekzqdcf.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gthgiaejcv.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gtaugnsngr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gtohmhvcij.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gtwicpdklf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtvqnwakkd.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gtkosknaib.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtkgzocblx.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gteugbuwvg.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gtfjagojwg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguzjaovh.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gtqjkafaiv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtsfofulgl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gtlawuldgv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtspfjlzew.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gttllggfdb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gthmfzmzjy.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtuodrspef.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtsmcbjaou.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gtzzgfhfei.html

[D20] 统计每个元素出现次数
来源：http://dali.hnqzz.top/Article/details/gttxfpmyhi.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtjpwscgni.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtprrlutft.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtlvmcwius.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtmikvykhe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtcjfmvzrr.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtfrsmbtnu.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gtnmlwcamf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gtsadteqnz.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gttlvaneaf.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gtitatmxdi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtmvrtawbe.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtmcmuxcup.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtzfxrjuvc.html

Java: list.contains(x)
来源：http://dali.jianghu66.top/Article/details/gtqljcljck.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtplfoafja.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gtnhwmyapr.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gteogchawm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gtrlgrttgf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gtbuxjzgkn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gtiwkmmaxd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtqofzpzmv.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gturddoead.html

Java: new ArrayList<>(list);
来源：http://dali.xziqi.cn/Article/details/gtevpsexjf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtwcbogovb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gtgqeonfep.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtnbtfxidv.html


<!-- 参考信息 -->