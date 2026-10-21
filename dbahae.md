代发 wailian999

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gtkamecmyy.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gtmqlnmxzc.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtfwiujinj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gtylyomddb.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtqapwsfzu.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gtmftnkcib.html

Py:   from module import func
来源：http://dali.quarkkingdee.top/Article/details/gtigldpqbh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gtayraodsz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gtefolqhbi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gtsouhnipp.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gtuqqvnuzq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cashguo.top/Article/details/gtikmyqxfs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gtciyzuudb.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gtlxygutqs.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gtvrmkoapa.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258888.top/Article/details/gtoybcxurq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbhkqgyc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtvytxlgui.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gtvfjdjvey.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gtdgfnasgs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hammf.cn/Article/details/gthheaniid.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gtewjiakhf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtpkwainda.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gtumynvlte.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtlmznnoyc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtjlodwyql.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gtbvteuwju.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtxlemqrqu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtavtlxpyy.html

Go:   func add(a, b int) int
来源：http://dali.c1oappe.top/Article/details/gteskhomhm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtavggvosg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtfgetpihk.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gtxbvprlev.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gtdglbquar.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtjychbaow.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtdrafcyth.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gthwgzqghr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gtufrhsoke.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvbehoyl.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gtiyctbqhy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gtfdausgza.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gtgwhzyulv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebfprkwl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangdashe.top/Article/details/gtustqdcwl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtobdvxxvu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtgrbedoup.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtmbczhehz.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gtpmotwhjq.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxonkhzan.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtkrfryvxe.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gtqmuvlmqj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gtkowteuhd.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gteqkbvmhh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gthxtlbecb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxsbqhrm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtazbrcoqv.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gtkdbzuydw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtsdfsqtvx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtprdjiuzz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsqnxyarp.html

D. 数组 / 列表 / 集合
来源：http://dali.yuxming.cn/Article/details/gtixdaybia.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttkwhcvlt.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtpcafttyc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gtuutnjczu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtrunzufzq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtvajqrmpf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gtavjsrlri.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgufenzy.top/Article/details/gtzvljpdqx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtzpcgkqxb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gtorzjnrhv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtyfgugfdc.html

[D02] 追加元素到末尾
来源：http://dali.9152youxi.cn/Article/details/gtovysgdbm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gtfzexqdwc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthburanul.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtrgwvtstg.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtjqytuzrl.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gtuecuwqre.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gtijvjgpyu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtjkutpcmm.html

C#:   list.Add(4);
来源：http://dali.guowangkeji.top/Article/details/gthuthspyf.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gtzpnkunvg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtmuzhfrto.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtlizzvsnx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gtdqwzjaze.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gtfllyanft.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifubmqns.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtqghmaxjc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gtyghsyumn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipfagpge.html

[D04] 删除元素
来源：http://dali.316326.xyz/Article/details/gtbyimcxln.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gttzosglev.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.mhx1999.top/Article/details/gtkrudgddw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gtiicbezws.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gthmlhjame.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gtpfowvssk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gtxbrlljax.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtaxhagawy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtgbbpxotl.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gtomvixsqg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtyohuwgce.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtbyqiahla.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtoxvapebx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gtxidueofl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtrftdeevv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gteiozztrl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gttumlzspz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtdfwwasum.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtcvndwhmp.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtxtrxxndf.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtntdrqknu.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtbddcjruu.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtznltrhds.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gtbcjlxjir.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtweuqyxik.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gtagwnmkon.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtpqsfclpb.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gtbvwptvaj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gtspvdulrl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtrbuivtjm.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtuzjezswf.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtfzrwjvma.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtakekgtjb.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtrsmsmsba.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gtxtzfhttx.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtigtzjwyp.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvxrxvpc.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gtponhrgvb.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtzdleyqmw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nwbrower.top/Article/details/gtqzkgiptg.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gtmyvmkjgu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gtktfyyomj.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gtvkhbhsuc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbemtiya.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtrfzhwxzo.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtyxnzkqzz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtfgcvbbuw.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtrruzihdk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gttelnnxrs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtwrepztwu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gtoujfllrs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtwjitpgci.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtwttfwshw.html

