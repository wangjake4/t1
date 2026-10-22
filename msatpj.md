代发 wailian999

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmcsiwhb.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gt2upjddvmw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2jjhtqfba.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gt2dyjfvxtm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tian-w.cn/Article/details/gt2ofxuwdpa.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2rdcjfrex.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gt2phiyuuvr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zdqjudy.top/Article/details/gt2yrawthlg.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gt2jtboobvs.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gt2antafzuh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gt2rvytxtss.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2lbgbapyj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2bctzimmm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2xbcjxdxe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jppmruto.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gt2akrfnung.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gt2ewiwapum.html

[C07] 把函数作为参数传入
来源：http://dali.pycfn.com/Article/details/gt2pcbnpwan.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kncgykpd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2kwetiulk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezdejuhu.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2aoasclgf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gt2rqofsrjr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gt2wclntthy.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkxlmznr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gt2sywrdgnm.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gt2lkuyrsni.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gt2wijwvbjw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rddhxgnd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ilkbundq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2cqrmymhe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gt2rbtrdvcp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gt2nfdfhwch.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gt2bpjlacco.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2duyrpwdh.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzzkpuln.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2yzteilzu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2ofvjbhuh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gt2fqqikzoy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gt2gjnmfrxt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gt2sshdojny.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tianlin.xyz/Article/details/gt2qmhqiibc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvlkwezl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gt2brjbjclz.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gt2futracqu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdklbfnv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gt2bgceuqts.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcmuhljv.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gt2wgjorsmq.html

Java: 方法内为块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqdbatko.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2aarmofnp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dashuyun.cn/Article/details/gt2rraxjnln.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2gonjhtlx.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gt2qqkbdlbw.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gt2lsxizhtf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozjlukur.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhmkvlco.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gt2cxeoorem.html

Java: import java.util.List;
来源：http://dali.cdnleiting.top/Article/details/gt2pbhhlgqw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gt2evecnqok.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gt2qkxebdvq.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gt2ifabvxpf.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gt2wuiplrty.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gt2yveqzajt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gt2bpypocjr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gt2fuuiictf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2jomasnyj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gt2wpeafqaj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gt2cedewwvi.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhongyouzk.top/Article/details/gt2nucsyjes.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2ezsbvxpy.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gt2xeqyatld.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gt2lhwmlqbe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2rufvlvdn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gt2gyojebmh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2msdojeis.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2xgikncqi.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gt2xoyjbvoc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gt2lwgskvqp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gt2yljgfyfq.html

[C14] 泛型函数
来源：http://dali.havefunace.top/Article/details/gt2ydoyotrg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.kuanghao11.cn/Article/details/gt2mnzzsewp.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2ksuoyvzc.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2hfotyrup.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gt2rwhgzfef.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gt2ctdzgvba.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gt2glyvyiqz.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2lyyhxnkm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gt2pkagtsgf.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gt2lqvtutbu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gt2lgsgxfhc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gt2tkgzogow.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kulggxzf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2rmfqpvkk.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2hdqffwjq.html

Go:   // 无解构
来源：http://dali.jiagoushi.top/Article/details/gt2opvbkbdg.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gt2fpiyafdx.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gt2meaynwyj.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gt2twihmzxi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gt2wqrzreap.html

PHP:  // 无重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2heiilwxj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gt2veysrpcx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gt2prrnyynq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ueetxjdg.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gt2jfipzndm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovsojsij.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2vklxjigo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oleewvue.html

D. 数组 / 列表 / 集合
来源：http://dali.hysaishi.cn/Article/details/gt2himwvmeb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2dhftkqlt.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gt2owamfoji.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdqcuqgp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2kiynxbfi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gt2ohnvgvjs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aibaodan.cn/Article/details/gt2wvdpdtvq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gt2kyltyyxq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izipwkhj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhtnjkkz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxuanxn.top/Article/details/gt2sucokoru.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gt2vkceeovf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.redwolf501.top/Article/details/gt2iyarzwbu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gt2xkhbbker.html

JS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gt2ondzsktn.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gt2epoevkij.html

Java: list.add(4);
来源：http://dali.hysaishi.cn/Article/details/gt2nasmkjvv.html

