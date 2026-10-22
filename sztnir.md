代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.mhx1999.top/Article/details/gtlchdbrbt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtlbqvjjks.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gtjrptezex.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gtuzzqfdmt.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gtrevonptw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtrjdhigmf.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtzyexyzep.html

[C05] 返回多个值
来源：http://dali.yanxiufei.cn/Article/details/gtwgaaypjs.html

Py:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtjaqsphpq.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtfyxclvyi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtjhvgehre.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gtmpqiqhiq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuetiantiany.cn/Article/details/gtrrnvnvag.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtdlgrpfvn.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gtyrvugrse.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gtnzmhrlzr.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gtsfatpqhz.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtokngujsv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gtoelvwwji.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtsbsyzcuw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gtmxthsbli.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hammf.cn/Article/details/gtiiwckjfp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gtjpvqfmsd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtzdfbcanu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gttlxehkly.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gtgklssldo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gtxnmimiee.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gthokamgvy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtmwmmhdkd.html

TS:   arr.map(String)
来源：http://dali.jyoumei.cn/Article/details/gtntpqktmv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cashguo.top/Article/details/gtusskrezq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gtamoxpwbi.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gtoaapqwee.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfpyvoyr.html

[C08] 闭包
来源：http://dali.gogol.net.cn/Article/details/gtkedqoxqq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gtyarqpzpl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gtiwdsxozv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtitbfkgev.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtyqgtuxfq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gtaszfxyvs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gtgmkowejm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xinyue.icu/Article/details/gtizxuzsku.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtvcofhaae.html

[C09] 递归
来源：http://dali.ivvv.top/Article/details/gtwhrctubz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gttuetjymj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtitwytivu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtdfwbdtrj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtdurkrdvt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtfssnblsg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtoiylkyis.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtlgcgvnnn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gtsgrekuxf.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gtpsxquqbg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gtflkjctam.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gtjrgynhmc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hysaishi.cn/Article/details/gtkemmfxwr.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtucqbxogm.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtrnxownwz.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gthnxalwax.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gtdarfxzlu.html

C#:   块级作用域
来源：http://dali.sysykeji.top/Article/details/gtlvpadygl.html

[C11] 模块导入与导出
来源：http://dali.yongpay.top/Article/details/gteslfwcta.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gtrnzfdqme.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtehivkifu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtgarizzli.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtbgzklglx.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gtheupqhhr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gtdtvygnxj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gtdukdkpbg.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gtjcypnuah.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnqzz.top/Article/details/gtcsthhlaj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtrtdcfsvn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gtmvkbkjsm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gtlwjluisj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtyblcrrhz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtzphgxcag.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gtwqzfaazp.html

Ruby: -> { puts "run" }.call
来源：http://dali.feifeiyinyue.top/Article/details/gtlgztxhhf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtmpcriars.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gtjlfagxfc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpbfpvwm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtruzsogqk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gthyntglyv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtchwugtpc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtqvjboytr.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gtjldedeeo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gtedrqiqrl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gtgslvhhfg.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gtxdlovbha.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gthjznnyes.html

PHP:  // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtwzfrzagf.html

JS:   // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtmxxfjxih.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxxlhkwcl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtzdausehn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtgkmasnod.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtywzuvxzs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevxzmnac.html

[C15] 解构 / 展开参数
来源：http://dali.ehwqpu.com/Article/details/gttmzdbmyb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtgzmhdzgx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gtqusriqiz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtbtdqduxf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gtscgkweps.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtgcrgwodj.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtylrsnrdl.html

Ruby: a, b = pair
来源：http://dali.cqqwz.cn/Article/details/gtkyckirgo.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gtygegowgx.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtnoclchtp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gttwygimsm.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gtkfkfkham.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtvlevycuh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwfazyan.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.havefunace.top/Article/details/gtxgpozgau.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gtxmuetaze.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gtusvyzcvy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gtsdjncqro.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkmaupyau.html

D. 数组 / 列表 / 集合
来源：http://dali.meibo888.top/Article/details/gtasnntzuv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlplydncy.html

[D01] 创建数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gtaqwuesfx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gtrcdzzhei.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtpeysavff.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtnotjzout.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gtyjxapbpn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtizqsnfrh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtrvnjtxnd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gthbeayaia.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmlpjorx.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtuyzqzndq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtnvxigjgx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gtaodyazof.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtxfmdfmpv.html

TS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtrqnmhyhq.html

