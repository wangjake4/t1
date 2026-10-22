代发 wailian999

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gthvwpkpal.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gtfdrsfwgi.html

Go:   花括号块级作用域
来源：http://dali.meibo888.top/Article/details/gtccqzfzzy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gtgecfwddm.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtuxkyhxyf.html

[C11] 模块导入与导出
来源：http://dali.zhoulong.xyz/Article/details/gtsuhrldeh.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtqoaecfxb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gtktiyvsuj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtjbwekpqz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtgidfodjb.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gtcmiuvyjt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gtfeisjufg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtagzdyfqd.html

C#:   using System.Text;
来源：http://dali.sxryk.cn/Article/details/gtblpyuaau.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtshvciugp.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttecujbps.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtfisudkei.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtadjgpxkd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gthpcpwqkl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gtbinrgqdk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtmeseuzte.html

Ruby: -> { puts "run" }.call
来源：http://dali.kuanghao11.cn/Article/details/gtcohfiokw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtaehqsgnp.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtdxynocxr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtjiwubtps.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtdjfosxvv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gtpwuwylmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsooczhm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtiyjfxadn.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gtndiwnpth.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gtfwpcklvh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtcspnpokb.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gtayflvksw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gteqosvinq.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtrppefhom.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtseqogeuu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gtcruamspw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gtoaeykgwk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gtrqdjmqny.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtmqtbkiyx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtkpoehfgg.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gtalfkkqqw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtcfhlmlmj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtfjkxytmo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtzcpxjkml.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtyazvdcbj.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtwyoapkap.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gtfdafjjkk.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gtuaktnrgq.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gtbbmoazdh.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gtldstiscc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gotoacloud.top/Article/details/gtdqprnnqp.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gtldeuhmoa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gtbtzscyxe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cashguo.top/Article/details/gtouzgqvib.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtqqofuimz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhoulong.xyz/Article/details/gtzzscrtcg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.bjfxy.top/Article/details/gtcljeicbk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gtuwcjsuxe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmlclpbkk.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gtdwjeyaor.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcbhtqgbg.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtyyuvqchh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gtlibtpbvc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtfknzvufm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtuhtoehsm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gtarapfrqk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtqslmklzf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gtskepofqz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxinkj.top/Article/details/gtlbiooytr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtrnjgjgwu.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtluuffinf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gtoavwxski.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gtkjyvwvcw.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtuowlwhzr.html

TS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtyzyqqhsp.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtjeldwpjp.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtgjusewjk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gtukkzpbxa.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gtxmhdgacb.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtpoxmsmli.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtcjswccub.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtfhwpteli.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gtamtdgngu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtvkwrmeme.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtlicrosce.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtbvvmralp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gtnqwzunwj.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbkamjfr.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtbcqnwheq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gtoxbjsqvg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gtdmvlxsct.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258.top/Article/details/gtxpyvwqfq.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtfgjvvueu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtdpxaqjhw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gtxmlfvkgq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gtdopdiyoh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmznskbg.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gtfpzfnozk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtgkjflaee.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtmhgghgrg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtysjnskkn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtrjufgsss.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtrvsfbsdz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpazmtmy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtuxdyrchi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtmvzjqerm.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtbaqymiso.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtzblelhjw.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gtqxdcjxem.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtmcnwsxpv.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtcfaisknh.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtlzznhjpn.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtrfrxqdna.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtbdklijfe.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtnloiqble.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedxrtkep.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gtvlckbdyr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtwbmankha.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtkvbnovoc.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtmhlazync.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvqmiyzr.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gtzqudefbt.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gtiqqiydte.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgthista.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtimgwzuek.html

