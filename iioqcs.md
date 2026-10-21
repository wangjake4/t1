代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqzocprh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gtkebpujky.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnqzz.top/Article/details/gtfewfrxgy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtbrvsyqom.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gtxaqltovy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.svipenyu.cn/Article/details/gtlsjdypll.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuxming.cn/Article/details/gtpukweatv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtabrqdmcq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuanzhike.top/Article/details/gtmwyngiok.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtszpylsyo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gtupumuvth.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hongshengwenyu.top/Article/details/gtaapxthpn.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gtnlyzuidh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtsnaktggl.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtwbfjgyxr.html

[C05] 返回多个值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaixslwyb.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlegqvuel.html

PHP:  return [$a, $b];
来源：http://dali.ydzc1.top/Article/details/gtfvtxdalc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekuliram.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtyrwrrywe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fengsongda.top/Article/details/gtnpvspdez.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtwtdntlml.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gthjcvvxqy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtpoqqeshq.html

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gtrkzlcwhn.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtehuejtom.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gtjkxrxoco.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtuvjibxbc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gtppeqshmh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sxryk.cn/Article/details/gtrgnbejhr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gttvrwvijx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gtdrobzlxk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtemplniyh.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gtvothquoj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gtyladpdyp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtktjkjfcz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gtutshlpex.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtbgjxpeay.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtdrkaxzcu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gtukcivozy.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258.top/Article/details/gtdgtnxtxr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gteuxxalyz.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gtawxgxpzi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gtenvqxjdk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gthcxnkrzi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtvfftygeg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtbseogdky.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gtwdqkxmtu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.kuanghao11.cn/Article/details/gtjqqnakcy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.redwolf501.top/Article/details/gtdduhmmac.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtsqqhinpm.html

[C09] 递归
来源：http://dali.quarkkingdee.top/Article/details/gthofvzlne.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtxudntbpp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtrabyexhl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gtgalmvsdc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtkuotvbzy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtaqkhvovi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtwqucblem.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gthzymqocu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jyoumei.cn/Article/details/gtlxduxavz.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gtcqyhztja.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shuidangran.top/Article/details/gtdjsfdemp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtponveudb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gtpbubkbqw.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvtmdumg.html

Java: 方法内为块级作用域
来源：http://dali.hnqzz.top/Article/details/gtftxxivuj.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtibghyctm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yongpay.top/Article/details/gtdgwlkasp.html

C#:   块级作用域
来源：http://dali.sweek.top/Article/details/gtnkeobnex.html

[C11] 模块导入与导出
来源：http://dali.xinyue.icu/Article/details/gtdteevwuv.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gtznxfwfhc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gtztsxgiem.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtagjmbbiu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtzhbifmtv.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gthssprrqj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gtnarymdmr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gtcriamuzf.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gtzjchugbm.html

[C12] 立即执行函数 IIFE
来源：http://dali.xylfe.cn/Article/details/gtwemdfucp.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gtpqfqsuzk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jlsjyb.cn/Article/details/gtupgekwqd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtbpoztvul.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gtjdwtludp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtutgqvgjf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtkhdfyopy.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwonmgeph.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtvsprhxww.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gtplbhvxmq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtdwpsbryx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsxosqzgl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gtmkvsvioh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtrtowfhac.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigqzwjnv.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtxxjbgxgz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gtqyecfgep.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtbxpuecck.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtumeirxpb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gtcqsjrdbg.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtihaduwyf.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncuszkcs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gtkxxheiur.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gtnfdnhiwh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.haohaochexian.top/Article/details/gtewmyjaxf.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gtmatjrbeo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gtxubwocjl.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdevdrnps.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtrnimckff.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gtaywdpgeu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtfrmlqlcx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhxmbiki.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtzgivjamu.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gteywozypv.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtexqulekb.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtiwzmnheb.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gtbtigvvkb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gthidlxcwm.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gtbudojiib.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gtcxstaleq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtpglgywtq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqleptblt.html

Go:   // 无重载：用不同函数名
来源：http://dali.pycfn.com/Article/details/gtlrwfxiwa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtiiwasypi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gtabatedgk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfwprzoah.html

D. 数组 / 列表 / 集合
来源：http://dali.redwolf501.top/Article/details/gtjigylrik.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnhzblzyy.html

[D01] 创建数组 / 列表
来源：http://dali.hnqzz.top/Article/details/gtzqvezssa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gtsfqqckvm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258.top/Article/details/gtbcakejzb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmiztfob.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gterkakagd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gtsomotmzg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gtmpylymgn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtfizfwvoc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gtmrwskwln.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gtapprnqrz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gtwwsxeuqr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gtrwachodn.html

JS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtrvcmhgwd.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtemrluwbl.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtcayfxcqm.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtbhwaxvgq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yangfankeji.com/Article/details/gtinqgqdhg.html

C#:   list.Add(4);
来源：http://dali.dashuyun.cn/Article/details/gtugctkqmh.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gtlyjtqgcb.html

