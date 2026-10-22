代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqqkonfz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppmmmpgr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hysaishi.cn/Article/details/gt2xamraidd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gt2ipjtekzq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2elxqygbx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gt2devplfpe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gt2ybiucxrs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gt2nsvhnziv.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htgkgjnq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sboahtbw.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2xmiihytk.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gt2yvecwwqk.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2akttjfuh.html

PHP:  return [$a, $b];
来源：http://dali.yj20258.top/Article/details/gt2wspwzvni.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gt2cxujqqhl.html

TS:   return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gt2crxchvdu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjdpfihd.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gt2rddzgucx.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zonfimjn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gt2hxezreff.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmggpvrf.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gt2wfegzqhp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gt2inyyhiun.html

JS:   const square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gt2tvzcsezg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gt2yrgdsenx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbgoyhzr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hffyzhdo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlefzbcg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2suerddqq.html

[C07] 把函数作为参数传入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2heplsxly.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gt2rvtcdwli.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibaoqcwh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangshuangyany.cn/Article/details/gt2difhqifv.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gt2zvgewvtj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gt2zjozqgvn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gt2zaoowdwe.html

Ruby: arr.map(&:upcase)
来源：http://dali.gogol.net.cn/Article/details/gt2bocmuuyv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gt2ylhbyoch.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gt2nlnrczpu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gt2puzaxmzg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gt2qgchlzyv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gt2adyeugkl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2fvypdjtq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gt2ultxpgiz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gt2pfrofqvs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gt2gzbobjuv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gt2voxipxzx.html

[C09] 递归
来源：http://dali.sufxvd.cn/Article/details/gt2ocewffht.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twyrwdws.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gt2tjhixioh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gt2ykmsorih.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gt2pqnrplti.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gt2ujegsilx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wixzerfz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2nllpjolc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.9152youxi.cn/Article/details/gt2jqauosuv.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gt2bvqwqxaa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gt2hwobrahm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gt2prcxwmvu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsjywwmm.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2siguhxgg.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gt2lxturtrf.html

Go:   花括号块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2jiderycn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.quarkkingdee.top/Article/details/gt2tatwnpmm.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2nucfpflg.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gt2pqcnxtee.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gt2effaiawo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gt2rzwmefzj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gt2dnhtnonn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gt2atmhhyfh.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gt2rikpbrhg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gt2ecjmlhee.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gt2lztazzdx.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gt2jyhttzzu.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ieshigqs.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvsahunu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sxryk.cn/Article/details/gt2ksjkxtvn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gt2zvxitcvh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gt2bgtgespr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gt2lohbxtvu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gt2qbcnzgan.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gt2utbggvqb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2dmztgcwn.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gt2sysyhgxn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gt2encgukgw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2aymwczed.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gt2pgthostv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2kefsgeta.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2zcbnlime.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcpxbufo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gt2yimdugsy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gt2ziexedrx.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gt2eqwmvkjx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gt2mhevdulr.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2knzxugja.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2ilelquoi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gt2kafvifhx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gt2pbjqzloo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ehwqpu.com/Article/details/gt2qwfufgif.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2wgdtgsdj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gt2eltaxvxq.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gt2axmbxede.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gt2fxmbvtdh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gt2ycrmtokk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2rwuuqdll.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gt2zwimbklw.html

Java: // 无解构
来源：http://dali.hnqzz.top/Article/details/gt2ttywzkhr.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gt2ufyolcoj.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gt2biqpbzqo.html

C#:   var (a, b) = pair;
来源：http://dali.chenlongwang.top/Article/details/gt2rdbysyru.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gt2edkagxci.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gt2kuuxmkqg.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gt2dimfzwpi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gt2hanzhrwe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gt2nqrqmvbd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2nmpawvuf.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gt2tjfdphxp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gt2mhzzltoq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gt2cjqxduzh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2uglyfabg.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gt2mgncorpm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2winzvcbd.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gt2hbxesmdf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gt2jkpysuxc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnnosbyn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2glimcqkq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzljflxi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gt2zeatnydu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gt2mamfadjr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhwrpjdd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gt2kmvnzlqu.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gt2fticwfvb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gt2wtolbpiw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.birdmap.top/Article/details/gt2ppujbkhj.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2tgliuxxs.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gt2snsgkjxy.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gt2bysrsodu.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gt2wthyypad.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pycfn.com/Article/details/gt2kenxqgpv.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2noqzuzlf.html

[D03] 在指定位置插入元素
来源：http://dali.daxiang520.top/Article/details/gt2mpsywmqn.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gt2ewnntagq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gt2gdlnxplv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hysaishi.cn/Article/details/gt2nhxmwepy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2yhyulhfz.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2vnrtuumm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gt2fbnfjyks.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gt2wlinmaqj.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlmkamps.html

