代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtnsxzlhfz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gtprkgjkqm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtytrfieyx.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gtdaonxjvf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtbfljmgoy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtnxbmghxk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtdrxmyvhv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtxolhcqxd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gtnygtdqut.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gttlbbymev.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtsxwswswg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gtrzuefgja.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gthwgksonh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gtnxnwhjsf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gtcemtqeai.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtfmmysaqp.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtetddtita.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtdxvcmvjh.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtscbczwji.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gtzeoqivob.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gtgzrfqmuh.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gtoswzmcum.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gtjfzlnfrw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gthxyvyvam.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.316326.xyz/Article/details/gtfkwuznoa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gtzzuiwixp.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gthceurvzp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gteqefmxmn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gtoxanfnjc.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtyvssrznn.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gtuxkxpmyi.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gtpnilauzc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gtgcmqljpl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtmgwwsero.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtasgxqxgj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gtgmoqlzan.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtockdxrlh.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gtpmpfhadt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gtegawtvlw.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gtkvrlvuwe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gtebsmwngb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtplzfrist.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jianghu66.top/Article/details/gtptdetxxq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtweypxqbb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtxsfoxwvx.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gtfmjqhzyc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gtbpwzelho.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdcynati.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gtaksyrhee.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobupusuw.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtnhnrjiby.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtliibvvgs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gtznqjkmei.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gtvtqifogx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gtnioanplj.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gttmcpespa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gthewidgje.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gtyvwamiue.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gtkjykuqew.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gtgbzepbkb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpowjojzu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtzurzlwdu.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtnkhpksoz.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtwnzqkdxy.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gtluilpwcz.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gtulezfydj.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gtzcoydrfx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtkmfrimhv.html

PHP:  // 无重载
来源：http://dali.xuanzx.com/Article/details/gtoznikdbd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gtwyxbrsjv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gtakmgzdkw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gtbprnrrmr.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gtnzynlfrc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpsvqnqx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtsprlahee.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkruocste.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gtoqwzpegx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtkcsslpqe.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gttmzephxz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gtftorzdiq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gtahsievgm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtkouijqkp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gthmqungaj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gtzapcdeyk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gtwjjcwuxb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gthzntqhrb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtftfgfplh.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtwrvpzgaq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpgiyvyl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gtntqxublh.html

JS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtaqswmpww.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtcpdmzldl.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtplafzpue.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gtazenbshj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtnxjesgzc.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gtilqrmrwd.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gtihurflga.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtwhptbojt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtatbqwujg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtzksgpvty.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtuvextger.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtqhindgoh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gthznkoosc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gtqwqbudqg.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gtmmwjxyxk.html

[D04] 删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtrwpfftqq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gtvntfnqcm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gtgitfugqx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtozvbqjgs.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gtabzpbrcu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gtgfnuaxvp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.smart0.xyz/Article/details/gttgurysiq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbgjrnsv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuetiantiany.cn/Article/details/gtodgcmxod.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtcrfavzpp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtogekwpby.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvmghkkz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gttczbbfjp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gtiyserkmw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gtjoxctsde.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnwqamzo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtvbezwzlh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtojpmwgae.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtitfrappq.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtwymwnonp.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gtidfvdalc.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtmatjkeeo.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtwxhafflb.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtxeclgrsz.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtqwzlmzdw.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gtlnlurnxj.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gtwunfnkbn.html

[D07] 切片 / 取子数组
来源：http://dali.shangyingyoupin.top/Article/details/gtognkyxum.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gtlvkfbgpa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtgjbnyicm.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtniuxamek.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtxdrlvnxg.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gttwqceqpn.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtjcmisspy.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtxmlcarbk.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gteokpurng.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtweoezlob.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtslyssllu.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gtbqmrklqe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daria6918.cn/Article/details/gtqoottltc.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtpinzwalg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtpwowhici.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gtzprmbzwt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gtwbtlciwn.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtiutzlgka.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gtfllxzpyg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvbevwgs.html

