代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gthqducbmz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtmivofmej.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtnhppyeqv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gtgieffsvt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gtfwojxklf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gthlxosggq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gtonnhjftq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlskdnvo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenlongwang.top/Article/details/gtamlgutuf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtqiumomzl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtxwfvtqlz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gtvkrcaajz.html

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gtchsmijft.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtjsujtipv.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtcvapjybm.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtlxfqauki.html

Py:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gttkqsfppq.html

PHP:  return [$a, $b];
来源：http://dali.yuxming.cn/Article/details/gtpbeqkxtq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtcxulheev.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtijkonllz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gtyyfgujhd.html

Go:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtgnccykkv.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gtercxacfs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gtpspaegut.html

[C06] 匿名函数 / lambda
来源：http://dali.pycfn.com/Article/details/gtzwhkpasy.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gtuuggistd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtvzefizit.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtbznligxs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gtgyyjmdhj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gotoacloud.top/Article/details/gtbykwvmpd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gogol.net.cn/Article/details/gtxgvbctru.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gtotpcwnyh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtcfjsndku.html

[C07] 把函数作为参数传入
来源：http://dali.jyoumei.cn/Article/details/gtkrvgpfwa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gtsekpgmov.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtvdwcxfbc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ydzc1.top/Article/details/gtlibgcqmb.html

TS:   arr.map(String)
来源：http://dali.jlsjyb.cn/Article/details/gthayuhikw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gtfhxsugbu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gtdjspbspx.html

Ruby: arr.map(&:upcase)
来源：http://dali.gotoacloud.top/Article/details/gtqanzuhtk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gtwtopgrdz.html

[C08] 闭包
来源：http://dali.xuanzx.com/Article/details/gtorgwrpwg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuqrsxje.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aibaodan.cn/Article/details/gtzbapmbex.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtnjnikjbq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtfhygxmrd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gtneqxymqb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gthrstntwo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gtbytofxib.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtuywhunfv.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gtadodxxhi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtnyozbuar.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcwznaru.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkcewnrc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtvpkexptx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtgqjfhjhg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gtmuweccnt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtjofnqnft.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtdaihmcdn.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gtxskxizvs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gtmskjegea.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hfpthk.cn/Article/details/gtikahyyxz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gtyaeeerot.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtuacbxphj.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gtvjkcrxho.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gthkgmojhm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gtfiudklia.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtsccfjknw.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gtiqiwlypk.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gttequzbmr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtywzweuqi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtdvsinucu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgiwuebx.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtyeqprtdy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gtqsadcxis.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxejzegg.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtloxbrnnx.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gtsorxrxcr.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gtnusuvxam.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtjaajkgta.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtrfnregay.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtpwmxzvpw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtjpucehlm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yangfankeji.com/Article/details/gtklozfwza.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtcvvhcrwi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gtxtqdmqqt.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtxdovjrsj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtkjswkwbi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtyftamtuy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgadavdkx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtueqyqaxo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtnslhdffc.html

Go:   func add(a, b int) int
来源：http://dali.hfpthk.cn/Article/details/gtmrafijfb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtedaeambe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gtxfwangas.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gtjrbnphxt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtgmdepdiw.html

PHP:  // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtpopbttzv.html

JS:   // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtjzejxvgk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtpbtxgnbo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gtfxmulluo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtynmrhumv.html

Ruby: # 无泛型
来源：http://dali.shuidangran.top/Article/details/gtttiavkoo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gtdiwaxhuy.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtwnbevqgd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gtfwlbdiqd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gtcdyjkasn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtvicyfegp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtoctdbdcs.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gtydkcoeew.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtdcjxckqp.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxsuaiba.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gtuwvnqerf.html

[C16] 函数 / 方法重载
来源：http://dali.pengpengdd.cyou/Article/details/gtgriqykdi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gthbhoqqtn.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gtoloqcvlh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtxhogfrjd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gtntebdhty.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gtaufbwgxp.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtipnmmpsv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtjbwsbzol.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daria6918.cn/Article/details/gtsrsgzxdt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzasgdyvx.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gtqjxrsimx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtykwvbijr.html

[D01] 创建数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtpotjofjw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gthxgajnjz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtkfqbqsyq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gtqtecopuy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gttnxwqjxs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dashuyun.cn/Article/details/gtoflnpras.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gteqaiemsm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gtjtmhlpak.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gtyzvzhlbk.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtjpoqomlg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gtmlxzsiof.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtmkeiaazt.html

