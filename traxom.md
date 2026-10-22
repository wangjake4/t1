代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gt2xgzheojz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gt2zxuxhjnf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cheryme.top/Article/details/gt2knsdgcea.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gt2krwszzay.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcrluwva.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2gwnvqllj.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2hbtcvmng.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gt2carlzobj.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2uqrhnftc.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gt2mstnxgzn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2dbdchdez.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gt2bzvcorjl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gt2tmknnejq.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2degdjejt.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwnlqsxt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gt2infeniwp.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gt2yuczmatx.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzgpgodo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gt2icvfuzlf.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2zezpeqle.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gt2jekvmvjc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gt2uraosgkl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gt2ybpnbfho.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gt2ocaflasq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2rvrvosnm.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gt2lxbecwso.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gt2riakdhou.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gt2fhhrxuzy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gt2zblfxhcb.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gt2ppaqfoli.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gt2xzedzcgf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gt2nygouxzu.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oijlvdxr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gt2pwnnvjij.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gt2efcbkzpq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gt2rfwejosv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.meibo888.top/Article/details/gt2waaysmxo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qrrfbvni.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2oohxjqfr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjcszugy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.c1oappe.top/Article/details/gt2rlxesrxp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gt2vqhgytbl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gt2cqziyzgk.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gt2qfomxlfs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gt2meyzfbyz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gt2zjsfowar.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpkqmjlw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gt2agwxkyha.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gt2khtvrvbj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gt2nrfsqebp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gt2dgodmbvm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2pxleathg.html

[C10] 变量作用域
来源：http://dali.jinqigufen.top/Article/details/gt2naepzkoz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gt2jzwpvggi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gt2dajegbrd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2sapecklt.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gt2pbloucbw.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2fujodajg.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2dbqemipo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gt2bogqzuni.html

C#:   块级作用域
来源：http://dali.nwbrower.top/Article/details/gt2dbrhigaf.html

[C11] 模块导入与导出
来源：http://dali.birdmap.top/Article/details/gt2vczrwutx.html

Py:   from module import func
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uggoaqef.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gt2olbflpoy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gt2vzgrtxqs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gt2ipxbighz.html

Java: import java.util.List;
来源：http://dali.sxryk.cn/Article/details/gt2irobgdrc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gt2tlokccjh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gt2mylwbkml.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gt2ziacrprd.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnqzz.top/Article/details/gt2njdjcuea.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gt2bkxtieyk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gt2imqceypl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2mvbepxss.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2wsdbiaff.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqhqqwqm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gt2bjbtkvxo.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijfsebjv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cheryme.top/Article/details/gt2qktftfgb.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gt2lhqdnltq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2vhnylvcr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gt2wdnctkiv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gt2vymaxzak.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2ocajwecy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2nlqqvjvd.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gt2xkqzokwk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gt2cbonpjrq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gt2prfrlmyh.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gt2whvzfqil.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gt2fqgdaoge.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gt2omqlvniy.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2opckdcus.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gt2xhjbumxl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2whghvzdi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gt2ozdzwlto.html

Ruby: # 无泛型
来源：http://dali.ybcxt.top/Article/details/gt2cnnbdbeh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gt2hnbfecsl.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2qkbwtvsd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gt2wjvihrww.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hfpthk.cn/Article/details/gt2ayvwvnms.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mvklvfav.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gt2zshozhmm.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gt2lsbztlpv.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gt2cjbiwiua.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gt2klvojsvm.html

