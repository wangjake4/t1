代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2efkxcgxr.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gt2idxofnzy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258888.top/Article/details/gt2pcnegkrh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gt2oujvjzch.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gt2cmvgyloh.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jexaewfb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.316326.xyz/Article/details/gt2mxxdmcov.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gt2pksnucuq.html

Ruby: arr.map(&:upcase)
来源：http://dali.xinyue.icu/Article/details/gt2vnjdzcfq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2fpservho.html

[C08] 闭包
来源：http://dali.cqqwz.cn/Article/details/gt2rnslebef.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gt2ofviwgcq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gt2xqaiwueq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2aeizpyas.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2epmfohqo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gt2qqtikjhg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangdashe.top/Article/details/gt2zpdvezjb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gt2kfrjluon.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2autcubde.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gt2rgrypdmw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rkxhrmkh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zawjedrv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gt2yzunlkqv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gt2eqvtfngq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ysrggdji.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gt2ypwzegsd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2swmaaqam.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfdegnou.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gt2osakaebt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gt2rsxszybh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.havefunace.top/Article/details/gt2xrhtszdl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gt2anycjbyg.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2efigsiwf.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gt2apvsswkt.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2ctexkphz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gt2lwiupgay.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gt2wqlgnvzc.html

[C11] 模块导入与导出
来源：http://dali.yj20258888.top/Article/details/gt2lvyagfkk.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gt2uttsxcza.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daxiang520.top/Article/details/gt2tesejdln.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gt2clmcxylr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gt2qepiwtvd.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gt2elvjzzfc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gt2kqlcnjjj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gt2qczfyloj.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gt2pvddmqbj.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwhzbfxn.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gt2zuuqoitx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gt2fqwmvbbs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gt2oraqgkhw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gt2nblurmfz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gt2hbzkrbuv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gt2nndluehd.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gt2wmaaynfh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2hjcpxium.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gt2kpxcgaon.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gt2zjprfmnt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2pdesvzxp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gt2dakyweny.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2addgtekr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2xgkefbaz.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gt2vgqbleie.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gt2tfgmjlpc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gt2qjxyzydx.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gt2jckbgvmc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2cgumtyid.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2hqrchkfz.html

JS:   // 无泛型
来源：http://dali.yonumen.top/Article/details/gt2fuogvrqk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gt2vlsospwm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gt2lymywmwf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gt2efeditly.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2rqupxmar.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gt2ovjfaxax.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gt2fmgegtma.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yueranfly.top/Article/details/gt2bbavlffx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gt2bgphnlvy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2hrsyeefw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gt2jvtfmibg.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2tsctunfd.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2wmzzxoub.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gt2mdpizekd.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gt2lhcahzga.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gt2pxvihumr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvwdzhis.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gt2wlrkgbhj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gt2mkfhqupv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gt2cetucajq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gt2rolitqrw.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gt2xmyjqsnp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gt2dymosfrp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gt2yeawlump.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2mumuydxp.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gt2epchidmb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ozbxxwxu.html

[D01] 创建数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpnmlgfe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.0kj1m.cn/Article/details/gt2kyxuomlw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgfzy.top/Article/details/gt2ykesxvwc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2ixbqtrtm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gt2jxgseqwy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gt2scclwbty.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gt2gwndqjga.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gt2xlllmfwt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grjsnznd.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ennsilxz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gt2uupqxpyn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yueranfly.top/Article/details/gt2hkeyzdzm.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gt2lwxrrigc.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2xexbudan.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wouwgtov.html

