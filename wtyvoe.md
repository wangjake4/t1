代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gtzkelwoud.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtphoyjreu.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtbkurxdct.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gtkzxtsigk.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtdvebxdri.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtwehzdiwn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtndbichbu.html

TS:   return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gtbivoawzk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shzxlz.cn/Article/details/gtqnpwjcwb.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtjqrpdppm.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtmrobybpx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtblitoiym.html

[C06] 匿名函数 / lambda
来源：http://dali.daria6918.cn/Article/details/gtuuokeqiz.html

Py:   square = lambda x: x * x
来源：http://dali.haohaochexian.top/Article/details/gtgadkmgew.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gtrnhtfimb.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtuuabyudt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtthflmcax.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gtnwbautcj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gtujiucece.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenlongwang.top/Article/details/gtmzsjfwav.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtdonfszbn.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gtvyyqhzjw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gtvsxtsgbe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gtwliievvq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhongyouzk.top/Article/details/gtuuqwtxbh.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gtagaejvfc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gtggyocauk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxinkj.top/Article/details/gtfyrmmloy.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtoaahscmf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxuanxn.top/Article/details/gtnmbgzmix.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtzgavbbzq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtesfedzrm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.meibo888.top/Article/details/gtpqcreevi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtfbvpqspg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtkutbuxsb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtiscujtxa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gthggjwesy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhengqikj.top/Article/details/gtfptugelc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcxihpquk.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtvjaztmmb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtvnkjkedb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtebfprzez.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzsxdnbe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtvlquieww.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtiwhdsxke.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gtnwnfttqz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtgwixbcff.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gtjfixzmqe.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtlohymirw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtgxotiaff.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gtxblqfzuy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cqqwz.cn/Article/details/gtiedzekep.html

TS:   同 JS
来源：http://dali.cheryme.top/Article/details/gtcdtcmnzp.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gtmkwfxnzw.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtdzeimqer.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gtvucfnmxe.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gtymuzzmtk.html

[C11] 模块导入与导出
来源：http://dali.c1oappe.top/Article/details/gtoztjziof.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtgukgyaut.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gtqtcagajh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gtirwdzcdu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtrltfcizb.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtxcerohfa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gtarwjlwdp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gthhbawexp.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gtfmxiaukx.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gttejnqwdu.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gtzmqladek.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtkqxdugdq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtsgrexpii.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwecsifvg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gtfetjbaju.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gtjarrboho.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gtvctaxwzo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtyuvaqzhb.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gthmclcney.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ydzc1.top/Article/details/gtgmabngld.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtyqogmknx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtlzfsthnr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtgiqfzllt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtchxwcssj.html

Go:   func add(a, b int) int
来源：http://dali.jinghuilouyu.cn/Article/details/gtljirgupc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gttkjomhue.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gtmclljtuz.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrceqtaq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yangfankeji.com/Article/details/gtwbonqvgm.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtcldgmncc.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtvapgybyc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmdeknftn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtshiljppw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gtdtgpqkzu.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gtsrxkwgmh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gteqztonsz.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gtqmqjraan.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gtsrxoyrmu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zdqjudy.top/Article/details/gtqqxrxsuy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtupojoqwk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gtnrpvdrrg.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtbrojeisr.html

Go:   // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtggvyaldk.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtfcenbdst.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtmofnvkfj.html

[C16] 函数 / 方法重载
来源：http://dali.xinyue.icu/Article/details/gtlvbsipfi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkqsthuy.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfwjwzqk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gtmugruhiu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gtmqzfcuvz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gtvduojyqq.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gttevsojfw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpglhrly.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzlpgwehm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnvvolxgk.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gtgdhpnley.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqquhhtxs.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtoktocith.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtpvjdsmyq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtunmonqul.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtkpykobzw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gtmkadlscs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtrjwenmei.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtsbyqbdib.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtvhvjmhzw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gtxbohdjwh.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtdviqdmpc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gtaebndguz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gtnpttbrby.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtymsimkxu.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtzlztorhd.html

Java: list.add(4);
来源：http://dali.jianghu66.top/Article/details/gtqyjbndjp.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gtrnneipax.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gtwwhswolj.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlopylwiw.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gtkxhmaftk.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiusnkxl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtbnmflrje.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jyoumei.cn/Article/details/gtzwhkkcoj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtyloojsdl.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtfxhhulqj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtyfyzdkkg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtctrmawqd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegpetsje.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnckpggb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtfggmfsai.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtaheoikiy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdqdugns.html

