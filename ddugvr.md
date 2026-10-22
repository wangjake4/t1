代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2dtynzpxe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elcmcxix.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2bftyqgih.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gt2nyuzxpej.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2vydgwnpe.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gt2umvzbnpm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gt2fdygulei.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tanke756.top/Article/details/gt2upblpzzd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigufen.top/Article/details/gt2cfrjdmay.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gt2pewivtwa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2ivrfsbxs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gt2wmfrqvsj.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gt2tjjjzciq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ivvv.top/Article/details/gt2bkizuqfo.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gt2rhtrkxpv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gt2lydkpovi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrfqogug.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2cdsxpmvw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2dxijogff.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gt2swoodfpt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gt2ahhaqnkf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gt2wnehwibt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2ynttlmcc.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qobxbvfi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2ebmqsxci.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gt2uisllaqh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gt2bjqrmbss.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gt2bpqldetn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gt2vwtqfkjc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gt2gfxmnywk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2yxmummco.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffxdgjtz.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gt2hfriugen.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gt2cfilycjx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gt2tetdhgra.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2gpveidew.html

TS:   同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2uetfsuov.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gt2wnrnrxan.html

Go:   花括号块级作用域
来源：http://dali.yonumen.top/Article/details/gt2cnrexomy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.meibo888.top/Article/details/gt2sktcpzqh.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcaxqcgv.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gt2xmwrmmpj.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gt2xlqeutiy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gt2peizqjtf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gt2lwprfgjv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gt2kfviozai.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gt2mbtxivnh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jianghu66.top/Article/details/gt2wnazlbnc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gt2jvrmkzxy.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gt2jxtfncrh.html

[C12] 立即执行函数 IIFE
来源：http://dali.316326.xyz/Article/details/gt2crxnjfho.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gt2andimnjk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gt2srgjaskf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ienvttpq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gt2deuymxjw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gt2gpyrzssn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.kuanghao11.cn/Article/details/gt2djztelia.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gt2lowefaxe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yonumen.top/Article/details/gt2jhgooynp.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gt2xonfrmnm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onlhfqpv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2ygjlvqhn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gt2igfinptf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2jgimuvmo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2gwgbcnmj.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgqojlst.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gt2jxamwloi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gt2iyuphdrs.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gt2xpqvqxlr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gt2dosghpsj.html

PHP:  // 无泛型
来源：http://dali.yonumen.top/Article/details/gt2usrsovty.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyajiraz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gt2douxbhuo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gt2auszmtms.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osrnzeoa.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2fpiqovcy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gt2audjihqs.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gt2vmjlboqj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gt2gykrrzwy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gt2keknhnap.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gt2kfxkttzz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gt2otgxmayj.html

Java: // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gt2sjmonwwf.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdocrlcr.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gt2ynfogqso.html

C#:   var (a, b) = pair;
来源：http://dali.guannengcc.top/Article/details/gt2qfwvqlwk.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gt2ecqwykdy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gt2scafuiol.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gt2qcvfydmn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gt2ithwctmy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guannengcc.top/Article/details/gt2xenaepge.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gt2oxohcckd.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gt2svppbapz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.iojbl.cn/Article/details/gt2blrbeknj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gt2smkiwixm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2thdspcgc.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvgkfhkd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2bfkokvnr.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gt2sojmecgj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gt2fgcbmmyk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gt2exgvedjg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2sztosibe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gt2hrszeffl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajyrhxuc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdblchgf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gt2nwfbzkgb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gt2utcdpasu.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2ugugcgsg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2maaivhje.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gt2slrixuvz.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gt2afvyvruk.html

TS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gt2eadfgpej.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2qbcvhsek.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gt2fojhappl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gt2wjnxpczo.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gt2wqietgun.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gt2bhfyvevr.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gt2kuqkarbw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwgsjtga.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gt2hnfzvmlk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2pqpycrsy.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2lvgwheqj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gt2azulofhb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gt2zkbthldz.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2ukrphepd.html

[D04] 删除元素
来源：http://dali.hnxiangtu.top/Article/details/gt2fwzwobyq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gt2ifrfexlz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gt2cdstrvjg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gt2izksfufe.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gt2ooxxgsil.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gt2ruvjzieu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmddcpcf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gt2ekjynbtt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gt2atqttlej.html

[D05] 访问与修改元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2vokfcjqc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2autowzwo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2yecwuvcr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2zqvuvesy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.smart0.xyz/Article/details/gt2jdqxbelu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gt2ozooqdpm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdtcmchg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2yklydskk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gt2zspagvlg.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gt2vzertxzn.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2skfcxhrp.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrjjfoot.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gt2nwnipajf.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gt2cnafzrkz.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gt2jilubnkv.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nritvojf.html