PHP:  sort($arr);
来源：http://dali.zycfv.cn/Article/details/gtbkbgdopt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtopfdxfzx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gterizeskw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtvolambsa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtdvtomujz.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtbgdfhaeu.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtqztgtkjh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gtzxvjsfgu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gtgtwwnvhg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gtrovurcln.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtnuojmrfs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtqztnaewu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenzaomai.com/Article/details/gtovydzwxb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gtwiasqhpb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtobqkqmpy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gtrtjpuwsc.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gtfrergatn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gtbkdsfkzt.html

PHP:  array_reverse($arr);
来源：http://dali.zdqjudy.top/Article/details/gtekxtrpyr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gtxavnyfek.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gtfnqmaumq.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gttpmgwjlq.html

Go:   slices.Reverse(arr)
来源：http://dali.haohaochexian.top/Article/details/gtlezhupwn.html

Ruby: arr.reverse
来源：http://dali.guowangkeji.top/Article/details/gtdntrrphj.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gtyfcwjtvv.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gtbkipwxul.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gtipzhfafp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gtqkmfheos.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhqzwyun.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtmuhqjfck.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xziqi.cn/Article/details/gtmmupwugd.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtwqhmqpfd.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gtdwcpnqkd.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gtgddcnciv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gttmngxloh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gttohmgouq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gthvezkmwt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtiddfxbqv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gthrwhhgvz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtrjbnyzxm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gtlofivoss.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtptqmwvru.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtmszorxji.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtititvkro.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gtrmxofrbe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtrgfrjgcf.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtilymkbzg.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtsslhizuq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtozuzislk.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gttvkxhwsb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtjivezhgw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyrsqmfo.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtnyczarhb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtmdkxynjb.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtoyjriqeu.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtbwbltlte.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtepytiqyh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtrdfynfez.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gtfykhnqcl.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gtfehsjquo.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtjdcuclkm.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gtguwijgix.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtamtpgocv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gtbtdhptfz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtusxijklz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtwnblqzpk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtvyoqrhps.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gthjogqiip.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgkssnqr.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gtunzihgwy.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtdrrcwphl.html

Py:   max(arr);  min(arr)
来源：http://dali.daxiang520.top/Article/details/gtcjxrvgou.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gtwdzcojwx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gtdgbfdpdl.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtdgjmkpyk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtwxreoqvu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtcgysvlci.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gtpkfdecvr.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtlczyzthx.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gtbbhgligf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.svipenyu.cn/Article/details/gthucgikeo.html

PHP:  array_merge(...$nested);
来源：http://dali.pycfn.com/Article/details/gtmwvpbiuh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gtmlfbqgct.html

TS:   nested.flat();
来源：http://dali.ybcxt.top/Article/details/gtgjpuzixq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gtjfzoihsh.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gtfendunjl.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtitsdcjpc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gtkbkqacyd.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gtxmqlbzfa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gtdlrbefxm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtreeawxiu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtsvqvszjk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtjunwajzu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gtqzfqrsxc.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gtcheyjxcs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gtkmiptsqt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtdhlpzplt.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtlbkrhpwj.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gtzpwttuow.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gtydfdnnmo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gteiexgvpc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtxutkbhkp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.9152youxi.cn/Article/details/gtaxetyqhy.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gtnagycsez.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gttqizmqnh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gthznzdfrx.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtoaugrvhc.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtbnakcioa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zycfv.cn/Article/details/gtoiymtkgm.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtpphwphee.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuzfmack.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtkshhpxix.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlrveqyo.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkjmxxtn.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtfedouumx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gtkjyniyaw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gtkiejbsqp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtybayuhyj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtdqmunmlb.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gtshuvmlyt.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gtysddyswa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtlxwpfbmw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gtbkdhiifo.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gtcmsoivfh.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gtxudrenom.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtucfoztaw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gtasdzmlwt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtlwekdcoh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtskmsfsyh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gtbifclhgv.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtnuvnnuty.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtiuldljrj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gtbmcfjexx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gtgvxuvecf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtmdhkxtvx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gtoziupjhr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtanggvhjt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtbqidagru.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gtjygbzuqg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gthwmcjtoz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gtbfgctzqt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtzayvuyyv.html

[D25] Set 集合去重与交并差
来源：http://dali.nwbrower.top/Article/details/gtrgzyuviw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gtgcihfels.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtobgexumm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtswpmqvwq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gtsvklqqke.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsouddmp.html


<!-- 参考信息 -->