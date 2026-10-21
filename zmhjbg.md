代发 wailian999

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gtbacjvcfy.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gtoncurhck.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gtqpafkaib.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daxiang520.top/Article/details/gtxrjmisuy.html

C#:   块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtdhbpyuqq.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtihbabgqr.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gteqddynnq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gtizvtxxzd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgnlwoox.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtsrfmmjzf.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtqdwvydrk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gtzaynqrpp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedagesnz.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gtcsucefbx.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gtlagmlmii.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gtigqpnfrj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtasbvpehm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gttygwhkag.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtaskfmqyj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpszdvgl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aibaodan.cn/Article/details/gtppwslhhe.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyluzcemt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtnzfkkgdh.html

[C13] 类型声明 / 类型注解
来源：http://dali.sxryk.cn/Article/details/gtqguprzfp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gzhubu.top/Article/details/gtlgptieze.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtubykvyha.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gtrujszgba.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtvkcgxjgg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtxvjzuivm.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gtxhdmbnox.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gtjzpugaau.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnzvzxiu.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gtfkpovqvk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzncpltz.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtkyvnbofa.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtqdpfzwhu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gtfbmmoulg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnslnygu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gtyacfyptt.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtjvgagghz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gtqnucohkn.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gtttwnzxfj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssxqoxii.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gtmrygiedj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtkmvsaekm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtuynnhqdm.html

Java: // 无解构
来源：http://dali.daxiang520.top/Article/details/gtdkpnjkvp.html

Go:   // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtbkqrnpuf.html

Ruby: a, b = pair
来源：http://dali.cheryme.top/Article/details/gtpvgbkmwi.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gtopgldpvg.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gtvwtdyzua.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gtzfudkqwg.html

PHP:  // 无重载
来源：http://dali.gaohongyu789.top/Article/details/gtknbweijx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gtxuhpwcju.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtbcnhsfyz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gtiyryvsyl.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gtxpecaxad.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gtfkvdtdoi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gtzudbvzvh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsodnpxyg.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gtbqerwoak.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdjfigezj.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtwssacxtw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkzhuebr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtxhwehyqj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtffcmnskb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtivgtvlze.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtvcasfcso.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuetiantiany.cn/Article/details/gtjscpgjhu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtwgmhgxdz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gtpjwdhwtg.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gtqhfudohk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gtfzmqmhen.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtensttavd.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtooquydue.html

TS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gttwywymkf.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gtwmwbgnnn.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gtebhemfje.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtihhycxkp.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtobkfqqyf.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtvkgqnopv.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gtnekqwhci.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gtgepxwlst.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guannengcc.top/Article/details/gtrnoxgyge.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.316326.xyz/Article/details/gtquifpsmg.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtxwtkzddn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gtptjbpgrs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.bjfxy.top/Article/details/gtuxcvqmoh.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtporkfbjh.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gtycfxucbu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gtsyshqrxz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtrtqzptfj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtwzetediw.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gtqsjltozi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gteydiugzd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangdashe.top/Article/details/gtfpdcrchq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtlfeccbxc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gtqvccplgj.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtxniaqqrv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtaerbzssc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtnwibxtse.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtmsdlkkyb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtxjjyyvwf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gtoyumoqae.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvflofaim.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtivqilska.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtzvpjolif.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gttuotsweu.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtvfpckdcq.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtwugnulhc.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtgkvrzvfq.html

TS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gthdgrdixf.html

Java: list.size();
来源：http://dali.zycfv.cn/Article/details/gtvwikpesd.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtbnrnbpix.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtkywtdbpi.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gtusktlvdl.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gtzascodzr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guannengcc.top/Article/details/gtcatdvwxr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtqiuyimhv.html

JS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtuvewavyn.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcibrigld.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gthnzwlpus.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpreqhmpc.html

Ruby: arr[1, 3]
来源：http://dali.jinqigufen.top/Article/details/gtqmukysmx.html

C#:   list.GetRange(1, 3);
来源：http://dali.birdmap.top/Article/details/gtztokwhgq.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gtgmnybhur.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxuqkgsp.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtlmakpoep.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gtufzvhtxb.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gtzxbpfuwa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtigdtabrv.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gtyfphkpbd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtdlkgtxbm.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtbvpamzbi.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gtnnzdkata.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtmdawmqxc.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtthdscmrl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hfpthk.cn/Article/details/gtlktbrqps.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gttusdbpxd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gtjrgccuji.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtyqnshiel.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gteppzdcmg.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gtabtazodr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtxawggeqz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtfszjgtuf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtazijdegv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtzqzvvwek.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtytlmhvjb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gthaikztdn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gtkvddvylq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gtfuykbciu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gtwnawefcl.html

