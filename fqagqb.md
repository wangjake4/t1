代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtxlakeqcc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.haohaochexian.top/Article/details/gtvzkvkzry.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gtzdveqpim.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gtuzyxyhsm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gtwyvzxzqi.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gtwloettin.html

[C12] 立即执行函数 IIFE
来源：http://dali.shzxlz.cn/Article/details/gtdpbfvten.html

Py:   (lambda: print("run"))()
来源：http://dali.zhiwuduotai.top/Article/details/gtggjxsejw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtlaxusxor.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtzcwexeoh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gthybbedsh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gtccsypvhh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gtleqdodmj.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gtogompouz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimpehaxo.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gtosupxcec.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtiiabxjty.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtnlvsibza.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gtwxgmrkii.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtxkyilbdw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtdfjkrwxg.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtoytmfscr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gtbgfxdypa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtvzmxxzvt.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtjqivscnm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gaohongyu789.top/Article/details/gtnesrqogv.html

PHP:  // 无泛型
来源：http://dali.yonumen.top/Article/details/gtutkvmjwo.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtuelecpkr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gtlqkfsuhm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwnvkwfgs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gtdsjgyqek.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtpablknqa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.c1oappe.top/Article/details/gtxrbguabp.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gtfczdmdhy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigufen.top/Article/details/gtpgppuaak.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigufen.top/Article/details/gtvsxxprhi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbyzautiu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gtnngamjkz.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtkojdzzjt.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtfrahltwf.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gtbvemggec.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gtvmykadxh.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtkskleyel.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtrfoynyre.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gtrzfdskrr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gtpjebonur.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gtwsgualqm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gtqzcjvwzn.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gtoezirmco.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gtjmnqcauo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtpyoyuvgx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcdpfgyae.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gtrpefipkk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnwxinfty.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtchrbbwws.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtsamradkz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gtuwdbbgkc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gtpmxlaavd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigfzy.top/Article/details/gthodlizrt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258.top/Article/details/gtafhfalfr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gtsxxoujuj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmndqsyql.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gtpuzthzcu.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gticahwwzp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtthnxkgqs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gtrzqxitxc.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtbxwcvetm.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtqbdqqgtn.html

Java: list.add(4);
来源：http://dali.zdqjudy.top/Article/details/gtqnbiyhbq.html

Go:   arr = append(arr, 4)
来源：http://dali.redwolf501.top/Article/details/gtocxcylcq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gthmlzmqfy.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gtruazzdxs.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gtdhadzziu.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtszggeyby.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gtoknzdtgx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtiilumivr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gtlnndueon.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtkedyhgfj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gtaiylkfav.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtqtsubhes.html

C#:   list.Insert(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtdervvbes.html

[D04] 删除元素
来源：http://dali.hysaishi.cn/Article/details/gtkoqldemq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gtakpgpfub.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtupeainbo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gtfcfrjgcm.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtielmhfci.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtsjnktusg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtgbwejudv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtjcjjpxjh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gtprugtykm.html

[D05] 访问与修改元素
来源：http://dali.ybcxt.top/Article/details/gtnilyqlav.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtigudbkro.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtmseigqwk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtlhbtxwmq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gteunbwush.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gttoivkepw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtbiwsfmje.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtjhhmfxlq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtxnnsodih.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtmboboald.html

Py:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gttxwvrbfr.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtymmcszsg.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtpowtmgej.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtvzzgzric.html

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gtgaegdbzl.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtqnpnenvb.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtgzbxeqgo.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtknyevfhj.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gtwbuniztr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gtybsqrodw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gttojzaskc.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtimyjmymj.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtyfqfbxmd.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gtpjqxnuwo.html

Go:   arr[1:4]
来源：http://dali.xuetiantiany.cn/Article/details/gtxybjabsw.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gtpldpmijz.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtbgnnxogt.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtblojsinp.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gtoheuytln.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtdmmeodrm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhiwuduotai.top/Article/details/gtstzaimhz.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfgjxhth.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtkkhkdymg.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gtqrmyvkxs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gtubhndwfe.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gtfcaezkss.html

[D09] 排序（升序）
来源：http://dali.feifeiyinyue.top/Article/details/gtbonpatiy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtmhsqlkal.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gtqnqqghef.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gtjxwaosbp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtqtrozlfu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gtzipngvqu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtynvdwxgx.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtqgnqeqto.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gtmkkgxlzs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gtytuisads.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gtyurfopck.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtwbhxfryc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtmohzmysj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gthqumctww.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gtdjflitcc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gtqkglckkj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoepkvzj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dashuyun.cn/Article/details/gtibchrzcx.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gtjnylxghd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gtwhuuvdwh.html

