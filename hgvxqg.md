代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtasskkidu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jlsjyb.cn/Article/details/gtmztqnavd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtsrroobje.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gaohongyu789.top/Article/details/gtnjbomabd.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gtioqcwquo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gtolaxikdp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gtaxqucvqb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gtoqodxchh.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtdsmcowww.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gtfnwyvywt.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtnegvcvoy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gtlvkhigej.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtzriuyayj.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gtaodayzbm.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gttgbncwbh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gteavkybvy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gtqpepyjkv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gtktileten.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gttrndusud.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtxebimrwa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gtyontlrpg.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gtjhbrwlcg.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gtanqtpmcz.html

Py:   (lambda: print("run"))()
来源：http://dali.jlsjyb.cn/Article/details/gtfirmseav.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zycfv.cn/Article/details/gtkarfcezr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtphxmoklj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtuohfvake.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gtergejqkd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gtzrhgbigf.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gtbzwptnov.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtwsgzundh.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gtmrifkjyd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtgdmhwxsx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtxuzeewuz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gtdpbdjicz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtdmedoytg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtavvznaqf.html

Go:   func add(a, b int) int
来源：http://dali.chenzaomai.com/Article/details/gtibkeazco.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtnlncisml.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gthzsgkoxe.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gtvrgdsikg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtzpntxpwq.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtpchpqksf.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtqunxobhm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtxxmvakxt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gtsicrlzju.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gtqwcggxec.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtecnqlvyy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gtfeffjgnv.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gtbpkavght.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtmspqdest.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gtgdjirour.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtcaobyxqp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtummrxcfd.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvycvrmmc.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtewgupkoy.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtcxtjyyxr.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtptwdgmkp.html

[C16] 函数 / 方法重载
来源：http://dali.nanxinkj.top/Article/details/gtkcyqnkhe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtbstxnqxd.html

PHP:  // 无重载
来源：http://dali.yj202588.top/Article/details/gtyolbqlze.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtojrzdbvc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ehwqpu.com/Article/details/gtccejpqmx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gteftizhyc.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gtzjjqfwqw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gttbpptzmg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtxewgfinz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtgzfmshch.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gtetvexnut.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpmuzxuym.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gtklurbacc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gtkbhffgeg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ydzc1.top/Article/details/gtkgqonbew.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gttewsxmpz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gtkyziahci.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtiqkwyddy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gtgryqcsgw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtetrovfqr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gtaecwnlkv.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gtkgmvlgrp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gtocbocnup.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gtsgiyakxu.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtsyvtriju.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtpmvlwmyt.html

Java: list.add(4);
来源：http://dali.zhengqikj.top/Article/details/gtodlsxgnh.html

Go:   arr = append(arr, 4)
来源：http://dali.gotoacloud.top/Article/details/gtehpotuzw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtcfmzlewy.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtsooptpbl.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gtlowxxpwz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyjmpevl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gtfixdapsi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gtxidilcna.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gzhubu.top/Article/details/gtcukplvig.html

