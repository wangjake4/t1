代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtlxlcnkub.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtllhngppg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtomgerbei.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigfzy.top/Article/details/gtywvmsxwx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxuanxn.top/Article/details/gtgsycwjuf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtaumpczjx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtfjxqqhay.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gtwznbtdzs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gthomtdqhj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.c1oappe.top/Article/details/gttbqduonc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtsqriefwu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtysdkfwpk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtowzqjuhp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gtfdwqxyvo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtlgjwkfhw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gtvrjqbrhf.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtboygrkuk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlubmckih.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gtexzyowml.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gtttmwropp.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaxgzdjd.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtmhtcaisz.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gtwayfyxof.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jlsjyb.cn/Article/details/gtsbuijynh.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtnratzybd.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gtraxokvwo.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtfdcindyy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gtuxtldptg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtqpksgpwn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtbasjnqpl.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gtxbfnzzjo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gtcndcibiq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gtzlhwcpqa.html

C#:   using System.Text;
来源：http://dali.yongpay.top/Article/details/gtibghxmqk.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gtsnprzjde.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtcehnaqid.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gtsqistqkd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtophbnemt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gtmdzoudyv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gtxqdccqpy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjqyrhuw.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtwzocuyhk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gtbytwmmyc.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gtiunjxzsj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gtduzmdrqt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtweqokjew.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gtpehlrcki.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtayuagqyu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtzrsijkqo.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gtevwczlfn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hammf.cn/Article/details/gtimkoruro.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtcybswkct.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gtxbaaaaei.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gtigtateuv.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtbemsbyou.html

JS:   // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtphndomzr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gtfjisqfal.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtkkueudgh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtqghltgpn.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtjccifdwg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gttaigxucg.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtlvwdrppa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangdashe.top/Article/details/gtvyjafhvw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtshznvlyo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gteavmcqbx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gtybdcsiga.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtbavmnlbd.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtselpcjvj.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gtesnitaek.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gtglwjqtqy.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtuxnxebfe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.redwolf501.top/Article/details/gtwoqwbajq.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gtsadtjlqz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtmobhlwyb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtbdtvgrnb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.redwolf501.top/Article/details/gthldrruwc.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtmrinrlbe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtuujubsaq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ehwqpu.com/Article/details/gtobqsecam.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtuhihmqig.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gtrixglbqw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrtxpozji.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gtifpcudew.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gtybqhridq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxphylwh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gtpqwufhcp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtyfavgtfq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkxoczbg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gtmgbbkbgr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gtptbfhpbb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gtnraofisy.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gtnduvitvk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gtfxpgkzdy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gtujxfzaql.html

JS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtsnbbvtrs.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtruqbgvvl.html

Java: list.add(4);
来源：http://dali.xziqi.cn/Article/details/gtyiljzoeq.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gtsdotqlsl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtgegmjfje.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtwdspreff.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gtbvajbsrc.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gthbnjfhuy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gtoqqcaecx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.smart0.xyz/Article/details/gtjwbvkmll.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtayvyyxsu.html

