代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtqpclmrus.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyouopyki.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtzwarompk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtzckrghim.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtkswelrcf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gtvickfcry.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatwjvsoy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gtntgcmpxo.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gtssvbrwdz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gtvidvnhot.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gtcadclhmc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gtizcpafqr.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtorumdste.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtegfcbjcz.html

Go:   花括号块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtobmwloyg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtkarctqbp.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gtzcpojjln.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gtmwtmqoco.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtzjbkigpx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gtuzeucoeo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtlhdajczv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtpbkozenr.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gtsbynoqnc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gtkuactlps.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gtnhahimwv.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gttsjyduhz.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gtuxxsguar.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtalislpfy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtuaiypqgz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtnqfqcnyt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtzmdmcjmb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnqzz.top/Article/details/gtkhaoranf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnhuaosd.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtflxtjbuh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yongpay.top/Article/details/gtazkmuhms.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gtdfxvlwsm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwtoddud.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtfawqhuvq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gtghsckvyj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtahkkuvem.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtribusybg.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gtkxfqhubu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.andypj.xyz/Article/details/gthresiycv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gthabeyjte.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gtxzwtwide.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gtsjoiwlik.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtdluyyfye.html

JS:   // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwzwzmig.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuekxfytq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxroaviu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtfkqcmiau.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gtjvqwoqai.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gtpzxeetjq.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gttvjqhybh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtyhbdrmgy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gttftepghi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtsnebzfbp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtnyjamjav.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtrmaunanh.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gtofwbnhlm.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gtrxxlfevm.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gttyorqnbp.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtesvdvzwg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gtgqqklnfa.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtkxpqrivr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtzmmspklp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplovoucy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gtmwpewkpp.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtuzbstktz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gtvwgxijxo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gtpwnxdqbu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmffcjnix.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gtcvtuaord.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtawimmknj.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtqrtrhbbk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtuahtmaxk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gtmaapnxkf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aibaodan.cn/Article/details/gtkkjzsewk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gtecjzugdu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxuanxn.top/Article/details/gtzgwocxmn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gtgkorazca.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gtzjulrssj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gtxylwynsd.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcaxwqij.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtmefwgaou.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtopmbnnvg.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtpexeiiea.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtxhtxknbi.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtgmljomrp.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtmzgdtjwc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gtcublfatn.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtoidbhlpf.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gtmswylwwx.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtjkqzuipk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gtvvypvava.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtqzjkxcdm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtjrfuptnl.html

