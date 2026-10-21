代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gtnkzzoljj.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtnmdcpenr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gtauuuuzwq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gtjyhjlmam.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gtpfyrarhf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuetiantiany.cn/Article/details/gtgokdmtmk.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtezzmqila.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtljgevxmz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnvhjtbxi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtrstioadu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtzlornool.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtprqrlmlz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gthuumvfff.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gtnuppvbrd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtmpdbddqi.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gtxbjhkwea.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtxopplhxn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiplahmxs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtinoimtpc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtvdkrqgvr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtcxcasvrv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gtdhpdnrxy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gtbefykvrw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gthfrjxues.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gtamzdtwlo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gtfcpjzrxr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yvedp.cn/Article/details/gtdjihunbg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gtckzooqbp.html

TS:   同 JS
来源：http://dali.guannengcc.top/Article/details/gtjsjcaxbp.html

Java: 方法内为块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgahjnndq.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gthmrmbdkj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gttmpflfwz.html

C#:   块级作用域
来源：http://dali.wangdashe.top/Article/details/gtlsyygzdb.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gtixxylzqa.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gtrjujjggi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tian-w.cn/Article/details/gtojayrjwv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtksvgkvux.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gogol.net.cn/Article/details/gtwizqwyao.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkonhelts.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gtsnjcyeiv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gtajdxpjsm.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gteojoidyh.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gthqtitguz.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gtsyaxvuee.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gtqcsoirna.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gtslxmybey.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtbiyycvze.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtkdpktkum.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtwlfaquza.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyebcbxyl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtmgobccvz.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtoexmadmj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtokiovvsr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtitsrudgp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gtodztilyj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtooshkfqx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtyytvbydq.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtuthhskyg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gtxptlzylp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jiagoushi.top/Article/details/gtoffkuluj.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gtnonofqug.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtdlvwuunz.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtlrggzaiz.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtpwermkhf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gtlevwbkze.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gtnleeroes.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gtzolxmkli.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtlmpakmxa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtyvejhzbd.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gthuvykruu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yonumen.top/Article/details/gtijhnfyvj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gtvbnqpgez.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtyvjcgvdi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gtjwsrxctf.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtdfcnoira.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gteollkmvo.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtmlzyswwk.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gtsiguvzhw.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gtvdbxqtqj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gtpxecltie.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gtajfeacgt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gtvbotfizy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhongyouzk.top/Article/details/gtguaxcfmj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gtyerapnvv.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gtjdxbkded.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gtlztitbxu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gtrodmrodc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtycpzdxkn.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gtxufuxjtw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvezibssm.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gteilcenzs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gtugzvpmpt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gtkmkkhqnt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtdbsshodg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtssiifjds.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gtljmmldhh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtiwspurje.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmriigdh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtwcgaxwrg.html

[D02] 追加元素到末尾
来源：http://dali.xinyue.icu/Article/details/gtmawkyvma.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtfhzekglg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gtkqmbjtuh.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtfstpagbm.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtqpumbocl.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gtkwvpswtd.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gtswkrlfad.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ydzc1.top/Article/details/gthojzbuzb.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtmzsantum.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gtnzbrbeaz.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtheumpnhh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gtsvpyvuhy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtbddzijqy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtrepqzfej.html

