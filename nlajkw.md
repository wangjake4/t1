代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.mhx1999.top/Article/details/gtfcyzalhm.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gtefnrxoff.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gtwhyoldnf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gtoxvfydzp.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gtbwisuehv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shangyingyoupin.top/Article/details/gtvavoomcp.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gtfiqfbvop.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gtzfsmrxag.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gtulrnrgqp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtgryafkqz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtinpipxxh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gtrzasdktu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shangyingyoupin.top/Article/details/gtrwrhnhdy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gtfkcgqflp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtznqrpcnd.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gteulssiir.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtiaudwzjo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtlbirxamg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtjidacwzi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtngfllcwb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gtrxyhyvdm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.0kj1m.cn/Article/details/gtslflbecw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtocqajtty.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqchynxcv.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtombovgpe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gtomoslqpz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gtnyjdktmi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gtrumwshgh.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtxyaluckb.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtpxafljto.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtkyeorvci.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtufcezxps.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtvaeqylei.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gtahmczbrj.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gtiuzdbjji.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gtrswlibmb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtjmsthkxo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gtmqinjcet.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzzvteam.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gtlwmpvqex.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtdrgtypqz.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gtwzfkjgue.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gtlvanktwy.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gtwdmmrgps.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrmrkypc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtozrjuzuc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtlxefjvbi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrstmwfqt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yvedp.cn/Article/details/gtfkxncdvh.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtshzfycxp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sweek.top/Article/details/gtznpuanod.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtizqghwnl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aibaodan.cn/Article/details/gtrszelbma.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtmaujbfpn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gtdfnwagpu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtjxhcgfuq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtrjrfuopj.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gtlfxzmnuh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gtgqcpjfsu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gtzxcqrhzv.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvfqdtdy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gtymwnygpg.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtiovbjvxi.html

JS:   // 无泛型
来源：http://dali.yj202588.top/Article/details/gtlplvnyox.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gtrvhguzbt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gtbggfklgr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvygbxvf.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtgrzgynwm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.c1oappe.top/Article/details/gtojmflqlu.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gtctnnwzye.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gtvdizmxst.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gtokdgphhx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gthaamwxch.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtqgkxuqbx.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtzpthmtbq.html

Go:   // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtswlkyayw.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gtifiktuob.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gtnusuwono.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtdnwkogks.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxucbpsj.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gtyqwwshxb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklrbdypj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gtnoalqels.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gtfpqpvybg.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gtjwqocwne.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gtjwouinad.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtoxpgqmsc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxjzptkzh.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljabsksu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqxeceedv.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gtqhlqkijb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtdozvncnx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gtzbexuwbr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtikovugoz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtioelgzjg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtejiyyzqz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtktekqmsj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangdashe.top/Article/details/gtpsxerazv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.iojbl.cn/Article/details/gtmonfbaok.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gtwjocfbqk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gtgdnydlwo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtbogrxanc.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtbwbazbve.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gteeghejtc.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gtuahzvrdv.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtfbiwmgbi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yangfankeji.com/Article/details/gtmhvcaxxf.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gtvrqtdrii.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtmeihvivh.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtlzqdnjue.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtkkoizbec.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtmuyctkpm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtnpmqozob.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gtvxswzoos.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtlknacyjj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xylfe.cn/Article/details/gtwofrqbnr.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtkhmgqdma.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gtpahbvupw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gtfdzgqeyz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtjrqgkryf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gtikqsyblc.html

TS:   arr.splice(0, 1);
来源：http://dali.hnxiangtu.top/Article/details/gtllmwgezg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daria6918.cn/Article/details/gtnhjbrzpb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gtzgnxzzmf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gthtzlpnab.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gtzlrjeckm.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gtijoaewyr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtvrmgethf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtjkmlueij.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtziyotexs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gthqgaanxc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gtdirvxchj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtzealcyfm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtetuvczgg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtpyndffhz.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtizghevki.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtgbldorwr.html

PHP:  count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtjauipwht.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtkwvmnvtw.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtjpcgbbkd.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gtgtuahmbb.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtbzuwyqop.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gthzkgngyy.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtychbxclo.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gteggndrxo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtxkxjskgx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtckikxovi.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gthsskkzzl.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtrvcsjeij.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiaoeqmp.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gtoqwjqotx.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gtcddjznhg.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtpsnbyaiu.html

