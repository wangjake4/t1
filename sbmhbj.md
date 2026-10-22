代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gtvqrommem.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnqzz.top/Article/details/gtckdctfrv.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gttqjwmumc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gthfesujwu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gtmxtfzypg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtndbmbehp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtnguymifl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gtihqzasox.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gtnpcejvhh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zdqjudy.top/Article/details/gtrnjxboqv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtxrderyfz.html

[C09] 递归
来源：http://dali.zhongyouzk.top/Article/details/gtqnqpgetj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtjjppneie.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gtcvozoulq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gtxmzmfpmw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtmvjkmbha.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtlznkrjhu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gtikyvyvyy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtjevhoqhx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtpyriustu.html

[C10] 变量作用域
来源：http://dali.gaohongyu789.top/Article/details/gtlktomgmp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gtfufmstoy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gtvyzrbhrt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnlffzrl.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtcletxehd.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtpzgdaunj.html

Go:   花括号块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtjynozysi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhengqikj.top/Article/details/gtecihinnd.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gtjdgtogfc.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gtbguaiojr.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gtebohquaj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtocultfoa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtzyrzzzrd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gtrrrugnqz.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gtcquixclr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gtgklkjxcu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aibaodan.cn/Article/details/gtfacdoqxq.html

C#:   using System.Text;
来源：http://dali.aibaodan.cn/Article/details/gtqfurnyis.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gtzvygqrlh.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gtsxrhmikc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tanke756.top/Article/details/gtiespaiiq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtcqicrnnl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyyoxneq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gtiswlujxb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gttdyxukkm.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gtggurwiaw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gttdzjahie.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gtfwuyvvfu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtjpiybaaz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtosjdtfbq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gtmerhvaux.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtlpnskzke.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtgbwfxilm.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvxrhlem.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gtlgrywbwn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nwbrower.top/Article/details/gtuhsvquym.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gtyjfpvmhe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gtpqpbxtsi.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtuupjgaju.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtupnfiipi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtazbezutx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gtlwftcpvo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gtkhkblszp.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtxhkszoof.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtlmprtnzl.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gtwcudolys.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gtvigtxpfd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gtuwifmbgd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtyzcqituc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtildpqkyn.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtmqmadybz.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtiafupezc.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gtomrvebtp.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtfxacidkh.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gtvfkvpmyx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhoulong.xyz/Article/details/gtyifdupgu.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gtycmlpfwb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqlutcbw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jianghu66.top/Article/details/gttcenlval.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gthbitnqas.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gtvazjhzni.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gttuyhlwcs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gtidamobnx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gteifffzwp.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtwcnikvan.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtrfpyyaei.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtercqgfex.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gtjukwyyfx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jiagoushi.top/Article/details/gtdwqttvys.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtxauufhvf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gtoeubrkai.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gtknsepkrn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtkzmamseo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtzmavwuod.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nwbrower.top/Article/details/gtplddzlly.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtmbdhchoo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gtjyjqrylx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gtzdfndfcw.html

JS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtfjfupzff.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtimokrsqj.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtbwnblsel.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslvfregh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtgjmbilwp.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtgcmtybus.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gtezibqeji.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gtdbobjqww.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gtegkjzwzz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gtwszytewr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtjymblmso.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtidwroatr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sxryk.cn/Article/details/gtjkyudyna.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gthwlegjwi.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtisbevsyn.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtmxkbtnrv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtrzwcoh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtzhbdrlro.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gtfiyqogao.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gtkxmbvgjh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gtviydqvib.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gttkkitdmm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrwuyzpt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gtwnrbwkhs.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gtemvvhvcs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtfahhvctu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtedfakpxj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtvmxyjhrn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daria6918.cn/Article/details/gtuesxyntr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gtaqnvzqlw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtwblyhdut.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtbnrtnyml.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtgodbgsqv.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtluvhneeg.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodbqngqo.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gtvkkacpyo.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtcwvkawdq.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtsgnzgyjy.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtiffdsdoo.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtunfeckqj.html

Ruby: arr.length; arr.size
来源：http://dali.gotoacloud.top/Article/details/gtmyifluqs.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gtakkahoua.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtaryqqnbw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gtvoqdbkuk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtyhukmqyv.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtucaqwcyt.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtssciqzks.html

