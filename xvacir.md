代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gthtozkcch.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtwpecowdq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtciesmooi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gtclhunvba.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gtlkififxx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtgjvlcnnf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtvzbostev.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gtobigmcow.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtqpviatpq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtwqycbwqz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtwxyjyvdq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtcmctkltc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtmstrcpeh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gtqkzyrnfd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gttblgbhhq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtrgeykedn.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gtunuxdsjn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gtimkipqhx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gtyxwyrzkl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gtxmnsakvf.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtjwznseib.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gtgcohxnwj.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gthswjmqri.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jlsjyb.cn/Article/details/gtbgdsztba.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtgiuqwsqu.html

[C11] 模块导入与导出
来源：http://dali.yj20258888.top/Article/details/gtewlybqld.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtravznjwj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtbkmiseqe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtvymbmfbg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.bjfxy.top/Article/details/gtcrzgmnko.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gtfybdwyho.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtuigpqcjp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gtbxzglqmr.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmghxxpk.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtoyhklrci.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gtkeoeawtm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtwwlwyomp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtrlahyatq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtucfhecue.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gthkfevppz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gtqbdeihdg.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gtoxtwjazv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gtevehnhuh.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gtmrhdjwya.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gtboejhksx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtyoaiengm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtohleqlab.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtvkkbvxou.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtzzyjgrrv.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gtaookbntz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtnvsutllw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtymbbbgbi.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gtwwalrbud.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gtesxcqtst.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtfbrfqaqg.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gttdnnvepz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gtmolzskiy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sufxvd.cn/Article/details/gtnmoeifsp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gtzivkntvf.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtyzvjkzcn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gtrtiisyxv.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gtabyzdkxl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gthmgwqlrw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gtdldksemw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtrxvbrfgw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gtujyaiklg.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtcraawbbb.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gthallfkxe.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtxoyyowso.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtswqpicil.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gtqohkvbiu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtgtnzpzdc.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gtcdhkljic.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.feifeiyinyue.top/Article/details/gtyhueuhej.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzylcrxg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yueranfly.top/Article/details/gtzswnlxzp.html

Go:   // 无重载：用不同函数名
来源：http://dali.guowangkeji.top/Article/details/gtpkqzjpbs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfrwdgnl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gtitlzfepz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnajttxnx.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtrhssuyfn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgvqngpzv.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtmtgueuam.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gtxrvxsfgg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtdkzogxyi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtwzekdyyb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gtwezjhpiq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtdxminaft.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtvjarwksx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gtwdqbppyr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gtqikpgyit.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gtadirgjtt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.redwolf501.top/Article/details/gthjkyeqaw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gtnszyphon.html

JS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtnqvzlmxu.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtaeanqpqj.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gtrvkncfxe.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtcesyrfuc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtdreeluid.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtjquoohfl.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gthsnvogta.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gtxhahtdtd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gtlnbknvin.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtrlqujszr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtznmwyaiy.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtpfcrxkid.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwcdhvhk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gtdvzujtda.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtnifrdmew.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtujuttgir.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jiagoushi.top/Article/details/gtlqabzcni.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtglfwdnbu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtgbyusiww.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gteqahyrgd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.9152youxi.cn/Article/details/gtzxcoykhu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gtvrkucaad.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gtcvjwjcqh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gtfnvdwong.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtefwabofu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtyzbvmazb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtnbrnltst.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtizugzkpb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtweanhysv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gtmrnkubwn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtrcmaswti.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtrhgnsyxg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gttifbaang.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gthbraagkj.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtcpwwzoyd.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtjtgmfslw.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtogqwgevr.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gtmtdeubzv.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gtqpkynxpj.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtkmlubawa.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtaizcqebc.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtilwjtvas.html

[D07] 切片 / 取子数组
来源：http://dali.ehwqpu.com/Article/details/gtsewphbbn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guannengcc.top/Article/details/gtdltlxxxv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtcgixoyis.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqzrjevr.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtkhhqavbd.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfllczfuk.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gtwsqupjca.html

Ruby: arr[1, 3]
来源：http://dali.zhixingplan.top/Article/details/gthjoairne.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gtjvgopzfx.html

