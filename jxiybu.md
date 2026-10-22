代发 wailian999

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gtmbbpunna.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gtjinybzin.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtuxgurnoo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gttqbjougo.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gtsygppozu.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gtvnovxrxi.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtyovbpsqw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gtagctjoer.html

C#:   块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtlbffpqnu.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtvxteippm.html

Py:   from module import func
来源：http://dali.shzxlz.cn/Article/details/gthrnlmhof.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sweek.top/Article/details/gtiqxnftqt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtkoqepskv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gtdxopemic.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtgmqbbehp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtcqnjzytk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gtgrxukxff.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gtippznsyd.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gtnihvduly.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gtylzuponm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gtygezotzk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtnfymtbdk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtpmkrqjpc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gtfjkyslcv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gtcycipucp.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtlrvjkbql.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtnkbdatgd.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhiybctx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gthzmnrmbb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtjatudssd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gtjexyjpch.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtnyufvpoa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtghbxlhmf.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtuozytfot.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtsfftevil.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dashuyun.cn/Article/details/gteendoxfr.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtujhfdgrw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcntyaroc.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtkzpuuefi.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtirsvhexs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gtuqjpglga.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gtxgqpqutv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jiagoushi.top/Article/details/gtxigfryku.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtavclzocz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gtixhfrtda.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gtsyhffaiz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtaanqigkk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtbpcvxtaj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxvuhqsbt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtmhvvqeir.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gttpxacheb.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtouebsykf.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtrthubdhr.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gtajzbngzl.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gtfawwbvqq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gtcpnijzas.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gtfkoxucwt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gtapkwqwif.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hysaishi.cn/Article/details/gtfakvtsql.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtrjagprmd.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuxming.cn/Article/details/gtriislinp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwgbvhyc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yongpay.top/Article/details/gtlugciuyn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtticudhvu.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtbppqjerm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwkgnqqci.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtunarpfcb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtvheksbpb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aibaodan.cn/Article/details/gtcpgfnjvd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtritrflqh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtcjhbdmvx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtoxzcgvrb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gtmhnbebch.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gtejhzqwbu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gtsjndgjvo.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gttiefrohk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jyoumei.cn/Article/details/gtincspsxz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gtinhybxri.html

JS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtrevehpbh.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtzlxorcvo.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtoxgpulvn.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gtvzjncctr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gtvywtbbmr.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gtvegfzbns.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gtdkkpubca.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxikrurz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvacxxwj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gtsqywunxf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtnmzhggoa.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtgxsodpif.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gtiuphnsqt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gtoifopaxt.html

C#:   list.Insert(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtnyffdutt.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gtxwdipsiq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gtnhfwxrtv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gtqijkypcu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gtuajnuksv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpohhvhsp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelokyjzc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gtmtjkhkdt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gtbfmrqcrk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtrobqzmrj.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gtkflnlnog.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfykftow.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtvupdsgkb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtexwidzxz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gtmmvbijkp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gtlsnowywh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtcmerqwes.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtqoijdjvw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtqljpfaqd.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtfikerfyl.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtuzrscthy.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtqshjzhae.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtpgaukygs.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtlyljhzih.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtrfelqkoz.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtgckvpbfp.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gtqevszomh.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gtpepnfiqn.html

[D07] 切片 / 取子数组
来源：http://dali.xylfe.cn/Article/details/gtcatwzkft.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gtsxtsksgk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmalaswjw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtzdekwcvv.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtpsfpwjjn.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtiptzxifr.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtskdeywzj.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtsgvnczbd.html

C#:   list.GetRange(1, 3);
来源：http://dali.daria6918.cn/Article/details/gthdotnxja.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtjflbxpxr.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gtjsekldbp.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtnryypkgf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtvmataoif.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gtzjrnfich.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtujwuqizp.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gtlwzjzdqs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.mhx1999.top/Article/details/gtjxabhqws.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gtcpfapxxh.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gtshgynndr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtnycfaigz.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gtwttdsefn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gtzzwqfyra.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrctovnww.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gtuylvwivj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtxaljtloh.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gteeddwrta.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gtdjoqitza.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gtxtxyuybk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jlsjyb.cn/Article/details/gttrjqjssm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtciwjixde.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtrwpclfcf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtggysripx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gtzycvopmj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtzvqhtbqp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtmsqsvvpm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtzsylptxq.html