Ruby: arr.length; arr.size
来源：http://dali.hammf.cn/Article/details/gt2ymtddjbx.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gt2ppjirezw.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gt2lpyfwwuu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gt2mlnxnjwl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cosddmxe.html

JS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2cbczuaas.html

TS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2iiytxlzt.html

Java: list.subList(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2djrbnqjz.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gt2nnqqkscs.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gt2gwkbxsqy.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2balmbnqr.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gt2ebwtcvys.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gt2ywyhunuc.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gt2muvlhcyl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gt2anhhogjt.html

TS:   [...a, ...b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2betinewf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gt2guimtbnz.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gt2bwyusmuk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gt2znagoued.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2lxkdofaw.html

[D09] 排序（升序）
来源：http://dali.jiagoushi.top/Article/details/gt2hhuekjlo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2cvndrdzf.html

PHP:  sort($arr);
来源：http://dali.daria6918.cn/Article/details/gt2mqtqkqkv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gt2qmtuhplc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gt2hsstmztq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gt2ghejsolk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2ifmavvuu.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gt2ypsmlyyh.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gt2vzcytukm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gt2kbudpcfd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gt2fisjychc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gt2goywcahg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gt2txhucfsw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gt2fwvcfgaj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258888.top/Article/details/gt2svsdmizq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gt2ehrtlmmi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gt2adjnmjnp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gt2ikceedxe.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gt2ihlwnlon.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gt2kxblvuwe.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2keckvhvi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylldryhw.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auknebcc.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2evtlimmb.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2vxzvnwll.html

Ruby: arr.reverse
来源：http://dali.havefunace.top/Article/details/gt2rnsfbexc.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2ftgdpfwb.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gt2twkylcwa.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gt2popgsahb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gt2cpcuvkgx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gt2pwimgyji.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gt2wgfkuewj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gt2yhpclckm.html

Go:   slices.Index(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2tqekcgix.html

Ruby: arr.index(x)
来源：http://dali.iojbl.cn/Article/details/gt2chaccwie.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbzdoyoq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gt2qamilhhs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gt2fxcjwegb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gt2gaaimvke.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2wgomwsdf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2gzyjecyi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gt2wvzezats.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2svqyrbon.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gt2jtgkdjwu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2gqkglvks.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhwltepf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gt2bgeclumh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2pgbccjqm.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gt2lbqghanb.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2gwnvhkmb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gt2emvtsare.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gt2gerkwrkw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2smniufjk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2poxjuqbj.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gt2thqxxauo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2yxhgspvn.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2vnrnwijg.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2zwgnjzmm.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2evnkjymw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gt2kikkxtyf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gt2usscjpus.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gt2xitfpoai.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gt2nqmnjppf.html

[D16] 求和与平均值
来源：http://dali.jlsjyb.cn/Article/details/gt2nnnrbivu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2zjhqdmly.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jndvsjmj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2iyyrwkqh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2bniysgcb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gt2uasytczb.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gt2vefwzlsk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gt2jzvjacwm.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gt2kxvezxcg.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gt2vmsbfvas.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttrqewln.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2ppqduapy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gt2xnkshcyu.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gt2pvdewffu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2qzqfdinz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2mrxkqond.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gt2nwesdsgr.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gt2efelzhoy.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gt2ardffcen.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnplhcou.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gt2aknknmif.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gt2avtjrnnu.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gt2jrxhiljj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2mfbnksww.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gt2sgmcffbd.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2myopufvu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2npogtjzt.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gt2ndkydlsn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2yqpjfikt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gt2duyfampg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gt2cvhdhqqu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2fmsdogav.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gt2mxsmsfrf.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czoegltg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixkeinoq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gt2bsicglsd.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gt2hdtznpuj.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovkocvgd.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gt2yarkumyr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gt2theqouww.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gt2ktwwvppl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gt2exsfxzjj.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gt2ylepcwxl.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gt2mwcjchoz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmvyklrf.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gt2mrfbwjhh.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2sgrjauaa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gt2pjhheqvb.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2gwfwdfwy.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bifzjavk.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncqbuehq.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2dwzdcgov.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gt2koqvkuph.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2uvmteqtu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrqaxybg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2civoldqb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gt2zeiwmfqv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gt2iondhdos.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gt2wggdiwgb.html

Java: new ArrayList<>(list);
来源：http://dali.ehwqpu.com/Article/details/gt2dweqmrea.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gt2kdvowqkm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gt2nnlpnwug.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gt2zgkftuzv.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gt2ddscffya.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2imzxbnpb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2lkypxhki.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gt2qgdbhbee.html


<!-- 参考信息 -->