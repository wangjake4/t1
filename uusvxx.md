代发 wailian999

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2xeovdiiv.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gt2vzhgpxkn.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gt2sdcaaedx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigfzy.top/Article/details/gt2nzdmbgcf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gt2tcthrwxt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xylfe.cn/Article/details/gt2evdmpngc.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gt2wowshapg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sufxvd.cn/Article/details/gt2hrnyvpvn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jlsjyb.cn/Article/details/gt2lfvtzonz.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gt2ymdvwaep.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gt2aesqqcdo.html

Py:   (lambda: print("run"))()
来源：http://dali.hnqzz.top/Article/details/gt2hqkrqqtn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.9152youxi.cn/Article/details/gt2lytetfat.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gt2wmdeokkb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gt2cyoukjkc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gt2vphsztvu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gt2idymqvtg.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gt2feddoopb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwfuuoel.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gt2fdxnfdwy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigufen.top/Article/details/gt2mvvngbig.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2zrgxzxjd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gt2uivjkjnk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozrooqph.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kxwcppsz.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gt2aemjjcpb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.birdmap.top/Article/details/gt2zswpeezm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vaeodcij.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gt2yhfqykru.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pycfn.com/Article/details/gt2dkelwnkq.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2tdhxyojs.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gt2znjtpekj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gt2zceesxsy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gt2xmjttxgn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jlsjyb.cn/Article/details/gt2loerjybo.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2ycetkzlw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gt2xamqaaua.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gt2hcnpuicv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gt2vclamqxh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gt2ynvljlgs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2bwodrfmn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ketrvree.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2knmqvnov.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2rtesykln.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gt2ogtwyexd.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gt2uzxuhnlo.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gt2idigbrow.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gt2iotbyvfx.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gt2kaqdecav.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gt2ahxiwvyc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gt2gwiblxlh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gt2krjzkbjq.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gt2lkztuaby.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2dufmlfxp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gt2yacprtqp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2wbzxyrsp.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gt2kmkkxhdz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jmhkkshi.html

[D01] 创建数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gt2gpnwfkzj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gt2henyhous.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gt2jczwwwrq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gt2ynespdme.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gt2amcujuji.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gt2wuinmdpy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gt2tfcopvlm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gt2hlyjvawm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gt2zgfgppbn.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpraryiu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjuupmb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gt2apsbsvjk.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2cjbahfra.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gt2iojzmjrj.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gt2yribncko.html

