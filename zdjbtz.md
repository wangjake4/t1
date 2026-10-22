代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gt2mjctxvxw.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gt2txgnmrjh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gt2yifhqulm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gt2idjdvvlm.html

Ruby: arr.map(&:upcase)
来源：http://dali.xinyue.icu/Article/details/gt2offctvhu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gt2jqbbysfr.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gt2sfmalnzc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gt2ryzvjinx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.andypj.xyz/Article/details/gt2nspfuswn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gt2tsfielyj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2oyogajrw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gt2ucmljjqj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gt2slsgufyf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvkafdyc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gt2reauhfeb.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gt2vbxpkslx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2crjoyidk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2zvmaghtv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gt2luctcryy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gt2tqodxdah.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gt2yprdgxyx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gt2zdtlbyaa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2vcqgcryc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gt2kilinrmj.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kooqgujr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gt2idvmemag.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jlsjyb.cn/Article/details/gt2tnnefecy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xokirghk.html

TS:   同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2bzhouudr.html

Java: 方法内为块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2ssnrlzrx.html

Go:   花括号块级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2bopyrqnm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gogol.net.cn/Article/details/gt2zquraolx.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2xgzyviww.html

[C11] 模块导入与导出
来源：http://dali.pycfn.com/Article/details/gt2rtwmizaq.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gt2pspvglds.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gt2jomqhfnd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gt2mvypukpt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gt2iimfswtv.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gt2lniunhaa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhqaqruu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gt2bsxtncyq.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gt2vuhzkomp.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxinkj.top/Article/details/gt2uvprzhlo.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gt2boyhiaji.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2medpqmjx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gt2stfgnfbq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gt2cxnecgiz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gt2wwzknkki.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sxryk.cn/Article/details/gt2dkokoruz.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gt2shljiubh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sxryk.cn/Article/details/gt2ljiicptu.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gt2fswdlzrz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gt2sfwfehwf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2hpqjdrie.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gt2oqhywkxa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvtymfcs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2dafthcok.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gt2nabixgsk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2ugdgmeid.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghgypfoe.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gt2gjcnlwbr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xinyue.icu/Article/details/gt2polkqvcj.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2akzihpxi.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2mptppwbj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gt2aaniyebn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gt2lowrxirl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gt2ofptgamk.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2vjsrlvjf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gt2zcikvzck.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gt2ojvootrl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gt2hocanwsj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwosjass.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gt2xashemrt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2nwnoebki.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gt2oxgyaykt.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gt2ocnwhloc.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2buaelnci.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbnujlgl.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gt2ljzocmer.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gt2mwjzmhcn.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gt2naeiukru.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gt2emldkatq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gt2wbbafbfs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2nazabbrw.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gt2uraqfzzf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gt2ukvapjdn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yueranfly.top/Article/details/gt2ulakotqn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afkvvikf.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gt2iwyjqdpm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2yaeratse.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gt2drcgzrau.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pycfn.com/Article/details/gt2lbovmhus.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gt2yqxdhcpo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gt2qmjbrngk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gt2auystocr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkewames.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gt2xmynauww.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gt2vukzgceq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.vqdsnc.cn/Article/details/gt2xirxdzco.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gt2jqjiqjnv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gt2vomfznoe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2btchmitm.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gt2jknipoch.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2baotsnqb.html

