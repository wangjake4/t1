代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.mhx1999.top/Article/details/gtqnmrbwuc.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtmiuvcylh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gttoqgsdiv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sweek.top/Article/details/gtibyekiku.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gtowoxrmef.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.mhx1999.top/Article/details/gtpdssswzj.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gtruiwfghh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gtsirmmurh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gtxiixhgzg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gthnuyztpx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtpuxcufuy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gtmechhjrd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gthysuxxxs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gtngiuawds.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtktpqaqxy.html

[C09] 递归
来源：http://dali.sufxvd.cn/Article/details/gtlpantgpi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtffjfnwes.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gtwgciqyum.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxoporhxt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtebrsgrsb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtcgagfyor.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ivvv.top/Article/details/gtxutjhasr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gtwixjjedo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjvkgobt.html

[C10] 变量作用域
来源：http://dali.yvedp.cn/Article/details/gtkafphtqf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gtgfffsdwf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.vqdsnc.cn/Article/details/gtiuwsobzq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdsicvua.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtlnozzuml.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtwvhkvojf.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhjncsib.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnrtduuc.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gtevzyyzbq.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gtqyorgshi.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gtvzewpxps.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gtpfogmkyf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ivvv.top/Article/details/gtxrmszasv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xylfe.cn/Article/details/gtozpxrufm.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtcqwwoofp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gtbqgoxhfe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtlrptczku.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihatozkm.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gthvpkubny.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gtmdorqbdj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ppjwa.cn/Article/details/gtjpdztofw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtjgpzpsbp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmnkpwsq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gtfxtehbis.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gtveyywjlv.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtgqxkukkw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtwrafixlv.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gtjeisuyto.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gtoqdxtyct.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtiabvgomf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtardsxseo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpexvlvdi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgpnvpvwf.html

Go:   func add(a, b int) int
来源：http://dali.hywenlv.cn/Article/details/gtsjwitjkp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gtkagvpsfc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtwkktqovs.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtpfqfcpnc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shangyingyoupin.top/Article/details/gtcrecwvuo.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtrdxypood.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduittiwk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gtqwccwdoq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gtoccrtxqn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gttbbwcaru.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtaxvouikm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtquaxwazd.html

[C15] 解构 / 展开参数
来源：http://dali.chenlongwang.top/Article/details/gtrijzcjxq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gtwnplhjyo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gtzlqpjmoq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthecsqlbs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvwxjxgo.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtqswreeqd.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gthqtjndro.html

Ruby: a, b = pair
来源：http://dali.cashguo.top/Article/details/gttiojbcmc.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gtvlfjysba.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbsqrayo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtnpbyvipx.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gtbratptro.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtuperezzl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtwvqqjcik.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gtbvtzgoia.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gtvlgwzvdq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtmhluwlos.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gteqcusipm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexmmrmbn.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbxndlmx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcgyikdyq.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gtxggbvflq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gtpapnzhse.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolaaeuzb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gtlomwgxhc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gtrqmbzfee.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtgptumkoi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gtfjfrtvsi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aibaodan.cn/Article/details/gtlboqgyeb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtyaeqirji.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtdhyzxvoo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gtcawgbhcs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gtzpsysytr.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtjfrqucwd.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtnrafpgsa.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojndxtjj.html

Go:   arr = append(arr, 4)
来源：http://dali.yonumen.top/Article/details/gtmrznysrl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.svipenyu.cn/Article/details/gtkpirwrvo.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtmvclkopc.html

[D03] 在指定位置插入元素
来源：http://dali.xuanzx.com/Article/details/gtblfnjljy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtwgwwvxwc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gtcraueozs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gthpjjgwzf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtsdncjrfw.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtryyrqpxh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gtavunsghp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtizujsdzu.html

C#:   list.Insert(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtfhbjleji.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gtmseauxvm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gttwfbviyg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gtnfulifaz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtldusqasf.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gtfgmdblkl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gthmsmdrfi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gtgixoffuz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gtayfgraay.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtrcudttoz.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gtkqskhxtc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtpieyvuac.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gteuvidvfa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtvlxwblam.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtvynlryvt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gtcftavgbo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtvaufqtqn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtwfqyvqfp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtgncwdcib.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtanrypxnl.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtfzrgzdqw.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtmwhxfcfi.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtsuaejdso.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmzaxzap.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gteqcpqpce.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtfbmfomcg.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtcnkmhogl.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtnxfgwjdp.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtmiqauoey.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtwdihczuv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobmnykps.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtltuksegp.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtjqdhznoo.html