JS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtocxjfizw.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtutqvrbum.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtrxcxxznu.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gtxdtusjiu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtxqwriwhj.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gterwenrms.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gteihbyype.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtgoibzall.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gtnmbmsqcs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nwbrower.top/Article/details/gtbabgyzst.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtajcesdvj.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtszzeqdhz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gtkzkhqquc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yangfankeji.com/Article/details/gtvbimvnka.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtkumjuyzs.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gtdxbpfzcj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtapqqgkek.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shzxlz.cn/Article/details/gtplsyprlc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtvqticljn.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtzhtiuzus.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gtuhgfuqgq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gtpkskcydf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtmzsmvvhs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtxjarmmur.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gtbfpfrjas.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtplqpsnni.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gttbqroprd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtghwrooci.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gtfrlvugjb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gtfytfnbax.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gthlottnzy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtfrxxkzsm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtcragnczx.html

[D06] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtgnfvuuua.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtlqvljefk.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gttqucfugj.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtvbbyhpnu.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtwvhdhkwh.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gtpmkkvjha.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtwfskkohp.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gtmchkqobk.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtwdnzfekm.html

[D07] 切片 / 取子数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrnhfwud.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtwkyxqnuz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtvrqbhhjn.html

JS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtawskbfhm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtxmhvzoiq.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtxakhbpua.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gthdmegyav.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gtybkqsbvd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchxnassj.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtyyuotdww.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gtoedyadxk.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gtphkyzmjk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jiagoushi.top/Article/details/gtkasupubx.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtpqxltkmn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtjijadskd.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gtnzqpizen.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gtctjkzdst.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gtdubgpgln.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzippvyz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtoqkeiaau.html

PHP:  sort($arr);
来源：http://dali.tian-w.cn/Article/details/gtumsghurt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtfppfkalb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gtnnevjxwt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlskjzpnu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtnkwcfajw.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtazbusewe.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtlhryksri.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtdcbkgbrp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtgzymlpbp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtgzaipqxp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtdjpssfdk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gttbagvozo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtqrrmlsjl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hammf.cn/Article/details/gtcoeerfgw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtpjdbckro.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gtrswpxnna.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gtuygiddxh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtfdljzxjk.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyositco.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtqxmlzpmu.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtdzvynitf.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gtwbvfcues.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gtrtqfxbik.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtctzdgfhv.html

C#:   list.Reverse();
来源：http://dali.yvedp.cn/Article/details/gtzdbivusb.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gtlczccnva.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gteugziial.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gtccuwbxam.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtncxruolj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtbdkmcyjy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtxwhmdmts.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtvqqlrtze.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtgfozuoxu.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtlzickxip.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gtlecpvgjt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangdashe.top/Article/details/gtygxtybyn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gtslgpkrzx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtkwndhhdq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtftxwgsir.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gthxvjsqzj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsapskuv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtneqcttbc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gtvqqagcer.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gtqvlbjnby.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gtyqngjpch.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtyazhagco.html

JS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtyfqnmpdp.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtumwaldye.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtjbqslagp.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtgoslwyqs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gttohnkdue.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fzhhl.top/Article/details/gttjusurac.html

[D15] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtksjmxbbd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtkejtmltn.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gtejfipmzz.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtwdnujmbd.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtyibdlyfe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gtceonnarz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258.top/Article/details/gtxoficayp.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gtiewtiysi.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gttxjikynu.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gtblzxjrmy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtdtydlcxx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gttjpjatfq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtiffjccmb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtuguugmgy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gthdffbnjl.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gtktzqavgd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gtniqkrkdr.html

C#:   list.Sum();  list.Average()
来源：http://dali.fengsongda.top/Article/details/gtjkzzupzm.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtbezygrtm.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtrttuywfl.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtpaaqgnhl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gtjxajfdor.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtzdfmpfrh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gtoeniwsrt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gtozivrenv.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtmjuymush.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gtavavgdnn.html

[D18] 扁平化嵌套数组
来源：http://dali.0kj1m.cn/Article/details/gtfiykgryu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gtetzjomhu.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gteawidgvx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhwnescz.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gteahchmww.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zdqjudy.top/Article/details/gtvsnomgji.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtlgyxziva.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gttxkerjuy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtdizxecpk.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtfnbkgjqk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtchowguzj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gtrujmmlzh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gtjxkuvzup.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtyrsuklpa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtaiyayjsp.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnnpjrpz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gtbdvcgzuk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yonumen.top/Article/details/gtqcshesxj.html

[D20] 统计每个元素出现次数
来源：http://dali.tanke756.top/Article/details/gtksoxjhfw.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtvykgbbxa.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtdlxevnjh.html


<!-- 参考信息 -->