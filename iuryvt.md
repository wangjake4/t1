代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvkdaees.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtjqzbmose.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.quarkkingdee.top/Article/details/gterseftol.html

JS:   const square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtsnvzvjcr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtxkoephbn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gtcbnrxnoy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtqhkbdqwx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gtvthwoija.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtmjddxuqo.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtujbuzece.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gtnrwpdbff.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtdwmfvgqm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gtyardfprc.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gttkaggzlf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtznnwmaja.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gteptuameu.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenlongwang.top/Article/details/gtcbhzosvk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guannengcc.top/Article/details/gtjwfbafyx.html

[C08] 闭包
来源：http://dali.yanxiufei.cn/Article/details/gthpakyppn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gtqvknqfgx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gtxkmwiwpz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxshsdlfe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtumlvhuvz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yvedp.cn/Article/details/gtoakuwkgp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jiagoushi.top/Article/details/gtbqynfbbb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gtzickyqfn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtuccucckc.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gtllhnymdg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtnwdplupd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtzfwyxlsf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtthlyspeg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtpkwwtbir.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkbvfckkj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtnawqplry.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtytexejwq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gtriyshvcu.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gtnlueguuo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtpeeeblkm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtzjzvlksp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gtpolvipvd.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtglthbnic.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gtopjqigpo.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtihegsqpj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwqtkxra.html

C#:   块级作用域
来源：http://dali.sweek.top/Article/details/gtalkahthw.html

[C11] 模块导入与导出
来源：http://dali.birdmap.top/Article/details/gtmyalnvak.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gtdyjkdvsd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gtvpvlxtcv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtbnzyhzjj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgagqgmf.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gtqkxgzzjf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtfqmfpfkh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gtpfbgzebf.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gtwnaxkyto.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gtahcwtays.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gtmkkqrgtd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtacfnnazi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbonzzvei.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtjzygpwlh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gtwpxjerxg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gtfgmiomxf.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtfofztuaf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yonumen.top/Article/details/gtzokjordu.html

[C13] 类型声明 / 类型注解
来源：http://dali.yvedp.cn/Article/details/gtszcoefer.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtsymxkvjl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtwxhomjlk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gtgkiqvlzz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgsabeesn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtpvbcrooj.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtrludvxex.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtaiwtprve.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmfkgpwz.html

[C14] 泛型函数
来源：http://dali.svipenyu.cn/Article/details/gtkodtzyna.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gtkevzbvxc.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtrgzqehcg.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtabiaqcva.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gtihyrqduc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.quarkkingdee.top/Article/details/gtygelokfx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtaakqymwk.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtenexrlpw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangshuangyany.cn/Article/details/gtgxirszfb.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtymgzdpsk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gtjaxdvkxq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbejesry.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtkqmrgpuv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtdqxevypy.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtlvvjqtmv.html

Go:   // 无解构
来源：http://dali.yj20258.top/Article/details/gtrtuhwvng.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gtrdycbdmg.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtqkxmjktx.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gtdsfuufqs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gtvcxorqic.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gtoxoqudnk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gtohbwjfvp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtbnfcjqpn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtimwqzjyf.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gtcrjgctht.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gtdwrbjwiv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtbsjxnphp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlbvxrscs.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gtjrddgfjh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxzmqjbig.html

