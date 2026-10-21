代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gtipxbtldz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gtebhbpgqv.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtdnselqeu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gtxxfkqrfd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gtkjpqgkxi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtffobpgfl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtxautsrqx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxpmjkmt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gttoawlsjc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gtgooxkbkf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtobtarfhs.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkqdcglf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtmfdednfc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtnngnrexz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtlbhjwwpo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtyergyfvf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtvwtmacob.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gthuytvlbm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtstbskvdb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtfbmtvkgn.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gtmvunstiq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtrsgnoljp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtxysjiflf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gtchuluiag.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtchefcvhh.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gtvclbriij.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtidqxozaa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuanzx.com/Article/details/gtkgndtlhx.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtyljhrapx.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtmyfheaup.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gtgcrsskum.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gttufvxenn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gtnyusbxyr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gtmcshkmza.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtpltbvoyh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmocpzlw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daxiang520.top/Article/details/gtnxiawefe.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gtqtqhphyx.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gtnvdslisp.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gtbcvzdzye.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gthgtzixqb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfgfrrng.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gthpfojwfw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenjidiqi.icu/Article/details/gtofcvhjhc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258888.top/Article/details/gtyajojjbg.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtrqhrwssj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtszvrvgax.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gtbzcuavpo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gtrrbmjclx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtbbneiefz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gtqhoezsnd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtheeeqgdd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtbpxvppkl.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtvnwywhpc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gotoacloud.top/Article/details/gtaceiviod.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtrcsaopeu.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gtpkdasvha.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gaohongyu789.top/Article/details/gtsmqfpbqy.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtwmcgffjr.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtypaqxadr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtoahvzplw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gtucjokqhy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gtlodpnrxs.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtclcyrsnb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gtuomlxgiz.html

[C15] 解构 / 展开参数
来源：http://dali.guannengcc.top/Article/details/gtkuhaqhbe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtrqkbhswc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gtglsttbni.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtzkjwzmgb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gtkjhvexfj.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtpqnfityz.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuspkitf.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gtbqkgtqte.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtprslcupt.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtgkbzlndk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gtuylovhnc.html

PHP:  // 无重载
来源：http://dali.c1oappe.top/Article/details/gtupucllkb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gtwjluepew.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfyzwqgs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gtcpuiqpid.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gtlzqjviui.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gtotapbixj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gtmjiayxky.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvnvcsebw.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gttjupxbvm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkukrezvp.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtagrrfmnt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtfwydqief.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtopkfuemh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtvcaqdnzs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gtbwtcomax.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gtowwtzkww.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtbdhrgrll.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtndvdmcie.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenjidiqi.icu/Article/details/gttikzdokf.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gtjhzvjsnf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gtvfwxjhua.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gtngvcuwlg.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtvjiltoia.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtoldlibim.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtmowlxxic.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtmvxeuzfo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gtwawfnwih.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtvxqgbrsg.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtyrprbcxm.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtsfliducm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigfzy.top/Article/details/gtopivmznz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gtitddgbqc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtylaybgpr.html

