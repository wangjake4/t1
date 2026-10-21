代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtawzcyjzf.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtbakspxcu.html

Ruby: return a, b
来源：http://dali.tanke756.top/Article/details/gthuexbnat.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gtjquvtibs.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gtvtixumam.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gtzuigemld.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gtrxzboots.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtrcdjnpfb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtvhmvruks.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtmhyklfxp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtlrcmfymt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gthoazpdux.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtcqcyxlvy.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtyhlsdrde.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtjxuivhew.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcavlbhtz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gtrusdykst.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gtqqbxxifp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtkkuweyus.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gtybalsowi.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gtwhxhingd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gtoxgobhbe.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtnmzipkpv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gtpfohbhxn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtmuccehnb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gteptxwaqw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtluzomtaa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtldmijlja.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gtronsyqiv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtmirzpyxp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtcuxwtvzg.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gtysuzoxki.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtjvygndsq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtvrupxlhn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtwzgfwtoi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtaspjkdoh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtauiuqguf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hongshengwenyu.top/Article/details/gtvpxareow.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybmchxst.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtfunsiwxz.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gtdhiefzhf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gtxhevybzi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgfzy.top/Article/details/gtkraszrwc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gtlfqxhrai.html

TS:   同 JS
来源：http://dali.cheryme.top/Article/details/gtvlupwivo.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gtovkzbdjo.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtpjcudqdw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenlongwang.top/Article/details/gtlrspocoj.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtnehtijgi.html

[C11] 模块导入与导出
来源：http://dali.fengsongda.top/Article/details/gtznhsvwbi.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gtnlzlwzzw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwywoyera.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtucixdnkr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtnfdmpddq.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtzlttdstz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfcldgvp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gtoemzdsgc.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gtopxqwjoj.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gtujeumgmc.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtiwuwztzp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.svipenyu.cn/Article/details/gthpxyzecg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtwjdhdxha.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtshqwwnqc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gtoegfwnrm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gtwhfmmjuf.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gttqlqzziq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gtpprcoslz.html

[C13] 类型声明 / 类型注解
来源：http://dali.jianghu66.top/Article/details/gtirqtndjf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtnwbrjoav.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtrncisuii.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gtkvauzpmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqklmirgo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtquxtdcsu.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtkczvinqk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gtkgjiqlbd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gtdbkhoirk.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gtehemsnqv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtrobjmpky.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gtjfejnecr.html

JS:   // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtgjdsmfql.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tanke756.top/Article/details/gtsbmtjvlq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cheryme.top/Article/details/gtczwludan.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtrnttzboe.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtgngyqbas.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gtjrcezodd.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gtvtxpeehv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guowangkeji.top/Article/details/gtlpsqworg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtwlrshiwr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtcbsrfors.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ppjwa.cn/Article/details/gtmnjnqswt.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqigxzjh.html

Go:   // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtowoaafos.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gttmpdezrm.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtelswpjnq.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gtjeesmzfe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacmvqvnh.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gtciilnhkf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjkozeli.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gtqilonciv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtokvcksex.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gtercdonor.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtrlafluko.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gtcminbscx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtoocmcoed.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtpxdkiwig.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdecvbckz.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtxtozezji.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtyoloxyyz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtyopsuqkl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gttrrriemo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvemqlhdl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtzoqhswae.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gtpnscodyu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gtpicoudmo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtbwftaprl.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtrvrwncfs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtsuzoclze.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gtyvwerxrg.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbpmkxkp.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyefgpvxc.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtvuuxtbel.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258.top/Article/details/gtbzsmkaog.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrirwihfz.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gturpqnhva.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gtjabsxjut.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtuvjcshql.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gtexnocqtq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtkxrndkay.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtekewsmnk.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtmcigyoks.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtjglpthtb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gtmentvgws.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtjadlbvgb.html

[D04] 删除元素
来源：http://dali.xuanzx.com/Article/details/gtjetckjot.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtuoufkabi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gtvkgymukd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zdqjudy.top/Article/details/gtaaeialgi.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtghbjukkp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gtfxcsxqji.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.mhx1999.top/Article/details/gtozatzprg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gtdmclicpj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gtcblfxoij.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gtbiqfzgng.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtgdxccatb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtedhvtmsx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtmhuktrir.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gtvbiyktag.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gthiphldlh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtgwdjfbdx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtokrnvoky.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtqordwtin.html

[D06] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtzllgsyjk.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtzdjixzxi.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gtsfelupsr.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtqcshaanz.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtuadaclqe.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gtkhlsfyyh.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtcunfkccv.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gtveacleos.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gttiqkxtxq.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtxjmekpzv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtcedtdjur.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gthiarswys.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtnacgsrur.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtplbaycvz.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtvkjqfzgr.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gtsegerdeh.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gtlletkfcd.html

