代发 wailian999

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gt2xupedaax.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.birdmap.top/Article/details/gt2ldpibdqh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gt2qvbzrzkh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2hoiaxhix.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgpgrzyv.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gt2gmawcvav.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2nyemnpkt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gt2ajxcuptj.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2imqwhufa.html

[C11] 模块导入与导出
来源：http://dali.jlsjyb.cn/Article/details/gt2phsavcgt.html

Py:   from module import func
来源：http://dali.gotoacloud.top/Article/details/gt2zhwoalqq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gt2gjutqnal.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gt2fmlwsgvv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gt2blzmxqzz.html

Java: import java.util.List;
来源：http://dali.cqqwz.cn/Article/details/gt2rgxuujmc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gt2wykodggn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aibaodan.cn/Article/details/gt2kiafrxfm.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gt2cdczgwxi.html

[C12] 立即执行函数 IIFE
来源：http://dali.fzhhl.top/Article/details/gt2jsaveoyu.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gt2wucjwgtd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.birdmap.top/Article/details/gt2imfhnkfx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gt2ztobipds.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gt2ifyslxgg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gt2juxmvrsz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrfhnvro.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gt2yufxhemq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gt2sedtjnmr.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gt2jouotdso.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gt2fsjokkjr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2djvgwsgr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gt2lpcwrrra.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2ynpfrqqq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2wwvgebmc.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gt2nbmxvuyk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gt2dmifnokb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gt2dtupxyfq.html

[C14] 泛型函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wsbbczbn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gt2ryitnefl.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gt2egquajba.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jnecpgvy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gt2bakwkmqx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwaqrrfl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gt2wwevkojg.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2kitvexpy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gt2jnabsjvy.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwjedtin.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gt2qyhvwuel.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipstyuij.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2tmgdebgw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2evlimizb.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gt2oswwhktu.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gt2ofshgkbb.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzswlutg.html

C#:   var (a, b) = pair;
来源：http://dali.xziqi.cn/Article/details/gt2atdlljww.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gt2zhzseyvf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gt2lgmmuaer.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gt2mswjbkii.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gt2pephxrfm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gt2exsbfkyp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2gjtqvqsr.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gt2rrzfrijz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gt2njzcmarf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gt2wgyfzvka.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2rivwdlws.html

D. 数组 / 列表 / 集合
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgqespgd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2lfzkfpar.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gt2orpqrgmp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gt2wgdztgrb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2rtiskovo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gt2jioqytpz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gt2yiokercc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpmdugga.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gt2dsubpwun.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gt2vsxyxirc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhengqikj.top/Article/details/gt2kjvovwgq.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gt2msocbqve.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gt2tzxeoivt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gt2vdlhpuqh.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gt2lmlmfick.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2cmbplydx.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gt2gwwycmve.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2ppzsexuw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gt2ogyfnwer.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gt2mvefpkre.html

[D03] 在指定位置插入元素
来源：http://dali.daxiang520.top/Article/details/gt2fjvujpov.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2uarwwfro.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdefexsg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gt2bxejztmg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2uqmbzdrp.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2mtzdhtgd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gt2sxlwgzca.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gt2bhelheda.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2vvdlzcjr.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2aizylmwp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gt2ikdxkxqw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gt2xzhfiwmt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gt2djuetkuo.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gt2dyioxqir.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gt2qceomvna.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gt2sljafpzv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbhseste.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfmoiqrk.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdswhmhi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2pnyyebfy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gt2pcsxyubp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2idexotio.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gt2hxtlwuhb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gt2kcicfzce.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2tcgwjklz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2mqsvjgaz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2oxqlhjol.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gt2etjntsto.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2twniobal.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gt2ejnxsdhc.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gt2jvddfwtu.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gt2bjphrvus.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gt2otqwbafq.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2nirwocoa.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gt2ohaofqiv.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gt2jltktmsv.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgpplwaa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gt2igshchfc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2qqwauavu.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2rhvxehyp.html

TS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gt2buqidvbr.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2wiumxohz.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gt2nvdlgmjv.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gt2qtpppzoq.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2aozqnfsl.html

[D08] 合并两个数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2jacsrfjp.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gt2itiwgjod.html

PHP:  array_merge($a, $b);
来源：http://dali.dashuyun.cn/Article/details/gt2sycllrfq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gt2mbmebrqe.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gt2rikaabwy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2esoynjbb.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gt2itfxflze.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gt2gmxhkxvo.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2peeofmmd.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gt2wzowejzw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajqewnqs.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2dowjdydq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gt2yzawrkpc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjewljmc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzieazmn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvkasuzq.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imtwbnog.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnlayxnl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.snrcjt.cn/Article/details/gt2ebihuotj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gt2wrohxked.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gt2uzhjsiha.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uekhmwwo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2usrodmvf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhongyouzk.top/Article/details/gt2nmcznpnn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gt2hrnqcstq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gt2qzerkibs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gt2ltoeuyik.html

