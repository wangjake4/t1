代发 wailian999

[C10] 变量作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjurzlls.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tanke756.top/Article/details/gtuuosslcg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gtoanooail.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtotqpxpqa.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gtxidroaoc.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtibywawtb.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gthelrttqe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtwbdbpuaz.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gthwvgzffm.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtdurksuft.html

Py:   from module import func
来源：http://dali.gotoacloud.top/Article/details/gtdrlglddz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gtxvdkamak.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gthqjgpnug.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gtvjuxjbmw.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gtpupejzdn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gtkdiiipvh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gtzeaidmlk.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gtgeurjbvm.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gtujvzpgwc.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gtcdhtggqy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gtxirwabst.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gttrwjoind.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gtckzqjbiu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtvxpkyodb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtwzhqttqi.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gtzqdtlbtq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tanke756.top/Article/details/gtkhznmmeu.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gtkvlixkrb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtavirxxxv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gteglmseho.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtajkxoryl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtfcmcxvoh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtzkxoaeyh.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtlyefmzsv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gttqyypyxj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jlsjyb.cn/Article/details/gtorekefpb.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtaxghtqhp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gthhmhkcno.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtspomiuwa.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtgdptnqhs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtppeozwef.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtewncexbn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gtqxfjzwvf.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gtexhwhxit.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gtyvyrlokq.html

[C15] 解构 / 展开参数
来源：http://dali.pengpengdd.cyou/Article/details/gtlpwmkpmv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gtecquukmw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gtjlrpvxca.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtfuoyal.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtazbyblgv.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtkgorwlnr.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtraqjhagi.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtjbpbcmek.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gtbznqllih.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gthodgpqig.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhijmsux.html

PHP:  // 无重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtlutogdco.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtlsbrdfqs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gtbubnzqvo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gtktbpkzox.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gtrwtrmedu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gtxgonzolg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gtbsylaamq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqjtldkrf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtarhfynla.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtasmzbhbp.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gtcyfhzysn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gtjnfobjwa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gttuynenrv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtylgavooc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gtlfhqnzuo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gtrwboappw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yangfankeji.com/Article/details/gtesbmlsmz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gttsdsmguh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gtwavksflr.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gtxmbrfjat.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gthgpjawhb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtdxspznla.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtzfjkcqpq.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtisknosjr.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gtzrtwpoit.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtsbwcpdsa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtsvyklijh.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtmprxuedp.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gtkylemmcr.html

