代发 wailian999

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gtpdagqjri.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gtoopnuguf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtqhtyztcv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnqzz.top/Article/details/gtrvenvpnf.html

TS:   同 JS
来源：http://dali.sweek.top/Article/details/gtkdrdifuh.html

Java: 方法内为块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtmjnmlkdv.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gtpjcqzmys.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gtszpdtqfu.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gtiiwebmuy.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtkritgjbj.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtnplrxaqr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gtsibmdhql.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtcpoksmsu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gtwedelmmw.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gttfrvtddh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtvfcjjejn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gtxswkisya.html

C#:   using System.Text;
来源：http://dali.xinyue.icu/Article/details/gtczqoblko.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtfaqhtdrk.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gtesxdfpsn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtrbumljki.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtefssgjlb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gttptspjzq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ybcxt.top/Article/details/gtyddutjgt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtdidkbjjv.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtthnojhvl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtpajlhtbd.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtqdgoysyg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuypgzpqe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gttontbwnt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gtoqrrclib.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gttjdjjycm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtafnhauma.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gttejrglga.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gtanxemeax.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtvdeyraho.html

[C14] 泛型函数
来源：http://dali.jianghu66.top/Article/details/gtuffchudj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gtnlpsxrtn.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtsybzzyyx.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gtdodhzbut.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfsyvcbj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gthdoispba.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gtpdbpnhqk.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gtsrnawrsj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gttiqvzxxk.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gtxqivktoy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gtctwzeyiq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gtqnulfskj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gtspwunxhw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtxxdnbgsw.html

Java: // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtnzitgudl.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtudmmygfn.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtemybfiqa.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gtjgqjcjpo.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gtyqnuaqor.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gtibcgkqcr.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gtacyplgdf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivlnwpri.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gtukznmtjh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtueyotiyp.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gtlfahfqtb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gtfpcpgsea.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gtrvbsygxh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoiiwoec.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gttfjbfhmd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocyysvgj.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtezxeskpi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tanke756.top/Article/details/gtgjhdetqz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtlaykzmbm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gtmhfqklmk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtifhqqsej.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gtmsqjjtoy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gtqgvcjlda.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gotoacloud.top/Article/details/gtfrarqoip.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxinkj.top/Article/details/gtccxjubkm.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gtrkdalcgf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfieiismn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtzykyruik.html

JS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtyxwlwexr.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtlztjfyco.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtagxzfvin.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gtmnjngcoj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtsgastogn.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtuybcsemh.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gthjtfxgih.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfhfbxoz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cucudq.cn/Article/details/gtossaqusu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gtsgssabqd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtylujxbir.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtjbsotsxh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtpwhwbllr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gtbjvglkpu.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtfxvpzlht.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gthzmyymjd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dashuyun.cn/Article/details/gtcbtjwzhm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtwerkeaxb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtbtvspsmc.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtlalbgnam.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gtmmumufza.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gtxyvxfgsi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gthxnazlrd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gtucyuwrjx.html

[D05] 访问与修改元素
来源：http://dali.hongshengwenyu.top/Article/details/gtzsxcowzj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtktlvcnrt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtppemsouj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtbfhdbisy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtilektubw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtdrcunsmu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtyxfcxvjp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gthdpiozky.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gteclpmfim.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gttrtkttcz.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtgdxazuxl.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtkxhpshwu.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtyuejhwvj.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtctpevujz.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gtlhirilqr.html

Go:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtxxsbhwbf.html

Ruby: arr.length; arr.size
来源：http://dali.tianlin.xyz/Article/details/gtqlyfpcjc.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gtultlxqls.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gttbqgpigf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gtuqxidjpq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtnklacwxd.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtqlgshtjo.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtjvltfyij.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtmjxxlhfq.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gtbtvpioyt.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtcbazogfw.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtqfaybajf.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gtsweamapv.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gtdomajjmm.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtmlphvmhm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gtlvsdankh.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtqryfjplf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gtgkbmuxjf.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gtimfohcrr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtpkohlnnx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtdvcwqbhj.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gtghjndmij.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtbrwdbmvp.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gteplfxpqc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gtpbgjvgum.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gtbkdrofdq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtjxcngiff.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtzqftxhcn.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gteelvjueu.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtalqlqbjb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gtjzyirpfn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gtvjfeqawl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gtobeljuen.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtmmiigsii.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtnlfvacre.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gtlwuhealf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaihgvdx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gtpdjvdxng.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtdslmuwiy.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gthplzysyd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.kuanghao11.cn/Article/details/gtbnpjlrqt.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gttvxdzoom.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtxydcnllq.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtfdubusib.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtmjlfddin.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gtmrlesawa.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkkgdagt.html

