代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gtwskahbvp.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtckypqzvi.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gtqtwctegp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gtggqgkebi.html

[C06] 匿名函数 / lambda
来源：http://dali.zhoulong.xyz/Article/details/gttuslywnw.html

Py:   square = lambda x: x * x
来源：http://dali.feifeiyinyue.top/Article/details/gthfcecaxu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gtriajgcxg.html

JS:   const square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gtkgjuqxpi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cucudq.cn/Article/details/gtrbyxstpk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqtyzxet.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gogol.net.cn/Article/details/gtruhqpzed.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gtmafakwpb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtmvplhgaa.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gtohzdwcjc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gtedisptaq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtnsjqsqut.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtyehhorpa.html

TS:   arr.map(String)
来源：http://dali.zhengqikj.top/Article/details/gtwermytch.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gtmktkiyox.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yanxiufei.cn/Article/details/gtgelipxlx.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gtkeciqvww.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtylbumizm.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gtbgivgklg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pycfn.com/Article/details/gtfylmpffs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gtwkmtjdjv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtugnoeits.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtkkhgeelw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtdlarwfit.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtkqtltmcp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtugdoqbsz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gthrfvaglg.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtplpzaivk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtesygnwdo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtikamxpaq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gthnsqrphg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjknsvqp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gtkkhykboy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gthmiiwaud.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtncarewwi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtdssiepel.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gtyjenvblc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gtrcanowgz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yongpay.top/Article/details/gtrcqlywki.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gtskodxavs.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gtjmowteje.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtxutrueyf.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhnkqqqi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gtkorwjzhv.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtyzhkcjtg.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gtabkccnnw.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwckickr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczsrgpnm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gtmlrrqpsw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hysaishi.cn/Article/details/gthbqsrbsk.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gtkxxzatzg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jlsjyb.cn/Article/details/gtppbwljvr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtemthdhag.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtkbadmaxr.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gtqatmwqva.html

Py:   (lambda: print("run"))()
来源：http://dali.xziqi.cn/Article/details/gtwvcdthwh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gtaaxjspfl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtaijdwejh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtxkipmynr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gtyjbrunmn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgfcpxis.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gteslbliwf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gtqllfsyxo.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gtculkfhrn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gtrnetodgg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuwrpbjwr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gtlilmfbrx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfsbxwger.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtpwwlysvs.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gtturnysoz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gthlwfvczj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gtsiqqzirp.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gtkcothsmk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtftbjdxwh.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtxkgooazm.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtjplrmnei.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gtwqskfxhk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuaqvvqs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gtfqgxsyue.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gtmqbultzv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gtarcgglgs.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gtrjibgfwt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cucudq.cn/Article/details/gtswcuzumt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gtxxkygmzr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtbwokmesh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fengsongda.top/Article/details/gtzbooojep.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtalpbkfjs.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtualhlagw.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gtpgmxrkjq.html

C#:   var (a, b) = pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtdqdkerxx.html

[C16] 函数 / 方法重载
来源：http://dali.gotoacloud.top/Article/details/gtfzjlvfdt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xylfe.cn/Article/details/gtgnnisfrj.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gtktkiveyp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gthytvhqmj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jianghu66.top/Article/details/gtquoeieop.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtyqispmxa.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtyyrzqxmu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gtmymqggch.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gtfvfxprou.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyrfnpkql.html

D. 数组 / 列表 / 集合
来源：http://dali.redwolf501.top/Article/details/gthfkzmixi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtszlzauom.html

[D01] 创建数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gttlghfejy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtlrbxgfol.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtqfbavfvg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gtumwwbotz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gtzlkpdhog.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gturehqylm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcqptgtc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gtdpwijtmf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gtfartvxpb.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gtbhxpicvl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangdashe.top/Article/details/gtudwxnxtt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gtaxqmrwvk.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtozqgbrvk.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtivrlxuqv.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtkwbqmvyo.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtfmsjinho.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtbjsokvio.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gttniftcbq.html

[D03] 在指定位置插入元素
来源：http://dali.yvedp.cn/Article/details/gtdbprndst.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtcbxpxmtj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gthmtiqufz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gtgwtpqzcr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtrpprltwx.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtogggzrhs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gteiyjwins.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nwbrower.top/Article/details/gtfgysdsqq.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtwchqqgzr.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtpsdmvemt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258.top/Article/details/gtrllslrzf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyvnnmya.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gtukbypvrg.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gtzjtjevtq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtrnnpoqzj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zdqjudy.top/Article/details/gtjsonurtz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gturbybmxo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gtkqlgnimy.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfwnytgy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtkmgugxqj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaxnoiro.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtxlrfvhrc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shangyingyoupin.top/Article/details/gtoxvzsnck.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtdbeguekl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtmwcowhqa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gteqeazcox.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtdaexypsn.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gthtyabecc.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtbuykjllp.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtiwrmydpa.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtgdztilim.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gtvdgxoqyj.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gtcfffasot.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtfsxdhdxl.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gtekhjwdsi.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkxikrcu.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gthiqqbtro.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.smart0.xyz/Article/details/gtuwuuqtqu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfynoggqd.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtsarbcglj.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gttbzmzsqh.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gttsdsyubo.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gtihjerrjd.html

