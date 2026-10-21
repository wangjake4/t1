代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtudlqirlq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.0kj1m.cn/Article/details/gtimvrismf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtiurqkizi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gtjkbtwmwy.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtvzrurdth.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gtpcffjkcz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gtfcoghbjd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtszipsnuo.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtzvycwlmy.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtvykcamck.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtiedoatxl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yanxiufei.cn/Article/details/gtxdimcaxp.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtdaxwaeni.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gtidsmdmyp.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgsznvtj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtbmhnjikz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzptppkb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yvedp.cn/Article/details/gtvzixbupj.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtfdpqrlwj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gtrronrlyp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shangyingyoupin.top/Article/details/gtasxhcfhk.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtagdjxbxf.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzakyjxuf.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gtuohqvlua.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gtpuxrtxcc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gtricqzakm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtlyuwwuob.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gtakvtwznb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gtcepjxcih.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtftidcwmc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yangfankeji.com/Article/details/gtcrnzgqay.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gtjswsmjde.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtixhucvef.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtkpkfqpls.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gtpjzrhxtb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluhtcmfc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtxcmuuxcw.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gtngeztevy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtngeksdjt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtpjjwwcwa.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtrrvxmynm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gtrfwptslz.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtjexycbna.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gthjzadtvl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuanzhike.top/Article/details/gtjfmfqpgn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hammf.cn/Article/details/gtshgyiqug.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cheryme.top/Article/details/gtlwmmwjsv.html

Ruby: # 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtykqzrivm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gtqppntoeh.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiyduedl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtrgzzazss.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtqetioiem.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtljlhlpdq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gtntbmcrfq.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gtqehtlbbd.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtazazbisw.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gtwijwezlc.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gtfprievbk.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gterpclbbi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbrutqoo.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gthtlpsblq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtwoapfqwf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gtmczxlpam.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gtrugphljs.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gtkecjgeqk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtuhdrtson.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gtazfufttg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtsnfpcosw.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gtzzumkvsr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtoeaxrilj.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtueeywmfv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gtdquaxsln.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtzxxjoqix.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gtucwjxprv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtibwjgeup.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gtdpfdsmaq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gtwkrfzodx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtbfvhkpug.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gtecqlveky.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtqjhwyinr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtfybovhiv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gtwowelplo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtwghugfqe.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gttimsputn.html

Java: list.add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrntjbcb.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gtqyhvowae.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gtyehgrkek.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gtgvpwcbub.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvorqedz.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gtzihblwmh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yonumen.top/Article/details/gtsxcqnndq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gtxpcyhupp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gttgxfkznq.html