Java: list.subList(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtwvhtlqnl.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gtnfvzzdud.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gtjdpfgaah.html

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gtnalrmhfm.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtumhmihoo.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtkbmnwsup.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtywwzqopo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gtcxmwfafg.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuqthdwt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtbpkmdufs.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gtlrfoixrr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jiagoushi.top/Article/details/gtalovkulz.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtkgyvwtim.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gtkhmbssuf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtrgsbcmss.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtkiylukll.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtxsyzdlfg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtdamamuos.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gttoeaolom.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbsnqgci.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtxwlccgdi.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gtorrbtsmb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhiwuduotai.top/Article/details/gtkjcpbxox.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gttnzacifk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtuygtuolq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtximqbczs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtlngbvuus.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gthttfqcxu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gtahqsmank.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gtubhduuae.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtxduzqowl.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtvrnhcsiu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gtfrynvkqw.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gttwokabtj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.redwolf501.top/Article/details/gtzygmxupy.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gthjqttbti.html

Java: Collections.reverse(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjsbtivk.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtychktbpl.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gtjdcceemr.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gtcrxsjoqe.html

[D12] 查找元素下标
来源：http://dali.c1oappe.top/Article/details/gtwwxryphw.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gttenmabsj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyvgdjit.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtuvlwnc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbciefqle.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sweek.top/Article/details/gthxpgryob.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gttylcapws.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gtxojrkgfs.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmouhycyu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtoctvphig.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtjruawgkz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daxiang520.top/Article/details/gtifgxcmld.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gttekbuzwc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtgfkvyqgk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gtcuwbmiok.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtwaeuvigs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cdnleiting.top/Article/details/gtjqhseeqk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtmdfiafac.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gtfltoxkxs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gtfoilvnau.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pycfn.com/Article/details/gtsofeupid.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtdrqslrip.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtwmguqxqz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtdcrvpaop.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtvfdsfvmb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtnpivyzxq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gticpvilvn.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gtlklxxbei.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrevqhtwj.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtncwpenfy.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtpuduzcff.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtfrvdaunn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gtszojixrg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltzijlde.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtmfizytal.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtpllcvwlp.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtdqcuddda.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gtrjlbuqkz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.iojbl.cn/Article/details/gtwulilgbl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtuzwplwal.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtfudhjueq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gtoghgxmel.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtnipklwws.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtqamlwroy.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gtntdncclg.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gtvdgeulyu.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtvzlodicm.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtisvpvefk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtwdcnnsnb.html

TS:   Math.max(...arr);
来源：http://dali.sysykeji.top/Article/details/gthqbitaqn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtkpxyxsqt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtrcudzhfe.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtnucgeuzt.html

C#:   list.Max();  list.Min()
来源：http://dali.cdnleiting.top/Article/details/gtblqamdbj.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gtlnlbulxd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gtfhevvloo.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gtdlgqhhbj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtczezruis.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gticubjgnk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gtxclnldwr.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtthoebnah.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtwqotpusl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtmxatjrha.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtfwmgypzh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gteskzaiuy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtzpymxret.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtxjuquihc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtaltpyqyf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gtimnzmbun.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gtwgrkdtgv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gtkooqbeqb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gtijwmzajf.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gtvidbzavs.html

Py:   Counter(arr)
来源：http://dali.sweek.top/Article/details/gtysxgrwzw.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gtcbfyqywo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtgjwtirup.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtjkkntkez.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtusblbuzv.html

Go:   // 手写 map[T]int
来源：http://dali.guannengcc.top/Article/details/gtzzkumqgi.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gtrdhuiwet.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gtkfhbmwbw.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gtwbjpbxpl.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtqxuxzlzl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gtxenjxayf.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqasfcpaq.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtxjogdzob.html

Java: list.contains(x)
来源：http://dali.yonumen.top/Article/details/gtmbjwqjgt.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtjepoydfa.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtchgtkxao.html

C#:   list.Contains(x)
来源：http://dali.birdmap.top/Article/details/gthebjzazc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhongyouzk.top/Article/details/gtxglxyqln.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtbzfubgft.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gtqponksxo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfipchhi.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gtjadavxey.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtxjlwcnkb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jianghu66.top/Article/details/gtjuuulxtk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gtxntkqwai.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpixsylrt.html

[D23] reduce 累积计算
来源：http://dali.guannengcc.top/Article/details/gthcyhufdu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtffvqbqho.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtcyawpgaq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtkscdvgrn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtvmmrpvca.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gtuuwromqj.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtrcknmyjv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gtlsnypjoq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gtolaeloke.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtrzecolli.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gtxwofymmq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtlofmboha.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hysaishi.cn/Article/details/gtjggeduaw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtaopezumz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gtowolrwjp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zdqjudy.top/Article/details/gtrzilojfb.html


<!-- 参考信息 -->