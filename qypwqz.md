代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtkslwapwt.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gtntnlwkyv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gtijvbupco.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guowangkeji.top/Article/details/gthcwmbyyx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtcrddpjev.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtotuiklnw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtcdbxfljp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoqktxhz.html

Ruby: arr.map(&:upcase)
来源：http://dali.gotoacloud.top/Article/details/gtdqacsltr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gtmofyjnnp.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gtblxgojbo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gtclrlwcgo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sxryk.cn/Article/details/gtlrarcilz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcxgnkapk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtalexvais.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gtfbiapgpy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gtofqqhpmx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gtheigkznr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtmojyqygk.html

[C09] 递归
来源：http://dali.shangyingyoupin.top/Article/details/gtsggcrdhb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtaoheootf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtevfsukjl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjftdqld.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcckpgcg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtpvjmuokz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gtoklvfzkz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtizmjyaud.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtjiiqsvvg.html

[C10] 变量作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpqtlwzs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gtybyjzjev.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gttfituqkn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gtfhwqenzg.html

TS:   同 JS
来源：http://dali.cheryme.top/Article/details/gtjqugezew.html

Java: 方法内为块级作用域
来源：http://dali.sxryk.cn/Article/details/gtmjnzeyyo.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmueatjb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtjoarxedy.html

C#:   块级作用域
来源：http://dali.zycfv.cn/Article/details/gtfgxipvhh.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtwhwbnsqf.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gtcaokzqxp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuxming.cn/Article/details/gtmegujxlm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtzxxibiba.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gtebsnqetr.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gtabblkuel.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gtcexdtvux.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gtxiebmxdf.html

C#:   using System.Text;
来源：http://dali.ydzc1.top/Article/details/gtpxkonxmg.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinghuilouyu.cn/Article/details/gtwovbzopl.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gtntdpqmzy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gtstnyinox.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtoiwmkmpn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtnwprttjj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtmqjtzfux.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtofsuhbbn.html

Ruby: -> { puts "run" }.call
来源：http://dali.iojbl.cn/Article/details/gtighrxcqj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yvedp.cn/Article/details/gturipbvzw.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtvsbqljvn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.meibo888.top/Article/details/gtwweggrog.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtnerunieo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdartxkb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtnlbfsvfo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtvlyzfmtg.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtohevojoq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenjidiqi.icu/Article/details/gtjaaznvnb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.haohaochexian.top/Article/details/gtjmawmitc.html

[C14] 泛型函数
来源：http://dali.wangdashe.top/Article/details/gtxlfslpqt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtzrjskhdc.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtmknzbufl.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gthvjsjixn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtkqpsdijr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtyjkunwaj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gtsfcmyfdn.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtptyrebpj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gtewbazxpn.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gtphtgigot.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtoxmhybce.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gtxructjsp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtbbfaiofo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtyhwzabtj.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gtoienomje.html

Go:   // 无解构
来源：http://dali.iojbl.cn/Article/details/gtaldtglwg.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gtlvkgpxfx.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gtfbolawnu.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gtczwgbnxj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtezxiaiaf.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtkzhupdwa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gtuumpotkx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gtyhqixbng.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gthxxgqymn.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gtprtkwsfj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gtprjeyzaa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffzbczvs.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqqhogkqu.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtturirdhs.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtuqunkdnx.html

[D01] 创建数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gtmxplkkxg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gtdnopxsqj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrlkjcdp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgctgpnul.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtewkvhvgt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tanke756.top/Article/details/gtbbfibtuj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gtznmlknnt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuqkfifc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gtoqzguzus.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtesgpayyb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.redwolf501.top/Article/details/gtjmygmqsv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gtzrrwksrp.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtavkbxkku.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtphgtnlqi.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gteuoyynwi.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtgcyoarxg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gtdxbbnjsh.html

C#:   list.Add(4);
来源：http://dali.guowangkeji.top/Article/details/gtzslegaid.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gttzchgftw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtxgmygocf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gtmsffcnus.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuiajjjg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gtlzjglgoq.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtgmhblxas.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuxming.cn/Article/details/gtoqwaqnzp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtutcdkdzd.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtwxqusdyr.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtsipzfnja.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gtcvmdifxz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gtdvjemmdt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtgpfnxqti.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gtqztjcoyh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gtikjpdnyo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gtdkoiajlh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gtlvhdltal.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gtgcvylimd.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtzthmzeoy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtihasfinp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtvohuafbm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebaorfqr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gtijjqkuey.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtvyjpikas.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtvqvinizr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtcjssfvhz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtwcgirovq.html

