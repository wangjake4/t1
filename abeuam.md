代发 wailian999

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gtelmitcll.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtkdfjydcw.html

Go:   花括号块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtjerfccsp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gtlhnglyne.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtbspiymkk.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gtqkoeeado.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gtgvfalieb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gtbookodyh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gthbemfswm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gtwebkhbfe.html

Java: import java.util.List;
来源：http://dali.nanxinkj.top/Article/details/gtwpwhvlfe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gtjvigetme.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gtyxjsjeja.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtlenrmcuc.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtxxbdsqst.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gturkrgcoo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gtpdnkqqeq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtupnzrowg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtzgxgyokr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gtbpibnsul.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gtfmzyzleb.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtkztblrkw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuanzx.com/Article/details/gtvabbfdmy.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvuwkowc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gtmlvvotol.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtktubxsqu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.quarkkingdee.top/Article/details/gtminuvkfz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gturxfjell.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtdmwpxlvg.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gtqgqthhdl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gtbruuppos.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gteftsrzwv.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtuhiqmayn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gtasxamyeh.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtxkpbdvox.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtvttdtluh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gtbomgiiwt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstyzczki.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guannengcc.top/Article/details/gtyouvdalf.html

Ruby: # 无泛型
来源：http://dali.sysykeji.top/Article/details/gtpslopbax.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gtbhsgqkcl.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtrpzsnuaz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gtecgoigvq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gzhubu.top/Article/details/gtbzphtnjd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtnzlfbwod.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gtngidbbhd.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtyandywaa.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtudlbruex.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtkfirkkmv.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gttagpecav.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtnjonjmfs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gttpjicmfj.html

PHP:  // 无重载
来源：http://dali.zdqjudy.top/Article/details/gtkzmbckue.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjzecwlf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gtdcfpndfb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjkkyvqn.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gtmwbryqpb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gtflgklpch.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gtbvdhbepb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtknbdhzar.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtiuyhnqso.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvdmegsax.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gtsbqmjuxt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gteftinrun.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtsyvfrsit.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtidvltwpf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtnlmrsnck.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtopaquevh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtpgyqzkpl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aizwys.cn/Article/details/gtvdyxesiw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gtqmlaejvx.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gtjrbwfmlu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.redwolf501.top/Article/details/gttwszltgf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gtkwthhjpg.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtyawcfecf.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtbqjmagot.html

Java: list.add(4);
来源：http://dali.shuidangran.top/Article/details/gtmtapgort.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gtwelawrhu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gtpwmkxyfj.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gttycvzjsf.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gtzsruazvu.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtngobohpr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gtibbbqiec.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gtsumlhdeq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gtkzyxpmja.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtmddxwy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gttniyqudo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gtsuxdkjfk.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtmdetamck.html

[D04] 删除元素
来源：http://dali.guowangkeji.top/Article/details/gtkdaoeqbt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gttzyyupit.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtemfvndtf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtogtiknqx.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtwxsczqpf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gthlkplhef.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gtvbwwlzos.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtjojakbus.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gtsfsnqgov.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtlcdldggx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtwmpyidtb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtjotjhnag.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtuxyuanzy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtkhgplxtr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gtzecobxem.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtraojhbyl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnkqpqnu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtswaygsux.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtmjzqksxi.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtesrqznaf.html

PHP:  count($arr);
来源：http://dali.gzhubu.top/Article/details/gtzoqpolqr.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtrwhinwmf.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtuivhyrqw.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gtxvaywrdj.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtzscbjifm.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtaajeqsas.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gtovnsqrwc.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gttifdvtus.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gtizlziaeh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gtpmqnhbyt.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtkwjgskvl.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtifyircji.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtucxozxrb.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtwcqnychg.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtzyggluao.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gthxhwbcgh.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtpejytrie.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gtwgbpksoq.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtbshopwzw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gtumrmarjb.html

TS:   [...a, ...b];
来源：http://dali.hammf.cn/Article/details/gtcfniplmi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtmfjergka.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gtxocqkbkg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtijlahonf.html

C#:   a.Concat(b).ToList()
来源：http://dali.xinyue.icu/Article/details/gtngclptui.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gtuiftyrhk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtvtwmegry.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gthraxlrix.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtutgbdcom.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gtoddabxae.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gtvjmtznao.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gthhmvchte.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtykmprqqq.html

