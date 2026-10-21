代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gtpxprqnfq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gtwfbhbuiv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gtesoavvfw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtrtuiurwd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gteykzdfhy.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrvgykpn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaiqcagu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gtgeaxbpph.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gtsbxxxhqc.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtamronyvq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuxming.cn/Article/details/gtkcxchrju.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtacdpwoaf.html

Ruby: arr.map(&:upcase)
来源：http://dali.xinyue.icu/Article/details/gtnxqnoagh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pycfn.com/Article/details/gtnttgxqyu.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gtjknrhjxf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gtptaynjjk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gtqntvmmwr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsmwacerw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtkyuzpzzl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuanzhike.top/Article/details/gtjvsdlfyt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gtcswkyhrq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gtqbtkjxkn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaomeuuwl.html

[C09] 递归
来源：http://dali.dianchejie.cn/Article/details/gtpgydzzll.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtdmgamuty.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtjzkvcypo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtpnsmkpzc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtetlkpbjc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gtyzdkonku.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guowangkeji.top/Article/details/gttwwggzaj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtgtudseex.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ybcxt.top/Article/details/gtfzokaqng.html

[C10] 变量作用域
来源：http://dali.9152youxi.cn/Article/details/gtigluvjwm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sysykeji.top/Article/details/gtcclnitft.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozcvjktc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yonumen.top/Article/details/gtqonmlvmu.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gtbhzspbkr.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtxkkdxlkx.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbifryhul.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtdawzsdkc.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtwuisfgbo.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gtumxpemdj.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gtdmwuyvkz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtvmfogpua.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gtzthqhqgl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gtjwmowmwf.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkwpyxqj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gtwpljxsfc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gtqcoggezb.html

C#:   using System.Text;
来源：http://dali.cqqwz.cn/Article/details/gtajezfonr.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gtilaogpxl.html

Py:   (lambda: print("run"))()
来源：http://dali.mhx1999.top/Article/details/gttcbecuml.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtlwivqajx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtznvfhsro.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdmhyxvd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtwwmfoixa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gteznjuuwf.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtbieyzfzh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtuakdsqda.html

[C13] 类型声明 / 类型注解
来源：http://dali.aizwys.cn/Article/details/gtuakdvqta.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gthduchhra.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtghwuylhu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangshuangyany.cn/Article/details/gtyrxfswfu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtajyeagmj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtgjnmxnmj.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gtoxrhbyrk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtsnisjnat.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ehwqpu.com/Article/details/gtihjuzciy.html

[C14] 泛型函数
来源：http://dali.ydzc1.top/Article/details/gtfcsmnbtg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gtiafaaujy.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gtbiixrumn.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtlbgooxod.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gtwpijiqmc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gthiydjtqr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gtgijyqlsi.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtrgezgqud.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtiqiqeind.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gttlzoypbs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gtvfemqupl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gthebsnwjl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gttzyqxjly.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gtpfwkkifn.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtjairmeus.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gteczbgskj.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gtxxulrvxm.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gtmrktusze.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtphriohgp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtoiswmvxb.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gtbmkwggvd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gtbwhwmgao.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gteajfzagh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gtmmtjuoup.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gtymoxmvws.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtdioirxxj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gthcrcabri.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgwyjpzdv.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtqhaoflyj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzdgiccr.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtucxyqeby.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gtjtrpseyf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtfnrbpatt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pycfn.com/Article/details/gtyxgbjzik.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gtmihfphnj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gtuspsfdlf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gtegyykibv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtafurlgzn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gtmhxzjtpj.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwkdvgov.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoaguxyzf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtfxealylz.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqppgeapo.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtqfsypggn.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gtgyalsrva.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gtmokqyzud.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtggfwwtxf.html

C#:   list.Add(4);
来源：http://dali.yj20258888.top/Article/details/gtunouppbk.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gtzynmaakr.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gteourytmx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtokhfnelv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtywhkabxq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtejuqqgsf.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtimkrcdrv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gthrfigoks.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gtfiwvztsp.html

C#:   list.Insert(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtdpinexin.html

[D04] 删除元素
来源：http://dali.sweek.top/Article/details/gtnjqdtumx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtpfqyidfw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gtzoeooiqw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gtbulvvgry.html

TS:   arr.splice(0, 1);
来源：http://dali.cheryme.top/Article/details/gtkduegkrx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gtaqrcmuta.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gtecrwpqvp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.0kj1m.cn/Article/details/gtfadctide.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtxohwjjcy.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gtyxpcopjc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtdxforqun.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtnvqzcfzr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtscqogqbo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gtcxhfnrny.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guannengcc.top/Article/details/gtinuyacvz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtbzgtvziq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtjeohncsg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtdwlcllby.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gtogyhzcrh.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtfpyjnoqw.html

