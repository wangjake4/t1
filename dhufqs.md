代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gt2vzdwyexn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gt2psfvhzgp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuanzhike.top/Article/details/gt2nqlaqjea.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gt2dewjtisu.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2offzlqed.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2zqwtrtue.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2jcvvzqsa.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gt2dgnssayl.html

Py:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dszthbsm.html

PHP:  return [$a, $b];
来源：http://dali.yuxming.cn/Article/details/gt2hjlsibhq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2rtijcyyl.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gt2gyloepcy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gt2yonrjvyq.html

Go:   return a, b
来源：http://dali.yvedp.cn/Article/details/gt2eeodllza.html

Ruby: return a, b
来源：http://dali.9152youxi.cn/Article/details/gt2rjcchcdq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gt2ljulvdez.html

[C06] 匿名函数 / lambda
来源：http://dali.aizwys.cn/Article/details/gt2fxumwxvp.html

Py:   square = lambda x: x * x
来源：http://dali.jqgfzy.top/Article/details/gt2iqtestjk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gt2rsnfnzhq.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2xcjwjotn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2atrovzpz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gt2mthghyss.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ehwqpu.com/Article/details/gt2selyyprz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gt2nvayceti.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwoqykyb.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gt2icndbwje.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gt2sekzogkg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2enayqagl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gt2vekmkjdx.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gt2mseyreow.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2padgvecv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gt2igppghap.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gt2vjwzjoyg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gt2egebqfet.html

[C08] 闭包
来源：http://dali.yanxiufei.cn/Article/details/gt2xihtqqzf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxuanxn.top/Article/details/gt2dngfdksm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.c1oappe.top/Article/details/gt2awmjtxdm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2aiehjqlf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2pyffclje.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhixingplan.top/Article/details/gt2sorrvwqe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gt2rtaugdcy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2mppnqalj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2fcqolijc.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gt2jfujiuzw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gt2bjnzyyio.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2nsiwvjki.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gt2kxpxnncq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gt2epkylxid.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gt2jjwujyap.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gt2imwhfkgz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqnztbzd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gt2atesyupe.html

[C10] 变量作用域
来源：http://dali.tian-w.cn/Article/details/gt2pioekxmt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhixingplan.top/Article/details/gt2tferqmkf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gt2qptzhuml.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gt2iboauion.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gt2kagbhyfq.html

Java: 方法内为块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2yqavxyxa.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2wcnivctr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gt2qelqweji.html

C#:   块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2tiapofsi.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfoitge.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njjybnnx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gt2nfyusdol.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.birdmap.top/Article/details/gt2ptndsjil.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.birdmap.top/Article/details/gt2wxkrwymd.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gt2gchdvepy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gt2enmifptv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gt2smbbitnt.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vuhhfibi.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gt2jhftksme.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gt2rdzbxkks.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gotoacloud.top/Article/details/gt2uqlcizhw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gt2rznckndd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gt2ccvkdgho.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gt2odekwdrg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gt2lumixude.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gt2czgpwsoj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2fiehuncj.html

[C13] 类型声明 / 类型注解
来源：http://dali.tian-w.cn/Article/details/gt2grejcfvn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2esszehwa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdnjdkuy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqqwaqms.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2hkbessik.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2usoettvr.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gt2zzoctrpk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gt2xdbqcgmw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shuidangran.top/Article/details/gt2jxosiuhh.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gt2lprzbmhp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gt2lmdgwihv.html

PHP:  // 无泛型
来源：http://dali.sweek.top/Article/details/gt2ulrpwrqx.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2wcrcdvxc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gt2lilfifia.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzyvseqe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gt2lfqubhtr.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmyqjovd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2piypkrtb.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gt2kudsbtpt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gt2nhcrukfz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gt2ayqkissc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqaxupfh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gt2nonhciae.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2tvcplogv.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2wrrhpopb.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gt2weeqyduy.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2cvttrrfy.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gt2cektbube.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gt2peeezajz.html

PHP:  // 无重载
来源：http://dali.smart0.xyz/Article/details/gt2qhuhauge.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qshqvscd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gt2huvpotwv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2wclbztcg.html

Go:   // 无重载：用不同函数名
来源：http://dali.iojbl.cn/Article/details/gt2hysxhhqu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gt2avqjlpdh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gt2vecdmjax.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2yzuucgzk.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gt2bkqqxoow.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2quuitxkj.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gt2yjwhwsgw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gt2npshljvo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cqqwz.cn/Article/details/gt2lkasbueo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gt2fqhhyzma.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gt2xkkdscmy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gt2yczgzsrx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gt2wsqqavlg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2bjkedwjd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifpnxckz.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2diaynxzm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.9152youxi.cn/Article/details/gt2fevzcpuc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2hrfanadg.html

