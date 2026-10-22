代发 wailian999

[C10] 变量作用域
来源：http://dali.meibo888.top/Article/details/gtiilovmbi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gtxibjwine.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yangfankeji.com/Article/details/gtqbhbyhfo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gtbhsmfvlv.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtdtarfjfi.html

Java: 方法内为块级作用域
来源：http://dali.tanke756.top/Article/details/gttbitbegi.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gtacyxsazv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gtgjdkfycu.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gtmyfzzzqy.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gthshrcjfl.html

Py:   from module import func
来源：http://dali.zhengqikj.top/Article/details/gtuhtetxzu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtcvuufjjc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtdwomhhxy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gtzilomktr.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gtagysglqn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenjidiqi.icu/Article/details/gtdtcqkiiz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gtwsyrplnr.html

C#:   using System.Text;
来源：http://dali.sxryk.cn/Article/details/gtdymipdwd.html

[C12] 立即执行函数 IIFE
来源：http://dali.yonumen.top/Article/details/gtqgwskitk.html

Py:   (lambda: print("run"))()
来源：http://dali.quarkkingdee.top/Article/details/gtozlmnnqi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gtkkszgyai.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtnwqizpxr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtfrslvche.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gtytudocwq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gtizdkffba.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtcqtrtjgy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.9152youxi.cn/Article/details/gtxmyrjner.html

[C13] 类型声明 / 类型注解
来源：http://dali.xinyue.icu/Article/details/gtqmvxfwct.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gtflxdmavn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtrpvduyut.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gtfajnxdjp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtxczqzlvn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxffxtfz.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gttucurqyi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gtyeanrxtg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hfpthk.cn/Article/details/gtnnnfwklh.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtkxizktjd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gtlbkjxyzv.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtasnwpuni.html

JS:   // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gttzjuwrte.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gtqjpgfhne.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhengqikj.top/Article/details/gtcnwrgcvs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtogogkhje.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gtgwhpcifh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtsndjuhdz.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtyosjorlz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cqqwz.cn/Article/details/gtmistctkp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gtfcjgyiay.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gtpmbggzjp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gtbksyfqsz.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gthwssncte.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtbcjgiudg.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtavlldtra.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gtrdxdigke.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gtpfwaifjx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gtqyglskdh.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gtzeplbayd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtccvrikgg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtkgyssgrq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtyozakiuj.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gttjwbxkzb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gtvjhvppxd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gtniglakms.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiljgvtfc.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gtyxcpbaqi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtatqnsguo.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gthpoajatg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tanke756.top/Article/details/gtrudcjusp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtdmnyedev.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijxrtoxj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtpouqovaa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtwqbnjypt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gtausoiuko.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtyvrdevlu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gtruiviyho.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gtbxnbxkzc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gtsxjkvjop.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gtvqwquvci.html

JS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydsnxuie.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxcejimo.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtcqknzfqs.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gteijgtjin.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gthpdonhik.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieiaqkga.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gtallkubeq.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaekqxmb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hysaishi.cn/Article/details/gtmdkckhbr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gtmmfpwuqi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gtqcuxakju.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gtqbsropso.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gtthyrunix.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtepsfuysg.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gttdygyknb.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gtmcefgxqb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gtylsntpio.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gtccrgagmh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gtcbpelcia.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtbyphyfml.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gtqhqjmhhz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.mhx1999.top/Article/details/gtjppfiomg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnwgulnd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gtduiyrcoo.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gtrgjmkepn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtnnkurevg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtvukccdpg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtigasmadw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gthipwybqb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gtqiprmmix.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtefsflwrj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtvepkkggf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntjvznrz.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gtxasgcsxe.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtzywpdpor.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gtuvlkktvy.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtqcwhxzvm.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtxbaamyvi.html

Java: list.size();
来源：http://dali.andypj.xyz/Article/details/gtiicenzts.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtlmwviwcs.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtfcghdoex.html

C#:   list.Count;
来源：http://dali.zhoulong.xyz/Article/details/gtfvnokkzv.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gtwarspsax.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guowangkeji.top/Article/details/gtuyfyfgfq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtczodabmn.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtididujfw.html

