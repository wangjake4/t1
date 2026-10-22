代发 wailian999

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtgnjiebom.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtjmtreoma.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtaabplnle.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gtgorijqev.html

C#:   块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtznnpwbcz.html

[C11] 模块导入与导出
来源：http://dali.pycfn.com/Article/details/gtfkwsjped.html

Py:   from module import func
来源：http://dali.yvedp.cn/Article/details/gtcekxqlbi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pycfn.com/Article/details/gtwfdxgrsu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtxisvfvlj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gtpvzdrtht.html

Java: import java.util.List;
来源：http://dali.sysykeji.top/Article/details/gtebxwjzzy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gtjjvbhijl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gtdjqrgttw.html

C#:   using System.Text;
来源：http://dali.xuetiantiany.cn/Article/details/gtvuheihtx.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgufenzy.top/Article/details/gtmmgtpwxu.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtnvsnhlvx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gtmmirkyyv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtszxftwjj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtbpfajvoc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtyqqxchmc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gtzltpeudn.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gtewofscsh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtxnbjnqtu.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gttuchotoi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtdizqewgh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtalatwock.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gtakxgjtdj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gteweixupg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtfzlyejfx.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gtkwiptzst.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gtfpnijqso.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtmrnljypn.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gttqnkgxdb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pycfn.com/Article/details/gtwqtfgdvc.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtjfzkdrre.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gtikcgmsey.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtvyyfyvgz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphrxunww.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shangyingyoupin.top/Article/details/gtchlaymhr.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gtlpuamxsg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gtquzrnnjs.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspxhyqtv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gtvksmvnqj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtkrbrhsbo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtglzmmbxp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gtcguwhfpe.html

Java: // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gttlttdxhn.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtzjkszzrg.html

Ruby: a, b = pair
来源：http://dali.hnqzz.top/Article/details/gtzyazfgze.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gtzzsykakj.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtmfwpotgk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gtdrjorcdl.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gtwoxmxbcn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yanxiufei.cn/Article/details/gtzyvovbaz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtldrpxsll.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtzbhdkwpo.html

Go:   // 无重载：用不同函数名
来源：http://dali.sxryk.cn/Article/details/gtamsrcesn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gtulupqqqp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtxpldmvyp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gturbokyms.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gtdiqaltdp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxgodwvct.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgqpqwsw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtxhropksc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtefyxbhqp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gtjqeidnyl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gtuhhjshxd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gtxyvgevgz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gtrqdgqgxp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gtcnsadfsz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtytujrblf.html

[D02] 追加元素到末尾
来源：http://dali.9152youxi.cn/Article/details/gtmpadmdqh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhqjxyea.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtsqtqsgfd.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gthbnmxhwc.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gthriqnswo.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtjqwdivhr.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gtrplhtflw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ehwqpu.com/Article/details/gtasnkwani.html

C#:   list.Add(4);
来源：http://dali.dashuyun.cn/Article/details/gtxoqyloey.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gtxgygquft.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtgylszuek.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dianchejie.cn/Article/details/gtwdxluuem.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gtaidsgdfk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtriywuzvr.html