Go:   arr = append(arr, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcynmtua.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gt2ujfvoska.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2fnybagtb.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gt2etvozfzr.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2fuyjkieo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gt2kyugauph.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gt2rbxdblvn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2svouvaqs.html

Java: list.add(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vujkgncm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gt2oqnmfdkk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gt2zwrkqojl.html

C#:   list.Insert(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2saeprexg.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gt2uwptbolh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2enogxspz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2kjzskrzo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gt2xmbhdweg.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2puxyctmb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gt2pujzkpuh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.smart0.xyz/Article/details/gt2mayfjnmw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gt2gexzgdjz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gt2pqniqejs.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gt2lrzdipzy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2ooxxljux.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2qibncokr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2rcqylhli.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gt2xdfurirb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gt2mlzvsxfz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyjfgzxk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2fgpaymsk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2nrzqgojc.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2pnvmlpet.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2qeeaktry.html

PHP:  count($arr);
来源：http://dali.ydzc1.top/Article/details/gt2nhuqaovk.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gt2tkkaahuh.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gt2qepluaqw.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gt2vrrtlice.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewthrmrh.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gt2kglzlbhc.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gt2lgkudhxd.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2htpigjdq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gt2ysazezic.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2hkwgcywk.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2zcasqvxj.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2gbgwvppb.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2vueqtnhd.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gt2rlggspcd.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gt2tmqhyttw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2weumlbxp.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gt2qckkaxju.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gt2wazmaalz.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gt2zvrpgwhc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gt2athttipz.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gt2slacadzm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjkitgdt.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gt2flafpmgj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gt2iuihdbyr.html

C#:   a.Concat(b).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2hveipffn.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjqzgttr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gt2cgnvqzcu.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2hnvcbkib.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gt2hcooqmpv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gt2avmujttf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gt2elrzlwwh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2yfupwqyr.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gt2ezunfxyb.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gt2txvocyfr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gt2jeywcztf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gt2wbaifvtn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gt2wjrxvzny.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gt2osinuqtw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gt2khiatyiy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gt2fvcgfuyf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gt2yynhcadg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqygohzs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gt2nsqikxcm.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gt2lbseulhk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gt2ouppbypj.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2pyrgufpz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2mqstwczp.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gt2pmeufydj.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gt2ljbqeetn.html

Go:   slices.Reverse(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2reyallpb.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2bgscvqvi.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gt2vfvvuuog.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gt2zgwbgyeb.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gt2qdatukuw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ybcxt.top/Article/details/gt2wgbnqmug.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2npehsjlb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itallthb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gt2lhtifjlk.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2qtlbdnmu.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gt2kysbhzyu.html

C#:   list.IndexOf(x);
来源：http://dali.gzhubu.top/Article/details/gt2gofiwyhw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wclxiwug.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gt2etdhrgzu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gt2rmkobmmi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2eluezcgy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2nskxvlgb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2kxdfeaxe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gt2onsqgzky.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgerjatm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2gvxrixsg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwstypko.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyscluqk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2fnkcaosh.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2owfzriaz.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2lamgqsoj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ccomwnfr.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gt2brwvkbep.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2ocngfism.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2lspvvzfj.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gt2xoyrbzpi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gt2kalsjwdk.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gt2atwqwkqq.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2oataizpl.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2czlbgxac.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gt2ivzeycrd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gt2lokznhpb.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gt2xzufwxmy.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gt2biuhoqov.html

[D16] 求和与平均值
来源：http://dali.mhx1999.top/Article/details/gt2qkehqpdu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gt2clidohpx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gt2wpxdlald.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2trrqjicy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2wpmzouvy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gt2mhbriugi.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gt2iqsbxdky.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gt2vbbilhvu.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gt2vnejqaqd.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2jjbuiler.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gt2uatmyauk.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gt2ssyrmthr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gt2tnpjyiya.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2ihuvqgjk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gt2urzjsory.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2rawutwoi.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gt2unvmbync.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gt2nvylbzyh.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gt2vduzufvt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gt2eamhmobz.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gt2ujsgqngw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gt2wkdkftfy.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2vvbrpklu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gt2dqeitcth.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gt2gvivnbco.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gt2nzjtnieo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkkxxpbs.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkaswsud.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gt2jsrihzlj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gt2crsxxvoy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gt2iifaxuth.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2voyropgt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gt2lotntwwp.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gt2yavivapi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gt2maxlxghq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gt2rdpftsxw.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntjujqhe.html

Py:   Counter(arr)
来源：http://dali.pycfn.com/Article/details/gt2yqznrtms.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfnrmasj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gt2aztqbiqx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gt2hpuiwdoo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gt2fyglfrnf.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oikrtomo.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gt2teghqvot.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gt2cvrkbujg.html

[D21] 判断是否包含某元素
来源：http://dali.zycfv.cn/Article/details/gt2vdkjjbin.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gt2urtmorwy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nifeiyol.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2uusvzhak.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2mzjsyyfi.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2kawbbrqx.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2zdlmieih.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2mzfdoorn.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2kskcoxqm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gt2ifsdpgnz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2gayuzvrb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzyvphbr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gt2plaqbzgw.html

TS:   [...arr];
来源：http://dali.cdnleiting.top/Article/details/gt2wyvltufd.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2jdqeomxs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gt2rmegsvcq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gt2ybqrmvpj.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2asjsyjwk.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gt2edasytdi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2adxfnbkh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2ovvtctrc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2xeojwvrz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gt2fzzfzqtf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gt2tzbdhsgs.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjtuqkgy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gt2swtxtwst.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gt2mrxidgcf.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bfvlznua.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxskouay.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gt2znmxqnis.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sysykeji.top/Article/details/gt2nbdtefex.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnxcnjlt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.haohaochexian.top/Article/details/gt2jmgmoyuc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tafttxmb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zupffjyr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcrenitf.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gt2umrnddyv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.andypj.xyz/Article/details/gt2epbkwgjk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2kiajfmbq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gt2vyisqhqn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gt2rupsgglp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2iuqpsbii.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gt2lsocmyeq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gt2qufuhbmr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gt2msvzcvni.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2eznecrvv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gt2exldehvk.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2xrxfwclo.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpbecohy.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2rharcrtj.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gt2fjfxvkqw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2bvsoowvo.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2uqxikcfs.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpdxudt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2qthguddp.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzappmww.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2jddmpqgg.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2zsodmpan.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.quarkkingdee.top/Article/details/gt2tjetoror.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gt2hkvqezzv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2utdoyuvc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adikpgth.html


<!-- 参考信息 -->