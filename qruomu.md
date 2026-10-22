代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtqkzjojow.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gtrdgbfsfr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gtborbqaoz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtmafhgmgh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gttmmwbwjf.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gtuvfrdvcc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtnrpfwqob.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gtmkkumuvm.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gthojxdupu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258.top/Article/details/gtizwumwxn.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gtyucopftt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gtryghrlpw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gthsopxtdd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtjgfycwjt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtltybmpag.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gaohongyu789.top/Article/details/gtcjmuuftd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gtldwuulfg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hongshengwenyu.top/Article/details/gtynvmjqmy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgmxmgsjj.html

[C09] 递归
来源：http://dali.hfpthk.cn/Article/details/gtudvbdqvo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtualrpzdc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtulwjgdog.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtmxpbgkjp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtujcpkmdy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtqmjdbsye.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gtvzqmizvk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtmjkyyzxs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daxiang520.top/Article/details/gtnkqhbuyz.html

[C10] 变量作用域
来源：http://dali.yangfankeji.com/Article/details/gtogvqbvwg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtdiynehoh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gtbbmyzfap.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aibaodan.cn/Article/details/gtqirvlclq.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtqeqrdwpq.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gtsfyxbdzi.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gtpyrxnzfy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ppjwa.cn/Article/details/gtsyisjhks.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtiivanipi.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gtetsriopn.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtqxfsxetf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtrzdtafkl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtqomjqxoj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtsyliubmi.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrmkrfsl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ybcxt.top/Article/details/gtppilyapm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gtcxzshocy.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gtaqusvkvr.html

[C12] 立即执行函数 IIFE
来源：http://dali.hfpthk.cn/Article/details/gtpaogqatm.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gtzmpxesdm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtanjusrgs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtkfvewczn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxizzbcgr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdfunhdj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqsndbns.html

Ruby: -> { puts "run" }.call
来源：http://dali.iojbl.cn/Article/details/gthesxcnnp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gtllyrqbur.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gtvtnzhltz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gtrmcbhxhr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjdproua.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtpuvjjutp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtjkpceifd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtlbtifcqk.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gtiebztkbr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gtoiynkirh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gtvogmmwty.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gtetyrvkbv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hongshengwenyu.top/Article/details/gtnmilapey.html

PHP:  // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtnatogwfr.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtfbvwyrrl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gtxpogztsn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gtzldnrqjk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gtmhnyqmet.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtuhozqalf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gtwozqaxwu.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gthygfsrwm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtiueulbdj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gtodvdiinm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtakjwxtgx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuuzinwys.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtodiphvwc.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtcvjtlszl.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtohbedbpc.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gtbyqytezu.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gthluszeng.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtnhuekrzh.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gtrfwksrdy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtphpprnjp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gtdzbghruw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtmcwmhfcq.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gtlatuluwq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gtnfidmblq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtxnyicojy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkuxrozro.html

D. 数组 / 列表 / 集合
来源：http://dali.xuanzx.com/Article/details/gtbahymznh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbtkksiww.html

[D01] 创建数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtnksormva.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtxvmakqac.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gtuqwrhxny.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gthjzcuuha.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gtgvpqsgbj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gtxutwnxxj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.0kj1m.cn/Article/details/gtqneirshr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gthzqzukeu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtshgynisc.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gtyldihzii.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gtwglhbvgq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gtvetjqubx.html

JS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtqvalwzzi.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtbykimfhp.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gtssvtotra.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtvtjrhigl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gtvbixwthz.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gtspmxidnr.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtxfdcbdlu.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtayruofdg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gtfmarkwkc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtfibczgzd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckmhqrna.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtxynzmjpz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gtcefrxldl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gtjeehuoom.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtggefcirb.html

[D04] 删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtcwvaqxhg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gtscoytmlm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtaxugtfjr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtwoamtjko.html

TS:   arr.splice(0, 1);
来源：http://dali.haohaochexian.top/Article/details/gtxfcbmaka.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gtezwxdvxv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gttegcejzj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtprtrzygw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gttfbbadbq.html

[D05] 访问与修改元素
来源：http://dali.vqdsnc.cn/Article/details/gtgpdjuefh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtbkitogvn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtsbppznsc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtbpvslrgb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtrlvkdnhq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gtjfuxdzff.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtuzuftvkr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtlhacbegu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtmblkebns.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gtdtagupew.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtjrrpravy.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtdigzpgsy.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtaghfkgws.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtkmxxezeh.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gturapmpms.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtyvfsbjnd.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtmnzfodpq.html

