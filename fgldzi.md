代发 wailian999

[C10] 变量作用域
来源：http://dali.tian-w.cn/Article/details/gt2wipqommq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gt2nhxdcpwr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuxming.cn/Article/details/gt2tsjodazm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gt2isrzvloy.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gt2gkmvzdph.html

Java: 方法内为块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2bnnojkig.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2fhglange.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gt2fwawctux.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2npgwobni.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gt2sytamtzl.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gt2pdhvnexn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gt2qaiurxoi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gt2gaufipgq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuxspiua.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gt2edaqgaia.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gt2nqvammzf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gt2uvehbtwl.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gt2ndzsexqf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gt2abgbnxmp.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gt2fdhhstvm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cqqwz.cn/Article/details/gt2szudmppi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gt2latqzomk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gt2ghmvogbt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gt2oixfkdua.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gt2eqznvdfg.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gt2yauewzcp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yongpay.top/Article/details/gt2nottytvs.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcdnzwrm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gt2zenlamdy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2sxohpdww.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqdfacyw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2eikyvxfp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2upfiudoi.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gt2wujyzjkw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsadioni.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gt2qtxfsnge.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gt2halfrtku.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sufxvd.cn/Article/details/gt2hyjscork.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igjylctd.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2fvjblyea.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gt2kurwjzgo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gt2xjvyyypf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gt2qynksqmc.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2fhanpjjs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gt2tooqecil.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ciqorzdq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gt2nhwlrsmo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gt2umrobdog.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gt2mcslyvml.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gt2qphllmca.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzlagtng.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2cresawtw.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gt2pgmozpnv.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gt2tuiurmzj.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gt2zjuhafdj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gt2bqfifjct.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gt2meubtbwo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecofghjn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gt2kwgpumuq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yongpay.top/Article/details/gt2ixjccsky.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gt2pgmmixex.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gt2ydifogck.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gt2mxrybsrl.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2pvovoaug.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gt2vznlrdvv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2rhscrjff.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gt2fnuxuwqk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gt2rktaywbb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gt2gsfublhi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gt2igfuvdsz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gt2itkxbzls.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gt2moejbkcd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gt2dzifweta.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gt2izvhurkf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gt2vovllsyu.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gt2cqcghnku.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vslqxjir.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gt2jemjtxym.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2hytpnomc.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2siiamlfj.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2emdewcje.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gt2ewgvqlkw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gt2cczpbkfr.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gt2vunqkccs.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gt2qlttopwm.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2xyhvplpl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gt2azvbanwd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhixingplan.top/Article/details/gt2zjjenlqa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2srhggtgz.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2nxmbhslh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2uzmpegwg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yangfankeji.com/Article/details/gt2orfdweut.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2pmfrvpee.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gt2zttwaale.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gt2ozolurdj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2thtiefhq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzenjgkn.html

TS:   arr.splice(0, 1);
来源：http://dali.cdnleiting.top/Article/details/gt2cgqhbhma.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gt2jaqgfvmi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gt2ownwxlsn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oyhpyxgo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gt2ayusyjhu.html

[D05] 访问与修改元素
来源：http://dali.9152youxi.cn/Article/details/gt2iuwbaufx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2aieitpfp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2wcipjvnh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2bcgrsyss.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2knrqhlom.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gywaheih.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2cqqxaigj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2fbgrrrvh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2qtjcomkb.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gt2qqinyyom.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gt2geavrpex.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2eqsbowfx.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gt2aadqcxeb.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gt2sgezqkka.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gt2wxqmgpdh.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gt2jrbsswij.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gt2ysdimxgx.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gt2ugewfndj.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gt2aspghmzt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gt2neypgbvz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gt2kospgous.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2zyhopeup.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gt2pvetjokz.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2lqojdmwk.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gt2qxojpzcc.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gt2dceqyjeg.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gt2nbmlduwy.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gt2omxmbgxa.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gt2oozvndgl.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gt2xiylgptx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daria6918.cn/Article/details/gt2imcwyylm.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gt2cjgtjeqf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2xsuwccuq.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gt2eegqpogk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gt2mbjccokx.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2gvbifvui.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gt2jwzqvehy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2rxojsfsr.html

