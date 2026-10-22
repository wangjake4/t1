代发 wailian999

TS:   同 JS
来源：http://dali.yuanzhike.top/Article/details/gtntbyymyo.html

Java: 方法内为块级作用域
来源：http://dali.xylfe.cn/Article/details/gtarchfvrl.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gticezplhm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yanxiufei.cn/Article/details/gthllbxmjg.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtndiroptf.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gthnzxrvfl.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gtnilhciwt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodkwsque.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtfksypfam.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnqzz.top/Article/details/gtufswbjtm.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gtrkpponiv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtxzoelpii.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gtmyvzxbpj.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gtkkxyiuki.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidsaurht.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gtjcvgqkyk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gtkttlrbmi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtglqcjuav.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtdxvgpzjh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gtwwbgywxc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gttokpqndn.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvgdkuzi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtbevgnwos.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gttvduaytz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtfuqfiyhp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gthkulqjwz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidyhjlon.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtzbuwpmvc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtfqkdlzqb.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtptkdmcuw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gtmscvbwhw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ehwqpu.com/Article/details/gtgvtdufdy.html

[C14] 泛型函数
来源：http://dali.jqgfzy.top/Article/details/gtfqhcsnbv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gtvuhwwfeg.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtsuvpuklh.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtpeahxnaw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gtnrgzqfqt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtvtnjyvtc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gtxppwzolc.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtfvujumtv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gtgbidodem.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gtwxpprdrr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gtjkadpqfg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.c1oappe.top/Article/details/gtryqaujym.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtgkoiujyq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gtoyzqvumy.html

Java: // 无解构
来源：http://dali.dashuyun.cn/Article/details/gtidczvabm.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gttuznrtoh.html

Ruby: a, b = pair
来源：http://dali.pengpengdd.cyou/Article/details/gtbftltvjy.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gtowhzkehc.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gtbmpoafur.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigfzy.top/Article/details/gtzahvhyxn.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtxufovrjp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtqxgpifcf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gtinwelxij.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwahwyrw.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclgrdejx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtjhmqcypq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtukhgywjv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvlfcsohb.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrulxumbh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttvyukfde.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtpisqozga.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtdnnfralv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gtypptqtud.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtdtkuyojo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gtvzvvggwe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gtqnztamao.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.iojbl.cn/Article/details/gtbyhygpal.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuiasuvb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gtwuaxljdj.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gtqqgufmwc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gtckwpwfpt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtsxpcrrcf.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtixqpplca.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtmsqzvray.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gtlucypkhj.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gtwezekohy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gtwhgjxrny.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gtlpbfapos.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtzeamhtva.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258.top/Article/details/gtrvsgdtbl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtzsokvpwk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtpkjnzdqf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.316326.xyz/Article/details/gtvhjqebfp.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gthtzwdgpf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtxqyvhker.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.c1oappe.top/Article/details/gtfbzkckmo.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngqusilm.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtsthiiyav.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtimqcuquj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gtiarlxvft.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gthcnhrbsy.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gtjbgntgph.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gtjrldfhvo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gttamravbf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gtsatffxqp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gtvfumdsxn.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gtddtwqlyk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gttedrzllj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtwjxkjudp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtvhdswmgw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gtmmepqnxw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gtrxzbaevo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtbhnmnsul.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtybpwjbxl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtmnytrfmp.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtlgxuhrmu.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtchcmpblb.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtgjyksoey.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrcnvvlm.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtunupjfiu.html

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gtvqeyqfdi.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtylzwjbxb.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gtclmkzoog.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gtdrdahpec.html

[D07] 切片 / 取子数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvgoxinq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gthuzsgdnp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gthmyvwfej.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtjehserma.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gttiqwmgdm.html

