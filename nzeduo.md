代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gt2bbewtbux.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2bzuekqqz.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gt2jifqykiq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gt2sedsfhgy.html

[C06] 匿名函数 / lambda
来源：http://dali.hnqzz.top/Article/details/gt2vbqsutyj.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfcrozso.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gt2nsqdpsre.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2gqhntfrr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuizckrt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hirmdpsl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gt2lhabfodn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gt2zkqjuctq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2hsgymswo.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gt2mxmbxhdg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gt2upfvwypa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2carszbgv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gt2xxztxaws.html

TS:   arr.map(String)
来源：http://dali.yvedp.cn/Article/details/gt2czokophv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daxiang520.top/Article/details/gt2jcroncqk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yonumen.top/Article/details/gt2fhewvzjj.html

Ruby: arr.map(&:upcase)
来源：http://dali.snrcjt.cn/Article/details/gt2nwrspgdi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxgblpgz.html

[C08] 闭包
来源：http://dali.c1oappe.top/Article/details/gt2beyxtuie.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gt2udtjmgyd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gt2jgvwuvmt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gt2xhewvquo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2xijdhsfh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwalhdhw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uevqpacg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gt2lqxeovvw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2ssvwgfvl.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gt2czhsysqd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2bjiitkfe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gt2lvuxudfd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gt2gqgtgmzb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2jzrfngwe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gt2ohtbwwmq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gt2uumycttb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovzfgslc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gt2vmlcfnes.html

[C10] 变量作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2skufonum.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gt2tfikonai.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxinkj.top/Article/details/gt2unbdetvx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2jbkitwej.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2hpjxzcpl.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzwxoelk.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2zicgyjmg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gt2mwnzpaoo.html

C#:   块级作用域
来源：http://dali.zycfv.cn/Article/details/gt2bnqvmoxc.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gt2orrbdfqb.html

Py:   from module import func
来源：http://dali.nanxinkj.top/Article/details/gt2qztrmwjh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shangyingyoupin.top/Article/details/gt2frxzjdca.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yonumen.top/Article/details/gt2bpkfiwju.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gt2zraacuns.html

Java: import java.util.List;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjtoyrna.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gt2ozrrowjl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfymmwxk.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gt2dbniovre.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gt2apzbyhta.html

Py:   (lambda: print("run"))()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qeqohcve.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gt2qjkieiwk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gt2exnliixi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gt2hahuctzf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gt2sicrmrqr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gt2ubuthlcf.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsgfckko.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2efymabid.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gt2nmawemvr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gt2mdaqakxn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2znlmqefs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gt2yeclwmnn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iovhcelp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rmvyhipj.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcwwffga.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gt2isqschqg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xziqi.cn/Article/details/gt2rzmwogcm.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gt2loiagpal.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqnachp.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2pzxrcgdu.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2ovfjraaf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gt2dgjggqma.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gt2gqsgpfjs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gt2ynszqvhs.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gt2fcdmkcvf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gt2udiuvfgo.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gt2uvtgoewi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gt2ewwlqgrr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gt2xsgihbcy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2uiqaauml.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gt2lfgmhzwl.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gt2lxgggngr.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gt2kjzcxrpo.html

Ruby: a, b = pair
来源：http://dali.dashuyun.cn/Article/details/gt2pjqmibdh.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbikwwlq.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gt2hajdsctu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gt2gvykytfi.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gt2mdxweecn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gt2ldacttel.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guannengcc.top/Article/details/gt2mwmtxbim.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2jyqgjflq.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gt2lgrgnvvf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gt2kwzhnfzo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqilkwey.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2bjjwzrob.html

D. 数组 / 列表 / 集合
来源：http://dali.smart0.xyz/Article/details/gt2nunzrpno.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mpthaeji.html

[D01] 创建数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gt2soiqeqfn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pycfn.com/Article/details/gt2apxuyayc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2afehuieh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gt2mylgjwlm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gt2glmafijz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gt2evyxqecr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gt2hzkcavsc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gt2xzorxace.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gt2ipfualkp.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gt2ybnleivs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gt2msaifosa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2ghvvoylx.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yplofvmf.html

TS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gt2vbjrkpua.html

Java: list.add(4);
来源：http://dali.shzxlz.cn/Article/details/gt2ocwsikoj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2nocpcmzr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2unqckcxq.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gt2pheokugq.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gt2empfwdat.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2zcwxnhpm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imocbjvq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gt2grhgujzl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gt2bnwdzysc.html