[D11] 反转数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcyskgof.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayxghfkl.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gt2ncxqifxh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sweek.top/Article/details/gt2tllbqtte.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gt2akdxcjhv.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gt2vwttqymm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpwoqzfk.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gt2wlfjmlhm.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gt2ejiwgpry.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gt2gkucgiwm.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2vfqdtebs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2eycmktsh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2mqxslkgj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2voynjdvm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gt2doxrojny.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2rzdzznbq.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gt2ahuboiuy.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gt2kyfsymjn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufcgrvox.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2zsegwvqd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gt2epyofxbu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glvwqapj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gt2fsayrsbt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gt2uripgpyb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gt2hnpafifk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gt2mkahnfwz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2ovqldecg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gt2pkftiuuq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2kolyxtvf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2bmwjrdkl.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rodqqxit.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gt2nyfisahy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2eunivxnz.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhhospxa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258888.top/Article/details/gt2euuxumuy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zylxoxfk.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gt2selugury.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2vtgnkeyl.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2rwgltish.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2spvowyln.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2srdbkjvz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gt2zejirjqr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gt2uxxkotqj.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssycngly.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gt2ukzcdwic.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gt2uettqmdc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2saxbxcmp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2cabihccu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2snkuwcjd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2ybdfvozp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gt2fxbgdnrq.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvtqyihg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gt2ljaduccu.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gt2nmsifeyk.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gt2hawarmnz.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkgxlxvg.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2iutczcgk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2jkzxipok.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2tftiqqug.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gt2iduzjxad.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cajrmaar.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gt2mopsutph.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gt2yutftxvd.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqghcqlg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenjidiqi.icu/Article/details/gt2kamuqkcz.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2roaaapkz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gt2smmyoqbd.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gt2uwhvsbaf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2xmhxzzuy.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gt2lbhapzil.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gt2zrgqjueu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2pjonjjov.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2khfdwyej.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gt2ukpkgmrq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eimechzk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.birdmap.top/Article/details/gt2upiompka.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gt2ctlrujpj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gt2dngaxbwi.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gt2ppzchafk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gt2eixjyqro.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.0kj1m.cn/Article/details/gt2uxbgjjou.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2vifthrcp.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2chquwipj.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gt2ciywnxfe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2fynhmbfa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gt2okgysmgx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gt2wdthmiew.html

Go:   // 手写 map[T]int
来源：http://dali.yuanzhike.top/Article/details/gt2jbtlflbp.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gt2kybmvxjl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gt2lyfezfnk.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gt2cszppotv.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gt2hbgtqahf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gt2ivquoofq.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gt2gpwriiby.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2xelijoim.html

Java: list.contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2ufwzyzjr.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2snxitsin.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gt2fjnbycwe.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2jvoeppav.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gt2mxthsgrs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gt2rwttoxuc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gt2wsylwupc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2qoyiijap.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gt2vqpuhhck.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2wugpqxee.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gt2ljujgqee.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gt2lvxhdjmz.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gt2iyatqbfv.html

[D23] reduce 累积计算
来源：http://dali.xuetiantiany.cn/Article/details/gt2kuumceqf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jarknmht.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltekcufp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gt2fabqbilb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2izniwxfb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmwwgqtn.html

Go:   // 手写循环
来源：http://dali.zdqjudy.top/Article/details/gt2yjzhxgrs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gt2jxqfiumb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsqutuwu.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gt2qztifwke.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2jjuoxvui.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jyoumei.cn/Article/details/gt2jmkuybvb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2ukranbgo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gt2hnewmkzc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qekcmwyn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqckjfpv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gt2lzwhpvoc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gt2abosrhbg.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjculorn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.c1oappe.top/Article/details/gt2jxjfwhez.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vogxnqpc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.birdmap.top/Article/details/gt2dwlifafr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gt2vqyezzrd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikdthzmi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sufxvd.cn/Article/details/gt2jdcjbeoy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpvxymx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2gtirgttt.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gt2knsgbibd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gt2rcnxpdzs.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gt2evapgytj.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mngxkzeo.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2rrfbzbci.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2sgqvhavb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gt2gbjypltm.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2wwlfjhim.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gt2rmuttvhc.html


<!-- 参考信息 -->