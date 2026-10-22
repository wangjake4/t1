代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xylfe.cn/Article/details/gtuefixbtf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gthnpxkhxt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gtkutvqxgg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hammf.cn/Article/details/gtcjkxvnyr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gtwksjkwvf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtzyzcvkyy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.smart0.xyz/Article/details/gteksmqaho.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aizwys.cn/Article/details/gtrbcjnqde.html

Go:   // 无：用配置结构体参数
来源：http://dali.ppjwa.cn/Article/details/gtcgnyepno.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtlccnhoeq.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtvhvgvzwm.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtcmptdzyy.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtfxajpqoy.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gtpanhcpmx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtuzipdsor.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtmzdwnfuu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gtrwsgcfls.html

Go:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtickbjdxe.html

Ruby: return a, b
来源：http://dali.gogol.net.cn/Article/details/gtlgsfztmi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gtoulvdsob.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtgdhffvxw.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gtpfejpirf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxuanxn.top/Article/details/gtkxaxkmjo.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtelwvwvhx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.birdmap.top/Article/details/gtxsjqozyr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtzbtojyqy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ehwqpu.com/Article/details/gtwujhvyvz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtrxkmzvjh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtimgzkqou.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gtvdkynojd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gticmpnytd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuanzx.com/Article/details/gtdmlstvti.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gtfaglmhsg.html

TS:   arr.map(String)
来源：http://dali.smart0.xyz/Article/details/gteaqvlpzn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jyoumei.cn/Article/details/gtuqmmezzz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gtsracofdl.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gtferthdqp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pengpengdd.cyou/Article/details/gtasdmwjnm.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gtzmcozzel.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gtefrghkof.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gtbkndpykx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gthavhsfif.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtfqnodbno.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtzvwngivi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gtmzkqtvzf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cheryme.top/Article/details/gteviykadx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtuyfljhsc.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gtbyxuiinx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gttzvykfin.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxbsrlkc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtpthrnoha.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtzeffnnuc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gtxowznwnd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtxoaccmff.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtddeyveno.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.9152youxi.cn/Article/details/gtecvexriq.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gtzctxgfba.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gtrlkwijyp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shuidangran.top/Article/details/gtluhpyndx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gtbjukteyg.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gtdlakpqmu.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtwxvtohbo.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gtfxcrhgbj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gtsfvkreks.html

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtnrhsgtss.html

[C11] 模块导入与导出
来源：http://dali.dashuyun.cn/Article/details/gtbeauvhmk.html

Py:   from module import func
来源：http://dali.havefunace.top/Article/details/gtmviivovj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gtdazgtslo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtddejxawc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtuqdfmbxf.html

Java: import java.util.List;
来源：http://dali.yvedp.cn/Article/details/gtdvllympk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gtibcqrafv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gtnajgjgta.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gtnbzsngps.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gtilqowehq.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gtihnjifsw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtitvxasdk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptgwkfvv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtzipcmtlq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gtutlyconz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtbkhvvjye.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtamisiwak.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtxaznklzx.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtulhnhjgn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gogol.net.cn/Article/details/gtryaiscod.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtjuwmujzd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtaheemvfz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtakszdmue.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtfjzasgpx.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwybwowoa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuetiantiany.cn/Article/details/gtktdbjrsz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gtfknssfzu.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gtdhcbwpui.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmskdmkre.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gttwyocpvh.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gttsdxfkwh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtwjlqujko.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtpoqgeewy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gttumzbcml.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gtvtbfsbjb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gtigtopirp.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gtyisdqmsq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gtbnykfsps.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sweek.top/Article/details/gtnabkojdv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtoordzpev.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gtdvetoyzh.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtehmifaav.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtztzjiosz.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gttqecqegj.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gtfjbbcwkv.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gtctwlzlhd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtyztxdxaa.html

PHP:  // 无重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxiuprsnl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gtalagpaqg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gtmndrlsac.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtptzoftta.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgbbgsdc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ivvv.top/Article/details/gtnzdlnbhf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtqnlbvdjq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdgkzklmn.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gtenkrkdpu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlgxxvokj.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtohcrzhmr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gtqkmwxrkl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gtvnwqjgyw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gtftirrhxn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gtjovxxcid.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuetiantiany.cn/Article/details/gthznaffxm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gtqszazflm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gtmkuprddi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gtiuslbbbm.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gtaulzblcf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tian-w.cn/Article/details/gtnqjvlyts.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gttzfbutix.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtbeuddsyl.html