Java: list.add(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2jsgdoabu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gt2lqcmehgt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gt2dyfjsbrs.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gt2qyuzwlnt.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gt2vqtuavgv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xziqi.cn/Article/details/gt2cgqfhhab.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gt2hqcistpr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gt2riojshum.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gt2cfqpghnt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.9152youxi.cn/Article/details/gt2kmdgvwta.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gt2actwkbjf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gt2oxmxgmlm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gt2utqnkeqj.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gt2dqvtojwp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2kbugaskk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2hoiuuaxr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2emaaeoqc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gt2susbdjeu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gt2qhdyznhd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2vikdgmbc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2ppsecsbz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gt2vjrbbcaz.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2zrfuawer.html

Py:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2tlorremt.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gt2lnbsratr.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gt2uutctxtd.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2moracwjf.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gt2edyejryj.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2jtjstruh.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gt2xcjtuodu.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gt2unzsaybr.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gt2wcmmjbvm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gt2iaijsdvb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gt2zsjuzwaz.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2invkdivg.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2ytuimzur.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2zkdytaib.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gt2pecpflmr.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gt2lobchozr.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2ucllngtp.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gt2llcakdcx.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2yrkqzoev.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gt2efjxjywi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shuidangran.top/Article/details/gt2wjhwdqct.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gt2sjevapjc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2hpllixir.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gt2norgjlpt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gt2xolhoolv.html

C#:   a.Concat(b).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2zhlqbxgd.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gt2oxsjikxe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gt2zxcmqufm.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gt2dynxufvi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvehyeuk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnvorulk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gt2thpoctxc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2lsfyepjr.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gt2ymidttmu.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gt2xqclheup.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gt2vlkocofz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gt2nuwtgnzo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gt2vbezyfnx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gt2ijydbwml.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pajvhbxf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gt2mzmeixak.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gt2umclyjai.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gt2qqifprrl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gt2tmqeonds.html

[D11] 反转数组
来源：http://dali.jlsjyb.cn/Article/details/gt2yyuawswb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gt2naznkszw.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2nzjziuwj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.iojbl.cn/Article/details/gt2nxgqcnld.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gt2rluaqdsm.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gt2kjxphukl.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2ayuvhrur.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gt2aligrvxv.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gt2edmlsyfb.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gt2qynuosyj.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gt2rmexwjhw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2sneauzuz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gt2qrtrekrv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2bqzxfdcg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gt2hyhbiclb.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2mykwyiho.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gt2ibkwohuk.html

C#:   list.IndexOf(x);
来源：http://dali.316326.xyz/Article/details/gt2grduudul.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gt2cxbyliqk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2mladrubw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gt2ygdornlj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2fenuodmh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gt2erstyvep.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gt2mfvrbima.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gt2cfwzqavm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gt2mmktvcog.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2lfqnrvlw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gt2vxcyowmn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2vxgrlmry.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gt2cswxatuh.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zefviyxx.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzcwsgqc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvovbzry.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2anzkhaqz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2rludxdht.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2nndnxsuf.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gt2qweyxhct.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2cqbhsftz.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrwiuiet.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gt2fknjpvpm.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2orbwrzcj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gt2zbrsddmw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhoulong.xyz/Article/details/gt2wwgnuuuf.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gt2ndbuxnzk.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzkyrczf.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gt2argasbee.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2wemofcfg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2aylfdluo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2axtrwunc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2btasbqcp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gt2obwtwyow.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gt2qzsjqpum.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvkzzxrj.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj202588.top/Article/details/gt2pwswryen.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gt2azptkbvx.html

Py:   max(arr);  min(arr)
来源：http://dali.yvedp.cn/Article/details/gt2ewlqhzgu.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2cwwsjblr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2ffoxsnhx.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gt2oeqodhoi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.iojbl.cn/Article/details/gt2emettpho.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2ynunnevu.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gt2ypmgbfyc.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gt2qtgxdabp.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2gdysrfyn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gt2gkdargqc.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gt2qlcbjidf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jahkwarp.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gt2clubfnci.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gt2yqocdgxe.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gt2jzgysgxd.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gt2lzpzasbf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2nygadjmo.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2voquokyq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gt2rjbwmhce.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gt2mmewtgmq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gt2fgcbqofl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gt2dwptyncy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gt2zamzxnqo.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldapxhmm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gt2zlryaecj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gt2rpictucs.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2jgbicqlj.html

Py:   Counter(arr)
来源：http://dali.cucudq.cn/Article/details/gt2optvctec.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2qdjyxgxm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gt2osizvrsa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gt2schcvdgu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gt2wokdcepy.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gt2tsginurh.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gt2faivteva.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzbnvgla.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gt2jmbujgil.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gt2dikuungp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gt2htbfshtz.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2vuxyqycs.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xofzivki.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qaqtiuun.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnditrxh.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkqqryxn.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2guhlrguc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gt2bgmhqjub.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdkwatrc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gt2ncsngyme.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2dfhtaoyj.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdojwokb.html


<!-- 参考信息 -->