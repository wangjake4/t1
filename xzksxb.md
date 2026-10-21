代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gttuizajes.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtngzmprsx.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtjabrfrvo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gtyzipemxp.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtfxabrrll.html

Py:   square = lambda x: x * x
来源：http://dali.hnxiangtu.top/Article/details/gtvsuxdemj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.mhx1999.top/Article/details/gtppqazszw.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgvrhmnt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtgifqunvr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gtahrzxros.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gtyajfmbup.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtptzgmlip.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtxaxglknv.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gtyvqbzcik.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtogimntib.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gtlqeysndl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xinyue.icu/Article/details/gtkzkrmugo.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gtieblyyvd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gtovzxsark.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqrxojjz.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gtyxiyocwb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gtvwkghamn.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gtimdvkrop.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gthubtuhws.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtlpnxkduy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtlzgdvbcy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtrdccwljj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gtvgbnpurp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gthnmrfqqc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gtalvmpdzh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtieejaioc.html

[C09] 递归
来源：http://dali.chenlongwang.top/Article/details/gtmskucuba.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsukbribj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtusuvgqfs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtwmbiyuxg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbozcboz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtpjlhoalo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gtlcxfqgni.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtozlxobxt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbtwzsyd.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gtnfhhenik.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gtvhidjhka.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gtwqhxnmkn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhengqikj.top/Article/details/gtxqsrtopv.html

TS:   同 JS
来源：http://dali.nwbrower.top/Article/details/gtqeznhezx.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtlmvajean.html

Go:   花括号块级作用域
来源：http://dali.c1oappe.top/Article/details/gtykfybtgh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gtfdmiuozt.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtueyekucy.html

[C11] 模块导入与导出
来源：http://dali.gotoacloud.top/Article/details/gteftvywzc.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtvjlbfvdq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gtbkclnbwr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmycpydtz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtaclshmjh.html

Java: import java.util.List;
来源：http://dali.cqqwz.cn/Article/details/gtxiaoxjad.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtkwpuhrak.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gtlnonlofa.html

C#:   using System.Text;
来源：http://dali.iojbl.cn/Article/details/gtgbpsxrqh.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gtkbbdvqgz.html

Py:   (lambda: print("run"))()
来源：http://dali.snrcjt.cn/Article/details/gtbxrdwgib.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gtzbfnhhcr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtqbqwczof.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtnziufchn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pycfn.com/Article/details/gtpdpynlac.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtwhkkkmem.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gtafhzgfnb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gtrjgdyipy.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gtkprfdrxx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtdmbbbcek.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtblfonzpy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigufen.top/Article/details/gtomhikiiq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtyjzaixcn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtrenybkkt.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gtopqzyher.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gtkurzuzgu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gtpjokgehd.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtlonbvbuq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenlongwang.top/Article/details/gtycgeqtxw.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtoseopnqp.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtykznvjvz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zdqjudy.top/Article/details/gtbunwdgoe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gtfollcdvo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gtungologi.html

Ruby: # 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtuoolbdnw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtdvzumfzn.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gtyrhdiknd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gtxormvous.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gtxvadlqwc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtyvpfmnzm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gtzzlsvjbr.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtauciajyu.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtzxgegleq.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gtoztxfyyy.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtgdfbvjip.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gttygqcoib.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gtrynnbccu.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gtfmtubdlg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gtjyknyors.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gthbycedni.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gtwjlifgjb.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gtkjbeztuu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwfkyqlm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtxmxwzozg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtyivfvchu.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gtyljveqnc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqjcscmwg.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gtgxpqltqs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gtfgudcndz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtrcskuzxs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtyldrdzko.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aibaodan.cn/Article/details/gtaacwuftv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gtjmecuyee.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gtdacdixvg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gtyvpzmzgj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gtnlealeqr.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gtgwuiexqu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtcmytwdmu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtvgpyonbt.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtppictpgu.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtenlxoihr.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gtnzrdosgg.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gtmknqjgme.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtdpemubfm.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtvghjzips.html

[D03] 在指定位置插入元素
来源：http://dali.0kj1m.cn/Article/details/gtiqxcjnla.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gtnwlqomzi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtzlrqxizr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhoulong.xyz/Article/details/gtnckukvmv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sweek.top/Article/details/gtiipnmtlz.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxvzicae.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gthfgzuoep.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gtyzzjvggl.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtlknqijae.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtygoglrrc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gtylsecwsh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gtmyfxbyav.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtkubvaxsv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwskrpcq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gtcfogutzd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gtlzxtiunq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwgdoimm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gtjzwejklo.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gtlxsqmzdu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtsvkjmzoo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gttxibveio.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtwhmlgvuh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlzysynv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gteokccobl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtfpxqckxb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtdbnurdwt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtpmwugpnd.html

