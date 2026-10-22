代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlbdxxlj.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gt2mnwinkby.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuanzx.com/Article/details/gt2ebsbkfcz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gt2wxjmjiye.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2brptkkwo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpdiyrqp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gt2eghemwag.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gt2qhsarkmh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gt2dbsimzsj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gt2xemntsqp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gt2jwbvdvrg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gt2pjhzqpwl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gt2qttkbyuy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2cxalaiuy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2gyiswimf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgufenzy.top/Article/details/gt2cmqihhjx.html

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gt2xrvwrhru.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gt2cdvgjkfd.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrazacrk.html

[C05] 返回多个值
来源：http://dali.yonumen.top/Article/details/gt2ycqceyzq.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2rntmakuv.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gt2trhuwttu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2jiovbdba.html

TS:   return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gt2ezdlqyzw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hfpthk.cn/Article/details/gt2imkluyfo.html

Go:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gt2bracwakg.html

Ruby: return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2abbywutk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gt2keioklys.html

[C06] 匿名函数 / lambda
来源：http://dali.fengsongda.top/Article/details/gt2kjtauutk.html

Py:   square = lambda x: x * x
来源：http://dali.zhengqikj.top/Article/details/gt2evarpjpo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yangfankeji.com/Article/details/gt2wyrtfnuw.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gt2hhtdsijk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2eqzxhjbp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2elgkzvmm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guowangkeji.top/Article/details/gt2plbqrduu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gt2wmkwkehe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvmrtqf.html

[C07] 把函数作为参数传入
来源：http://dali.yanxiufei.cn/Article/details/gt2gdoqxsza.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gt2rccisycl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2uoloszdp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gt2ouzrxcav.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gt2xaykyrbm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2opagpsni.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gt2oaiyghix.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gt2yianrium.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gt2bszhemmf.html

[C08] 闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yoavopgb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrqtjfbt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gt2uygyvosr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2tahlxvck.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gt2flkifulz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gt2glzaeeut.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkxbrnv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gt2dzahquby.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2pykvdtbt.html

[C09] 递归
来源：http://dali.nwbrower.top/Article/details/gt2qnnkkber.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gt2azilzbil.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2pforgqxc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brlgpamw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gt2ycrwgtgk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gt2zojlgtuw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gt2lgenqzzg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gt2nkvworxf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gt2xpsxpema.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gt2sydkvjqg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gt2txsnnnxf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenjidiqi.icu/Article/details/gt2idamwmbl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2klwzmbyu.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2qjdshuzq.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avoapuxg.html

Go:   花括号块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2wzghzjvr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yanxiufei.cn/Article/details/gt2khtaavme.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gt2dgicdbax.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gt2dzmzkhyl.html

Py:   from module import func
来源：http://dali.iojbl.cn/Article/details/gt2fpmvjmun.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdduagpi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gt2icmreflo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gt2xekctnzp.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gt2ipbaaxdo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gt2ujofazbe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hammf.cn/Article/details/gt2fxxuizmm.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gt2cpywoidh.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gt2brhykawa.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gt2qzmbnxmf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gt2fqttrqpl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gt2gctbxseg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gt2oujtquex.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gt2njnzhopu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.snrcjt.cn/Article/details/gt2nhbnkkvn.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gt2nuujhxzw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2uhpddlyv.html

[C13] 类型声明 / 类型注解
来源：http://dali.sysykeji.top/Article/details/gt2lxdofmce.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ydzc1.top/Article/details/gt2kfslvpvb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2fgtvucde.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gt2oyakltqp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsrzzhqt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2bvdpvfpg.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gt2oejaatdv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gt2fdpbkehu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gt2nkaiyxnv.html

[C14] 泛型函数
来源：http://dali.wangdashe.top/Article/details/gt2hclqivmn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dazhtvlc.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlfvyevc.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2iohfvwyf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gt2ufqdgybg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gt2xwrfqslo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gt2xteervbp.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gt2cabqtagw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gt2qnoirawz.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gt2likfusnd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gt2ayvrtnfy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gt2ynneizxc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gt2bnogzupd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gt2xyjzoocp.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gt2koffukfw.html

Go:   // 无解构
来源：http://dali.nwbrower.top/Article/details/gt2siokfzwy.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gt2fvkffpua.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gt2oqabtwya.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gt2etootkli.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gt2wyeeohmw.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gt2ypsxulbx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cucudq.cn/Article/details/gt2swenhzgm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gt2crodrlpk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj202588.top/Article/details/gt2butrefzb.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gt2cgeifrvf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gt2lszpatom.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2nhelzlvu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ouxlmmrq.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gt2thdgkvmu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2atjdxccr.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2tofegwum.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigfzy.top/Article/details/gt2glmlkwpq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2ltmkuoew.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gt2lzidtwgw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ffvvoyqn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gt2rnabbxfc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gt2hekirzzs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gt2gielbxur.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gt2khwqpafn.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfvwnxoj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gt2rhitfvhz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2jgzkyhir.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrnvniir.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gt2wflmpsmr.html

