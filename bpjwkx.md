代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gt2zcfsbcwx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhixingplan.top/Article/details/gt2nmjgifss.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yueranfly.top/Article/details/gt2mxinkilg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gt2jpbtsnxj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guowangkeji.top/Article/details/gt2rgzrzyov.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2hxccyabd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gt2sstrgdtg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gt2ppyvpham.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kkaovozu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2hnmubxsv.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gt2lsppbhcd.html

[C05] 返回多个值
来源：http://dali.andypj.xyz/Article/details/gt2bnxblinz.html

Py:   return a, b
来源：http://dali.daxiang520.top/Article/details/gt2pvllypvw.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gt2ttlphjby.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2vxrjoqvi.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gt2cixsrhrs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.iojbl.cn/Article/details/gt2vkiodrup.html

Go:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2lckqqdkz.html

Ruby: return a, b
来源：http://dali.gogol.net.cn/Article/details/gt2ncumdgxh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gt2rqzkxico.html

[C06] 匿名函数 / lambda
来源：http://dali.tanke756.top/Article/details/gt2gsdlapsq.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gt2jocllhet.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gt2mggbqpux.html

JS:   const square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amzmitqk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2nnshrjce.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2tpccdhtg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2bhpwqmai.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gt2orctmwgt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2oszkwvmi.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gt2gotjqicf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258888.top/Article/details/gt2tnxdjflz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2xmodgacy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxppsuek.html

TS:   arr.map(String)
来源：http://dali.hammf.cn/Article/details/gt2sotzxvwe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqjsndat.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigfzy.top/Article/details/gt2tbkcvqeg.html

Ruby: arr.map(&:upcase)
来源：http://dali.haohaochexian.top/Article/details/gt2fktktzpa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gt2wcxplqpa.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gt2grwzqmyr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gt2fxoazbei.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gt2jclzboap.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gt2jeudqwmr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gt2ufnfhiqz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gt2iroboved.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcitahpv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gt2jgyhiqjx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2mvdvilyc.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzxyopac.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gt2smybsywq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tian-w.cn/Article/details/gt2xeadtafw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gt2wxjlkwzz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcqjbayr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gt2cuxvpbbf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gt2zoqvgbtr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2wkljjmxc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gt2jafrfbib.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gt2yeykxmxs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gt2opdyszye.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.birdmap.top/Article/details/gt2jvxxxpxu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2swdyswcw.html

TS:   同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2vkesycyd.html

Java: 方法内为块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2gtdpdjgn.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2qiltyjgj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytagnfig.html

C#:   块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2tjbfsryr.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gt2baqsupwy.html

Py:   from module import func
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfzxqgkh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gt2kollzmkv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2oxfbxusf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gogol.net.cn/Article/details/gt2klevgsog.html

Java: import java.util.List;
来源：http://dali.yonumen.top/Article/details/gt2zkeznldl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gt2rtrugnso.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gt2innomliz.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gt2jqjpobkz.html

[C12] 立即执行函数 IIFE
来源：http://dali.meibo888.top/Article/details/gt2ztpirkdl.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gt2qvwwwptd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gt2bdryrowi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gt2ynuobftz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2wtcxbcek.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gt2eihhuztz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gt2waraoffo.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gt2scbjteph.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2chpyzzlj.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gt2wvidenyq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gt2hhrdnemf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2kmcgntmw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gt2lagpbqbn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcrqsohd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2uypscwly.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gt2fnfhzwvc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnqmxwv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdyiwnej.html

[C14] 泛型函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crwqhyjd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.andypj.xyz/Article/details/gt2iqnvbtpd.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gt2gpjjfbjq.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2oltjhswi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gt2fgdyeeys.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.havefunace.top/Article/details/gt2heejludt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gutuosqu.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2xgcvzmpj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gt2tcsdjcuq.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gt2yvoryntk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgjadnts.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgmxcdvo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gt2igpwjlek.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gt2xxyxeuvy.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gt2ftcwbhcy.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gt2jhtjfxwh.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gt2zlkrcpsm.html

C#:   var (a, b) = pair;
来源：http://dali.gogol.net.cn/Article/details/gt2vwyzjawc.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gt2vudqigos.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2mdalxxla.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gt2msfwpktb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gt2srdmdrgv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gt2dxlbppet.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gt2dwzpnjgg.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gt2rvdoyikr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpttatsx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2aakrkres.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oavqnsnx.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gt2ukkhyqaw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2lfiohvwy.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gt2hvunssxp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ivvv.top/Article/details/gt2vktxgolw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gt2uqxwigay.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gt2ympbasck.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gt2wsyyoeyp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gt2siofeanb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gt2kjopexzz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2wasfiitl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gt2rvnrofkb.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gt2unybgxtr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.0kj1m.cn/Article/details/gt2vwyaywki.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gt2bffxbbga.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gt2hvbmglyb.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2sccctifu.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zskfolzc.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2fslqapus.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gt2rbvsbven.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gt2qufjzvyu.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gt2crcmlxgn.html

