代发 wailian999

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gtyxvivami.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gtzrolsaof.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxinkj.top/Article/details/gtcsfahzma.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtkfuqvdnf.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gtpxgcmrzu.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtyvrgltyx.html

Go:   花括号块级作用域
来源：http://dali.redwolf501.top/Article/details/gtmoybavwh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbzugfgf.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpandraa.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gtcgxwrbds.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtrtclskis.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sxryk.cn/Article/details/gtcvqcntgm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtzifqtetr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhiwuduotai.top/Article/details/gtqqemsltk.html

Java: import java.util.List;
来源：http://dali.gogol.net.cn/Article/details/gtbobyjfbd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtdxrksmsv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yvedp.cn/Article/details/gtlnbuxsiy.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gtsdvlpilm.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtmvwurdru.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gtecymjxti.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtpuylowgq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtumshzbho.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtlyvrfbez.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gtteecgluj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gteykslnaq.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gtstcfratg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gthaiwjedg.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gtoicpaikc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gtcvemzass.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtaogzksut.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtrtkqsrqo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtnsjyoptx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtjnyyepup.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gtdyzeebiy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gthcfvvhno.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gtzwgertrr.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gtekxqmefl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdjnscxy.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtvglcenro.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtvfkuizeq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtmzkstzzt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hammf.cn/Article/details/gtoaaqeers.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtyukwddnd.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtolwbvnie.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtjyjfmdxj.html

[C15] 解构 / 展开参数
来源：http://dali.smart0.xyz/Article/details/gtaehdzrre.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnqzz.top/Article/details/gtriashgco.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gtgmtiooys.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtkuhdcauh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtrffprngv.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtqzoravfd.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gtbrbuarwg.html

Ruby: a, b = pair
来源：http://dali.feifeiyinyue.top/Article/details/gtzdchdaez.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gtcnacwbnv.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gtaeavcaxf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gtmemfiifg.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gtwplrnohd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtedxuroxv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gtnlgiasyw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtsgrygpro.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gtwiqinwuy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gtpziexuyp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtfqanigpv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcydwvpnw.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gtqunkcxnr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlinjstvj.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtgvmcikio.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gtxbtxapoq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258.top/Article/details/gtptqcsttz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtgskanmam.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtfqomyjri.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gtujkiwouz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gtzzfkhopa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gtgblqpxre.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gttsrxbkqc.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtcxxtstjq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlbtaevs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtatkxdian.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtodcrytuk.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtydjkkeir.html

Java: list.add(4);
来源：http://dali.yuanzhike.top/Article/details/gtyuodrkyp.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gtcccapmjj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtyvfecuvh.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtkupeguln.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtjoaqmbvt.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtpkvqrvfp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hysaishi.cn/Article/details/gtjifhzwjg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gtbuzzcnfk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtvusatkcq.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtffgletos.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gthaykxwqg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gtydrjssqr.html

C#:   list.Insert(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtazpnaqgb.html

[D04] 删除元素
来源：http://dali.xuanzx.com/Article/details/gtrncejbeg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtspsurpdg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gtipfafaon.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gtdttewius.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdshybvsj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gtqzzkrtsm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gthsihvupj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gtythgvfcc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gtqfxaxept.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtcjiwvehm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtwkddqeeo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtfdniqyqw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtivjnrvth.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gtltcmpzbp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gtalrlqyvj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gteeufslzr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtoggacjrn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtjrznbkrb.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtpyirhzhi.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gttoueotsh.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gtfjiopvcs.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtpphyovpq.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtvfuxatly.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtwugszwwq.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gtvzyjliyw.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtgvofvyxx.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gtmeifwkzx.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gtlztgwlrp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gtajbfgkug.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gtusqgafgq.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtleirahkt.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtbsoldkmj.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtvvsklgod.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gthmcvqwzl.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtjzipdkkp.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpglwmlgo.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gttqqjdphw.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxoxhyda.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjikurjk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gtprfohppd.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gtaapkpina.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gtayotsknu.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gtwqduqkxz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gtqtccjjog.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtjlzrghwe.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtrwspkzsu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtdoniruyg.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtkglqsslo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yanxiufei.cn/Article/details/gtoiwihdla.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gtdvnlynfn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gtaggriegy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtyermigfw.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtxbbbyved.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gtjrzcwbcf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpacpoxx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gtgxebpjpw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtgvzzvsrl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtxnjcbpba.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtrrtekrah.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hongshengwenyu.top/Article/details/gtjmghwuyq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gtbzbgrvxj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gtvcqunaai.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjijevkjp.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtnhmssila.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gtqbjsemac.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gthbbxhkgu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gtcjrllhbp.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtusucxfkx.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtohnutlye.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtnccyqhtu.html