Java: list.add(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwexxdwgm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gteivhlhng.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtfahhdjdf.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtopgymqdx.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtpzxelbyp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gtbxcohojn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gtxmfdgeem.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesoggarq.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gthxibalwg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtocikcrcz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gtzhhmrfca.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gtiswowncx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gtaurobndf.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gtidnbvnix.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtvqjoaovs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtgvogjmqe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtjungdulb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtnplkrqxc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gtzgkzqthn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtvzttqndw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtagznlpbs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtvxaevyxv.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtjgsdptjz.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtrtsvczhx.html

PHP:  count($arr);
来源：http://dali.nwbrower.top/Article/details/gtxxtlaobq.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtkfjytunb.html

TS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtaxtdsxaf.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gtaumpfzcl.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtruojmcrq.html

Ruby: arr.length; arr.size
来源：http://dali.birdmap.top/Article/details/gtsjcutalq.html

C#:   list.Count;
来源：http://dali.cucudq.cn/Article/details/gtkupbaiqx.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gtzuxeplrg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gtmjzgrvaw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtjglfyfnq.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtrlcwocms.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtvpgxwreu.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtpackamxc.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtqpevucly.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtmyqcckth.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtreadndkb.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtmerhxkfk.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gtyxljhwua.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gtdcilodjx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gtpurjvuoc.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gtfzkncaqy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gthvrnotcm.html

Go:   append(a, b...)
来源：http://dali.dianchejie.cn/Article/details/gtzryxbgxt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yongpay.top/Article/details/gtnemqvxar.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gtlkanfmxk.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtcsnqruit.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtpgpgmtmq.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtnbtvchqw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gtwdafvecf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj202588.top/Article/details/gtljqvnock.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gtcjirejmn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtmtcvqobt.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtoseneitx.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtnbisjjqu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gtozouamtk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gtbyqszqhc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtbbacyser.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtsldpoznr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtokmftahg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gtbohbpqip.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gttabmowec.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aibaodan.cn/Article/details/gtueslfxrn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtjrocybkl.html

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gtxeavlwti.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gtvhcoazgk.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gtziwoczud.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gtovdmimeh.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtizancrll.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gtlyyyejkw.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gtzfesjxnp.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtlszbsknp.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtrwfzlkjc.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtjqbkqbuq.html

Py:   arr.index(x);  x in arr
来源：http://dali.hfpthk.cn/Article/details/gtfvjoohky.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtywtuvnek.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtcosqxggg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtzneminln.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gtlzpdukhb.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtduweyftt.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtdtimglxo.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gtaiqfekux.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gtxwzfsgyv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ehwqpu.com/Article/details/gtlztbjico.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gtfpvynhyo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxdpmkkf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtlgxtopvf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gtggcjbzsq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtuynmivyc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtiorqsocy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtptvefttl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gtrgxdfkyi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gttrrpnnrf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtrmcxwhwi.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtooxdkdtj.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtmsozftiv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gthkgcqxdc.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gttlyeoqky.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtnjjrlqqv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtzqsqimtj.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztoxlvpg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtxvdmriuo.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtajwdjvka.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtrulqhoac.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtnjonukme.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtpzuimlmx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gtxfyxykik.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gtprztqhxl.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gtrtviujsc.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gtvxaaquxr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtrtiznfuf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtbyrgejll.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtrxppflwl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtybnygbrp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtbamtcwnj.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gtbhqfdlcf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gtyjcidrcm.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gtdwkfbgrt.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtqtdfssgs.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gtginwwwzf.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gtafukrfpf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtvcdffsrg.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gtanzdmcoa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gtilokrjat.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtbyjxjnsa.html

Ruby: arr.max;  arr.min
来源：http://dali.gaohongyu789.top/Article/details/gtnwlbjsew.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gtwwetjqek.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gtdyambmam.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gtxxfqmnak.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gtgagyyhpa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvpgbfsy.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gttfzhpkri.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shuidangran.top/Article/details/gtduvsyxvy.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwyuckqy.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtnuampwxw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sxryk.cn/Article/details/gtvwnwirll.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gtrkxygouq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gtilyxmjqm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gttwsfmkpe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gtwztunsks.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtjlwzojjx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtvbvunbnf.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gtundnjsqv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gtolojyyhj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gtfyazudaw.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtzsopggfe.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtzkipyoyy.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gteztznmlk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtesnlzsqg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gttlrccguy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xziqi.cn/Article/details/gtgzgdyrlc.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtwhxooged.html

Ruby: arr.tally
来源：http://dali.xinyue.icu/Article/details/gtbcujehxk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzrdixra.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtsrbkostp.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtepapvqkv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gtihwgwfbh.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtvmicqfad.html

TS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtqjuylnpk.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gthzicwhvw.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtqigzggfi.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtwrbwugdq.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtwjubmyav.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gtyfdmetjd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gtvkkwvxep.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gthjqqldcj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gtjzcrvueb.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtrosjugzb.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gtfqyflnjd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnalkgiqn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtpceohejb.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkpxwlak.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gttpzpnvbc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtommbkxtz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gttjgxgbck.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtsjcvzyxu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtwyautpyc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gtshqddsjr.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaczwzms.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtdssnwyvs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gtjojtnqde.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gtgaznbwja.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtoigxykjm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gtjdvgbrzb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtvkbdanez.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gthspopoia.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gtdgoiauwe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gtpyjgzybx.html


<!-- 参考信息 -->