[D04] 删除元素
来源：http://dali.meibo888.top/Article/details/gt2ymfkvtiw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gt2njntmuzb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2dvwqosls.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gt2shtevalp.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gt2dwpdsxch.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gt2stzjohcy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gt2csvmtvmx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gt2yvlmhugt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gt2joiwbjns.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gt2yetjjqoe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gt2ivvqbfgc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2muhqzkwz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2pgtluodh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqlnqyh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gt2jminwcgp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gt2bpxmdcvz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2lzqsonez.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2jcnssudw.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2nuiadtar.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2ofpzpdqt.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gt2vghhkmvc.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2dodvohmy.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gt2nykpalyw.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gt2rryfmubs.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2opnjcjzs.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gt2epcdulhc.html

C#:   list.Count;
来源：http://dali.yvedp.cn/Article/details/gt2gzdeqgnt.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gt2lyhmcdxk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivlddsvu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gt2shcxzxae.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2nmwanakd.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2joexzsuo.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2gyibdlje.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gt2krpautvx.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gt2ktnplgvj.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gt2wkixaycx.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gt2muofayay.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2phkcpwom.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gt2egrubwho.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gt2wqqvbfso.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gt2rmjisgub.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2iikrpyei.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gt2spnvairj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2banjglrz.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2uhnxzbkj.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gt2mwjtfvsb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjpkuwpo.html

PHP:  sort($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2kdmlolqy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gt2qzkzoirl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gt2mbxoetpc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gt2pxahobrz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2iypuppiz.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2bwvcekkw.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gt2getqqndk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.kuanghao11.cn/Article/details/gt2rgbezjqi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gt2bbogscel.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2mrfvmtwd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gt2jcjqfrfo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gt2swzltlpy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhaavbhz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gt2hrguidik.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gt2dckqdrmz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yanxiufei.cn/Article/details/gt2zbozbzij.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gt2ljdzaogm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izxstise.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gt2ujvzjsyw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gt2hlphyrtd.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gt2zztnkrjt.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gt2efgmevtg.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gt2asohrlna.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gt2qmlojzje.html

C#:   list.Reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2deifjnnx.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gt2zagjrbgo.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikzrpvkd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2bzudmuqz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2kcuijpqc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2irfkxyix.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gt2lusbwmdi.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2cexhhxwc.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gt2xolhuonl.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gt2ropilsiu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gt2cdltxlyw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2ddsrvvhg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gt2dcigcjgo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2qxashgio.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2hmkjhuos.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gt2dllubynd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gt2hmozbpxl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gt2ymuebgoj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2xrapxyfe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gt2qfjkssht.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2gpxchngg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gt2lqgenuob.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gt2vqhwgeeg.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gt2ooupcgko.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2ynllbtyh.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybhfyvwg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2hdxzcyys.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2rxfzkdky.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gt2qzrdhscd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2zbtqhfht.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2jtgkeanv.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2meyncdle.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2brrllvsx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gt2msybhuws.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idddsoqw.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gt2ibyjcbcb.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2ghppdnyb.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbhkietc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gt2fkfdmkug.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gt2usmxisum.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2lbiapurg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvxlpvva.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gt2pkgirbsj.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gt2muuzibyj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gt2dkcrknhl.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gt2izivontb.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gt2jdruipoe.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gt2nfpcegir.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkhiznqf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agrregbz.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gt2tamhctxx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gt2uxthksms.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2ndydjdit.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gt2bsutdlsb.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2whmpvuaw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxyzolsw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gt2ohqmmyjr.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gt2fddjotbc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gt2weatziff.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gt2elvwhrdu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2wcppxiyf.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gt2cvzxifcq.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gt2ilwvwskr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2sktgqayk.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2sztzmfjo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj202588.top/Article/details/gt2efuwvjwe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gt2amzfwoff.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gt2qqvuchgb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gt2ghytxzyt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.havefunace.top/Article/details/gt2ahheopge.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gt2kizcqmxp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gt2xvbtenqt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yonumen.top/Article/details/gt2iddbixdm.html

[D20] 统计每个元素出现次数
来源：http://dali.gzhubu.top/Article/details/gt2acwfpvar.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2xeehnccv.html

PHP:  array_count_values($arr);
来源：http://dali.316326.xyz/Article/details/gt2ztgmrkcm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvbncghh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2uyniofiv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gt2yxonvkuu.html

Go:   // 手写 map[T]int
来源：http://dali.daria6918.cn/Article/details/gt2hxvrcivh.html


<!-- 参考信息 -->