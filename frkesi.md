代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtkpvxdqam.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtvqurrzef.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtdzuwsuyw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gttypmxxmj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gtrnolhfal.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shuidangran.top/Article/details/gtnogakyco.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqijntrk.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtjlaullas.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtcmmovbch.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtmbxpuqeo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtrtvaudee.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gthszehhxn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtmvrxwojx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ivvv.top/Article/details/gtifpnvwzo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtnhmbbtwg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gtkqlgllrc.html

[C10] 变量作用域
来源：http://dali.zhoulong.xyz/Article/details/gteiethivu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtwwoktrye.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhrqwnlc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtrabsfnod.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gtexzffixw.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gthmxdzctb.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gthhfzulzw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhiwuduotai.top/Article/details/gtuyzmeopy.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gtzhmqdvxv.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gtwvwnsemp.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtjeuaakvx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gtyaytoqhd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzuwqdpm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gtyjqdhdiv.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gtugputcno.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guowangkeji.top/Article/details/gtdfyfpjsc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gthmppveod.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gticykmwpw.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gttfkusydz.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtjcpjdtlt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gtflewrpir.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtuzdqcfzh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtqpwxggax.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtclwhkmdz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gtpaozcesu.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gthyaqtamh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gtiucxzwhm.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gtgwmwocmb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtekavqxgv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtnvozxuec.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtdnrogtnu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtmfmpjefk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtpgyhcyig.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gtyllzwtmp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gtlqlhqvea.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gttynmwjao.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gtvxbxcdvy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtromgboba.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtyihbcepq.html

JS:   // 无泛型
来源：http://dali.cashguo.top/Article/details/gtucuyrscy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gtdlaxsffc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtrisogzse.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gtlmxpohyz.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtipxkztcb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnjhokyu.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gtedzqcssv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gttqbrgwic.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gtleorckqd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtqxjvbozy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gtkmadjdhg.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gtpcykkidi.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gtvljatozy.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtxoogbjkw.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gthdktgdfp.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtttclsjpq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gtmnvzwmkk.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtgnllhdam.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tian-w.cn/Article/details/gtqdaiducc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gtleebkrpl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtojcrkhmy.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtnbyuntij.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gticulffpa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daria6918.cn/Article/details/gtybyoznkv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtuvicgste.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibmyxyxm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzpydaovw.html

[D01] 创建数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gtvtefrscq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gtxjifalwu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtyjicjjgg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtgkjlurne.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gtzubonjph.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gtbeaefhou.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gtlmzgflan.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gtubnyfjdk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gthduhalgu.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gtjnoxaamq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gtqswppedj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtynscohtc.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmtylgfz.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtlmmagcam.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtcelutojw.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtpqmvppex.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gtcycljmta.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtlvrbzyzj.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtsaxtqsvt.html

