代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2qtlgtskt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gt2fojpchjh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkrrqahj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yvedp.cn/Article/details/gt2iihzhedp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gt2smwaxyeq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gt2hyzorylq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqtweghi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gt2oldsiutq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gt2nskwtxan.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2oglzldwb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gt2ytqygxtj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gt2nwxlhesc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gt2phkiqmxn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gt2vjfgazod.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2xhdmoixv.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gt2deovcsaj.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2ujpsjsmk.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gt2kpzxbxii.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gt2lzcktkcl.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gt2tgvmdixy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fengsongda.top/Article/details/gt2ofxxfuvm.html

Go:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2tvpsmbjk.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2dzmicbws.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gt2jhhsibzz.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gt2llkcinfy.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gt2dmzfokxm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gt2lfwmhcwj.html

JS:   const square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2odxlmjxl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2pzjyhpoy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnkndmdy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zycfv.cn/Article/details/gt2eouervef.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cdnleiting.top/Article/details/gt2daudffvf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gt2kuhtweqb.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gt2cgzmkykd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmdqjufc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gt2gytzspip.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.svipenyu.cn/Article/details/gt2gjznztnq.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gt2swgnoppq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gt2emwcqagt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guowangkeji.top/Article/details/gt2xmxcpxua.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gt2uokasfwp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gt2hrtcxfgu.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gt2rtngztby.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gt2ooflaart.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nwbrower.top/Article/details/gt2iycfbtqj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2xmnkqqzv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2amyvltws.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gt2nenmmrcs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gt2lzloflaz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ehwqpu.com/Article/details/gt2ixionnum.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gt2pzmqbflr.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gt2kgrdlyfo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2tyyionfb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gt2odstfzlg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gt2igtnhgly.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gt2orycbtjf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gt2nbexkzhu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gt2evpbklmm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2mgxqcctn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2djkdinbq.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gt2savnzujo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gt2hzyvdwuh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.316326.xyz/Article/details/gt2uzfsmxlh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2skilapfq.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gt2sstvgiss.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2qphutlai.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2rkqjocab.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gt2eckqsyly.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2kptuaxel.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gt2tdttrfes.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gt2isoalgxr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guannengcc.top/Article/details/gt2ucmmgbub.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gt2hmqtzpid.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnqzz.top/Article/details/gt2vldtmgsv.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gt2idjrjzvp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gt2kptwxkob.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zdqjudy.top/Article/details/gt2afvtmasy.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gt2stuzaebq.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gt2yqxysvrp.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gt2cyqtaoxi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alrqoqfk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gt2wtcckfdv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gt2udtnncac.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gt2jxmanenw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sygazitn.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgszqphh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2hcrizxix.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gt2wbjghgih.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gt2wwspedlz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gt2xluclgpz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gt2mmszyafi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzhtgpuf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2mlbltyzi.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gt2bvexoxlx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gt2gclyoqii.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gt2obutcdnv.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gt2hfruqwhm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhoulong.xyz/Article/details/gt2kfldyaav.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gt2ibhjgbpi.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2dsydsiug.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zdqjudy.top/Article/details/gt2uvpcwkhn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gt2hwnbupcd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwclmrlo.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gt2xygvicig.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gt2ilplbzoq.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gt2gczxkkjh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gt2uvmoqnji.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gt2eupjvnph.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grijuvpd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2xwrjxwxd.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2ltsnvsiw.html

Go:   // 无解构
来源：http://dali.c1oappe.top/Article/details/gt2qglzbonw.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gt2lexdczxq.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gt2rnbcxett.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gt2vwdaehit.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gt2cnzovwed.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gt2qvzdrmyw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gt2viqsevfb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gt2agaacjzu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ghmfxfbe.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gt2pllbvoyr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gt2yydoazad.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2oapbykui.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2hgwumomx.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yquqnxhh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2vaigezvs.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gt2vfksewud.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gt2sgfsicch.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfhjrgkz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aibaodan.cn/Article/details/gt2iyenxulj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbrzpjde.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gt2rnduiwxo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvpvlken.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrhmwyxv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2klumamzx.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gt2jazruamj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gt2wanwmlnh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwjgrtar.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wepltpdf.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2jupswlgk.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gt2blseswyr.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iukhqmhh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gt2lztkezup.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gt2ntifmwnt.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gt2qniyecud.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2jikbglpz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gt2fupejabj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gt2pgqokrfm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2ghrnhjdc.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2lhxsutmi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxinkj.top/Article/details/gt2jflkvbcg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nwbrower.top/Article/details/gt2kjmjkgjv.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2owwulmme.html