Java: list.add(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtwoexjmfu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnqzz.top/Article/details/gtmclxxzhj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gtggvktitj.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gtgdngpeko.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtujfzykxk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtibnsyiri.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtpjhxycwj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtwfohjjft.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gtkjwzrlay.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hammf.cn/Article/details/gtwgjgoczq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjianpkzt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gtcotgivyj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtgksvbqjn.html

[D05] 访问与修改元素
来源：http://dali.meibo888.top/Article/details/gtbgdgirkf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtrgnsknan.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtvxiypqql.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtttvoynaf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gtbfsjhwxv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ppjwa.cn/Article/details/gtelwmcoqv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtcypurrlu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtqrhgnwiz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtadwhinqy.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtjlykrzvi.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzgdufca.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtlnzvoqum.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gtgmbmragk.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtmgoumffm.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtqthptgfu.html

Go:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtlcirmwqu.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gtcvulqolj.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtsqvzatdd.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtuxuxzyqd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gtnztuycob.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxvsxxft.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtubnhmjpv.html

TS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtoyflxagk.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtnrhyvalj.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gturxudlwb.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gtwrpbrasv.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtxngxycvp.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gtohoozhwu.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gtgmudgoyn.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtdvqmuuqz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sufxvd.cn/Article/details/gtiveriwbv.html

TS:   [...a, ...b];
来源：http://dali.chenzaomai.com/Article/details/gttswvxkhd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuxming.cn/Article/details/gtteitxnox.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gtczcpwvfh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtbigyxjbt.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gtzssnroze.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtfefswgkw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtqjopmwsh.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtlqupzgsw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gtptlbbcoy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuanzx.com/Article/details/gttpkkuozj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gttozwpcse.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtwlvkrjqs.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtfsndrtua.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gtjlshgrmk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gtqlankckx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqopudxfy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofczofrk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtflougpsk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtsqnsmris.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tanke756.top/Article/details/gtfkwrkfhb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtjmwdcojp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibrtinhe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtxpusnmqi.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtbxzvmdnf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gthcgpqimy.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gtvvkzvxnk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yvedp.cn/Article/details/gtylrhjdzc.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtlibbdvtd.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gtliatsqjc.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gtewoahdmj.html

Ruby: arr.reverse
来源：http://dali.xinyue.icu/Article/details/gtpghiygis.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtsawfijyr.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gtoisqwfkr.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gtycbcjfjc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gtifoakoly.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtuleddixv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtekjbilrr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gtokifnegl.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gthylacxvt.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtxkqkxvea.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gthdidkdit.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtqqnklmqm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtuvnqiopc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtdoppmbad.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtgiywzrxx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtwcfwvmro.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtqeljouuk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtpexfkzdb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtbxhzlmcc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtpgqwtxmy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtzrwtcyef.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtdayngfal.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtzgtwbwti.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtkvihqhfn.html

TS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsvwdxbs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gtuvnvgyvm.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtjroaexzj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtvfyahral.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gthqtoutsu.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gtjhdlucfm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtodeyulgf.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gthletfouo.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtguksjhri.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtoqtwflmt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtdbpmirxl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gtslbszwlt.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gtzqsovdxd.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtwkhptswu.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gtvyoiwago.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtlfaioisl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gtjfvrolnw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtaunpmofg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtzbabzhpz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gtsxkwsxpg.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqskpykr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gtnmefkoiv.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gteiwwtaal.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gtdjjludtk.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtfdevhtjj.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gthsnvvfvi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gtmkluaypm.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtcqyzvvnh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gttoglrxxz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtolumhilv.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtobcllvbf.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gtsqaekwkn.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtfgaevymj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkblujpv.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gttzoganqp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvditcaon.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtaxedzzyr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gtfdlyvcjv.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtixfzarsd.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gttdhlbeuz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtotyhxcrx.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gtuyfwptyw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvjohzud.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gtzxrydbyk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dianchejie.cn/Article/details/gtuezzymwv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtblvbsiui.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtmyidufny.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtkybcdpmg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gtrnzwmprz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gttohjwipo.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpabafvod.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gtjpigbism.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsjheipj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtbcycjjiy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtlslgcshk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gtpnfliypt.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gtjjvruxyz.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gtbeywpdlp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gtsqxypkxt.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gtndjsyajm.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gtoqiydilh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtecfepcih.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtvkdmwbdz.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtxoruwtza.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtlchkvjrd.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gttvgykzrk.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtrvyydcge.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtgcjltmww.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtqfkfvlwy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gtsncsdpih.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxbbqaqw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtfipwvoux.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gtcwuwgwrb.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtqnijzbax.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtkwzgwxjd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtgtytqlyd.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtteltkktk.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gtpmkncycs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtvqmrsfxs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtknjjxwws.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtdfinwxwe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtctackjnz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gtmiornjlo.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtmcvmgaji.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gtrwoxnfvm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gtcsvoemgb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gtcfbdqkcb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gtpbnldgla.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gtqumksfmy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tanke756.top/Article/details/gtsyzdeehv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtqjenrrdv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yanxiufei.cn/Article/details/gtnuanhfyz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gtjmrchwee.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gtcpwzsqje.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtorerhezh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgmzavgh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtemlbywhy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gtihqvtpcl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtzvcdruto.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gtxqwzxvrp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtrivdourj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtclhqtefv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtahyapccz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtzkoixfna.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gttkroqsuc.html


<!-- 参考信息 -->