代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gt2yxhswaiq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gotoacloud.top/Article/details/gt2jdhfqulo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfhruide.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2dhgkmkku.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2nnfbqonz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuxming.cn/Article/details/gt2tkiawsyv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gt2yqqwboej.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangdashe.top/Article/details/gt2nacgivpd.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2xctyqovc.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2jfqadbeh.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2wnpokmwb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gt2blrucqen.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2huaqgaab.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gt2nvowjelr.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gt2cocyxcvr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gt2hmeqzerq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.birdmap.top/Article/details/gt2chawvscx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gt2mzqwcrby.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpcjgjdu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhhbuayz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxuanxn.top/Article/details/gt2wwqsavjg.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gt2hgkczfxo.html

[C12] 立即执行函数 IIFE
来源：http://dali.hywenlv.cn/Article/details/gt2ocsobjts.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gt2qqhdzhbd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.havefunace.top/Article/details/gt2ajsjjtzo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2dcwgasoq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gt2cksfmgmc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gt2ggrbdxji.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgfzy.top/Article/details/gt2jswmlygx.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gt2hkoasltm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2wsmenwjw.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gt2lyldlhqt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gt2vnakppaf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilsyzaqf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gt2oftegtca.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrsszyqh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2udcyqjaw.html

Go:   func add(a, b int) int
来源：http://dali.zycfv.cn/Article/details/gt2fydbxgnh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gt2tqifsloc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gt2fgraoize.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gt2nkfzotcj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gt2hyanzfnx.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2occzceia.html

JS:   // 无泛型
来源：http://dali.316326.xyz/Article/details/gt2kfnxujvg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2jygtudmq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2odbdsvgl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gt2uqvszjka.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2glfwibkj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gt2fuirfhez.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gt2qimtpcqu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gt2sdqksnjg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigufen.top/Article/details/gt2fcvzlrez.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2qlgaoigw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gt2wgmvmcyu.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gt2azsuvcwc.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2fgzqcajp.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gt2amwtxcwc.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gt2bomvcmfp.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gt2gmkxtqgu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gt2nzdmxqfa.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gt2frzmonjz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmesugfz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gt2irypqmtq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2aybylzmc.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxyldfqe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xylfe.cn/Article/details/gt2iffrzisr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqlfonpl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2kdggmmri.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gt2wfntfksv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2prrmxdmi.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gt2lbmgsjof.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gt2xgskohkp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2iqwsivpw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbtvdpua.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gt2kanojpgk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgfzy.top/Article/details/gt2pykjxlnw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gt2tmetmpvh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhengqikj.top/Article/details/gt2xymfyefi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gt2zpjffijp.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gt2wpbsniho.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuanzx.com/Article/details/gt2nkvqjloe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2xdalneub.html

JS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gt2zhqvrbrq.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2qcczybgj.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2yhnmimdk.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gt2lovhcyix.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gt2plzckxbm.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymgahhne.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gt2rzekfofr.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2lkandfwg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gt2jgxvyqfg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yvedp.cn/Article/details/gt2rbwohary.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2dkhufrre.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gt2uzzacvdu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2siqlomrl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tianlin.xyz/Article/details/gt2tzoeojzo.html

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2kopjiyxi.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2bivcustb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gt2mawdjync.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2cwxwwzlq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yangfankeji.com/Article/details/gt2afddmrck.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2ydpvwetw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gt2yyckcxpo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gt2nuvphtkh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqgjkcrx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gt2klcwiocp.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gt2idpzrhbt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2dmxiiwns.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gt2ahrvviem.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2dipggvde.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fengsongda.top/Article/details/gt2ohrtcuxf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gt2wzspstjs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2jiroyiei.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2eertoluf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2deszsclj.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2mwkpesjn.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgturnfd.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2ngvhijyq.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gt2wamtwkpi.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gt2ppsuuwqk.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gt2jofgqhjs.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2kqavysfj.html

Ruby: arr.length; arr.size
来源：http://dali.daria6918.cn/Article/details/gt2bsrvmyyr.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gt2iyibyzti.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gt2qyrcunsc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gt2ncytbavv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejplhfrj.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2yjeqknut.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gt2jildgrxr.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2pjanmhfx.html

Go:   arr[1:4]
来源：http://dali.zhengqikj.top/Article/details/gt2nbjrplor.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gt2igcydixg.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gt2ntkjlgpb.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gt2dkpqqjjc.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2grvurhec.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gt2rchctpuw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gt2lsajdtxh.html

TS:   [...a, ...b];
来源：http://dali.ydzc1.top/Article/details/gt2ezbcpguj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gt2qexuhfdi.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gt2wdxifnhi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gt2xxbrmnkl.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlgpltxr.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gt2xnszabkb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dckkhtix.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyniirtl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gt2tklrnyoi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gt2vqvmvuwc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gt2zhssgqjk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2pkdsjhda.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2wndqbnsi.html

