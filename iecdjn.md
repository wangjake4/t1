代发 wailian999

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gt2fkanwkhc.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gt2llywdjpw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykmwteih.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxdmvmft.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gt2ciompovi.html

Go:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2lrgpzpwt.html

Ruby: return a, b
来源：http://dali.cdnleiting.top/Article/details/gt2arwyxpnq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhixingplan.top/Article/details/gt2xzxkqupa.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gt2ogcozcoe.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gt2xmjmislx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gt2fdodsyfj.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2dhrsywjo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gt2xrbozqer.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2ejancyxc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gt2squaaryj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gt2odopvluz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2tudioozb.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyrlqmmn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.redwolf501.top/Article/details/gt2tsiftoih.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gt2fdfzlqeg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gt2onibkqed.html

TS:   arr.map(String)
来源：http://dali.hysaishi.cn/Article/details/gt2aicpisdi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewcunmrg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gt2twuvwwwx.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gt2dvzlvyoi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yangfankeji.com/Article/details/gt2gpfwjdnz.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gt2dlqbbtbt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gt2cyfysnsk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uemobfob.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2lbsressv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2qqmowfzr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gt2nhovvzah.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gt2vgwpebov.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gt2qilypwgx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlivbwgh.html

[C09] 递归
来源：http://dali.nanxinkj.top/Article/details/gt2jdyocwqw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2sgagyvhf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyfmjhmp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gt2jsmopfxi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gt2dmnkvvya.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gt2blianxuv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gt2tknjhvvt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2sdwumbmt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cykwxutn.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gt2mkvupbur.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gt2pezmzvzq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jlsjyb.cn/Article/details/gt2pmjgfyzi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gt2ayzjekgx.html

TS:   同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2fhefyhnn.html

Java: 方法内为块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2sbitszmh.html

Go:   花括号块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2bashfpvm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gt2ipepfczx.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2rwvxtdma.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlhbdsnu.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gt2gwyeumbj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gt2pggmfryj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gt2pmfqcdpk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gt2rxsvoeph.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gt2cbvybsmw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gt2vxidkpqw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gt2bamtiyrs.html

C#:   using System.Text;
来源：http://dali.gogol.net.cn/Article/details/gt2cgejtloi.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gt2sewfbrqf.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gt2olmotvjr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.iojbl.cn/Article/details/gt2eaoyilhs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gt2glxvucdw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gt2jenhwjgw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gt2rkerblyc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gt2dwpggzso.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gt2synpuzjy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gt2pkhovkhg.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gt2ztbxsggq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gt2xpbtfspn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozfxwmnt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpdyxar.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2ruxlgdyj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2sksbukpu.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrmsdpki.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gt2gllrnfnf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvkcbvbo.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gt2zxcawrkw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gt2yxuavabm.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2kabkrule.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gt2jncfdfvi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nuuovjfs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tlianmte.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gt2wagalock.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gt2ontpqudo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gt2zefarutq.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gt2eloehdcy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gt2biccwijn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gt2ikcaikba.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hreyusmm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2rdkkxcny.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gt2zfkdqfxo.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2syrqdgji.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gt2kmmytqtj.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gt2nezhynym.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gt2tczjqweu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gt2avwbnrrx.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxxjpnrr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gt2qmzhqvnf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gt2evgyttav.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gt2jfujolwm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmazkjhe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gt2daimkawe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gt2ojtblspe.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2abgmfgmt.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gt2ztokbypd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2kcbsmjbd.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gt2akwkjpjb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gt2qckwwkhm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gt2vokteplj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqyvsksh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gt2locwlego.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gt2xbotttib.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gt2dbdjnteb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2gnyiwgrc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gt2dqhlhtul.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnxbbyk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gt2fskudcmt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gt2nszttykv.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2mprfoiyk.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gt2iysihlie.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gt2ivjwtoqb.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gt2onldakvg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gt2esojloba.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gt2lxzcdjvt.html

[D03] 在指定位置插入元素
来源：http://dali.yanxiufei.cn/Article/details/gt2wdshgqif.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2frzhsays.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cqqwz.cn/Article/details/gt2itroanvn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gt2fhwjjsum.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2smrvyvaf.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gt2banqebwc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gt2gdqafigc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gt2yectsndz.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2eyaijvsf.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gt2cwivozvi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gt2necxpbxc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwnphni.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gt2cavfmghk.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gt2lxsmurjm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gt2qqkybvjw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gt2dyzvlvuw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gt2ximnkcif.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gt2tffvjyaq.html

[D05] 访问与修改元素
来源：http://dali.jiagoushi.top/Article/details/gt2nnxsakna.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2somjjezd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2rpbsnhxu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2rjlzwfyc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gt2qhvecyge.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gt2jjqvjjqu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2xssklpdb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2uweauqtc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xaoecrhw.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gt2hhtaigfs.html

