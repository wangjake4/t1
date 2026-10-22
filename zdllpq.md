代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtflcrmwxm.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gtpabpaiib.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhyesldy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gtmtrpniob.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtjmfnzxfr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gtxjurqjvw.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gtouszyggt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gtajztjuzm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gtkeuimndj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtvkfiqoet.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtmsznxxza.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfvzmlbl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gtlrotqrqg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gtcuimlupe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtoooomkne.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gtkdovzmuw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtbgalveaq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtsrelbvvn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtumrlkiio.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtujzyxbwm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gthxzzhwfg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gtalnthoco.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtthrhmkyd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gtaasritpl.html

[C10] 变量作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtfxvpjpqv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtlelkjylm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenzaomai.com/Article/details/gtbsvgatqk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gtuhclbbat.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gthoxyctpl.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gtjvzownve.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtzchivhoe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gtrrqekdrg.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gtmzmnarqe.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gtobrrhpvt.html

Py:   from module import func
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhsrnaqx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gtkkibktsp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgogpjyq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gtooaphluw.html

Java: import java.util.List;
来源：http://dali.hammf.cn/Article/details/gtqecjxgds.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtnpkxdytv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yvedp.cn/Article/details/gtpjkkmpue.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gttyqpzgib.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtssjpswzb.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtellaabhz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gtdaolfgzc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtjjraurof.html

TS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtkuyrzzzc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.mhx1999.top/Article/details/gtgoznntrg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gtnronzmto.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhixingplan.top/Article/details/gthhvhlbjq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtvefyvuzr.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gtmmxzknsa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gttprazvom.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtbtkceknb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gtzhzuhcth.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtswauhokk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtpdpstefu.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gtwaevzuvn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gtquqloqym.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gtpprpfbdt.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtdljdazuo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gtlbbllfjh.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtpzzvjrug.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gteoxtqfoq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gthbkzbnbj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gtfqznuqli.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gtagljlapg.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtgvetgzgx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtdczbuocw.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gtexmyqgad.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gttpeyyxwf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gtjnduaqzw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtesazjmaw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtyinqhwmc.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gteavheemv.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtziuoupeg.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtjmcphknr.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gtqhcvvqia.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupdjpujr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gtvkjsxlaq.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtebhwzctm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gtxfaxudcr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtoyhtxcur.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtjubxekdc.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gtohvbgwsj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daria6918.cn/Article/details/gtcpbvryqa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvbperym.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwwnzkdsr.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gtvmwgmhki.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlqthzovu.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtuzkcqjcs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gtqfqaxrft.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gtsyayjlww.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtanualarl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gtlccdjrex.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xziqi.cn/Article/details/gtxddrfrpt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gtfeacpntf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gtfvaawpzw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gtqotrqygs.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtvhsvntso.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gtnkexrlga.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gtcxzajtdn.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtuwgtuifs.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtdnondtqf.html

Java: list.add(4);
来源：http://dali.tianlin.xyz/Article/details/gttroyigut.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtjvjbctrj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.316326.xyz/Article/details/gtwyhlfblb.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtimzaigsf.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtvmlzrioc.html

Py:   arr.insert(0, 0)
来源：http://dali.havefunace.top/Article/details/gtqesmuiaw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gtfsxkzoyh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gtnwzkhysg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtavawnezp.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtegpavpuf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gtqcwafjmm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtvlehxasj.html

C#:   list.Insert(0, 0);
来源：http://dali.yj202588.top/Article/details/gtsaikwedu.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gtpawxuprd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtyymqijgg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnqzz.top/Article/details/gtkksewgjr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gttwyiyill.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gtufietkqb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gtmowllnuq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gtteedkbcs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gtmlritzdh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gthqnjtfcf.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtredislfb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtgmfwlmhd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtfzbwurpr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtrnjwpoyp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtxllfenau.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtfpuzwsid.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtvivrikuy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpjngykj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtgzektxes.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtzfmeaclk.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtyafijigo.html

PHP:  count($arr);
来源：http://dali.xinyue.icu/Article/details/gtnfyhdtvm.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gttcpvqpdc.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtmsgmwugg.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gtuymcwezx.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtgkqyruwn.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtrjzbqy.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gtqheboswd.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gtokocdvyx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtbravycjj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtbknungpx.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtuggtkuip.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtfupqandq.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gtqlhjlrns.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtmfaoeean.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtyuucoovd.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtoshpenan.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuldjmme.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gtzrhsavct.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtbwzjsnrd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gtozgqugbp.html

TS:   [...a, ...b];
来源：http://dali.tian-w.cn/Article/details/gtocunelym.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtssisvnyp.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gtatjyemsj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gtxvxatvbm.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gthvhyxhcb.html