PHP:  sort($arr);
来源：http://dali.yuxming.cn/Article/details/gt2ckeiyoay.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gt2rinefbwo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gt2eawqvzsi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gt2bfoojwky.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2mzaklhaf.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2kwgyvooi.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gt2yyijiios.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gt2ojicpigr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2rzzunebh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2idsfqkko.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gt2hhalgudu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2urhyixoa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gt2vjyvteib.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gt2poizelid.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigufen.top/Article/details/gt2rueileqm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cucudq.cn/Article/details/gt2ccsfqgca.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gt2goviulbk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gt2tfmbbjkm.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2ixgctoxk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2qnhwckkj.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gt2wtkjbuif.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gt2chivlbqc.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gt2pbuinxur.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gt2viybdowt.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gt2gfqxgxdj.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gt2gbsifluz.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gt2ysxwutvt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2hcgdjchx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2wivrtomr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2shozrndw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gt2vthtfwqk.html

Go:   slices.Index(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2hoikjhsz.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gt2xdalrkph.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gt2uuthkolg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gt2fitjczcy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atsebnus.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gt2ivshxqln.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2trvufolx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2nndmlmrg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gt2oaongudu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuxming.cn/Article/details/gt2sitcevou.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gt2akhpxsqi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gt2rpfaaddn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gt2kzvsyqzz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gt2olicrkvk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2wduxhtrd.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gt2vvvomzxx.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gt2qailiplj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2jhabyzfg.html

Go:   // 手写循环
来源：http://dali.jyoumei.cn/Article/details/gt2yndvawmr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2hxqrnbbb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ivvv.top/Article/details/gt2thqreapj.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdbomost.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2lugbikhn.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2qpxfmdvn.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2tptumpzf.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2hfmwotnt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gt2romtmorm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gt2aekpermh.html

Ruby: arr.uniq
来源：http://dali.316326.xyz/Article/details/gt2aonevagt.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2vmbpvrrj.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxamief.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2ssmfnjdl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2vgyoaaha.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2tfmugfmk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2phfxlxmu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gt2cfurvciz.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gt2krhcrwwa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gt2ekcqjnmn.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gt2jkhqdgpm.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgpjttdt.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gt2tdosnmtq.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twyuffih.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gt2hpyjixwx.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gt2lqplyubv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gt2uofaqohd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2xxmkijqf.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gt2rxntmbem.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gt2nluwtftr.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gt2sgtkqrhn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gt2cmpdbaje.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fotvnesb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gt2buvulkew.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gt2gcpkvobb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2hrlemrpl.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gt2bportotk.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gt2qofuocby.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2kckidblf.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2sussvuul.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gt2jwzodwpb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gt2bkccwuto.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gt2ozdigehi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfwqhccs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvhcfdmr.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gt2lwwfqfdb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gt2zdfxtudp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gt2qkuzatqv.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gt2emybspte.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gt2nyxiqayg.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2joctpiql.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2fcfqwdlt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2kreasqjc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gt2mbetrksu.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gt2odrrbivu.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gt2yapycuen.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gt2xlnbvxjs.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gt2eeuuvonx.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2evajkwpr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gt2vmjgbvsh.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gt2cbehdqsm.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2motuudez.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2ddxgzjmn.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2uafhbkqk.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqnchgml.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2maifamet.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gt2nloogczu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2hzdpnxtp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gt2kxhoyvwf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2ckgprzjm.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gt2qfusdfjt.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gt2ujxxfhqn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gt2adigsebv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2sctcsfyl.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2gwnjffgu.html

[D23] reduce 累积计算
来源：http://dali.yj20258.top/Article/details/gt2xeksfkyg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2hmrjxkjp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2bljmdiur.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2nxofrcbn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gt2iftcknrp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gt2gpavnzbw.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2aajdodeb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gt2thxjradi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gt2ayccgiue.html

[D24] 字典 / Map 基本操作
来源：http://dali.yonumen.top/Article/details/gt2njovtxag.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gt2klyrjnhx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtyjdaiy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2nveuzwli.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2nbcakrae.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gt2oeyqjung.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onvmqbhd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gt2ueadpbmh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gt2clcpyqvg.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gt2sigygbhl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gt2zshzffhd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gt2nuavucbj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftaglepa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gt2pvjhmvhk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2xofyruuy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gt2cgjvglza.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsbphjoz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gt2xfkvlgel.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2eymetucy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gt2qzihbbhq.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gt2zxiblzcd.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhlcglpa.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2yoirhilo.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gt2lemguopm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gt2bwxgnqpz.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2njkykssi.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2foealzxm.html


<!-- 参考信息 -->