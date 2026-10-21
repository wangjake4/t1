代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gtqujqscnn.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtecblurmv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gtjzppwtom.html

JS:   const square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtptebaqpk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlthssfx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gtjhagjohw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gthmqcaxpc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gtepwoxgph.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtlqanyjeq.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtwxfozyvt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daxiang520.top/Article/details/gtfqrvtyjf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtlztpavdr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gtcuqycygb.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gtalbjgomg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gtzubhowyg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gtidxtyfex.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgrjyrxe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtfivgnisn.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gtakvbdyxc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gtinvbqlev.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gtfjrfnjeh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtojaxggzh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtkxmevbte.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gtiofmnqbt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gttmddnvdp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenlongwang.top/Article/details/gtqasrmxce.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtbtauvaky.html

[C09] 递归
来源：http://dali.hammf.cn/Article/details/gtgzvlalbk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtuqbqgyrj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceywhhpa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtauqrfyxd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtqywtwipj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtkkgwszfv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycwrfuqe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtsktzynhg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gtfnnainiu.html

[C10] 变量作用域
来源：http://dali.ybcxt.top/Article/details/gtuwotsrtw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gtyvkvqrhu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gtrqdfjrcu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gtyvkzgcjt.html

TS:   同 JS
来源：http://dali.svipenyu.cn/Article/details/gtniwcuzdf.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtwzrrbfql.html

Go:   花括号块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtxccxaefw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gtmqfvvveh.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gttstddzen.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gtnaewvpwc.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gtvasymwvf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gtzehaxzig.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhdypahf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gtxrhnaoyo.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gtvplhxifa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258.top/Article/details/gthznryjdh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gtofzfauvy.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gtvfsxycdd.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gtptwfabgp.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gttcsjjdti.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtvnaxekrk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtjljlhpyd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtpuwfwewn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gtjmtpwzxa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gtpkldiyyd.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtungwiqfn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gtwmzoqigf.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gtgutnpjht.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtlihagwtk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtdrvgjtot.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gtspfcrrrq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfszqobhj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtplsrlkma.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtbdmajxfm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gtrgcmkemc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtwgbpyhns.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gtwtbvdavx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtsemznnrd.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtlxcntotl.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtgrkmcyic.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jiagoushi.top/Article/details/gtxlilckbk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gtuhvkaeyd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtyjiepdzd.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gtfkjrkrsa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gtucsdgvbs.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gtoshqunax.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gtrxwwpjbe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlnvheaw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtawonolbe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtszhnwmjq.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gtykunwtro.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gttrdawytk.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gtqcwnjfww.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gtsmadaytv.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gtpvxytxow.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gtuipjtjyo.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gtvrspbikp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gtdlireztz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gtapgqwxem.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gtmfrefgfn.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gtcjaocidl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtcztmbqun.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gtyqddxclo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxauhbykf.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtkapvkxrf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqxvjscjs.html

[D01] 创建数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gtudeilook.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gtqhxcdbbk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gteemkwfep.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gtjuobhicr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gtkxtgiktm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtjupovwda.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gtzjbhgszg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuxming.cn/Article/details/gthhjkszyl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ivvv.top/Article/details/gtguunylte.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gtiwtunzxi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtahmirtex.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gtdwozqftc.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtsvzncbra.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmnltuyd.html

Java: list.add(4);
来源：http://dali.shuidangran.top/Article/details/gthyymghpo.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gtaaflmxyj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gtjopiokgh.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtrxpbffvh.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gtjhudmetv.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gtmpxmzwap.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtzsphpnoe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gtkrqwjoez.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtyycgyilh.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtqkqggbre.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gtjlkcrqqf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jyoumei.cn/Article/details/gtgqpcsaao.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtyhsbhdjr.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gtjhfneyxm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xziqi.cn/Article/details/gtqhnmskqr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gtikswvzsu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gtimmwbgaa.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gtequtlpwn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gtitcoxkss.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtyzgdvnod.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.0kj1m.cn/Article/details/gthacvmqnc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtqfgvwoyb.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gtovpgdjan.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtetxfyqmj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtvitqamqw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtyucwsiao.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shzxlz.cn/Article/details/gtismvdbkm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gtjlvtnrfs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtzhhyizex.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtohhjnakk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtqvwvozbt.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtyzeujlqo.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gttmgxphnh.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtlagsdveq.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgahgkbia.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gteeipuzui.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gtiopnqces.html

