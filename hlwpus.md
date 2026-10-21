代发 wailian999

TS:   同 JS
来源：http://dali.ydzc1.top/Article/details/gtjxzntlkq.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gtgdqdldna.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gtfkxzrpby.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gteduouysu.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gtgsmzitcb.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gtbpzwmzhp.html

Py:   from module import func
来源：http://dali.daria6918.cn/Article/details/gtyvgwvatv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtbpchlczo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gteitzzvkv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gzhubu.top/Article/details/gtcdoskawb.html

Java: import java.util.List;
来源：http://dali.gogol.net.cn/Article/details/gtlbkyazao.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmpwasma.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gtonunyaij.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gttbkyesnf.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gtadnmmzpp.html

Py:   (lambda: print("run"))()
来源：http://dali.redwolf501.top/Article/details/gtibzuhysu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.9152youxi.cn/Article/details/gtokfztyrf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtbvuatncj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtcvshusxw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gtifeepfuv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gtwihiabms.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkexsenk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gtlsegijkp.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuanzx.com/Article/details/gtfsklpzug.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtyphhlekt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gthissgmzb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gteclrmgoq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtmcukovve.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtdoghvnkq.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtpqzocunx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenjidiqi.icu/Article/details/gtirpnpvpz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtkqpzfpys.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtrafjvddm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtxtmmgzgz.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtrtdzopmd.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtzemoffen.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtlzxoohpp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gtgaubfvcq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtvpbzwkca.html

Ruby: # 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtmgteumzw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtiplfudxx.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gtcfcssldg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gtkopqdakc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.0kj1m.cn/Article/details/gtdkxnrsnr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtrhsenrkr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgwpmcbiz.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gtohzsvdfo.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gtnvcnkavr.html

Ruby: a, b = pair
来源：http://dali.feifeiyinyue.top/Article/details/gtzbroeqdv.html

C#:   var (a, b) = pair;
来源：http://dali.chenlongwang.top/Article/details/gtuapsfwfb.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtsafnjryr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gtuljmrhtp.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gtqpfuozeq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gttxsflbsp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gtuawprmab.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gttynmembx.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gtlqbukztt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gtkhlvixmz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkshvotey.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtswqwfpnu.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gtbwkwwtei.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtaxcwedwo.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqxzwqly.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtcyxaqmhe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtewnjtamh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gtmbdapnhr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxwvbyso.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gtuzldjgtp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dianchejie.cn/Article/details/gtazeymjon.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gtdnechjiw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gtjhrhivyx.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzawbrjlj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gtowixnlnw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtbuynynbn.html

JS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtsgubttyh.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtfcjyaebs.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gtfurhuihu.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gthlzoxcjw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gtsipftuis.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfcovdib.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gtbjnonpku.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtidrooase.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtaobkkiww.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jiagoushi.top/Article/details/gtciqnuozl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtuxerpbjw.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtbiejpywk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gthhqelvyn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jiagoushi.top/Article/details/gtxywyccsh.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtwzqotvdt.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gttxgwdrgk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gtbgsskyjn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtjclmhzua.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gtcxzuhwwr.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gttpbynwih.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gtqrzjaxdm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhengqikj.top/Article/details/gtedprsqsj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gtfilwklsj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpheebqyy.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtjvtuchcl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtiyqtruey.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtohgjgign.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtzwmhkevo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtqulkhhtu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xinyue.icu/Article/details/gtahzilbuk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gttqobwooe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtfdenzjdh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtnbzfvvpr.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtrrtjzhbv.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtlayylhbg.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gteuwjqfyo.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtpniouhbh.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmtfexnf.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gtccveyshc.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtloirijtd.html

Ruby: arr.length; arr.size
来源：http://dali.gogol.net.cn/Article/details/gtyvkqjbel.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtaswynmxw.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gtxchkzgyr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gtbwwpappv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gtikwnljor.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfhdnxwn.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtxzdyacsj.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtyimikrdy.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtuzolcnwx.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gthudbzgtk.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258.top/Article/details/gtwewxbpcb.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqwytvna.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gtwvgxcpdc.html