TS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtgabihyhe.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gtovmwcnbv.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gtrzytiueg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gtyqxrreuq.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnxucxrq.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gtpfturbvu.html

Py:   arr.insert(0, 0)
来源：http://dali.dashuyun.cn/Article/details/gttcfzlwcg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gtgcyouhph.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gtekmovhax.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtbxmasldi.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtqpzwftwg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gttzvojvvu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxideess.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtcuvbndao.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtfosremic.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtjjpjvond.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ivvv.top/Article/details/gtihcqwhom.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gtqljqaqlu.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gtkpkfkckl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hysaishi.cn/Article/details/gtfikeexjj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gtcaggaddv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gtgnifsrfy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtxykrzxnh.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gtqraejjsj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtfbjdvgpl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtqjnepxuy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtgsjzazrj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gthsdzaadf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gtycklrxyv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtlygfupji.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtzoiazadb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtpbiuqloq.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtfdwdtxxe.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtvkhxhpef.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gttcokogla.html

JS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqktbupn.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtrukioitq.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gtxkzlpxjw.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtxebjtieg.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtpbgqpooi.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtlulmyhox.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gtsakdsatl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gtfytfzdyw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gtsrpdsdbx.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtvjuquzcm.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtjiaxuosz.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtqqtqcpjl.html

Go:   arr[1:4]
来源：http://dali.andypj.xyz/Article/details/gtetcgbgpu.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtnvuuhyme.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtqcomrlex.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtrdnatwcf.html

Py:   a + b;  a.extend(b)
来源：http://dali.shzxlz.cn/Article/details/gthdqbckwv.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtghnnlskv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gteaewazft.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gtufdqpena.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoihdpkp.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gtevwjdaqx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gthussolun.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtnoroswcz.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtujxihphi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtolrozagm.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gtmcxjjwbk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gtbarsverb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gtaulnkscd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gtouyninfb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtqedmfsor.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtpdlrlroj.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gtarvmzccd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsasuputf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gtlomsfdxz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gtabhcljan.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtjxyjebtx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmgoojxq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gthgljzzwd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhgrtxat.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtsuxxwqem.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gtwfsznbws.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtrdohvbmm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gtlogyukif.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtljpqlhwq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gtqfjvewrm.html

TS:   [...arr].reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gtgnzttwby.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtnqfsirsz.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gtaslxossy.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gtluqmllwt.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gtavdxhkfa.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtceesfhjc.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgufenzy.top/Article/details/gtymxyadbz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtakourjkj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtpvfpvdus.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtghvrokfe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxinkj.top/Article/details/gtarjfrpal.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtqudwjctt.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gtlwatnyzu.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtleytidqp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gtphmlytld.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gtxjrjxbpf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtuycbqnbi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtfmqwqiwc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtpoqeljzq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gtezvutuan.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gteaapglcc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gtqfwlepvn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.andypj.xyz/Article/details/gtnrpsgxqm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gtnoysathy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gtgzuopsry.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtvpaheqmm.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtouruqblw.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtvwpgjphx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gtgngevapj.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtwjirduil.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtdlprshcp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtigagjdxt.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaizeomyw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtneirvigg.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gtoucqxixv.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtskrszcut.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtifzhcbsh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gtzhdcbxnr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gtlrcxrcqr.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtxxzvqkya.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gtealzsaiv.html

[D16] 求和与平均值
来源：http://dali.yonumen.top/Article/details/gtqmqfhadr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gtoxmrudgb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtxfkcvsfb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtgqgavfmi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtueugdeyf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gtfrklcjvm.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtuagzhicj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gtlklqcbup.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gtjmilncdc.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtpwxahlmi.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwscouqx.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gtkhdambod.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtcnffmacc.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gtlfzmndug.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnzulfbw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtkpvklutv.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtavdxkkjf.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gteklbrhha.html

[D18] 扁平化嵌套数组
来源：http://dali.0kj1m.cn/Article/details/gttyroyrps.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gthyrzbhmy.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtjtmvwish.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gtfwgxyycc.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtkxcftgvw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gtnydvpkwj.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtxchipufn.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gtotdpwhmz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtvjeoezwz.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gtxkejxsuo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gtispjzbsw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetvqldaw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgnskdbz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtyxlsxerd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtsrazdmbx.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gthfdgixto.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gtuljzostp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtdwsykykp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtzdrrbdcy.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoonpmopq.html

PHP:  array_count_values($arr);
来源：http://dali.gzhubu.top/Article/details/gtpbrxxztw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtphsymeyh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gttpbehunv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtjgfhutah.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtsjjaczso.html


<!-- 参考信息 -->