Py:   arr.insert(0, 0)
来源：http://dali.tian-w.cn/Article/details/gtirszzfyz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtazdqlwqo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtpklpeoaz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtpirumird.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtmvquilaw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gtfzoupczm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gtdrspynwq.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuihdxtjs.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtthhdrwpi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gtmgsoycvu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gtgpmyupxw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gtmfebkxpf.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gtfcawjnnr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gtbauwkgun.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangshuangyany.cn/Article/details/gtzfkcxgyu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sufxvd.cn/Article/details/gtgrgoijjb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gtjniyxqrx.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfknyksv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtbecjdllb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtsgxcfjwg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtnjjiiwyz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gtsirtavbm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuboatlt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtevnwilnt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtsxnxfgxa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtkpwshytk.html

[D06] 数组长度
来源：http://dali.cheryme.top/Article/details/gtjawmzlat.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtqswwpgnu.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtiqhlkpie.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtgohkrrrn.html

TS:   arr.length
来源：http://dali.sweek.top/Article/details/gtemkcahkr.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtrydkfnji.html

Go:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtlgsagdxh.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtjqxegfho.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gtxlmaiifo.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gtwexgahsr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gthfzxtzbq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gtsovazbfw.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gttjddiulk.html

TS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtrpaygdwd.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtfnrobmie.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtrufmgrma.html

Ruby: arr[1, 3]
来源：http://dali.daria6918.cn/Article/details/gtrglbfffz.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtlymezvln.html

[D08] 合并两个数组
来源：http://dali.wangshuangyany.cn/Article/details/gtkzdrqrgk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gtluecyjli.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gtqxqwgloq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gtdlbbsfjp.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtdhogdxsm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yongpay.top/Article/details/gtkizauowc.html

Go:   append(a, b...)
来源：http://dali.xuetiantiany.cn/Article/details/gtitvniimu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gtoyqksabj.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtludsijio.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gtkhwetxof.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtquyuwzwm.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gtvkykyynr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zdqjudy.top/Article/details/gtbaazdmkq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtpsxipjjd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gtrgwvlpjp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtqzjbbjlv.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtlqnykkbq.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtrwdgjmfb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gtdzxnqstq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtvhulbktx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtzmckamgi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtywribbbw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtryvzucdm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gttegozlya.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrssfvfl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtkxqnxssc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtupbvvfgz.html

[D11] 反转数组
来源：http://dali.quarkkingdee.top/Article/details/gtwmekalam.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtmeitkdvy.html

PHP:  array_reverse($arr);
来源：http://dali.yuanzhike.top/Article/details/gtvhukgcux.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gtsqqwztmw.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtyhmikjul.html

Java: Collections.reverse(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqueouslb.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gtqjnpphge.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gtxcqaclsq.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gtfnqlzobi.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gtwycglvkt.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gttmqfuvpl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtaqaztyph.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gtrjjvjrwz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtdzvntlwh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xziqi.cn/Article/details/gtpzwlznzz.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttebitdij.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtgclqjgvi.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gtfitsvbwp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtiaowrybs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gtrpsxvwpc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gtprysiqzz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gteeguktar.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtynbryiht.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtzhjdjnfd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gtyfaurlhr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtzlaflsqn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbebbcekc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gtwggjrvpq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtablzkepl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtebnlltdx.html

JS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtslcebfoh.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtafserpbn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtavsgaipk.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtdlioxaxu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtckyngjgf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtnvwgghab.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtghlddwyi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtlhyhkxsl.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gtbopjoviv.html

JS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtwmymtwga.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtdaggwduu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtwxacxiub.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgghqmpq.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gthldlbqqj.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtficbphpf.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtmgxqibhs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gtqsdbrvqh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtdadiaoao.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gthqknfhmm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtgyqlkqzl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gtvumeyjay.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtlfgnndyj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtzjldyxvr.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvkzskcb.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gttqcbguaf.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gtjqmwcqxk.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmemgnmec.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtrcxmukxe.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gtorwptmku.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtjkdoqzut.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xziqi.cn/Article/details/gttshyupts.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gtrbulnfcu.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtnuetdmqi.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gtqkmvmeur.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtkamajgxp.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gtzcfarzfy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gttagougfb.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gtvynuyjmt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtgzygdvdy.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gtueiffvnn.html

Ruby: nested.flatten
来源：http://dali.snrcjt.cn/Article/details/gtwyiumlfb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gthezvxokk.html

[D19] 按字段分组
来源：http://dali.fengsongda.top/Article/details/gtvjfsfjjs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gtjapxtubz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gaohongyu789.top/Article/details/gtzwxvvpms.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnoxwmhx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gthxsktcai.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtxhqqacii.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtgrgsjsyu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gtetdneqkc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gtlufovrnh.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gtnydgtqhq.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gtdtutimyp.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gtcicvlxcz.html


<!-- 参考信息 -->