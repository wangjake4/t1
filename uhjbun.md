代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtepcowbnv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjhwitnl.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtponibhit.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gtxoaxikau.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gtuuqwcayn.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gtvkvzaoga.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtqfmkolpw.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gtrmnfqgef.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtrxwmjsuo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtvmnzekei.html

TS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtcvjocxfc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gtqghnnxfp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gturcjnkfi.html

Ruby: -> { puts "run" }.call
来源：http://dali.jlsjyb.cn/Article/details/gtgvkfourh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gtfqzlbien.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtfctuafbn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqltalkgq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtpzhkycew.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gtahojscfx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtwaqqsole.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtkgouhwxr.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gtutmkygkt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrvfbqid.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhoulong.xyz/Article/details/gtldzkntfg.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gtffbqrwmd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.andypj.xyz/Article/details/gtmnguyfje.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtrnuixeqx.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtgvyveeni.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gtfkeltpko.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gtwgsfxstg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtawmhrkmb.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfpfovif.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gtvwvjqfae.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gthxsoylrl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gtelcnklas.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfessogvt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtdvdralfa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gtzgruxvek.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtynwphcvh.html

Go:   // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtjqvhozpg.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gtbbnafdoe.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gtnedzflqa.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtrseirsbv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.haohaochexian.top/Article/details/gtogqnkhgi.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gtapceyusf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizpgbuvn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gthnrbchtr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtwdqykfts.html

Go:   // 无重载：用不同函数名
来源：http://dali.xinyue.icu/Article/details/gtkndjjnvz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gtrbmmhlkg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gtctyvkmae.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpbujelos.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gtvuivovlj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthfotzkgy.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtuhmsjpnc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.c1oappe.top/Article/details/gtprvwydsb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gtvvahnkcq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gteqbidvgs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gtgngeecoo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gtuxeksdqt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gtnnwhkmvp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gtgwwzcuxa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gthcbboyat.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gtvxmvnnup.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gtzlavwkpj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtoidgetfi.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtuskpebfx.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtegtxgwiz.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtdtevcupf.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgfzy.top/Article/details/gtvtsskuiy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhengqikj.top/Article/details/gtednniotm.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gtfuowyxxr.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gtbbzaknij.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtutqwtfko.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gtzhuznfau.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gtxctomnxl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtpjlqedsc.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtetewcpwa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtkvjcuizt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gthxctixsg.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtvfwhvyfw.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gtzvguqzih.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtbhjraijr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtvmncqnqy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtsqzyehqr.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gtkyyerweq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuvmniih.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gogol.net.cn/Article/details/gtwqomradv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthinprvt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gtqwtblwil.html

[D05] 访问与修改元素
来源：http://dali.pycfn.com/Article/details/gtefhgdjhl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtkttmmzaq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtkzsvsvhz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtgnrazvda.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gtrdmstnpy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gtitbekufn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtsuocarsu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtryxkvkqg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtbmxkjaee.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtvaqlwrgk.html

Py:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtysnoffiv.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtwjikkycf.html

JS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gtcnsqlezz.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtnhuwkabr.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtpnnyfqpg.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtyhkzavgv.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gthluwzwbq.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtphnfphvr.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gtnelujjkj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtczrbhnev.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtrrslffmv.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtmekxkflc.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtugrrjogi.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtrdnaihdj.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gtqckisnuw.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gtohgtwvba.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtzdynjxnm.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtrnwzjwdg.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtvcagghzt.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtkrfnmooh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gtvgfzixlo.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtvusrkwrg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gtzkihdqhk.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gtgtrawsdq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cashguo.top/Article/details/gtpikjukwb.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtkthskyio.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gtnxyxyvym.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtrezemvud.html