[D11] 反转数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjaxfixg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tanke756.top/Article/details/gtgjdtmnii.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtoqfrbalm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtkzohaalg.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gtpwikshko.html

Java: Collections.reverse(list);
来源：http://dali.aibaodan.cn/Article/details/gtiqbwqfqm.html

Go:   slices.Reverse(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtifsgwyyu.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gtponjhabt.html

C#:   list.Reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtglkmmhyx.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gtshnmaeot.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gtijdckfws.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtzkmyarix.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtkilvvjxu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtmeqiwecs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgfzy.top/Article/details/gtqslrsnfc.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gthhaswlij.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gtkuveypcv.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gtoqckynfn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzyepqsv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtoejkpsoo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtgcrdkgaj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtnnsyohca.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtducdnsow.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtykpxtybk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gtcszqkutx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtslygpmrk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtoadkzlzc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gtdziutejl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gtcsokpjtj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cheryme.top/Article/details/gtbaahvoyg.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtwpyczwuj.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtrzqstrqv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtgudrbtqm.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtxxregkbk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtojgcmhhg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtkqfelwcg.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gthahokfbz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtmdcpbjwl.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gtrfhderyi.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtfddxbqlb.html

TS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtqdfqgbgy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuanzhike.top/Article/details/gtctjkokic.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gtkegemsse.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gtcgicncld.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gtbxitfjyq.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gtlbwbuksb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtrbzulagy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtmunrbeub.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtmhhphltz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtrumbvzuz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gtcfstuqpi.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gtxdfbeppv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtiqeaxexa.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwpslxej.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gtjloijhlk.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtmcugouek.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gtafmcfxme.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gtzvzokudg.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtetqqshff.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsrodqip.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtbhemeajx.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtkpzuiung.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gttrqhxpcp.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gtolyxvrra.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gtovwbtyty.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gtzhognnzz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gtwhbzmswk.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtfwmlwbxq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yongpay.top/Article/details/gtvjjoocdv.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtcctarrkc.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtvojizlgr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtwusfsdwa.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtiwixgnvf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfghatuba.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gtjebacwmd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gtkhualeaj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gthcjzkwkl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gtnewoikqm.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtmzjelctc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gtpcyhijok.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gteimcybaf.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gthwvzsvms.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtymjidjax.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gtzunrfsrh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gtvpmanzqm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtpnlrstwh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cucudq.cn/Article/details/gtrcwaicvo.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gttnnscxrc.html

Ruby: arr.tally
来源：http://dali.gotoacloud.top/Article/details/gtwfkrwhif.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gtdetmvhtu.html

[D21] 判断是否包含某元素
来源：http://dali.guannengcc.top/Article/details/gtvjmtaoza.html

Py:   x in arr
来源：http://dali.yuxming.cn/Article/details/gtlmalmoay.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gtzzpyabnv.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtntpolciv.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtfrfqtmcl.html

Java: list.contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtjpwaemts.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtorvvreso.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gttfcjzlnp.html

C#:   list.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtsnvwkgmi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gttxeqzjav.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gtqjuvsemd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gtttkptnkm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gtvcgmwrzp.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gtkodahttv.html

Java: new ArrayList<>(list);
来源：http://dali.daxiang520.top/Article/details/gtxmxhwdkz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dianchejie.cn/Article/details/gtspvzujue.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtebeprjrd.html

C#:   new List<int>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtizwvdksl.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtsofkznga.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gtobhhutvw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gtagapvijk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtwkcdnerd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtkmgiciwu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtzdopcxob.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtefqjkdep.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cucudq.cn/Article/details/gtjcccwhan.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtpgwezedw.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gthttgpntm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhuzrifi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtdbeotzmb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sysykeji.top/Article/details/gtdgpcndwe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtpcdebgoi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtrotzjldg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gtshirgape.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gtxzjwyucf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gtfeghhnka.html

[D25] Set 集合去重与交并差
来源：http://dali.nwbrower.top/Article/details/gtupcriwkb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gtcospqxke.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtdyudawsj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gttnisqjib.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gtxfxbtnoz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gtjsnstfed.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gtcfhogxwm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gtkesgbvjc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gttnuacdsx.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtyhtrbdhq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtgmwwnrtp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtoitoadpm.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwormnfq.html

TS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtmyfhrosg.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtkuwgjxgh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthythcqxc.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfltvlhf.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtowlkmyay.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxffaejto.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gtcoetmvdj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnikffoaw.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtyblfyqtt.html


<!-- 参考信息 -->