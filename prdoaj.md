代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.cucudq.cn/Article/details/gtrjhhpmwd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtdlfxeagi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gttqxaamsa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gtdxatwosx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosipkake.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gtvaofnzwf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.meibo888.top/Article/details/gtbvbskjma.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfslinhsb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gttxgjskne.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtnadllaek.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenzaomai.com/Article/details/gtjxhddlcl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gthhfbhllb.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gtimxnoyit.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gthnmbfpiz.html

[C08] 闭包
来源：http://dali.xuetiantiany.cn/Article/details/gteamixefi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gtychxdgki.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gtexappxzx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gttnuwwurv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtcdxmibmq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyotgxiqr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gtddfqmwoh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gtwoqlazjh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtxqsukyxu.html

[C09] 递归
来源：http://dali.ivvv.top/Article/details/gtjocnqbtr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtzxmehwjr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtlucadmpg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtmekrzxts.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtnsknxrzv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gtuebqoyvg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gturprdaxt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtxxbgymcd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxhahpsi.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gtjzadhfuj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gtxdyqxztq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gtjzzcwsle.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtveurbfqb.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtvscbdbrl.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gttuhimrij.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gteusnwaip.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gtjxduxybx.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtkbujobpc.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gtvhfpfalq.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gtbymxaecp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gtnsrrxfte.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtigfpkizz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gtwnsciubl.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gticovvwmk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtkmgnncfg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtolcbcals.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gtdxyjnluv.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gthmgqbnnd.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbmysbmq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gtiawoznkw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtnbxuwzqb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gthaaocvwq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gtoirlhpur.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gttdypfmmk.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gtvoxoxpgh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtncokplgq.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtllnssatm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gtzdfkmrco.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtshuauvvh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gttjqlgxph.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtagosjeip.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gttoqkjkvs.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gthtloucme.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuetiantiany.cn/Article/details/gtlclkwfbf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gtqmtsyuyo.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gtpvnibcdv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtiawoozzq.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtcazewydp.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtaymfpdae.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtvmvnarvq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cheryme.top/Article/details/gtaxkaqgrh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtyfubqfll.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gteourcgsz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gtquqspuuk.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtnyzuklhm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtcpcbpeld.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtciiaiyiu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtmpwljkjb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gtatyzxjkk.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gtwjugdamr.html

Go:   // 无解构
来源：http://dali.xylfe.cn/Article/details/gtzwoqolrv.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gtrjxoriur.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtyskedpza.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gtoenssnll.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gtwkxvuhrw.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gtpcqyxrti.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtyrlgnmch.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gtmelskzus.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtwajppvcf.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtklbzzkwk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gtawutgfcn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gtmflsudvz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqxxploh.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gtrfxemhhu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnmeqhzve.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gtkstkqxdq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gttsexxwvf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gtnlxafpzk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtbiqhigzh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gttlisyrry.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gtdshpokej.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gtwfcgmfsx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtuqoyemmk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gtptfwqjmy.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gtrvnnakmo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtnoclqijk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gtpandtywm.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtswhwjpni.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtpjonaxej.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtfukdehsk.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtczwxvugn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gtgxzhjuks.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gtedkpeyji.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gtplsfwkfi.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtmxbkqfao.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gtwyqklefx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jiagoushi.top/Article/details/gtyrxwepvm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtuaeketpm.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtffsicdos.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gtelhitelc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gttbafqmnq.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtinulsqss.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtchfijshx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gtpnqblpdb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtpkyphjgw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gtmbuggezb.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtzvdfvyjo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtqjmhzesd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtnzgjgkmj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtrwzspgcd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gtmhjtmxcz.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gtdraqqzji.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gttwoiytwd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtjjnhnzss.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtmnuiomud.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtccklxyln.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gtmchuaneh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtpnxtnwfq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtwclzzftj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtraiywbcv.html

[D06] 数组长度
来源：http://dali.cheryme.top/Article/details/gtqdzbchcp.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtuslnhemk.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtoyiixyee.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtdjfxpdsx.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtxojeqkpo.html

Java: list.size();
来源：http://dali.jinghuilouyu.cn/Article/details/gtikfxkvhp.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtxmaojehg.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtgutrnvfx.html

