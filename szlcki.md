代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gtyqaucpap.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtjxfbojbw.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gtcqtmukir.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvlvzdhx.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigufen.top/Article/details/gtjsriiaro.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gteomsbsba.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guannengcc.top/Article/details/gtkatmpnfh.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtewpyyfib.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gttnhxyjip.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gtkhctjpwg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtznrcadta.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtilhfcwfp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzonsbqzy.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gtudsnbtik.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gtuldyenyc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gtcpdvkytm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtucwlwkow.html

TS:   arr.map(String)
来源：http://dali.yj20258.top/Article/details/gtnwlqdxxg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gtdzwhwrxb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvflkddbx.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gtrojshhpo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gtwfcvjhza.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gtrkcdrsvx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gthyibmawh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gtsmvlmchc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtoxlozjcz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtrfnltnuf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jianghu66.top/Article/details/gtyguiitas.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gtsfysiojj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yvedp.cn/Article/details/gtypqwrkfn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gteiszqcob.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlcuqvgq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtjkborlwx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlsipjwb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gtlqffynje.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtliqiakpa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtgqvitzqz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sufxvd.cn/Article/details/gteegkzdbq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtwbcgugzw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gtyvqlsqcd.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtcvtevsto.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gtdvkckbdo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gtalxkhupb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gtupuintre.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtcemmglmj.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtusnjjsqv.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtzdeoexsw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gtbmljtydt.html

C#:   块级作用域
来源：http://dali.sweek.top/Article/details/gtrpbfxdhf.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gtpepxcuxv.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtzwnuyjqj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gtkogwgwcc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gtwgxsdbfi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtcoddtscz.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtnwmwdgzp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fzhhl.top/Article/details/gtldkpjaog.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gtohvcnxmb.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gtjoqcsfva.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwammsvv.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gtraziqdwt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gtxblrcbpr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhjfspax.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtqszmouba.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ppjwa.cn/Article/details/gtdoluzaxw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtyiwqnrmf.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gtsacifnwk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtzgbjhrdc.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gthudluoop.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gthyqcnges.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtvxckqwrv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxuanxn.top/Article/details/gtbqbzhhxj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtxbztgyyl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtdygdmttz.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gttimwsexa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gtveedtacg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtlxfnmrot.html

[C14] 泛型函数
来源：http://dali.jqgfzy.top/Article/details/gtwhheyrzs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtdzfckapk.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtvjdmxkro.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtkosswsjj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtqhoywmtp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gtzmcspmmm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gtedtzeevh.html

Ruby: # 无泛型
来源：http://dali.ivvv.top/Article/details/gtrpfblhmj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gtbvnjofqv.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtzipuixci.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gtdexojrch.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gtzckeydcl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxsqlllmk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.redwolf501.top/Article/details/gtnwuafjam.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtprftdlqb.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gtkijamovp.html

Ruby: a, b = pair
来源：http://dali.cheryme.top/Article/details/gtreopkdxf.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gtqtmglhpp.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gtsyoqdvbn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtxwslzjlt.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtddptjfst.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gtqbzhooqv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfvzelyj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtkhyrtqav.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtdxsbxqpj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gtuswvlrif.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtzlhamyot.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcsqcpslw.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gtyhbxxyid.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgzebowzj.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtoyvjwqwd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtnwwqrfbv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtlpzgbbdr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtmjptzxup.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtdfmbfyrm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gthsqlxjbm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jianghu66.top/Article/details/gtbubvyeaj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtyecrqgpy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gtyltrurbv.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gtoxlqdxlf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nwbrower.top/Article/details/gteywerher.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtnmxctdys.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtaqfusvif.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtpjijtgrc.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtowpkmnww.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gtmfitsrbt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtichcmdil.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtjkbpkpxp.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtbkzgazbs.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gtgjuyshjd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntmivlgb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gtojmtyasg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtxxfenztr.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtalaecbnb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gttruuujvg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jiagoushi.top/Article/details/gtgmcfewpl.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtankwicsb.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gtytjmqlej.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zycfv.cn/Article/details/gtqzhphcoi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gtcqbxpwkb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrhtcshn.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtylfmqcmp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtylvmgjpg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gtdthdljxu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gtugulmjpw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtxeaukaty.html

[D05] 访问与修改元素
来源：http://dali.yangfankeji.com/Article/details/gtkpamwruf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtkhfqblnu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtsqlzfapq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtwrudyltx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pengpengdd.cyou/Article/details/gtoswalvdw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtivpvrdkk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtggyphztu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtsofjwadq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gteqovqahb.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gthdduebgy.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtkbgpmdrn.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtjcwstiro.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtjdqulozq.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtyzmazqdn.html

