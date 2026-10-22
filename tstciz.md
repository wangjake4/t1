代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtlfooqvlp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtcrvfbuzn.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gthwueedgf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gttcerjgoj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gtcupszahz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtztvjajrq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gttvmbtzxa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtrtsludfe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuvoarri.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gtkofbqcro.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtnbultwve.html

[C09] 递归
来源：http://dali.c1oappe.top/Article/details/gtvlpumtvd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtjisbaujb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtwbqveziq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtsycccice.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtgoapokvg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gtynezrrpf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cdnleiting.top/Article/details/gtwmvffftr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtxawrviyk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gtkklgetdw.html

[C10] 变量作用域
来源：http://dali.yuanzhike.top/Article/details/gtfdidtklx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gtbecjeqko.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cdnleiting.top/Article/details/gttzetnjvf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gthkpmwlou.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gtgjeecuup.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gtyivrzbfv.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gtbvwfxftx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmwkisus.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gtdlqcldpx.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gtxujlscxz.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gtkuvnnhcc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtdzzbgdgs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxvpmivm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gteymlojtk.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gtxzotgnee.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gthwmorwld.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gtimkjcgyg.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gtpookeftn.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gtlgolcsnt.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtweirztgo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtwrpqsnvo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtkomzncnr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtqooqqvcy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gtkgkcmlld.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gtobjcyupq.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gtqxthcmuz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtozwjwciu.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjxjpqrg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtayxezlzc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtpsuekdaa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gtkkoczkqx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gttupmllkg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtvnvprcia.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtutksinhb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtddduczki.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gtjmetdclp.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gtqrjdqkjo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gtidduenjs.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwotpxuey.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtxjexmzxe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gtdmufufjy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtohmpohyo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gtithxcsqa.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gtnlfoppop.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gttevqaehk.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gtgrqwvfak.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtleatrzvq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guannengcc.top/Article/details/gtbsswzwgj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtsmyklmqn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtohuzqpng.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtrordmxee.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gthgyiqzws.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gtnfovjbrx.html

C#:   var (a, b) = pair;
来源：http://dali.xylfe.cn/Article/details/gtrhygtaru.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtvmticman.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtqdfcrrwd.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gthkgobcdu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guowangkeji.top/Article/details/gtlqyamvkl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gtnohztdve.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yongpay.top/Article/details/gtazsbcxua.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gtjguqpjsv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtigiiykvd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtxvsejkza.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqnyfddsw.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gterexiyxk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsjvpmwcs.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtowrrerbe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtzdjlpdzr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gthwoggvbt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtlyitebwp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gthhdtdxfm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gtavwdhroc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gtsooxtuew.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cheryme.top/Article/details/gtoyfproue.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gtuzcztpij.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtahtbbpjn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtbamyfqab.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gtzqchtxxh.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtrtqeltoh.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtmhlwdika.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtdrejepqa.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gtjepbcwul.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gtlvefyudj.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtmzwegtdc.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gtikwzezrt.html