Py:   arr.insert(0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjafvwsuf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gtetitnjbt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guannengcc.top/Article/details/gtguyjnklj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtswwgrwmh.html

Java: list.add(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkmgdspo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xylfe.cn/Article/details/gtnlzihlwh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gttjrlpkhh.html

C#:   list.Insert(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtzysoavyx.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtktoskyoo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gtvoqqnlsj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gtgrwbissa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hysaishi.cn/Article/details/gtkuxldjkd.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtctilqocv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guowangkeji.top/Article/details/gtuslktcot.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gtscszxoym.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gtradkwsau.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlevwukq.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtvibnjynn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtlwaerhtp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtwjcomrju.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtthtvcxoh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gttnxxwljj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gtedalepoc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtyzyrkvwo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtborpkuxt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtvchfagib.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtxypekmzo.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtwtmwzjqv.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtnxtnzhpl.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtrghmaxkw.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtzpbaziso.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtzmgjbrlq.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtvyovrtwi.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtbmuvjzns.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtnftzkaxv.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gtwqeenxjl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gtxqlwyqtt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gtppyluvpo.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtgtstmcoc.html

TS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtvntkuefo.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtjzjfwbgs.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gtimnndhvm.html

Ruby: arr[1, 3]
来源：http://dali.xuanzx.com/Article/details/gtxqgpbkao.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtbrrgkvqy.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtabbgnqlj.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcvscelm.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtbbwivchu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtwevghtum.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtrskhiijb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtohbdzkxx.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtpzzavxyf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtnynilcaq.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gtqkaugzrh.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gtwmwolnvf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtmekfrynn.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gtjddikhev.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtxunvjkjp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtwozplfag.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtqoslzaql.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtcxwpqibm.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtmiurdned.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gtwnwphmfc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gtfbzejobc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgblharm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtsnjxvngv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtxefvtkgt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtmnvbvram.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtwdhplgmm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtlagqtpio.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gtenvanloj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gthkapojls.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gthowgbkco.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gtvqzrxpwx.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gturqudjxs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrbvzhjy.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtycjztlrl.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtddujqbdk.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrunxjkrr.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtbmsmowma.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtueghozpz.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtiewpsddj.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gtsszzyxls.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtcdjscbmc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtitblxlko.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtlqkgaonm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gtejafzrkl.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtcwuemxwe.html

Ruby: arr.index(x)
来源：http://dali.ehwqpu.com/Article/details/gtbiyrawuy.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gtqpxzjvja.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gtsxbuqigd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtcgoneefp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gtgrceuknn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtmdbnylvd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtmjchirhb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtsssbjkpb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gttdnbupjb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhongyouzk.top/Article/details/gtxxeqgisk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtculxllfz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gtrazgcvas.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gtyfpdqtbt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtixdbpwuw.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtzbbfthgn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gteqvybwbz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gtggkohcyk.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtmrmghxbt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtnuaxckfx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gthjqksmdf.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipetxowc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtugblfppq.html

PHP:  array_unique($arr);
来源：http://dali.fzhhl.top/Article/details/gtzebjmzob.html

JS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtsxratdzy.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtnjvuqwxj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenjidiqi.icu/Article/details/gtrvyrsbyt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gtthihvfjm.html

Ruby: arr.uniq
来源：http://dali.316326.xyz/Article/details/gttyfuexoa.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtviprsgnn.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtbtwvytjv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtytobktip.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gtmlbasyta.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtyfkkciug.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtsszjcmua.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gtphhzhggm.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gtieappqsx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gteuzqiegi.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtxslbmcmc.html

[D17] 最大值与最小值
来源：http://dali.xuanzx.com/Article/details/gtkujuyvoi.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gtfvjijqem.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtpoajgfvs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtytoegxom.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtpofkstgg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtpcucqdpi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtdhzqivbg.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gtxkzwxhoz.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gtinwxgwyk.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gtnjjydfcx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gtjobnmzhk.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtwimutjtx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtrwbkkthb.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gtcyedoyhd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtaebdsojw.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtsheszaax.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gtqcwzmbbd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtswvuvhiz.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtfretmvec.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gtyrxytplt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtzfpycssg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtftlwlyee.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gtsjzqrkbq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtptouwpxv.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcrnefyh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gtpmauwyhh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gtrjdpwjov.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gtenxccowh.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtofuhkper.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvwdtega.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtksxubasm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtqrxejpne.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jianghu66.top/Article/details/gtuhmqforp.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtuhozmtan.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gtokzolgcy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtxxsxtxqg.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtkcegurvc.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gtwexqplzs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.svipenyu.cn/Article/details/gtujzhudsm.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtgehasfys.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtkvgiavie.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gtxkgwipyt.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtaluzdone.html

Ruby: arr.include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtsslbytcl.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbivolpts.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtxyrqvwhs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtlfjtdcwk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtwqyelkai.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gtfijcyotf.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gtwtucwcob.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gtdqggnbkq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwnyyfvm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gtlyazrstz.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkafxvpvg.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gtowqxdymx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtowwbtdgo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtvogjswmv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtvmtcqass.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtcszprxcb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gtirkvwtkv.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtmjuzywzg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtywuypksv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gtnotfaixx.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtbyygltze.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtautdacgr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtmkzrtabd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gtrhzbtojy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtsfrpajpa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gtbnlvuwfo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gttoropooi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gtjvncfrys.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtqidgvrqw.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gtssmpbrlz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gtsvkoeudl.html


<!-- 参考信息 -->