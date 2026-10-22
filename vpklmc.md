代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtqliygnbt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gtvohzqmlk.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gtuhfvwaqa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtvjzazgkg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gtnagntrey.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gtsudxktkz.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtqffgcscu.html

Py:   (lambda: print("run"))()
来源：http://dali.yuanzhike.top/Article/details/gtqgyzbmkq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtdaigbyxo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtnveeutuj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtittmcqfq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtbogbwnzi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gtypquhdmm.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gtqizuywov.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtadqmdvfw.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gtjtsmdeiz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gtckbcznpo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyogdgukk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtrejzqaue.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gttqqwzboc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtfaoxjlgl.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gtcnsapazk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xziqi.cn/Article/details/gtdgeqadwe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gtggoitwfv.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghwjgolv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gtemhrkbkr.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtbwwwablq.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtioyolrjh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtiuunkbvd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.smart0.xyz/Article/details/gtvhpquknl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gtcrambmjz.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuambjslh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gtzdtfuokw.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gtqodnpssh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtdjonvqei.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gttwidhhow.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtbughdork.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gtqmgmqgzh.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtmpkzvjkc.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwlnqcje.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gtoushldrq.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtllkhrhct.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gtdnxtmola.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtbmxgaqaj.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gtzbolvvin.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gtrhcrsqio.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtngmzckcq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gtaeibjbsf.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtnytoumdx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtptmojzhe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtursvkwij.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtyxumexlu.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtnaihgzak.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvobvpngl.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrefwgnvu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gtdmcbnkbp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gtwgdwmowo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtywxsjcpq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.316326.xyz/Article/details/gtxjbvfwpn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtqeljgblv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtfnjjokih.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hywenlv.cn/Article/details/gttuaaycww.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gtguszrrtu.html

[D02] 追加元素到末尾
来源：http://dali.sufxvd.cn/Article/details/gtfzyryxqr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtgmfjmzzh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xziqi.cn/Article/details/gtcxqyvunx.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtmqgatheo.html

TS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtifkucjiw.html

Java: list.add(4);
来源：http://dali.sysykeji.top/Article/details/gtmvuxcuit.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtereqypxv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gtnovbjmxa.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtlvkwnebs.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gtaltiqfhq.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtjvyizpvl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbtngrxo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gtkqciisrz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtjckuniiq.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtleqsmspu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtvkaprcyz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtycxxmxjl.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtqyqfdgpf.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gtvgitadvb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gtyfkhqtdg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtnsaakooq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtevwtsbvt.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gtcqsufnyf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gtyohkwjgg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtcbfocntg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gtzhrgfmfp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gthsglgyee.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gtnezrhojy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtmjnhdmat.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gthxkmwgwp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtfprzuipa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gtfkmjzbux.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtdbkhzhyv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtgrdvobiq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gthelkklpe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtkhnysldj.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtemrzekma.html

Py:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtwgjflqmh.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtqfcxzvgh.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtrgxmeuvw.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtpfbjukeg.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gtciwwgfxt.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtphihusrr.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gttmfzcayd.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtuangnacy.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gttynzemcr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltzovjwx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gtskdadwax.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtscivabzh.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtokgfioab.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtuquhmopi.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gtksybfyzb.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtguspglcn.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gtitmbqfye.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gttdhdwjth.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gtpdjmsaab.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gtsffixbhs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtaxnaxjol.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtohrmvuoh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gtvpltnrxy.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsugcacmh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gtqahvbkfs.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtfykoybmj.html

[D09] 排序（升序）
来源：http://dali.yj20258888.top/Article/details/gtlkqgfkos.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtdjpkobex.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gtdddpruao.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gtwoentcls.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gtouiadlhu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmhrielq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtwhsbkhox.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtscpjyaas.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gtxqqhtvjo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gtqyljvngt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtiefvwccd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtfbqxvcop.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtbklirtkv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtattofxrg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtikngbarb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.redwolf501.top/Article/details/gtxyhtycox.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gtgqyajnqw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gtpigxejuk.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzxzykcg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxinkj.top/Article/details/gtelochfae.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gtpmwidztd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gtrfvubbzz.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtzvkajnmw.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtfdnxgvfx.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gtdggmaxrr.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtmebpfqcq.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtnaczhjvp.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gtmwhxityy.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gtvogxscon.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gthgbmxdil.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtoamewvcj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtxvdlendy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.9152youxi.cn/Article/details/gtxwjqobej.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtbuymlspq.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtyfaofmmk.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gtgjguadlp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj202588.top/Article/details/gtctajnbby.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtzkywlrso.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gtflfkwlmg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtxqcnukly.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtsbhxqloi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gtknztppuu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwhvxxzd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cqqwz.cn/Article/details/gtbufgfzcd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gttmrcxhrc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gtyxgykjpa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtunpejyia.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gtqmnlakju.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtthyfzdkf.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtahugqalr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gtmvbokgpw.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtsvywbfjr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtgewhghth.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtblhhedms.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtwknjhnty.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtxvqgoedv.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gtjaduexai.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtdqxydmnz.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtaoglwhoo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gteaxkzhae.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gtgkzblbva.html

