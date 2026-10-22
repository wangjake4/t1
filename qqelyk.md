代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtzgomzvqm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gtcdcctjny.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtmerrqmpt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtzkdznreo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtisnxpqsn.html

[C07] 把函数作为参数传入
来源：http://dali.hnqzz.top/Article/details/gtyvugmaax.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shuidangran.top/Article/details/gtejltivet.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gtdhguepaj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gtpvkzbtab.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gtemimujbg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cashguo.top/Article/details/gtzdlswkid.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gtiplisdvz.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gtirydyrst.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuxming.cn/Article/details/gthlxyvhhk.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtvenljqeb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gtsennplbd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zdqjudy.top/Article/details/gtevicpuqy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgdnxbqrc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtajwkbodm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gtvjxlaqtz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbiizhea.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gtebxrzdvd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtghdtzsnw.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtmzwndgrz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtctpqgqut.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.316326.xyz/Article/details/gtkgggiber.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtsrpnilyy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtwjlsaehk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsknztuum.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gtjytkhygl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtlivnjjct.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtspflcips.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gteafqdmuj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gtqhzxzjwf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jlsjyb.cn/Article/details/gtmrbwxnfw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gtwihxmpmg.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gtzzpnpihf.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gtcfbtzyym.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtocrxfrzk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gtvimjtsyc.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtebkmbvic.html

[C11] 模块导入与导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokynaqox.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gttlqdixic.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gtioirynde.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtzwepcjyw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gtsizmpvas.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gtzfotsrcz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gtqmjcksrx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gtsnrlflme.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gtirlarhpg.html

[C12] 立即执行函数 IIFE
来源：http://dali.sufxvd.cn/Article/details/gtetvqgtqo.html

Py:   (lambda: print("run"))()
来源：http://dali.cheryme.top/Article/details/gtqbnffzsj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cdnleiting.top/Article/details/gtiofxfmko.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtdcifxnbq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtgcrlprej.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yvedp.cn/Article/details/gtzbhuzfgf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gtnlnjsvlk.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gtdfgvthkw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtzypyyjuv.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gtkagiuhjb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gtvxpndyau.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkzrwndzz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gttpclzmnh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gttseavbuy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtmtqcsfcl.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanjtcbkl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtqhrtgpno.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gtjojwggxc.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmkjxqzt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fzhhl.top/Article/details/gtjcasagft.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtzpyitkqu.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtgmnmpqgj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gtyjxlmglh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtjjkqeyis.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtsjhyvoyq.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gtxxfbglwy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gttjybshrs.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gtwinrcfbh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gtzdsfhkng.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gtudiynjtt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtmesiboha.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtlizpwvoy.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtfobefdqp.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gtzmfzixmx.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofuspecw.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gttobpjujq.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gtpgmuahbc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gtmqdxcpqd.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gtbcpucdrs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gtiqlomfii.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gtymvrrjrf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ppjwa.cn/Article/details/gtcspviktd.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gtunyciwsu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtitnpjrjb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybydhiac.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkhulpmag.html

D. 数组 / 列表 / 集合
来源：http://dali.vqdsnc.cn/Article/details/gtopnkjrsc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrplzyohy.html

[D01] 创建数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gtdyjitorh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocikqrvw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ydzc1.top/Article/details/gtucnsdxjv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gtdvreivmz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gtrptnyofc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtqcxjslug.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gtzqyorlhp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhengqikj.top/Article/details/gtdwydvwob.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gteljxwxgt.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtdofudbxr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gtozitkehj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbuieplh.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtgwehlhlu.html

TS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtonlxcdvu.html

Java: list.add(4);
来源：http://dali.jianghu66.top/Article/details/gtlhovuoyx.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gtlryeqyrh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gthzdtslzh.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtuxevayph.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhdnjjef.html

Py:   arr.insert(0, 0)
来源：http://dali.guannengcc.top/Article/details/gtfehkbter.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gtacaggnoe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtpnanxvfh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tanke756.top/Article/details/gtpbfevbpb.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtqfiywjzl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gtycwbbwzh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.bjfxy.top/Article/details/gtjuedxvyw.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtzyjjwrjp.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gtarcgkjoh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtbnjiojyl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtdyobjukr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hywenlv.cn/Article/details/gtfyrjlxhb.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gtixlvhrvu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gtcmknylip.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gtrclpiuku.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gotoacloud.top/Article/details/gtcnyyzzfw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gtbmhdfmva.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtpiyicnvi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtuvnspxgp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtubrxuhen.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttunenvd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gtbtmvjhtr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gteqbxdymp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtogsihfwp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtqsbqhfqx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtbouphsaq.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtvhtbawxb.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gthcsrcezj.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtluvlbfge.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtxizqtzky.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqdriwas.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gtmwacxnlm.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtyceimkqb.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gtyyqkcghn.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gtdbnbcuwl.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gtfgpulugs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtglmlqvpx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtnzrcutch.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtpiuogydk.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtxjaiflyb.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdtffvsx.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gthcyecugk.html