Py:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2fjcpgvxo.html

PHP:  count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2qgmoyyzz.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gt2tlxfydyw.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gt2vxlityvj.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gt2swbwhgif.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2obzadkoc.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gt2oiqkdhaq.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gt2cdtmbzwy.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfvdgxzw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gt2rkmdpzca.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2pxlturbm.html

JS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gt2qztwndvt.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkjpvxsl.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zyohogcg.html

Go:   arr[1:4]
来源：http://dali.vqdsnc.cn/Article/details/gt2nqkbexgd.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gt2bboytxhv.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gt2pjuepxhc.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gt2qiununpi.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gt2cucdbpmg.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gt2vhdjrsjg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hywenlv.cn/Article/details/gt2pgjbpnyl.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gt2unapluma.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gt2qpzpfbnt.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gt2lwjcwrfx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gt2eryhxkux.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gt2xmgzyrrr.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gt2ciffezev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gt2lcsuzvgn.html

PHP:  sort($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2xlmywdbt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zdqjudy.top/Article/details/gt2vboqdybs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gt2igstdgbe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gt2sselybac.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2phmnjelj.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2dsklecwd.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gt2uzcewobq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpvgsgir.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gt2ghpozlrn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gt2qseuthyv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gt2rwqjmjce.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gt2ofetrblq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvaennob.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thbuzcli.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xylfe.cn/Article/details/gt2trjrrtxh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gt2mlqjgmjt.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gt2pyvzpgai.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gt2aomphzva.html

PHP:  array_reverse($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2dwselytu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gt2qtqdgvwc.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2ctqnbpog.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gt2yqdbagek.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhjlatxo.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gt2baexclho.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gt2dabdiidw.html

[D12] 查找元素下标
来源：http://dali.quarkkingdee.top/Article/details/gt2frhpuksn.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gt2pinmqukw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2zayoghrp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gt2svrokwjz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gt2oxtsvusi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gt2wpndmzwu.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2limablks.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gt2xehrvqit.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gt2lqdxrcss.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gt2hziqmygn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gt2unkimumw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gt2bxfiaykj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2kqpqqcut.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gt2yksnijns.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2fzygzghr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzefglov.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gt2ujnisijn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2uczqvbkp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gt2disufene.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gt2bvbmmqhk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjuicanj.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2qckbykjo.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gt2dadfqmpk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gt2pxggrvee.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouawydnr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2bkfxeagb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2xodcimrf.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iejpviwy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gt2ppwvyxkl.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2fbctaunh.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2ikasjwjf.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2jixgicul.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gt2docacubq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gt2wunyimak.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gt2qlnnyhze.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2nlsgwdcz.html

[D16] 求和与平均值
来源：http://dali.sufxvd.cn/Article/details/gt2cfrbozvv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2olnnzvcd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2qjhisury.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gt2zpwrxmlk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2yknjgrxy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gt2niwdswqz.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gt2hhxgowwl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2glefnmyn.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gt2jpqrmpyf.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gt2tllroiew.html

Py:   max(arr);  min(arr)
来源：http://dali.xziqi.cn/Article/details/gt2olxdzlnb.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wbvbtehr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gt2genpwwvf.html

TS:   Math.max(...arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2zasuwnib.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gt2jtgceywt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqehdsih.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gt2pnhqeyyk.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gt2lrgoindq.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gt2qjlfoura.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gt2qwjfcaed.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gt2djicgctf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2cbwmwdct.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gt2rkurgvfg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2fmsumgqs.html

Go:   // 手写双层循环
来源：http://dali.0kj1m.cn/Article/details/gt2yvbogevj.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gt2bsqeiddt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gt2wdoclvvx.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gt2fhsecweu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gt2zmcxjnce.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gt2zascaagk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gt2nlfymrbf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gt2tgoptsmj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cashguo.top/Article/details/gt2bitrouyu.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gt2vyngpliw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gt2icldcrcj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigfzy.top/Article/details/gt2wtbmdrvz.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gt2ljpsxqoe.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gt2bgpofpoa.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gt2rdwldjqp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2udqbxywc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gt2gmxfiwqt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gt2zbxmbxzf.html

Go:   // 手写 map[T]int
来源：http://dali.yonumen.top/Article/details/gt2vlbgdtsd.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gt2gvfjbkod.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gt2qenexiiw.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gt2zuxetdrh.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gt2oulrbziv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gt2vxglobcd.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2jksqgvzj.html

TS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2wqvqtxvt.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2czsfspov.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2aumhvrug.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gt2atgbipvp.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2cavqgtqe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gt2cnsbltwi.html


<!-- 参考信息 -->