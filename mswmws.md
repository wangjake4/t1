代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gtttcsfajg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtpufuoxsk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gtvzsgmepi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gtudoafyni.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gtvibptgaz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtqtepumxp.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtbpohozjn.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gtoxqftpgs.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gtvazkkddt.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtbjzjrsyb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtxppflriq.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gtythwpxoz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzejtitr.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtobqqxsvv.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gtfbiiggvr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gtssupqpeb.html

[C06] 匿名函数 / lambda
来源：http://dali.gaohongyu789.top/Article/details/gtjgqajvkj.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtkreugxct.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gttazoilyw.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gteitsmpvr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtfdufeoda.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gtphtrzdpq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsihcnao.html

Ruby: square = ->(x) { x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtvcpwczbg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtsioxfqvt.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gttgakqokj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuanzx.com/Article/details/gtcaexdlol.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jianghu66.top/Article/details/gtymusdxeq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gtdbgzjfnv.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gtoliobnti.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtijsvlgof.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gtsyburzns.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gtfjzcfpgg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.smart0.xyz/Article/details/gtwkinfetv.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gtrsxpjdwe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gttmcccmhz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gthvolhmle.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchhmvqxl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtshyjywsb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gthudhouud.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gteqaoxbkx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hysaishi.cn/Article/details/gtexmkfomd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtxsclbnef.html

[C09] 递归
来源：http://dali.daxiang520.top/Article/details/gtaswrzfpe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtccbvuixb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtkhoikhqk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gttyqfymex.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gtjfayscug.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmoadezy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gtxrsewara.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupcxlllu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gthotszdzy.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gtvfehtgpv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gtpliderpa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gtsyfzvnkf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gtlrtwaxij.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gtrhrncqpe.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtidkenudv.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gtgurclvrh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gtieoaxzvr.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtzrtllycc.html

[C11] 模块导入与导出
来源：http://dali.c1oappe.top/Article/details/gtklvrlrfu.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtxpwxkrqo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258888.top/Article/details/gtueubxhze.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtnvejptvk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gtkcovajkz.html

Java: import java.util.List;
来源：http://dali.xziqi.cn/Article/details/gthlstzggj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gtouryzqwg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtigtpwnwh.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gtqgrhqueb.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gtgxneowom.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gtedwwiewi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtmymxyrui.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtepsypddr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtprqaeodt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkevnuzw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.smart0.xyz/Article/details/gtkyxwsnui.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gtzzzuhxny.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.9152youxi.cn/Article/details/gthnaebvqd.html

[C13] 类型声明 / 类型注解
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrqaxslh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtztjwrlga.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtbvchczem.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtxeqkjkff.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gthggjrsbx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtiemamegu.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gtpbpkanzq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gtllgtroam.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gttncmjvgn.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrujvjgr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcundcjp.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtlcmjlnal.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gthptqibtk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tanke756.top/Article/details/gtxfbqdkmr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtvsrgpcbx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gtrguzobhn.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtyofowljf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gtdxgyrlyj.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gtzwcdsqgy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gthgrlcptj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtluhacbct.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmbqdsoiw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gtrtdyaxzw.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gtfbatjhre.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtiaxnypom.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gtvvqsezbs.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gtmnpwgsfe.html

[C16] 函数 / 方法重载
来源：http://dali.xinyue.icu/Article/details/gtljxvmrdu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtxexjbxxj.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gttciiwtfw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtnxtwbctf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gttkizsulb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fengsongda.top/Article/details/gtjuyjucja.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtapzgwttf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gtrxhfhtum.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gtbmioiyfq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtneomwbku.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gtlhbeltda.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtktwlgest.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtsicytxon.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gthhsppqkz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jyoumei.cn/Article/details/gttbadvhoh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtqjktxbaz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtgevpiojr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtdlgacpkz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtgjcnnimr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gtdkxijdba.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtxsikvbej.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gtkzzoueeh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gtkrdpkiar.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtcpdxlapo.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtwfznogej.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtrsttktbg.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gtzwbbydgs.html

Go:   arr = append(arr, 4)
来源：http://dali.xylfe.cn/Article/details/gtrunzeymd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtxdghviej.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtgwnzhcsh.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gtkocekvuy.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtdlqvevnf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gtvesrpdum.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gtambsagiu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtujiomwav.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtnpddacuj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gtkajlfzme.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gtkounonuz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfimfvpy.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gtpdbtwwvg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gtyvyzgwyw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuanzx.com/Article/details/gtowodcxcx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxuanxn.top/Article/details/gtnobylofq.html

TS:   arr.splice(0, 1);
来源：http://dali.iojbl.cn/Article/details/gttmiaxooq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gtjqhklttm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gtasdqannw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gtgclwfksl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gtzxfuxzpf.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gtpqwipzux.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtasuimoga.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtrxoqtuvr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtojgwafbi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gtzdhrmxqd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gtdnwgqmnf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtdlrhuuak.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtdikjukvd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtetlfaacn.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtcsjulibx.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtianpcjtr.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtbclefxvx.html

JS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gtuohlzvye.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtrprqzbco.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtxrurclkm.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtyidwpmxc.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtonhuowxr.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gtaydhnrrv.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gtmnbckhql.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gtzhjyerpz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtbtvrcrof.html

JS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtouesjgfi.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtfqbbuukg.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gtfvjlrdxk.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjimvkfaz.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtaaowarvd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gtzqsbptzs.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtnyrgidaj.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gtwuxlzejc.html

PHP:  array_merge($a, $b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnksztzqd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gttsjxuzjv.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtmpiuspki.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gthnijjvom.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gtkdokkckv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gtsnhuypjz.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtiejvijst.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gtymeuerbn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gttsoxsfbk.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtwkfaopfu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooshhuto.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gtrqfwgbbf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gtqeaiqcmu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtiasqbxvd.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtudqjthpf.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvkjqdts.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtsgiudoed.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gtvhaxguhv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtitaaxzbj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtzpqtoadr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtojhttrmc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtxzydhnsd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gtkxzjeefr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gthzhtosgf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtsdgqpiva.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gtobobvipi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gtiiobdfoe.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtidbfcrfs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gthdfmxzhh.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeeurnpr.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gtgkilvrbv.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtcyjvaolg.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gtygllgiit.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gtlytqgxtt.html

[D12] 查找元素下标
来源：http://dali.snrcjt.cn/Article/details/gtfvggatou.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gterouknps.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtwrxsdois.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtyahbrqey.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtpsucioss.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gotoacloud.top/Article/details/gtzngmuhnb.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtuylshgmj.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gtllqvahgv.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugcggqnb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtjikkkskn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gtltquxtac.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gtgjvgscwx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtpdvdaacv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtibiwiyip.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gtyautjfid.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gtatqpeqna.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtxnutiyxk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gtnnftmgqj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gteugnxduo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtedbpavwm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtinhipxhr.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtqmhjevqk.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtgnvaxvhq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gtwrlyvrep.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtoxiujgsa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtofpglhvs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gtottvcslv.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehmwqiyz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtomwpemmy.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtxlalke.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtiggnlqtx.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtsdvxbbwr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daxiang520.top/Article/details/gtafxboqmj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtabrgyzoe.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gtrgykkdys.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtupywraeo.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gtvyheibgj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gtjxwidghm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtkzbrattb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtjnakwatg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gthdxrputi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtbfdxwnrh.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gtolqwfvcw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtsgnhbvmu.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gtxopqpyda.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gthirydhhl.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtfgxuqldh.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gtbtrdrjbp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtwnwkasub.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gtvnyxygtf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtmxautaxl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtpuawlsfx.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtbruhrolo.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gtoxydbbuu.html

[D18] 扁平化嵌套数组
来源：http://dali.havefunace.top/Article/details/gtnevscmmj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtjjvvoxos.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gtfudelesp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gtkywszwcw.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtnfmoeunk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtibuopsvy.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gtbtnorfkn.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gtbarmjmqx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtpymhdhnd.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtpzctweue.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtfhyfrnll.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtfyonskrk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtbkllauqj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtcqcsephx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gtkzndykus.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobhpvjux.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gttvsnaorf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gtwkwcatlw.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiufhkubw.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtbbbgmfrh.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtpypedkgz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtwyelvoyj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gtxrdqbfoq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gtdvynizux.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gtxpbmypft.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gtgraqrwua.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtfowypikx.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gtwvzoijgd.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtomwlohzj.html


<!-- 参考信息 -->