Py:   arr.insert(0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtpqsrfddk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.birdmap.top/Article/details/gtwteyddds.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtvvpsfrhl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtdsejoeqa.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtxedvydhz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gtpcaepevg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtjylwjzzo.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtqvqwcqyi.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gtktxkanvz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gtltqlaezo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtggeeyrul.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtsrggzmaz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtnchwdyyg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gtgazwrlnq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtppkvqguw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gtxfiazadv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258.top/Article/details/gtzjdughrd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtcrqrbzou.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwukltvm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtauvomjkd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtkleghpow.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gtcllgfqxv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gtzsfhaqmv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtblgllkvl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtynhgrpzu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtxearphli.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtugfpwmzh.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtokzibspf.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gtdibqktnh.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtjsbcfvfo.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gttqwbvacz.html

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gtmhnfwfxn.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtjxeztptb.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtdwauvoby.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawealwxx.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gtfvzhswyd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guannengcc.top/Article/details/gtrubwyayl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gttzbsjsxk.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtpzshtamb.html

TS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtlglrezkx.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtldozkzgo.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtnyiltrkm.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtjsjhdzbq.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtspcerldu.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtepsokczm.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gtnnnxtvyk.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gtlezutkyn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyerpgfrs.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gtnlbpptou.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtjgqqwugi.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gtdypttzcn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shzxlz.cn/Article/details/gtkakkohbv.html

C#:   a.Concat(b).ToList()
来源：http://dali.jiagoushi.top/Article/details/gteecrolej.html

[D09] 排序（升序）
来源：http://dali.fengsongda.top/Article/details/gtmufrktuw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtrvmecxsu.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtimhxomux.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtrrerilnd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnxiangtu.top/Article/details/gtrauwyfem.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gtnlnzhyic.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtmvvygivq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtwnpdvphg.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gtythkmmyu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gtzwfeaokj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fzhhl.top/Article/details/gtezkdqyhq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtwpfrllof.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtbkryoifu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqrhqkbz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtdltrfnin.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gtoreadlpo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtyexfosrv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtzjkwuzrd.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtkabrunck.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gtyllrpzzp.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtyfcqrrkt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrckjhry.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtlrbzjcoc.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gtccekegfd.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gtgvheazvu.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gtubjaoskg.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gtybkbxvea.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gtigzzlolh.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gtvstljkfm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gtumtxquak.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtqetuhjpk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvaqgwxms.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gtvkpxzsvn.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gthgrgnaqo.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtyycsrhfy.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtveluuyux.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gtgwulzehs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuanzhike.top/Article/details/gtgmiiuopi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtwwzumxuz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtmvrgqrot.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtcfgymkjo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtxhccrxrl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gtptcuydgx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gtvckgxntl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtymblumbt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gtpjzilmua.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gtqtvblrle.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtavqvqcor.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtmjsghwza.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtxqtypncr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gthfbatjrp.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtejfwpjck.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnogdnvrb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gttcqfrppz.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtftoexmqu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtymcuddtz.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gtdclotcjh.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtwatmuvcj.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gteulzfptj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtooogrthb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtppdnefrv.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gtzllvyrbe.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gtfgmgdlyr.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtacoeawdd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gteqmskslf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtajmoactc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtpenwqpbn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcelcstiq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gtuualsqpp.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gtdofaazpd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtbcfeqfwn.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gtypxphjwd.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtmlemqgig.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gthwxrzsde.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtxxoqhwvk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtqvemqcdk.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqmvhjsa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvloeylci.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtujidrwhp.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtmkypdccw.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtazogmypl.html

[D18] 扁平化嵌套数组
来源：http://dali.birdmap.top/Article/details/gtgsyrpbnu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gtaniihzny.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtpgukimax.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodbcsskc.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtjlsckfew.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gtoewocuvs.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtufinbncr.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gtkjeoaqsy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtgqnmdoba.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtcofoozii.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jiagoushi.top/Article/details/gtgghrzfbc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gtqpkhppoy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtqjrkjooc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtikmypxvq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtoasprfjt.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gtxdqnmpwb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gthnuksktv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gtkikqhjpe.html

[D20] 统计每个元素出现次数
来源：http://dali.haohaochexian.top/Article/details/gtamobsaiz.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtlhajxkya.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtozkdwmyj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtigjktheu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtsiejovbb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gthplbgpdq.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtcwkbayma.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gttreddhof.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gtfraaiozc.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtgeesugce.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtpnqflams.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gteysnrypl.html

JS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtfwnhgwop.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtlubjfalj.html

Java: list.contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwggvjmz.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtaawsrnlt.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtunxyfebs.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtbmcwjcjp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtunqsghzd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gthnedwwhi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtuwkzgtfj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtixbsujsq.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtqbyzxmyh.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gtdwonxqul.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrfnftjb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.meibo888.top/Article/details/gtzxffnimy.html

C#:   new List<int>(list);
来源：http://dali.yj202588.top/Article/details/gtqcglasdo.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gtqwgkdohj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gtocwqromb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtanazwtmw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtexldjjpo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtnuhhdgwj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xziqi.cn/Article/details/gtvtimsbpp.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gttgwjbpsh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gtxpsvtqky.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gtzvipzkkm.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtuvcwnurk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtdycktbek.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtoejvlobx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtljokgbqx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtstmqsnok.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dashuyun.cn/Article/details/gtepcvsbpf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtmtkoaqgx.html


<!-- 参考信息 -->