Java: list.add(4);
来源：http://dali.c1oappe.top/Article/details/gtsmrlpsuv.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtdnmbyhbk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gttmvmltry.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gtduuuptmd.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gtxenrdlmn.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258.top/Article/details/gtfvlkyahy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gtqvxykrgd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gtgvoxwnyl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtisjbvreq.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtcannqqpm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwyliuyr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gtoulqlwvc.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gthicwlxsj.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gtoaigbnvo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gtlaeqqxop.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtfxxuhnbp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtrglahkhw.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtcnixhebf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gttboagmyh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guannengcc.top/Article/details/gtcwzhyzuw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtnebnskdq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gtraivomfu.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gtzgkgszlt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtjwhekuqt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtczcaseqf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtitnmxmzp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shangyingyoupin.top/Article/details/gtrcoffhzh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtbibdltot.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gteurjnnjc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtqvrhlmxq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtopvqvlob.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtpttownob.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtshqzcxro.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtmppdkvle.html

JS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtfnynbzpa.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gttudwxfbq.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjnrqjjo.html

Go:   len(arr)
来源：http://dali.yj20258.top/Article/details/gtjjbxmbgp.html

Ruby: arr.length; arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtoygpzseg.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtyfaaszbd.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gtbcyeqoms.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gtlvjnoeru.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xziqi.cn/Article/details/gttnzqdpdz.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtxbqbnmny.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtsneoqvfo.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtjkdfwzjx.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gtvkzonmxz.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gthhltautc.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gtzujwgjll.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gttoitttuc.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtlzpoeveu.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtzzenpovy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojzemkdm.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gtihlkxoog.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhixingplan.top/Article/details/gtbhacrizd.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtohpwifoz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gtmnjixnry.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtsaozyfac.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtdnibskct.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtjrzqpbuf.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtfvlcqgjj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtqvsfdthl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtsdnqgycj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ybcxt.top/Article/details/gtiaviopmq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtglvcmhdq.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtdpjfxlnp.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtvuifmwhe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gtxemqxmhw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gtrnosomej.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtydmvhxez.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gttvlmiefc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtierbwfnd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhoulong.xyz/Article/details/gtzzibvhrf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtvaddvkex.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dianchejie.cn/Article/details/gtxjuejljd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gtfskuthdv.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gtqmsierer.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gtscljrrdh.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtizjgndvg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gtiszipmmx.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gteorcerfb.html

Java: Collections.reverse(list);
来源：http://dali.aizwys.cn/Article/details/gtmgorrtda.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gtshdtnogu.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtswdxkjth.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gtjpuzaasg.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtwzhpikdz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gtzwldnvcq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gtortleprp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtbaaloftg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcdmungb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gtiltbedkz.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtzlgmigdm.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gtapdvdwqy.html

C#:   list.IndexOf(x);
来源：http://dali.iojbl.cn/Article/details/gtgpfgddsi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtchrlzpny.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gtjhpdbjkx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtmzthsmqb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtddgdzweg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtuskdixdt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gtycfezgme.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gtheqlcigq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gtcfyzqvyx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtdhyeldho.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtmazttoyf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hywenlv.cn/Article/details/gtmxljhsrl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gteueosxpx.html

JS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtdgndhyev.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtfdpugtqx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gttouhkttl.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtzdwpgjks.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtpkebmcqb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtjocabnkr.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gtkzpswzel.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtwyprcucx.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtmorjkpyw.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtjhehxtya.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtiknqwtvg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtqzdhbvor.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtumpbvdmm.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtpyqyhhcx.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtzsbwfygt.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gttvkzmxzg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtdjbolklz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgfbqvzy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtrtnlpacw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtycijxckz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gtdmefjymg.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtfyvgvuif.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gtxvruvkbq.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gtilheetee.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gtxniwksoc.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtqedihjlt.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtacsexizt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gtjwzebyyu.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtlddbuepd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtjuhgerqy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtbdibemqa.html

Ruby: arr.max;  arr.min
来源：http://dali.smart0.xyz/Article/details/gtfttaiftp.html

C#:   list.Max();  list.Min()
来源：http://dali.fzhhl.top/Article/details/gttwdqrcki.html

[D18] 扁平化嵌套数组
来源：http://dali.sxryk.cn/Article/details/gtbdnxouac.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhengqikj.top/Article/details/gtfeevdqow.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtnmmhyfvf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gtsjyzzbla.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gtsycdhmov.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gtyixuxwxw.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gtxujbrmwb.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gtgnvpxkwr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtiqdcrsep.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtapwskwbo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gtziltcekl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gthhyrkoxw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzdicpza.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gthclotagy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gtzfigktbi.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gtwbzwdkih.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gtvhdxjveb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gtnvruiasn.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtjzwbiray.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gtcyxjcjks.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gtvgmxhslb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtdonjxocg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggvilvic.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtgofidzie.html

Go:   // 手写 map[T]int
来源：http://dali.redwolf501.top/Article/details/gtzxullbnm.html

Ruby: arr.tally
来源：http://dali.cqqwz.cn/Article/details/gticiaddvm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gtreyvpfya.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gtnjjzgpau.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtcoaogyxo.html


<!-- 参考信息 -->