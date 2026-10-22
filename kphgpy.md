代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecyuytgc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gt2wzfdithb.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gt2jhurkgvs.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gt2azlzmxhh.html

Py:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyzyqylt.html

PHP:  return [$a, $b];
来源：http://dali.fengsongda.top/Article/details/gt2aajcxdyf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.mhx1999.top/Article/details/gt2bntiyqsy.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2blwflbrz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nwbrower.top/Article/details/gt2ucbbntwg.html

Go:   return a, b
来源：http://dali.cucudq.cn/Article/details/gt2lywwspqj.html

Ruby: return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2hewgskgh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upyszqyd.html

[C06] 匿名函数 / lambda
来源：http://dali.zhongyouzk.top/Article/details/gt2lvdwmgcz.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gt2hbfqnnll.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gt2guhaaohn.html

JS:   const square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mklnhiox.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2mijvxqnc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gt2asjrjoyw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gt2sfuckgnq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gt2mplgdlot.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbehzwdn.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gt2zctkehqu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eunkrpzv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gt2mbxkgodu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gt2wqljikcd.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gt2zpaehncs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2prfwanep.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jianghu66.top/Article/details/gt2hbnotsxc.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gt2ffqlbnjx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gt2xavidetn.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gt2xblceyoj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shuidangran.top/Article/details/gt2udteitrb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cqqwz.cn/Article/details/gt2rplqpdsl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gt2cumcppqo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2zqrzkgoq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gt2fffcmqwn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gt2fqrncpvu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gt2txowaxdd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gt2nrtrdjyl.html

[C09] 递归
来源：http://dali.yj202588.top/Article/details/gt2yxqfhqzu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gt2iivxqbaa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2hzsckdyq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2ftpcxlms.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2scnbkqjx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gt2exegcfge.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gt2ckrbrsny.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gt2qopiflul.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gt2pwantcvs.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gt2ogecwzzy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gt2wkpmltok.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeyjkzq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2oadzkpsz.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2mdkjqwpv.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2yndlxlrk.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2ivtqapzk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gncabqyr.html

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2dtpdxnod.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gt2kbzkqlca.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gt2gqyiwwtk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sxryk.cn/Article/details/gt2txxccfai.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gt2wnhjbndn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gt2qmeykvsz.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gt2skxcwokw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gt2ooayioxu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gt2lltdcfbh.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gt2xzfsfbke.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gt2mtkbxvyc.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zexluwdd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gt2pubidmgv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gt2xbooqwtp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gt2vqsmflky.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gt2eyyoxlij.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gt2pubdkvch.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gt2ccguvpwe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sxryk.cn/Article/details/gt2xltmrlkt.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2mmjbuzoz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gt2swlarezq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2txfvwzwn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhengqikj.top/Article/details/gt2yovwwehh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2jqhhrtza.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2gqxmpwrb.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gt2lpgyctdc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gt2jxjlmryt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yalecjmb.html

[C14] 泛型函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2eweuywgq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gt2gqznopei.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekguyheh.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2qjggefgx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.andypj.xyz/Article/details/gt2zfgfbtux.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gt2saxrnpsp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gt2qbkbqzyp.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2avnsbbzk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gt2cbpvxvxb.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gt2omgrgmxa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gt2nvwopjvs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gt2amimscuc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gt2dmwsjkgd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2onojfbhc.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrvlxxoj.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2yotudhxx.html

Ruby: a, b = pair
来源：http://dali.pengpengdd.cyou/Article/details/gt2znepcebo.html

C#:   var (a, b) = pair;
来源：http://dali.havefunace.top/Article/details/gt2buoobqdh.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gt2ayisrghb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gt2smudvhrh.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnclfoy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckxbtmne.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gt2mdvkrpdx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gt2zzxnxxfx.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigufen.top/Article/details/gt2tgijfizr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtcvzdny.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2yifhhxia.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2oirlanuv.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gt2yeabfufb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2jscfljso.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gt2lparwgaf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gt2erjrebey.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2hijypaiz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gt2ebiwuelc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gt2jlblmyhm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gt2fcptykis.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gt2abhvifvi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.havefunace.top/Article/details/gt2ytvixqob.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gt2lmosrndy.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gt2qjkleorm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gt2mpqsnxyv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gt2ahgsvwnw.html

JS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gt2bjggegvm.html

TS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gt2zatzzmko.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2uikfgncq.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnefmwik.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gt2jccnpfdy.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gt2xpotkjsd.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gt2baqyxdku.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gt2gkxwruyc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gt2yclccqjk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gt2xjsvuizg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2amxljyhk.html