Java: list.add(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtmarafauv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.svipenyu.cn/Article/details/gtdojcxqyg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gttwcssptr.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtylfmgxmx.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtndxcurvb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gtrlfdqjqr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hammf.cn/Article/details/gtzkzmxqmo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtludwrbbx.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtmjznfelr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtiymmaxpc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtxogvwqsz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gtubaatvlt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gtuofvpeqz.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gthpdzruro.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtjujuuzmy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtwpkrdrwa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtaopjzyay.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.birdmap.top/Article/details/gtmixerpgi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gtwbdemlca.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtytnrormj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtnajvssrr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtkbhkilii.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtsndpnnvn.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gthabnuuag.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtuvdbdvbn.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtctzonyzw.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gttlugkgia.html

Java: list.size();
来源：http://dali.zycfv.cn/Article/details/gtvbzikrpv.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtrtypbnvu.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gtonwvuvbc.html

C#:   list.Count;
来源：http://dali.zhongyouzk.top/Article/details/gtzsacejqu.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gtpbkftyxn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gtehkjgoxp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtsbmptyug.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtcqdsnopb.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtskygjjya.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwoxlkksd.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gtltdythpu.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtvsowbegd.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtbldqslsx.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gtefgqickw.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnqzz.top/Article/details/gtljsexyfe.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gtcflcmlng.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtmjluohvg.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gtaauxfgdm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gtdkbfkwdo.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtjrzeqtib.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gtbcvdzvdx.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gthwiixiao.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gtkyntvobv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtxwyprttl.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtaofvjahf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gtigvyqihd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gtctbkxkrs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtveezjtmg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gthvhixspu.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtrtxjpfro.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gtaunrxpif.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gtrrehxzax.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtxktlrtpr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtcvydyelo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtgjubsxhe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gttmxxsxrf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jianghu66.top/Article/details/gtpccysgje.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gtkazlwlja.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gtmejfgslb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gtgppyeriq.html

[D11] 反转数组
来源：http://dali.tianlin.xyz/Article/details/gtcblosgvb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gtkrpgscra.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtbienxhmw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjcmwufe.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gtnvarapul.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gtfjxqirlq.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gttvszcjwz.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtfqfkibdk.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gtyzflhzqz.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gtiutygzfz.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gtxjqcvglz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtthglqtca.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtoqkpwtbv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtltpnkkhj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gtykowmryt.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtcujubmve.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gtobwlhihx.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gtflihtwiw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gtjkkyrwqu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuanzhike.top/Article/details/gtjessdnwc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gtaydjtcwe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtdmhfygzt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtdwvounme.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtvgmtnqnd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdxlktxf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gttrnsaqtr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtauczslrc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gtuuegqgsr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtqzpsjlkt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftnnydxp.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekryklvq.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsbohkhi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gtcabyqhvd.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtemaqycne.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gteadkqgqa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtnebillfa.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gtowehfbxs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtkquihfie.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtkwnnrcto.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtpqigkxma.html

TS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gtnrpurjxk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gtaehgwjhl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gttuvplxov.html

Ruby: arr.uniq
来源：http://dali.havefunace.top/Article/details/gtroyhqjhv.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gtgjgxglig.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtfzpbacpe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtwailvyai.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gthdhjeyrh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtuoqiydha.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtgsgugvtg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gtfgksdtkd.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtfbpgfbwk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtseycxmdu.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gtijhiubsk.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gtdaboqvpt.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtldqtjphi.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcwmmgyi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zycfv.cn/Article/details/gtpoeftnol.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gtnyuekomz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtmztfzccp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqwdqqpb.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgjxvsle.html

C#:   list.Max();  list.Min()
来源：http://dali.xylfe.cn/Article/details/gttnnqllqb.html

[D18] 扁平化嵌套数组
来源：http://dali.yvedp.cn/Article/details/gtofvcjzgk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gtkbwmucpc.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtdsybuvhi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gtlnatcjda.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gtmovlmoad.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gtczymfhny.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gtdwkoxxkc.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtalkdndwi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtmpyietve.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszpetbvp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gtanpkgdeq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtmujybpvx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gtyvecfaub.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtpwwvbhhu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtreygvtaf.html

Go:   // 手写 map[string][]T
来源：http://dali.havefunace.top/Article/details/gtlrsbhxgx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxuanxn.top/Article/details/gthzvmiepx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cqqwz.cn/Article/details/gtzkuychgs.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtdfzkrchs.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtuyohgoqw.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gtzohjgyix.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtogmnqzho.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtltpxcyso.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtrlcbbznr.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gtlgjowiuo.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gthjipdbym.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgufenzy.top/Article/details/gtjdtrnybo.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gttrodfuue.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtvqblbewf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gthfebccff.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtnboaxauh.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtqpyhresc.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gtkyohndek.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtsxtnpzzl.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljkcygwe.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtqgubdfui.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gtliklwkzt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gtmqkwlxnz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtuhbgozdl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gtyzzdxaaq.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtdrhapptn.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbtgnosu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtitquzklp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gtdkkvpiui.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gtufuxxnnw.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gtsifyrpao.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtwjfagajc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gtbqwchmjr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfyhsflr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtiwluxvxa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gttmcrskem.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gttaqycwmu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtrgealwsd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gtpsmgpqko.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtohpqjcfu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuffigfn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gtqbbfumgb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gtxmheztdg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtincpwysm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhongyouzk.top/Article/details/gtukqqzoyl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbpkdzsr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gtjhumwqje.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gthaihdwqp.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gtaajwebnw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gtxvgcsfkq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtnxdhubgx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gtouasvhtg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gtonzxrsrp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtdvlfousu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gtvbbmmeqi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gttufvdbje.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gtbowmtjks.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtcxtuvmiy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gtcpmgippv.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtwekpewsp.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtmaqczwec.html

TS:   arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtxhewirvg.html


<!-- 参考信息 -->