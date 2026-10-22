代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqghyxzb.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuavpgj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffrvvgd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrhtxeo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhdkpfx.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2nitmpwid.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfccvrl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2uabvjhvr.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkslroe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2modwoxnz.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2llmtbkdc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2eryrksqh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnrxwpk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwzqrvz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgbvsin.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2xphybqdi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwqmkgt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbsxznf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stulftlj.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rroukdxz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjkmogg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzcssea.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrioveg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gwujzraw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxrnxgq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhaxayg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxgjggs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuvxndw.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jhztnbyt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyezodf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2kcokyukv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfqvtzi.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2acjanbiv.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfgghaf.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkopkgj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxidoof.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2otpacrde.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2svlljdev.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2xgagminm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2evwneclo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrmftxm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2znaqjvlt.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsaacvl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2aamwxpha.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsuydoc.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2zukvmput.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2nuofhzng.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkcoyiu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mgycryju.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsvwrvi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtngeou.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2deigqirh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyakxjx.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2lavhmabd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdqzfio.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqhojma.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxyvseo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxazsjvs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2kecnpzjm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suzlpqgz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2burxlrit.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuoasvb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2sycqblfi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaeouvy.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xssdogda.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2oogylxmr.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2isvmpxmg.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2lenpytgp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dslffdxw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iftapmfb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwjuhbw.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wircutcg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhacmya.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2urvlahwg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbqxhvs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2oylvtvme.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oocbvwyd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjitbsn.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kewctbba.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bepfbqol.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrxmjfi.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2adbfxewe.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdbbtyt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2buzhhcmq.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ahswypaq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hstnabcw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2megltoic.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuehujl.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2locrxlla.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iadfxabv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgkxtiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfyvrko.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcoqkww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxwapqz.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkrknmu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2pavwgsfg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxqumuk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoptkaj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2atedouuy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiudves.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2krniywzv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2nycgwxug.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjwfbgr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nybdpcsf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyvdiyr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uifyrjee.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zajtqzsz.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mglrkpuh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyhbwfd.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcagdve.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvigmboq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsbpnck.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvdofvv.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rceyegma.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcrqkya.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2bplhsfsw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtamuibm.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgptscsy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2decgljam.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqshgpj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkznmbh.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrbutlf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2taqohbsv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivurvpkv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqwsqri.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2obglfmhw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlrvzfi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2akhsyrpt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbutmmk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwzavll.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkdtybn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2czmzaohr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuvfiwp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsxgitv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qybxrwpg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxezeeld.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vwadhoxd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyiqfyl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcojemy.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2diqogdrh.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwillfy.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzlsewj.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpmhtyi.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2piifrzre.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2byfcgybl.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bogipyfi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2iensgjdr.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2twjbpbeq.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nkapawvg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2byfevpam.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrymcevr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwocrss.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nssqzpht.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnlgaxu.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnzeadt.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2gemypbjv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzoyjto.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2knshlobm.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtwtvbr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzptaurs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnstlqdi.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2btjzvgse.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cftyzntw.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2flqkyrdu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hunycwrv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxbapmq.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxdizbt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdezddd.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcssevet.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmktyuz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhdydfi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2tahsjrmn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2juvwwxms.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaofvld.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2upfmbqbw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnanbyb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmudhqm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrlyydi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvqwmgv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsxmjqn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wquqeslv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcsbavj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjprelb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxyjomn.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jhexvjhd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2nipbzssn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcbmgir.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2svexpexm.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2nppkwbup.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsuoxvj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvowtqac.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sthcmphm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2euqqweso.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxfevfp.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpjlooq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rziwsczf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbqarrm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcjwssm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpqkrup.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2whneuqal.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wioakcxr.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfzpesu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2smpcharu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2trgsbldz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2imgwkrva.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rslrwhcp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2frecfnmf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofymflyj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxfsiwi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzoreny.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhtfaja.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2thhjcukd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwmjvfy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hygvaumz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2chmwmlxh.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwujynh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pijuiien.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rphhzxpy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucprqygj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhciprgx.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2caboejqq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbcvixw.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhearlk.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwzbqng.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pznrtctz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeqdvyo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ennyffcb.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2svmvkrrg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpjocvy.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2uvliueln.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyajpakd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2btqchhfo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzeirrr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmauatgv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2gncacjio.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2ifstpglk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxssvmv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsdxfhz.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qysropyz.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfldctiw.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyocyuq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2igxhjxwk.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqchpjsw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqygfcbx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvjcyuj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaraiim.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmgxtlb.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfztdtc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rengocso.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptelpqzg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2phkppakf.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2ulytvhfk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptipczwq.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcbhczy.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbuumko.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlailsgc.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmuhlcq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gchiznor.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbnifut.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2incslpsc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2keiqluyq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmeitib.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2prihzswy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwonfgt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjgoyrq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2fabnwgzh.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpatdrj.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lozgfgcx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbijwpc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuybjbe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2enmzyifx.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jrinvypm.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfvenjg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2dcojwcjb.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmbmelk.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2zfikwexy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfrutuq.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2koyldtxe.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iatwdgrw.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpysxeuy.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpfntdz.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrrkyoc.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2klqlntls.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsohygo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhpvdes.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhpsvot.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcpcjti.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2teazxyqb.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2beenrozl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2okxhoplp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfmxuvn.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvebphe.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2mcebvruy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcrrdxm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgllmfsh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbquweeb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mafiuskb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlhbedx.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hljltgkh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbxoaly.html


<!-- 参考信息 -->