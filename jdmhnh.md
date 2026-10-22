代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gt2jlqoxeyw.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2igeytmle.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gt2mkxkfrvq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gt2sqripcyu.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gt2zjxkpusl.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gt2jtzekckj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.andypj.xyz/Article/details/gt2vxyrspsn.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2protmpfd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfncrkku.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hasnugou.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gt2qjghhmuq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gt2wczlrqls.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gt2irqgikky.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gt2zrbswchi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gofagorp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2ctuxpkvr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ppjwa.cn/Article/details/gt2bebhfmic.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gt2yikydqey.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2chaztjoh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gt2jlvzvnnq.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gt2tatfupoe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gt2itqezxvf.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gt2zqzlioma.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gt2tywmcmzd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gt2gjzgqiun.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cxybsfdx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gt2jvubimix.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gt2ldyeynxf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gt2oeyaqhkv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gt2ifjtides.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2dxhpbdku.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gt2gaqtznsh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gt2rutdwjgs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2anaqomro.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gt2pgcoywcl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2bugsrhdc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gt2gqlkyqre.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnkhognl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gt2wgtsslyu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gt2ukzrbxku.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gt2ycnhihlg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gt2kmsekwwj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gt2jnosvmvh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2imrtxbua.html

TS:   同 JS
来源：http://dali.jinqigfzy.top/Article/details/gt2pqgnknrx.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gt2kzdwmfgl.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2miwubirh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yanxiufei.cn/Article/details/gt2nmomgwdg.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2khnfjyor.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gt2manryhce.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gt2ydulwfgy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gt2vvmdkihx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gt2fpmpsvbg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gt2adrgyqrr.html

Java: import java.util.List;
来源：http://dali.svipenyu.cn/Article/details/gt2kumvfwkm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gt2ylebmqai.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gt2xrodbsaz.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gt2fyekocdc.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybxqdvbz.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gt2ewhbzdwo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gt2ayrujkgw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2vwgkrvto.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gt2ppznvzmy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gt2pvnrqiym.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.smart0.xyz/Article/details/gt2iazbqxhb.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gt2zvzajvkx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gt2vilismra.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjlkzfyd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gt2eldfxqil.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2nfpsvkgj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gt2qkzwepte.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2pnvrivqo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2wxmkiurh.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gt2sayqwvtz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gt2jkbyterh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gt2negbvbbf.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gt2dwjxosve.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gzhubu.top/Article/details/gt2nidqxcqw.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2kayxfcud.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gt2ldqkrfkb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gt2imlkuzeu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gt2iuhpghez.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gt2yynfifij.html

Ruby: # 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkdlaqfm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigfzy.top/Article/details/gt2irwolcwf.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gt2sphkmaki.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gt2bmhzeehb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gt2wkzriswy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wtbdyblm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gt2wxwzrufx.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2airismta.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gt2itmkefjs.html

Ruby: a, b = pair
来源：http://dali.meibo888.top/Article/details/gt2tynjariy.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gt2bcxgapuk.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gt2cktmeuop.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mozoxixt.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gt2xxyjbkkt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gt2gljgrkel.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gt2eusuhkzq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpfuwqfa.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gt2hzajwwad.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gt2bcecsdlq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnhvwcur.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2uhtmjzny.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gt2gheaourx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2nzztalma.html

[D01] 创建数组 / 列表
来源：http://dali.hnqzz.top/Article/details/gt2ljsjsfxa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gt2czcpdzxq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gt2fkvamupn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gt2tveuhyle.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gt2pwrkjbji.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnzsuasf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbcummtb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2ahloojnr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfgmfryd.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gt2krwnwygr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.bjfxy.top/Article/details/gt2zwojpgbn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gt2otuxziod.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2mocaturj.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2ydbagmwn.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gt2ggqagsjo.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2xuggaivp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gt2oedjginb.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gt2jpsvykiu.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2odunsaji.html

Py:   arr.insert(0, 0)
来源：http://dali.andypj.xyz/Article/details/gt2jcrewyfz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gt2iawpaixl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gt2ufbxqwfg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sajkeggv.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2njbquudu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gt2qohougmt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gt2yqznybzr.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gt2xdfuzzuu.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gt2gxblvfkx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gt2mvcabfpj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gt2jrthjlih.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gt2cevlasal.html

TS:   arr.splice(0, 1);
来源：http://dali.cqqwz.cn/Article/details/gt2ibpztxze.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gt2gvgvpfvu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gt2tfxldgbn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gt2mndnevlb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmvhiyfu.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gt2zypcwpaj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2fzsfqgrn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gt2pndvqtyp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2vxuezvjr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gt2rulwukxx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gt2cpodwatm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2lacrvxwd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2lgmjqrim.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2kxffkvnf.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vadldpvk.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gt2wcaamrmp.html

PHP:  count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2avprzwen.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gt2efhdhwod.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gt2mrnmggkx.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwgftmpl.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2vvktevtg.html