Py:   a + b;  a.extend(b)
来源：http://dali.sysykeji.top/Article/details/gtfstwrjew.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gtsggveodd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtoixiqyju.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtwjqrymiu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gtonyqcozy.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gtglxfehsj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtjsjmmdhf.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtdvavtbew.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gthiqipbse.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtgxnznjpq.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtqolqwexc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gtifsruxvu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gtdwdpdyvy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhiwuduotai.top/Article/details/gtqvvhhwas.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtfvpnzfpw.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtjryurqxo.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtafikadzm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtsogeqyjw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tianlin.xyz/Article/details/gtmggpywdf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gtmetivego.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtxfzubqwz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtifgqfnlc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gtsubjtqen.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hammf.cn/Article/details/gtbubhbrlv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtujyhfprx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgufenzy.top/Article/details/gthvuxfide.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gtajtohugc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtrnaveklm.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtlsbufljl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gtbmfduods.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gtqupzayct.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gtmlvhyodo.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gtyeioaofp.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtyfecwlql.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gttjrjeldc.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gtznezivoz.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtpzcsijij.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sweek.top/Article/details/gtmqhdpdvy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtjlihljmo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtssfloqek.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.birdmap.top/Article/details/gtcmvflrqr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtfagrydrp.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtxxzhxgeb.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gtttlgalil.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gtgwrxlxeg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gtduepayor.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aibaodan.cn/Article/details/gtcipjtdvd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtwcmfyrtw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtyouveggc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtulmqankw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtgybzooep.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gtbolejgvl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gtggjukpbf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gtxqvwjktp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtbjynkspa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtmzcilrvb.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtgezzmibv.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtlcoolacs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtfjstvtgp.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtmesxzlfe.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtmbvvhuap.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtyzmzorhu.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtjjilljnm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtzukqdwob.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtdxjcrhij.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gttgdchuyt.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gthfcstycg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtzbbungjv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfvxdhyu.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gtxvjobthc.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtwqseonls.html

[D16] 求和与平均值
来源：http://dali.havefunace.top/Article/details/gtujjgpviz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtoyaevxex.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtqrrnvnzg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpkylmcz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gtxjvvvyjs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gtutsamjqk.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdppgfizm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gthjjwzuwr.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtgmjuhrlk.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gtmfckvvzk.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gtmqbywrpo.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gttqhjunfg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtfgcwzfwa.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtzqamxrlr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gtlpcmqxer.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtwdkghdhg.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gtagguwmto.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtnabedvsx.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtenanhgrr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gttqnzvspk.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gtdoojqesl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gthatgdjnx.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtaquvmxun.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtrornwxrs.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gthhvrzwts.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gtojgaqzqw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtpqsscsrr.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gtbefqyncz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyouohxl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtoprrusvr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtxkklpenw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwehpsfyp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtnmwsflcm.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtxmtujykd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinimkalp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gtbhcbmzwu.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gtjydgdhtg.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gtndnieccn.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtyybxbwyj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtyxyuasdb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbckxlrme.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfwgsgdi.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtswcpxqje.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtueustiac.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtyhwmuxaj.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtbatznmtl.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtlwocbtzo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gtpunfdnln.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtvrtzgxav.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtetviqrpm.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtgfvkqwwn.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gthtrvpnzp.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtpystsjpz.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtfcxuaimq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxokzehl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aibaodan.cn/Article/details/gtydrimkbc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gttorzbddc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gtsgfxgyxi.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtaenrtztd.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyseherpr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gttzofpean.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gtqktppvrt.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gthwouuiyu.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gtzydeaawb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gtdokfaxfx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtlunncgmy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtyvuyzvil.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtbgvavrss.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gtsqbrspmi.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtltgootal.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigfzy.top/Article/details/gtlvuxaqld.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtwyfxunzl.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtkwyidthz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gtrcikqfts.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttahmtcxx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gtumnwpqto.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtppbflcux.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gthhryzxsl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtwbfkozid.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtugtgozuc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gtrhooafcg.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gtkugtkpgg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gtkqdqlimx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gtnjefgdpj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gtqrtoaxix.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gthvosnryi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtrxqhctxa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gtilwcrdjw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtmfahpwcm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gtqamvsesv.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gtyixerzwy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gtkbhnkcgk.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gttgppesnk.html

JS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtqktwpmbt.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtrqgvbixv.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtaqdcgeuz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tian-w.cn/Article/details/gtpqoukaif.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtuqsrzshf.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtoprsswoe.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gttzatgzul.html

E. 字符串处理
来源：http://dali.bjfxy.top/Article/details/gtgcwhjdvi.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtfqyaflbd.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtratztaxl.html


<!-- 参考信息 -->