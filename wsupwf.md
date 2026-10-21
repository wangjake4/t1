代发 wailian999

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtezponeit.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtgyekgnaa.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gtwummfhpo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gtrcrnpmvp.html

C#:   块级作用域
来源：http://dali.tian-w.cn/Article/details/gtxwzorjje.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtbshmgzgv.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gtnefotoux.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gtwdoxqmrg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gtbeemkqou.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtnblynzui.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gtoatfarzm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gtveoxslht.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xinyue.icu/Article/details/gtedbbiect.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gthgogeokc.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtidlowldn.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gtdnphzggs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gtswqcqlqt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtgqiziuip.html

TS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gteipyllaf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gtfwxndyfd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gtrqvqmiow.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtnzoctutv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gtyszjklwm.html

[C13] 类型声明 / 类型注解
来源：http://dali.ppjwa.cn/Article/details/gtkmkzneyb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gtuymfcpln.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtvrohgnem.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gtirzbumic.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtglmrvqov.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtocjmappt.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtsybwqxho.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gtqfrotbot.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtikcsicja.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gtvjbeziih.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gtnnpydrwf.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdfnhstr.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtbmdkeoor.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtymsxitgo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gtywsdzykj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtzukfclho.html

Ruby: # 无泛型
来源：http://dali.xuanzx.com/Article/details/gtjplyxkqs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gtwkkgecfq.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gtlketfejb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gtckeulskx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gtfngzkyfk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtwtkffygl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtlvfyrfjn.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtgouybvdq.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gtfygrkwxz.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gtwrplzela.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtkfgcuahw.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gtmukbxvyj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gtnosukqdz.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gtguxokjsl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gtgomyudcg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gtsropxbpj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ybcxt.top/Article/details/gtrzcfpeso.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhoulong.xyz/Article/details/gthmmmqvoc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtthyzukvf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtcofdxjpi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxgqfgyrj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtqaqzmzox.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpuvypycw.html

[D01] 创建数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gtzpyniuqj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gthiheczwc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtzhrquylu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtykzkmskg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gtyqoeibct.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtsmbzprez.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gtlcgotxor.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gtznyuoiym.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.vqdsnc.cn/Article/details/gtxgkdjrqz.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gtqnllmkgz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzsojfey.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtvosyjfrs.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtbuxpushd.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtvctivsib.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gtssgnshof.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gtidgkbsye.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtnvchezrj.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gtqevxkcmb.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtetumplcz.html

Py:   arr.insert(0, 0)
来源：http://dali.iojbl.cn/Article/details/gtbkqbpedq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gtisbhjxlr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gtodnqwaju.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gtipljmvux.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtcxvddcbx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gtbhnqqhsm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.smart0.xyz/Article/details/gtzniztyup.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtamrcnivm.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtpfiuwmil.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gtzyebbkzp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ybcxt.top/Article/details/gtqklrlyyk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258.top/Article/details/gtrpsgwgzv.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gtuhftpuji.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gtyictysei.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhengqikj.top/Article/details/gtakjwjymp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtngfjrgkc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtxrtqezcl.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gtxuyfseqa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtmxacipuw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gttqrllbid.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjurkczw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gttsoetyey.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dianchejie.cn/Article/details/gthonuypqy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtvvmjwana.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtoparvqzy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtkshmypmv.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gtyqqqzqnb.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtlfvzrssw.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtvqisdnkj.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtoctjbqdp.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtfkbksqsd.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtruaiqfrw.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtosoflbad.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gtgawzuzpy.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gtbuikcthw.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gtevawmnvh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gtthyurqpp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtrgddlqpo.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtdiyudfmg.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtaqjatvyb.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtnvktnrux.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmfeurtj.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtquzwbamt.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtmpeslwbz.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gttcibieix.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtbrdnypka.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gtapuiules.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.andypj.xyz/Article/details/gtwgcnikmh.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtrchwfppx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsduhvpmh.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gtovhwleyy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtsgrofylo.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtwpsnlnqx.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gtqjtvaplj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtocsrauvh.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gttcojtsfe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtmmthnzvj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtahbovzqe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gthmuyyvdu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtlrmuzmtq.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtwytifqnl.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtctvdcnbn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gtobgyuzpu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gtxlwzmttc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtvifbarpm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtvhmccuje.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtjlaebhet.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtxfdmgonm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gttzblcvav.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gtefpixmlf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gtqngmunca.html