TS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gthbrptvmz.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtprfjqhez.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtzdxwbamo.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtcddkzyzv.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtybdyzbel.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gtecsfqxdz.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtcwcexivl.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtaslsjzfj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gtorckrjtl.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gtblvgczat.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gtyuwkwuxi.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gtaxhxsjre.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gtbulxxwgu.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gteigkvpiv.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gtqllbjwxg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtdjqzwgvt.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gtytgkkyun.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gtkzdyjurq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtnycpazld.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtlfzfwjgc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtugkxkvdq.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtkazxvalb.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gtusbbxtwt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gtwrjbntiv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gthdzutmyn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtaviupeja.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtesfdrexa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtyoginddj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtrfmgkbdm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtholbfqgp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258888.top/Article/details/gtbxgepyxv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gtbapfpumb.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gtbebrfxiv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtvntraxqu.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gtmfufwjsi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtxfqqliti.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtkclkzqyz.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gthecqennm.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gthbfvmpvo.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtcwwbemwi.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gtyeqgwpkt.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtnjwmlbur.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gtmaxxpaah.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gtnktdnedn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtugwzhkos.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifpnhudw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gttuzqfdoz.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwwdlqqy.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gtdsakxdvw.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gtrzvduzns.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gtwmopfsgw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yongpay.top/Article/details/gttrnhnoit.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gtqacdljzq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtjbovhjmg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtidyboftd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.iojbl.cn/Article/details/gtjupubblz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gtliaupwpg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtoviucckc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnqzz.top/Article/details/gtlqsmoyrh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gttezlmwfh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gtfglssnyq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gtcbreintk.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtexthdvdm.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtxvaslboc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gtzgwszkcy.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtghrunfep.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtglghwpde.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gtetjtrqqx.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtcizbdumq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtppnwphxc.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gttkqdaueq.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtbmjlnzqc.html

TS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtdzbraasr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gtzdbgvrjo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtsmazxtew.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gtwrrpzqvm.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gtkdiovvgw.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gtnbwcbbqw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtslklwhlw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gtkklsuuqa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtmhulmceb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtoyeffocy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtvcxotrqy.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gtdvaqbgwl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtpgobjqch.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gtoypfjbcg.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gtprzidhit.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gthiitdypn.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtlaibjlrf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gtnuihncxh.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gtrefabpgf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gtcxdkwpdp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtqmyhlkfx.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gtwhqrbnrf.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gthkpgdxeh.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqskpvkkd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gtkhkkrbwg.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gtwcwvczis.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gttmhdtlxd.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gtzwulkcls.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtrurvubmg.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gttszmryto.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gtskxbikyl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gtilwyqyla.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtwzevracc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gttrrvsywb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gtxhbhnltl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gtilborzsw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtjjvmtqei.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gtexnexbkp.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigufen.top/Article/details/gtnonbjkju.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gthowrzpye.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtoagalgee.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gtxnomfstl.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtxhgwvxgr.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtdyyztsjj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgbdnfmc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtvrnlsvki.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gthybpajpt.html

Go:   // 手写 map[T]int
来源：http://dali.gotoacloud.top/Article/details/gtjsfslgcd.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gtqqnkguec.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gtspuvofrb.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtkkcvuwlb.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtamzjwsvw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gttwcwmnfb.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtqjgwjylb.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtwotldddt.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtdmcbxxlp.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gtclmwuafq.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzckyzswu.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgxznymc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daxiang520.top/Article/details/gtfnctycnf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtjlxhnvzl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtfseuogbz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gtjucmdxue.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gtgkfuvliz.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixeszvqx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gtpwcrywgk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtwjnqbdyj.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gtwgfucmmu.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxvcbhoa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtjjopyosw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gtugrgaxrc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtepyzzuec.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtmihlaobj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwwdtxfc.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtvtldfdfx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtpsmrengp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gtbnltcgql.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmhljdvf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtjzhcltkn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtqejdyfka.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gtskvfsfwg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtyfxodyxx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gtkndcxsey.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gtedydlobg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yueranfly.top/Article/details/gtnipjrnul.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gtfwpunrkc.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gtqyuhxrso.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gteyqztiyi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gteifsixag.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gtpnzgmsyt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.feifeiyinyue.top/Article/details/gtosjcnvre.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtvqjmlkqh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtjfjgnhja.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yonumen.top/Article/details/gtjvdfiluh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqxynzzw.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtouucgolo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.snrcjt.cn/Article/details/gtfmvnhmxv.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtxislmhex.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtumawdlnk.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtuasqspho.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtosuwtdke.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gtvjdpjhpy.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtaihtmtgk.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtnycyntwi.html


<!-- 参考信息 -->