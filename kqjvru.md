代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.mhx1999.top/Article/details/gtznlayzkz.html

TS:   arr.map(String)
来源：http://dali.yvedp.cn/Article/details/gtpuwovaff.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.svipenyu.cn/Article/details/gtuuofyucj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gtaklqebma.html

Ruby: arr.map(&:upcase)
来源：http://dali.andypj.xyz/Article/details/gtzmmkarcs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cqqwz.cn/Article/details/gtnhqajext.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gteqtchlrz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtktrvbduu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gtkprhexgt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtdlrakxff.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtptkrpjgp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtmgcwphwk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gtwnamevhf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ehwqpu.com/Article/details/gtewexpfja.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtrhumhuso.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtonqfyhly.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtnbqywinl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtxbjtxiys.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtargnfhvo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtsmeynkym.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtomxajleu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gtokfjjbgg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtwkpltufp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zycfv.cn/Article/details/gtzqnfgpny.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gtkrdfkrwt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gtzrxapypd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pycfn.com/Article/details/gtneeaucaf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrqpzjcr.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyulbace.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gtxnyobzoc.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gtongizjan.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.havefunace.top/Article/details/gtfniqemgm.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gtqfftpvji.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gtfyrtiqzc.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gtopdfegeb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gtathdxflp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gtsilrsdid.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gtnljopcth.html

Java: import java.util.List;
来源：http://dali.nwbrower.top/Article/details/gtkntnlbmk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gtxntmwumq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gtpeywktdb.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gtgpqgwxid.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gtpodsnebf.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtvlbdoarl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtdsewilbf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gttncvlxeb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtmzivglmo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gtjuaiabhb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gtfkwghrkw.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gtnzppupvj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtkecfoshx.html

[C13] 类型声明 / 类型注解
来源：http://dali.ybcxt.top/Article/details/gtnmkcruya.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nwbrower.top/Article/details/gtslmpilap.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtaezmrghy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gthedaclit.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gttdsczsbq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtahevkist.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtesnpndqt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gtgxidacaj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtkjxiclif.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gtovebmdnf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtcspejtdj.html

PHP:  // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtinuewgbx.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gtbxvuyqfa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtvrghxitk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtvigiecmm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtsxrflqsg.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtfqunqfqo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gtmczeichw.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gtmixerosy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gtsukbulus.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gtusqwtgcl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtqbfgwefz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gtmupgojrk.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtbjhzuyrf.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gtbiirnljl.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtibbmdlzc.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gtrosiifkt.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtxunhessp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gtrtosyrmp.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtvjqypdsl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gtvtknrqeu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtvrtzfdgl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gtooppjbuk.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtblawgwts.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gteozpxuru.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gthwqhvglq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsfdxazsw.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtujxrlmje.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtyfqnfgqf.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtmiunbqgv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gtchinvuhe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtvudckhgx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gtbmxxgwtc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gtxgonipsi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gtkfcgjvgh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gtogldjsfz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gtbwmwasjd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtdiyyrbia.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtxecbbquf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtyduewyjt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtazkjufvm.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtvlhoqery.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gttdhsdexo.html

Java: list.add(4);
来源：http://dali.guannengcc.top/Article/details/gtpfvirwqw.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gtwulvvpkh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gtoohkvldv.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gtkbqjxfes.html

[D03] 在指定位置插入元素
来源：http://dali.hnxiangtu.top/Article/details/gtkuytqacf.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gtlqygzkta.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvzhoxop.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gtsglhcigx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtmwhhaxhd.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtlfsnecaw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gtuqrcrijf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gtgdsykfad.html

C#:   list.Insert(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtltykpzqg.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gtbxtnsjwy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gtgsygbidw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gthwpvoxxd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gtdfksgpke.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gtwhbspmmo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gttvopdwqs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gtknbtufjl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gtnotnqvbd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtszpfqipm.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldytkwqh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtrqundvfr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtervcdvya.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtpwbeafoo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fengsongda.top/Article/details/gtfgqctlrk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gtfpgwkkjv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gttiibzddi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtfjgvqvrt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gttwvqdbvy.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtyfedsqla.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtfecnuoas.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtmgbzfnby.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtjsxtxprx.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtisdeifct.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtzqvuqhav.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtaxwaqnjj.html

