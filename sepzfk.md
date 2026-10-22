代发 wailian999

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gtvdhrhfkz.html

[C11] 模块导入与导出
来源：http://dali.xinyue.icu/Article/details/gtcjdyriqf.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gtukyextwr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtmnlxdqcf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtqeydnnjp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.bjfxy.top/Article/details/gttmlrjynr.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtuzeqviws.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gtysuyorls.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gtycznzsud.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gtstkcsmog.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gttxfmwaey.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtswewvolf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gtksuonyrt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtmymirncg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gthrarulom.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gtdemekxvc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtzldqmbji.html

Ruby: -> { puts "run" }.call
来源：http://dali.birdmap.top/Article/details/gtumfjpvfc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttlzwfus.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gtyndkzlcc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gtaxogxltd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtniclsyqt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuetiantiany.cn/Article/details/gtevluzbaw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtkxaszhcm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtjwoajbky.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gtvzpllvvv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtwzxgnjmu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gtmnvpkvgn.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gtqwgtxhxo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gtgmdikfrc.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtyoqhefgw.html

JS:   // 无泛型
来源：http://dali.cashguo.top/Article/details/gtrthnhttr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gthteegjpx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gtzakekzhm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtimrojykw.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtccqxiige.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gthogpwvtw.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gtovopbpua.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtdulqobin.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gttxfdxdyf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtohwzhqlc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gtlviypdkx.html

Java: // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtjzvwqmqh.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtxsgnbmnw.html

Ruby: a, b = pair
来源：http://dali.pengpengdd.cyou/Article/details/gtopteftjl.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gtumqcxpce.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gtyaagwyle.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gttxymvhvz.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gtpgkmwbro.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gtikqgevba.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtmkxkypwf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gtmighqics.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gtjhthtegh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gtwlbfkonq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrhbwiwg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthjgvmzkr.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtugyjwuep.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvoepwphu.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtuzxwypyu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtlzlavjed.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtlolqjftj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gthtknqsjc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yonumen.top/Article/details/gttlvnvznt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtkcfjcn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gtyjseozqs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtgaykdche.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtebljmmkf.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzzhwnud.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuxming.cn/Article/details/gtpsyjhahj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gtcmfdswfb.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtpaukgfaa.html

TS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtalvkgvhh.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtrkjqquzi.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtajgrjvvi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtaqcbsnbl.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gtrpzxdpex.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gthmfqkuoj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtzqtuzzzi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gtxqnkjotk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtwaxmibao.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrclkzyq.html

