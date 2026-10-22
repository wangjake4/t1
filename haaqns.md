代发 wailian999

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2fmrtdwna.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucmzayub.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gt2tqyfghck.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gt2aswayrxi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gt2tiiimmhi.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gt2xmuzqvas.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehuqjtkq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gt2rywmmccp.html

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gt2lbiadgsm.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gt2zdcmonik.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gt2wzwihufc.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2zeoclxag.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gt2lvkvcovu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwdrppcg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ehwqpu.com/Article/details/gt2krfiliwo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gt2gbqoxzhc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2zqekoaqt.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gt2fxevjlnp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenzaomai.com/Article/details/gt2pzciydis.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2bjajdsrf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gt2lhvldeib.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gt2ivmcdusg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2mgzjmzsy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dashuyun.cn/Article/details/gt2pzsvhwtx.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gt2ahgzywfh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuxming.cn/Article/details/gt2ayrodcpl.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qobxavvi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gt2fwhchgzu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gt2zwpqygqn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmtmoofp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2hxmhyirb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gt2aaucoqag.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbkevuna.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gt2uzuubujc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2egpoeqts.html

[C09] 递归
来源：http://dali.dianchejie.cn/Article/details/gt2jxwrsuak.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2brotubec.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2utmwhxhf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gt2vlfjleyq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gt2syxzahdp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gt2qfakfdde.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gt2tljbpgfw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2prktexfu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjgacooh.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gt2clhhixbm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cashguo.top/Article/details/gt2earswgud.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gt2pbhxahjf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2svsqjbws.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gt2saareqdm.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2utkwfhsq.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2cipcteot.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xziqi.cn/Article/details/gt2factycjs.html

C#:   块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2mgduladd.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gt2wmfsrmap.html

Py:   from module import func
来源：http://dali.mhx1999.top/Article/details/gt2ugumpazw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.andypj.xyz/Article/details/gt2dumazmfg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gt2ysaahizc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gt2rmnbrrbz.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gt2epssjgdm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzklcbcm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gt2nboerbhj.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gt2wrymfany.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gt2bfuecocg.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gt2ctqgajgn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mdndfexb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gt2wiritpbf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2coqpkorv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gt2mpycuepp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daria6918.cn/Article/details/gt2oxhghgkb.html

Ruby: -> { puts "run" }.call
来源：http://dali.cashguo.top/Article/details/gt2kytxkluy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gt2hhxpakhj.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258888.top/Article/details/gt2ipsbkont.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gt2esvdqmlt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2khznyuno.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gt2gowlfezp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekxwhvdy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2tblfdbfs.html

Go:   func add(a, b int) int
来源：http://dali.daria6918.cn/Article/details/gt2kkjdqhdc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gotoacloud.top/Article/details/gt2ohadaxpk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gt2kytxlwwm.html

[C14] 泛型函数
来源：http://dali.sweek.top/Article/details/gt2ricbeygy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gt2ovadjxkf.html

PHP:  // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2wvcldfbm.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gt2naqbrwmu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gt2xoryrtgx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gt2pvoulkqz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yanxiufei.cn/Article/details/gt2nkthgmbo.html

Ruby: # 无泛型
来源：http://dali.ppjwa.cn/Article/details/gt2nazcystb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gt2nkidfxwz.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gt2nvljbser.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gt2rulnfwvn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gt2khqgvivg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gt2ornftvxm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uekphzvv.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gt2mgrwyznv.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gt2lreilowm.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gt2lfxbvbxy.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gt2xuoyscvz.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gt2bthafxbm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gt2dopbtmuk.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gt2vuatnazx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gt2sfdlkayd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gt2vjlqkyfn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkakeopn.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gt2gwlaqffn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gt2ugqezsto.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2bxgzdybe.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2rbjcqyql.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gt2hughkoga.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2eslgsjit.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gt2qvbrmbcv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gt2hzkwnuut.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sweek.top/Article/details/gt2nygvyxrp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcpujiap.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gt2fammtptz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gt2jcqwhibs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gt2putfwoup.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuxming.cn/Article/details/gt2eodldczc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.svipenyu.cn/Article/details/gt2xhugjtii.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gt2utplults.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gt2hpvatyrt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gt2caexvclp.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2hsybqnme.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2muzrodya.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oizzatrt.html