PHP:  sort($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtpkfhvnfq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gtucrpnyef.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gtivsbzxcs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtvbeilvbu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtlcnsqqph.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtmowbnomu.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gtjdfydfao.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gtjyatteur.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtusnkqvpp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtiexxofgn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gtryncxgml.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtxlksiqml.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtkxqkajfb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gtqiwgguyl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gtcjhimcnp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gtqzrvovei.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gtcwyxxcwo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.birdmap.top/Article/details/gtleqomzew.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtgikelsgh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gtbsgpparc.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gtufuderpb.html

Java: Collections.reverse(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukkpphtb.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gtgwyujlfu.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtyaosiffa.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gtgvdbkflk.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtswxubeob.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gtkoxwlsfu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtcghyhewk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtuiwvqtyq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtfrojulxf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gtxbzjsagm.html

Go:   slices.Index(arr, x)
来源：http://dali.yongpay.top/Article/details/gtpooatszh.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtmtmihigs.html

C#:   list.IndexOf(x);
来源：http://dali.0kj1m.cn/Article/details/gtqifewroq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenlongwang.top/Article/details/gtlkhlpmiy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkhveapd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtqiakmlyu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gthxiepujy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtuqxvkuok.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusdnngtu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtukmvzyvh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtstchnjvw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtwondliqp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gtdxyrxnkk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gttplpcviw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gtzazruype.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtprpfylxa.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gttzuyqmqo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtacttcznx.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtrvrhwgpx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gtwdvlnilw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gthhqkpsxj.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtemkrxjyp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtohruffgw.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmokkddaa.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtulteeycr.html

TS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtgyusrqip.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtzusdppuv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gtdvcsnzxh.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gtixxmgjwl.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gtrjaaytxd.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtvptugxar.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gtxlvwtwqf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtyvlifdwn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtxshugxsi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtetaywxls.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gtgfbumxwb.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gtdtmzfttu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gtlwcawasc.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtfwmakrnn.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtpjjfcwmz.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtrntqvpoq.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlnkpfuz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtjnjgrkkd.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gtyokdwkre.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuurabeec.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtwdmaczcq.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gtwqdpigto.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gtshfmlfwy.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gtbqzxsbcl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtykbzsdjm.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gthqordbnk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gtdqqxqwjg.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtrosoerff.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtjgjvsanl.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gtnpgjyldm.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gthqffeujz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gtugqnoxay.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtbwlrkvju.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gttdgkoskq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gtyihrzpsw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gtrkwguhhp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gtpjsezoht.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzdvoimp.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gtmobjedls.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gtulaktvbu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hysaishi.cn/Article/details/gtvkuyymcc.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtiwcmqjrr.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gtkhuhsrww.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gtnkamzxed.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtapewivep.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtgcitgqss.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gthtizgwhi.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gtngtbabov.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gtxtzjpqnl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtsvfxauod.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gttadcoysp.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gttnvxhhth.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hammf.cn/Article/details/gtoyywjoid.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtlfjqlmzj.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtshbrvthf.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gtuupnprxm.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgxayglpr.html

Ruby: arr.include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gtpfnsdtud.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtosmchdeu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtafwuhoqg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtinrybbsp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gtzxdvrhrc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtfsvawnex.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gtzdfinfaj.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gtizwqwawc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gtueupcrna.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gtingyswyd.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gtnfhukwlk.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gtgvmzzmzy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxinkj.top/Article/details/gtysvzhuvp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtvaiftntp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtmxaosrcj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtviulczhc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gtqrvllypq.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtdgymqsvb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gtjgqunuop.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gtjrjpaisi.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtsgcxokvn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gtvafhgubg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtrdseilpl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gtlqluimjl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtwbjgsvkf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gtictptths.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gtzipvybrh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gtllunxwed.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gttcqhywif.html

[D25] Set 集合去重与交并差
来源：http://dali.ybcxt.top/Article/details/gtxafvfygm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gttyrwidjb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtaxlnvbjw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtejdrxgfj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gtrnstgrkx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gtlsghqqqs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gtozdivlcp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gtxblqbsvj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtcenbbpvx.html

[D26] 数组转字符串
来源：http://dali.havefunace.top/Article/details/gtlcjgognq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gtsbiqrhva.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtvjuzrumd.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvdscmwo.html

TS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtnozcqsru.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtrlwpenyd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhssduxf.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtosqokgdj.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gthugxbcnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtoxfsdxct.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gtmcarpknx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtuhaxvkti.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtqnmgxcyn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gtxvzwjqee.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtwknfimvl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtammysntn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtaoswjclm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gtwunloghw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtoiztsgkv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtjzzsahxm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gtuyhgdrqw.html


<!-- 参考信息 -->