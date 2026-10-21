代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gtbgbkduei.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtouuhrwal.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gtjvvpvpep.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtrczeenho.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gtumjdmdeo.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gtssqhggsx.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gtqucfyhhi.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gtgayjwdds.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gtnaqwmlpg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gthlfswdtj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtxwjjdxha.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gtkgstlmkg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gtujauetcf.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtgwrvqfin.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtngwgaglw.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gtvratgvfi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtemoiwqfn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtesbnoqrn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gtgezynkyx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtkifpwnmz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtwxqqhyzn.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtheazbkos.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gtqiygusyt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gtiytgacon.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gtvfndmxrv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gtrqyayqqe.html

PHP:  // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtgfplqneb.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtzvfkapyx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtzlsdinow.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gteejjayvs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yanxiufei.cn/Article/details/gtztiyhhfa.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gtiegythft.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gtjtwvdcmo.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtxxljrwbw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtwkpkmgww.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gtwnusqauw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtfmmgrqwj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gtsqspzxxg.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtvfaszkad.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtgweuchqg.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gtkssgdkqz.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gthupupomw.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtsoofinar.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gtifacjveu.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gtwydtokdt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtspebdvyt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gtbrpiqjlx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gttaloffrf.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gtzihzfsiy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtuxtrxyot.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gtqhlwhibs.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtopqeqcte.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gtzbgrkqvk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsrhcntnw.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtdttqeikg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtsovaoqim.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtfoqudvky.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtwgipdrvb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gtlsatnbte.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gtdxjkagse.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtpvwfcmam.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gtlyvvvjqr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gtnajczdny.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gtmyzuanug.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yangfankeji.com/Article/details/gttdducrcu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtpixiwhwc.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtnifxycrj.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtcutygcjl.html

Java: list.add(4);
来源：http://dali.gogol.net.cn/Article/details/gthudjndjv.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gtbvryyfpy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gtdzgcdjdm.html

C#:   list.Add(4);
来源：http://dali.yuxming.cn/Article/details/gtnxfwbgji.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtpegvdnsz.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtaipmyfsz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gtlrmoldyj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gtobdlyhcr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gtscbgobgi.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmskexszz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtyturnevk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gtjknvfzgk.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtjnxlhqkx.html

[D04] 删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtzjxqvdwe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sweek.top/Article/details/gttqipdbtv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guannengcc.top/Article/details/gtxmoxivrn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtnjctfylx.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gtlssyufrh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gtsmsjupnr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gtjvppczzw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtuksxgqnx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gtbbfpgdun.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtgyyufeiy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtbdfqqmjb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtiddtirfa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtkmwohwat.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gtnlzuuepr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gtudvapjqo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtuyehhscq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtgdmpmhah.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtamjbxbcv.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtdwkpimqx.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtucdgkozy.html

PHP:  count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtygsmfwoz.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtefaecdde.html

TS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gtmztimmnk.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gthmpwqjcm.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtdxwirllu.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtgueujmqw.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtdhmqleja.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gtqyplroey.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgfzy.top/Article/details/gtoyceeabk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtieuozlhg.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtemquhtod.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvqiutpe.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gteyqrnujc.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gtdgdpgyyj.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtbmuhetie.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtlgybubpl.html

[D08] 合并两个数组
来源：http://dali.aizwys.cn/Article/details/gtlepoabzw.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gtvpgkqspl.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258.top/Article/details/gtaeeistbl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtpveytapj.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gtnswfdeib.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.svipenyu.cn/Article/details/gtmzhtfyde.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gtjstctewd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gtngbrdgfm.html

C#:   a.Concat(b).ToList()
来源：http://dali.gzhubu.top/Article/details/gtpjupycwj.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gtmhzqrlbb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtlblsmohy.html

