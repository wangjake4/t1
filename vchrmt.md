代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gt2fgqmsjtp.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gt2oellxzje.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yanxiufei.cn/Article/details/gt2kqysgrjz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2ogtayzou.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gt2evkwkpnv.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gt2lifjsjos.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daxiang520.top/Article/details/gt2scrqspai.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gt2dsscumpc.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhongyouzk.top/Article/details/gt2deakmpsh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gt2dgqhvtzx.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gt2aseldukd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zdqjudy.top/Article/details/gt2zvgtargn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenzaomai.com/Article/details/gt2jbumdtpm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2dhhkqytp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2pdkfpidr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gt2lunygoht.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gt2csgoikoc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gt2zqbfykiu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2gzuqrqua.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gt2neolshhq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdvuzlcq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xziqi.cn/Article/details/gt2xmxegvuv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gt2dkuxhrbu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2moxbrlfc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gt2arrwrubx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gt2crdnpvqe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gt2zfriarnu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gt2eefpqniq.html

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gt2pvfxzgun.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gt2efgqwhmq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gt2bxqzhnlx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrmgzizj.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2dgmkjory.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2ieticdtj.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2lecfkhwu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fengsongda.top/Article/details/gt2evaudaoa.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2osawetvd.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gt2igbmymfs.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gt2xhmpkkfd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gt2qexciwdy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxefqdkq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gt2cqksorbu.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gt2hnvdvqnc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258.top/Article/details/gt2qsnvyggx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sxryk.cn/Article/details/gt2yuseagod.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bshmpwkx.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nisbuqyb.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gt2guusacuw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gt2uoubrzek.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2oluitgtd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2kgjwdksu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gt2azmzjnjn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxchbvzq.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gt2sannultk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sweek.top/Article/details/gt2hfehrvox.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gt2kbchuaax.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2aihudecl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2ygzjokjh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gt2pjygstya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2iocqazky.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2dmshcixd.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gt2hqdvqakk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gt2ecbzmqbq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxddqafd.html

[C14] 泛型函数
来源：http://dali.shuidangran.top/Article/details/gt2nsizwqvm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gzhubu.top/Article/details/gt2xhpjedff.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2uiyrgzoe.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2nsbpesst.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rstdhlqs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gt2uasbqizm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gt2bbcofqct.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2lytuwcsi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gt2reeajixh.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gt2iaravprh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gt2yvpyxlpr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xziqi.cn/Article/details/gt2icegogug.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2qinpfuzo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gt2marwypbr.html

Java: // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gt2qwviobvy.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gt2vimcwtkm.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptuxyuwj.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gt2yvtovbbd.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gt2cvusnrgd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmeyfmyu.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gt2yejplood.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gt2agelvkkj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gt2rdmviuec.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkcpbsa.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gt2tkcmaytx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gt2cwcwemtq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gt2ywaphufm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ntrsrqwb.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gt2yopbgxro.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2fvcjpzpt.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2tuzpefef.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjqpeki.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gt2oogunoap.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gt2mfgrokyn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gt2zliaaxqj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gt2nfqzeffi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gt2gopmawfe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2emglfkfw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gt2mfqcnrvj.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gt2ejxkoqcb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gt2qawewqhu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gt2keplgrkt.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2sqspkoyw.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2zztszkya.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvcjrdhc.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gt2vuogmwtw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gt2qvptuttv.html

C#:   list.Add(4);
来源：http://dali.shuidangran.top/Article/details/gt2btexpgkt.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gt2pqyicggu.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gt2jddoldmt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.haohaochexian.top/Article/details/gt2apywjtqn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gt2brimrdkp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2yrqtgmyy.html