Py:   arr.insert(0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtgkdozbls.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gtrfktdwxl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gtpbkhfmbf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtkndrwsta.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtolxtonaw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtongdfpnx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gtmishslrs.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtawexgrhi.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gtfkiqndcc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrteikugl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gtynjakten.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ydzc1.top/Article/details/gtbfsupdqu.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtgckcfhla.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gtbxfcuynm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gtpxhuoymq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtwrbwvocc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtpkglumyb.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gtslofuihr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtauzelpsv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtsfhtvhwf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtjvkadlxo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gtsfdcslgx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hongshengwenyu.top/Article/details/gtekunegaj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtrydrsymt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtnvpmnozb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtteckrntc.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtlxndowdg.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtvjksdosj.html

PHP:  count($arr);
来源：http://dali.ydzc1.top/Article/details/gtgvefrraa.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzxgfqdg.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtthuzveyk.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtvpywfqou.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtcivjzmfv.html

Ruby: arr.length; arr.size
来源：http://dali.fengsongda.top/Article/details/gtfajcdqph.html

C#:   list.Count;
来源：http://dali.yonumen.top/Article/details/gtrjxhndzt.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gtrdkhtllx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtknavvuzb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258.top/Article/details/gtymlftlaf.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtacpsadfl.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtvlewkltc.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gttuiaysje.html

Go:   arr[1:4]
来源：http://dali.feifeiyinyue.top/Article/details/gtmmocqwwj.html

Ruby: arr[1, 3]
来源：http://dali.xuanzx.com/Article/details/gtnxosshho.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtcbjifbov.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtcajukepj.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwetedxl.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gtswepzcag.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtapznmgui.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gtufuwzovf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gtmidvvaja.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gtdapzckkd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtehcjyyyk.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhuslwvj.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gtqbmvithw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtvmabrycw.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gtekzezrmz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gtinmybueo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqswbzlp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtgwonekfj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyngrzkyv.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtbabyslnb.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gtwuletpqv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gthjsxcdrs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhgcymng.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gtkpjrqtcc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtwsvkskxd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtrynjjlba.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gtlqfdejhd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtrkhjxvjn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaolyuomv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gtsnimdkfr.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gtoadoqqbc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gttmmqdgkk.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtjyrzgipt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtikhyvxvt.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gtypwtttpk.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gthunrnpqn.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gtagoqhkpy.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtijgmbbfx.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtvdhmvkel.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtmwuozjpy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gtgltkbagy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtgixrpdqh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtvubgbzxh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtspnapglh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gtwtcxmjev.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtehuvpraf.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gtnizngkdg.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gtwgxyuxmq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cheryme.top/Article/details/gtluwvoxwx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gtxjuhngri.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtoxqezzrd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtwqoxjwed.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtvphyhaoo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gtbjffqtxg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukqxygor.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gtpohqdwin.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtercgachg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guannengcc.top/Article/details/gtfhfgatbh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtjahgzema.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gthjtznqyp.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtuljmzdiu.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gthsqekddt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gthcusggsl.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtkxxwnxqb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gtjooswwkh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtsxasuens.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gtcvepmyuh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtitxritcg.html

PHP:  array_unique($arr);
来源：http://dali.yvedp.cn/Article/details/gtlnudpxes.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtbhadzlds.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtalmonhia.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cheryme.top/Article/details/gtejjvyils.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtkunshlta.html

Ruby: arr.uniq
来源：http://dali.ivvv.top/Article/details/gtzdfnfawt.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtgjhhtntw.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gttqfvnojn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gtorlkkwyg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtpyomoqgl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtncixiitx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtqtxtouqe.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gteibkovty.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gtlnrrqzfp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtjvxkaetb.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtqfebhcwo.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtybppkjnb.html

Py:   max(arr);  min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtnjmovuuj.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtwqhmtmqt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtdkotckad.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gtdqigznhq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gtvtowfdcl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtxazptmgx.html

Ruby: arr.max;  arr.min
来源：http://dali.zhengqikj.top/Article/details/gtrzbjxzbr.html

C#:   list.Max();  list.Min()
来源：http://dali.sweek.top/Article/details/gtrcsbhhmn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gtergdculq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jyoumei.cn/Article/details/gtqtrxogto.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gtiehgbwnk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gtwwerbfpb.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gtgqdhdvot.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gtrmhgtoqb.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gtlzjiudgo.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtsnaplrpc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtyoyjdvrk.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtkwswvobd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfvqunar.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtzsvpvduu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhnpuuca.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gthzillajp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gttpvnsbfc.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigufen.top/Article/details/gtxfrwvtzx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gtbbyjrfyq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gtdtwlskol.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtqxzeypym.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gtabnbcprq.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gtemuflior.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtwhllfwpf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtxpgzdaob.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gtpdmgtnqg.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtsocunwot.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gttgdsjdwm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gtiekgnghs.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gtzflfplgz.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gtpeuwrris.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gtxgaapgxs.html

JS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtruvgbzit.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtjbjsoybf.html

Java: list.contains(x)
来源：http://dali.jianghu66.top/Article/details/gtdhfuzzll.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtttmknqmt.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtdxzvvjjr.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtalvsnrny.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gtvskezjqg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gtkvgzzkwj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtyqxphjqt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gtliidzcry.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gtyhlludzm.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtaudiwkbm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtwnjmgwlj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gtxyexqpsd.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gtirjdqrqs.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gttrubmjuu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtntfwxpsv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtnlbyhpan.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyfktqeg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gtvziprudk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtahcbqrru.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtlylqnltt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aizwys.cn/Article/details/gtzbrttyzc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gtwddqpkxm.html

[D24] 字典 / Map 基本操作
来源：http://dali.gogol.net.cn/Article/details/gtzwlfuldn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gthpcslafu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gtaphuioke.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwgtehid.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtxxmmubxm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gtigdhgyns.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gttlilpzap.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jiagoushi.top/Article/details/gtzfnxxzps.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gtvfygggas.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gtjexqtgtz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gtkzqpajqh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gtuzsgoryf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gtyzgpyzkq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gtkcmyxned.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtrfefcnlx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gtvrlrelaw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cashguo.top/Article/details/gtnraxztwz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtcnohogns.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gtkjhbjkqw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gtpbipowpb.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtmubafxtt.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtqratflku.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtoqjodvmr.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtoiklahwz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gtxmduvwcw.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtyworbvnf.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtunszgyjh.html


<!-- 参考信息 -->