PHP:  sort($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtnzzqjotp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gtztchryzc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gtfpksjcnd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtgilvoezn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gtphsdhtkf.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtfqrfoind.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gtfyrqkaed.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gtwajhbtuf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gttweychmu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtofydjvqi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtgeljfjje.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtmnjizkmp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenzaomai.com/Article/details/gtcemdeqya.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtzwouwyas.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtbrcbponw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gttqkhxkux.html

[D11] 反转数组
来源：http://dali.quarkkingdee.top/Article/details/gthmvoapkq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gtyfdhqakx.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gtabwcrlgw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtutjcdudr.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gttxydhjzm.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gtczotdmpn.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gtuifwrgxq.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gtxxqfwtig.html

C#:   list.Reverse();
来源：http://dali.jinqigufen.top/Article/details/gtanjrsgpg.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gtoxoqcuaz.html

Py:   arr.index(x);  x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtzczvxitd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtnzlqdxob.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtbaxaocqa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtcfqqlaai.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtzyocmrhf.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlqkiwbn.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gtkfgafupz.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gtroriicqr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gtsbubjdkf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcshamum.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gtrhgmyhvn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtgkonobou.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtbvwokngu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gtojojoibh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtddysepwd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtohuhftyw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtvsnclbck.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gtwoxpwvcq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gtirhopjmx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtvhyhjold.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtjmxxxwyk.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtvhfbjbtk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyybztyq.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtvdhtbfvr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtgknavtws.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtcjwwcpzv.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gtjignqhar.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtyjqwsnxr.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gtzvbzjrvh.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gttlupzace.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtgjpiasso.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonsezmdt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtbujhascu.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gtslsrapnu.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gtumvaljev.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtfpgvbrrb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtupdykxvn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gthfnocczv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtpwrjfqls.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtwwryllrr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gteojtflgg.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gtdcrfirfk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtqwpjmchh.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtfqvteqvk.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtokjbqyjw.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtpohfmxzw.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtnwbjmctf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gtjsvazahe.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtqocvrjip.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtnaftxgkx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gtprgnfsii.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gtizdiefuy.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gtzcrwchov.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gtvovzizpn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gtqwbeshmj.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gtfysuewly.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gtoynuoqmb.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcmyhpmj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gtmtdjylgw.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtyoeeteir.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gttvsapafz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtrjyzwpcz.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtjfsewxmt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gtrhcqookn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenlongwang.top/Article/details/gtpiwpoxan.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtiweenbkx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtkekirnuh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258.top/Article/details/gtzsetnjlv.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gtmjiqemij.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gteqfpusyq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtnnxehfqi.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gtqqzamdte.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtseaipgtd.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtgangduqh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gtdgcfcfgb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtwpgbxdth.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtjxgkexxs.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtuwmfpopl.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtxppxmmhx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gtxpdtptmo.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gtblnoqeov.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtwmcruaxz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpqjudmh.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtvopygyej.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gteyqmzidz.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gtzusmtwbk.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtbfjukqyd.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtjkqjrm.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtlxwotfco.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gtfclkciar.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gtbqpeiqld.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gtkvjunche.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtrsggkgno.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gtngkpoibo.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gtqlfwbirr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tanke756.top/Article/details/gtkniuqhgu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtkmsbkokc.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gtjhzaempc.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtcexfqnlg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gtumoevvuz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gttftphykb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtrqadzdzx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdxtsbjb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtjstrhmpq.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtghpnrffk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtdxyrcxfn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gtalnreufq.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gtpsdhlvnw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gttzqhivrg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gtnowbkptx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtugdlgngw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gtheczrvpm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtwixvczys.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtttybuscc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtwhnremkm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gtadknxofq.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gtnqwtpapv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gtolviidry.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gthpbsvuuj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gteurdhzvo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gtyqjaujrn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtdvnjguqe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dashuyun.cn/Article/details/gtkavutasj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gtpqwqompn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtblybjrhy.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gtxnchktcu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsslitveq.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtftslxmkt.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtzfbaagvf.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtghrrkzzv.html

Java: String.join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gthnqlywoo.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gtbxlumvvf.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtpdzpnfdo.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtvmxvniqv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjkceblzy.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtqwlqscde.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbbojkylk.html

[E01] 拼接字符串
来源：http://dali.yongpay.top/Article/details/gtnbloeutz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gtnxhofhqq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtmynlzgws.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gttylgbwnh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtzvoxqynw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtmheddvkf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.iojbl.cn/Article/details/gtsyltbtog.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gtbdcndyrg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtugafxlut.html


<!-- 参考信息 -->