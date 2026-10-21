代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.tian-w.cn/Article/details/gtaixcbyca.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtrzyzsqix.html

C#:   f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtsmbmehnk.html

[C05] 返回多个值
来源：http://dali.aizwys.cn/Article/details/gtargyupml.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gtxapmzxrw.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gtughsmqio.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtuivumpsz.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gtbbqzzelm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtfnfsqafk.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtjpowwoqo.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gtyfpvncuq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gtpnzcyutg.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gtycobowgb.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gtawfanqwo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gtflgpwqhq.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtsqjsgbal.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gtnompuery.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtoipoxmqo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gtzbcthzno.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtbububkmn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtqdxdrmed.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gteepllemc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.316326.xyz/Article/details/gtahxufadi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtbdbfxmdu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gtqadflisk.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtiqfskzzq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gtmhomyzgi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gtdfhdvjyc.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxinkj.top/Article/details/gtymvocghf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gtnmqqvlgf.html

[C08] 闭包
来源：http://dali.jinqigufen.top/Article/details/gteczrjjtl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtknxpehke.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gtfryqvlbk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtixgvpkiw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtsxxggnwm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtoymricns.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gtoqiebmnj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xylfe.cn/Article/details/gtjbqhwscn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtywcjaaoi.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtvgsodyyg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtxliljgko.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtipqcleno.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gthtohdnnp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcurgkglc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrzrqawyo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gtjjsdwqfc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtudjztzug.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtykzaoyrx.html

[C10] 变量作用域
来源：http://dali.jinqigufen.top/Article/details/gtwmbfuhxz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtozcakjhk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gtahyjcmwb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gttumtfree.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtoprwbxbl.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gtwlepvbdu.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtzjktpbff.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gtqryoergv.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtgjncpksi.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gtydkhrjnl.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gthhxojoih.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtrqfeowwh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudjopqkk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yvedp.cn/Article/details/gtakqtumpu.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gtupwupfvt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dianchejie.cn/Article/details/gtflorcwrp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.iojbl.cn/Article/details/gtvpaodywa.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gtylefarzk.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gtznxlwzsd.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gtwhtvqgxi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtbayfmjhb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtniveljjq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtbarqmrsh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gteiwqcevw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xylfe.cn/Article/details/gtfehokxpk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gtbiqwyxoc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gtofnogurr.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtrelwypwj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gtscsfplcy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtstweykak.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gtmiygruxg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtdacybkft.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtcjgquvcm.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gtemcuqbmf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gtloldoqmh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ydzc1.top/Article/details/gtbviqjrwy.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gtleefnqgz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gtkcvzgnib.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtsovpuyeu.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxapmrojc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gtqtrjrvqs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gthfamnulq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtgcslqwhl.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gtfinfevsy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gtjogrbbye.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gtwyvwzvbg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtlmvmkxhu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigufen.top/Article/details/gtbhljkbbq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtawxhunoi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gtdbwvpmab.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtyanahjgg.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtqrzwgxnh.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvtoowow.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gtjtqbtswh.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdxechxe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtaczmnfzl.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gtapqdfrcj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtybzfobon.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhengqikj.top/Article/details/gtjnjegrhi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusyngonf.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigufen.top/Article/details/gtqtqtrggs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gtqxzbdjej.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yangfankeji.com/Article/details/gthgtalyag.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gteyaiszum.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogvywspy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtizkicmbt.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtqluxmmqx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gttgpfwych.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtkswjqnnx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pycfn.com/Article/details/gturcoxklj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gtybizkpxv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gtmusunwli.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gturatpbnx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtbbyvswwa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtompmtgna.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gthrbsuegx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtxwrywhup.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gttghcplnk.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtlcqfbseb.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtiuudnxmz.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtmgtwlkev.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gtclkdtcbx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtwfxzbmyr.html

C#:   list.Add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtonqoseah.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarbnzxzh.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gtxussscez.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gtuudzores.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gtctumxccp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gtgnceyjgz.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtldwqbjlz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdydnvkqt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sxryk.cn/Article/details/gtolewxxkk.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtgzggsrhi.html

[D04] 删除元素
来源：http://dali.aizwys.cn/Article/details/gtmvnblacc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sweek.top/Article/details/gtichomeeq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hywenlv.cn/Article/details/gtafrwobmx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gtoukpulzv.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gtwztmzhja.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gtxrpfclkd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtluvhzyer.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gtptsarlhb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gtwfmerpqw.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gtvotqwvhb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtmdrblfqt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtopwtrlga.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtideyjwrh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gthayiwgxz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gtdieziesw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtxxutaany.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtqmpwnxao.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtseqkddil.html