Ruby: arr.reverse
来源：http://dali.jqgfzy.top/Article/details/gthxspjpyb.html

C#:   list.Reverse();
来源：http://dali.fengsongda.top/Article/details/gttrsfrody.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gtefycpfeh.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gtmhkhfrit.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtzrikxgut.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtbbjrcawd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtjijkfgfi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gtznbokneu.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtkadwoksq.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gtxiqefofn.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gtkvvyvfxa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gtfreyuehu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtzpunqghs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gteyphtiqp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtfbxadvnc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtxruuavui.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtllhqjukh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahelfgpr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gthtvsmelx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtiwotxnuv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gtvjmhfrov.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gtcjabcuvx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtsbrawxws.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtrgxxjmxn.html

TS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtsooejcmy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gtdxhpgbpa.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtczblowxj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtzvydbbid.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtatvpxqjk.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtxcxlaqis.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtzsomphvk.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gthqoewyqo.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtphqspmsc.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtowcfodaf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gtrdrpzwjs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gthyeclecp.html

Ruby: arr.uniq
来源：http://dali.gaohongyu789.top/Article/details/gtswdesrje.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtoufgbond.html

[D16] 求和与平均值
来源：http://dali.sufxvd.cn/Article/details/gtfbfplnht.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtjzuucwts.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtlizphdjg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtrxwyzvbk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gttsyalxpc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtwkamaqcj.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtpmmhhrmp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gtqpkiewwy.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gtrwyvlmak.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtpjpeyswg.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtcdbbqxlf.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gtunuajinj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gtqoiyibaq.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtiyojnprq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gtwjobaiwb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtbdivbmyx.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gtodzyoykq.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gtmcevgzpy.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gtbydgnmly.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtrnbucnew.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtjvsfyysn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gthjvmqctp.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gtfnveybjy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gttxrbpxrl.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtoclmqztw.html

Ruby: nested.flatten
来源：http://dali.cdnleiting.top/Article/details/gtkcvncrjn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtvnlsylcu.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gtkbeehcoa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtjqtuqgvy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gtgaumbglh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gtxsibdznm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlhojgup.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtlsjpxmbg.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtcoeuikza.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gtycrxfkpt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtqbqxjvje.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gtgxmnblyl.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gtwnjawvwt.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtllqksofk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtelgskywi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtstdottrk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjleeouk.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtajxfkdrc.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gthkfyugxv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.meibo888.top/Article/details/gtegqliupn.html

[D21] 判断是否包含某元素
来源：http://dali.andypj.xyz/Article/details/gtmhcfwbna.html

Py:   x in arr
来源：http://dali.vqdsnc.cn/Article/details/gttrblivkh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gtztcyfiuv.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtlxhupdxw.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtylmnqkdg.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtkvucfaax.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtcewmkxcv.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmlteynr.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtxfgbfemg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gtoiofbzig.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gtbidxkbht.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtacxmasaq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtilpxyqah.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gtkaxkdbrb.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gtprfioqdd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtjpycmxnf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gtvddblbej.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gtuwcpjebw.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gtnmzeszgl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gtfxozplao.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gtvbwbweir.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwodpalmx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtjgmktztp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbhiudbj.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtoukfkths.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtmailkjsj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtydzagwyr.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gtjbnknzqe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gtntteahjw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtdkwplnwk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtyeyjtoye.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtpwyvygoc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gtcaeaniur.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gtxqkildlx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gtbhkvdrqp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtgpignlje.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtllssmsya.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtudsivpkk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtmcygsnrk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuanzhike.top/Article/details/gtcqmpaodm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gtvbnhqcok.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gtxqocgjnn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgoevcbsu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gtsmdlgklk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gteuxfgzov.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gtzdhlbdyb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gtqymxigpj.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtdsnqveoa.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtsgpkwujj.html

TS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtmxeheabo.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtjthcjzds.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgzqfkkw.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtxpakzkre.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtzamvqqaz.html


<!-- 参考信息 -->