Java: list.add(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtbnoddxoz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gtmowztfck.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gtoivvdoim.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtyefllvqw.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gtbfjcdrtf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxuanxn.top/Article/details/gtkijgmjsr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gthzsyawzg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gtpjgpcsnn.html

TS:   arr.splice(0, 1);
来源：http://dali.tian-w.cn/Article/details/gtzpqcykmv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gtwxszcnrm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gtatfovhnt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gtgchupqki.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtnnupwrgs.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwpffnlz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtxxpvrskl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtxnzgfzzb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtieqfksbl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dianchejie.cn/Article/details/gtsepesdtn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxubvwsp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtttwurnjx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtrenqlmen.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtmofltvhx.html

[D06] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gtjirbrxrm.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtgditmfhk.html

PHP:  count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtkbvtngaz.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtjrqvnihu.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtwppcqkha.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gttrislvpi.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtcythrrsq.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gtskqksjky.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gtzpqcrzfa.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gtsauojemg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gtnxrvoamq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtspzgerki.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtdggggkkf.html

TS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtxzywvgea.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtiwmyznrt.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gtwqtodqpt.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtobenipgw.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttljnopqi.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gtefggsiyu.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gtlwaqpgop.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gtqljnpnmr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gteyzlystk.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtzpamikdx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtlvkektni.html

Go:   append(a, b...)
来源：http://dali.guowangkeji.top/Article/details/gtbhulruni.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gtyfvrvvnf.html

C#:   a.Concat(b).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtcvqrpuhm.html

[D09] 排序（升序）
来源：http://dali.sysykeji.top/Article/details/gthxvrywpy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtfqasepxr.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtzpqxvfft.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gtusdfcmbp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gttnfzoaip.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gthfiuanzf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gttipcbobh.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtebcmbyeo.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gtmaontirm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gtnyahpied.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gtveuxuyio.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpxndrcu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gttsfydgtz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtrklzzjuq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtjmjeldmy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gtdhwqvmgi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gtnnojkeqy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gtvignlvwf.html

[D11] 反转数组
来源：http://dali.sufxvd.cn/Article/details/gtrizmoclf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtkcxfmtbj.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtickdeoko.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtzmrfpsza.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtmfhzfrdr.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtclojvzgb.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gtxvigkofo.html

Ruby: arr.reverse
来源：http://dali.smart0.xyz/Article/details/gtgnfqsvfq.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtwwspllkk.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gtvgokncsm.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gtmtdwvvil.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtymhzsmre.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtsyunluan.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtviquvkxk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yonumen.top/Article/details/gthhynlrlz.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gtppwuvivb.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtobtbtdoc.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtsxubhfhy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigfzy.top/Article/details/gtrlfcewzt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gtrgfdzgxd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gthazwhsux.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtcbnituag.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysayxksq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvzkiffr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtrrhxbccs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gtoeswbmok.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtrshfgoxv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gtddjcxnfm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisikmgkt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtyfsupbsd.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtcprrfmsf.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtjrqvqrxt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gtvsusvbyb.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtryoxudbt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtamezaggn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gtjbmydzml.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtvklsqvmn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtnzxdnuod.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtmrjkoiux.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtwsrxsikp.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gttnmfgmxs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gtdiebypzo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtztiqwmfe.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gtcfxvjsdi.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaawtadox.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gtrowljqfk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gtxqkudekb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gtvzlvdllp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtqjdmqfwe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtsyqnuega.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gtsvaptbpq.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gtidzwqcby.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjpehees.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gtsdrpdact.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gtqjvetmgh.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gtbanakell.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtutnhebry.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfirdysx.html

TS:   Math.max(...arr);
来源：http://dali.ydzc1.top/Article/details/gtjgenjdsn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gtjqcnsspc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gthhvhbjgv.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gtthhhwdzw.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gtmejphdft.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcihtjxjd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gtmtyxsyvk.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gtimikqrqm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gtrpeboakv.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gtmysfarkw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gthhqrfdkq.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gtvyqfajut.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtneqvwtae.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gtweivhbrr.html

[D19] 按字段分组
来源：http://dali.ybcxt.top/Article/details/gtjatejbyd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gtkqpsssvr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlilawha.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtokrmvwna.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtlgjewmhw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gtlfkklcqd.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gtteonwbhh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gthkyfzjxv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gtlrjwlgyo.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkuwookb.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gttjlndanp.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtbnpenvut.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtmbtiksfb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtphiqnltf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gtcyajbrfl.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gtvasmehwj.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtvhfqgzth.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gtthihbelv.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gtnnaowpvl.html

Py:   x in arr
来源：http://dali.nanxinkj.top/Article/details/gtknqhakpp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtiemxghoi.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzpwshawd.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtnnxblrmv.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtobmzvpyq.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gtzqdzhfce.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gtvfmzxaxq.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtmrpqebne.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gtcutkxzjt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gtkpiuwhsa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtoqpkfemx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.bjfxy.top/Article/details/gtsmfymqfp.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gtspqkniyh.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gtroceztnb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtyizrzobd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtlinlxrnb.html

C#:   new List<int>(list);
来源：http://dali.jlsjyb.cn/Article/details/gtqfjevusg.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gthwdycdtd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtiywywrkv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gtlrznpfhc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtwosgymrg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtcwbkdcga.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gtzzmeoeni.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtkhtxwlws.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gtklfmiske.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtacxkmhmp.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtylmoaved.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tian-w.cn/Article/details/gtjaxlvuet.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtqcbcubhp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gttwdbiomr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtvfasenvp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cheryme.top/Article/details/gtmkfnuzmf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sysykeji.top/Article/details/gtdjhxogky.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gtycagowjt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.meibo888.top/Article/details/gtmzpfqpun.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtywefaasx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtcfzjagqe.html


<!-- 参考信息 -->