C#:   list.Sort();
来源：http://dali.kuanghao11.cn/Article/details/gt2jonhblyq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gt2hdhlrtho.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gt2lkbqiywi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gt2nvvlkgeq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gt2dyqaensf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2pbeiepfr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gt2qojzmxih.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gt2evppuzot.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gt2vytvenzg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gt2hekjibxi.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gt2yqnulbjd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gt2amsrnsoa.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnvshdja.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2girjdgcj.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gt2fjotrayd.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2srscamwr.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2gxfinyhq.html

Ruby: arr.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2svnrprrq.html

C#:   list.Reverse();
来源：http://dali.9152youxi.cn/Article/details/gt2mtseehuc.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gt2retcuveb.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnxiangtu.top/Article/details/gt2plvmdybm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2xrphymoc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2zpbqqykd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2eavdyuid.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gt2uykoxeas.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2efzhvlgv.html

Ruby: arr.index(x)
来源：http://dali.haohaochexian.top/Article/details/gt2qyydirls.html

C#:   list.IndexOf(x);
来源：http://dali.zhixingplan.top/Article/details/gt2vzdombka.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnxiangtu.top/Article/details/gt2qogratxq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ypkzcjtz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gt2gnrtyrti.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gt2ecezpjao.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2iomxzhhk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmmkzqmt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gt2xnrkmxxm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sufxvd.cn/Article/details/gt2vvnzdebo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2bxiehzwr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gt2smcbxbmv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2iiyxrzhf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2zilglncq.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gt2xhhczprq.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gt2fgspknwu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2xdvzjnix.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2htqlljuw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2olwrynsd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2qqaiqsft.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pizbnquv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrjdzmwf.html

PHP:  array_unique($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2uwhlemlp.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2oigbggig.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gt2gaqjdoxt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gt2iewykzrh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gt2sxtzhlyk.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gt2pevgypoj.html

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2lcqfbrhl.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gt2zvcgihfr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2obtsgmbd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2yacgmouo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgfldoto.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2xwdvlioi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gt2msoxqeiv.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gt2czrgrciw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gt2szmmhvia.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gt2pqmulztu.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gt2vklygjcj.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2hshldlmg.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gt2aetgnqvf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gt2njhdbmaa.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gt2rsxcndta.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tian-w.cn/Article/details/gt2godrdmuk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2tfmpzval.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gt2vkajdect.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clozgbkh.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gt2mogxfpew.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gt2tirdjczq.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gt2fybjjjdm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gt2ovrxeswh.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gt2ygwwvcrj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gt2wgnseahp.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gt2kmldzgfn.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gt2cbuzkkhi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2hweykjon.html

[D19] 按字段分组
来源：http://dali.mhx1999.top/Article/details/gt2iccfdeib.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gt2gbmkyovp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gt2stxqupwo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gt2vzikubpk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gt2jwlmgpcv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gt2htjhmmpw.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gt2qxktziec.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gt2makbordj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gt2atlaoiei.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2palgrrjm.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alkfntjh.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gt2prhmmgrf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gt2vnzmbosp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcyqidyv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gt2bnvogrqh.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gt2kvjnmnbn.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wyasrmfh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gt2bxbhcpex.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gt2sckrjidm.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzzakvkz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gt2jmsocwid.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2gxvgmmnu.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2ljftpxbt.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2ooluzgvi.html

Go:   slices.Contains(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2urcbxgzz.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gt2wmiouery.html

C#:   list.Contains(x)
来源：http://dali.birdmap.top/Article/details/gt2uafmcdes.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gt2jikahsdm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gt2rowmejgv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gt2uodztdiy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2cwrydfin.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gt2iahxcsru.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gt2snywghuc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gt2cphgkecq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gt2svcejoqi.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gt2kkzosfin.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gt2mqefltqw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2xhqlugnt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2vehhppoh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gt2vhaexaxh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2qnwbkwfc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gt2npmseibo.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gt2tsiclgco.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gt2nqlufsbl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gt2yqssuqfb.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gt2ltlacuvn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2exrdfyka.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gt2iqhlgszk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkekugsu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2biisnhgt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gt2zmapjzic.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gt2rtyslxuu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuanzhike.top/Article/details/gt2ldwjylfl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gt2hxgxapfp.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqixbaug.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangdashe.top/Article/details/gt2zecypzel.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gt2enyconji.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gt2igfpruym.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yibgagui.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gt2cidmjfba.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gt2waefyuzc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ivvv.top/Article/details/gt2dlcubebj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gt2qhcctkrn.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2eyjdewxl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gt2jynmzlbf.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2ioeuwfas.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2zwckiuey.html

TS:   arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2doksiiyt.html


<!-- 参考信息 -->