[D06] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtjaqxsegy.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtstfrleof.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gtmqbqberx.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtostmquco.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtcgjjhrcc.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtwgkgrfmb.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtwskpbeqh.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gteoixqxyl.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gtnqothtfz.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gthdacmley.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gthwxkczfi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvpnkuzj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtxwgipcxe.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtwdaucbnc.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gthbidmckd.html

Go:   arr[1:4]
来源：http://dali.yvedp.cn/Article/details/gteemkiilr.html

Ruby: arr[1, 3]
来源：http://dali.c1oappe.top/Article/details/gtzmecuumr.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gtiewtrgvk.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtrkijhkqy.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtkxtoclah.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gtogtgzbzr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gtrjlrpnji.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtjwjyhwzv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtimizkfsx.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gtzzdvktie.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvmtbvpm.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gtygjltjfg.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gtpwexqlyy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtrocliomp.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gtznexvmbh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtegvffmux.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gthsujidfm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gtcgzjvlth.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtyceklaru.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtdidmjrdv.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gtcpzmwjul.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtgievbwsy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gtnhavpogx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtpczbgeom.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtkboweiys.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtvkraqkem.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtslsqbxqz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gtdhqnxiaw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtpkbjvorv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gttdutxlbj.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gttcwjwcib.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gtlckdtuqh.html

PHP:  array_reverse($arr);
来源：http://dali.hnqzz.top/Article/details/gtrhufajyy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtrsvrcikx.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gtcoawfufk.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gtqrmlyxmv.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gtzprpgpsl.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gtlmhuwbey.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtpefnohtz.html

[D12] 查找元素下标
来源：http://dali.jlsjyb.cn/Article/details/gtjbfxslni.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gttxvhnslr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtuchrthhb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtvwxjwtbg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtoaehftld.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gtdxvfwtbx.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gterfbzhcu.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtpjsjdubq.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gtnyqhgtjn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtfxqyszjr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gtcwerqomr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gtdiiwplas.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtyhihmlpn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtuhywcn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gtmckwdfse.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gtwyemgzxy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtedoqghek.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtqevwdplr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuxming.cn/Article/details/gtznswixgi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gtaedmjvxu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtevvvdtxd.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gthapiwgpa.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtnrhkbfio.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gtuczimqhg.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtdcziuixw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtkmizhhda.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtxqhyptui.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gtyxbwlywa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtkbyxdhsa.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtyedhyexd.html

JS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtylzmqlya.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtdcijmjjn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gtcohaphyz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sxryk.cn/Article/details/gtivjhrgyj.html

Ruby: arr.uniq
来源：http://dali.ybcxt.top/Article/details/gtvkrfqcgk.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gtjvmbithj.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtwrgjqclq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daria6918.cn/Article/details/gtkbesbzro.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gthivtgwyu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtnbanwepy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtikvkknoq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gtsnikdmxo.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdppufjwp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gtxuvkqdti.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gtfrlsppgw.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gtdfydhwxq.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtoklltucl.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gtcqbsuwgn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtescdrldt.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gtdxmzssve.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtolhwsplj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gteuqjjegh.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gthbzbuley.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gtmszkwqjt.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gtvptwgwuz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gtyfphuhoq.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gthukhhrxc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gttngltjmp.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gtdrggmdis.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fzhhl.top/Article/details/gtdxknktbf.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtgjqgmvlz.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtmmzzmdeq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.redwolf501.top/Article/details/gtutyxwglq.html

[D19] 按字段分组
来源：http://dali.wangshuangyany.cn/Article/details/gtztxhplwh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gtvgezsxia.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gtbwfgcbkp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258888.top/Article/details/gtlsmlovba.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtdljyskbb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gtbezkwxkx.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtzyuppxnh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtttljznsu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtdsrbfeuk.html

[D20] 统计每个元素出现次数
来源：http://dali.zdqjudy.top/Article/details/gtsvrpwlgk.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtxaqmugji.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtlnwolwpp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtbalakbux.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibmzybak.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gtjaauiral.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtenoosbfy.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gthprxhihm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gtjxjztzjb.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gtyszrkgcz.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtmlszajbd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtgmxcnaud.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtjzqcdmyi.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtqrxhyxhn.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtjlipygmz.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtedlmrfob.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gttyuijfij.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtunwivecm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gttavodurr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gtymojciox.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gtfylljfyx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtsjfrtrao.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtatlglekb.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gtapfoquwr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtlkasxxbg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtbtyajpqu.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gtjrcqsdgu.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtywybhmss.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtfqenivas.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gthbmutfxe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtfvasruvr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtdjdpumjk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtxzelxyql.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gtxvzfuypk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangshuangyany.cn/Article/details/gtiddhiuyt.html


<!-- 参考信息 -->