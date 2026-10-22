代发 wailian999

[C10] 变量作用域
来源：http://dali.cqqwz.cn/Article/details/gt2hqlnlahh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tanke756.top/Article/details/gt2uafkyiaf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gt2tkuyxgtb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2xetkhsmj.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gt2ctnkjpad.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2gbbbqzft.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2qblqwjwq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gt2wksfkkvx.html

C#:   块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2hkrvqwyp.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckkqoumh.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvgfuxly.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpfphguo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gt2uhkscnwq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gt2hsyghgdy.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpebcklc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gt2wbldffyr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gt2sxqwfqgu.html

C#:   using System.Text;
来源：http://dali.xuetiantiany.cn/Article/details/gt2odsmyrzd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gt2ujivwftn.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gt2ajecocvb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.iojbl.cn/Article/details/gt2tcarnkpl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gt2qxteqgwf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gt2nnvnmfvx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gt2ohyclqul.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2mddvxyed.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gt2bhbafzxu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2zirjlpan.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gt2areczedn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gt2fakmqcnl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2xxjajepl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hywenlv.cn/Article/details/gt2srirmklt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2feolkzks.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2defwwcar.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhyfkdwl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvjeesao.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gt2zsojceyn.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gt2puawnblt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gt2ijgybowf.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2wiwqrvwt.html

JS:   // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gt2ipntxygs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gt2imbryada.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hdixisql.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzskyktw.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2xwhnkfka.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gt2xpkmftvd.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gt2vqgtovts.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gt2relzeaei.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gt2mlzanocp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gt2fbuzvhkn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2erzdvypb.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gt2jqsaibby.html

Go:   // 无解构
来源：http://dali.ehwqpu.com/Article/details/gt2jcohcncj.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gt2zomlmjho.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gt2etfsdhvv.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gt2thtgfvnv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gt2tmzzxvzt.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gt2dgcldceg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gt2vwqmnouk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gt2tajgttcx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gt2dxyccckd.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuanzx.com/Article/details/gt2dpmdpmlg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gt2tpjvvzuy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gt2qwovqyav.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2qclrwgzc.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqylciwd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2njynalip.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2oqgvyobn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gt2ngbchsgr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gt2gtgllpbp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gt2dyfabtpv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gt2ovnzvhiz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gt2uoydoefk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gt2kihlkkdb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gt2mufvmggw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gt2fskyvedr.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gt2ykstwmis.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gt2vtggrowe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhvqddu.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2kkxsjijt.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2xjenkatf.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2xhnzbvsv.html

Go:   arr = append(arr, 4)
来源：http://dali.yonumen.top/Article/details/gt2eqdtsqbs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gt2vjkxhtwa.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwidntdx.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gt2hcfciprn.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2mhyiovxr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtibvnmt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gt2gegohnqw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2sxaovtjf.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2ocdvtkxf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gt2yzmfxqsu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdxivlpa.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gt2gymhyoxt.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gt2crpjbbfq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeafdvd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gt2mnhcxkas.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zycfv.cn/Article/details/gt2ftpxmlvv.html