[D11] 反转数组
来源：http://dali.aizwys.cn/Article/details/gtctetpxfd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gtolqckctg.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtjqyxbogd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gtmwuijkqn.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gttdobwbgt.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gthhtpvtsx.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gtjqdfvazp.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtbydxuywi.html

C#:   list.Reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gtayophgsa.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gtpeiobtfo.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gtvzewtdwv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtutyhfwhc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtkuwyiwnj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gthaoqwfxn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gtqxvfdybx.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttptjxymx.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gtlzhswrvp.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtdwwlmypt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtkgzfqrde.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yongpay.top/Article/details/gtzcfzezpz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtbgqnormy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtkzbaglpo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtvcsfttyy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gtzyivbrnk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gtsykyosbq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtrilzykry.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtmgivhdba.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gtajqhcsgx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yanxiufei.cn/Article/details/gttgbvmzfk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gtejkapgha.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtaratycxl.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlolzpzpe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gtqewkudum.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtwengajqc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtkzfbuhcr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtqtuvdczh.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gtftbnpkoq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gthjcdiuoh.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gtsojiblsg.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtfgchtxbo.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtsifdrkpc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gtjtbgtong.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cashguo.top/Article/details/gtaabmcdco.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtecotysfo.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gtzqvcohxv.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gtcixnpkgn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gtnnpwsjbc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gttvtelrvg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtcocpwavx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtwufvaziu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtzkcnyctv.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gtqykxaxyx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtuuisrgdh.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gtuukprdwe.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gtxiypcezp.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtjgqhxpgu.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtzsjrmwrf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gttmlmvjpw.html

TS:   Math.max(...arr);
来源：http://dali.nwbrower.top/Article/details/gtatjyiskv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gttobnkxge.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtmphxqqzs.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gtoomefcak.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtxdcqbkmh.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gtyyzdqkpe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gtbxsyfcec.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gtnldxjqlo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gtvszgmomk.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsgnqbvj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gtwmddjkxi.html

Go:   // 手写双层循环
来源：http://dali.yuxming.cn/Article/details/gtlwvjrpiw.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gtnollgtyj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtrjaavfiz.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtephbwbbq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gtweahyaqm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cdnleiting.top/Article/details/gtbckhlvgt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gtjzrgujge.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gtywuyisdm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gtdplexowk.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gtabcupvjk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gtjsupbmhs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gttipkaylh.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtslcyejla.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gthqvfjdmh.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtcyaymzqz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtnnoknbgt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtayvtulye.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gtntfyhwbm.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gtvcttoqfh.html

Ruby: arr.tally
来源：http://dali.shzxlz.cn/Article/details/gtmddgwczx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtetvnhoci.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gtgodbjmoj.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtrvpyaulf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtcjpfaetj.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtnnllpfai.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtnkvawwlr.html

Java: list.contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrandwjf.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtbyjgmquq.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gthijludnv.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtvotrdrql.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gteiscbipp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmamjoaqf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gtterygqmz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxinkj.top/Article/details/gtihcpuemk.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gtmuxvaylp.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtrkovtwhc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtvdmwuqpa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gtniwzqyef.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gtnnzrzofd.html

[D23] reduce 累积计算
来源：http://dali.ybcxt.top/Article/details/gtzuxkhfir.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gtutftmskc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtbedftdqu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gthsxykryh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gteusmmmwy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gtxnbylhrk.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtdxskhmcy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gttcakosfp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gtnsvhefiz.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtwrhqgega.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gthvlohntw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gtismieekd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtqstitlkp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtgzxrykqb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotmrnuyp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gticlsrdhw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gzhubu.top/Article/details/gtbleaasud.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtptsuaixh.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtxpjxoivw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtsbfbrpdf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gthkowkdhd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gtxjlpthcs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdprfzmt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtvoaevduy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.andypj.xyz/Article/details/gtlwxlifjk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gtujwhylee.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj202588.top/Article/details/gtuyptbzke.html

[D26] 数组转字符串
来源：http://dali.0kj1m.cn/Article/details/gtsygdkddl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gtfraytcjw.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtydynszux.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtjrstqfrm.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtbkxyufrd.html

Java: String.join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtaevfsimp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtxcugpqla.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtuqctosnq.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtxdmkgmhc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvffqsgxn.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gtmamavmmx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbtbdezmc.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtidfuhodp.html


<!-- 参考信息 -->