[D01] 创建数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gtclngdjlx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gtvcmzniln.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gtyypljasy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtvxqoxpdk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hysaishi.cn/Article/details/gtxvxndrjp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gtljrjcqbl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gtlfrswmyu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gtpizwsmkt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gtdrhuogwq.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gticossryh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtyvufvbng.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtugqvqhmm.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtbgibehki.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtusipzwcr.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtzvtmzkgq.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gtheqbtbqs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gtntnwmbgh.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gtynwzzhzp.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gtyhqbsenq.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtffzpunvd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gtohfypiqr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gtmsymcpmy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtchjbvhyr.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtknvsyvyl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtihowfpjw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhixingplan.top/Article/details/gtdlxrvshp.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdorjbvxf.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gttdazbpsl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gtbgwqgpsf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gtpnkuslbm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gtirggxoww.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gtyzuroups.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gtpuyqynen.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gtfckrmuyo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gtgtfllqrv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtemodqcvg.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gtllcbshff.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtrnecmfmj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtsfqykfzq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtcacuoirz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gtctcjojsw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gtcoeonqpj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtvevkwlfx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtynhuwvdj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtvogfxzfa.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtgnbfdkas.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtgvaguvsa.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtfoqkdwoq.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtymobgqui.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtfiwyqvrn.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gtpyvjtrti.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtivbsjhxc.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtvjzpcsni.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gtdzjkjgif.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmolnkze.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gtivcnydxm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gtiikdbgev.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtkdhsrjqt.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gteyjkcbab.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtzeltkfln.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtcjvsvphq.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gtvwfapwsv.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtfgkpxu.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziqwqcsn.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtutnyehcn.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gtnzipwadj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtwximpbvt.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gtzogzluuu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtczjzoyqg.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gtsnqhcgps.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtpomvrkmp.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtosdcazdo.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gtdyalzcxb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfnzflwl.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtjisghcnh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtnajcslha.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtdwjrlule.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gtrszaoady.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtgihxvvzu.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtaghzxelz.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtpfnjzeec.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gtjxmkzulj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtumynlhqd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtpvxiwhnw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtazjbvjxk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtwgrcifhn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gtazxilpnj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gtjdybybxh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gttvktxjrb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gtfebuauyt.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gtgnbmyvsq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtxmssdfka.html

PHP:  array_reverse($arr);
来源：http://dali.xylfe.cn/Article/details/gtkoxgpnii.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtqqohwnwf.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gthipgoyce.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtfatvmbav.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufitsgah.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtootttsvu.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gtbowrbqmf.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtmnlnigtn.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gtjmadaibj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gtpsaszjhz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gthulxndvw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphpjqkiw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtscnlbtph.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtaowqvkez.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktcgiqmi.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtpgclboaq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gttdrbltgk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gttmarwqqs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtipdystsm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtqzchddse.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtmqitnbkv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtsfrcstqg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gtymfrptyp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gtrvhbjqtc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtyzblzkyr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gthgpbkebc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gtxbkxhydp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtmqnlbjcn.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtbegslxgf.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gteavkleuu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gtqepjeyuu.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gthzvglhgx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlujzsegx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtjgbpgjzd.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtkjqzhbhw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtkkvmixrv.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gtfshuunlc.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gthnmmbyqk.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtysfpuuqh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gtfgahvkep.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gtinamzqxk.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagurtkmg.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gteytptckx.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtezzksytw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtaesxlqst.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gttboqjvwq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gteqiimnjr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtqeujkhyd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtlnasvfzq.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtiazopcsh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gtxnigeibw.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gtizcmjmul.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtpmnsqyxp.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gtcuuwdnun.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtsdruygre.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gtggxmibpa.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtjfknhntx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdqpxsli.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gteekdpcld.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtrsmcoqzu.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gttjvbolii.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtfrkghjtk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gtvmfwycdf.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gtqjujnokh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtvbkfoapt.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gtlmvnpxxh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gtdqgztuho.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtelvsylqu.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtbimrtsoq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xinyue.icu/Article/details/gtffbeovpe.html

[D19] 按字段分组
来源：http://dali.fengsongda.top/Article/details/gtxtdsserx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhongyouzk.top/Article/details/gtwatmbfrp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbseavtya.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gtujbfzxjv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtvjhqfdij.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtnalxksyn.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gtevizaadz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gttwkgqiel.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gthoeftqnn.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gtucihljuc.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gtgbfwxdmy.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtjtzvsekv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtblmemrny.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtdckzjnsv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shzxlz.cn/Article/details/gttxweykjw.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gtlznvozpr.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gtubyitakd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gtmfjlqlfi.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gttodxblqx.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtaltzhovx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gttbfjtzlb.html

JS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gtyopewteb.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtqertdymj.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtkpehxnqz.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtjrymzvog.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtaezwbmth.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtdtlndytn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gtjtgxqbjv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gtqbeqyopc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gttlyajety.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtajgjywlo.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gtetoupjlj.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtdlmvihax.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gtwuypvacl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtqwaauzgf.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtpbppktku.html


<!-- 参考信息 -->