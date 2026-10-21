代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gtxchnpwbb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtyfbnfpqn.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtxwgqoaef.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gtsgbswycl.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gtldovajen.html

PHP:  return [$a, $b];
来源：http://dali.daxiang520.top/Article/details/gthtueqtjk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gthhguihmf.html

TS:   return { a, b };
来源：http://dali.yj20258888.top/Article/details/gthlbatapn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqgewcbz.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtoftubrtg.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtowootqpm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtjcqlhphk.html

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gtlhbktmsi.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gtowtutofl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtviyfazjm.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtuauofcul.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gtlgjvpmza.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtxiowgriu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gtqccawvaa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gtyylvdbpm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gtyegcbksb.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtngfjmtqb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sufxvd.cn/Article/details/gtduasddgr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gtahmlfqgk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gtaqjubqat.html

TS:   arr.map(String)
来源：http://dali.nanxinkj.top/Article/details/gthjuolxxr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gtnkyecipw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gtqqokmmwg.html

Ruby: arr.map(&:upcase)
来源：http://dali.guannengcc.top/Article/details/gtkalcnyqw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.c1oappe.top/Article/details/gtlbvccwuc.html

[C08] 闭包
来源：http://dali.tianlin.xyz/Article/details/gtzmknzsmv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tian-w.cn/Article/details/gtoikwyaxb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtwwkesjeg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtjbamyivc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtoljawlmu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gtgnknorez.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gtnmufbmtu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gtneoruumg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gttjsztxvv.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gtrxyvkcol.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gtmbpwdygb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtkmjmovjn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtrzambhzp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtgbbnuqhg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtgiierlch.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gtfzjccjeq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtovdmpfpw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jyoumei.cn/Article/details/gtccbutwip.html

[C10] 变量作用域
来源：http://dali.yvedp.cn/Article/details/gtwjkhblkc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyubygux.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gtoztynuzt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guowangkeji.top/Article/details/gthuqzeket.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gtzhiphlxz.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gttzpeofpr.html

Go:   花括号块级作用域
来源：http://dali.wangdashe.top/Article/details/gtkjoyrrbk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tanke756.top/Article/details/gtzvxhvzzm.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gtaikwdzje.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gtdhfbcfdi.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtohclfcxg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gtpvcfohya.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtnrcgylbr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtzevaamzz.html

Java: import java.util.List;
来源：http://dali.mhx1999.top/Article/details/gtqezmztef.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gtgzjmlsmx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gtebvhdtyx.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gtpcerdnzx.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnqzz.top/Article/details/gtvcpmyozc.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gtclldnhri.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtdnjcvycp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtxneololm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gttgjdpzvm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aizwys.cn/Article/details/gtpasnuhje.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gtvlimroef.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gtxvknxwvk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gtijrptxme.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gtaxiaidji.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkhpziwg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtapprapeh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gtzbpdzlkc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gteatlxhxh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtdslystiv.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtugurijto.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gtttzbggiq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gtwyqxlnbb.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtogmjrvls.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gtgiwdomtr.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtqqibgwdt.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtqzmwzhgn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gtwetvfrwk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtjawfyvjf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gtnebdscbm.html

Ruby: # 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtvkjnmyie.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtjmxguvyd.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtwmmvuyzo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gtgkcmptjb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hysaishi.cn/Article/details/gtprfpqcwn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtqijsmiut.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtshjycxus.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtjmfpzvpa.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gtruljhvie.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtefwbxbsu.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gtbqilnaoh.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gtklyrrdnv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtrzldksxh.html

PHP:  // 无重载
来源：http://dali.c1oappe.top/Article/details/gtgpfalmvu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gtxyqrdbxe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtxxcfalkh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ybcxt.top/Article/details/gtywviozvy.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gttaamrttw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtxyafhkap.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gteonxrvnk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthcphzvni.html

D. 数组 / 列表 / 集合
来源：http://dali.meibo888.top/Article/details/gtuzunifzn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtogewspqj.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtttlnevrh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtchmquppp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtflvtdfwr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gtlqqgrler.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtdrrzkeek.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtpfxrbips.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtriyvmvlp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gtuedohbba.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gtgzabtxvq.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gtdbfglnxw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gtpjhwximo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gtbihzzycy.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtwgskswrq.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtbjdnprzi.html

Java: list.add(4);
来源：http://dali.c1oappe.top/Article/details/gtrkevigdd.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gtpmtplxmj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gtlrkwfhcq.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtnjfhdzia.html

[D03] 在指定位置插入元素
来源：http://dali.pengpengdd.cyou/Article/details/gtbrjgcsjn.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtpavigkbt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gtcsqhbpmh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvzwogur.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gtjuhzpydg.html