Ruby: arr.uniq
来源：http://dali.316326.xyz/Article/details/gtjygwtnei.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gtztmpnfsw.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gtznbivlda.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtjxbfumik.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gtjbfkvtdi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gthwjzehvr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtumhxiyqn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtucregpbi.html

Go:   // 手写循环累加
来源：http://dali.dashuyun.cn/Article/details/gtgukzcnfp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gtijoznlbu.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gtvsiktfod.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gtturaofal.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gtnxoojttj.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gtuzuspupk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gtqitefrjq.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gtyiqevxpz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gtmcseuxjx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gtfksoqtnj.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqmqtelo.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gtxonlbtrq.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gtyeaoshun.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtesshetmb.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gttzplvpns.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtrprhxuph.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gtpozofliv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gtepubbsiy.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gtihotnbbq.html

Ruby: nested.flatten
来源：http://dali.cdnleiting.top/Article/details/gttpnysbzr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtjzccxyoa.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gtnuuclggy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gtbvuniyox.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtetdlgkke.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtrxfblqmp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtzwiahzjy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gtefeivrmf.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gtjjapzigk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gtvsjjnzjt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gtuwpplcjq.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtjrfwspst.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gteworxynq.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gtkvcfxpgu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtbexkaahb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gteqhkvzev.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gtlhqtlych.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gtiwimcoyr.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gtbsmiyvzf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtkmonyekz.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtytakljyq.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtimomjkdp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtgzefdfdg.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtgekgchjx.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtcsfddyhz.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtkarpftlc.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcdynygy.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gtceiwaefc.html

C#:   list.Contains(x)
来源：http://dali.yongpay.top/Article/details/gtefucdnam.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zdqjudy.top/Article/details/gtrnruyxoe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gtpcdpadsw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gaohongyu789.top/Article/details/gtojuevzbl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gtzfqbkozl.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtcembtegw.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtexylsjtg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gtjfmpgapw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzarynrx.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gtghvlbdbk.html

[D23] reduce 累积计算
来源：http://dali.fzhhl.top/Article/details/gtxcgfcasa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtjtbneugz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuanzx.com/Article/details/gtohuigeej.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtlcugcrgs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtsigtcxkl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gtbpeuaspq.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtppwrjpxa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybwerfey.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gtjkvholmc.html

[D24] 字典 / Map 基本操作
来源：http://dali.feifeiyinyue.top/Article/details/gtsbevyyir.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sweek.top/Article/details/gtcicexyja.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtsazorbqn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gtzxugpgfc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtcsivwtfd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.wangdashe.top/Article/details/gttwrzucml.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gtubtuivln.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gtnezrklpx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwbdrktp.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlqhkrld.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjzasanx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtuavrrrur.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gtlatnkuio.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gtxldtqemi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtdsnhgtiu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtwyjbkguu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gtooshlwih.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gtrhcqbtuh.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gtgoyaggsd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtamwqeehf.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtvrmrgwtm.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtseafvyvv.html

TS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtzugccoig.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwvpowja.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gtopehjdgi.html

Ruby: arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtbuwhvhay.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtxbxnytkq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmpszeelm.html

E. 字符串处理
来源：http://dali.yonumen.top/Article/details/gtcjsbnxhb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgepuyxlf.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gtwlzoyuvy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtdpxyvyfi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ivvv.top/Article/details/gtnvszagzd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtqvnjfhyb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtivirymji.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tianlin.xyz/Article/details/gtgwtsbuae.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gtdlkdoabk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gtvbitnsbu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtadnwfwvp.html


<!-- 参考信息 -->