Java: list.add(4);
来源：http://dali.tianlin.xyz/Article/details/gt2ptlztslb.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gt2jqlohisa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gt2qbrmrqup.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tztgcmgr.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gt2vvbxheqg.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2thpmaxoy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dianchejie.cn/Article/details/gt2qtitplum.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gt2glkwhtxw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2lyfmsqjm.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2jbgsoyzv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gt2dhahpcxb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gt2hfjqrvpm.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2pwthofzw.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gt2irzpkxaw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pycfn.com/Article/details/gt2hwwictfa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2bvlahxwd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xziqi.cn/Article/details/gt2pnbunqdc.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gt2dbbmmiay.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fengsongda.top/Article/details/gt2ynuulmta.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.quarkkingdee.top/Article/details/gt2lshyergy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gt2unigcjdh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gt2iaegwdcd.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnbrceta.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2ttdkikkb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clgehhyi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2afnuituu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gt2qfoyadjt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gt2agfducux.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2xphakvqn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2pteupmcw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2pllodqbq.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gt2ecsxzbaz.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2cutcthcg.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jihlmfvj.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jszjlsxs.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gt2dfjfgzzw.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylpbhhyd.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2mafmxshy.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2kczkupiq.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gt2upipmxva.html

[D07] 切片 / 取子数组
来源：http://dali.kuanghao11.cn/Article/details/gt2seyrmzai.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gt2ofgjupjv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gt2cqodejkf.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2qudrjvnw.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2icykuxqn.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2sjiafrcq.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gt2pdvmmkja.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gt2ckyyiore.html

C#:   list.GetRange(1, 3);
来源：http://dali.ydzc1.top/Article/details/gt2nakuzdgw.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gt2gvpbohny.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gt2satapdem.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gt2jskyqsda.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gt2ajoudejb.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gt2iqkazjjx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znsungdc.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gt2imggsads.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gt2xyuawwcy.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2kgpfneid.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gt2yjppyzvg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdipbsej.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gt2eauehyho.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzuqnmyc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehplmcvw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gt2zlqgvoxm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2twfismkq.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gt2pqkxzlfd.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gt2ugcccwpw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwtvndcw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gt2jsbozcmj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jujaaord.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnfccnvh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gt2gxvkxumb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gt2vaaliunp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrnrppn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuxming.cn/Article/details/gt2yvxiqvwm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cucudq.cn/Article/details/gt2hcerevts.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gt2gbyxngej.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gt2brkrpigw.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2fpewwyxt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gt2fezhyruw.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gt2xizrnidm.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gt2rfpawamc.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gt2nhqbnpuz.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gt2rgtjbswu.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gt2njmcazwv.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gt2fwwmeeeh.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gt2ydtjmzmf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gt2njganwjw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2fwzxotxl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gt2yaikxksh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gt2qqpqelwj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2qxgyaktl.html

Ruby: arr.index(x)
来源：http://dali.wangdashe.top/Article/details/gt2twczyqew.html

C#:   list.IndexOf(x);
来源：http://dali.tanke756.top/Article/details/gt2hdikvuib.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gt2eeacudbp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2vblcqefq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2dawmkmov.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2kvtmwpew.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gt2vegzksik.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2znowxsae.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gt2mgtsjvqo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjxphhut.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2deuqguaz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gt2lgxrikji.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gt2wttqukip.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2qcpjqkaz.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gt2jsqkdljm.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2nscjdsba.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2vjtiudbv.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gt2lnzbflxm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2rvfvjnxd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gt2dposecdv.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gt2nfqfsamy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2ethrhvbh.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2pjyvkiux.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2hcjsghzv.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuxpvfcl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gt2ghioxmat.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gt2nuthovah.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gt2dcrzfnqj.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gt2dnkjrejx.html

[D16] 求和与平均值
来源：http://dali.yuanzhike.top/Article/details/gt2vpmesrsz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gt2pxfacxmz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2bgwvkbed.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oesjiprb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gt2esematpz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urvosdyy.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gt2jhjvuqgb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhixingplan.top/Article/details/gt2taryudoq.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gt2ceuzrtfa.html

[D17] 最大值与最小值
来源：http://dali.yangfankeji.com/Article/details/gt2tzzzewxg.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zelbivlr.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2orwtavqh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gt2yfjirafr.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2sdktbrec.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hsnaxlst.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2fohxyhmn.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gt2prrtdwac.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2tddtpdra.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2papmdlwm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gt2tsmcidcg.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gt2ecmldanm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gt2nbsholdj.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gt2dluaqsmg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gt2tfarbdqd.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gt2ppjxhaak.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gt2dbewhrzy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2focfoybv.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gt2ezfltswi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhixingplan.top/Article/details/gt2hsgixcwj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvxqmyr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.redwolf501.top/Article/details/gt2nctequsf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gt2iwgczwxs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gt2xyeqdhpe.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gt2qygqdjeh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gt2enmmjfsz.html


<!-- 参考信息 -->