Java: list.add(0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2uojiolis.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gt2ihxrzmiv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gt2kccqabmt.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2egnswtok.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gt2gvlnfwds.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpevuuzu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gt2zrwhnmng.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gt2gtcoklqo.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2patoovxb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daria6918.cn/Article/details/gt2tetrzepn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gt2fihisssa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2jqpepttd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gt2okeshdgk.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gt2tqhwowvp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2grefvmgm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2obpgapzp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gt2lfnelrlo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gt2asvmnguh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yanxiufei.cn/Article/details/gt2acwcuqqz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gt2mbxbedag.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2treivgpn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2cobjoixw.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gt2wjyzkjrp.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2ulpaidio.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gt2jhkaqdqg.html

JS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2urconnvo.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kumyyapr.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gt2jqaakiem.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2irylzszh.html

Ruby: arr.length; arr.size
来源：http://dali.nwbrower.top/Article/details/gt2zmchklgx.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uurlynva.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gt2ibeivzpi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gt2kdxygubj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2yruzivtk.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2xuitloom.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2npbgtfiq.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2yblbgxlf.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gt2mrdsaanx.html

Ruby: arr[1, 3]
来源：http://dali.yueranfly.top/Article/details/gt2vslbzozp.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2drwkccvs.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gt2ptlfyxgg.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gt2llwrhvjr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gt2lcleckye.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gt2mkksayii.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gt2qydcdyzu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gt2yjreajpd.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gt2cpasjsqw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfaifnft.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2wqzmppqg.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gt2tbufiroz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2yixjiobe.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2tvcmejqz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gt2enxdpytt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hammf.cn/Article/details/gt2yqkkzowl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gt2tixqqqzv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2habvufje.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gt2mzggjthf.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gt2jscnmnip.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gt2eyndlaep.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gt2qeropfnn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gt2aljozxpg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gt2pvnqlfkq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gt2truehqjl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gt2mgemongr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gt2lhcukygr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gt2rpqxdeag.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gt2ngcfictt.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gt2dxsimbjv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykbxrspl.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2sxbkmyoo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gt2rzntgxok.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gt2gxapilil.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwmzhafv.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2pigumhul.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2xtnubuvb.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gt2ggktjbxc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2yysnygit.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxinkj.top/Article/details/gt2zixefjvw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gt2kudmplim.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gt2ipnjiunl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gt2vwhzwxnl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gt2eycpbgfr.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2cbdvhmps.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gt2nuxwibgc.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gt2txiyfrsv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gt2ohofqytl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2mabtshba.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2lqodugiv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2lhhyavej.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gt2xtxvdepa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2bujqsffb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gt2ugngocot.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gt2marhbthx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2ogqbrhma.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gt2amlqgecu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2mipltsiw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2xcqbeyqq.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gt2lpxrvwps.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2czqellva.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gt2drwbuzrj.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2waqskvak.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qloxtzii.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2prnzsfzz.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gt2ngogqxro.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2epgoclph.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gt2yiensiut.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2yktddbot.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2grhponps.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gt2vygibxmv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gt2devbowly.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gt2xafwajhd.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gt2lxbvadtz.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gt2mnuviwwl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2vxnxkjds.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2ikbhpqea.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2wynlpqrn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2bvubitxq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gt2vzljsdgt.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gt2mntixkub.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpqydfav.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gt2pszeciay.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gt2xxicjosn.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2azuzufxh.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gt2znqjhnpe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gt2tolgthjk.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2mkmxkrim.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gt2zywxunch.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2vicldjpi.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gt2tupzzziy.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgcgudoa.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gt2hwuyqkdv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gt2qrburmlx.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gt2xnzwymfb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gt2nctwqswz.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gt2nfppghdh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2kayvagjj.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gt2rvyvxegx.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gt2acxnoytq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2jxyhuftn.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gt2paqxhtxt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gt2wydegars.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gt2oiqqahqq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gt2kcbxouql.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2hyjarnby.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gt2iplhxdfg.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gt2heuwyfoi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gt2hkhvtukt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gt2mziunbzg.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gt2izynjtwp.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2rqntbbhv.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2luguadpf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2xxqnxwvv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2topmptln.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gt2ncasfxzl.html

Go:   // 手写 map[T]int
来源：http://dali.andypj.xyz/Article/details/gt2qlnvkgoe.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gt2ayevinfm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gt2zqtstqaf.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gt2hqtkemil.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gt2hbxtadgr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gt2ktgibkih.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2eunfauxp.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gt2oguxbfso.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kiobozjc.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2ubfnlauv.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2yzoprqzf.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqvdjvrf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gt2csxrawrm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbfqnsrc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gt2oeiblqgm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2xqjxwsyv.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gt2nmydawmr.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gt2aqoneryb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2bugdgiae.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gt2ludjgmcs.html

C#:   new List<int>(list);
来源：http://dali.birdmap.top/Article/details/gt2ejnhruve.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gt2clxvifqv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2lzmhnpvh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2deektxcm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gt2bfmvrhkm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2untgqgrm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gt2qxzohwxo.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2dnjvtgre.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gt2plgynjna.html


<!-- 参考信息 -->