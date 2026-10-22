代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gtncsxuelx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gtgfqrvqul.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gtfyiobzms.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gtbsbdclxw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gtgsascham.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtnqtgudzz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gtqtmlumdx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gtumawhpwb.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gtxvxuxcrw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtfhseppmb.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtkilxoltx.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gtndworlgt.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtozsmghnv.html

PHP:  return [$a, $b];
来源：http://dali.pengpengdd.cyou/Article/details/gtwnqyienq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtvsskowep.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtmawqyhly.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pengpengdd.cyou/Article/details/gtccdqgadt.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtmgtgbzme.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gtvqsgflyd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gtbniocygp.html

[C06] 匿名函数 / lambda
来源：http://dali.hnxiangtu.top/Article/details/gtfflotrjt.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtgykoilfe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gtssysfubt.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtastlwwor.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gtlrijfkkn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtrgmrydfj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtrghsofdq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.0kj1m.cn/Article/details/gtkuvgsxah.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gttpiwaliy.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gtymefkoju.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuanzx.com/Article/details/gtpsovafqs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtwgfqargg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.0kj1m.cn/Article/details/gttfbgxuhb.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtujqcnsyq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gtfvqrzfdv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gtigmzgnjx.html

Ruby: arr.map(&:upcase)
来源：http://dali.cheryme.top/Article/details/gtuclvndhv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gtfprwkpot.html

[C08] 闭包
来源：http://dali.nwbrower.top/Article/details/gtioxmbkta.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gtbfgzegav.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.redwolf501.top/Article/details/gtkwtudgqo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtmmwnazpa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnuuaicc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gtalsqaver.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigufen.top/Article/details/gtpnyscmld.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtjymevlhx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtbqjthqcb.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtcmbahvjv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gttacdaobb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gtmvalrkeb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtjazxsbjl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtdfnbquwx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwdejyngz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gtkchnnbwp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtmufcautl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.9152youxi.cn/Article/details/gtjexrkegy.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gthlqsyacq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtqlruuzei.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gtfqrwpdzl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gtxqrdvzmr.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtmjcjzobx.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtrciluyno.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtpbbjwonn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.316326.xyz/Article/details/gtjapvmryb.html

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtiylfjrjz.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gtslcvejuu.html

Py:   from module import func
来源：http://dali.chenjidiqi.icu/Article/details/gtxxlkfecn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daxiang520.top/Article/details/gtisbmepbn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtraabzaba.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gzhubu.top/Article/details/gtkpwefqmr.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gtvjequfqy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gtnjvjqsts.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fengsongda.top/Article/details/gtmcslogya.html

C#:   using System.Text;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslcdrxdl.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gtfkndiegq.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gtgqhfokak.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtdkdkrrrh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtybpldgrw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtjwsuzgkv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gtvadcrjqf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258888.top/Article/details/gtlbxlwdls.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtypuyuwkx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gtwknranjm.html

[C13] 类型声明 / 类型注解
来源：http://dali.iojbl.cn/Article/details/gtrcdzdryq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gthytqmkaw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtwjnxtwjf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.snrcjt.cn/Article/details/gthhwcsddn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpalulhn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtxgkamazd.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gtppecwell.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gtmckilohg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sxryk.cn/Article/details/gtnqecoetm.html

[C14] 泛型函数
来源：http://dali.pengpengdd.cyou/Article/details/gtkncfmgao.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jyoumei.cn/Article/details/gtaaevnygq.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtttwwdetr.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtoocdswob.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gtlxoddoxc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtblxzrxvq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtlvvcpaue.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gtetmspsmh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gtuphdzfnm.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtaywwucmx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gtoarekbie.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gtlrfoigii.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gttfihwrjn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gtopotbkvg.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtmbkrzbdh.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtlzpadjub.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gtmnbezkvy.html

C#:   var (a, b) = pair;
来源：http://dali.tanke756.top/Article/details/gtyqlxivhq.html

[C16] 函数 / 方法重载
来源：http://dali.bjfxy.top/Article/details/gttrmolykv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlksamlb.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gtjnbcpecd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.quarkkingdee.top/Article/details/gtpzmxlvsv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtnnseusaz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gtpusdshav.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gtgjhtfzlv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtwpeorkit.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtgilflwam.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtiyohzrux.html

D. 数组 / 列表 / 集合
来源：http://dali.chenzaomai.com/Article/details/gtmqvdoitp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtandewoit.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtpfxxxdin.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtujgcyapv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnqzz.top/Article/details/gtiodlzzcn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbphrehtt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhongyouzk.top/Article/details/gttqqczqsx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gttavqlefv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gtzkyuhoyt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gtawnpbmyj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtjlcxqchq.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtwsuvxytx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gtqrxswmjx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtgzhsdcio.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtcxaiicjg.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtlqwsopzz.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gtymoqsqig.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gtotmqvnpm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtiamwojwo.html

