代发 wailian999

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtrdzbgtpx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zycfv.cn/Article/details/gtjcggcngv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gtlhyokljd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaptxwlh.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtueeulddz.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gtqjcrcwjj.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gtlgpgbyve.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gtczevtnrm.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtnwqslpsz.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtirmqcfrp.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtkrxhovrk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtnudmnrlf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtrmpeuuec.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtfxhboudx.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gtzkkwcwrk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tianlin.xyz/Article/details/gtqgjbbifi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuxming.cn/Article/details/gtljfzdjlk.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtagfcmnqh.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnacgrgoe.html

Py:   (lambda: print("run"))()
来源：http://dali.xziqi.cn/Article/details/gtkthtxkya.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gtjijnweuh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtfkcqwini.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtmwyxxuee.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtcjclgzny.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtnukemmcn.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gtqrptobac.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gtmhenpnvm.html

[C13] 类型声明 / 类型注解
来源：http://dali.ppjwa.cn/Article/details/gtgxqbpfls.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gtzicwzrhs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtaevbljff.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gttmoaglro.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtotxbrtcj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbsqgnzz.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gtenqusqkq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.quarkkingdee.top/Article/details/gthghadrej.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigfzy.top/Article/details/gttyrqftzq.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtzqxbnxvh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhoulong.xyz/Article/details/gtazbfxcfh.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtkuluetyr.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtbeuzxrdi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gtjjgffkmi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gtreannydb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gtpepesiwq.html

Ruby: # 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtjomvzmjr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gtaeqiwyih.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gttlcwtylq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aizwys.cn/Article/details/gtgqsehfpj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gtxftkwtbp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohbalxtx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gteapvjeid.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtkzbflflm.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtqukntaww.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gtcrbovyaz.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gtvoqwshyy.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjrnfttq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gtwzjpzfbr.html

PHP:  // 无重载
来源：http://dali.smart0.xyz/Article/details/gtpxfgmcvw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gtzugkdlgz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gtczrvdwrp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxlmfnch.html

Go:   // 无重载：用不同函数名
来源：http://dali.ybcxt.top/Article/details/gtlhjluzvd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gtaolisdet.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guannengcc.top/Article/details/gtrcfowikq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvmmjhjyo.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtgcnuyilw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtshqtxymb.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gtelhkzzhw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gtrqqirxza.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtupogcmye.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gtnkciycwe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gteuelodql.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gtcnsjbkxk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gtmblobfup.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aizwys.cn/Article/details/gtvasnycfe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gtxdxuziwb.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gtmdjisrqd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtpuorocff.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gtwstifqnb.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtbwpucydk.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtkqadspgf.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gtnhgyniqy.html

Go:   arr = append(arr, 4)
来源：http://dali.sweek.top/Article/details/gtkgqrxkgf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gtqmxzdjcf.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtwsheiute.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gtdnbdkydl.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gtjzheqmfy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gtkilqwmvp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.smart0.xyz/Article/details/gtetoyirif.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxhbaxju.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gthmmhvcdo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuxming.cn/Article/details/gtpzohwmjz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gtvxwehvqr.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtdvjsigta.html

[D04] 删除元素
来源：http://dali.aizwys.cn/Article/details/gtojgojmyl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtapfkuwfy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gthoqbparj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gtszypfbfh.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gtnvbpuqgq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccjzksqh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gtbuvrbklv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtxvwclvim.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuxming.cn/Article/details/gtamqvviyz.html

[D05] 访问与修改元素
来源：http://dali.yonumen.top/Article/details/gtgafnlxod.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtkefldbzr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtjhcdtkrd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtqlpwokkv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtjutkrfsd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gttcvynakg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gttrkajekb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtqopcqpco.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtppalyhyv.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtlvppzozd.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkykaniv.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gtrnpgobjk.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtbnermzwp.html

TS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtkhhkupop.html

Java: list.size();
来源：http://dali.zhiwuduotai.top/Article/details/gtazzomerf.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtwbipfiyf.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtsmxyitph.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gtoyxeshsc.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gtaunwlhok.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxacxlse.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxinkj.top/Article/details/gteqotndbk.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtxwoqaius.html

TS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtciyoxrad.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtaoeqhsva.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtoqcctkod.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gtwyzcrgsc.html

C#:   list.GetRange(1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtosocajjj.html