C#:   list.Reverse();
来源：http://dali.9152youxi.cn/Article/details/gtpjjjgbzy.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtnvxjbuzb.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gtwymqrimm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtvqgjnswe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gttvvjglku.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtgsfxcbmc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gtjgamznnf.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtpvmcwdet.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gtbwprjikm.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gtpedxgfds.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gtqrcmcedp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgntpbln.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebuimohc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqbfxtzz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtvqhefztm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtzynjrxuo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtzrtnkmtn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtpqgbtgia.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtsnslkmxp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsarwuiwi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gtaomdouib.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gteatjnrku.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtqtdwpbzm.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtgkswafsg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jiagoushi.top/Article/details/gteexjtzij.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtbvvrxaav.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gttotyirby.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtyysmhlid.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gtsxcgvzit.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtjmmyonmr.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtvztddfyi.html

JS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtveedleve.html

TS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gttfvjoqvp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gtmgomnxyx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuanzhike.top/Article/details/gtrftskefq.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gtgkpgpuqc.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtshixoslp.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtputpobfk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtgjetbrxh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gtgrkmzvqc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtyikugnzg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzoczqdq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtwrlgjvuf.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtxdsfftwd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtnmsdlhpe.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gtwpgqkttg.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtxuuekvhr.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gtkyybhnxp.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtokztdwuk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.meibo888.top/Article/details/gtwwduqzsx.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtitbdseal.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gtiwbejifb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtngzhdzsw.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gtxlealobu.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkoplxlju.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gtrfdejgix.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gtcywfljra.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gtbljdjpgf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzbekhyk.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtjyjhypqr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtljktrsxg.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtoizlvixx.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtxtijcyze.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtqqsupfpp.html

[D19] 按字段分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjldzrcha.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtmoxykmei.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.0kj1m.cn/Article/details/gtxlconyew.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gtfpfsncmb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtldkqhzmx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gttdaeahyf.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtuecevbmz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gtddzirdbw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gtookabizw.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gtwayncwkf.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gtuxozgddt.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gtsbsqbbnj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtczvzuwso.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtgyibwrea.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gtgmqtnduh.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258.top/Article/details/gtmdhqqmls.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gtybovhdvf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gtslrjcjye.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtmgfeigpo.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtxfmwtdni.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtlkgrhmew.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtcvvmczau.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtfnlhnhnh.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gtkrbnmivf.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtjtebjlhb.html

Ruby: arr.include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtxyijpepn.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtipglxseb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gtmzjqnjhg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gtncmdpetu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258888.top/Article/details/gtachvxkav.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtddnspjja.html

TS:   [...arr];
来源：http://dali.feifeiyinyue.top/Article/details/gtcltwyiaa.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtrmcesjme.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtlxdzcanq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gtbinjdypf.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gtuodgoxob.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gtconeeeth.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtmpzvqocu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtogboohbh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtylunoyae.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtpytdyjea.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtnivjerdw.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtuaqhehah.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gtybkvdlky.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gtjgnmrvvp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gtuxbpxklv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtbzybzakc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtyjvhuyhg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gtjyrpboqc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gtkrjhulxc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gtvowworsz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gtomnwctph.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrsfzsui.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gtqfncjavx.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtpswqjwjo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gthyfdevhi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gtcydknivu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gtgimjnjao.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dianchejie.cn/Article/details/gtispaemfx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtljhgukrd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cashguo.top/Article/details/gtybwntbtx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gtxhittzmr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtxaoinyhv.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtjdbwounz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtndnthgca.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gtxbqecxas.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtwbrjrilk.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtfggwsdoq.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gtcojznmui.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiujvikb.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtwdrdnnml.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtgnmfzrpg.html


<!-- 参考信息 -->