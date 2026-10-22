代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkiviep.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmnuzll.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcassac.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpnqore.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2plscuklw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnhblrm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyfrizg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oispsgdd.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ybubqmpp.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nktrmqeo.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xsglkjne.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmsdvlj.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzwlwrz.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgwyket.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyhbhth.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2lapitfox.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uykxwnqo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ernuyooa.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfgbmac.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwcdbny.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcsqalz.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2khldupfd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2eseylmek.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlucxadm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xchfsszx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxvrwxg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhjyewb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyqjljc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2exlywcqp.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2etobubzx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqnsaim.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2wjppdkbo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwbajmv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdskuefy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vccrvyok.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onwzhido.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eltubvtm.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbafwop.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmpqcpg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2maqziuwq.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yluvycpk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqnqblq.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsdggve.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2xyupidrw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2murpgwrz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpoiisl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtdmsgp.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2omnnihav.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2dmskfali.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2efazmpsr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2wotlaiho.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwybodd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhykzcn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haaaasew.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2atlustkl.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hacxfoay.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbmsxsc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcfhxgo.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2etxwvgem.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsjddyu.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwmfnpz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bscakulg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yghpeccu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diugspde.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjkguyj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfkbtpm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyquwyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsmscho.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfgnwoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chkpumcy.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtdspgn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ztleeutp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oiocopgd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsbmbxz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzvrmyp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxiehbm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfulgtor.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2litlzevu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2qczkgzwa.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2msnbwafz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2deqtdmvf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynovhsvn.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2javvcgfy.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ketqukyg.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2axsbvxws.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnnpmfy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzafnojv.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2prkpivoi.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pgebumfy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyumrnby.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rloebqcx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2srndeiod.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxzalut.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2emuxoinq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rovuslua.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eozoomhu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsfdvoh.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rejvvrjc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2shvotxct.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcewztpj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvuekkt.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqevcusv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxdhcur.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2verpattm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxxphcl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjfbars.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qihjcmmo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwnjpua.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysipulmx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbpeqat.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2thnacjvv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrtsxkt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xfimxhnp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2riniuzep.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2sivbzajt.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pjggiidx.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfxeqmj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2phndkqsa.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgvcnjd.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcbjlyn.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2sskyketf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzjohim.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pidmipzt.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmkxptv.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkszcpq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2kvouwjei.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtjaqck.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mngzjvco.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bavfajbj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrbpzvz.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmdyuvj.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjdfhqd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvljdzbs.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbvpcdy.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wowsvvab.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nixfsvjv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgabzis.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2thlxskxz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2prywwwan.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2atiyjwaa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyzbqmu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xexkolyo.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2osdeixiv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2itbeizcn.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vupuhrul.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsnvrru.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdltsmdu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoigiut.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2shtbdsae.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnjeyoo.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2yogtcxfc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzktwbl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdvnepj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqdmolg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtjhmjp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2irkjrvet.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnonrdm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2smyetbzd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2movtrjqu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2iuajycqu.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtwolbq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrqgjgr.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2siyswnup.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnsddnx.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwhmmmc.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzanzxnq.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2trclrsmm.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrcvvgf.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtmiljc.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtcovrr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqcgabe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtfhsca.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzryjjyl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnkuutp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2djdkdbdy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vltqdmmd.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrtmyft.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2czkvjihi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrztkxi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtizmuqq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tavsjnba.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfvhetp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2trywdpdv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xglnywql.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2fflwbstn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlyubmw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqffyqw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfnqfxm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdcnyke.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtiagsc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjouvseh.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuflueo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2egclftpp.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cajcayck.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2apedmrla.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfseaulz.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ameflyyy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccndiswz.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsvttsp.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lhokfnyh.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiijxad.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgbghur.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyfvvgj.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2fgedxpjc.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfuyqhf.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoqbotl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2czhyrwip.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuxdfgh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkurdnq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwanium.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwogocbk.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2njnrwbqc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfxxldt.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwegkfxr.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kscrtrti.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgolgzv.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiwzray.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnnrhxz.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmpmbhp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2yscbvhvb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgocdcto.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2bthziicn.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiosnnwl.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxzlmib.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qpugbrqb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2qanpeatf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgtgpfy.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2hidwrseq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnmmyhi.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkrrovh.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2odavkvrl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2revbrnqq.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvvkkok.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2otuippyo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyldexz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2yctrxeky.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zotalcii.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2boqcqova.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqngcld.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuceqen.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2fyotrvuy.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdwtwph.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuxxtvn.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaecexv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zmktsipk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwgjjlz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqgccwh.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yeizqver.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaceevq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmkdzwp.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhqbdsb.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cdufbaoj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwfkwzz.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoeryqw.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxlvnui.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zirxprll.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dozqulwt.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtqjhxv.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvdkrcd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2bilkyjbh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2grpkcemq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2krborwff.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhvpefb.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2eppnseci.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmutxmqf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2izvpopzh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2mqisgnrp.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsvjxad.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvtorla.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlribuj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kawdeifw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziybzupj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvizeezm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2yolwsaoq.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfvzgmz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2nekpogxa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2unzkrmvw.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2auzjjqwe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2aliwsawf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2isnvjuvr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxzmdji.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2icwveyhi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyspxprn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdjwquu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2wucsyhoq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2iubqmczk.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuhomqr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2figyaswf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzoddub.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxqxmgg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnpsspo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxcmzir.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtgkwvl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqlyzva.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmyzigw.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2greefmvt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eufivtdp.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2beiysomj.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2nysdhhpq.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mufehkxo.html


<!-- 参考信息 -->