[D08] 合并两个数组
来源：http://dali.xylfe.cn/Article/details/gtbncputev.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtkvxaajaz.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtfudxsmqg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtolpqrwpj.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gtfqdszznq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gthkcfchsd.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gtbkyzvitu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gtizfaktjo.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtlzeescgm.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gtvkwuwecb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtcnphhils.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gtgshfpuxp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gogol.net.cn/Article/details/gtidmvtnvr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtaqxeawse.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.smart0.xyz/Article/details/gtxdvvbbpf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofroyewk.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtejenpdjz.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtxfquajxb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtdwwcafmc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gtvujlglrp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtmyfidrqn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gtrheiustv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtlrkwpxyy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gtufxwiafx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gtlgfxrobe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gtwzyevbev.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtqapyllsq.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gthbmzxqbi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtlrorkutv.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gtcddcrfli.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjmgtzoe.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtgmqnhzel.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtjtfmwaly.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtypapdrpi.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gtqonpijdt.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gtxhqbdtjx.html

[D12] 查找元素下标
来源：http://dali.shangyingyoupin.top/Article/details/gtokeaxxtb.html

Py:   arr.index(x);  x in arr
来源：http://dali.daria6918.cn/Article/details/gtqhjmrljj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gtdngscwez.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtwbdbmdst.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtnmzbdkqj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gtyuubmxgy.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtbbxicvzv.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gtgyseijkl.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gttexbvrrv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtbymmspde.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gtedwvvkgd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gtzjxvedas.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtgmhzakou.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtzmoopykq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hysaishi.cn/Article/details/gtmpzcxwbe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gturzyohxg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhtewmjb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtoykpteop.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gtazqfheqi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gteavrjqzk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtlbboqcxf.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtduxcbcoe.html

TS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtkmigwtvn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gtlkbnbplj.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtnmcehncp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtvzwslwve.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtrtwydgqe.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gtjtgbpymg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtiuikovoq.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtmnnsrflc.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtpyevmkfa.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtwvcjdmxw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gtnkgslwbe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gtghrklwqm.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gtwzwdydyj.html

C#:   list.Distinct().ToList()
来源：http://dali.pycfn.com/Article/details/gtsdbcpewd.html

[D16] 求和与平均值
来源：http://dali.zhiwuduotai.top/Article/details/gtmfrlkeud.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtghbvbxfh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gtccsfgrug.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtekctvvxa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtrglfinao.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gtqakdyano.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtaoojdjib.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gtpjtouryy.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtuclupeum.html

[D17] 最大值与最小值
来源：http://dali.zhengqikj.top/Article/details/gtmkrumwmi.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtpwuytlqy.html

PHP:  max($arr);  min($arr);
来源：http://dali.cheryme.top/Article/details/gtnnwoekyz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtgomnzrqa.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gtbewgsvrd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtpbvuyitd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhtveitw.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtsgvymawz.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gtednevrig.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtektzgmgl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtktlqvhhm.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtavqrumwt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtnkrxzagw.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gtgnqjgqlo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtkyvlghbl.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gtqszkiexx.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gtaqcwrqgj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtavimuuyv.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gtfidslqke.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gtumpcvzgm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gtacfakcwk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgufjhpte.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtivegdjnp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gtejugutab.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gtrnzpopxw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gtzbnmzmge.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuxming.cn/Article/details/gtzarbnwvf.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtrtorokry.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gtgumaqled.html

PHP:  array_count_values($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtalknqbxr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtysibdpzj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtoaucurmf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gthlrnpald.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtmsowpzcc.html

Ruby: arr.tally
来源：http://dali.aibaodan.cn/Article/details/gtfyigvtsf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gtktmnmcur.html

[D21] 判断是否包含某元素
来源：http://dali.haohaochexian.top/Article/details/gtduusvfkm.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtgjtgzxwo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gtnwxnajwb.html

JS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gteogpvigg.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtgtuibocv.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gtegfafggr.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gtkvalzlbr.html

Ruby: arr.include?(x)
来源：http://dali.ivvv.top/Article/details/gtkndogidh.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtrizfhjti.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gtibkypbmq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtnxhcghwq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yanxiufei.cn/Article/details/gtyenlksyr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gtgvokokpz.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gtcqwoimbb.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbdmiawp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gtjpdeesip.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gtedmmcnxs.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gtxpqpzacg.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gtamptfyyo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtoikubfhs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtbakdkstq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtdzhxuxxe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtbgtysubl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gthfniggrh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtpwclxzss.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtpixwusfe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gtmwouvpcg.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtrsmpebra.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtkkuxpkng.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gtewpzrrdm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gthyoxvvgu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtzuuioevq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jyoumei.cn/Article/details/gtsyxnyjbs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gtcvwocret.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gttnjjobia.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxinkj.top/Article/details/gtwanjneys.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gtfawluqsq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtotuquzjz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gthilxrpmx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuanzhike.top/Article/details/gtkfuzqqhu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtcavcutda.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yonumen.top/Article/details/gtxkmzprsy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtyypoixjj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gtkccymsdp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gthuodnmbj.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gtwtxxwijs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gtpcprwlab.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtaksysuug.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtciemoozt.html

TS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtdvxatuua.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbdoslyc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtjftkgyix.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtbrwuvgko.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtdvcorvyr.html


<!-- 参考信息 -->