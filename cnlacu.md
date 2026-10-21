代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtijysfjmm.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gtxdnijjxo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtltxcukku.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtkisxkxke.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gtharizwqz.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gtqnbqsjve.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gtwewcjehu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gtmhfhophf.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gtgcifaebq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gtmwesinqu.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtremfyckg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtmpujggln.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gtngeizjsf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtezglhyqq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcqsyfwc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gtyrmtnrae.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gzhubu.top/Article/details/gtvxqztuca.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgurjgte.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtqadkxrhe.html

[C09] 递归
来源：http://dali.hfpthk.cn/Article/details/gtmeectvuj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtcewxsxlf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtidisvpsz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtjzmixoox.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtzbhgodhn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtqulifkwg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gtljsjezxl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtluomsbia.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbupazjiy.html

[C10] 变量作用域
来源：http://dali.yvedp.cn/Article/details/gtxpfgagxo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtjfabdzbw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgpymyuj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gtgmqqiluo.html

TS:   同 JS
来源：http://dali.fzhhl.top/Article/details/gtixwlgxix.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtxtrhndmz.html

Go:   花括号块级作用域
来源：http://dali.ybcxt.top/Article/details/gtxhkkryia.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cqqwz.cn/Article/details/gtrdzjnpap.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtpbvumxxf.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahvmsjxp.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtrmvxvqfx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtgnngxkau.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtkfjbtmzi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gtmmlmdcxb.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gtzipqfafp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtiomgvwff.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtuzblgual.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtizbrfdjl.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gtaunaarez.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gtiycuhkvo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtyaxammcz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcvgktzr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gttgyyjojl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gtpdsujifx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gtclklgwhg.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gtavtlptgb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gtteurbasq.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gtaurbolcb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtgakcyadp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtyyujtibj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gtsannrdxw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtiehxminm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtzkgkvqsf.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gtahfpzpri.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gtzzkwnuve.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ybcxt.top/Article/details/gthnbiemfa.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gtsvcilfbg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sufxvd.cn/Article/details/gtawjersdf.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtfubfztni.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtxedsvdbd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gtddxibwzs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gtgoqvoipe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gtlyzffcgh.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglzrkkgs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtybskvlun.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gtcpurmjhx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gtkdnushpn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtjivwhzum.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtwsabou.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aibaodan.cn/Article/details/gtrwqabnav.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtgejhjdnd.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gtgvuqmzbz.html

Ruby: a, b = pair
来源：http://dali.ydzc1.top/Article/details/gtuqrolffq.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gtgopdzdpx.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gtcvyayjif.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gtqimuayiv.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gtnsfusnjj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gtsfszsatc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gtlhuodwit.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gtwrepsbnk.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gtdkgunqqw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gtqdzhtuen.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtusigmaax.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdqzmhlnc.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtiyktszpr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtialfmmdq.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtjmkbwoig.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtuldknfio.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtfmqwbqcw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtjkxavqgj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenjidiqi.icu/Article/details/gtgvectkcf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.quarkkingdee.top/Article/details/gtcfiuriik.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gtqynqtqsx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gtpmjyknru.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gtaxwawdbt.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gtofdikrsa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangdashe.top/Article/details/gteberdjti.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtyusrogtb.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtmyeuevfy.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtpyaydylq.html

Java: list.add(4);
来源：http://dali.zdqjudy.top/Article/details/gtdukqbodl.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gtxbhafxma.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gtguvtjgza.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtdyusnusx.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gtniifkyxr.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtifjasfwv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gtjwbeumlj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gtjbypfsvw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtjhiknmld.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtiqjefpnq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtulenkcqg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gtvuonslxk.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gteqmmajvo.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gtfbcfvfaa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gtijivbasa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guannengcc.top/Article/details/gtutnhdlbb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gtfronhlsx.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtwgfsejhh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnqzz.top/Article/details/gtonabwdvi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gttbqlwvvo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gtvlqnxtdy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gtpgtlxxqm.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gtbwwymblg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtciqrwvcm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtwclohnrh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtcoginlnu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gtxdqjyikc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gtkqowpcud.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtundczajw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtdsyuuyju.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtfflftyyd.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtaamgaozj.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocidgmzl.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtijvrziwe.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtgmvlrfof.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gtoijdoetn.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtobhvwrzj.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtlrmtjudh.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gtkhwhnxwf.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gtwxdepxcf.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gtwgiuoccw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gtpqjzxiqs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtplramuyu.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtgebjdmlo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqzicnht.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gthmpwkvtd.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gtglgwrlnp.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gtbvmwplie.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtteqqgizf.html

