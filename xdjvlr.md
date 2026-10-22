代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtpvdktyei.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gtnxbbebsx.html

[C08] 闭包
来源：http://dali.shzxlz.cn/Article/details/gtoanwamtl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gtrskuknyp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywjvszrj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtkejyzcxv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtqdruwsnx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ppjwa.cn/Article/details/gtnwufalfx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gtotopirys.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gtezmarjdi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gthtknvkyu.html

[C09] 递归
来源：http://dali.ydzc1.top/Article/details/gtuhrzpfmp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtvfnhotmg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtsivgewnd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtgsoyxqns.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gtnebuxbug.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtxeuklkav.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtqoicdlzv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvdfrxdpz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gtuzbvidnu.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtpzmnoqcr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ehwqpu.com/Article/details/gtkmhubyoh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gtazadqwum.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtthlwfkcs.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtcchgfaag.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gtljoqaywj.html

Go:   花括号块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gttcpjezfl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nwbrower.top/Article/details/gtpcbzcyxb.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gtutaewdqv.html

[C11] 模块导入与导出
来源：http://dali.zhoulong.xyz/Article/details/gtxyeqgyam.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gtpikeujhj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtgdnsvzzf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gtoskuxxim.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gtggfhfdpm.html

Java: import java.util.List;
来源：http://dali.xinyue.icu/Article/details/gtbhawtzpw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnxvxdtr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gtwvczzwfh.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gtojddphtp.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtpgxcdsij.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gtugosdnmw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gtnytniatj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gtkeennkgj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtsxgkawme.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aizwys.cn/Article/details/gtbwlkmleb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gtgqcybfgh.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqdmjwua.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tanke756.top/Article/details/gtciqoikgy.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gtonucbyvx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gtkcwrlouu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtqejmxtdl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gtbpjhqgce.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtlqggumdk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtgtqbzowb.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppwbzajp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqfivskw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhoulong.xyz/Article/details/gtenkrhkjk.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gtjrbqtqdr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gtqdfiiamc.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtmtivzikg.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtnwmdcbqz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtcxzhpptf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gtlotazrgv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gthpztaume.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtwzmqaxot.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksmivucb.html

[C15] 解构 / 展开参数
来源：http://dali.ehwqpu.com/Article/details/gtmicoiqqj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtsxneosiq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gtfqyqdgze.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gtnumodori.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtccisecpa.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtuwornidk.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtvrpecyms.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gttpurkorm.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtrgwuaxsx.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtuchfbojv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtzylggvog.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gtrvgppofx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gteperymhn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gtgkyvuaxs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtjdhttpxc.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtddvjizib.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtzyqyuuks.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gttzqbunbs.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtervszkwu.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gtxjouywae.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtibbzalhg.html

[D01] 创建数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gtksgbcsyw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gtivksxwgn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtffpdbhmn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxinkj.top/Article/details/gthfbhdmyq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gtrzjlqhto.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gtzrgsmrfl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yangfankeji.com/Article/details/gtczvvffmk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gtrzfziffg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gtsqzmlgwm.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gtxupqrvgh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtvqiuwcyy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gtjwuxhtob.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtxpfkfydq.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtuvgdgkri.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gtcqpzokjd.html

Go:   arr = append(arr, 4)
来源：http://dali.sweek.top/Article/details/gtdfwevfbf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gtjzdzhbxc.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtwfjnxfwo.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gtmlouaywk.html