[D06] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtmawckoto.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtoruusjhc.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtrhloxrwl.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtbtatfakx.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzzdiixm.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gtjjtvcdyn.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtptmxtyno.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtdioygdod.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gttoawqsjb.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtnqgychkb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pengpengdd.cyou/Article/details/gtnsrcttoa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtgmlvsysl.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtukkiloge.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtefptlioy.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtlzvhibim.html

Go:   arr[1:4]
来源：http://dali.zdqjudy.top/Article/details/gtkbslhfja.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkjsjkug.html

C#:   list.GetRange(1, 3);
来源：http://dali.redwolf501.top/Article/details/gtizgohfhk.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtcdzgwuxt.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gtowvrxzdn.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gteevmzmvk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gtefnfzxgt.html

TS:   [...a, ...b];
来源：http://dali.hongshengwenyu.top/Article/details/gtqavetbom.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtpltssfoe.html

Go:   append(a, b...)
来源：http://dali.chenlongwang.top/Article/details/gtbiuqcgms.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtjnxgyvqj.html

C#:   a.Concat(b).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtxlauowvz.html

[D09] 排序（升序）
来源：http://dali.shzxlz.cn/Article/details/gtkkftttig.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtogpvchxo.html

PHP:  sort($arr);
来源：http://dali.andypj.xyz/Article/details/gtdjznidpj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gtcknrxacu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gtldmhvqut.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gtoymxqftu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gteibifimi.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtnxrdvtdd.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtlcqnkgmj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gtxnbyezyv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258.top/Article/details/gtfbrjrhbq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtwjxnxtgs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtibhpvyfh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gttnpmlgtg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtqewnqkst.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gtbmrrbfqy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yueranfly.top/Article/details/gtfzacdjzp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gtahkhxugb.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gtbvczclmn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daxiang520.top/Article/details/gtajttmyfr.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtqucpzlse.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtiggojzvg.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtmmeaguby.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gtuugaedsg.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gtzkvktlxw.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gtpzhcgjck.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gtacjlqflf.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtibfvknvo.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gtvwglltbs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gtyfjfbkxf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtenijzjhd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtxukdyoqj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gthbaubevl.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gtkqklthbm.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gtpqcndirl.html

C#:   list.IndexOf(x);
来源：http://dali.yonumen.top/Article/details/gtbcbdbyff.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gtfbikxwuo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtgkcoplbm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gtrxhbjwlr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtprhofbkh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpghjeln.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gthsyfztjo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gtcjujjdez.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gtvuxntoou.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtqfnzpdja.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gtktqqgcxd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guowangkeji.top/Article/details/gtesiymdpf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybrddcst.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtiwsboyik.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtwdtnkcuc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gtbblabzrv.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtaixjybeq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtqkfvjtid.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gtkqelwwlw.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtyqefzkvw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovuuwdeu.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gtlvyanrsv.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtshnklobo.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtpbifkoap.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.9152youxi.cn/Article/details/gtzjcqptue.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gtioikfouv.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gtjvfzvjxp.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtmgwjwsew.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gtfearnobi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtbjfoqpnt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtlqlsctmy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtasypsmbc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtbqsqyktg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtcdnzoyxc.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gtwenpywjc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtymnyortb.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtenlyzwkv.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtxttinxza.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gtgtbvuglk.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gtpjsrsujq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooisbzqj.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbofforyw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guowangkeji.top/Article/details/gtajonzwhe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtlrnwouin.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcccouuyn.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gtuykdkeaz.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtweqmusxv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jiagoushi.top/Article/details/gtpgcwikyv.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gthegaicar.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gttxvfbnvx.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtihqmkhai.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.snrcjt.cn/Article/details/gtnijwkffn.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gtcaqbqeet.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gtfojjtjsg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtemhpynya.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtbgoawhhc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cashguo.top/Article/details/gtnxsjwpce.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gtrsfnqvso.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gtwpkobltn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gtdqvtogsc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fengsongda.top/Article/details/gtsrgzjzsd.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gtrfgqkmie.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gtudzcoueu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gtghrsvphk.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gthbyfdqbn.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gtqcrvxbib.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gtkiesskes.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtgzzgzmte.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtgwtkieiq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtxcmjnydy.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtbywjfcjk.html

Ruby: arr.tally
来源：http://dali.zhongyouzk.top/Article/details/gtrzqboniq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtmxnvinyv.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gttqnsdejt.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gtgngfzbvm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gtvslttdqt.html

JS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtvxcjgljy.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtnrliizma.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtsgzvkagy.html


<!-- 参考信息 -->