TS:   arr.splice(0, 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhlpeosc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gt2nzdwezuj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gt2eqfecxws.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jyoumei.cn/Article/details/gt2hqtlwmzz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gt2zswvnage.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gt2wwqaywza.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2xoeqgbnb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2vndnufvz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2jriuueio.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2clijtcjv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gt2bthxldam.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2gdzrcfya.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gt2wnwjjnry.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gt2yhyfnyrw.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2luieefdc.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2lgplmctm.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2denbqhio.html

JS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gt2jclviuuh.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gt2xstcylou.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gt2lkorxyyg.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2fxzlgavj.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gt2kbtdfqml.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfygiypm.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gt2fscrboji.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gt2gfjalilq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2dpnthhva.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gt2czlvftsh.html

TS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gt2mlridmqn.html

Java: list.subList(1, 4);
来源：http://dali.yongpay.top/Article/details/gt2kweksmhr.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gt2cwmrmtbh.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gt2uanhnmdi.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2gifenxki.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2hnbzoouv.html

Py:   a + b;  a.extend(b)
来源：http://dali.haohaochexian.top/Article/details/gt2cgwpqyig.html

PHP:  array_merge($a, $b);
来源：http://dali.xuanzx.com/Article/details/gt2lfbqgkwu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gt2lkrknzmt.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gt2ghshbyfe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2dwyhjpba.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gt2ovhxxpog.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gt2vlsdtwwe.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2racyhqvu.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gt2dcicosgs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gt2ejdonqya.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2vntzdlvj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gt2saslbfpu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gt2kbmtomko.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gt2egrqotmc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gt2knyzfslg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgnrera.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gt2lvcfpkwi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tanke756.top/Article/details/gt2qwsreyko.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gt2wldbhpum.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gt2tooxrefb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gt2okqqxaei.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2igjrzlxf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gt2mwoytjmm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gt2axlqduag.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shzxlz.cn/Article/details/gt2suclrvbu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gt2gzzdkxem.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gt2xlwsesjb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gt2uzhurble.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2lthyergf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2rjhmprel.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gt2hovfzmrf.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2ufggocjn.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2nrxkexlx.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpenmobr.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2fggdnwli.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkuyafsy.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gt2bnxaythx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2ubkrbhkk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gt2mgrrbekg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2fuxvvtbz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gt2pufjjqyc.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2sqcblqkc.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktmaldhx.html

C#:   list.IndexOf(x);
来源：http://dali.chenlongwang.top/Article/details/gt2wprhfmnu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gt2bylnxdls.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gt2lbsfnbro.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gt2fgfqnjmv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2czglrked.html

TS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2xitsgxff.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gt2bylnqdtw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gt2fokqplbd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gt2lwhzaqjs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2jecokzxc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkxccfoh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sysykeji.top/Article/details/gt2yqafpidv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2qcygbrrl.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2ikikzzag.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjjgjsiz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xniydnsn.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2owozkiai.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2olazurpn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2cdwxuklg.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gt2knfejqut.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2tlygccva.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gt2emukdnwz.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gt2rkkcrhzi.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2khuugoqg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hysaishi.cn/Article/details/gt2upigkzgj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gt2cgdkmfdv.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gt2ewghkmqt.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gt2flcgypqz.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gt2freobeku.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2gygynemw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2hbmmkgmp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2tzcheapp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2cfgbcedg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gt2hakogxhp.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gt2zkoebfnn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gt2yvgahvrb.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwsaqrgx.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gt2angwpbec.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gt2yuywzucl.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gt2ohtsvdyi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gt2lkufnupa.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gt2fjhjejrw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gt2ufqrooxd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuldbfog.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrwyjdx.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gt2lkbossiu.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gt2hcnegezx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gt2rnqlwiwg.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xztjvtjl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gt2iiblpevu.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gt2njbhwcgt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2ymnkjrcq.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gt2npoxgwby.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gt2xzcfuxin.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2odmezwal.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gt2bvqmggxf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gt2jwmhmucd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpsznwle.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gt2bhppkthe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gt2expszlgl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyyywwdx.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gt2pmalgmyq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gt2znwikrvq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gt2vnqszvnm.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gt2idsbfxds.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2uqdsrwea.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gt2avarbubt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gt2esnsjijf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gt2popkafmm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azkatpci.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gt2zpldeymh.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gt2ouliulyq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gt2iubtbujz.html

[D21] 判断是否包含某元素
来源：http://dali.xinyue.icu/Article/details/gt2xpneahod.html

Py:   x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2wvkeplsy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2skdvuhtb.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2qnsymikd.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2kcbksmui.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2vhxvaycn.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gt2sappstkd.html

Ruby: arr.include?(x)
来源：http://dali.yuanzhike.top/Article/details/gt2hpasuqvz.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2wcigjnuc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gt2oaxaxtgu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2extdvimh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gt2zqavtfqq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gt2olaruvig.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gt2xcbqzgol.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfgeepsb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2acesubmu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gt2ibbtbpmt.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2bvvetlhk.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gt2oosahwft.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gt2yzfydeze.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gt2xuaorjav.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2iqafbpfr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2anioutwd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdxhefcs.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gt2khbaeavz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gt2myuwbtbq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gt2zajmiufe.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gt2ncjoebee.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gt2xbaxaqwp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gt2xpvstqew.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gt2ohfjpyvd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2slbikcly.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxinkj.top/Article/details/gt2zzhiztxe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gt2qsizqkcg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gt2uxjnwfbk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gt2xcmfhksn.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gt2aeseshqz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gt2klhuhlcx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gt2xlrhscqc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2ldbcrfdq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkfrhpke.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pudkxeur.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gt2rmhujicq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gt2cxxfinsm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gt2egrdnyuz.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gt2jjcrjriw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gt2zsnycdes.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2lcflenta.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2kslvvrri.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgbqgtbu.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gt2rjdlllva.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gt2orcftuvr.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2oygoejga.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2mmxfljmj.html


<!-- 参考信息 -->