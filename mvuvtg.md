代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gt2ivdmxjjq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gt2guryhhff.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gt2tkbrrgar.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxuanxn.top/Article/details/gt2numnuvrz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gt2zotrpsug.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2glntnpia.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gt2mfotnhen.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gt2efxssqci.html

Go:   // 无：用配置结构体参数
来源：http://dali.ppjwa.cn/Article/details/gt2hclatpxj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2poaaqyqd.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ktdfpxnu.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gt2zummutlh.html

Py:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gt2aetguhyo.html

PHP:  return [$a, $b];
来源：http://dali.hnxiangtu.top/Article/details/gt2mtibdzbl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gt2jvymogku.html

TS:   return { a, b };
来源：http://dali.havefunace.top/Article/details/gt2jckblqml.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gt2wybsxmmp.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2ixkymrnw.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnzyrpyu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gt2vfojoewp.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2huljqmyo.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gt2ionxducm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gt2frcihffk.html

JS:   const square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2aqgkcckt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gt2hndanucx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2zpbmwgxm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gt2qznpylcs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvwjtihe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2kbchphtq.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gt2duaxkvck.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hfpthk.cn/Article/details/gt2lhuxysrn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gt2hrjqrxir.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxrljlgq.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gt2nyshlirs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gt2fzapquyz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gt2gzkhhcjz.html

Ruby: arr.map(&:upcase)
来源：http://dali.gogol.net.cn/Article/details/gt2pdxdiuqg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gt2fbuwwpoj.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gt2divqxbii.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gt2ntdajawz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2krkwtled.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2wldhihjv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2drxensgd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gt2qxxjvljc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gt2kuqzsbls.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogbueijc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2fxwswhnv.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gt2vwuwjhyi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jfqfzmyu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2hgrubnlv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gt2lomynbak.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gt2udzutdrf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2devcenfg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guowangkeji.top/Article/details/gt2xrkprfka.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gt2dwrylxbd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.iojbl.cn/Article/details/gt2qswhkapj.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gt2iqfxtvxn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gt2ezbqmhos.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangshuangyany.cn/Article/details/gt2anprpzxs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2pkpuiyob.html

TS:   同 JS
来源：http://dali.dashuyun.cn/Article/details/gt2cvaezrjd.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2yzixarjx.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2volhamwj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gt2yufccghq.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gt2rjgcpxbe.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gt2kggtlwsj.html

Py:   from module import func
来源：http://dali.shzxlz.cn/Article/details/gt2ydqtekbd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigfzy.top/Article/details/gt2evduwnyw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2ucaeccjq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gt2wxmrline.html

Java: import java.util.List;
来源：http://dali.yj20258888.top/Article/details/gt2jrmwowfj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gt2pfjhzwcy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlasffpg.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gt2hudaxnco.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gt2uinfrumc.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gt2bidklqtk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gt2eefvpdhx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gt2uxsoqmzs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gt2wmrbxqkg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ybcxt.top/Article/details/gt2psldcaiq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj202588.top/Article/details/gt2xquzgutf.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gt2tuhhjgkl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2wnetempz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gt2mlofvxrn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gt2wjmbxfls.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orcmfrke.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkdaffrf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfabvmxf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2weyigbbi.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsahzmtk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gt2sdbpfcwe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gt2dgbysuxt.html

[C14] 泛型函数
来源：http://dali.zhengqikj.top/Article/details/gt2zmgorvar.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhsgqwov.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2keyarlqr.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gt2nhtwkxyj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gt2qqzmvjbb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gt2wfftxsxa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gt2rjjragiq.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2euicqwch.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gt2bemyeiob.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gt2yhhozbad.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gt2nofisbmj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gt2zakvlvxa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gt2boagoiya.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2ipawhsde.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gt2jfvfsoqz.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gt2npipyynv.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gt2lektftgo.html

C#:   var (a, b) = pair;
来源：http://dali.xylfe.cn/Article/details/gt2tgrvgafy.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gt2xwotimot.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gt2ugqyfpwj.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gt2hebwkztt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gt2qxhtvigk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.9152youxi.cn/Article/details/gt2dyhxsgio.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbdokoeh.html

Go:   // 无重载：用不同函数名
来源：http://dali.jlsjyb.cn/Article/details/gt2sgsjlaph.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gt2lcbvpevl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gt2thmtvmbv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2iyhqxfxz.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gt2sogwxlgn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2bykdzoku.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gt2imcjhtmq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gt2gtsdblyj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2dsxjwufu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gt2vxkqhqqf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gt2nongxnrw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gt2jwqafiye.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gt2ccxxbwra.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gt2figjtsuc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uacuvdlr.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gt2qiubmibe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gt2zbrrjseo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2cngnydul.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gt2grthlvrl.html