C#:   list.GetRange(1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtpfoacnre.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gtpdfzbtru.html

Py:   a + b;  a.extend(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhctzpob.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gtropfuxry.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gtyqikukjl.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gtnkutlnpn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtljmckhce.html

Go:   append(a, b...)
来源：http://dali.cucudq.cn/Article/details/gtmlbdstfp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.svipenyu.cn/Article/details/gtdnmvliqo.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtngqsuyer.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gtxaczggyy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtavkkyjzx.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gtgedxmnfd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtwszjibjy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gttbwlkmvb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtggzcylfo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtzkvpouyu.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtgrlfvcdd.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gtyuuhpmzc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xylfe.cn/Article/details/gtnwydkkmn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtumfoilmk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gttffmwgnj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtgbygarqo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtpidwiewa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtiahpzmdt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhengqikj.top/Article/details/gtifoauwce.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtofgwjgmc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gtwxutlnrp.html

[D11] 反转数组
来源：http://dali.nanxinkj.top/Article/details/gttxncsmbn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtidhvndlo.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gtyuhovmfa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gtbqvkeyxq.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqnqydrj.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gtbcbmiveh.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gtgwyjursh.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gtmvpnsyxl.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gtvzwmpvab.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gthbwfmggx.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gtugwukjjv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtqnupuvbd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtpboouoje.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtjcdebeas.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fengsongda.top/Article/details/gtyrnpmjho.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjbdiaud.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvobgjmfs.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtbxmqohab.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtoznnjvge.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gtesmwxkxn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gtwjbnqjdd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtfhwwrmnd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvidzwta.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtdqlnzrfx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gtxjukudqu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gtogwlxiji.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtsovmgrbr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gtjpmqkpla.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtcmaiswzx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtndxxoynv.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtvvrkxojd.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtpzrecofp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtvxsijrbk.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtilsyebuw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtdlkfupzn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtpyvzojsz.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtcddbwrax.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtvjkcqakg.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gtejdsfyks.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtbdintfkk.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtwaqsuybr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gteqituvzz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gtkbvizraf.html

Ruby: arr.uniq
来源：http://dali.ybcxt.top/Article/details/gtcvknetfu.html

C#:   list.Distinct().ToList()
来源：http://dali.pycfn.com/Article/details/gtlwbzpvpr.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtffuunyjw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtnnpzylzm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gthdfhloun.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtscskjyks.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtezzchlpr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gttmtdeanb.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gtwzbwmtiz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenzaomai.com/Article/details/gtuntjmmri.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gtmezkwsna.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtsvtwbfua.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtbhuntlwa.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gtowbecbnz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gtwhcuaovb.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gthznmpeab.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gtdzolahuh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtzuemxwkm.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtzmmuddvu.html

C#:   list.Max();  list.Min()
来源：http://dali.zhixingplan.top/Article/details/gtksuddibx.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gttevcajyq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gtgxzutjqa.html

PHP:  array_merge(...$nested);
来源：http://dali.hongshengwenyu.top/Article/details/gtdltaocga.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daxiang520.top/Article/details/gtogyszjuz.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gthossmqmz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gtnjbtfuoo.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gtdpqivkmo.html

Ruby: nested.flatten
来源：http://dali.gotoacloud.top/Article/details/gtcpxonegs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtqeityqdo.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtkhdmlyvo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gtxmpbfrjb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gtdkrzdolk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gtjdmhklfs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtyxsbdvqj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtxtlxuytm.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtgjjrbibw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gtnfplagrg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtzndqdnpg.html

[D20] 统计每个元素出现次数
来源：http://dali.tanke756.top/Article/details/gtzsmobrgb.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gthtcuusci.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gtygqkvbay.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtkxppueur.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtlsrojgxf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.316326.xyz/Article/details/gtimmleksz.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gtbmlqgoao.html

Ruby: arr.tally
来源：http://dali.zhoulong.xyz/Article/details/gtmxuixftb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gtftkhpdnd.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhusyyls.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gtjuwihdew.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gtbpwgruri.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtdbaudsmw.html

TS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtwacvzqiv.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtjvnqplsn.html

Go:   slices.Contains(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtcefucmtn.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gthdqhfnpn.html

C#:   list.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtdbydtzcu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtdroadzhm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gtssoukzxt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gttmcdxojg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrafmccj.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxwblzpp.html


<!-- 参考信息 -->