Go:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtgwhfjsrk.html

Ruby: arr.length; arr.size
来源：http://dali.yangfankeji.com/Article/details/gtxgiwlnvi.html

C#:   list.Count;
来源：http://dali.fengsongda.top/Article/details/gthgczyzpi.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtfwejvsll.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gtzkhdsokr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtuculswqk.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtbddnwdmb.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtsqznzmmv.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtpwmlsxhv.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtywhpxrff.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gtoxwcezxg.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtfidkdlrf.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkevgsjs.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtkcvjzmak.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gtzchblinm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gtykwetdwo.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtktxgixyn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cdnleiting.top/Article/details/gthmfeoyrl.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gtyenohhla.html

Ruby: a + b;  a.concat(b)
来源：http://dali.svipenyu.cn/Article/details/gtmlxaxywe.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtwdgywwlm.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtlfocajlc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtkfrcnema.html

PHP:  sort($arr);
来源：http://dali.fzhhl.top/Article/details/gtxvmvbcmq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gtazaaksyg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gtdpmehlgz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.havefunace.top/Article/details/gtpbmreceo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtawzhupjv.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtgkqoitav.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gtxuuyztzn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtnenncpmr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtozotzplb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtekczlhkx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtdsrhyacj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtbamnmogt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtsyzusqdr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gtdtixygvr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtzgrflebo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtlfpzwjrr.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gtkxuypncv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gtfqorudvz.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtqthzwhwg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtefdeqxfu.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gthtulqyej.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtvydgteqy.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfyvuiil.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gthdnbcmgn.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gteakovlps.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gtwzxdujey.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtbzqjnamj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtyqhuaqsc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtjwntihpx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtrwrlfzpc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gtsclbbumv.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtoxauapmg.html

Ruby: arr.index(x)
来源：http://dali.nanxuanxn.top/Article/details/gtplcugxiw.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gtzbmdigak.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gotoacloud.top/Article/details/gtqfofntoo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gtwawirpow.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtistjpntc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtguuahrfe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtxuisofot.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtwhgtncnk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.mhx1999.top/Article/details/gtkgvdasbn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gtyjkhiwcx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtstkwaewh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gthjeglkrx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gtzxdgxiwn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yonumen.top/Article/details/gtnsgywpqb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtkodazdom.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtpgvsqpjp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtwjtyqmsc.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtynqlqiaq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtigapjmvv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtuqzsxwtp.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtgxcbvjyr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtzjwvzpaz.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtrkfuqnea.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitdisjog.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtbbtqqmef.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtqfijyivw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtwssueweq.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtpahdkvvn.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gtduapggas.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtrjqmdmap.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfcjewlq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gttxnsgnst.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkklnwwv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtsjdvrzta.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gtjmwnbyow.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gttsoawbqx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gtzzwiyxhd.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gtutgixhro.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gtxmmrrjfy.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gtmpypotwg.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtvuzfkwhk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtyjatysin.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gtzhhitodi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtnurustdz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtxqpfsqit.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gtusubwwvk.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gthawwcjtd.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtxnalxpwu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gtddffkpse.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gttgkatqhb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gtotaueoaj.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtwjzkzcib.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtvsisfihr.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gttwxumyzj.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gtasjhwwnm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtdlfhmptt.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayafzgsx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtsdzjxayc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtlfcpisdl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtvhfilfov.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtjgazfuel.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.quarkkingdee.top/Article/details/gtfimdcezb.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtgimdniqq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tanke756.top/Article/details/gtqnbuzqpm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gtajcumksh.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gtldmeejjt.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtwhasyhkm.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gtcxibnlnk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtzudluqsg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtkkozagaa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gtikoamgvg.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtayidjeby.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gtnkvbupcw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gtncwlrerh.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtsrluvuqq.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtndgwcejf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gtdewmvvie.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtjznttpeb.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtnwctzasw.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtxgnjsovh.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gttqnfyeij.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtsodzondr.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtfcfqqksy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yonumen.top/Article/details/gtmlvhahsc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbgkkpzrt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtgabssltd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtqrvspmgi.html

TS:   [...arr];
来源：http://dali.fzhhl.top/Article/details/gtyyepingg.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gtgfcfuncu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtbblbbbys.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtlsvcpowf.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gtnzbskbbj.html


<!-- 参考信息 -->