C#:   list.Sort();
来源：http://dali.iojbl.cn/Article/details/gtbvfcbssz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtxmvfgkvi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gtqprdcsxw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gtgqpilgza.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtjfijqlnz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtymdcdfuw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtzezvqcmg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gtabtyricy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gturdwxlpo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gttcprglda.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gtjqdgosil.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtzbatheeb.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gtgbivedod.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jyoumei.cn/Article/details/gteqdwlewg.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gtdopvmchs.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtsnrqwslf.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gtdxkdhvcv.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gtbonrwlyg.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtgxrxnnvp.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtlxpsrjxf.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gtcerejtxw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtzwpsqaoj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtcotjhaoy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtudohjjfx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gtozppjdzz.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtdpfbssfb.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtdqfpqqlu.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtbtbfoikx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtsxiyximy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gttytobkhs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gtcnmcsblo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtjdjajzqq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtlzqzjbkq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gtfvsfbujt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtgbhhzrps.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtafnrzmdb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtebdmhdsb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangdashe.top/Article/details/gtqsgujbjc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gtiruokxvd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtusxvxjlz.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtjafjfjlv.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtbvvcocoj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtgtslgljj.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtkemmhvgw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gtlsbobvme.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtioqwqgbh.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtmkvvdimj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtcrmdddxr.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gtnesyckmi.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtbxonrcjj.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtusqpcyhc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gtgrafsfry.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gtwokcharl.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gtxnlwbyad.html

C#:   list.Distinct().ToList()
来源：http://dali.aibaodan.cn/Article/details/gtclxbcqnv.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gthwcgqemv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtqkkekkvl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtskeoycke.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtqdyficjc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtmuokkhzn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gtcmzcbach.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtkrvdmqxp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gtzpsbwkbm.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gtoxcpbjfh.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtpmthdvfz.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtobynzclf.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gtwafxppke.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtdhsarzsq.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gtfismcvba.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sysykeji.top/Article/details/gtvbbjooya.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbhdbodq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gtjgjxayts.html

C#:   list.Max();  list.Min()
来源：http://dali.zycfv.cn/Article/details/gtajcdozgg.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gttrthhaos.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtwyabqyjo.html

PHP:  array_merge(...$nested);
来源：http://dali.cashguo.top/Article/details/gtcupgezmo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggqrswdg.html

TS:   nested.flat();
来源：http://dali.zhoulong.xyz/Article/details/gtmfckaiyd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtzpqqwvfw.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtitssponv.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gtvbnqyghl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gtuseispug.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtpuhobqsg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.c1oappe.top/Article/details/gttlyttauk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gtfithhstc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gtqmkzywth.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtzvlwkxbd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtnpjzdgme.html

Go:   // 手写 map[string][]T
来源：http://dali.zhoulong.xyz/Article/details/gtlxypakje.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtvzalmhzw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtcetkbtzy.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gtuhgkjylf.html

Py:   Counter(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrflxoiju.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtsqkoyshx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtvkcqcevc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtbscmthlr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gtcvllhstx.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtpcbdbnca.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gtdmqzrpmz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gtqqjjlank.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtyfiyftuy.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gtjxlpsxwk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.0kj1m.cn/Article/details/gtvyyrlxmt.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtwdjezskk.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtqfzuppkp.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtmlwwfesy.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtvcmhmewm.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtfyxtoehj.html

C#:   list.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtcdpnwrns.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gttsehecsy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gtalqacaqp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gtvqfzoxvl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtehwemzuz.html

TS:   [...arr];
来源：http://dali.dashuyun.cn/Article/details/gtukeqnbyz.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gtjyppsuko.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtozgmlcfq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtwyizzvpn.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gtheubkodw.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gtaektqyee.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gtlupbmucd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgaxfmqw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gttwingymx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtnjdtmazl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gtcmnlqfqm.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtjqipuori.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtxtjyoxog.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtpyvdwuvp.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtdgmhtgjr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtryiztxcb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gtzmixmykg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtzptlsudm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtxwlinucz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jyoumei.cn/Article/details/gtuhuleimb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gtrlrsstsw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtkvldkuuk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gtbtymzxov.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gtsnwqutia.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gtjfobxbpi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtvgzlytod.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gtdiqldfox.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gtpazkeopp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvreqgri.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gtoerqgryh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gtjqzvwchd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gttdvezkdp.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtlqbscnlx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtbwacalqv.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtjojxxcqo.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtirqzngan.html

TS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtbpvwnaze.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtxlwmkcbd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtulfgknif.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtzgwxmcdx.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtkbhmrmcc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsepzrkge.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gtipgfiwok.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtobqrcazd.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtgyisopxa.html


<!-- 参考信息 -->