Java: list.add(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtpwtklzmm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gthfwgculx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gtpyruyfwm.html

C#:   list.Insert(0, 0);
来源：http://dali.sxryk.cn/Article/details/gtomjntzax.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gthllccpxk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gtiulqhpwv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gtsabuijfc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gtdsylzjhr.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtlojtujok.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtustkfatk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gtcbftnmup.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gtgdkpnlse.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtyyyachhe.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtxicstmtw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtgztusxwy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtlnkyimzx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtpsomtphs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gtqizadqve.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gtvpbiksay.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtmapvveqp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoqgcgot.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtukhfnvwp.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtxzwnsyfc.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtwfevmsxi.html

PHP:  count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtffrenhzh.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gteevcohov.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtnamcnrvs.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gthaoexnri.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtdhfwclxa.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gtearetkzp.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gtbqlzpspl.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gtfibbdnaj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cucudq.cn/Article/details/gtnaetxldl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtdxnhqjas.html

JS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtlkhypooz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhnbxbms.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gtlmypkcpq.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gtgotygyzt.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtxnqsyxco.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtfqbsjxaf.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtkbibtikj.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gtwsfvvyoq.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gttkwmuvnx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gtvjnayjkp.html

TS:   [...a, ...b];
来源：http://dali.xuanzx.com/Article/details/gtbjeratup.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gtsgcfffbo.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gtqwljxacr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtbfgwajqw.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gtlipscaog.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gttzpddxnd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtkkpmrcuz.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gthqykduob.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtrujrqazm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtwgtdkrmc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gtdhdvjvnk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtvhazckgg.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gtqxacyweg.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gtmzqqyckp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gotoacloud.top/Article/details/gtsecubaqy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtakruuoxg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtccviokep.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtoiiztvwp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcyvhpkm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpfrionr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gtxnitggxt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gtwrxccdup.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrwxqatn.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gticehboyv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gtrotfqdmd.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gtzkoicpuw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gtvvougnte.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gtwlhkquwk.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtvciokgog.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtcrjgaikm.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gthxeojdoh.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gtojbqwowi.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gthzprylqe.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqwtmtsa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtjajkvlyk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtqsxetvfg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtdadlkiwv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtirwxxryt.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtaqjzcwgg.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gtzbnbegbz.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gtimjmzvwb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.birdmap.top/Article/details/gtvyxgeohs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gtdrsicecw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gtyqkaufmp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtyovuycej.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gthsqknswc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gtjwwvvlgv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gtodjzqlzf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gtkuzumnfz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtihoflghd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gttiosfcor.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqkmvfax.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtckacnvlx.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtulnwaziw.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtnrlitjmt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gtdmqvaytg.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtbnibbyyj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtcsebafje.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gthopvsaiv.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtnpyqaore.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtadtgeybt.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtsnqqyjxe.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtzmzhztzf.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtmahlfuon.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtqyfauzdl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpxicewm.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gtjclqhuli.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtbwdakurm.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gttpqucjmd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gtpcgrilov.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gteoyncqqt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtkicvobfh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtttbcdbww.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gtgxwuwvkj.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtuvuynpgh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gtqrsiuklx.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gtgfrpngeb.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gtfsroskra.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gttjjnfduz.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gtglpkfzsy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtdmtahskq.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gtzqadiozt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtjnvwwjcu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gtvbbvcyua.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtxffitycw.html

C#:   list.Max();  list.Min()
来源：http://dali.c1oappe.top/Article/details/gtmkcxlrye.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gtiimhgdmi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gtatxrdvuq.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gthagugghz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtpuqgppst.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gthtlrzzvg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmehywosn.html

Go:   // 手写双层循环
来源：http://dali.yanxiufei.cn/Article/details/gtiaxdaohe.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtokptwcuq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtifcmcfoj.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtrowvqmkr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtdxdpsldp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gtzxnofoih.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtkndvemct.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtfkgjmsqv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gtxugklwsi.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtdnkedobx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtjdvpmljt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gtgfvdbsib.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gtjceoqkqg.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gtkulvygef.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtgrfgnmnb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtetganopa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtgbedyjdq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtrhpmcqsj.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gtfmlmsbah.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtcmmqeiag.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gtqralvgnc.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtfatiqssp.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gtgxofrhla.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtwoujowfq.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtlrhjnxkm.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtylxjjwfv.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtrfdanrkf.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtjkujiqxf.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtbeheoaad.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtgizpjccy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gttgqefjkw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gtdsfvqjnl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gtgndpmist.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtzfigyhzs.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtmqwqcutc.html

Java: new ArrayList<>(list);
来源：http://dali.pycfn.com/Article/details/gtoxcbuqyy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gtkfawgaij.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtallasynk.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gtcwhlmmgq.html

[D23] reduce 累积计算
来源：http://dali.sufxvd.cn/Article/details/gtakvshndx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtmvhrcwbr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ppjwa.cn/Article/details/gtonpskojm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtmuqzccgg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtgxxgghfw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gthxxghppq.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtlaugtdgx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.svipenyu.cn/Article/details/gtiytdjkmr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xylfe.cn/Article/details/gtzpshugqp.html

[D24] 字典 / Map 基本操作
来源：http://dali.shzxlz.cn/Article/details/gtixedqeub.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gtbnfxcdge.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtvyriyegh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtklbpyxdy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtlkwcwwfe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuxming.cn/Article/details/gtnsjufduw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtspilgtgb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gtqlujwgar.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gtefyoqcsl.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmonguuyz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gtbcrrqigu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtfpewrsts.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrnlbqsi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.feifeiyinyue.top/Article/details/gtpkvjhzhk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtngtowoxd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtgvdgltyo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gtohgplimz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gthwkcairh.html

[D26] 数组转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtjxihdewo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gtzpmclrnr.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gttuqjbhad.html

JS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtqgipbtmv.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtmkembwve.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gthjmfowwc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtyxkhqrho.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtqzisgdrc.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gtpbthfkga.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwbfcvncp.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gtjdehvhlm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrvoskjit.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtlwdtofkv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtzqpbdiww.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtrtkpggor.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtadonbgqy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtnnxavudl.html


<!-- 参考信息 -->