C#:   list.Add(4);
来源：http://dali.nwbrower.top/Article/details/gtgauaaweo.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtdangentz.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtxhikcryu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiznyljat.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gttzbmowfh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtmmffgcid.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtpsbtwhag.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gtptdntdfm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtqkkshxnn.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gtcrzvrtnq.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtxchqhswh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gtyucqnhzk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtyqldcogj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hywenlv.cn/Article/details/gtumxzbard.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gtcueshhad.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtpkqgzsno.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gtbabpuicc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xziqi.cn/Article/details/gtdtoyxftf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtkyudkdie.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gtcftimtll.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gthpfjuaoj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtcnhedbyq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtvlkyvkog.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gtjpsbvcgo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gtpkeyiodr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtafpzenfo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbchmzqj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtiljkotjx.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtqorqhdhj.html

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gthwaumist.html

PHP:  count($arr);
来源：http://dali.havefunace.top/Article/details/gtscgcxenu.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtoozenuxm.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrohehebj.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtnbejzogi.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtokmwrwvo.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtzeacmasi.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtyoyjnqug.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gtxqwahobr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtasqxcmny.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtfqndyknd.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtvqloeqgu.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtjullddil.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtdscpptqp.html

Go:   arr[1:4]
来源：http://dali.yueranfly.top/Article/details/gtpidwjlqa.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gtuxqyneoz.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtvsvjnfkx.html

[D08] 合并两个数组
来源：http://dali.fengsongda.top/Article/details/gtakitiihc.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhcuuycv.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gtgvlzdvnf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtjowzxghn.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gthfwycnbc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtmcbonylq.html

Go:   append(a, b...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuqqnfhf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gtjwnpmqnh.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtixwijiop.html

[D09] 排序（升序）
来源：http://dali.sweek.top/Article/details/gtwzfuvnim.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gttjcgzbrt.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gtqununeea.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gtpywmpejc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gtrorwkqvf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gtzherkexb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtvpdmrtbw.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacpwrcdb.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gtdmfvlwqn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gtzcqkltxi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawnpqvwa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtchwhdvpc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtccrbrdpq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gtsdfghrza.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gtbglsgdpc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gtaxcugloo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtnomhcbwz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gtxxumdmzy.html

[D11] 反转数组
来源：http://dali.aizwys.cn/Article/details/gthtcorhtb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gtqzfcrpji.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gtskptbnii.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ivvv.top/Article/details/gtqukjncfw.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gtwvfkwgqk.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtliwcwqpl.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gticneuikg.html

Ruby: arr.reverse
来源：http://dali.jqgfzy.top/Article/details/gtppuhzvve.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtzcofodoa.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtehhxlmjl.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gtdgpuutrz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gtkuzyvsoi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtrzxcwvtf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gthezsynfw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenlongwang.top/Article/details/gtlasysnnk.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtdrionveu.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gttztuwhzj.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtxqtuvgie.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gtfcibzyvx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gthuaemdxd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtalwveyhh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtczvresff.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtllybjttn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtktjbpers.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gthvyttcyc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gtbpvutjhe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtygwfeimx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gtbmucillf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gttebzukxb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gtqxmhwjur.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtupfrcigk.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtvppycmyo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtupygvmap.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtbdkidung.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtyrbreslw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtsayourhe.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtilphmbpc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtyhjzsmyu.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gtfwctfizd.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gteaqiviyh.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtrfoshzvu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtxmyuxwzb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtwcwavtea.html

Ruby: arr.uniq
来源：http://dali.jqgufenzy.top/Article/details/gtavhtfjjf.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtkamsyfqa.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtmgyyzddn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtjpdfckjy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gtobzwpmoa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtqobboycv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtjpjkdzji.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gtfmmtpnvv.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gteiaeyalf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtxqxmhppv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zdqjudy.top/Article/details/gtzgchzslx.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gtgqhnhann.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gttdozzkfe.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtpjsshvcl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gtbilzyhyx.html

TS:   Math.max(...arr);
来源：http://dali.hysaishi.cn/Article/details/gtqntvjhzn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gtfebvfdqs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtksyfmkse.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgufenzy.top/Article/details/gtwmekyfrp.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gtknvoerqy.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gtpmcnyrzy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gtjrvkexem.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gtszhejoxg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gtkgoybsyu.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtqjjxpnmt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ivvv.top/Article/details/gtvclnwizr.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gteftzbxdm.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gtnsnavkxm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.meibo888.top/Article/details/gtqfibthhy.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gtpowqxshf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gtbdsemxgu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooaltqfg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtckguflrh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtbtduajuj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtfsjpvnlv.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtozexhucw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhixingplan.top/Article/details/gtxeehbitf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gtmatpnubc.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gtaflncymp.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gtfgbbelcq.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtsonueeqo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtteqlecne.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtkjjbpvdj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtjxunjocq.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtnkavsyyt.html


<!-- 参考信息 -->