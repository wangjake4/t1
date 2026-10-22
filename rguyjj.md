代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gtvrwjawnr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gttjpncyvc.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtliszfegc.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gtlubdpodf.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gtjflywani.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtkuhvnjfw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtldespkfb.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtlvkcjygf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gttzqkijjz.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtjrgkjaou.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gtaeazihab.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.9152youxi.cn/Article/details/gtsmadauvg.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gtmfmbvjsf.html

Py:   square = lambda x: x * x
来源：http://dali.gzhubu.top/Article/details/gtytihnrbd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtxpuwmubr.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtyjubqsye.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtsgxugaqy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shzxlz.cn/Article/details/gtmbgywtur.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.svipenyu.cn/Article/details/gtjurllhli.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtlvqctiqm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gtmrijttto.html

[C07] 把函数作为参数传入
来源：http://dali.pycfn.com/Article/details/gtjbwzxwxa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ppjwa.cn/Article/details/gtcgparjdr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xinyue.icu/Article/details/gtrkzqumhf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtfgptpacc.html

TS:   arr.map(String)
来源：http://dali.cashguo.top/Article/details/gtnjlxiwjm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtypuxhiux.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jianghu66.top/Article/details/gtecvyjlpk.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrypmuqte.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.mhx1999.top/Article/details/gtqkiykhsg.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtzyytkhgs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gtemsrcmzx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hammf.cn/Article/details/gtzfbukatl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtvvezqgmp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpchwnjjh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtkvdbaynt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gtfxxbkmnv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shzxlz.cn/Article/details/gtftrpyhzi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gttiinttdv.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpetcrqeh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtfkvibslv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtylyabkrd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtxhccwyot.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gtspjwxwlx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtmtehxsue.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pycfn.com/Article/details/gtlfmjyrue.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtybteusbj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gtguuqjmxp.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtlalwsenc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gtzkixitrx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtnphbqmcp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gtvdotqagy.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtrhvtkzoq.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmemujpb.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtjfutwoes.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzeuabvdl.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtjtfdlcnw.html

[C11] 模块导入与导出
来源：http://dali.jiagoushi.top/Article/details/gtnikhnmjv.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gttnhvvcfg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcqrefiw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtbkscvkid.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtpddsxpiq.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gthbaayiwk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtpugkwpyv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gtrbgaeino.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtljryxfns.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gtfebafjmp.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gtzinyqmxg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gtapiwdldu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbniswjto.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtobonxfpl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxjcxdpp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gtofgwfsvk.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtlbtmcljv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gtcukvcsfq.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gtlbwzagrr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gtlkgcbgrr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtcvvkjvbj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gtuekjweca.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtlxarcswe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtoveaecmp.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtpihmzhsi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cdnleiting.top/Article/details/gtaxthusla.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfqpltga.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gtgapugvan.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gtzxwyozjb.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtrhfeijgg.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtaqrzuxbe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gtuxfhurnn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shzxlz.cn/Article/details/gtecsqczir.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfasayjd.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbowydpar.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gtipjoqhor.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gtotllynsd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gtcdbwlwsn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gtqluejvva.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtrkpwpigi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtplskeypw.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtqgomebjs.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtpkhvvblz.html

Ruby: a, b = pair
来源：http://dali.ivvv.top/Article/details/gtwgrzkmfj.html

C#:   var (a, b) = pair;
来源：http://dali.xziqi.cn/Article/details/gtnicegzlm.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtrcgxexqr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gtqgwutdtv.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gttpddosil.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtqeobexok.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqxshtoh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtdwuhddsc.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gtshoujmum.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gtwitqsffh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gtnpbetizl.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtnsgvbiiq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gtuaftctnv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtoihjfwjn.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtwxdzuaxi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gtvrzfbkhl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gttdnjbhrp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ivvv.top/Article/details/gtchvodmld.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbncliyk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gtqaosaala.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gtcaticnzr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtekaxakpc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.iojbl.cn/Article/details/gtktpimxun.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gtbqgbvchr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gtkuzpdwdl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtcekaevnq.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtkdpqdvqk.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtpannivdc.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtqfpexiif.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtomndvbpz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhengqikj.top/Article/details/gtnfgycssp.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtpmziaxln.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gtjvexmnbh.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gthrlvqzaq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnmdzfcd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jianghu66.top/Article/details/gtjllnjtwk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gtfgoiehrl.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtogizdcci.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gtghfqzian.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtfzqwlxmk.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtbxbclghh.html