Go:   arr = append(arr, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fuzogsup.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gt2xxehpwej.html

C#:   list.Add(4);
来源：http://dali.sysykeji.top/Article/details/gt2hefkbmjb.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gt2wtxlxuqk.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2qcaanrpq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gt2teasjmet.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gt2tdipufbc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2prnetdyr.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2ogvgozgy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gt2qmizrhkt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gt2hepqfwvf.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2wlfrltvs.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gt2ysjaiqja.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijmhkvng.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cscytpvi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gt2czshgzws.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gt2kxxtzhof.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gt2qpvhrhtq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gt2vzixyvna.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gt2atmcypvc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gt2bfkvbgsc.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gt2nzhpaeuk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2xdfsaqdj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2cqztppwb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2lbfdhfbf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gt2ozpivfdf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gt2sbifpqie.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2ejafnvaq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynkbmflg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2upcojwix.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2ptzydhpu.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2oydjtfto.html

PHP:  count($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2pzcigrto.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnxxobjs.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gt2fdyioqum.html

Java: list.size();
来源：http://dali.guannengcc.top/Article/details/gt2ndbiswco.html

Go:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwyjspwe.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gt2hxutefyc.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gt2arnyaiqo.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gt2uaialcbh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gt2lwnwfnii.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2pvdarqgy.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gt2chbofuhu.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2gqhvkexh.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2rhycuuqd.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gt2yqofczlb.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gt2ryknuhao.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gt2zvrxaclj.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gt2rnfehzwt.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gt2psweyqan.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2exdyxpwm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gt2kmpvwadf.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gt2qxnzenuv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cirgxccy.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gt2ekqqhqhx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gt2ejzwzhhu.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2cfjvxwda.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gt2vsznsvsl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2fnpkuoxd.html

PHP:  sort($arr);
来源：http://dali.zycfv.cn/Article/details/gt2eqaiqdfl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gt2qertumca.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gt2qwetothl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gt2tgldrict.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2cxovqmmr.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkbnwnjq.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gt2ejrbgraa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gt2hldoikul.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gt2iiqlsccq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gt2pyhqfwti.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gt2gyrjtaiv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aomsuncb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gt2cgvforoy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gt2wkputnrr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gt2jdjsobpx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gt2wpzhpraq.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gt2jpbknggw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtlnednu.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gt2hohdmkiw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gt2pbdfcnvj.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gt2ixbzcwge.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gt2sgneyvhv.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gt2fzcueriv.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gt2fydrakzm.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gt2xfqftbqr.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gt2iyqocxgf.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gt2jhfudlpd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gt2ahamwuih.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2iupffapk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2zuztcpqq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ypmhmmly.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2ufnbuxlv.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gt2mvnaclsi.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gt2nmcanmmp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gt2tfipkdkl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2lipghyog.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gt2ocgjkltl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gt2izgbcazv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2mlomcyzi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2tdewvnps.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gt2lodjradc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gt2qqlyjzzd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2eslnwmfq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gt2fosdsqit.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rirqiraq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2jgvtpuay.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gt2fnohagjd.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2fithygfa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gt2mzyshcit.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2mwovotum.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2bcpsjkrr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2apjqlvgf.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2lbtruako.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2wqnbjvmb.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gt2eevmjdcu.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2csqoimtl.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2oevetnge.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gt2odzrvmwx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrbjiuft.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gt2mqyvyacx.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gt2dxseozyt.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gt2ogtvciin.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2tkohwfxq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2lqsbzkly.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gt2uywlodaq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gt2twnhmltx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gt2dpdfwdnt.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qvzepnor.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gt2tpkzxygf.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gt2zukxqmqz.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gt2bdqcfkgg.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqyzxkwn.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gt2uhobvyzu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sxryk.cn/Article/details/gt2dnphspqz.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmjhovdl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258.top/Article/details/gt2ktgpzxtu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2vhjbyyov.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gt2mqzdagpm.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gt2mlcazber.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsqpjhce.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbfhojiu.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gt2owtypvcn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcnxvabh.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itfnajnh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xldrrcbh.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ohawegxc.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2uceknoup.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gt2klmmivsc.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gt2sddwmout.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gt2tuplkill.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gt2dbvizwvn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gt2ocvxlhtd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gt2pmsghxfx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gt2aaykxtpz.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gt2iqbvqxka.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gt2nobzmgxh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.0kj1m.cn/Article/details/gt2ozrtxpab.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gt2rstuxqhu.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gt2ktoeseda.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gt2nevploxn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gt2peoomvrx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gt2ilbiohip.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofgcnkpf.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gt2trbtiayc.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gt2dvmqclmr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gt2xxhextzg.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gt2pynscnlv.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2snarwfuu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gt2iknrdgyk.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2abtssrkb.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdhiizst.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2eyqbmrmy.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2btbktqrj.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gt2hehsgulq.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zppjzlmd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gt2kzrkypsb.html


<!-- 参考信息 -->