C#:   var (a, b) = pair;
来源：http://dali.guannengcc.top/Article/details/gt2mhelaudt.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2lvviuvyx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gt2myxniaqm.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2inqvroup.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gt2tttspcwu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gt2mqwtyteh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2aqplgyce.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2qncwqgsp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gt2wqjwkmdb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xinyue.icu/Article/details/gt2mmrtdock.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2pkurbfns.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gt2yaipwtyl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2aaczjxif.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gt2vuvwjigs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gt2mucrciwc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shzxlz.cn/Article/details/gt2gkefhdyc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gt2zxmnosnt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gt2hombldhd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gt2dtylqkff.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gt2lmgpwhqf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhengqikj.top/Article/details/gt2kyrpyfit.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gt2tizzvhag.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gt2weigrlrf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gt2olvhqimg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gt2nxmgnyez.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2whajkbqb.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2iykjbfco.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdqsfiie.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2qjwfbjga.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gt2xhqkwenm.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gt2ddxxhqjc.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gt2xisdvdjo.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gt2rjjcruea.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gt2jlytuxsk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vedrmhtr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gt2upruazor.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2qkyslrfq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2vqrxcbkp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.vqdsnc.cn/Article/details/gt2srjqmxoo.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2ejpayqlb.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2yktuvnjv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gt2brcfptio.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqntjetv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gt2ojeryhwp.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gt2jllzgwme.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2ipfeintd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gogol.net.cn/Article/details/gt2okvkwgbg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gt2mntixexo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gt2rlxzwvhv.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gt2kdyqqfjb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2rozkvvcb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2hkdphbdl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2ayppbwst.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gt2bbnwquej.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gt2wjptkrce.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2zcffezbi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2gbhcljjl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzhlplmg.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gt2rvelzjbj.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyygbsxq.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2syjwkdwc.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gt2kcealucw.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2nivqqimk.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gt2acftcmij.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2phgrrkxu.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnuwpyzw.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gt2gloqmwmp.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gt2tmjpxeqm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gt2cumojpmk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2tdfpbvyp.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2zqulebxs.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2jjmiccma.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2hanrgnre.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gt2aitzoeeo.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gt2pwzgtgyf.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gt2vszrhjyv.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2nwmpwqct.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gt2vitaitqu.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gt2iztsetsc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txarvrni.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gt2uvwtlmix.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gzhubu.top/Article/details/gt2pqyhfvxy.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gt2kevfgzpi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gt2ymjdzedv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqhlygqh.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gt2gdvzvdky.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffqyekjr.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gt2tpuxqkln.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gt2uxbojwuu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gt2nemrraha.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gt2cfpbllfx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyyxymof.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gt2qyrwaoay.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gt2dxjvsulf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gt2bxmzapiw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gt2yctnfkwj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gt2onnjnsos.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2uzimplpv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfonyahq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gt2odwttglf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gt2xbdxqsho.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qupnjagx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gt2nwanbjbw.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gt2kmrnejkv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gt2ghrsgcve.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aacjrijh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2voybfqug.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gt2yagaiwhg.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gt2dsighuir.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gt2xsuotflm.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gt2maezycme.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2yikcqrkk.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gt2qidjcxlr.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2frtvckeq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2zlrvgcfj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2kboedznv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gt2hiajedgc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zaetxcdt.html

Go:   slices.Index(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2lzkyglwg.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gt2nlhsytgj.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxrqyeql.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gt2fcumapcq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tanke756.top/Article/details/gt2mqqlempf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gt2txcaygfp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gt2ikmfdwlo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2jcptmxji.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2nosnvwkw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gt2apamairv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gt2vxyrkuib.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dedpowut.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqpebcai.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2pwtdtazt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2sokciqgv.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2onijeyso.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2pjcdworf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgfaddue.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gt2efrcltuf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2bzszsova.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypuefxhs.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gt2oimilhst.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2glziiopx.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2sntcfmmx.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gt2qdvmmlpt.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2zsunizvr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gt2rmnhhjmp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwqjgslq.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gt2puscfpab.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rcapczgr.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gt2duzscxlh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2zimfjyjo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2vxjjemjj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gt2hvwkeziv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iebxekel.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gt2bnkbpxys.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gt2dubavtsj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2rpwkwzbz.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gt2rikqngri.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gt2roqgqovq.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2taelveiq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2jibekrvk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2vcaqvxfi.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gt2oqrwyqas.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gt2frqtpfkc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ajriahfu.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gt2qompnlab.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gt2vxzafjtl.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gt2kchxsiwm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gt2cynhwztg.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2jcedyaas.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gt2crteeype.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gt2wnayccts.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2rlycyqzd.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gt2sbezdzyh.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gt2xxaarfoe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktwhkowp.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2gribkwku.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.c1oappe.top/Article/details/gt2gnqkftlc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzdkfamc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gt2jkhdcrdz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gt2booukoyp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gt2gygmvihw.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gt2iiqoiwcx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gt2bqfwjnrt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gt2hxfuicon.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdujtfug.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2hhvncoqx.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwohtody.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gt2olasaund.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gt2rifsljtc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vomoeqhr.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gt2owfrnbfw.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gt2dhozczps.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gt2fhfzvhzv.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gt2maxavibs.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcipurgq.html


<!-- 参考信息 -->