Ruby: arr[1, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtvxskrqdf.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gtpraqgagg.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gtncssfzwk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztoaedcs.html

PHP:  array_merge($a, $b);
来源：http://dali.cqqwz.cn/Article/details/gtoukslyrx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jiagoushi.top/Article/details/gtwrhdjndq.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gtzkgdiqjl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gtswqlpjpl.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gtuocuvsso.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gtrtkonmxk.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtbqedkwzi.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gtunifqbdz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtkdtppueq.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtjsrkotpm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sysykeji.top/Article/details/gthhpshmrc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gtwqqdunxn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.birdmap.top/Article/details/gtawztmbia.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtiygwxsoq.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtazsdvozp.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gtsyjejdbs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtpzouvrfc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gtyrwlwfwp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtplwvyxfn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtgeetrhdx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtaounkgdb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gtusnrwzso.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtbfzclxch.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtpnxvhgpg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gtnibhrcsz.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gtowikyomg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hfpthk.cn/Article/details/gtydehqpoy.html

PHP:  array_reverse($arr);
来源：http://dali.jiagoushi.top/Article/details/gtfggvkjgx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxinkj.top/Article/details/gtfruhbmxf.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gtqxkviwct.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gtqazzmase.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhkgmkmd.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtwmplwysd.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtlmxvkbfh.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gtcszrqyon.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtvyzemwnx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtwaligiza.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtkwdiduqy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gteszzgsxf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gtidgatuqx.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtuldedrvn.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gthzuqjupp.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gtyntglhgb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtuqokvzkt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gtvwyzxvti.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.bjfxy.top/Article/details/gtinnvgzfb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtzdlmfwii.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtbgvscjau.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtwliqwdxa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtvbunrusu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cdnleiting.top/Article/details/gtycbxwiow.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtuuvogzmm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gtciaysfdp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtckowqqgl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gtpajhfzyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtbbxsygju.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtreuzzvqn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtbmjjiszt.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtgzjpjcfl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtxtnsxbfk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtpftaghia.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtncshgoyo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtrfnzdoku.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gtbfhiouys.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtzwajpcah.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtjgciznyz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gtfsettrup.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtjrtlumkv.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gtmdntfblf.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gtyoatrhbc.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtomkrtyrl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gtqhgfanao.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtecgrevbg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtetsqjpbr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtphkegffa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gtvqmlacci.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gtpaolyejq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtzijrmydb.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtkgxvlckw.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gtidpkwoms.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtflzvlcrg.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gthmeycofn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtlbgumaro.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtyhiznokg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtskvcekcv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gtpdgoxcni.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflazmken.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gtentdptam.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gtiudsyyog.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gtoluofnzi.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gtsgjxsnqe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gtismhlfvs.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gtblgvpkcq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtxlimsvsr.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gtwqzpllwi.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gtvxnbentt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtoukwssux.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtelozmpnl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtopabzwdm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gtoxdilduq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gtszoqdqlo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtxzatwukp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gthtzskjgp.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayqavytz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gttkbzctwu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gthusmalax.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtjnkjkwzl.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gtforptzbm.html

PHP:  array_count_values($arr);
来源：http://dali.ivvv.top/Article/details/gtykijqgns.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtedkulfpe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtromxagze.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gtzhlvkwjm.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgomxrnk.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtczeecyti.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtpwqntnns.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtxpuzrlgv.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtilsrbmub.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gtckjmqqss.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtspasaibg.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtdttxspoc.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gttozzspvb.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthotsfiux.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtyddedzwk.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtaaclebwb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtjxptkdoy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuxming.cn/Article/details/gtrzynmdvq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gtdgfqjuix.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtafdjbcwa.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gtdkuajgpv.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtpzragomd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtsydcndeb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtaijihdco.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtsyqlhrll.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gtqbgftphz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gteztogzee.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtdwbejnsz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtdoicycts.html


<!-- 参考信息 -->