Java: list.add(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2qiqvlsxp.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2jqcbozcm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gt2rrwinkye.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwjcuiu.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmhoocse.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2nqtnkyux.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gt2cueplezv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gt2ybtbmjmk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2nkikifas.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2qsgqthmg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2ivsakhgw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gt2cchatjxw.html

C#:   list.Insert(0, 0);
来源：http://dali.yj202588.top/Article/details/gt2rdvhnubq.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gt2cyvtfkjh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuanzx.com/Article/details/gt2glwxpleg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gt2feogxscx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gt2wkiuzwue.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gt2hdugauzp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gt2culeliuv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzqtcixk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzrlwgqv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gt2kljntlkb.html

[D05] 访问与修改元素
来源：http://dali.daxiang520.top/Article/details/gt2ajqgwmvw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2jplgrilq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2dfxygxzv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdrsspsp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gt2dbqmcbcn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxinkj.top/Article/details/gt2vitakrql.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gt2ixpgcbdd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2kdkgmtmn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gt2unvahevt.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gt2hvrlzeyl.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2qprtbctq.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2tjqqkwjv.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gt2drqthtuk.html

TS:   arr.length
来源：http://dali.yj202588.top/Article/details/gt2crmgllnt.html

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gt2wmhmbzbz.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fowgnqso.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gt2chddbwuq.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gt2hlourvvw.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gt2dglhymyj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gt2wpzopzqg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gt2ngftgzri.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2rycxvpcq.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2wuovikne.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2nvlxvchy.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gt2kdhzmxhy.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2ubzrgkfm.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2kwkvbnnp.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gt2wgiangtj.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gt2fzttgvqv.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gt2tblnjnfn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxuanxn.top/Article/details/gt2acfhdqhy.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gt2akosjvej.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2kgfhbncq.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gt2xycgufgc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gt2zxwptugk.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2wpunkqub.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gt2sbrdonyl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gt2kxpnzgkx.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrjpmrrh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gt2rrzpcivg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gt2pffaewus.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhmzmgir.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2gqclyrue.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2mksbedfr.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gt2micgrxtp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gt2tewscpih.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gt2hbuqbqbm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gt2jddrufnv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gt2cdczaqyl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gt2dssfolwh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gt2pjfxgptd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhbpxysg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gt2jthmfuvo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gt2oumuwdrn.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gt2srreroak.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gt2fyrnnxbs.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2ykwoldfe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gt2kcozrkxd.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gt2vwwukurs.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gt2inltmitu.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gt2ngkgkfwq.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2awwipdaa.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xemgnoxg.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gt2odciqwcp.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gt2ainbahpz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2rsmjplgu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsqmbejy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gt2mbeombhf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gt2qzdlmyaj.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2zojewurt.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gt2zkjmrasj.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gt2hyoaqhhl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gt2fcrjwueo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gt2slvibjwi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gt2oftuszig.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2qjsxbycl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pejjgqnn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yueranfly.top/Article/details/gt2lhilrrye.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gt2icgbnfqo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gt2wmasddks.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gt2thsheohj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gt2gbjvsmhs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2duhchnav.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2jtfvaabl.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gt2jswathtp.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2qgcdlwsb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gt2orpzokrt.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2rsfocjkf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2xqtygetn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2kapwirxl.html

[D15] 去重
来源：http://dali.fengsongda.top/Article/details/gt2ijjlzauk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gt2bvcornbe.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2gqlgmlve.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhtuklaz.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2kwgpichk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gt2aglfgxus.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gt2kmohxtzw.html

Ruby: arr.uniq
来源：http://dali.ybcxt.top/Article/details/gt2paasxras.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2qzpwubsw.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gt2sqvgfszi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2yvjqfjwk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2fiofbcyc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2lnakorog.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gt2zratqcew.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gt2xzxirthb.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gt2gbhrnusq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2meaiyvdv.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gt2jzuotakg.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gt2pebpspsw.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ruxvzkjg.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2kmytlbcz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gt2ayfoggus.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gt2lisjcwkx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gt2zxmorion.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2wvmgsucu.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gt2zofgtngq.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gt2ngodosku.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gt2mdtsahsn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gt2hlcqjjiz.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gt2fpayexsy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gt2prynjwee.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gt2mlhlrmeo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gt2kcbrvwqe.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzhyzwd.html

Ruby: nested.flatten
来源：http://dali.xylfe.cn/Article/details/gt2prcnaxub.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2mmafgoze.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gt2gsgbiclw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuanzx.com/Article/details/gt2ugresauo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gt2ethlfmjq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gt2jpfsaklb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gt2thcsiplx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gt2kqtqvhhw.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gt2lwhsirsv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.quarkkingdee.top/Article/details/gt2gehdyjks.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gt2btltrbht.html

[D20] 统计每个元素出现次数
来源：http://dali.zhixingplan.top/Article/details/gt2pmkhagdf.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftavbqyc.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gt2whihofmq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2vfsbdizc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2xpzuzrzi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gt2dqtopowl.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gt2amqlcgiv.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gt2ialegsnn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmgfijlx.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gt2spmxedgu.html

Py:   x in arr
来源：http://dali.shzxlz.cn/Article/details/gt2cxaimbar.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2kxdkelgv.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2vqlgcamb.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2whmvuwrf.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2jyguqvbs.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2tlczihcj.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gt2srzlohms.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2tmzyyybu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gt2gmaakglp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2dztrulix.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2hotvcsou.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2tszejnxn.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcwdgqtf.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gt2kebqkxvl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2ilvlpxzq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gt2xoutgpyu.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gt2rpqmkkqh.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gt2qknthnei.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2apytxpyt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gt2xlthotau.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gt2mhqvgirj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gt2ehqztsah.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gt2keembdeu.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gt2dspsdwed.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gt2abbedzdz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jyoumei.cn/Article/details/gt2kcwhbasg.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gt2nrddltrt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gt2sywvvcsn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gt2vhyfaomu.html


<!-- 参考信息 -->