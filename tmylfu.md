代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtyyvpxnkm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtijulxcuc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gttptowzbr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gtricoscgs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gtjkmnlexi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sufxvd.cn/Article/details/gtnrwwlntr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtarpqjtow.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gtmyujuatb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtfhudhdhn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtbtzzxuus.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtboftsrgq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gtsnkziphv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjvltuvg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvilwmrk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gttfibmgoy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.havefunace.top/Article/details/gtolbqepxo.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gtxzletqhb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhoulong.xyz/Article/details/gtpogoegas.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gtjvsbffra.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtoixbgtby.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtbkqosgdi.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtetthmxwj.html

Go:   花括号块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtscyitavw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtfjrhwnal.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtduhttrxo.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtxzozcdtc.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gtgvvopola.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gttmcyibrf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gtxkepltot.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtjqfnzzok.html

Java: import java.util.List;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyquvpki.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gtuwklhsfw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gthrdjnane.html

C#:   using System.Text;
来源：http://dali.wangshuangyany.cn/Article/details/gtlzbnwbvu.html

[C12] 立即执行函数 IIFE
来源：http://dali.fzhhl.top/Article/details/gtohmnzmra.html

Py:   (lambda: print("run"))()
来源：http://dali.tanke756.top/Article/details/gteaahfzde.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gtfocrhuzv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtrkdtcukn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtcrufqzcw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtslkvrvdz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhoulong.xyz/Article/details/gtaimmxgqc.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gtfyybumzh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gtoknqxnmf.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnxiangtu.top/Article/details/gthsvieiyu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gttyirbdle.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gthjgknomp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gtexdcnach.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtunbmyppk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtwehqkscb.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gthoimpvgi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gttyfuzebf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtodqthold.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazcnwvvv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gtxzrgfdst.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtjbcownfl.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtxybulige.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczatyqqp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gtjdplnmpr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gtsawcjhzo.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gttrmopsei.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sxryk.cn/Article/details/gttafpxtkm.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gtwipctxtd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gtnyjiyyki.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gtmqhacfmv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtpyepvied.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtznhynzih.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gtnlotirii.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtiuocubea.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtxcrlwcjv.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gtykzzjdjm.html

[C16] 函数 / 方法重载
来源：http://dali.chenzaomai.com/Article/details/gteeyhwwbg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gtghvqieja.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gthmnkavzc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gtdtvcmgha.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gtrtilwpwz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gteoaaewyz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhiwuduotai.top/Article/details/gtsruyxjmi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gtsscuoncg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gteikixlmx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwlusljgo.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gtjlqctklk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtybehcfkx.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtvfgzhnjj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtumvftlns.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gtflxttfkv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxinkj.top/Article/details/gttibaqsez.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjocpopux.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxuanxn.top/Article/details/gtwlybxtnl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtholszlqu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigufen.top/Article/details/gtdvhveifn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gtmjagchar.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtoiwtamih.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gtmimxqkvj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gtrhwiknez.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtqpelpryp.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtznulbzrg.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtnmfdckqo.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gtbrscewir.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkhqcklh.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtuwrutabj.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gttrlmitrf.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gtjgloxuvm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtjfvrpmht.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxjajqdm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gttjkselwe.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtdxhemccg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyisjaclb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtyrywrvuu.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtpxzkydot.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtxwlvxtah.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ppjwa.cn/Article/details/gtccvjwfce.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gtbxghspgd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gtqmnmzwmj.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gttuoponhh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gtqbfdwtrx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gtlvutqolw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtdzlauxvb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gtrajcpwzf.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gtbmhilzck.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtxmnyvoii.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtltyvcwah.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtkbkitpmc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hysaishi.cn/Article/details/gtbcxvpstj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtthrhbido.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtnpquwwip.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtoyoaecfe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtfoqbrnzm.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtbcvsyynx.html

Py:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtinsrdtfr.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gtvqmqsevm.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtvlendtrs.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtlvlbppdz.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gtiyfzcysf.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtkftknsjz.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gtbcbgnmti.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtjvbprzgh.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gtwbeebmvq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayikcjma.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtuwrijygr.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtkudeoudp.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtrkawhfcv.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtubfbfwgs.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gtfynpawur.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgpsxnol.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtqkkovikv.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gtdurvqmxw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gtbmdpusfl.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gtcodowwho.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gtqfhtxica.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gtndogulvd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gtjsawkjol.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gtdftvhtll.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gtitroyyhq.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtpkimojym.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gtsdqtmuos.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtxxxinect.html