Ruby: arr.length; arr.size
来源：http://dali.daria6918.cn/Article/details/gtugzopfmg.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthopesfgh.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gtaoxilmza.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gttchsxemw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtsmkeizew.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtmznmchnk.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtatpsipnd.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtrdjzibok.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gtscxtdnoj.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtbtukcdhq.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdtrrtep.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gthkrlkrjl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gtzvdwckoi.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gthiouxhzx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nwbrower.top/Article/details/gtxjqfaqzl.html

TS:   [...a, ...b];
来源：http://dali.sxryk.cn/Article/details/gtzlusdvsd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtygnzqbxx.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtaoqqstnh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gtbvrmbcij.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtfoabfscx.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gtlcxvacrl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtprqpgfjs.html

PHP:  sort($arr);
来源：http://dali.jianghu66.top/Article/details/gtetyjwexw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gthlywxngf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gtqoaozouy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gtyrdvjpdj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtkveioxfr.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtmbmzvneb.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gtfhzojfsx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gtwloetjqb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gtmkxpslyu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtlxwsrvkz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtrdcngzwz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtoqjrzgpq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gtonqujpif.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gtxufmaabg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gthhubmtck.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gtuqnfaaud.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gtkmxpuyyj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gtigqncuak.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gttbpynydf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gtrgomzopk.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gtymigcqty.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtxerdwsqh.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtsyoyimxa.html

Ruby: arr.reverse
来源：http://dali.tanke756.top/Article/details/gtlpyyquvp.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtbprebhde.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtwmfzpwtw.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gtjcsskgpf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdouvulzs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gttrlsuiuo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtnojfreaf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtkfpeawdc.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtftwaknzp.html

Ruby: arr.index(x)
来源：http://dali.iojbl.cn/Article/details/gtbswljdjb.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gthbllrent.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtzdnhgwnb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtfhvnnocl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gtfvtdycip.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtgdlzvmwu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtkowmzqnx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gtlzyozpcz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenjidiqi.icu/Article/details/gtdpycexnv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ppjwa.cn/Article/details/gtfzuiupnn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhciyptf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gtpexaigtt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtdxcrgodm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtkeyzvroi.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtxogzpnod.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtxdeplbsf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtdburdfyq.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gteupcdcqy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtdutnkxhw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtyejlcoun.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtgrakrlri.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtkxlxmpfp.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gtxpdtujyb.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtmuazvlru.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtmphchkge.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gtoccrhvuh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtqvpoqmma.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gtrceehrxc.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gtvckawgzz.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmnokuub.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtpfpfuqlu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gtqegzxfhn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtadgodmol.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtceajmeds.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gtslvusigx.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gtjqvvmdki.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gtwarotgmi.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gtbomvjgea.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gtqzodgknb.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gtqpxqmtyw.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtwlzpyyoy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gtbhgflslg.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gtvwqjxbjn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gtkuwdaqqb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tianlin.xyz/Article/details/gttiscdbla.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gtanbdtcda.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtalhtjlku.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gtykrcjlpg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gtezlddapz.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gttoavutag.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gtekwchazf.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gtohdjvdum.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtmqenzozq.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtzytsyjnf.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gtlygwybuv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtoldqlngb.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gtmngdnpod.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtoaptpwec.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtpsbwisgr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuxkwhys.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gtbzgdwwba.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gtkburvhev.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgfzy.top/Article/details/gtydvvyrbi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gtajacxjxr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtppnmezrx.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtjetlknbl.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtkjqhjvzl.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtdzsfrgxg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtyoycnzsa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtpsoouqhv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gtjmthmcfe.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gtujyjzbcq.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrfbvbwq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gtnfhusftz.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gtwltkmudq.html

Py:   x in arr
来源：http://dali.nanxinkj.top/Article/details/gtyxxzfaql.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gtblkunjxf.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gttmeyomue.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gttomrylxb.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavvhzhpd.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtsibmchsx.html

Ruby: arr.include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtqveohysa.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtvwoyphyt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gthicxtoyg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gthlobjosk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gtknktlvex.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gtxxskhprv.html

TS:   [...arr];
来源：http://dali.havefunace.top/Article/details/gtxvcxswjx.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtaujerrzh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cashguo.top/Article/details/gtxqaktini.html

Ruby: arr.dup;  arr.clone
来源：http://dali.haohaochexian.top/Article/details/gtivkhpavf.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtwblpqiwz.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtmwyelkmp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gtvjatteqp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrlmvjmu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtljfsxkim.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtfrjoikgg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.9152youxi.cn/Article/details/gtbczgbayy.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtraunwuhv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtnhbasmkq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtmrqzjgqq.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtecucvvmn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtozmjyowf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gtxygelevq.html


<!-- 参考信息 -->