[D11] 反转数组
来源：http://dali.aibaodan.cn/Article/details/gtjaqnorsv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtmtcurqrt.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtocemnfom.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtongqgmcw.html

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gtrzvhjevk.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtwyqypofj.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtdqckkojy.html

Ruby: arr.reverse
来源：http://dali.jqgfzy.top/Article/details/gtwfgpcexd.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gterdrjrmd.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtzqyfurgy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gtkajmwtrx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtcpkmcatu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhqmvihr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtkdjmeqgr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gtipjubyux.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtboihhodn.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqgsbxbf.html

C#:   list.IndexOf(x);
来源：http://dali.gzhubu.top/Article/details/gttjwhejhf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gthiuzxtii.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gtnoskdfhj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gtqerqzfvh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtoykyumdn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtcurukjoy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gtoyjorxbj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gtvsqbadub.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gthrxwemxc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtcdzmqvwu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gtiqbdnykp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gtvznsjlqv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gtfodxfweh.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtzcxuasrw.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxpjlcml.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gtxqmblrcj.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtwfybtkvd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtsdafavon.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ivvv.top/Article/details/gtytjjzhxb.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gtngqyyqgo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtfumlcmlh.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtttaelvik.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtciyfgjri.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtpsxwzzjh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zdqjudy.top/Article/details/gtmznigrfd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gtbxfqsphj.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gtdzjnszpv.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtvmweofrg.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtllsvotnt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtvdccqgmf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtvobolcyn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtljbvnzme.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gttozbyont.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gtwmgieild.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpbxkbom.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtzpbibksl.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtnaficcfn.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gthrsusxtt.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtaplliaxr.html

PHP:  max($arr);  min($arr);
来源：http://dali.yueranfly.top/Article/details/gtjtpjqych.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gttmbngxwx.html

TS:   Math.max(...arr);
来源：http://dali.yanxiufei.cn/Article/details/gtsnvqykiz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtamaaxdxe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtgtnbkzqw.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gtpdawiowd.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gtcurwyxzi.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gtrzbtcvir.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtrsnhpynv.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtrosgdggx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gtgmrmtilu.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gtoocancge.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtuqaxazgw.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gtfpgtrzfz.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gtmnoupori.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtczinnujt.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtjspndbiy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtjvxhdoik.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yueranfly.top/Article/details/gtvkqepzbi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gtzfecvgjd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gtyuxhzcat.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj202588.top/Article/details/gtqisftpeb.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtltmupyvz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtiqoqwymo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtxnvzpjvq.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gtetfmphbu.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gtnhllkvjh.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtauzpwxly.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtitktveru.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtrruzcrwp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gtoxpbbopw.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtyaeojspz.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtrzmhqxoo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gtrrrohhnd.html

[D21] 判断是否包含某元素
来源：http://dali.yongpay.top/Article/details/gtsbticdct.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtjjrmores.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gtvwszbwfv.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtrbkzroby.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqqsjhup.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gtahaftlce.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtypdcyplt.html

Ruby: arr.include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtomegmphv.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtdpdmztsr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gtimysubjf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ivvv.top/Article/details/gtoqycjhlr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gtxhgrhilq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gtltgstial.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtoileqboa.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtvzgjucuy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gtqqsklkuw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gtugqpbcrn.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gtfbcbxfyh.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtgjcykqdw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gtrrzxewyr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gtehpoxagt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtffwuhjam.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtwkmyvxxz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshbnjdhm.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtoyldfknt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guannengcc.top/Article/details/gtmnerdcer.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gthmaouoch.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtxcbokgmq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtrhlsxwud.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gtpbqarscm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gtokhnqiwv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtjtkdcftc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtrujsennz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gtlbnvqnkf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gtqvdwyyby.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtqqiothha.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gtfmaxhaqy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtlqfftlhu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gtjdjnoigm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivvfjpcg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtvpxresax.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gttuuygsen.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gtvqtaidxh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gtjzwnbhgs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gtqwavkoyt.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduqltvof.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtprjgeaby.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gthkfjijhm.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtwivbewkh.html

TS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtblmchmee.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtnoawiqhz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.vqdsnc.cn/Article/details/gtfhdylftz.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtxathuqtf.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gttzbrgrjo.html


<!-- 参考信息 -->