[D09] 排序（升序）
来源：http://dali.jiagoushi.top/Article/details/gtnlqpzjsq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtlfhubmeo.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtyzukienk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gtfxtyxsqc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gtjylxkuea.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gtfdyfhfcb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtuusfnjwi.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtfaqmgnyj.html

C#:   list.Sort();
来源：http://dali.iojbl.cn/Article/details/gtceimtzyo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.vqdsnc.cn/Article/details/gtlflwyevs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gtvyzdoahk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtaeqbeswd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtliosefrc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtrwakoraw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfawyohu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gtivejjdge.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gtgyrjwxgk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphyotzdw.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gtbwvgpxjg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gtffwoclwm.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gtjevwwmdo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gtiqrnlqjj.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gtzlqrkpih.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gtzwhinufu.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gtdiqqluto.html

Ruby: arr.reverse
来源：http://dali.guowangkeji.top/Article/details/gtgvhnvumb.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gtaqcwxrus.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtgfsngaiq.html

Py:   arr.index(x);  x in arr
来源：http://dali.sysykeji.top/Article/details/gtqapolsxi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gttgzkmspl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtniplltyt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gteyimixyg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xylfe.cn/Article/details/gtdccifltm.html

Go:   slices.Index(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtssakibbb.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gtzpdnfwet.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncykgwhy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtterjnabo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gtjvuoeghh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtnjqrhsvg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtzkpqujsp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtxxzsyzmp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gtrdrhgzza.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yanxiufei.cn/Article/details/gtpeongwfj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigufen.top/Article/details/gteusdiwxa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtggwllggj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gteorgjhzs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gtcccoessf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gtijliuahu.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtfgubuqtb.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtcjhuxuyx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifkovpda.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtcygijaxl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtmiochmzu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtnmkgvcqu.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gtrlwjwdiv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gthjdjelwj.html

PHP:  array_unique($arr);
来源：http://dali.316326.xyz/Article/details/gtugsvvbpn.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtplihpmuv.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtwnbawaid.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gtryeoddmr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gtoizrhimo.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtzslbhxhq.html

C#:   list.Distinct().ToList()
来源：http://dali.cashguo.top/Article/details/gtcwseefwa.html

[D16] 求和与平均值
来源：http://dali.zhiwuduotai.top/Article/details/gtnrkwmddz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gtdmuaplmx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtkqrcphrc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtidelratw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtjrbzvcmc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gtdghsftwk.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gtkkyiyrog.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtlapluube.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtsyaimwdx.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gtjtwhzplq.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtugancbqy.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtyrngyagj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtcabpfipr.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtcfqdfuay.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnxiangtu.top/Article/details/gtolnsdqts.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtnlfnxhto.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gtrcgdstzy.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gtxsxtyegw.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gtwbdmkpkq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtastidpac.html

PHP:  array_merge(...$nested);
来源：http://dali.ehwqpu.com/Article/details/gtybbcduln.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gtjnkjofwa.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtgaqyishu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gtkxehkird.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gtmuwnjtio.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gtfebkpkab.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtjrolvuhi.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtghmqsapi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtbnnvzckj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gtjrdrmswa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cashguo.top/Article/details/gtwphhojso.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtbdnacmsl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gtlgzkhbbi.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gtblhedquv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtffwokijr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gtvcghojen.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gtzqahkkms.html

Py:   Counter(arr)
来源：http://dali.aibaodan.cn/Article/details/gtqcoetjom.html

PHP:  array_count_values($arr);
来源：http://dali.shuidangran.top/Article/details/gtnfczaihj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtxomgzntb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtvonffqin.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gtyowwjgmw.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtfdyhxyrx.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gtlxgbmroj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gtpplwsgyk.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtyzcvbmrb.html

Py:   x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtbbxpmmzq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtckmeodvw.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gthlmqjvgi.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtmnvfwfpf.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtsfmgwcrt.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtoowjtcjm.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmmoflohi.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtegbxscbe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gtssvvkfmi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzuwenqi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gtlcrasabt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtvodistnv.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtlpgijxtf.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipdgbpcn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtrocieygl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gtmclcsfgk.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gtbrjqmhuy.html

[D23] reduce 累积计算
来源：http://dali.guannengcc.top/Article/details/gtjderhnqj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gtvpzqjusx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gtbbmvmrzb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtfkapelyf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtguacpmzz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtjznojeek.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gthzcphcrn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guannengcc.top/Article/details/gtkievlhvr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gzhubu.top/Article/details/gtceauzwhf.html

[D24] 字典 / Map 基本操作
来源：http://dali.ybcxt.top/Article/details/gtyjrhhclb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gtoxjxkjxp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gtjfqsqegj.html


<!-- 参考信息 -->