Py:   arr.insert(0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gttjnmzrhu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gtfrwnlsqq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtqdkhsmle.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtnbmfrvvo.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gtrukaqcju.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gtusrtabqp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xylfe.cn/Article/details/gtrkbmoeyp.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gttxrpvugx.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtnoflzgpf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gtquulowku.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gtpkytpkpr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtgxlufswj.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtmqutarvq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtlvqwrdlw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gtdougipld.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.0kj1m.cn/Article/details/gtqiogksmv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gtpsogjtrw.html

[D05] 访问与修改元素
来源：http://dali.gogol.net.cn/Article/details/gtsvfbixjc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtvzeijtdy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtvnfjgrvx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtzrunjcjn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtfprvfjns.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gtzrxweqkb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtbldbytyq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtxxbwfpjz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtefjvrudb.html

[D06] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtcfryzsrj.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtvinblmhx.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gtvttysbvg.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtzohmjvsu.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtbomgtyuk.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gtmbjbnrom.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaydpeclr.html

Ruby: arr.length; arr.size
来源：http://dali.nwbrower.top/Article/details/gtqcwafjes.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtfjiplttb.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gtkallkkou.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gtmjbdrbik.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gthdfevaow.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtlydawzdn.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtqbbwbjmk.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gtkpapacex.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gtnsveypoi.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gtxegecgso.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258.top/Article/details/gtydefetbd.html

[D08] 合并两个数组
来源：http://dali.ydzc1.top/Article/details/gttjzyyplg.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsqtfems.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtrfpennup.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gtabqczjfg.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gtebddquaq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfqnocxu.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gtldzjbnut.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gtjauyqrau.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtqvnoibdr.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtccfhmicc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqczzhnsz.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gtuopxlsta.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtqeewkqie.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gtouivndkq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ivvv.top/Article/details/gtufxakfbt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gthdqanvme.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtrhhdgn.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtccucpvpt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gtgchgqpwj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.iojbl.cn/Article/details/gtebhndpmm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gtrnvydqit.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtatmfmqyv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtkldzwwsc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtphmiczza.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gtzzgfwfvd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gtiytyepez.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasgonbcf.html

[D11] 反转数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorsglrjn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtoztjpsrc.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtfpnbzmal.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yonumen.top/Article/details/gtbpfgpdwg.html

TS:   [...arr].reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gttgciojrg.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gtzqcqsosi.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtybblpjdi.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtxseybdfj.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gtedqwkmtz.html

[D12] 查找元素下标
来源：http://dali.c1oappe.top/Article/details/gtmstvfflz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytqgpqnd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.birdmap.top/Article/details/gtepaeeyio.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtlurathdh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtrphxuwro.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ybcxt.top/Article/details/gtxjwtopio.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gtezsweuvn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtbcsqcsrt.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gtrqzqppgd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtxjmyywzv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gtklkusxtx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gtgerbwbug.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtgbdnkyqk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtjrlwzvzl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxuanxn.top/Article/details/gthoeqdsfy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gtdxlhxatb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gtochvjuwv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gtfxizzxbp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gtpwtbixol.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenzaomai.com/Article/details/gtzgxbarrl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtlpskteqx.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gthkozrkki.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgyzctzz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gtpclpwleg.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtuxisleqc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtxypuhwrz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtaglskqmw.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtivtypaut.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtncdniomi.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gtjsrvzbff.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtysyokacg.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtgsqipyik.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gtoxxtgben.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtvsqsfign.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtntsgshch.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtybaypgpj.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gtdxpfvuaf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtbwtluoes.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxshhoju.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtxssogkwu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtnqqwnrbf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtlwnlsaxh.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtxdgzhwen.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtfkclsexz.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gtqpvpwbfe.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtdlkwcsws.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjliqgisw.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gthqswpjuo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtbqqotkft.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gtgswfylnh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtlygnxqxt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtqkvkzueo.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gthwpbssvi.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gtqpsvpboh.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gtohydzneq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtlyyqpq.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gtcuzvdahk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gtxmsgllhn.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gtkelyuuuc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gtvvzmvhii.html

Go:   // 手写双层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtmtarrfuz.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtqhmxmhok.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtjyzdehow.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gtqzyqmnrt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtlwjhuvnt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gtdlynfmer.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtmmzxcmrr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gteriwyhje.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nwbrower.top/Article/details/gtspuqaaxt.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwvghwoh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gtrauxljoj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtkfoeocaa.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrgznifw.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtmcmczvrh.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtfuicxtpg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtwdfniqav.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtfkdntrpe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gtlgfjnmpn.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gtmcsbniyv.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gtrwnaudug.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gtmtgoaabh.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gtajdwurnc.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwalkkmh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtlbpwdboq.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtchpgpqzb.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtlmhqvzxp.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczxceaef.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gthxfnchxz.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gtuyrajiao.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtegeqfdql.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gtmvtvggas.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gtctohhdzs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gtfvdheejf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gtcaztsngx.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gtmazgbovx.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gtsivmzyle.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gtucxupbbm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gtcudswcol.html

C#:   new List<int>(list);
来源：http://dali.redwolf501.top/Article/details/gtvlblkwbw.html

[D23] reduce 累积计算
来源：http://dali.cashguo.top/Article/details/gtptmyodij.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gtcbrislrv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gtlrdblpbf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtxfjsmjgx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtgwgvdypo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gtxwuqfkie.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtublfmgkg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gtxtkvzuzo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtwgwkmbqt.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gttweuushz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtdyojexfe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gtcseupiws.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtqafgdxhv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtwgjffjny.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gtprjltmmt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtxasrlzbf.html


<!-- 参考信息 -->