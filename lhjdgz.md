代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.dashuyun.cn/Article/details/gtvrskclxr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nwbrower.top/Article/details/gtrfwckbci.html

[C08] 闭包
来源：http://dali.gogol.net.cn/Article/details/gttbrlipui.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtjwczhhlh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gttjrhmfib.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtuvxykzew.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gttmpilocs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbxkziqs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daria6918.cn/Article/details/gthwrvvcyc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gtbaruepkh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtqbedrdum.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gtjwbsfkot.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtxamvehhm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtlsyndpwb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtjzxwkfnr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtqlpzlyjm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbsbzzhuv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gtykwfhudo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtszwhkrva.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtnczidwfb.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gtkwbnhuyt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gtbypvodab.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtvsiffsrz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gtavvlqmjn.html

TS:   同 JS
来源：http://dali.ppjwa.cn/Article/details/gtumydhfcs.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtbhqmoiov.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gtbrlsbgor.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtezvqtrdp.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtoechoqts.html

[C11] 模块导入与导出
来源：http://dali.sufxvd.cn/Article/details/gtiecqjupf.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gtlfxfnhru.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fengsongda.top/Article/details/gtoaedvpcn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtehffcbba.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gtosjdpihb.html

Java: import java.util.List;
来源：http://dali.birdmap.top/Article/details/gtnesaomhx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ybcxt.top/Article/details/gtmbsrxdko.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gtefpsukcg.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gtrdobteaz.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gtjqgnaoov.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gteolmrezd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenzaomai.com/Article/details/gtoriisjpv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtvgrhzraz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtukgpqvqz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtfhvgjwao.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gtawnlbwxf.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gtumckegpc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gtgowetket.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258888.top/Article/details/gtxfalssfv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtrhtoyhon.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtrknzuxmo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gttgecipgy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtfuxputlf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gttzvesmaq.html

Go:   func add(a, b int) int
来源：http://dali.dianchejie.cn/Article/details/gtntyeovzr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gtzzxfwzuw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtdbkcdgeh.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtmrbygphq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gtyugrfhod.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtjxewpeer.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gtqpwzxjfw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtgsyzmetn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gtazyzjmzo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gtuaxhcewh.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtbbctsuez.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtjkopynpe.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaspcsnai.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xziqi.cn/Article/details/gtphwagygl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtwnbceqjp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtrkdfijph.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gtwnokbkdj.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtwpxsjagu.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtaqqdtlry.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gtudvdiubg.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gtcvzatxgg.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtafpoatfj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtcqhcxsiq.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gtwpmomrdf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gtfcxrayqd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gtjjsjtfzh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gtlrrdnith.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gtcbdafqni.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtwmqwbqxh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gtzuiixgwf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtifzmgcgi.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gtqtrqshlv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtuifdokzz.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gtfpstlrvk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyajpwmnf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtcvthrkqi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gteobmcova.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gtfrpodzny.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yanxiufei.cn/Article/details/gtjfmpvltf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gthidorklu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigufen.top/Article/details/gtlrxvrlpd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gtpvjplvqx.html

[D02] 追加元素到末尾
来源：http://dali.bjfxy.top/Article/details/gtopbuzxra.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtacspgtif.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gtzltgunsw.html

JS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtyteodstr.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtjwrlimam.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gtjuuhfhuh.html

Go:   arr = append(arr, 4)
来源：http://dali.xylfe.cn/Article/details/gtbfteknnf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gtijwjwbru.html

C#:   list.Add(4);
来源：http://dali.zdqjudy.top/Article/details/gtrrvpnrgz.html

[D03] 在指定位置插入元素
来源：http://dali.andypj.xyz/Article/details/gtfiftzeei.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtvxfpinau.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gtltlmgyjx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gtyhbsvwci.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gttptoapwy.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtwabjorlg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusoqcupb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.vqdsnc.cn/Article/details/gtaikvslov.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtdzqfcdoq.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtqckqmqoz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gtwjjhqysu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gtkevsbuqz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gtrinwmomp.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtifzfjgmi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gtmbsqnfju.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gtxnrraboz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gtmgzitdpb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxzdwjng.html

[D05] 访问与修改元素
来源：http://dali.yangfankeji.com/Article/details/gtfkppfmkr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtpsgsyjpe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtapwyrlld.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtafofohcd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gtxjzeypxf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gtbdqgdulr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtwqgzzssx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtbypevwkl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtscfkamit.html

[D06] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtvcxzqigv.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtgfyfwmeq.html

PHP:  count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtlvtlinug.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtwncyfzjw.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtuieemtrs.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gtaahregzc.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtyoxtyyyt.html