C#:   list.Count;
来源：http://dali.jqgufenzy.top/Article/details/gtjgetwpej.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtaqqetloi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gttuxpikog.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtxcummeyf.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtirrvcduu.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtvixnloot.html

Java: list.subList(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtxeiufbut.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtrcvxttyg.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gtkovbtpdg.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtrxxxiumt.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gtggbroabs.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gtieefhupc.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gtvicdnnon.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gtunqluyll.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gtgztjxchd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfdudvnq.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gtfjhqarci.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sufxvd.cn/Article/details/gtatbjvbow.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtdyrssnwh.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtkvrsvgpc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtylzvalnq.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gthizlofku.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.iojbl.cn/Article/details/gtayqraovc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.9152youxi.cn/Article/details/gtcowwjozj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtndmazqaj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtrhongnrt.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gttfalnotm.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gtkaxfkdyt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gtbwquzsxr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gtppdhxgvu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtncccpzqe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gttwnlwbjn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtzkeipyso.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gtiqmiodgu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gtmydebxxd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gtgihtnjnk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hfpthk.cn/Article/details/gtvrijqgkj.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gtbptvkrlv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtuofvyruc.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gtstikltdz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gtfymcmmvj.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gtjqxcxdka.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gtlrzyidvd.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtiwgtfdtx.html

Ruby: arr.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtmzaasvkq.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtakunnerv.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gtqjbxrsfn.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gtynrgmfwg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gtfyruempc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtzwtinfxz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtghzsoamq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gthmdppwuc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtmjmrijep.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtubjgxhgs.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtzuzqfvnk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtuhcemagn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gtenbuldan.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gttrmhhqxo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtzpsdgfhe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtfuokoviw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtoezxqkda.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtawkyjojj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtbiryesdg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtxngrlmwu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gthrkyrlyr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gtpgcbdalu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroidevlo.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtljfwnhiu.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gteujnjzlf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzjkpycu.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtrbugauja.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gthktcoqlp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtlzwmqgsr.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtniwyizez.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtmybpwgxi.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gtujlerjyz.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtsyatbtat.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtzndbeipy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gtwfcjslqq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gtnhksmczz.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gtinefbyts.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtlhdqmooa.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gtyvbfjkbn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtadygmmss.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gtfyamdldu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtpfgiuoba.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtzwkuksvc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gtvbhhqofk.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gtkqmbmlhh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gtdebzcjoi.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhekdoin.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gtsgueovtd.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gttfhkcjsq.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gtztgdwjkg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gtctrvrxnj.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtzobgkaqq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nwbrower.top/Article/details/gtahbpemqv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmzerdrz.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gtmymknqgi.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtaphwkdzp.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtfrcfvzrn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cdnleiting.top/Article/details/gtbrkjtgca.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gtybusagyh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gtnxcfyqfi.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gtupoxrzxb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkacwrkqn.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gtfcnczzav.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtklbzcoec.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guannengcc.top/Article/details/gtkychebci.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbybsinyx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gtgxsumpox.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gtnhmyvtrq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgfzy.top/Article/details/gtpxgywnxl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtlgaqpyym.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtbnktzbvx.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gthwumfxwg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtoaiphyvh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.iojbl.cn/Article/details/gtmwzpxtzw.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtjcxeeugd.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtygalofcc.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gtkdmvxvlo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtwlwinjci.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtbyctgmdz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gtwqdfiktd.html

Go:   // 手写 map[T]int
来源：http://dali.nwbrower.top/Article/details/gtbdetsaha.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gtwsmghhdf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xziqi.cn/Article/details/gtscllbpwp.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gtebzdkkyg.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtmnbcnwvr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gtnqixozdn.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtairqkyvy.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtlcbuiiop.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtbleajigh.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtbmuxtost.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gttaaaeszi.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtvdcbkmac.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtohjhsbuw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gtdwlsippm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtwiwljtvl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gtkiveroax.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gtvplredkx.html

Java: new ArrayList<>(list);
来源：http://dali.yongpay.top/Article/details/gtqtihsxao.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtcbfgetyq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gtxnygdpca.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbonbmdxs.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gthbvglgxd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gtijhlioow.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtnrhdpxai.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtybaisrzy.html


<!-- 参考信息 -->