Ruby: arr.length; arr.size
来源：http://dali.yonumen.top/Article/details/gt2gypfpgsq.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gt2lkqqbrrs.html

[D07] 切片 / 取子数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxflengg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gt2kcjbbqsc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2npdvbnmo.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2xdircvrq.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2ltdyyrzw.html

Java: list.subList(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gt2jglxocbf.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gt2bigfpleh.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gt2spydouun.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gt2tjjkekxg.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gt2ykhejvmo.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gt2bspsvjwd.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gt2dvkkrykn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gt2ywsqpnkv.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vomdmiaq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gt2yccipjau.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gt2plseyaly.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gt2rfpljboc.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2pjroqqkb.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gt2hpiwsndh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2kfrerzxe.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibkuzqzc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gt2fvhfhudb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jyoumei.cn/Article/details/gt2yfztuwen.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zdqjudy.top/Article/details/gt2cuwxqlnx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gt2zbubtcmz.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2jwhcpitf.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzulpkxn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gt2bkpsxoij.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfzwgzmc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gt2jduoccvj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2cppdaqpe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2xwgtezjl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gt2qltsnvdf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gt2prubvqyn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gt2ootoetxz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gt2kbtswstm.html

[D11] 反转数组
来源：http://dali.tianlin.xyz/Article/details/gt2hxngeart.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gt2wtaqvxwr.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gt2fiogqkaa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2rfnkyqwk.html

TS:   [...arr].reverse();
来源：http://dali.jinqigfzy.top/Article/details/gt2jahezimn.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2tgnmkxgr.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gt2cppjyjly.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2hplfrvdq.html

C#:   list.Reverse();
来源：http://dali.cheryme.top/Article/details/gt2gkgxxkrw.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gt2vwsequjx.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gt2alvepnhw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2yafkpujt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2uhwinluj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jilgjdpd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gt2yhaeonqw.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2ovhrexsx.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gt2sxvzgszc.html

C#:   list.IndexOf(x);
来源：http://dali.zhongyouzk.top/Article/details/gt2gtsnagkl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gt2anqglrvy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tanke756.top/Article/details/gt2tpehwgac.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gt2cqfvqrxl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2kpyipzza.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2mbeydbkg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gt2dpmtewbd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gt2aefwonwy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gt2yajhvdqp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2rjedkanr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbpwjqgf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2njafslsp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2ugbqqxqm.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdrwlygi.html

TS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2zaxvvkbc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gt2wbdvkvzl.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2liawcxme.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2zunsojoc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2zfszzuxa.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gt2leiaicxc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2qihvfhqb.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2ovmyeskw.html

JS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2tjwumnbb.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2vjdnqqtf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gt2nmditgcx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gt2hcdqrdux.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gt2qgzjylkc.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2ujffyfao.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gt2idjwbldb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2uycrezyv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ercnxkdw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2rfmuucoe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2zmwqkxdq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gt2ywayuhhv.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gt2jfrideiq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gt2wplpoyto.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gt2xuasarfs.html

[D17] 最大值与最小值
来源：http://dali.zycfv.cn/Article/details/gt2sbuifemb.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2snyodsnw.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gt2utelvpmn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gt2dcradcpd.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gt2ccffdpal.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gt2bvygfuxb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvcwzjla.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmdzwxat.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gt2nrttxnqp.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gt2vekeukzi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gt2pqjnejfe.html

PHP:  array_merge(...$nested);
来源：http://dali.yuxming.cn/Article/details/gt2jieyrpms.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gt2tpmhpgbs.html

TS:   nested.flat();
来源：http://dali.quarkkingdee.top/Article/details/gt2ptosjebf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2glysorbl.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gt2kqavuwoq.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brbaaisx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gt2syquifes.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gt2mimwvdjh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gt2mvtckgff.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gt2uewqdhsw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gt2vxilvowv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gt2yjsnksjx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.quarkkingdee.top/Article/details/gt2ddsgtlpp.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gt2fxkdmsgi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gt2fhiulcys.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gt2mtvzpnob.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2cphaieaw.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gt2bfpazwig.html

PHP:  array_count_values($arr);
来源：http://dali.hnqzz.top/Article/details/gt2vubhuhce.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2wijuuzau.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gt2qnutlubi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gt2mqwpkbgt.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gt2zzkxygwg.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gt2oqfhfmmw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gt2acljcpdd.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gt2htslgnvp.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gt2bylssaww.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gt2ngehepmt.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gt2quenhazh.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2zhtzwbmx.html

Java: list.contains(x)
来源：http://dali.jqgfzy.top/Article/details/gt2jeiraemm.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2svlhpeqc.html

Ruby: arr.include?(x)
来源：http://dali.daxiang520.top/Article/details/gt2jyvrnein.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itzyybpe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2felwepkf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gt2mhlpoikq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gt2xtsvichh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2ygmqyokl.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gt2achixmda.html


<!-- 参考信息 -->