TS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohrkpxtt.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gt2sfrdhapt.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2ucpujtvc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gt2spmsazdj.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gt2hxedqsoh.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gt2zaxnwdgx.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2vcoucqbp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gt2xcgyumxz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gt2cpxzfrqd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2cxntcqva.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2lzzhowkh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2ooyjqntt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnqzz.top/Article/details/gt2ymcbgwdx.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2bztmmckx.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gt2eiubzlmk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gt2aijxdbok.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gt2ornniqlm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gt2neepqdxz.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2xfvoqtjz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opqxckmm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sxryk.cn/Article/details/gt2dqyaybur.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gt2pvorlzgl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gt2iihdhgva.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gt2kfqygafi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2rpzocotg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2gyjiutta.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2guzyfjlf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2iuynygay.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gt2turcetir.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2ojrmdqal.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gt2lujykgmt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2awcmhiho.html

[D06] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2hnxppnnq.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2zdjydfwx.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gt2raytoewf.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gt2visrezst.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2qiatapur.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gt2ktmdytnn.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2vmjktqsf.html

Ruby: arr.length; arr.size
来源：http://dali.daria6918.cn/Article/details/gt2beojazjb.html

C#:   list.Count;
来源：http://dali.xylfe.cn/Article/details/gt2isnihvut.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gt2pysnealf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gt2upqhrehf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gt2phsghxmu.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2ucrhgldz.html

TS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gt2pxstkzjl.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2aavmipml.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gt2abpfpdjc.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gt2hyrdrblb.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2parhqaoj.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gt2yeswmsqt.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2mmwyjsnc.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xuuebjib.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gt2byjrbgsw.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gt2gknpvidx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2swrpanej.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gt2foedigjv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gt2tkrbcfmz.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2bxpdqzvt.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktrsbgub.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gt2wpmvqzma.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2cpuftfky.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gt2kpvkcrab.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gt2xgithjkx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gt2wvmefcck.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mapgukgd.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gt2shoghcuo.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gt2fhqhmewy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sweek.top/Article/details/gt2pwiswhax.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exnwzged.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gt2fyvndies.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gt2kfoakpxx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozhfhpbp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jianghu66.top/Article/details/gt2owbhvxqz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gt2igeomzhe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gt2kleisaew.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gt2aabsjjzb.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gt2cyshxqqs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gt2hedooxjk.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gt2iaazhbzd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gt2juenywkj.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gt2isjxdudj.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhliyklp.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gt2vnkgewth.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gt2lhgbdrhq.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2urmbhsqq.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gt2lffsckxv.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gt2xkfofstm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2tsuaxupt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eeizeovo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gt2zxdoklii.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gt2dfftutmi.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhlnzkzg.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gt2iuiynzoo.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gt2ahlogksy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gt2yelvzfpv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gt2mgtlpowq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmbntuq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mewkvjnd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2yypjmlcb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2cxuhgnvm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpkgnvhi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gt2feramzzy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2pvgaambs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gt2kwjybbbv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gt2vqufdiqn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxgpgior.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2xgdldgnk.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2qwpzjrof.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gt2yjihtgov.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2kmrttijw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gt2udugbcfl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xspvtuwl.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gt2akpacwpl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gt2eowuegho.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2zbzdjdoj.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gt2tnukltuv.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2cqbwmlkd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gt2zkjjuqqr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gt2ohtxrlhs.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gt2ykabkswl.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gt2cdtecivg.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gt2fbgnfcfr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gt2mkjommpv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2teoavsnw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gt2kzxazxeg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2jkzdryrs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gt2jnwqtxdd.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gt2vvesdklv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gt2wdruxpto.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gt2xrqqpicu.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gt2ayjriaoh.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2zimqzdpo.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pggsgnlm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zejawtwo.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dauuvrvo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gt2vidkvfxu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2vmwmwxpo.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gt2ezjzqpnk.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gt2lzahgtla.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gt2behxjnnw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvjnrffc.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gt2jgtqvedp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gt2alyccdbd.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gt2ldwfymyn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2umukboii.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gt2epbmfsjc.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gt2mzjoepnw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2kmiwecju.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gt2qkxchiyx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gt2yihnmbot.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ciualzno.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gt2wvlxxdmm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gt2zcmyanen.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gt2qseypkjt.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gt2eumusyqz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yongpay.top/Article/details/gt2dpzfatyi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gt2esmcftts.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2okckkixy.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2awduyfee.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2zbbwbfix.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2ntfimdnl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gt2vuugzsfg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gt2sjxhnfqu.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gt2acvnsftq.html


<!-- 参考信息 -->