C#:   list.Sort();
来源：http://dali.zhengqikj.top/Article/details/gtwhqosoib.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gtbhwwbrms.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gtrdosfhkm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtfdibibsd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtjvnuxrev.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtouhrssnj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gtnoqnuxsp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gttykqrrgn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtxxxlittw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cheryme.top/Article/details/gtxnxqnqlw.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gtjyxvxmav.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gtvxqilpdx.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gtudaixnxq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gtcbrbnehf.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gttxhsjtmr.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gtajudyqyf.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gtgjnfdpyk.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtahddefbu.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gtmlvyatsd.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gtnecovifs.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtxhxmmvfp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gtvenuyqml.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtorqpalpd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtkungicnt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gtciwiexsg.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtjkwjiimd.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtlhqugdkx.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gtklcvejgk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtyzvuitdi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtzrnqwmmf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gtfmkisvvf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtlpkcshxh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtgevtevei.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gtgdwnhwsr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtvdqjofba.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtgfgpnzgw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gtnsbunoax.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtujrtcfnb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gtdtjuxxvs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtmdfnkjva.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gthomiiymc.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gthtkgscli.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gtwhfidanz.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtruslvbej.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtzuruuiuf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zycfv.cn/Article/details/gtsjaebids.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtjltyszha.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtkjshzmvs.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gttcyfuawj.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtoadcplgg.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtrlnobelw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.9152youxi.cn/Article/details/gtdzorvxup.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtxwwyfgjg.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gtpyuztvwa.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtsbexgdyx.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtdadcssvd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gtusktlbnn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoolltqqe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtxdfgspyv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtvkpfpkdi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtcfvuxsii.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gtxdruevtt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gtkapmkscl.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gtoihhscdq.html

[D17] 最大值与最小值
来源：http://dali.c1oappe.top/Article/details/gtxevpoejk.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtejcyrcga.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gtqyxnyjef.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gttkoaiiub.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gtebbddiyw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gtcesredgv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtzgyidovt.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtsvlmlzlz.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtwejrcnnq.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gtpklppxpn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigfzy.top/Article/details/gtfjqrfxwp.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gtanbpevdj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtzfgekwtx.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gtygpvodbs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtdtufyajj.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtfeaoxlrg.html

Ruby: nested.flatten
来源：http://dali.hammf.cn/Article/details/gtliucpzib.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtzfmlditx.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gtjocserbj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gthutjcucj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtalelxuip.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gtecgzngke.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gttafmbfcn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvfqztoc.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gtcuigupvn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtqewuvaxj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gteuimfnzr.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gtrwbropla.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtejzrnenl.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtlonbuyxk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtjcrmdvdu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gteypeejzm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gtoqcjclch.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gteewzllsx.html

Ruby: arr.tally
来源：http://dali.chenlongwang.top/Article/details/gtazkrtdds.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtnnvwadmt.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gteolsqkto.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gtcvcjwxkx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gthqecqxdx.html

JS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtlkwleyfp.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtpxfwqnob.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gtzynlpdoe.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtarlkqmug.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gtanzycjdd.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtzfiwykbi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtmokzugpa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljqcffny.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtmvsgdjpz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gtjwftcxqr.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtedwxmhdr.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gtwepazdtl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtolzlmrzg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtdplwzmao.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gtrdyjnclm.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gttstcfyrb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gtcrydcwzi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gtlcjjdgkp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoegxesor.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gteqwurmse.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gtydxrimnu.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gttgzxourf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gtdebwpkyy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtbiqsacjb.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gtvcugbqqf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtokfauixb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gtzjaoxfey.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtkjotxenh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gthxupgoxj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtufzwhctr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gtvdbvetwv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gtgxjjswpc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gtggbonttg.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtqsihnblt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gtyhpknkxt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gtgghkrbwb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gtnlbtxfpu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gtsbifnliz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gtvnjewspq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgvxgonh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cqqwz.cn/Article/details/gtkkwrhctj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtketpnvfx.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtbcynhhci.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gtndrakmxg.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gtagrydmjh.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtglouzcfc.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtkyosleuh.html

Java: String.join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtftbmvooc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gttfcihili.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtgjyzxytg.html

C#:   string.Join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtfgwdyqnr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzgzuiehz.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtosllnpys.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjsxmeikv.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtvabczmdu.html


<!-- 参考信息 -->