C#:   list.Count;
来源：http://dali.xylfe.cn/Article/details/gtfgywladw.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gtjwxipciq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgfzy.top/Article/details/gttfbujmjb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtuvhetten.html

JS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtsylskupb.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtzibyyadm.html

Java: list.subList(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtcdkdtxmw.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gtutowggcf.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gtrwdzbjhh.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gtwkveejaz.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gthfltmwmy.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gtrqhncmom.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtjpzzxrwc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtfcifmthp.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gtgeljhizf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gtzpxqdoiu.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebzpnnai.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gtwisdhkvd.html

C#:   a.Concat(b).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykqaheiu.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gtlkmfrstk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtgknmzdif.html

PHP:  sort($arr);
来源：http://dali.svipenyu.cn/Article/details/gtkxrwezvf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gtdurotyyx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gtsksymvgc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gtswwdutne.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtclmethtk.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtilgtivbv.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gtxlgudxtk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gtakicfbfr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtehwhljhl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtruwqfxus.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtofajjzca.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtvdnqmeov.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gaohongyu789.top/Article/details/gtzuvdxkqw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtwbbjygxj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gtbftwriwz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqktibtml.html

[D11] 反转数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgyjayit.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gtviomnroi.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtjjpuctbw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtvmmzgrqj.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtuofqvojr.html

Java: Collections.reverse(list);
来源：http://dali.shzxlz.cn/Article/details/gtjmxmadtl.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxinkj.top/Article/details/gtniuxkfyb.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gtdezudmqw.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gtvknrsvkw.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwnzsfkr.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtkaqzxfdp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gthbzgoyrb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtsdkfxtxc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtwurdudqv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gtmlfwlfbf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtcmtqfubi.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhsxxwwt.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gtkjostslr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthogsrzck.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtouglssfg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtyzdmpqmb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtjqxrvnrz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtcsvlhuhr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gtnkzmoryg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gtwwflsgba.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtxlvefdda.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtgdwzzxoa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gtrzjugtpi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gtdrucqbki.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gteuzlmmid.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtqspeydyt.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtzvfaauol.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gtjqtwhyrc.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtmonsdsdo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gthfomqpnc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gttulefbjk.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtxqokkyif.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtbpmunsxn.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gtomuxnfmf.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtzfppmrom.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtxjycexqn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtehzlcoeb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gtazlbrbrz.html

Ruby: arr.uniq
来源：http://dali.dashuyun.cn/Article/details/gtkaakwoyd.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkrpilfe.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gtondnkmzj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtgqamqsqw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtuzpcfizv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtnkekwdai.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtrnvnncdd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gtkbedbsof.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gtsidoqiuu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gtfbsdnvbu.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtbtlfeeqo.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gtxtqcxtji.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtetrgmwbx.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gteoqrulho.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gtijxgjoub.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gtuqtxxrpb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtpjsgtwtq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtcuwxscsp.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gtulpdilxu.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gtnamcnqkl.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gtgmsaqrst.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gtixhseuxv.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gtplyxtrur.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aizwys.cn/Article/details/gtdhkqxggh.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtcpuafgqm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gtmlgsbysv.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gtfemevsad.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gtktrogrln.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtyycchomg.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtotrhttme.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtxudhjrqh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtrmldweaz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtrsnezcqh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtvqwdiufs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fengsongda.top/Article/details/gtpxfdbfde.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtmufzwffa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtuoeltale.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gtuarsimnj.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtebhmubek.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtwgiyrhgn.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtpmaodbwu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtnnrwddwm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtnuckblnl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cucudq.cn/Article/details/gtvnerdrot.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtilhetedq.html

Ruby: arr.tally
来源：http://dali.jqgfzy.top/Article/details/gtfaettzog.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnqzz.top/Article/details/gtftezjbtl.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gtfgjwokrj.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtcbmnzgbq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gtfisrolww.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtnwrxdsmo.html

TS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtaqlrjjrf.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gttpxcuuke.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtyfufxeyk.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtgoffpmzs.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvefibjk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gttbstlwsw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtcfacfuuq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gtlkmpluxb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gttrpsbzoh.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gthfdisohi.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gtpbzkogcr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gtrijgzefu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gtrjbmsrxy.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gtbeewusaz.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gturcodfzf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkawrmtic.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aibaodan.cn/Article/details/gtmxzlmzuz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtivhilaue.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtmgtjnqxs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gtredkttjf.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtujmzdjxd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gtlkskegvs.html


<!-- 参考信息 -->