Java: list.add(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtcnrpjmyn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gtotstmjkd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gtxxeeiekt.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdsbiahd.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gtudwclfuu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gtvcebszhp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtmmsqqino.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtxjgcrbjx.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gtsoptfujd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gteinnycvx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtxdzgzfty.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gtsdnwcxyn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtggzrbhqo.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gtuxuuosmo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtxnpnhbsj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtrivvzrqi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtqusmmiyv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtprdbeoqc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zdqjudy.top/Article/details/gtgdicslsi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtoftsdtkz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtivoljphh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtynijrzle.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtnenktrpe.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gtczoalnvj.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqghitqcb.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtpmpqwftv.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtsepyohbt.html

Java: list.size();
来源：http://dali.guannengcc.top/Article/details/gtehtdjdyi.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtscanxhbd.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtniukaqkx.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gteyyuvdle.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtofrkikcv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gtevkacfsh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtimohwjcb.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtcwnoxrab.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtcqtafrxz.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtwlkatash.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gthnkvzups.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtitcfofeh.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtyajqbsau.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpmtbejw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtfsjnlibw.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtnzhniles.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtyvaihooq.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtzedhlvry.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gtsqucrqbb.html

Go:   append(a, b...)
来源：http://dali.wangdashe.top/Article/details/gthsvhakss.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gtbfqrnysx.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtkqftlmtf.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujtxyukn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtcmblqwje.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtpzwfzefl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtprkwdkhf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtfkvxgveh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gtdnqioead.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtjgfwrpwo.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnbxrbmo.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtrqqvzzac.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gtaejinzkz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gtqtheylws.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtkyifklkk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtbcweipti.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtdzienqmg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gtakejjwhn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gtepscihru.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gtuuxumwxf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtnqwvzzko.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gtnlodfibm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gtujedbwhx.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gtqwbapmpd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtbkgxyizn.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtdadixiyy.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gtkotencwd.html

Go:   slices.Reverse(arr)
来源：http://dali.cheryme.top/Article/details/gthitlpbnz.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gtqguiyarv.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gteztnehib.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gterbaushc.html

Py:   arr.index(x);  x in arr
来源：http://dali.sysykeji.top/Article/details/gtdwnjyylz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtbmcyyutr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtzjkjneel.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtsuostcsl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtuvfgnthz.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtvjdcccwx.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gtnmoxrqqc.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gttnmttiel.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlwixuvu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtklksctwe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gtiqoefxhw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtksimyybe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtaixtcnjd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gtxcxqrqgy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtyambftfu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gtokbensmn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtoqufnlrh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gtxynvqysa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtxqxpvids.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gtpdoxctwq.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtqmtroxhe.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gttnwxykeg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtmoksplfs.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtbypwuskg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtrkupofol.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtyszqhhtn.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtzzkxerru.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtikrtdzxi.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtgrabicla.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtrtcfmefb.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtzebqxuax.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gtofemlxlb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtzvoraumi.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtlzowhera.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gtszypyehu.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gtibbuzccb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtirdvgrfg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtjafclqyf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtqjfcctww.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtuydenfuc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtpwgvrphj.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtcrpmoqmv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gttjcjzxbq.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gtacjawsol.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfodyqas.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gtoxsuozrs.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gtcodkitpz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gtimxnvfbf.html

TS:   Math.max(...arr);
来源：http://dali.hfpthk.cn/Article/details/gtwdbmyskw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtltyjmlkx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtxkmmhozc.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gtbkdarcrt.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gtarddlmhx.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gtqnvjzwfs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtlsroqygd.html

PHP:  array_merge(...$nested);
来源：http://dali.sysykeji.top/Article/details/gtpdtzjlys.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtcwarzeqe.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtatsrkjnj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gttjfpyudv.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gtbulhuzkd.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gtnlijoeuf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtcjeknzup.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gtxaordohk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gtlthuacos.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gtvgnuagra.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtxrichmgv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtknqnxrgn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtyeawyjwv.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gtdluvbtub.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gtqbyjrpvt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtnbxeehpa.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtgqwrpkzp.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gtaodalgca.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtehvsvmum.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtlsryhujk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtcnoohagd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gtziihkpws.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtwcemhexz.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gtxyxntkjt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtwfjsvlaz.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gtgclojcvi.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gtciysrsok.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtwkwvilta.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtpyfvacei.html

TS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtasyvufcy.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtokxagwlh.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtebmimogm.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtkwybfjgk.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtynpcincj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gtbjiaitoy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gtgzdmadue.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gtcrmvbttb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gtweqrnczc.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gtlzqzseqo.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gtifjbulow.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gthgyalhnb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gtmbzhkgbv.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtjtakcszk.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gtchgexkfc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gtrghohzgz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gtzlsybdtt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtipizkuoq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gttwyuxbjd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gtwpuetsst.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gthxxjunbs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sufxvd.cn/Article/details/gtsfrhntcb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gtlwuwcxym.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gtshfkmhpy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtqcjmjunm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtpwdykcsc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtawfwaepw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gtolifznlu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtpjsfwoby.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gtqihuhnqr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gtwojvzkrw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gtchgfvafx.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gtenyujptz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gtuwlqtuou.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtugpwjgkx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cdnleiting.top/Article/details/gtdnxbvzhp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtcxisonxc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtjmbbexps.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gtesagognc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtqqtpkdwv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gtimjynhyj.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtqulyldkk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gtbzqmkshn.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuvsqklz.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtctlucysu.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gthnuiqquu.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtaikckjkh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gtkutlzrqk.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdsyfhyh.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gtsvmihgji.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdepdeghk.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtyvcgnweh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxrbtgfs.html

[E01] 拼接字符串
来源：http://dali.sweek.top/Article/details/gtzpswbiiy.html


<!-- 参考信息 -->