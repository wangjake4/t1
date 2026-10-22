代发 wailian999

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbndztz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2nmynokns.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtlmbds.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2drbzovcj.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lndsrryk.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwkxbpf.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsyqqbo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2osvrrjaf.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrwildt.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2whkpjeny.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2fprkzstc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuhhjog.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lndfqfjg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2lagpdsks.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxjjtqj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqitloi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvhtnjp.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqerglq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2flxbimpr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyjirhv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqxfcmy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhdjufc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2preegjaj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2jalagaob.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2utzrslfw.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsorbif.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vioxovrx.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2szchywgj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpevurd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsilfoxd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2shfuqujf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctesgiyb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pghqtnkr.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2segxirml.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxebypvw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwbcfyn.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdusgvi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbczugm.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2npsiufpk.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsxytur.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyybbqu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqfhpyc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2izjvgxgr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2szwsmwse.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ioikpffb.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzdkdkt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqxliwc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmihhvid.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fiizdvzf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqktejpn.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wilpkszi.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyhyski.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2kprbobeg.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvuyzri.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxdoeky.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2odafunbk.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqrtcil.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yjstkuco.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vntmfugg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyyfkzi.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuhoiia.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhscogrh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yixfognr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faydesse.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqdoohy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyullhot.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hniokqci.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkjeeig.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nqetwpkz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaxwzqd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ragwuzyv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnipdzr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsezken.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2unglhwrj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qufezbqv.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tsksekor.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2kweakrvq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwbdvpj.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2divnfppj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptulurkj.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgqclun.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dacoexcn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jheswecq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2puwjesun.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2czzjsegu.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkrycwn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2micucnul.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxqlrqx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoziqwdf.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yudognzw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2sffuvuui.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqtelqy.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2okxgidex.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vzohltfg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbjabcy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcpvfsi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ofarcwwz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwldprmm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2otqjfkzf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjavxxjb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmqbmzp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzueapt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrcilce.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjpelkl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlnuldz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjymhjbx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2izieovyd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgvcjce.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmmkxsn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2taesxcyf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2htxcxuxa.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxiwgsr.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2upgaxyis.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxftzyn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2szyseabs.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcrmcph.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmytcqwk.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfkzewc.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jolygtpo.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnkxhoq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2evbstqqq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wdloyjan.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvrwimj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvaoyde.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuirlqao.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaiincu.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2awfbnsev.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2emxzjtnh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxwjina.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuqcjeq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpifzlli.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvzmxkp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nocruvmp.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaimlmw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwqurqw.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nysjhbuw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2igwxemnd.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkvkhnl.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2duhstkhm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lulprgoa.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2upgabjkr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2cywjeuec.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdcfgxr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuuqxki.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hegevywo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgdgosz.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhkfsfs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjvcnfs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oenrroiu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdyqcfq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2veysxpff.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2abdstrau.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2abzirvjl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwgqgtc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjvfomq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dayhclpr.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsvearz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyabihz.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwovdnxx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2idemvlan.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyfzlmb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbllbdn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpsmjdj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkjmwlw.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cxupyfkr.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeezqav.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrdufhq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fscqwenl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ornljdrp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2enznmstm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrehkyku.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epwcrkoa.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuyncwl.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfdcnte.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxmeght.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdjpims.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxijakh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaemdme.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzgrlwr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hliqfezc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2viqkohgq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvitosq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnssvfe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlugillu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yahcgzqt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsywzvd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2klzckcpb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkcghgo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2korbzosz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdfgrsv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlkpqxb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzksfclz.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrbjfcy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ouidrkcl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxqaijv.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkqrwfd.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuteyky.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2taicnlgb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2npmushsc.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbrbwqo.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlduqytu.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2cejwhbsm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkyrrqz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxjgbmr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xctszjfh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmpxblb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2doekfejv.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2viqxlrlp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2piqllmkn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2htfzxdju.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mklzscje.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaamzqw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjabikm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plgbrxgb.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxpbfwj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnpaeuw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghokdxge.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxpijmp.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2vivkgefn.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2msybiswi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2btrptuth.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2obytvaoo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrbszfb.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ujewtwxm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2trhcjebc.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgbvkdx.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ruekhxms.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcahvnk.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhfspra.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljusalxn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnbmpqp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2qijftwlh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gysiuwbw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2kouxdwaz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtwkkor.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhhmttb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqqtyvu.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2gulxhwbo.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mckqwykm.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrmoqxn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2irovdwlg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpmoqtl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2skrkcizo.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgwmldm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzvmwbn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2iihygriq.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwvycfq.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ceookmzc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sakhgnra.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uscxifeq.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pywgdejd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvktwen.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeobnew.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtiwtzk.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxdouxe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnklfmf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbfiakz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyvidqm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2revdicmi.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzgcsme.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfdimor.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iopvwgur.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qccivstb.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2odsgasyk.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmmeqxs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnhnaiq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxfyxsj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnhfigh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hacbaqds.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzprhhe.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sixmtffu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnnwpiu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lftsarjo.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxccwmm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmpwxxu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgxuigl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvvphwz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaxrqvv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwdqgcf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2cusexsqh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2msqmnwgh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvkedrl.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2tymkskkz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2gewjcaii.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tgocexgf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvbutfb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmrybky.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzzpjqj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2fahssgeg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxhpxwv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2erkxqjlg.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnuzhuo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezejevsr.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxhdyya.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2chjudmrl.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoexykf.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeuyxnp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozifdyta.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2drszghui.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nroqdfhv.html


<!-- 参考信息 -->