Py:   arr.insert(0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpuebmwp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gt2nmkwgdli.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gt2ftjxhjxn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2mwmhetpt.html

Java: list.add(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2lsmpnwlo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2ibqlszre.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jyoumei.cn/Article/details/gt2qszcbgry.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2gouyyhww.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2doauwytx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ivvv.top/Article/details/gt2rdwohuoj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2koflxzab.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.quarkkingdee.top/Article/details/gt2oaorkwto.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gt2acovfgsw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gt2tonwtjgt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gt2flozzuhr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gt2fbqlgnje.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gt2lfkniqec.html

[D05] 访问与修改元素
来源：http://dali.quarkkingdee.top/Article/details/gt2tztzaave.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2xtnhaokg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2xjdtxkpb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2voxfjrmc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gt2rtzuvitt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gt2tlityqvj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2osovztfw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2bwihanyw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2sowexgza.html

[D06] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gt2domgagwa.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gt2jhtlcaws.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2fiujwnxn.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gt2yomhdupa.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gt2wtruwpyk.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gt2dikzafug.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gt2qpqtitfl.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2geivifwl.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gt2khmodgde.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gt2jpttzrol.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yueranfly.top/Article/details/gt2utgfrjxc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2iyzszlja.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2sqnkleww.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2iwrchzik.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gt2qdoorevw.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gt2pggnbuxv.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2ndamazhp.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gt2wqtysfzp.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gt2hbgfjldg.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gt2occytkam.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gt2wezkvgio.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gt2butewzwb.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rssxhhyd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnyoqgxl.html

Go:   append(a, b...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltggztxc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gt2qomayxor.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2mewhxbdd.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gt2cveeqyfp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gt2bmnoalmm.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2mjzpyhis.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sphlodwc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdevywu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ppjwa.cn/Article/details/gt2bjlebhkc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2rkjyfthu.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2enhijkin.html

C#:   list.Sort();
来源：http://dali.9152youxi.cn/Article/details/gt2mooybyao.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gt2ewwrmumb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gt2emnjcyfr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gt2oyqvfdci.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gt2oswtlyew.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gt2zqeawspd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xziqi.cn/Article/details/gt2iglzppcy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gt2fcgoewsz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2altbirmc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gt2mdowmomx.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gt2kzzfwwio.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otndarhq.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gt2rkbxeinm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2mvuxbxvp.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gt2twvkowao.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gt2baqpnvgh.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gt2fiakefng.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gt2aqinoxck.html

C#:   list.Reverse();
来源：http://dali.fengsongda.top/Article/details/gt2fiihcric.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gt2hnznipyr.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gt2jrtdtdhb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbwyocor.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2ruiwfexx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uectmkwz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gt2rhkxhmzl.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2hvtiuckw.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gt2zyxrrohw.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gt2hcwtarmr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gt2lwbfcurc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gt2iqmhkwbs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gt2luhcxoul.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2jvhjdhos.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2hmzsisxg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gt2bhnvqwoh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gt2rmzlxyan.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gt2diimsewb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cheryme.top/Article/details/gt2vmxszlex.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gt2dfzmzqbw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bijhzrpk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gt2eivosmdb.html

JS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpdjhjcb.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2bjpoqvry.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2xrgmbowv.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxujrhds.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2ajzwadzk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2kxewqkwd.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gt2rqpuyury.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gt2eqkoqzwh.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gt2pcxfiuzo.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2rwytjyub.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2ptiaeajv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gt2ngmofmjb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gt2egkwgypg.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gt2mtzgfwpi.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2bhkhqfwc.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gt2jrvjukpj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2icptjumv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gt2pkbkrjzr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gt2swakdoxg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2wgfekirn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2zeeuyjae.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gt2druxvvvo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gt2rksvxscd.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gt2rfzeadlc.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gt2xojdiaji.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gt2smxmzxtx.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2tmbqplhc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigufen.top/Article/details/gt2ukecgppy.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gt2pghvyflf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gt2jrkenszr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2mfvocpsn.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmqhkfoo.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gt2bhuqdkoy.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gt2mfivkroh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gt2lkdxafgd.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gt2lmjkukmt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gt2ownkouzj.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gt2rdwnmckb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gt2icjbckhs.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gt2jdgtjdxh.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gt2vmcsltfx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2bvkhirnp.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gt2kdliebai.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gt2jmubwhbl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gt2toehstzj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gt2poyzqrsk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gt2gnetvksu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gt2zwrbmrho.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gt2bqqxkcux.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gt2fgfoghpz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gt2wgfltpez.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gt2wgzrnwhu.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gt2rwuwsrjh.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gt2wqlhebap.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gt2giqjrbui.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gt2znnvyjce.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gt2uwqbbrfq.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gt2zobyzhks.html


<!-- 参考信息 -->