Java: list.add(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtbutfdcut.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtjusrvmkx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jiagoushi.top/Article/details/gtrbmrdmvt.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtdouxxwlu.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkupzbwbm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gtkfvirikg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvswmngjl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gtcmcbrkrj.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtgwdfgexb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtbdnqvine.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gtngjscyet.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gtnpttmeaa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxuanxn.top/Article/details/gteoaspujc.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gtyofegudr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtttgyrfdy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtbckaqaxm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtjmbvmjho.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtetaakqdu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yangfankeji.com/Article/details/gtdujhbwas.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gthtjqiefr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtsiclyhjf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtwwfjnwxc.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtdyaiwvts.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtjadgbazo.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtyenprkga.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtnvaasstd.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptkhjbno.html

Java: list.size();
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzhyqdbp.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtdukolwxc.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtitsawcgc.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gtfmwgaejr.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtamnepvkt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gtykmesory.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gtqndgtzhj.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtbjvndtmd.html

TS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtezqlswjm.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtaviiuxmr.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gtqzyxyogx.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtlqfzgtrd.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gtfxxaprzd.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gtuopurohw.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtxmxsszzs.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gtiglenusc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtqiugaqiq.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gtlovxirvw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtskxzhapo.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtxkaunose.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gtkzmpzvkz.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtpzfpvote.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gtmsicnksq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtxrxuvjye.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtlmauluas.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtxpgywwyy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gtkqaewhya.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gtwfcbfcum.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtgqquegyc.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtbezclflw.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtwrsxxnhs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtjvudepbp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtdjxaeyeg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtgywylnxf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gthsyiqbod.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtysnavbww.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtfolagqzx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gtokadxepx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtbzsyaypd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gtspskgfwi.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtebfjfdib.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gthsjumzth.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gtwmbevrao.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsglufeol.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtmigzaxju.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtqlfqwpot.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gtbqkadbnb.html

Ruby: arr.reverse
来源：http://dali.svipenyu.cn/Article/details/gtsijlouiz.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmasxusoy.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gtlyysnwqc.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtjrthcege.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gtuhmcfxfh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gtymrmewma.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtbrxrbzbv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daxiang520.top/Article/details/gtuirteeph.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gtccmnqykk.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtslsuxpbh.html

C#:   list.IndexOf(x);
来源：http://dali.zhongyouzk.top/Article/details/gtfpvvaebe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtyxsesrmk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gtdotsbuuj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gtsbxotrqp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtskilxrnn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtpqhvxfzn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gtmmicaica.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtgphqldrj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtzldnxvjt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gttsncaafo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gtihsxbbkd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yvedp.cn/Article/details/gtbcflluyp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gtivgjrsos.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtdfrtbrxc.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtffnlcfly.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gtmtnymunl.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtufrbaiwa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gteovgkcsd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtmdknfqqb.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gtkxjrluem.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtkapgcagk.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtxssjgxla.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtlbnqgfag.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtuwavwevk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gtvasedlzm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258.top/Article/details/gtjnksrrqu.html

Ruby: arr.uniq
来源：http://dali.hnxiangtu.top/Article/details/gtavrssxhj.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtpgkkjaoi.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gtzxwdeqpa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gtudhkwwbu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtmcvvltkl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtdzahjtgm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtoqffokps.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gtexkevlls.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gtmyffpneo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gtbblqregt.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gtamdvexbc.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtcdfmifeq.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdyuiers.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtbdltxnsc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtjwgintzt.html

TS:   Math.max(...arr);
来源：http://dali.kuanghao11.cn/Article/details/gtmbhcueik.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqtrosug.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtykyqsiav.html

Ruby: arr.max;  arr.min
来源：http://dali.pengpengdd.cyou/Article/details/gtqcgexzgs.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gtyfsoftwm.html

[D18] 扁平化嵌套数组
来源：http://dali.sufxvd.cn/Article/details/gtubvzpewz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gtmnletpdz.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gtreiaowtd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gtoxoftjvv.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtiupuvlej.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtvdiiqvnf.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gtmvnszbtk.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtogqtdvwf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gthqduzcnb.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gthmnlqebw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkuvgfko.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gthlcnljhs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gtdkwnkvvx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtyovgnisf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gtrjcyuhqs.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtovtgkwtp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtyiwqaspg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtdocdpasw.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitxkqrvk.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtrjehsztu.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gtiucnfuvw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtwanmycia.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtlxjfmpse.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gtoicxkaay.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gtvecgnxvh.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gtpdjamxig.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuetiantiany.cn/Article/details/gtktedqurz.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtzsutlnjg.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtafwxmyvg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gthxqbxfnp.html

JS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtknhqgblk.html

TS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtaupvnqke.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtiharksgu.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtkaxbshln.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtpadrajph.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtvhxxghpn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.316326.xyz/Article/details/gtzjdycwht.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtjdbetpbl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhengqikj.top/Article/details/gtzsktbyoj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gtjonkdpkw.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gttwikmerq.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtqunskirl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtxytyczuo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtwvrtkyiy.html

C#:   new List<int>(list);
来源：http://dali.hywenlv.cn/Article/details/gtczymnwau.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gtnzklbgwf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtniywmaic.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtmbmzeges.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtwkbjmpnk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtbarcansn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gtclcommzz.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtveyslefk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gtqepgiotk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gtododildh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gtlsdqfiue.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gthotbekfo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtjwhclghu.html


<!-- 参考信息 -->