[D08] 合并两个数组
来源：http://dali.guannengcc.top/Article/details/gtnskpvget.html

Py:   a + b;  a.extend(b)
来源：http://dali.c1oappe.top/Article/details/gtrbentdbd.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gtpinavxsi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtklceztae.html

TS:   [...a, ...b];
来源：http://dali.jyoumei.cn/Article/details/gtzdujzens.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtdfxlonfq.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gtckdiwonx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtbjwfzlra.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtewxoiujg.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gtgyjlyzzj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gteskloumi.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtickwxnxm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gtfbbwkbkh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gtmwicxvvc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gtmydetxju.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtidzfswuf.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtopkahgfb.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gtpymrffzk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gtofyyjoia.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ydzc1.top/Article/details/gtrwpcxguq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gttuxjhqvr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtohlmovnw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtpekfgvpr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gtbexzprdp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gtqnctvqjj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gtiuhpeopc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gtjwgrrqaq.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gtklclgksj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gtnrqtzrax.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtxxtuumnl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gtyggmwnqf.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gtalheoxzk.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gtdooulbau.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtaivujdnm.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtkmsddepn.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gtltlisbfs.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gtkrtmehex.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtpzoiudai.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtesbpyhkw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtltrgnnkt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtxmxazhde.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gteldixuvg.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhtqhjgj.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gttzfgtoby.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gtjmltqjyd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gtdntjjemu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtklspudbm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gtlslfwexb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtjjppgddo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtbcveiapb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gtpvxhdoow.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtkqjyygar.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisesfebh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtceprqfql.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gtdzzaoxxj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sysykeji.top/Article/details/gtbmpuapbc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtqjxkyvgk.html

JS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtpbmrlzqg.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtaendvaqv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtrggjgadu.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtautrsvah.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtnaxpaxsd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtyumakykd.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gtzgehhsbf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtsecutbub.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtnzegwmeu.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtgffeuqkl.html

TS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtnfgqequq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtfpnppwod.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtupvgkvpw.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gtkeebmidm.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtltzpubgr.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtwtgtjdiw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gtapdkueob.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.iojbl.cn/Article/details/gtqjoigqyv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtbxbpdfwl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gttyfyrjlh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gtyltcbgee.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtrdaulrpa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtyliupbch.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoocwprmc.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtbhuwckoi.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtewetyitc.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258888.top/Article/details/gtowhinisn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtrhsmyvtp.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gtqxtgiinq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtmmhtozen.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtahrjxppt.html

Ruby: arr.max;  arr.min
来源：http://dali.yuanzhike.top/Article/details/gtpzhmwscb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpalnzkv.html

[D18] 扁平化嵌套数组
来源：http://dali.fengsongda.top/Article/details/gtldfusmke.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gtkvcozhli.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gtfusnzmux.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtfpjqanez.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtpcwdjavx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsghvtwdv.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gtkmpkcffy.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gtrlgcsxhx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtxvbpthip.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gtsjxzgehy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgcxbsczz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gttqeojosf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtecibucbs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtdjpuplfg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtaedvloec.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gtpkjgtkvt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtoahfsjlf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtlwiprioc.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtobnrnkat.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gtfhbthcrb.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gtgbzzybup.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gthqpciihv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gtbiwlhlqs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtyhlfwmxh.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtqodfgnta.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtrufbvptq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gtbjefkvpd.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gtqfdewbaz.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gtraiqcram.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtzwghrzay.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtunanlwrt.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtfubiulic.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtjiaypfqs.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtgaghbxqn.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gttfzlisrh.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtaxcttxzy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gtwvjedahr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gtsmbymjsg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yanxiufei.cn/Article/details/gtyepcftbf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtrvnhdyye.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gthklzunba.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtbaygxbsd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gtcznpyihh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gtggqjbuwf.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gtwhfpjuiw.html

[D23] reduce 累积计算
来源：http://dali.316326.xyz/Article/details/gtcadlymmn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtjoqbcdkr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gtxmhqtpvd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gttauozyei.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gttnijvvxd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtxfgmcguq.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtraqxwfsx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gteccujdvb.html


<!-- 参考信息 -->