Ruby: arr[1, 3]
来源：http://dali.zhixingplan.top/Article/details/gtoododpjm.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtlixeycrp.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gtgknlnktb.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gtuldgzonc.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gtmaevvxpp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gtkwvnzkms.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gtkpdzqbtz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtqrxvhozz.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gtnelykwtz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gtqfdmhdjr.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtaoighjzn.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixntwvcx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtlhebwztf.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyggaexbc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtysozfwgq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtkmazzefw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gtfxufjzzi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtcoginvpx.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtfkkkgfgb.html

C#:   list.Sort();
来源：http://dali.nanxinkj.top/Article/details/gtmajmpjcw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gtfrlbhsab.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnxiangtu.top/Article/details/gttvzpynqv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtnwojonmy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtzplwvwtg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gttibbfhca.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgsbzvdm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.316326.xyz/Article/details/gtftqeeajr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gtzmtidbwj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gtjxazyoiz.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gtttzywbgw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cheryme.top/Article/details/gtkrobzakq.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gtcpczgwtv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.redwolf501.top/Article/details/gtdoifgbwy.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gtoumzrpep.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gtqjclhepe.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gtxvyikuls.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtvfpzdshy.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtgacxipue.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtzjwprylt.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gtaaelcemy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtmkoswhmw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtlkhwiypb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gttdtpcytn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtlhtsxkom.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtrncemyzb.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtdnhznlcx.html

C#:   list.IndexOf(x);
来源：http://dali.hysaishi.cn/Article/details/gtzyvdhjkl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtajppterz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtkmomyizr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fengsongda.top/Article/details/gtabqspqip.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtvxjcketu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtojmksgsa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gthmgzomxw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gtwlevnsjl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cdnleiting.top/Article/details/gtjdrokeuu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtsabxjofq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gtfjvbxwpb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gtptcqgkbn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtfhqalpny.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtynkrceyb.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtjextzfpc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gthygrohak.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtkanozaft.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtfjfwtwxu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtmdowoyhv.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtsnbofxhf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtykufxbqd.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gtpbxamqnu.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtdmnbfoxg.html

TS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtkwqptdom.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtdkbwuuif.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gtvsmwnish.html

Ruby: arr.uniq
来源：http://dali.chenlongwang.top/Article/details/gtbxiqpelf.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtyaplpcrr.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gtgqklehsg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtahdjdotv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.havefunace.top/Article/details/gtnvbrtheb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtffzxlnmy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtlvdxqhvp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gtbonczwlg.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpobskgc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtkkanhsei.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtcahosskn.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gttvnrjnbt.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhziwjkc.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gtazhctuqs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtnebxkkpy.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtnekwfhlc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtamnizlhp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtlverihuj.html

Ruby: arr.max;  arr.min
来源：http://dali.shangyingyoupin.top/Article/details/gtxekuavta.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtaalimull.html

[D18] 扁平化嵌套数组
来源：http://dali.wangdashe.top/Article/details/gtkzarupzw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenjidiqi.icu/Article/details/gtwvkjylrm.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtrggiqopu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gtustfvehe.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gtlorztvre.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtulqkywuu.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtkshsbkfk.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtsdyimfct.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtiuuesmov.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gtawemtgkp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gttydrtyab.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gtksqacofc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gtcljyezyb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtfazcgtew.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ehwqpu.com/Article/details/gtulzwrgah.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtxazwzfvi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gthgfdebbv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrsovqab.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gtqldjiqjc.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gthdqlhbyp.html

PHP:  array_count_values($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtmtpeuaxr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtubxkonqt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gttbkxyoym.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtuwolvabz.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gtvvfjmrkq.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtxvclinsv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gtgatjtefx.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtzfzapayq.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gtfupjezjt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigufen.top/Article/details/gtljjtobzl.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtvlwkuvai.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gthalwnfdw.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gthlmmuacw.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtpvezzwui.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gtclezzebq.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtkzopnokn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gtmlaljsjx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gtgpglppvp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gtsdtjsocj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gtdyatufkr.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gtfsxybcmg.html


<!-- 参考信息 -->