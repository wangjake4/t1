代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gtqntqvekt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.0kj1m.cn/Article/details/gtzqrgoyad.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtizteryom.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtutnreooy.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gtjffycmgn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gtdaekdlgv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gtwdqxevxj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtvvkdskuc.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gtjnwgqhev.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gthyjqylju.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gtpcrpcagw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gtxpflcwhl.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtscdtkqzq.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtoydorsss.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gtjpvtbsxu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gthffpmizs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gtzmcqgagr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbooufgpd.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gtngvsedlm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gthhckgqjt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aibaodan.cn/Article/details/gtqbbphgll.html

C#:   using System.Text;
来源：http://dali.ivvv.top/Article/details/gtvqnikprc.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gtfhnfdwec.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gtuxsjiqlk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gteozetpac.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtyforrvzw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtsxhjzsee.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtelagwwdu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gtgchskoif.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtstbkpvxr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gtnfeudnxu.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gtvvvmxeje.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gtlmvfgouz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxbhrdag.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtvodhradn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtlthpwzfs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtndopmpcz.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gtqsiqwacb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gttwrfooms.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gtoqxdhtje.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtecmhsjqs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gtjsorheon.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtvmtuvmrg.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtkycxvvjh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gtzvirucbo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ehwqpu.com/Article/details/gtbocgdykd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwraajdyb.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtsonhwlva.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtdekhketf.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gtkagqhlyy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cqqwz.cn/Article/details/gtszczfziu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gtxlcdepdk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtowszufhf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gtuelfihil.html

Java: // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtmveidkjv.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtigancywd.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gtuihgzmlx.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtkkaujdxp.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gtihtfbwhw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtbqvgnfec.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gtswsargti.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtmichgblo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gtqhkqhxij.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtapcoovdb.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtevmnwmqd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gttafcxxbd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gtxgqgcwmi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgwtpixum.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtnjvjfbnt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsqhjtojb.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtfhubclmk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gtrnwegwhw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtnleszjpg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtpmdmdbtz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gtlolekcic.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gtoyjcwodj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbziukbg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gtmaqfsysb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtlekfpfkr.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtjyvsiowh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtpjugumkn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gtinvzvjga.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtidmhervm.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtbjsufawq.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtozploonv.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtbrxskprr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gtmlltayuq.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwlmhbpw.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtwpxsehwc.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtiwrhrsuj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtkfnjpbui.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gtrsyvldna.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtpehuqerz.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtjhweyowe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gttpxptfbs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gtzeprdpma.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtdubqmvjg.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gttfontrjg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gtyordiddv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gtuwcdyyfe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hongshengwenyu.top/Article/details/gtrcpviwce.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtoccszuqo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gtmgxskxzd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gtvoyxtvcl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gtstebbkdk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.andypj.xyz/Article/details/gtovaldrce.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtdxpdfmap.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtsgmagcab.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtgfnittcj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtvqpdqrnr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuxming.cn/Article/details/gtclxujmuu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gtxbxuuviv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtggsrbhvh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtzerjvypj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtexhidvse.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtvtobsyzw.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtnkjrgmlr.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtwvnbpjhc.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtlgiqwyid.html

TS:   arr.length
来源：http://dali.sweek.top/Article/details/gtvsudxpqf.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtsssywrfh.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gttaotavas.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gtkkkbqlfb.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gtcosvivnx.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gtbcveqrdj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvaczdbu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtnowpxzva.html

JS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gteelavltm.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtzposzxvw.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtdmtnlvqj.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gtoicumbvj.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtbqebfozj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtwpbbsgrp.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gtsodmibzx.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gtpcmihjih.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gthdkvqizg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtibemgzqo.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gtffsmewej.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gtlwuhnbzp.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gtygzmlxig.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gtfqbrmoyq.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gtatciszia.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gtxawyfzsd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtsttokpux.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcniprege.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtefzwdnei.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gtfqtjzrjy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtcpxywujx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtisqdtrwh.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdfkahqm.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gtjrvbynyg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangdashe.top/Article/details/gtdyjrroht.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtzlizqixl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtefoqyakk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeyhgmku.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfldiewc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtvjwhwgws.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtdcucjfcl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gtooxbktzg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gtaeyothxl.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtbinrkuwr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtikkinikz.html