[D06] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtrcuetmvc.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gtevzdmdlr.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwgtwtbs.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtcvzlabcw.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gthvabfrjm.html

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gtoyjdqigb.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtkswxadbh.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gthjkucdci.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtsusndnbm.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gttqzbzgkz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtiinjqoxk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gtvbnhtraq.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtsuzmawxf.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtprzqbtyx.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtwosiaenp.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gttvnqzxvm.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkazvybqn.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtxoyjjxqx.html

[D08] 合并两个数组
来源：http://dali.gzhubu.top/Article/details/gtztpedhza.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gtcjxubgsg.html

PHP:  array_merge($a, $b);
来源：http://dali.zhongyouzk.top/Article/details/gtpooathwx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gtomwefxhu.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gtxrctlmxy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgfzy.top/Article/details/gtsvqgcqdc.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gtmfniasdd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gtthadgvbp.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtenwhabyd.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gtiuvmcelr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtqurhzges.html

PHP:  sort($arr);
来源：http://dali.gzhubu.top/Article/details/gtpmrefsmh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gtcncrubbg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gtjfoakmyu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqaobzekb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtnlxcsxco.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtamvmxhzu.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gtwanbzcik.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gtgbdjyggp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtkiyidnnc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtzylbfmoa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtoiyotbwd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtocerhzhh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gttstqpxyx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqpjiwpq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gtvjmuihrh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gtwsjdnchy.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gttqasgjoq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvonqglh.html

PHP:  array_reverse($arr);
来源：http://dali.xylfe.cn/Article/details/gtpckoqxiv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ppjwa.cn/Article/details/gtmzjngazv.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtcarrvlip.html

Java: Collections.reverse(list);
来源：http://dali.vqdsnc.cn/Article/details/gtkgrohvoz.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gtyndbuwwn.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gtkwbrlozq.html

C#:   list.Reverse();
来源：http://dali.bjfxy.top/Article/details/gtjklcvsju.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtlynbkjde.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gtucrrmhhe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtqvxhygsq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtmyeaazkm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtkskmivub.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gtwpmazzvi.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtyembezal.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gtmlbketxl.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gtkccdfben.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtzgjgbibu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gtdmbguduw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtvtthxlia.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtoxxynwpu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtxmzaalvi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gthmydndos.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtkepicwqo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtsaracuay.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtswfuzygg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gthuovyjby.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtlzgjoklk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtsmgduqbz.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsywxcem.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gttshjttxo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gtgzuoqoph.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtinerdngk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtysgwpvhi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtqsdpcbsl.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtxqhvqgxo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkintpjob.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtkrqkxsyc.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtnfmnwswv.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtmoqiojri.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtgansqrxq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gtezaxurij.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gtpmudbzwl.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtmljkqzgk.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtxciunvtl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gtusvgzxti.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gtaaxhfsgt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtnibmytin.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gthjmvlvmm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gttwpehsxb.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gthsvqfqws.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gtafjtvyus.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiifueemy.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtudqrqeaq.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtclusoocq.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtjpscccha.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gtxeajfvzx.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtccliqswb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gtluezpdde.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtyqsxvrdw.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzdnxief.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gtmavxefma.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gtqxdbaciq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gteormykcn.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtxjjfaehy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gtfuhlrkww.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrffrcaxd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gtsenxzvie.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtxtjzsmvs.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtdjvmirij.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtbuxqmqja.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtvwfsboas.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtvfslrifu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gtwzalbbll.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gtgriabyly.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtirdomucg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gtzigcmdfl.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gtrspdnnmf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gtsinzzfjg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtimjjfuhf.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gtpmuwomeb.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gtiyvkfgrp.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlpwqgwc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcfwnrly.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtfkzgbfxa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gtoezelvfp.html

Go:   // 手写 map[T]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwzgowlc.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gtdigvpmtz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtduozxxya.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gtrhqfatgs.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gtequrwbfq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtwdpavdmn.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtzqfgrqdy.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtrdwgqcgx.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtdffkwfho.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenvxxafg.html

Ruby: arr.include?(x)
来源：http://dali.jianghu66.top/Article/details/gtsqdwxoiw.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtdoupwcqo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtvftecqxm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gtjvwefyqg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtccslrrug.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtmkgotmmp.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtuqfggthl.html


<!-- 参考信息 -->