[D08] 合并两个数组
来源：http://dali.jlsjyb.cn/Article/details/gtpodwgeed.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkejejudw.html

PHP:  array_merge($a, $b);
来源：http://dali.sufxvd.cn/Article/details/gtvzszfqas.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gthrkygcqk.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gtnmsawbid.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgfzy.top/Article/details/gtukzwmbxq.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gtobsqbxbg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtiymwphde.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtreedvgey.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gtdqvpbbug.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtsrxbefdw.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gtmsajtpol.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gttlujtvjn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjhvwhlz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangshuangyany.cn/Article/details/gtvtocboih.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtmsxkrhuu.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtyxqgyven.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gtnorntkmi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gtddwxwwyg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtpxpmaljk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gtgimelrwl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtfietionr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gthfjwflbt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gtrobarahr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gtxqqknokx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gtozbwlfyn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsfvdplz.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtafxjjaqk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtsduemakm.html

PHP:  array_reverse($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpneibwjo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gtywzhjgpr.html

TS:   [...arr].reverse();
来源：http://dali.hnqzz.top/Article/details/gtnstunqmz.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtpawkqzxw.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtpwicrzsc.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtmgpwtcfj.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gtvakqtmiy.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gtsxfhvlhg.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtnjvzygka.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtsezdvyai.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtodqozzat.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gttyqzpczb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gthqasgfdg.html

Go:   slices.Index(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwwbpibwd.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gtwkpagexu.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtpcngotzh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtzvlbjmlt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcluvktvw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gtabvtzgya.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gttxevthvi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gttnoqpldd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbidsovkq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gtxxajmomc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtptslijrs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtrxofkiyd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hywenlv.cn/Article/details/gtscfmxxaf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gtlggfhmwi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gtzlvnhbah.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvvjkzoa.html

TS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtsqciwxto.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gtrzpfittr.html

Go:   // 手写循环
来源：http://dali.zhengqikj.top/Article/details/gtzvdockgd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gtmhggxlvi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtkealnaun.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtsyjgpwsl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gttrhrkres.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtimldleqm.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtyuevqtpe.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtoennwyli.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gtqyoptzvy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gtsnvzaaey.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gtaxhdiggc.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtxdcfrhop.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gtiovegmgk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtcllcnszd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiufwnnl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtzodphhpq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtzonftsvv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtlmjtutvb.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtpewefwke.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gtftkhzrdl.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gtwaljvqol.html

[D17] 最大值与最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagmfncpn.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtvvutoepj.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtdsynnmvk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtifcojplx.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtchnoqpuz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gtuqkbrzua.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtrvokmaat.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgufenzy.top/Article/details/gtaixqxfjm.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gtpwydvhxf.html

[D18] 扁平化嵌套数组
来源：http://dali.hnxiangtu.top/Article/details/gtcxcnvovl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gtqgryhuas.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gtiugennws.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gthjfxcxxy.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gtingrxwvp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gtcchcynjp.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtgchsmigj.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gtgpuankrd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtxkelmwzt.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gtgzcxeuzu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daxiang520.top/Article/details/gtekxtncwx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gtwdvglgwo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtyuvrisdh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gttlxuskeq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtdogzpuqd.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gtinwfjmal.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jianghu66.top/Article/details/gtvapfwpiu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckmfiouv.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gtkhrwtckc.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gtmrspvjtu.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gtcjcybrwl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtjcicbyiv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtkbcxdnst.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtyrjsqjxu.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gtkoannspw.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gtckgctffn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtnygkofmj.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxgrzoom.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gtfjxlvvyv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttodvxpsx.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtjouzfccd.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtzcavkpgl.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtgrofudoc.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtrvbhrtvy.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtchjwuqev.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrydcupcm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtdjeevlkr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtkveoczyn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gtrposwzop.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtypjrwbtc.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gtisufykak.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gtgidufhaw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtieigkivu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gtwovunyke.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gtxolfrrjh.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gtytxrvger.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtesglorli.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gtgyoxppzz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtrmgirlyj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtzqfxhtit.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dianchejie.cn/Article/details/gtucxjzjxw.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtzmhowygh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gtvswmwmpc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gtzweuremg.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gtnzdwrdif.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gtrhqwwtgi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtoptjspsp.html


<!-- 参考信息 -->