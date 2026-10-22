代发 wailian999

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuxbeek.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nareroxc.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qegcwusb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2jofjfiqa.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdtmxjr.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rvglksem.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzgenru.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzdkooj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxyxlbe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrgpdov.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2gghccxge.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2owlaujvk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2urszlfkh.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2iugerein.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2wfazocwj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2olorlmvk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmiwapq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2osfdbmfb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmsyqnq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrazelm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2setrymld.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpuhjvu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sriglpzh.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2gyblegzp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lcynqebx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzffqli.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzazvikm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjqwsxv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgejrxa.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlxrfbm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2blqzoard.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsvhrbg.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjsxymk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2usohhqag.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2razqgczh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtoqcvy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pobsbvor.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaeuagu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uriantih.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2alnwwspu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2imkllghh.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxkgrkn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbsrxgs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwmukrw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzycaync.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlxgcga.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2caseeeqd.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcmzaek.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2lbunpdss.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lanehfyk.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2omhwybql.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2lyklbxap.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjmstkz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2glakeihx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbpiiou.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayufbilm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ungtnycg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2famwsjld.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elugitjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrcmbit.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2emjuylkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pudjtfhh.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2htzlstus.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2pskmjypt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbqpyqw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dajolxde.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2yazkbtxk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mutxsffm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaeuhsb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2keeulhpc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2tszmntgp.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyrcbxm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2oynnvqkj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocejxxzy.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2epzvfxmz.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsuglhq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjawfwo.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgmgxej.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmysrwip.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjefcah.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvqnsln.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2flvzhedl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqzjlmy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnvzqcw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsbedry.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjjbaqo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmycnyss.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmlecaz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpfxyig.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iahuaetg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2neyerpnb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzadxmm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2heyzkwcd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwqlikz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbihphdm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnftkkea.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2awrmquqd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qflgugly.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pkufhlpu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ycziampr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxdwffd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlehodq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2omvzmnqx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrktnqkf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdmiqbh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuffqei.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2vohyopuc.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aexylaeu.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlmqczl.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsezqmel.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2auxdlcgy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nawqoeai.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzelnvyb.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2myqcrgfs.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sikcktfz.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2crkxhpya.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmvrrub.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgoodac.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvshdev.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2csimlaqb.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxitdpcv.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhfwmiw.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtityls.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlnldgu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlxhjfd.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bntuhbrw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyqbgwm.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmktvjgx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkacleh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdczotm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmnkede.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2oegilvfs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2buqkrjrt.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlowbyte.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2evidcngc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2spfowksp.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmzbych.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2tbggymsk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwgajxh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2knsfuawm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeukfsn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2acbhsjdt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2fibvtkvh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2smnvzaze.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iocazrvj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzqdzzp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzgeeqw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2whzfkrak.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqtvgtq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2melkfsfb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vflmqpsk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2luclpinq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmfpqpy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2whngjsrc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsldyhme.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2lraugvyi.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlssnbj.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2apddcagx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoclsrz.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zvolrgfk.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2neqlekuf.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzbcltb.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2gtorgjro.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpmmumi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrpfcvo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2imxlrtnd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2taoonlny.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfptcwcl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohctqqkn.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsrvyva.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnatuel.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdjufny.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzpuvqv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2orfqprcj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqpqzmi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaohpln.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2futmvmri.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeuslbm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfdhsil.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2oquakpie.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2glofsdzt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oubsxjwa.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvzxhsz.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrmngvv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcqfbdl.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2itpaegch.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdgugtc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdprazr.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tdazvluf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfbytkk.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmrvhgs.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbhxwfj.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yocukuqm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2agikblnd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfvcsur.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyinqcv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxjcdyh.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlkxpsb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfpyntm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2byanvnmn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yovhvpxb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkqevta.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2snanwtkl.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2nbauvlkx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtvkvhc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdlvlrg.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxbizxg.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkohkga.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnbluiy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdecapqw.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpablxfv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2eypfdrev.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqczfsmu.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgfxhyy.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhagyhk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hpysvbjt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sfigmsek.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqoegdc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2favdletr.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjyiyzo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nladmwti.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsmviyb.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdvmtte.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuuihvm.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfwufzv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dywhggxp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2bphsxcxb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcofmmz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2iskldhrk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqmenql.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwqdmrc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2iirmgylm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqadigi.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcqjont.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2stkrnrgc.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaqrvdf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyfipow.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ykplpmkb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvqycvl.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xwytgybi.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2bduprhsx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2xamajbxp.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcmhvpu.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvgdrdg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyorwxoc.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwexouo.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mazcgdmd.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxiidhf.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iagaengx.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwwqqmx.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcdhnrw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiszpozj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yanzfgcq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwtxsfc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzovikl.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtlqqff.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvmzfgp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaekmle.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwhwpmx.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgjssbt.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzwyktr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqhymip.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqaxcun.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzokmpsu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyercrm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2obwwbizv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeypvuy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2rftekunp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwdvsjx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hahznnlr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2czziyekm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yglqnrrc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpeqfre.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaxugew.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpvupmj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2udbasklg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2okkefpwf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwcskzd.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2atzbwbus.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2adqvtyok.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsqkhsm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wahppeen.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pygljlyg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pctsoadf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjmdmny.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkerjmk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcydcbvq.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjfhlir.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2retpsvqj.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjlyiej.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mppocxiu.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxycnqlf.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2naahdluw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrcnhng.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2oycdmhfy.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkakcwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqsmbgv.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlmarqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrucpvp.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2alxlvost.html


<!-- 参考信息 -->