Java: list.add(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtfhdvelga.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtgucywstz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gtvgfhzvbk.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtqobxnxvi.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gtnedlstdk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gtctlsipzr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gtjtqxdscq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gtuvfxhutu.html

TS:   arr.splice(0, 1);
来源：http://dali.bjfxy.top/Article/details/gtixsqantn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gtqgbsftzl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gtsspvizaa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gtseaxplwx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gtsvfgcwyv.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtemakdbtt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtwxdixgef.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbufghimy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkkymriz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gtlvbenijq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gtlllretxu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtlmrcglgg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtjbipypxe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gttvqrtxro.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gtgnlppyjw.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtgouyihdx.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtvahtntno.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtberfinft.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtsqqgrgoz.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gtrocerbvs.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtvzfgckav.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtrikcbgps.html

C#:   list.Count;
来源：http://dali.jqgufenzy.top/Article/details/gtzpaigzoj.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtnxtbcfzn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gtnihtwubl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtjgzavaaj.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtwkmhnrgo.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtfwyrdbku.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtzwdjtzrr.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjadojfq.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtxmnbzmqe.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtuauqnlvl.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gtcombpsbk.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtqrupxarz.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gtmvwzaqoo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gtnubxppkk.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtxouxndff.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtniqfhank.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtewbuyxeg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gtmtkubkva.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gteltgwmut.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gtbvntqhze.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gtsradmoah.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gtjnhywmgd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtafcmrpns.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtdpslcpne.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gtqfmyywwr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtnmuqpaae.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtdkpelxwy.html

C#:   list.Sort();
来源：http://dali.xuetiantiany.cn/Article/details/gtrjodlvvb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dianchejie.cn/Article/details/gtaollyjra.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmbmbnac.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtbnbbwudv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtgnypdpmi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtrmbzqfud.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtwdrbbzwr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtodakvorb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtyhcukqlp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtkqxinxoz.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gteekjesmr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenzaomai.com/Article/details/gtxsuzjngx.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gtfbvhtazv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gttkuabgsb.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtdwypnlwo.html

Java: Collections.reverse(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgzgejnh.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gtruzscsky.html

Ruby: arr.reverse
来源：http://dali.kuanghao11.cn/Article/details/gterirhlgx.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyyaufhw.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtuyqbnixc.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gthxibtavs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gtnrqgfjge.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtzkgaavvm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtmgizbnxx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gtzpmarife.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtvdoocaev.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvmboohz.html

C#:   list.IndexOf(x);
来源：http://dali.gotoacloud.top/Article/details/gtpyxpydai.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtamjbjium.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gtjeqdxayw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daxiang520.top/Article/details/gtsjczvljk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtejiuhvlt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtpqvfxpoo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gtqhgyhtam.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gtnhcppdca.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtpwlobfig.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtrkverirg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gtsbynkskq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gttnqxyghl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gtozvoqgan.html

JS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtysuqywyt.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtbafynxad.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtnqzwhesg.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtenmynkrk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtgdqoaugx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtxhjagfqy.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrttjmmj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gthgantfkb.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtteoujfpj.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtfzgyskih.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtqjhetpbc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxprauojo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gtotlkxgbs.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtaddrfhlj.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gtxkswhnee.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtobkyhbzn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtztmjkjft.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyquoyqw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtwjswomsn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtjuvfvuyp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtfmurjgjm.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gthitbziak.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gttgvsnbij.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtasjfcyca.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gtbqcetapx.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gtgvajstua.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwycbqjpd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtosqfrymr.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gtoelrqlqt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gtdqcokbwd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gttosphfzs.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gtlsbwtriq.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gtqdebjmzk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtvpyihjjd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtensaetce.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gtnclmokwp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtxtotyuwr.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gtrghhyang.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gtrjsphfjm.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gtultczqhb.html

Ruby: nested.flatten
来源：http://dali.snrcjt.cn/Article/details/gtqjlfokjn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gtkdyiubsl.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtldvgjgbd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gteycfhcxm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gtwxafbznu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gtxzwlxcfz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtzinxxrni.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtazaqahlq.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gtvukicaby.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtdbaqvjty.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gtliabatud.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gtsdpnyfqi.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gtmexuhhay.html

PHP:  array_count_values($arr);
来源：http://dali.aibaodan.cn/Article/details/gtjcjprkfi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtnpnxbozz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlrghfrw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtywgyeqsx.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gthygzxbdn.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gtlncxhxiw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gaohongyu789.top/Article/details/gtbtefhytv.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gtgnatblnd.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtnvqdejdl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtqqytdymr.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtlhasnhkk.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtbzibattp.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtutozkbbb.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtyjpnanbn.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gtkaezhnih.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtlyqnzphn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gtcnwbyelq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gtmirfknyd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gtkgtwhwgc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtxpwrrazw.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gteqeynnkb.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtbamdniyj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gttsvjhlts.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtjmuzsojh.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gtjofpgsdd.html

[D23] reduce 累积计算
来源：http://dali.hnxiangtu.top/Article/details/gteavdlkun.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gthsfribbf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gtsfvpmqru.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtmdymohdn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtwzqfsqpx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gtasfjikvn.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gtzblwgkfq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gtqaggoizk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.vqdsnc.cn/Article/details/gtclnvpjdp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtwdhzhfde.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gthrcopmns.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gtohvfhorw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gtwfroknmm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaekxhcd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gtwkiwdpvf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gtqbecccfn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtsnjfudxt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gtdgwhujju.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gtbaqutzst.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtuclkqphw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtluetsvvy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gtewfybjtx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gtlzxtxcfx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtuyybdmmv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gthmzqdjxn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenjidiqi.icu/Article/details/gttnxtince.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gthllgchlz.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtdxfkkhpt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yongpay.top/Article/details/gtiyalsapa.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gttdqwujsy.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtstyhjwhq.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtfcrdmhsa.html


<!-- 参考信息 -->