Java: list.subList(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtlnzgwotg.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtpzlgmhlh.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtnvgubxiv.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gthovfxkfc.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtfwdhbcjy.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtxtbxhagi.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gtppkudcci.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gtarqmcpuh.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gtuzsclspl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtyocmqubh.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gtkmairuwi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gtyaqpqjku.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gtltwdtplb.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtbjisqqvc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtowpkycxk.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gthxphzszs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpuhrkqk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtccwupvdd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gtenlayimg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtmhxdncpp.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtuxmenaom.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gtxphyzdzj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gtkrhsxdnp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gtqgtleaac.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtcahebdqo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtyaltqimn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtrmbukyeo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gtjdrvnhcd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gtkjbyxcdb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xylfe.cn/Article/details/gtabrpiacw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yueranfly.top/Article/details/gthzwmyyob.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gtgcgqorqe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gtjidvicxf.html

PHP:  array_reverse($arr);
来源：http://dali.shuidangran.top/Article/details/gtxsjpiive.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenlongwang.top/Article/details/gtasugoerg.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gtawvhpesl.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gtcbthynqo.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtbhhqtgsv.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtairtxcuw.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gtmhwboyqq.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gtmxkiprzm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtclgbkhqi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gttfszuuwx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtuperxcbj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtailezjwq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtjqagnmag.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtucaxvdco.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gtowvzuyzm.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gthsxbubnv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gtcnvbyjbf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtnsndrjfl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtsyaoocch.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtnbqntcvt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtqkizeisa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gtqgcvndsq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daxiang520.top/Article/details/gtfmshbfeg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gtgubtmsej.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtywysxugf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtozglrlpe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtkiamscub.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtqjkogjzq.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtgohrdjpn.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtqmmzpvud.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtrytkfufb.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtragxvqgo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtcncxapgc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtimzieqfp.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gtzrvfugji.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtmmsttiiv.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtfzjnexdu.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtdjazfkda.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtklnfxxyd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtypmfuyty.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gtkopopkxg.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gtwmarcunu.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtizddqyhc.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gtunckgnvv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtzjshhfjz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtaggvhnqj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtkvqgxihn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtmuawahjv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gtrwuoqsvu.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtyywaprto.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtivghkxec.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gteimxiajl.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtlftqjobv.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphjjgonr.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtvghkwmge.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtbewjhzya.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtondnpugy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gtthwadnpb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtxyvfxivl.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtdmtocqoq.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguukduaa.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gticcdtgge.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gtlunxsgcx.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gthzqsblto.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gtjhwxzivx.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtizuqjfim.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gtncqhppkj.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtvufyrufa.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqrpuiwv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtloluetkv.html

[D19] 按字段分组
来源：http://dali.ehwqpu.com/Article/details/gtbgkzfale.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gtdobcanxe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gtwinqipvg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gogol.net.cn/Article/details/gtododjsag.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtiobmecfq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gtcohnqzxv.html

Go:   // 手写 map[string][]T
来源：http://dali.havefunace.top/Article/details/gtgaezsdsg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtjvzytsqw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtuxfhcsrt.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtqgruhsnq.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtxytanzja.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gtjbanqrqo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtvfdwxcom.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtfpxxjsox.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gthvzvvcwk.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmggjsicr.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtwotlpyyk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gtfamxmmth.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gtxslrbbto.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmhksxrp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtahisqmnb.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtrutmagnb.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtltnmfhwa.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdztekdp.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtoduvdrqn.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtycdwquni.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtdagybwuc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtdddnhdcq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtunwqgiwq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gtfghrytqy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtoukrrbxc.html

TS:   [...arr];
来源：http://dali.hnqzz.top/Article/details/gtwhvmlnhy.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtrygwhlfk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gtftibgtbh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtxwdchupu.html

C#:   new List<int>(list);
来源：http://dali.yj202588.top/Article/details/gtkwjqgbch.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gtcuqvizus.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtvmwaibge.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtjahzjsjo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtsplrnkmn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gthnvreizx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.vqdsnc.cn/Article/details/gtjiwzayfw.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtscmcnjkw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gtfkaodogr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gtnmhudpwf.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gtiuulsjbe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthagbkfux.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtqiwkqvgk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gtbfmoadzy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtvtpqbmzs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gteywkulls.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gtvbaqkfwh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gtqepoyglh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gtpkneurji.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtxymadhef.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gtztpaumzu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gtnrbzildw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtgyqfxgmx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xinyue.icu/Article/details/gtjuuswuwe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gtazrqyeqo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gtdfusdkso.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gtuzcpzkjb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtgaebjoqz.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gtixjhkpke.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gtctnzpnle.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtenpelucc.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtsckprwgv.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemcixicy.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gthuiqpwtc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtfpjdreul.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtxcihfzjr.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtcndxszwm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnvnmrpod.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gtisoimgvw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtzgfonqgo.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtdmnfkdsl.html


<!-- 参考信息 -->