JS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gt2odbxdpgy.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2gmrnsaaf.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gt2ncqggvpo.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gt2ughzrfjd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cdnleiting.top/Article/details/gt2dqacfxir.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gt2kiflsotf.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gt2laedepgc.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2vrrgzxmj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gt2juuxtrkx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gt2lfvujykk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2qphojwaf.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdohmkko.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpbcgutl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gt2xjfytolp.html

C#:   list.Insert(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2zhypiiml.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2jlzxcltl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gt2zwdqcjvq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gt2lzcnkkqy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gt2tbyzsdly.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjdjtckv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gt2dzyimtxv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gt2wztveeny.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pjcirygl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvlofwuk.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjmgwkxm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2rcdjuzif.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2ztocrixg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2ncfilepe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gt2fmbppjrq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gt2bczuuktw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2cedmtpzk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2zhfoaprz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2ddndjxxm.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gt2dqlnwesj.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jycqomua.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2hlofxsge.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gt2zncmkivh.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gt2xbjgmxeh.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gt2ynbcuexq.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2xxzjtxif.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gt2iwafxwwi.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gt2hcehytdo.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gt2vnfafuwv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gt2cbblzslc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2nzmwtqel.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2xqfeapyv.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwfzygsa.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2wpzizsfq.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gt2yjoogwdi.html

Ruby: arr[1, 3]
来源：http://dali.gzhubu.top/Article/details/gt2foeaxkuw.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gt2xvysbsed.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gt2ulmvndyg.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gt2kpnsyied.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywjdsqkh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gt2zbynmntb.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkvbcxbl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gt2abmruzsm.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gt2aogysdye.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gt2lrcbaqqh.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2yntjicnd.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gt2akenqlnr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2syreatnw.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2flkkldah.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gt2ljkpnpxh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gt2mulgiwal.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gt2hvsymfqs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzcmgnpz.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2wifdajda.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gt2kdzkehzf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gt2ibvrfjmu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenlongwang.top/Article/details/gt2jikwvryc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gt2xofsqhjg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gt2nlylifuh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gt2irpedcuj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gt2fhyqwjtf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnrcafsu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gt2srvsyzge.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hfpthk.cn/Article/details/gt2diokbphr.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gt2mebaolch.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gt2ybuywpst.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gt2cxsqixgm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gt2puvatoej.html

TS:   [...arr].reverse();
来源：http://dali.jiagoushi.top/Article/details/gt2kynnuwfw.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gt2vlwzpoiz.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gt2stgirhgn.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gt2zednmesc.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gt2lljfhlzr.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gt2jlpzaehz.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gt2jcuamlva.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2lunkzmxv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qawaecig.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gt2ourzpron.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gt2rfmvutzz.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2fdtzrkph.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2vbzuhgqn.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gt2tnldefzh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.bjfxy.top/Article/details/gt2tsassnhc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2caohnjgo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwyomamd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdzvqdtg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2rzdkpvsd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2akpiroqb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gt2lflrvwnu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unndwmnn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2yjgmokwr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvetmzts.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gt2zpxldyvl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2kikbeygk.html

JS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2uccxihod.html

TS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2ifinijlz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdjvisax.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gt2ocmxunzj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gt2kkuqfsvb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2enseuwbh.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gt2fphqnlxy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gt2jzjcnxhq.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2bagfwywq.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjkntzm.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2uzyjwuan.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gt2qsllajmj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gt2viadzqir.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gt2kopukgcp.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2mlpiunra.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gt2irinwdvc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2nkkvjvdm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2fupsaajx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2homajwyt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gt2aexdldvy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gt2tfgxwbri.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gt2rpcnchmz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nwbrower.top/Article/details/gt2awkjmqnt.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gt2vxonwemb.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gt2dwhgvtav.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2oqzdjrhd.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gt2ltcnmmvt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gt2gbiwsqdg.html

TS:   Math.max(...arr);
来源：http://dali.meibo888.top/Article/details/gt2xnjurkjj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenzaomai.com/Article/details/gt2rvnnacef.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unzwisqs.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gt2napowhbm.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gt2voekxtue.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gt2sgpzmcaq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gt2mreeexwi.html

PHP:  array_merge(...$nested);
来源：http://dali.haohaochexian.top/Article/details/gt2bsfpngbc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gt2nzptdtxa.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gt2xewswqut.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gt2dzrsyssq.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gt2cnrwgpvm.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gt2vvfvqolr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bctfzkln.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfhkmdpu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fyynrytm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yvedp.cn/Article/details/gt2guurriys.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gt2lcbyexyv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avxcbwqz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aizwys.cn/Article/details/gt2besavkab.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gt2vhsbcuaw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gt2tmcvqslr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gt2dmpnrxfe.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gt2jdgpaafy.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gt2yuzarzjm.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gt2vydgzjxd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2dszwlifl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gt2jrryihpe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gt2kuazarbc.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gt2zzzazrno.html

Ruby: arr.tally
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haytjnpz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gt2ntsouutg.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gt2gmkyrtmg.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gt2lkhnkbmc.html


<!-- 参考信息 -->