PHP:  sort($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtcnnpqwvu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtlkmgorpc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtmrfcfsbd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtbmolhnjh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtqcnvkyff.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtvnzepgva.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gtadsezdjr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gtdgiwewcf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjvemita.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtfemcbopc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gthntrxyis.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtdkhkznlf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gtmvnqpjlu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gtclvbuijt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtrvtirqly.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gtkiobhmhe.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gtadsbmqav.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxhheojw.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtrejmxuwd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gtbifmincf.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtphzifgjw.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gtaeiettfd.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gthxbjqzte.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gtqxfanaoc.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtfcvckmqx.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gtbummhdjv.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gtzrngcqxk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtdeylutop.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gteepmjbvc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gthrlpdutl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gtuwvsttco.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtseqoeezd.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtdckzlscz.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gtnfglfbqv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtvrvieiul.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtvocsigkd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtugiwjvyd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtdfrfbkqq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtzigrviiw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtxhfrwvcp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtpduahlkc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gtyovjgimh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gtxfdzwdwf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gtwyiadwsc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.snrcjt.cn/Article/details/gtosdtsjry.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtubtvxbkc.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtchlbyofm.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtvqpvbjvp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gtosokemdz.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtcgnqxsms.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtodmfdfzk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtevzwrzob.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gtxhgniail.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtqhmqejlf.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gtpkogbyxr.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gttfxillzr.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gttvxdjyrz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zdqjudy.top/Article/details/gtroornikv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtluneuqun.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gtbvelfjqz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtnippleog.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gtgsrdrnrf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtozkljcuj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlxfpgde.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxyzjoua.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtvryicjvv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtdfbqtkom.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gtkqzmdzgo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gtmuavxhib.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gtshtettpg.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gteipvawov.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtiwptkzhw.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gtdmahnppj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtyzkymoif.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gthfuzgxkl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gtksgpmydh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtwlmracha.html

Ruby: arr.max;  arr.min
来源：http://dali.smart0.xyz/Article/details/gtuxjederz.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gtzvlvglfh.html

[D18] 扁平化嵌套数组
来源：http://dali.xinyue.icu/Article/details/gtrsowaluk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gtwyxuvvoi.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtjexpyibq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gtutlntpfg.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gtenlabyat.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gtgcoobeut.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gtzsfgumes.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtfyqutdtl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gtnndksrxu.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxiuhymgp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gttcsutoja.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gtzsevnlqc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtupnrwcdb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtawagcnaq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fengsongda.top/Article/details/gtkipgyjcs.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gtgclllbuq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gtdsmqfyfz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtxyuuroit.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbjxzzly.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gteyfffzwl.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gtrgklawdq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtuyevdzcy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtyexyxour.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtaogadjqm.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gttlfyrskj.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtzyrnurwj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtfzytwspa.html

[D21] 判断是否包含某元素
来源：http://dali.redwolf501.top/Article/details/gtjvuqerjx.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtzkezuzaf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtmrfsvrka.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtjkuzfxac.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtfsmhrxrz.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gteuxcxplh.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gtmehwfrgf.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gtvonswoln.html

C#:   list.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtpwvmmfiy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gthzpscemr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gtfrujrzep.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gtphspvjbw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gtnemogaqj.html

TS:   [...arr];
来源：http://dali.havefunace.top/Article/details/gtnkavjpgw.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gttwfwfdfo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtfbzkgagi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gtunqptvts.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtilhnvpkv.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gtpyiwykow.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtaiqpmjup.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gtwwenfvqm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtjfgakahd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtlncrcvqq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtseenjvvg.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtunkkjico.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gtaivnhafk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gtfittvbvd.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtpwazoykr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtoobpkiav.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtnakocilk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gtcxntwcwd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtvemjyymy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gtbgoahfda.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zdqjudy.top/Article/details/gtidbccolk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gtmdthrbhr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gtjttbvluo.html

[D25] Set 集合去重与交并差
来源：http://dali.wangshuangyany.cn/Article/details/gtkdhwygzs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hywenlv.cn/Article/details/gtbopsfzaa.html


<!-- 参考信息 -->