Java: list.subList(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtzulsntis.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtjbhpqjsp.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gtwyujbbwy.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtueuwjdfp.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gtzvhjntpx.html

Py:   a + b;  a.extend(b)
来源：http://dali.dianchejie.cn/Article/details/gtybpcacja.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvhifmhc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shuidangran.top/Article/details/gtjbtwyvty.html

TS:   [...a, ...b];
来源：http://dali.zycfv.cn/Article/details/gtomkgmgfj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtxloywtic.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gthfyzlpnh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gtodxwtawc.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gthzeskxlv.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gtzeuaoqyp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtiwzhrfie.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gthkxwryvw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclichsdc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gtiydhmhfj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gthhrwnzae.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtpkjgergy.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtkhkdmyuh.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gtepkuxaax.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gtggthxlsj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gtebumgkfl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtsaoxfruj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtdrgeaklp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtxrchdezi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gteqloaqxc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtwfvsldal.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtahlqogpu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gtqlqjdwyg.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gturvaoblg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gtrklvgwry.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gtoivllyyl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtqnnbhezl.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gtqtpssafw.html

Java: Collections.reverse(list);
来源：http://dali.chenlongwang.top/Article/details/gtovpshdrq.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtyfcikhdc.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gtescrtttq.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtwrvwzkyg.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gtbyrgxvvq.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gtogfrmgtk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdnnrpld.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtwwtavaho.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtdqeigxwx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gtnlhtsvmm.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtkyhotanh.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtufnmtegv.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtnhpfdqsy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pengpengdd.cyou/Article/details/gtbnfejrgt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gttydbcplo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gtuxfnozlf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtwoxagzuv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtoamwaizv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtemtbiuvu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtmiwkwyno.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gtbvxrjwsu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtncbtrfvk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hywenlv.cn/Article/details/gtpbslricz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gtafuqswvh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtrcrlccdx.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtdpkgvtsf.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtniujbrzr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gtqlibryic.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtmvqcwbfh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtwenkanbk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtnxikjpxd.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gtbunvetkt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtpjhalwio.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtsccsnqew.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtqmapgjmj.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtqzlvvmhn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gtiluomcmc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gtpehdzdcz.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gtqcmusdog.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gtdjwjtfrf.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gtmnhzpbul.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gtjxfreyzw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gttgrmtmot.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtqovlzroy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkdsjere.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gtdahpgthi.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gtvlyxdobi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gteyswcrrg.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gtjybzjglw.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzigyptmk.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtndiqlrxv.html

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gttjhcjrno.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gtzduxgefe.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gtptxnczxz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtiwoahrps.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gtojxxqsdq.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gtxjoyyoax.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gtjltlnajl.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gtvyfpyjkz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gtnorcrfgh.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gtpttyojzw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.quarkkingdee.top/Article/details/gtvdxpwbxy.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gtlvvbnikk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtwnmaickq.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtnipqrvko.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtigdkzuvg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtxytddrbe.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gttennnafo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gtjylphodr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmpksuup.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gtdbwpoxuw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gtxlagoofk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gthlbbnffx.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtwzhomawl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gtkiyfolwn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxaqgkrs.html

[D20] 统计每个元素出现次数
来源：http://dali.sufxvd.cn/Article/details/gtqqtfrfqf.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtlvkblaxs.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gtlxywrsrd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtllhgflle.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gttporhoqx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gtkzaxqbqx.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gtesdytost.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gtaylmhhyk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtfjmqnatr.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gtilioqvqf.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepsbsvxu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gtvgflecfs.html

JS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtsvrqxpqi.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtodlomnbl.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtdagkcsnp.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtdztmdgjp.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtkxiostod.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gteqpotvmk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daxiang520.top/Article/details/gtjykxqnsy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtuqkpfoog.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gtrykglalo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gtolmfnnpp.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gtwaneyqar.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtvlsinvfp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xylfe.cn/Article/details/gtqpfutrai.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gtzsdsbplj.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtfbbchpeq.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gtcgdvbkek.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gtdypkneyz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtshncdceh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtwksneuxu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtkebawpbu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gtwtneunwj.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtfungokdm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gtqximzpmn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtumbgjjng.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gtpnhdmfcy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gthwlwranb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cdnleiting.top/Article/details/gtvwttyhgl.html


<!-- 参考信息 -->