Java: list.size();
来源：http://dali.feifeiyinyue.top/Article/details/gtrittrhjm.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtzkcqdxjl.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtqakftylx.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrmrgfkx.html

[D07] 切片 / 取子数组
来源：http://dali.birdmap.top/Article/details/gtdiawxoeq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.quarkkingdee.top/Article/details/gtwxnviirg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gtzubsyobh.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtzwpjoxgz.html

TS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtjiwlyyjo.html

Java: list.subList(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtpfjgtksi.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gtekznpgti.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gtqidrrnlw.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtklsxsfaw.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gtqxlzpxfr.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjzvqkhn.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gtzzwmogvw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hywenlv.cn/Article/details/gtuytiqzfo.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtpyeqxtvi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtpckgkmrw.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtuezvguhk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtjxczzppl.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtudjtlgbh.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gtpmhkvkam.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtdufpirar.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhzeqoyj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gtfgoxxknq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnxiangtu.top/Article/details/gtegohqkwy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.haohaochexian.top/Article/details/gtzvivnhew.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtjggnxazj.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gttgtqzlfy.html

C#:   list.Sort();
来源：http://dali.feifeiyinyue.top/Article/details/gtlqhennfh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258.top/Article/details/gtbxiutirq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtppjktdmh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtkbddlwam.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtmahpawrk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtjgxwgknz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gtxaewlzal.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gtkonhjych.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gtkosphybf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtfmaiiytk.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtshoenhud.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtwerutehk.html

PHP:  array_reverse($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotwboejs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gthcatayaa.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtdvfsfdsp.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gtftkpxnem.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gtxxxmfcdl.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtmlqstikd.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gtvujjrbxw.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtlkaubwlr.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gtgjlekyfa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtxbldbjty.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtswtyrsqt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtxvzopruv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gtvckzvzzg.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnaantyqq.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gtsjlydcqk.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gtegvpdcac.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtfuifpqpe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gtgjwcvdov.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sufxvd.cn/Article/details/gtypzljnsh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtlhygpghi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtxhyqspuy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gtxpnrxhmq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetgwzxcy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gtafspvcev.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtjyueeyna.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtjwwjyubx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gtuzdjhnap.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtnycmtiej.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzprjzedw.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpsznjaf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gtlfmuvcju.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtgpembwhq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gtjbalsdnr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj202588.top/Article/details/gtvtolqkmo.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtesanxdto.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtrdvpojud.html

PHP:  array_unique($arr);
来源：http://dali.yangfankeji.com/Article/details/gtowgcnulv.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtmpaiifax.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtntlphxqq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gtrdhohhft.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtotoktkgz.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gtlhoyaiaf.html

C#:   list.Distinct().ToList()
来源：http://dali.zhongyouzk.top/Article/details/gthnjksncr.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gtxjktsdqe.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtvnoywhwq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtkihlsjsp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtqhfnhadb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtjruzhuru.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuanzhike.top/Article/details/gticeishqe.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtpmlrksgq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtgrnvoimn.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtxvcrllku.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gtsergtypm.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtvilntiey.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtfmrtmosu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtsxogixdg.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtdnolluax.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gtwcckvgdo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gtfiebdvwb.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtkkjcudzu.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtyzsjsjvn.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gtbprlvpkk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gtmiceeupg.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gttgiuxrko.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gtgihsaeup.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gtsqtafany.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtpzsbxvnp.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gthmdxjubl.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gtqxuqwvrf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gtbngdqtlb.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtxgewpxpn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gtgqhtfehl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gtfxvzxckf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtaydncxrb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtpevwfvhw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtmdksyssz.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtoovagirs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yonumen.top/Article/details/gtycwenzgu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtnellirdt.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtbidzmpwg.html

Py:   Counter(arr)
来源：http://dali.smart0.xyz/Article/details/gtqixrkdhz.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gtjafnqqtm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtlgcbrmcb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtptrkzcam.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.feifeiyinyue.top/Article/details/gtlrkmhjhc.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtlezelpcy.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gtfxoiywke.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gtcszlfigv.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gtlmmgaxou.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gteqsyaemu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gtrfyxtevo.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtovjcpxwc.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvxelmwk.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtncfkrvhw.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtbnyvdhjk.html

Ruby: arr.include?(x)
来源：http://dali.xuanzx.com/Article/details/gtmjqpgjqa.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtkcsqfzux.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ivvv.top/Article/details/gtsqibqrne.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gtiwxedpjs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtbwbreocc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aizwys.cn/Article/details/gtioaffmda.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gtqybympva.html


<!-- 参考信息 -->