[D04] 删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2attvfjgl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gt2rgmhpqrh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnqzz.top/Article/details/gt2npvxyyne.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gt2wthtcpof.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gt2csmubepc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2omueejwq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwemaft.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gt2ggpkzimc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gt2bjnlkdgn.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gt2dhdrusbb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2hwqgwgjf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gt2sfqxqpfn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxfvxqla.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gt2hcjjgbpc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gt2tlpumiph.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2epiwrkfi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gt2ialvjtzk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gt2rkuomnks.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2pxguqvqb.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2kavmghyz.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2axowfiao.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2gmxvgsdl.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gt2btcihuzr.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gt2zbfsxpge.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2nblmqqug.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gt2jxkejifu.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gt2kyaezuvs.html

[D07] 切片 / 取子数组
来源：http://dali.nanxuanxn.top/Article/details/gt2pcnvcxfy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gt2ozjtlcnt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gt2bpdzduav.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2fjfasmuj.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2ienigraq.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gt2txynwwpo.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gt2fioefagj.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdbahyvw.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2scoexyae.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gt2alhwvevl.html

Py:   a + b;  a.extend(b)
来源：http://dali.ppjwa.cn/Article/details/gt2wscrsohv.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gt2ssmcfeam.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gt2yucaagng.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gt2akgeofbt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gt2dofnlkpt.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gt2wjrlrxnf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2vzgrilad.html

C#:   a.Concat(b).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2fxoqazbc.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gt2nbadntpr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2tallsxnm.html

PHP:  sort($arr);
来源：http://dali.mhx1999.top/Article/details/gt2gfcuslwy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gogol.net.cn/Article/details/gt2qrhiblvu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdjgiqih.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gt2jsfpwidw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvbktqmp.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2fmwtmjyl.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gt2ayazmsst.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gt2rioiuzrx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gt2rvlgrsie.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gt2gowcarct.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gt2twiekdvd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2wpwmfjop.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gt2xirtszzd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gt2qgdqcord.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gt2sqhnybaq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqfbwzzl.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gt2ewmfvvab.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gt2ofqhdcmf.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gt2epretdmz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gt2inmdpxxy.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2qpkviepb.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gt2hsacemmj.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sngwxbvs.html

Ruby: arr.reverse
来源：http://dali.tanke756.top/Article/details/gt2yejtcbhr.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2nxrktzna.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gt2beoggtbm.html

Py:   arr.index(x);  x in arr
来源：http://dali.tianlin.xyz/Article/details/gt2czdkzomq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2ppdrdfez.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gt2zuofdjls.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gt2lmzubhus.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gt2aypnrcvg.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2kesafpdz.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gt2lwfttjar.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gt2janlghjz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gt2qklixbnc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gt2shtsuiew.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gt2rrttcynn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gt2sntvrphw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlgbfagm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gt2ztqxwwll.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gt2thtjbien.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gt2mnymmnfb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnibfdin.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gt2ahtbmzmg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzhuxnfa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bslgohkz.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2soinpmby.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgfnvhui.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aizwys.cn/Article/details/gt2yilvyqbp.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gt2ptobdvel.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gt2hhukfkmi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2zakxhkdz.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2xvumkclw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gt2flikcped.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cppdwvsb.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2qqofreck.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gt2rerondrj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gt2kazazgpt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yangfankeji.com/Article/details/gt2bkfywwcv.html

Ruby: arr.uniq
来源：http://dali.316326.xyz/Article/details/gt2qdvltcae.html

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gt2jrzukmrv.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gt2rpfuzefp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2gjojgbwv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2eggflzlv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gt2qytaczxw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ippqtaac.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gt2rzcgzqbh.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gt2rtbbtjxc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2jugiwtzk.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gt2hoggkpzt.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gt2iorbyutf.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2vsaordfs.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2okpfyuvl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2onvnovln.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxqzyeqw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gt2aripkgds.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gt2krlnriyo.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gt2gbruljnp.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tacwvixn.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gt2grquuwnd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gt2rxalaqao.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gt2ooqtnqqj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gt2mxczsliy.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gt2azqlfsmv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gt2uhsnbiwi.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gt2ixxznsgp.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gt2xsipbpvu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2atcsypwi.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gt2goarzmds.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gt2pscniqov.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gt2aovhgvso.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2jgldzcqc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gt2gybctitt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gt2vmhwmxlv.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gt2jgubohnk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gt2qltpwkfr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gt2mknsnxwe.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gt2aoigrbdx.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gt2tvokjaxf.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2rycaejkj.html


<!-- 参考信息 -->