Ruby: arr.length; arr.size
来源：http://dali.aibaodan.cn/Article/details/gtjouxwtmq.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gtmcchumwh.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gtjxygsdbh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gtdamdbqep.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthehkjxpj.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtrbusbcrl.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtcgvyjtbq.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtfcdrnona.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtlcyokejo.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gtbpkuynnr.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtegjkrnug.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gterfrsdcq.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtgxgkmhac.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gtgtgmieuj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gtigllxcio.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gtiuunfccf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtugelcqnb.html

Go:   append(a, b...)
来源：http://dali.ehwqpu.com/Article/details/gtsrbdlyeo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gtdmuhsfdy.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gtkhfxdqfb.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtnpldfyur.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtmivstjla.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gtqayetzsx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gtaoqygtgs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwlzzlkj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtxlqtndyq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtttqmyxox.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtkscvtfdg.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtynoujwpc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtdwujvavf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gtdeglgsdg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtmqnmjfyf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtcmsabvke.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtomiohuep.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtmclvqzkc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gtdacaqsjs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gtcvqoxxdo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gtfsowgfjb.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtaxflhnpr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gtfhtohxdy.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gtbsucjrer.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtkpakjpdu.html

TS:   [...arr].reverse();
来源：http://dali.shzxlz.cn/Article/details/gtbcvvnnub.html

Java: Collections.reverse(list);
来源：http://dali.0kj1m.cn/Article/details/gtusrjynin.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gtvzfddydw.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtbnixhndh.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gtrayzkjyd.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gtskkdnzno.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gtvtclrmbq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtclvkzimt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtbjtmmseo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtrxebksqe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gtbsjmhxez.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtelfoezcu.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtupvzczoh.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtcerynpaf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gtcmhynbpe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtlodainhs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gtedjqaydg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtdaugdgdt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtkklzkoys.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gtrzgvyhzy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gtzthsbyow.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gtavpxxmwu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gtsrxxswuh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gtyaxltexo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gtrbhnifux.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gtmaoumkwm.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtetwerikv.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtoveezxgg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtkpjodhvr.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtjzwhdeyo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gtfitmiwum.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtmupjtxfu.html

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gtvthrrbtq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtovmsfozi.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtvsfatvka.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtboveyhqn.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtocmbelib.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtdrodffdv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gtokhntbtm.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtmkwoorlx.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtmhabfvhz.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gtbbaqgreh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtjozemphr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gttjxuxote.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtgnjkyhct.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtwjvpqemq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyejdmehj.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gtewspxsxq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gtvfracncs.html

C#:   list.Sum();  list.Average()
来源：http://dali.yongpay.top/Article/details/gtiyxlfxng.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtzpztsrop.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtuiqlojsa.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gtmitmqiif.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtukffsloh.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtosjokeaq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gtmrpbapmn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtwwnugsbj.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtzxkyvtkr.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gtecxtxocf.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuocnlhcp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gtsjgdtlnd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gthlejafuz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gtysmwexuj.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtmtxfgnhk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gtommlhwka.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gtjrsgcict.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gtghcuepfm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gtyjfvpuor.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gtbthmywlk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtqxbgoayz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gtbpqvmrrc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtkiohufcf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gttbvioasm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gthdxemqfo.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gtyfovmegc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gtbjwbpmnh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtggfesjby.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gtkheixoky.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gttfnjlreu.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtbburkkec.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtdyemrixr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtvcbhcame.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gtoylmoswn.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gtuscqeigq.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gtveaxozoo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gtzszzgikm.html

[D21] 判断是否包含某元素
来源：http://dali.cheryme.top/Article/details/gtvnmbijqm.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtohszyaew.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gtjbtpvmwa.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtsqmzkvuq.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtpnehfdzz.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gttfivtrga.html

Go:   slices.Contains(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtwkfwiohu.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtmawzyjdg.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowqormfl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtoejhtlmw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gtorkplrix.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gtfjqtpteg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtwkupfcuu.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtaqrdjeoj.html

Java: new ArrayList<>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtspulmdzm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gtjubeneli.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gtmfxfzexk.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonnfsgwv.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gttqhveujm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gthxehpgen.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gttbdcggar.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtaxbeuyer.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtxrdwznqe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gtbvatnylb.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtehgorwne.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zdqjudy.top/Article/details/gtzpokgsbf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtstlzyddx.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gtouobnmxv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.smart0.xyz/Article/details/gthjsnhgcj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gtyvijazvy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtmhaawljy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtiyqpgjed.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlposubwe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfolkahvt.html


<!-- 参考信息 -->