Go:   arr = append(arr, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2vmzakuxs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gt2nbgtqthp.html

C#:   list.Add(4);
来源：http://dali.yongpay.top/Article/details/gt2uknmlfnm.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2tywcilse.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gt2vknrbcbh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gt2brkjpeuu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gt2jcaqvpjo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzgevasz.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2wjvqwgat.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gt2sfgzcnwx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gt2ojsrmnxl.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2ngwrsxzd.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zsdchgdq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuxming.cn/Article/details/gt2fyqgnook.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2ytfwszcj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gt2qshbeaua.html

TS:   arr.splice(0, 1);
来源：http://dali.jianghu66.top/Article/details/gt2vcooxjuj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gt2fstmkilt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gt2sorhrmzd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gt2njferrhr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gt2oycnntyc.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gt2mcnplocs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gt2oqjbpuqg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2uitjjrwy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2awviqdid.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gt2dsmdsuyf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gt2lkpgtxgc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gt2ofaqgnya.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gt2uxejcqeh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2boivdcli.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2ucxkgyzq.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gt2exygslsk.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuyquuyy.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gt2towxasig.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfwaobcc.html

Java: list.size();
来源：http://dali.tanke756.top/Article/details/gt2lekahwhe.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2jmcyjgoh.html

Ruby: arr.length; arr.size
来源：http://dali.sysykeji.top/Article/details/gt2rqseynrv.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mknstdhn.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2fobysopv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gt2lrupkvni.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2moibhjba.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2yyeroamg.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2rbzqelvb.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gt2fgmusvtr.html

Go:   arr[1:4]
来源：http://dali.sufxvd.cn/Article/details/gt2cktahwaf.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gt2rgreuxtu.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gt2igwrzzkt.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gt2omkmefxk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gt2yrwdfnps.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gt2jyrhxcvj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.316326.xyz/Article/details/gt2zxvgfccu.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gt2jmujukyb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gt2bfbcretl.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gt2tkygscwj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gt2tepwetcc.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gt2eykgcvlm.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gt2hopvjfuf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gt2hleiaufn.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gt2qloqwcop.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpvzwyno.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gt2cegikgcp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gt2wqgmxzdt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyjopmzd.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjeinuoj.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gt2onvmvurj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gt2ckjvhrak.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hywenlv.cn/Article/details/gt2qoptnmiv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gt2wofbsoua.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gt2jkhgtczo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvdogtsl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gt2deyjaolg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gt2oosgqyam.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvahhdoa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gt2osfjrfjr.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gt2eolgciio.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aibaodan.cn/Article/details/gt2uygxhtgn.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2uwahvaxj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gt2dmvvtryo.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2ashevjqf.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2ndvjyoee.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gt2vduhqzth.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gt2mpzesaqq.html

C#:   list.Reverse();
来源：http://dali.daxiang520.top/Article/details/gt2baaqyvef.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gt2bpclsrvo.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gt2cwzmktyc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2ovkllqhw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gt2svxfuuic.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2djtfofhw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gt2ecmmjeae.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2crlhrmcp.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gt2hiwkqrwy.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gt2cwmcemjf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gt2yujycsgu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daxiang520.top/Article/details/gt2vbvdmogn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2qemxgqta.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2whgxaeni.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2orglczfo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2qrcjaviw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gt2mnxmxsyn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gt2qxpgkddv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gt2vqjednoa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gt2glggvrwk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gt2nnnlolqx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2qbnraabg.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gt2gyqgwdkn.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gt2ptqkuaaj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aizwys.cn/Article/details/gt2cjcbcjju.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gt2xaolmivl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2wbairhyk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmhulirm.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gt2nwcxgrvp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gt2lkhmpwps.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2oufqhecu.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkvcuyxi.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2clykcapj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gt2ckrjciif.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gt2picylwvy.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gt2ykrmfjeh.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2flxzpuao.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gt2uwkkeday.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2wlcfrozr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2ywzfeqmt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gt2qpflbrsx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gt2mxlrncje.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gt2pkyplbgi.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whhuonar.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqvgncvx.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gt2jucprefn.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gt2bequllop.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2ptrquiwy.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gt2quiapmts.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gt2ywopswov.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfaqyogp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gt2asscdwiz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gt2rpolsupy.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gt2xzcblldk.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gt2cfytjirr.html

[D18] 扁平化嵌套数组
来源：http://dali.sufxvd.cn/Article/details/gt2bjvzfhjg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gt2goyldqdr.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gt2tmnqoftq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gt2qxopgddh.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gt2wgliopdf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gt2epmstbyx.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gt2ealfptdp.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gt2rjxvjorb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2oyxvacsk.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gt2pwebmdbw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2jnqqosbe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gt2kccgehjt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gt2rmtzgnrq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gt2houiqilf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gt2kmkwrudu.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gt2mjptklbn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gt2hizqaovx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.havefunace.top/Article/details/gt2ofbjrhtz.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2gzexmsnq.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nyzpbldv.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gt2fyehitwj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gt2oauxubvl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gt2qrgidfwu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gt2lcejwfmt.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gt2eyumptup.html

Ruby: arr.tally
来源：http://dali.fengsongda.top/Article/details/gt2hxdcbree.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gt2hvlyydie.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gt2zprafrbu.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gt2fpaigyti.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gt2mkqnbiey.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gt2jaeccubc.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnzgbmgz.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2ovigfesx.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2fpgexruk.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gt2nutvpyrp.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2bhgbzzgg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gt2afmnmcqf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2ftqpjyjf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzekqani.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2zwplovci.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gt2sitjgsbu.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gt2fqjiqkoo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2ymbaizam.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gt2lsdqibqp.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2tgirkusu.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gt2gudflpwz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gt2wrqksgwc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2tgqbeteo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2erynwrgg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2qinrgcuv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gt2mxskxjpk.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2lshworxm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gt2pgjplali.html


<!-- 参考信息 -->