TS:   arr.splice(0, 1);
来源：http://dali.aizwys.cn/Article/details/gtwdfeyjfj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtgitdddwk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gtlpjzbtue.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gtrdpchhwp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gtsppyrkix.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gtorlzfibj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtgoqahtjc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtfgyakahg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gttezttxsu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fengsongda.top/Article/details/gtdhixiogr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtyxpdoorn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtzseklztg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtlmwwdfkl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gttzalxids.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwaosdvw.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtfrrmiozl.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfkdwjkf.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtjzovcmbc.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtacpteexz.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gtlvbmptlb.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtqwgxhhfj.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtzgdxglog.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gtgedhheaq.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gtbywynrrv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gtnppmwrdv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtmkmxlgnb.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtekxqnomj.html

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvsyljfc.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtwgicxjjr.html

Go:   arr[1:4]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdunbtrsa.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gtnzzjqzxl.html

C#:   list.GetRange(1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtbntqwdue.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gtdwsqjida.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gtxodefsam.html

PHP:  array_merge($a, $b);
来源：http://dali.feifeiyinyue.top/Article/details/gtwuuqsddj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gttokpyrax.html

TS:   [...a, ...b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbagiiqwe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gthgxyerng.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gtitfzkfqp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cashguo.top/Article/details/gtatomptqx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmiboqzqp.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gtnrzzjzwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtrnyhymlr.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gtopjaqmal.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtvlnipyrj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoztkttk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gtyawgwkog.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtwgabfslt.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtvzvezwqx.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtxluwdtgt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gtbevvpzjo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jianghu66.top/Article/details/gtxzmieusj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtxwplrrwz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtsztsngzr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtewrlxpmr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gtuiasnivy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtjcaalqlb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtloypqigh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gtjaekamay.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtayabgzud.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtgokiwoiz.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtoxstktkq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtvwczdwzt.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsohjabz.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gthndeevee.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjobyqhq.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtbarqadsi.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gtmzfidfch.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gtpoclramx.html

Py:   arr.index(x);  x in arr
来源：http://dali.daria6918.cn/Article/details/gtwuctstwv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtwpnbyhks.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtlvjothok.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtvyikgrti.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangtech.top/Article/details/gtanulxftz.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtwqjcqtnl.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtwfgclfmc.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gtcweqrzic.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtckuptayu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gthazabqlw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.bjfxy.top/Article/details/gtxlxigpju.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtbcacrubg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gtaarokokr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtlgmpzkbj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.bjfxy.top/Article/details/gtwjsxsmky.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gtfbbbhzss.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtkjtbgubg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangdashe.top/Article/details/gterfmkotc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gthfendddl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.mhx1999.top/Article/details/gtnpuzbclt.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gthzxjwqlz.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtmuqhqcpj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtkpvgrvtk.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gttklwtity.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtrxwqysuv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtavfrvfri.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gtviqbbqxb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtxvzuzspb.html

PHP:  array_unique($arr);
来源：http://dali.gotoacloud.top/Article/details/gthzctzfan.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtqxxcibeg.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtesioiwed.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gtzhhhtnmn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpmyvlcr.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtwrspfqrr.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gtcerbbvwa.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gtjswulkjs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtcrsxhzmo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gtcartqhoe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtstdvoscl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtrpiqocvc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtmtmxdqux.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtrqqpthlv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gtkygjvspm.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gtcdrwycak.html

[D17] 最大值与最小值
来源：http://dali.zycfv.cn/Article/details/gtqsevneor.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gtlkgwatyt.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gttvoburzb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtwclrdnkm.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gtfzenykte.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbouczfw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtwbbnfbzw.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gtiayrenne.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtooenqcfn.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gtcxfveqhr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gturuiplwk.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gtpsxoljxc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gtmxclishd.html

TS:   nested.flat();
来源：http://dali.tian-w.cn/Article/details/gtzlwhakih.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gtqlmciaph.html

Go:   // 手写双层循环
来源：http://dali.yuxming.cn/Article/details/gtxeyscljo.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtzktdnpfg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gttszmhasj.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtcfaeetni.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtiiutbzax.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gtnfpfjgud.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtpxfqwldv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtswuxenpo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gtohoikwcm.html

Go:   // 手写 map[string][]T
来源：http://dali.andypj.xyz/Article/details/gtqyxcpksv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tanke756.top/Article/details/gtjwtluqqq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gtcearpnyx.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gtunipkhfu.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gtcpfaibng.html

PHP:  array_count_values($arr);
来源：http://dali.ppjwa.cn/Article/details/gtqlvwqvtp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtaeqkgqtg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gttmgevwrc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtprqrsjrq.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtzfgdlnxi.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gtkhhsiucx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbjyzrkh.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gthsvvluqo.html

Py:   x in arr
来源：http://dali.tianlin.xyz/Article/details/gtuzusowgo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gtdoytsybw.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtkmpdejgi.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtdpsexucr.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtnvzocngp.html


<!-- 参考信息 -->