Java: list.add(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtfgksazva.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuxming.cn/Article/details/gtlouanzfu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gtoibhjqqx.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtbotsqiat.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gtwthxrdab.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gtnxidetpu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtmjlvxzhm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yueranfly.top/Article/details/gtonczxkpg.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtjbvdejjd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gtecgptjta.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmobjumf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtcnuijsvr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.feifeiyinyue.top/Article/details/gtnqbgjihq.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtcbbqhync.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtrowuekjt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtmuitmhom.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtfndrtfbs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtiprmbggj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqtksgkl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtgraswpug.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrauhpre.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtybssqzaa.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtiazvgphk.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gteuifgoki.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtvkxfqqen.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtmnhtndfv.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhxraymy.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gtegjyvzps.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtphufpc.html

Ruby: arr.length; arr.size
来源：http://dali.aizwys.cn/Article/details/gtaboyzvfc.html

C#:   list.Count;
来源：http://dali.havefunace.top/Article/details/gtvavdvday.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtvchevjfv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gtsxjdavpx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gtwebfmwlj.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtqecjmltq.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtatutfkrs.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtpubrofjo.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gtrfyfimmy.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtlsvlhwxh.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtgzcnylhr.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gtwmmqpbbb.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gtkqnxcnzm.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gtlprrxphp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcddmnpi.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtxxqrxdno.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gtpxbebnzn.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gtqgkyjnns.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtnkloahjh.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlietrrwn.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gttsvmkbxf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtcbvyrzyr.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtifhewpfe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gtpqliecod.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gtrbzqcmaa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtiewdkorp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtrupwuizp.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtycxfxmib.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gtbtqujxmb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtvyxkkmnu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ppjwa.cn/Article/details/gtfwjgpqdp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gtktdepfkb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtknhgcmpo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtlikydndn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gthdubvxkz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdotmhop.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dianchejie.cn/Article/details/gtdqfrkqqi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtlvnvbenr.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtkfmqudhk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hfpthk.cn/Article/details/gtnlltvcja.html

PHP:  array_reverse($arr);
来源：http://dali.mhx1999.top/Article/details/gtgymlrbik.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgugpfym.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtcmunvwym.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gtwaknzhrs.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gttmxdjfev.html

Ruby: arr.reverse
来源：http://dali.fengsongda.top/Article/details/gtfhrjmtjk.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtgkdsmjsk.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gtziwyvlap.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gtqfjsidlc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gtdbpfmrys.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtfmycwhec.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtgjhekwhi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gtfrxukift.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtrymouczf.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtgirdzwis.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gtfsjntznt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gttuvfkmhc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.haohaochexian.top/Article/details/gtrapeupkh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gtydqocffx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtkfhbowca.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtqgaxjifi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtulmhjone.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gtgyqhvdts.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtusldgksb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtryjvybqj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gtcrfkmrsi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtizbplyzo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtzwogcqld.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtcmwnyxrz.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtinprtgkg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtszxrdduv.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtfdjlmrjb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtesxumxrc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gtzomfhiea.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gthuisxbsr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtoxewjkfi.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtztxhrqdp.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtwpgajrmw.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtpthwptwu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqxthjrg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtoiguzdow.html

Ruby: arr.uniq
来源：http://dali.yvedp.cn/Article/details/gtqhiaymyx.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtrzqheyzu.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gtmhcguxmg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gtcxhvmytg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yvedp.cn/Article/details/gtdpnenxrm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtbmgkylno.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtpkmpjzlr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gtcgyolytr.html

Go:   // 手写循环累加
来源：http://dali.fengsongda.top/Article/details/gtdssnlglf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtrtumuurb.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtsbjjmjfp.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gteqdxmrri.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtofwvfcdg.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtdcoskohu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gtjcgjbtfc.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtiwcacinj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gtajaflkxh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtbrkulrcx.html

Ruby: arr.max;  arr.min
来源：http://dali.tianlin.xyz/Article/details/gtkhvrckca.html

C#:   list.Max();  list.Min()
来源：http://dali.ydzc1.top/Article/details/gtzyyxoyrn.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gthgbceqfr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gtkfwgcugu.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtclbtwick.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtdntyyjkz.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtxwwluvxl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gtdljhbbgs.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gtmufdncey.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahiuqhik.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtegevlvbg.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gtletvvvba.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtfmatvvst.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtvdhpxluy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gtzldauckd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtrgqsgjit.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yueranfly.top/Article/details/gtfeygfkoz.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtgxjfskid.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gtgqwgrigb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtesbfmdcp.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtjmystbui.html

Py:   Counter(arr)
来源：http://dali.gogol.net.cn/Article/details/gtpzdulfdp.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gtdzsohyqp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfrpocbb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtllnptwtt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtikddhuxt.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtbtvxhgcs.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtjgdowqnj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtdsttdhfq.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtojyxcfrl.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtcwfbqoqz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtzoqsmemc.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtodqmqysm.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtvqgyyuyr.html

Java: list.contains(x)
来源：http://dali.wangdashe.top/Article/details/gtkjlwarum.html


<!-- 参考信息 -->