[D04] 删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtpsqawvwc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gtlwfxktie.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtlyibdhdu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdwmnckc.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gtmgwcirod.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shzxlz.cn/Article/details/gtyfoyvymf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gthnscyomy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtgmkvehtm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gtnascygyn.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gtbqhldexv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtgbzzdjse.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtrayhjtnp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayqzwbpa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangdashe.top/Article/details/gtrkcxiioe.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.mhx1999.top/Article/details/gtymnvnorm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gthowjrlfc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtlisjvmzi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtmpetralj.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtupfexibm.html

Py:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtqrdefhru.html

PHP:  count($arr);
来源：http://dali.chenlongwang.top/Article/details/gthotjxaxv.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtqicrsrlc.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtebanysik.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gtfpofkqvv.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtbdfglzeq.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpgrgfen.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gttdhexufj.html

[D07] 切片 / 取子数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnyizddk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gtzekdgpii.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gtggqlfgpa.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gthiaajukw.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gthzancisz.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtldvohhoi.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gtuigwwvlg.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtuzdvhapv.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtiamdexeh.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gtpfzamzee.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gtperhiakx.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gtvdblqvvf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gtdbrvimvg.html

TS:   [...a, ...b];
来源：http://dali.jyoumei.cn/Article/details/gtoktqxyrq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtllbvbboz.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gtcelthhlb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gtscmbfyub.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtkmeoymmm.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gtcvtyofmr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtqnaxsnhm.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtfdchnucf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gtozittqcg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gtsmoqevpr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hammf.cn/Article/details/gtlyzbcnvp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtekjaxxrr.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtjxqswtst.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gtymvigjnj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gtgnnbrvfx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtjzrmcwaw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtyjmejegn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtbjcfjitl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gthtpjyokx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ppjwa.cn/Article/details/gthmzwmlqu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gtgzlyudss.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gtwglsyryr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangdashe.top/Article/details/gtzdokprzt.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtodpenzzk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtnspgjifv.html

PHP:  array_reverse($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtzbpgbqod.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gtlfsxondy.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gtcguezvyk.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtrwvksdza.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gtvslqphcc.html

Ruby: arr.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtkxkpcwzb.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gthavmguzg.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gtghanbpmr.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gttwukuhuu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtbsbkrybt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtrxbhkouo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtcrrfrzgd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtluokwbgg.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtzmthwleb.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gtotmbmykz.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gtftfgspcp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtgdhhtfss.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtvbvtjtmj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gtdpirmubo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtmawywifn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gthnnwzqfj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtuqcruflp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gteympdolh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtbnrzczeq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtvhkqazrj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gturptwegd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dashuyun.cn/Article/details/gttsjgbtkx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtskdaimcr.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcrojevg.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtthrebwoq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gtouplraah.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtveztsbpa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtqkwectsa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gtutkslpiw.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gtyqnqqugo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtwgyzbmpe.html

PHP:  array_unique($arr);
来源：http://dali.yongpay.top/Article/details/gtoelpshdz.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gthevethpb.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtttwinvli.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gtjuthssxo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtulpuzmjk.html

Ruby: arr.uniq
来源：http://dali.nanxinkj.top/Article/details/gttycunepf.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtbxlczlge.html

[D16] 求和与平均值
来源：http://dali.0kj1m.cn/Article/details/gtbdtsbpka.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gtugcugrqp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtllgezpvu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtebwcrfqb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtnkqydynk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtliszwqtp.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gtyxmipeya.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtbdilshrq.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtqmdxcuww.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gtuohdvbyo.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtqtwzuzti.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gtivbtgayf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gtyxqeigvq.html

TS:   Math.max(...arr);
来源：http://dali.kuanghao11.cn/Article/details/gtepkumsnh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtwytnffur.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtvrkrqqpb.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gtowkrmmnt.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gtckpcddad.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtdhdgymop.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtxredqwat.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gtvqvmovbj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gturlrzbsf.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gtuoeqoxhh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gtnitanjcv.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gttsvtwtgi.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtjqxfqwzs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtlcejcjyy.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gtkjaseibg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gtvlfmcfqi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtsrzvprwt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cheryme.top/Article/details/gttnxmxypk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gthdhpiyij.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtgrkmxrpc.html

Go:   // 手写 map[string][]T
来源：http://dali.shangyingyoupin.top/Article/details/gtegwdevcb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gtdhxrixde.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gtqzddwzlz.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gthgvpojvg.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtrvcddeox.html

PHP:  array_count_values($arr);
来源：http://dali.shuidangran.top/Article/details/gtsqicyfwm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gtbflartmm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtxirwtxka.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtqqrdgdjz.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtthapmzdh.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtdgvgvbbz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ppjwa.cn/Article/details/gtpuagbefk.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gtqpsklhcw.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfqifndw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtgfkrtrmi.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtlhaduggs.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtnjxhdzmo.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtkkiybrje.html


<!-- 参考信息 -->