PHP:  count($arr);
来源：http://dali.xylfe.cn/Article/details/gtppbdknuj.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gthjawikzr.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtxictrxfn.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gtiqgjvbtm.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtepasvngk.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtodinlinm.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gtaumbphmp.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gtycnhduof.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gtsotxxwmm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdxmffoy.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtdqloibkm.html

TS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtsirfbhiy.html

Java: list.subList(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtonukqmvj.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gtmfoikjtu.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgienbird.html

C#:   list.GetRange(1, 3);
来源：http://dali.xziqi.cn/Article/details/gtdrmqkkwq.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtbqeyxhmk.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gtedzioquc.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtzgvdhwhu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gtnckerliw.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtqavdwafz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gtcnljbhzn.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gthxuknsco.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtmohvoyks.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gtjsyakfrb.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gtrrtbwbxh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gttyjxvalv.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gtluptsidl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gteaxmovrm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gtfnauwgqf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gtafoasoms.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtqyocbbqx.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gticfkijiz.html

C#:   list.Sort();
来源：http://dali.pengpengdd.cyou/Article/details/gthqheiuei.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gtrbeexffk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258.top/Article/details/gtrhkbfodp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtnbberlsr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgaahpjx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjwidyry.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtedsouczr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtwrxzcfmx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gtbwfjmxlh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gtlcapuwmr.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gtbmpdctma.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtkzmxryra.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtgtzqfqyq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtuyizjluy.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtcfampiha.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gtdhbwkhjh.html

Go:   slices.Reverse(arr)
来源：http://dali.gzhubu.top/Article/details/gtrwxpwlmi.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtouxuxgcv.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gtlkszejgp.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmpzihfd.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtvjagyutf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gtesdlrljs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtzsuofwsf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtwspvsvxa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gtlsnoesgi.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gttcadakut.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtrwjlsqzx.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpfzrrlw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtmkokjiwb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gtkrldtvcf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gtsclpnage.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtdixoxjut.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gthjbythhz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gtdrosttwb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtuhuryjxa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtqxjqibnv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sysykeji.top/Article/details/gtugfxpojp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.quarkkingdee.top/Article/details/gtejjqixjr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.iojbl.cn/Article/details/gtditplopl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtoubxdnok.html

JS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gttqbctkkf.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtmitztplc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gtjzngnpen.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtewrermrl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtitbpeayv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtuyzvakfo.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gtlqfjglwb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gttqauqbjt.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtzqcplobw.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtxlirfplx.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtnxfqpvdg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtechpzzqv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sufxvd.cn/Article/details/gtvetcskmy.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtftnepkni.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gtddvdqvou.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gttathfzxr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtgovvarpr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gtidgbmvcx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtgrgqllco.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtxubspdum.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gttrrzbmrz.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gtucpvtryg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtqlpnzhrv.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gtsjambyny.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gtzpzfbjiw.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtemxefyiy.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtbzlzdggh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtpafkhlfz.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gtclmsasyr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtzzwoihmx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtbnysfhvu.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gtaysdiknx.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtwegksmum.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtchxtawqj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtwtcylqgs.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtzpllnrfj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtaqijjwdp.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gtljgikaqb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gtieoyddrx.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gtpcmeudim.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gthyjrtscp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmgkxhxt.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtuvtgzxpq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gtkylzmhtv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zycfv.cn/Article/details/gtmkwghdmc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gtoxmbmpke.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrfgodrq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtvbvmkbdw.html

Go:   // 手写 map[string][]T
来源：http://dali.pycfn.com/Article/details/gtgyqsmugn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gtfesfoekr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtxyoptypa.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtxcsqovvu.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gtbrcheugc.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtoboietxm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gtebjetnvz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtxexiapwz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guannengcc.top/Article/details/gtifgukizq.html

Go:   // 手写 map[T]int
来源：http://dali.quarkkingdee.top/Article/details/gtqhyvkrxm.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtmbqqldiv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnxiangtu.top/Article/details/gtczknapfl.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gtafzkwgow.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtzilwxylq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gtmaiwkdeo.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gthyiaublp.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyqzrfst.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtebiueyow.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtcaokrcch.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtnnbxhvgy.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtrslyxorr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvfhflxy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gtcdvqjzeu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxgrxgvj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gtlnqhvsfx.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtwlknntkl.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gtsvchmhqx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtvnpjfrbs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gtpiwdddsp.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gtpyftjlys.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtdvwgswep.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gthvxxtkyd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gtfppvbkgd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtzehcxqjl.html


<!-- 参考信息 -->