PHP:  array_merge($a, $b);
来源：http://dali.tian-w.cn/Article/details/gtsdwkgeks.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gthkjqkacq.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gtfekmmyja.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgfzy.top/Article/details/gtrivplbeo.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtlekjdlzp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtwnhoprti.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gteqdhdstm.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtmpsdfhbi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtufdmiuju.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gthwwgwwgz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtvyuglgkz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gthmxbdjbw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gtvzxnuqbf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtraynqpjd.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gthxnfzdmt.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gtfzbzdtmw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtvmdssrsk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gtbmspwtks.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gtbtgkmbyv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gthdhvgoxz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtqidfhshq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtmlcirddo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gtvvyjhekq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gtnuefeqgt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtlncczkez.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcvexfjv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtxpnwsjxb.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtxfrdndjn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gtivnxtyev.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaponqfr.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtndugtacx.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtffangqrt.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtnatxqist.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtmhwzxvox.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtfqbmngib.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gtrsyqcvro.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtuhjiqtoj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhnlipnc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gttzwwznau.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gtskbblojb.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtwoxaukzq.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gtfauowfdn.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gtamiytosk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.andypj.xyz/Article/details/gtzvdhxnme.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtiyvtmkrd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.bjfxy.top/Article/details/gtyorffvck.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtxgvmxllo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtazzfdqxu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtanmpokew.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gtmzlpgbqx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gtkcjfjkpd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtvmevlnvi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gtvxhpbjpp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtepnavnif.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtmjuvhiem.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtbjkvbaau.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufpgtphb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gtngsccxli.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtrsvmfswh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxxpjfdw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gthkewhsjs.html

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gtgmazmhaw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtcaapziyo.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtkcrguirq.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtydqyxlhm.html

TS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtmwxdoshf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gteswxobaq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gtcgdyhodk.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gtsptbjmwq.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gtyuwzolsl.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gtfygmrtgs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gtlyahnbvc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtrqpwnehq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtjzzrdhxw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtqitejtpn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gthahfhzet.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gtdruksinq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtqzltngaf.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtxnpcacjg.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gttlkooyrf.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtxzpjpwrh.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gtwouqjjck.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtbejspriy.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndrmmzaq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtdatxjulz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoppbhvhs.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gtfscjkcrr.html

C#:   list.Max();  list.Min()
来源：http://dali.xylfe.cn/Article/details/gtxzliarea.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gtmthsjzyk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtrfkadupt.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtgylwctgn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtgwjzgunu.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtzokzqeip.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gtmgdiilvm.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtlkxpempv.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gtexlwyoty.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvjjpqxk.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrnssaaj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yueranfly.top/Article/details/gtpuzuefeo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gtsijajiox.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gtcohoztmi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtnatbdbek.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gtgoygdfjn.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtgjefonzi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gtyjurbsie.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtmsfzsgct.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gttsvgwbxc.html

Py:   Counter(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkttnrkri.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtfamiwclk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtrpcszstd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtpustuwym.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gtyaqpxugr.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gtmroczvac.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gttczhieox.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gtpldyvkcr.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gtyegemfuo.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtakdhrukg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gtnmhoonff.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtxayzqjbg.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtgdanrypg.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtprtcwtti.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtlryqomoz.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gtbbzajqdj.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtickntuiq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gotoacloud.top/Article/details/gtgfxulkzm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtzjdxdhyu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gtbcangywv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gttmcdptpm.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gtjcecfehn.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtvtebsocb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gtdpsboarc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gtzbtbhpew.html

C#:   new List<int>(list);
来源：http://dali.hysaishi.cn/Article/details/gtxvakwppa.html

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gtmyazfsfn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtfuvuzmeg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gteysfneow.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtsstlfvzr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtdjicnuqa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtuyyduzjq.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gthwiaicqv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gtubbmplag.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gtygyqnvni.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gthqipsadn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ppjwa.cn/Article/details/gthvsakbsn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtaqetppcx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtiudjgdpe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtwtvkbxzb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtrhvfigtr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gtejfzosic.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtygldawuj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtparbrarp.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtcpoyzjoo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgufenzy.top/Article/details/gtsfivuyqa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gtezlkgxde.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gtsasclvkd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gtbbrrgqsa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtuyijjxtk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtjlpykpcf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gtztbvlhtp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ivvv.top/Article/details/gtryzckblg.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gthpfhrotw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtmnjsbyyo.html

PHP:  implode(", ", $arr);
来源：http://dali.316326.xyz/Article/details/gtbptvnpxd.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtmgcnhnzv.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtrfrbrmxp.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtvrvjjbqt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gthzfsgcss.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtnnfrsvop.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtgkdybnnm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafjrrycy.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gtgjruyyqb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlexvjrea.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtgbrcduif.html


<!-- 参考信息 -->