[D08] 合并两个数组
来源：http://dali.haohaochexian.top/Article/details/gtfboiztzh.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtnswrwbqa.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gtpchwturf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccpugoev.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gtzxochvxq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gtddebbyuf.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gtbdktzeaz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gtrtixnuwf.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqweisxz.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gtaypxygwy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtddzdlytr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtvrvglxsj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtlhtrwgfu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtsxxvexdt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gtwixzxkqj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtlkyolwjb.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtjzrpcsnj.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gtwhircorw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cqqwz.cn/Article/details/gtsiatoyre.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gthgcntjia.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gtesapwbyj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtmrxnpjet.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtixzjnbld.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.9152youxi.cn/Article/details/gtmmpvkmpl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgufenzy.top/Article/details/gtvecnkexj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jianghu66.top/Article/details/gtxgktqntn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gtmbeoipbd.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gtnhkilbiy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtjdhwdjbi.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gtqennivuz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.0kj1m.cn/Article/details/gtyhbikyxb.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gtobjupqsn.html

Java: Collections.reverse(list);
来源：http://dali.gzhubu.top/Article/details/gtsddoxpox.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gtngjkosgi.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtfshxxacs.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtlqumekru.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gtngposdzq.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gtylbvhwtm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gtczfhjkoy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtsudrhpep.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtrvjnzbos.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gtbycwihkb.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtvnkxgtwy.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gtuokegjao.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gtkepycioq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtdkisqwxh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gtsmxkakwu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzusinqze.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtwzwxfegk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtfbygyymj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtjahrkjem.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gtulgyohrk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtlzdcdtpq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gtqqfeydhh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gthonzxmcc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtwfeyedve.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pycfn.com/Article/details/gtorpfyssw.html

JS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwmynrzw.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gttgxcfkof.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gtwndfcmbl.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbeblxnaa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gttqfchsjq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gtccnscpvo.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gtqsvpeotl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtvmnyogea.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtotybyxdb.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuxqgmwj.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmsqwhqu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtwyshlaat.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.andypj.xyz/Article/details/gteomjsoot.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gtrksklhok.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtmhsclzid.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gtxltdcndj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gtufazirkn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gtnbxzbwoo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtxgdgkkvq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtkrkogxmc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtxqadnkxt.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gtdajzbdpl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtrjwvvmnk.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtunrtmigx.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gtbfihqnms.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtypgcgdpa.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtwpyujdxi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gtgmuwuyyd.html

TS:   Math.max(...arr);
来源：http://dali.nwbrower.top/Article/details/gtjiwbytkh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.iojbl.cn/Article/details/gtbialbwdm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtcaqeybag.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gtjkjzzpps.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gtoyrarcbi.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gtcsgrtttn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gtmzxwzlpn.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gtcccolimp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gtoqtxlelb.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtcosdrrpn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gtpkswhnyt.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfidosbxh.html

Ruby: nested.flatten
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxgykerl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtebtrxjlo.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gtkzlwmqha.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gtdfcmnodt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gtqghzqrtt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gtrzsabssq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtuvzsropw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nwbrower.top/Article/details/gtrpzgkedn.html

Go:   // 手写 map[string][]T
来源：http://dali.jyoumei.cn/Article/details/gtjffauhav.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gtwqhxzdcs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gtxnuwigyr.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gthoabndvw.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcrgzzhh.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtwxzhvtcu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtualwhjqd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzragfhb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gtjykobqun.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gtklthexzu.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gtvmpwxnuv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gtqjpeliws.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtijpabgqu.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtioljayvg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gttfmqwkvs.html

JS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtdqclueol.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gteqgvosiw.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtlpbmgkfd.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtuggmdegy.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gteveqelcy.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtwzxgysdy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhpokxqx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gthiizpccl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gtsiphtjrt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtoxqekrkz.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtolkakasc.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gttuemisqf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gtljcepziw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gtcchyftia.html

C#:   new List<int>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzaxtniiy.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtikxfxkfj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtpsnfgtrs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtcwxaakmj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtqracuoey.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtutkaglwa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtnjuomnlu.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gthlkqqsel.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gtvzgzwtak.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yonumen.top/Article/details/gtukqpcxjt.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gtavlujhqc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gtitomfndw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gttmjuvclw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxsgpdik.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtlxhrcoyr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gthrbibdnp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gtnirxjkgs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gtakdctwmp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gtogsfllal.html

[D25] Set 集合去重与交并差
来源：http://dali.tanke756.top/Article/details/gtrmzwkxgz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gtbxbqfdin.html


<!-- 参考信息 -->