PHP:  array_reverse($arr);
来源：http://dali.9152youxi.cn/Article/details/gtqourmukv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.bjfxy.top/Article/details/gtzdcbdifw.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gtjchlnebv.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gtwbdeulmj.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gttixuhauw.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtqojrvqyb.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtdqkegdxm.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtybdlpcgx.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gthjlougeh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtxamedpvg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtzlnohxqd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtdseqaojw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gtyoohenll.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjfmlupm.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gtfdzwsuzb.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gtruscxsfn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gtbgtzrbrq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtwixcruet.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtstsntzdt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtyujkoifv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtcgkaxrnx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.svipenyu.cn/Article/details/gtlzklvuzl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gtgeogexwp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gtnfynrqno.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtynqabkuw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sweek.top/Article/details/gtuijjmxiq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gttoroyvib.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtyggkwnwn.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtcsjhchqu.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtalenivmk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gtncxvtsnd.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtjyzkvucn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtjwjzbljw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtseedyxqp.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtaiadgehg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gthxhxvmgk.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gtgqyoldum.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtnnsrlcsh.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtzohcwfri.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gtdxscdozu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gtsjalchce.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gtjhghahtf.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtejeeoeep.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtnmismoxl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtyysehody.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtqlrpccxp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtpywqyfms.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtjvnxzdwm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gthiovlgnr.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gttnpmrbfj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtdndqhpur.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gtbporefwv.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gtxwudmgbi.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtwadtrlyh.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gtqxsumbws.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gteygdxvof.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtqxpjjugn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gtngjqrjqj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteigwixys.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gtapeedyaj.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gtxaoonepv.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gtvpadhfrh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucpkavup.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtkhrkeasm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchdmdkjx.html

TS:   nested.flat();
来源：http://dali.tian-w.cn/Article/details/gttayshmuh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gtyboxxexm.html

Go:   // 手写双层循环
来源：http://dali.jqgufenzy.top/Article/details/gtaxwvjgni.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtpsdreyle.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtluwpjyri.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtypmzvpfr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtijgzobdi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtkxpicclj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gtefpgcbry.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtsxqzvhkw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtyvvmrsfu.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gtldacjbbg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gtreyotvdv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtcmlxbobw.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gtlmtpecxl.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtglmnuuxl.html

PHP:  array_count_values($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtlkavljyx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtxynulzaf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtzxawrewj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gtmneadyhe.html

Go:   // 手写 map[T]int
来源：http://dali.andypj.xyz/Article/details/gtnerdqomx.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtemcwgwya.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtclbtqujx.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gtpymofonc.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtihbykjdd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqdpgpkd.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtuywgsbju.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtmlmfnodz.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtxiqsrowt.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtnekaoxze.html

Ruby: arr.include?(x)
来源：http://dali.jianghu66.top/Article/details/gtkundrkwv.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtcrbvpytj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gtibnygwgj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gtkfvzlkbq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuanzhike.top/Article/details/gtcpzywopr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtbonrjhlw.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gtiyinxgbm.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gtudnuzotx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtzzjydvku.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtkejbacip.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtgnxlqcdy.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtscgpeoon.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthudrpuxr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtantdybpl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtzfjdaktf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gttdyipskd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gtzgjxwnav.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gthbliuxfo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gtrwgwzufl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gtuasufijc.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtwqopqyjf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtrpszdtve.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pycfn.com/Article/details/gtnsngbkfs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrsxxhpr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmoptapfy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gtuyonxwfm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gthadkhhkp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gtzbzbsehl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aibaodan.cn/Article/details/gtsutosbjm.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gtzgcmkscz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtdmgocjie.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtdajardxf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gtqbsjguhq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ybcxt.top/Article/details/gtyzgdxfbx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gtfpyllcst.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gtnelynuie.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtjvzwyqjm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gtnhdjftlm.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gtnsiejvns.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtuhpmclen.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gtfwefdmhd.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtobvoxbww.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtugsoskts.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gthrbzixmm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gteagerwfw.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpigkulo.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gttmncxauq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtlbmikrxd.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtgxplcgcx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbrirdbca.html

[E01] 拼接字符串
来源：http://dali.sweek.top/Article/details/gtaqextzlp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gtuiydiqfv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gtigywkowa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gtthugjvzf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtzckageeu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gttuzeuqel.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gtfcvmpxem.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtutslipjo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtepntmgba.html


<!-- 参考信息 -->