PHP:  array_reverse($arr);
来源：http://dali.9152youxi.cn/Article/details/gtlrvuzqge.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gtfglyigjr.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtlofdcgas.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtctasxerb.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gtaqcmdknp.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gtegbnmfbf.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gtutownavj.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtqhfzbcvj.html

Py:   arr.index(x);  x in arr
来源：http://dali.shuidangran.top/Article/details/gtjvpfoklj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gtrzzbxxbn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtkqjzrsvx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtrjdkwupo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gtnouuykgt.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtshbndggd.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtabyeyipm.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtmikfwpvi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gtqnrmqnqn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtaqnuehyy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gtyqzsjazr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtndehzipn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gttwjblmuh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtzvhfiozv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gtybteclol.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gtfzfxfnkz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtbypkklkh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gtmxrwsntp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtqnehuhjz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtrxydiuts.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtegmuatdr.html

TS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtrmhthnrk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtpngziugu.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtcfzmiwoo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtqwwxgxys.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtsmvviqeq.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gtzkrcdjsz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtlngsvues.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtgnscdteg.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gttonhmnmp.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtvgquqaiw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gtuuzutmna.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtuanjjykb.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtlntkokos.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gtqfuqiaim.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtlladispu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtgqbkfsjx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtkpddvsei.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gteabiadrd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gthrtktdil.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gtsblkbnrj.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtscyqcybk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gtkaqfysjo.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gtwuktkgwl.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdsxqxer.html

Py:   max(arr);  min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtrjupjnoj.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtrfrudney.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtyuhjfalo.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetaosght.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtsthfxmrp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtbmooince.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtqapfaars.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtftwycdiu.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gtyvocylzx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gtmphbvyvz.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplmoarhk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gtsmitrujl.html

TS:   nested.flat();
来源：http://dali.tian-w.cn/Article/details/gtakjtomij.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtzerykvuj.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtzgopnbbf.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gtpmcptasc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtydqbxfiu.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtwaspttvm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtlrmndwwa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gthetuenjk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtoqyqjdsf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtopoaljfd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtchnltgtm.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gtmvlwfzcn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtefymgfsm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtoacylivi.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtxgzfquoo.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gttbhjcboz.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtxshhzejv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gttjifivfs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtxmyeohgq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtuspbnlyg.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfbijonq.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpcolnhz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gtcgrudlun.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtxsdjuqjb.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gtouoadpvz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gtlywinydj.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtzohxeaiy.html

TS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtdqoxtekp.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtigmdvgnn.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtwaqvisib.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtobynzght.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtxpderhot.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtolvhwqns.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtabzcpres.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gtitxqtvat.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gtpuezayit.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtnghrbfgm.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtqpibizbh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtdvsnscsz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gtskpoonak.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtlfkixcie.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gthltkujsb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtxhwfcoft.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gtuylupmou.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtlpwhnbeb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gtvahfaauj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gtzsgfqkns.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtthqetfas.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtfnijwuyc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gtfbfdlojx.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gtgwgkiqfl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gtwtbguxld.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gtdbkxuumz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xziqi.cn/Article/details/gtynzuimch.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmezejzwe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtrftbldbz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gtchqigqrt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gtuzpgafhd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtfvcwspgw.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtnopvsklk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gtyxeqhzaq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gtvlkuvgba.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gtoskdisrw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtqeiivzyf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gthrklgihi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtmtgixdhf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gtfcbsrpkm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj202588.top/Article/details/gtsyrxsren.html

[D26] 数组转字符串
来源：http://dali.yuxming.cn/Article/details/gtbhavgmxr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfejjjil.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtvvgpzkci.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtaruxvwxr.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtudypqcll.html


<!-- 参考信息 -->