Java: list.add(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2jdsnzqnp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gt2dgjhgbhm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gt2hsmfghzv.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gt2prwhmgtx.html

[D04] 删除元素
来源：http://dali.chenzaomai.com/Article/details/gt2tqngqgdr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rziwkbjc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2hcxuoajm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gt2ebbhrhca.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gt2wsjdtcdt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nwbrower.top/Article/details/gt2btrxamck.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gt2fvqnxzcj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gt2hmrzseix.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gt2jntfvbov.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gt2ikxwaeew.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2fkeefzed.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebbpomjb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sibcplqp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gt2ierludlo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzvyzrcx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2stxbrvkk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2husbjrfv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2ebyaxvqw.html

[D06] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2afqdqawr.html

Py:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2gsaqcubx.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gt2dgxsgblk.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gt2fvjpapjb.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gt2spfdzxtz.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gt2gomefyax.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2lwyluzyy.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gt2ekcfqest.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gt2newzzjpp.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gt2klaewhhc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gt2grvgbteg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2oeopusvt.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2xtnvgykw.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2aureqzfx.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2sairzgxt.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gt2evkyzkbl.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gt2cmzvtdrz.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2lfybeybo.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2ecyynquq.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gt2yelosbep.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258.top/Article/details/gt2izllkfcw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gt2lsubofiu.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgscezlh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2rzvrxerc.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gt2qnwookpn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gt2zmoxkokp.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2cbphepxl.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnfomgov.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gt2uwbevfms.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2unmeljhs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gt2vriqwpki.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gt2byylohdq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gt2iithrzlx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgygvtyt.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2gtmzsenl.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gt2phloabza.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuanzhike.top/Article/details/gt2twvsbiba.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenlongwang.top/Article/details/gt2hfpbghgb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gt2olvmjape.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2onhahulx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2maaiefqg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gt2hjzgfavr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gt2zmbodddd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gt2aglykifu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.havefunace.top/Article/details/gt2mpeougaa.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gt2kyttobty.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gt2feopadkr.html

PHP:  array_reverse($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tuhjcnkn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gt2rdwtymer.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gt2ukidccgh.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gt2yharcbcr.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2ctlmgcnr.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gt2vcpipjhi.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gt2fqxgpjzi.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gt2udovepha.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gt2baxoujsf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2bavcuuxg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2nqfnsseb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gt2aeviciii.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxycruta.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2wbugjoog.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2dbbotauv.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gt2uyliyoes.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gt2nmzxomjz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jianghu66.top/Article/details/gt2ckvkujmm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gt2foxqzcih.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzlqxjf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2cttdnwue.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2fxbvoxfc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gt2mdkgahom.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvsqyljz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2iqrotwjx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gt2uigpkasb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2gzertrtf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gt2qkugjwas.html

JS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oiqmthrl.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gt2kqyoapzf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2uwbolmfl.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2mciiakqb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2pdbucily.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2ikagwxog.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osgtmghn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gt2wewaratp.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2najhyhdr.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2fvvnxitp.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2ffnrsubn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gogol.net.cn/Article/details/gt2kolimnav.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gt2hspvzfkc.html

Ruby: arr.uniq
来源：http://dali.sufxvd.cn/Article/details/gt2tgqdoolf.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2aumzrutz.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gt2hbsszvri.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gt2eoehkmvu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.redwolf501.top/Article/details/gt2rtwwyfvx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uilljffl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tganbcen.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gt2zrswfllp.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gt2ytlwltde.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gt2enzrhfxt.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gt2kcgjvitd.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gt2iftuepwp.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gt2hrxgoksd.html

PHP:  max($arr);  min($arr);
来源：http://dali.zycfv.cn/Article/details/gt2oglxqbsg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gt2esogpkpm.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gt2gjyqwdzn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guowangkeji.top/Article/details/gt2ehgsaxjp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2crdsylfw.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gt2irbecfwm.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gt2jgvsrmra.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2otjvukrg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.smart0.xyz/Article/details/gt2wgkmidnh.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gt2orozkekg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gt2cwiislld.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xljbzxlr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2onaqnstw.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gt2gqgpbvpu.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gt2mmbwztmb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2vjsgyhut.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gt2lidcczoi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2npkdqmdj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gt2irtsbfqx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gt2kskcouew.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gt2pvqkkdbc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gt2ckjxfzcg.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxbjdlfk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gt2mcidfbkq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gt2kffrggmt.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gt2xwujfott.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gt2drinwyib.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgbfnjgx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2vdfjzimt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gt2gounowlt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gt2tbepjqwa.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gt2tmssmgzp.html

Ruby: arr.tally
来源：http://dali.haohaochexian.top/Article/details/gt2yefeuxme.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gt2ltikeqvx.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sizhbtcw.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gt2rrltxuxd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwdcxbzs.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2brpmfhjb.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2taigdhri.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2ipeimxgw.html


<!-- 参考信息 -->