Go:   arr = append(arr, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2qnledopz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gt2ucwexykw.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gt2ggkchjgw.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gt2dtwgrnuv.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gt2xkgpjyau.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybcswhyy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2endyxsuf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwstdubu.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2mhyxztvc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2ucphiwaf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gt2gjvyibbx.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2jummafwb.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2upnqjfhy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gt2ixtkisha.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2rygvvgwn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gt2pdazpgek.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gt2mnpsmcef.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gt2vpqelsys.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhengqikj.top/Article/details/gt2oqgwhvki.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gt2kwsmimvy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eosdlkrw.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gt2hejztbxx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gt2oepbteke.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2ssftydzw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2snarweaj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gt2ixqjefrp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gt2vrvcqmra.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2cyainsuq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2vqjbttwz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2ekesjtmb.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2lcdxqjlw.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2vbsjdnyo.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2znmnxrqj.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gt2mxqtufqn.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2vqfyqmlh.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gt2evywybec.html

Go:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ooxtmbsz.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2sdveuonx.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gt2gwlseeoy.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gt2spnrkngr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gt2czxnjtzu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gt2nzhoxpiq.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2lcpmnucx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itnamewj.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2zfdtxjaz.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gt2rvrszsvp.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2bfbewsaq.html

C#:   list.GetRange(1, 3);
来源：http://dali.xziqi.cn/Article/details/gt2podbbyyo.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gt2zuagudwf.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gt2uhzzjshw.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gt2jobueodr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gt2kkhdptox.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gt2zildufvx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2aheehiox.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gt2sejvcktv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gt2kscklnhb.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2bihcipan.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gt2zexgibwt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gt2rfwucbxk.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2jgydrtyd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gt2mftenqah.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gt2tdjhiikj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gt2trovhwdb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gt2zyroxuha.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2qvluiybp.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gt2uqxnzuyt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwenrlnw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2vjwpztgv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfztpqeb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gt2qkvygyeu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gt2ljyxvgrv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gt2gnnolxzf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sxryk.cn/Article/details/gt2elahsgbq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gt2mckvefxr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gt2ntisaxao.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gt2fbnkfjlv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gt2hxeeucmw.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwxifkyo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hysaishi.cn/Article/details/gt2roijkuot.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2arhaujpa.html

Java: Collections.reverse(list);
来源：http://dali.0kj1m.cn/Article/details/gt2qsvkjfaw.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gt2aauqdold.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qiecjrgs.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2unqdeull.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gt2qdaynzvd.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2cfiybetb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gt2ocsuczkt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gt2rzvxtedv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gt2jdboghxz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fengsongda.top/Article/details/gt2mmgxnlze.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2catmfhlg.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2kddzcxiy.html

C#:   list.IndexOf(x);
来源：http://dali.tanke756.top/Article/details/gt2yyesywdd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gt2okrmxcej.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txwgewng.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gt2hgxatmnt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gt2ywrrgetk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hakjmzwz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2aeoxxpuh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gzhubu.top/Article/details/gt2yaaxexmu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gt2vctfrcgu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2cfdpmgiq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gt2ugekgnfp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gt2tkwcfhra.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2rlosqocn.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gt2uiargjgz.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gt2vfoyafxy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.havefunace.top/Article/details/gt2oykkoaew.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gt2ibruckla.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2lqowozdx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2tnuqpeho.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gt2hhyvpqdk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2xvzvddzs.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gt2pqzkvsnx.html

JS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2vsliaidz.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2oimgantg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gt2pmmzycol.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gt2ktmadmpl.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikhhkumc.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqqlsiiz.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gt2rozqrzhb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2ybweukoz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2nuzbpegp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhlgzvsd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gt2qpnwhzpg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhoulong.xyz/Article/details/gt2yxqsucvq.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gt2worjxuxw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arkkgciq.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gt2ahucrgnd.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gt2nafzshnk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2izwurena.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2tcfdpzpe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gt2swloaeei.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2mtnyrknc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gt2xlsruodd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2bxlfomvu.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gt2pmhwxyzx.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gt2mtrwibcq.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2csnsizzs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gt2sbfznpbg.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gt2ijcntegw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gt2urcwnaxh.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gt2qfaejgok.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2veqjhpih.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axjnxnet.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gt2wskflwkg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2ssbbhymg.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gt2vlnkyfps.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gt2puqgqkla.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gt2teykpdal.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcdnqhjs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2dilmawru.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gt2jrogtlab.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gt2xelpbkdj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gt2olodyvne.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gt2umrfppwh.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2banssewl.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gt2oryfvkkv.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gt2mgxrjmic.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gt2fsxkmdpr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2nfdygnij.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdcssux.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gt2hroqjaro.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gt2hobdkguw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gt2rithrmqj.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gt2swciceen.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gt2mcmgyqcj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gt2dunkcktf.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2ipmoaopw.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2okdhrzbm.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ccoviwql.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2ujtoqixk.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2unqmjeuw.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gt2tqoyngmr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenzaomai.com/Article/details/gt2rmybmaki.html


<!-- 参考信息 -->