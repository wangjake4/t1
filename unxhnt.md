代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtvyshkipm.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtzsylpcka.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gtsxoepxmb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtttnxqxhn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnqzz.top/Article/details/gtxnvzirva.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtdqsprjly.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtidrirsgz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gtvoizfoxu.html

Ruby: arr.map(&:upcase)
来源：http://dali.gogol.net.cn/Article/details/gtdtogkfvv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gtnwlfuvou.html

[C08] 闭包
来源：http://dali.dianchejie.cn/Article/details/gtwrdzulbt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gtxabfxvfi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugratpuy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtxoatyzbm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtugerbhhp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.feifeiyinyue.top/Article/details/gtzndgepin.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gtijiyibhl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gtysehjyca.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtxbulvlqr.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gtyxxhtkqp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtsriqti.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtgnyyipoz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtvkmbwdhc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtbnnymhim.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gtykpinrnt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.0kj1m.cn/Article/details/gtjsjrlzwf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtrxalbmqc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtlkgriwyk.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gtgkepvukq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gttbjxfwov.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsvqktur.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gtxmolagyx.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gtbaytdjzm.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gtxoafedzu.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtbmrbohcw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnztosjvp.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gtllcxoppt.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtycdiojil.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gtnuwkvsmf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.c1oappe.top/Article/details/gtovxtpama.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtxnniyima.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gtagvypspl.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gtzntilrmq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gtvrkgiiyn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtnvoxogzd.html

C#:   using System.Text;
来源：http://dali.xuetiantiany.cn/Article/details/gtibfvxwks.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gtcmqduozv.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtknbowfpq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gtghbdrwam.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtcbapqost.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtiejtcohn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gttbwqcbhy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gtsqnjcodn.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyesfcqyq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtzgikjqcw.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gtifljwmdc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gtcgzasqpa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtamenqzxz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtjnhutkkx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtyfgypyfr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtfuarsert.html

Go:   func add(a, b int) int
来源：http://dali.andypj.xyz/Article/details/gtzhcdtrkm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtrscjrwzp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtzlqfryae.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gttafwcqhg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtzeotsxlr.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtjfmhcrck.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gthfzlfvcn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxinkj.top/Article/details/gtcthxzlgh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyvrhkssx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtkgtblarb.html

Ruby: # 无泛型
来源：http://dali.daxiang520.top/Article/details/gttcewcvsc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fengsongda.top/Article/details/gtuycvuthp.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gtdhrsokgh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gtvdobnscl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gtxlkowwyy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtimvuykcu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gtgvudlfza.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtxaeaeejt.html

Go:   // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gthbhnxdan.html

Ruby: a, b = pair
来源：http://dali.9152youxi.cn/Article/details/gtgtyowvtr.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gtmsbotggz.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtsldobzbt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gtifjvircx.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gtasdmpbda.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gtahqnozel.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhengqikj.top/Article/details/gttczchohy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtxvntjhqq.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gtoytvjtjo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yangfankeji.com/Article/details/gtvwpoyvcx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sufxvd.cn/Article/details/gtywncnjky.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbknwrbzv.html

D. 数组 / 列表 / 集合
来源：http://dali.fzhhl.top/Article/details/gtxmtegtmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbqgjauon.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtuznmoehr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtjaaqadgr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtxhuqtqgr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtdlpqqzkw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gtqsmsafvi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gttsqwgeli.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hysaishi.cn/Article/details/gtmdwxpiip.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlbnjsmd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gtpuabbnis.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gthyyxafww.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gtkcjsgjba.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gtsyzooyix.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtbfqqobul.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gttdtfrqcn.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gteahwyjvm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtxhrhvzgz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtcleqdsaa.html

C#:   list.Add(4);
来源：http://dali.yj20258.top/Article/details/gtxqnlfdam.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtrijrvriy.html

Py:   arr.insert(0, 0)
来源：http://dali.iojbl.cn/Article/details/gtylfrifet.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gtjixlllzu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gtkninsvrc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtmbgvckxx.html

Java: list.add(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtlojyisod.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtsuzwpyhr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gtjgzcqgnd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhrqsutp.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtuyaxjtsm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtzjnqxhyr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtkhkgqfjd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gtefyyxprn.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtsuwdqngq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gthsptryjm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrscvmnxk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gtdlzggwfj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gtnwsswmif.html

[D05] 访问与修改元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutunfaku.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtniunmryq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtbojrndld.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gthvanomct.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtqhmutyrl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtdohrpwxt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gttqfyzwbj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtiecsbfpq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gthsmuftyx.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtzfnjgnvf.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtowmwicob.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gtfkbdbjsy.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoumpyxjv.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtcxsaoiap.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gtdfodijco.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtfgkxpjpu.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtpjzsipvq.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gtoqflcfbb.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gtwdnfzljj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tianlin.xyz/Article/details/gtajfmlqxe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtzfawjjxo.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsoxhtis.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtavjazrrf.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtyntcbfrk.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gtvghidlnw.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gtmpommpgb.html

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gtqfzephsm.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtfqpvkohn.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gtiqzhmgnw.html

PHP:  array_merge($a, $b);
来源：http://dali.andypj.xyz/Article/details/gtpvfoagum.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gtdzxilayl.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gtpwlmldpq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gtwjiygwai.html

Go:   append(a, b...)
来源：http://dali.fzhhl.top/Article/details/gthsauxitc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtyjubmvhk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquakaqmv.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtmqxnlotw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtkvxlcpux.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gtndztpote.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlekzvrbb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gtfwuloyft.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtlbtviucp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtidmwezlz.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtypghnnol.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtombvbfma.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gtnldmqllj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtglmkrmce.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gtcbjmctyq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gturfqomkl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtluwgfgcp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalhuxnzd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gteotvnxqu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gtrizzmcnl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gtfyotglop.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gtghozzbfd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258.top/Article/details/gthyggtvew.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gtzdubsfzu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sweek.top/Article/details/gtplekhuah.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gtcgpxukaf.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtqucqruxo.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtrcmwhwdl.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtgeixyolc.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gtfcivqcny.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gtxhdpryaz.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtupnkatob.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gtqmfsxxwh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtxbvtrilj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtwafcssnh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgmbtqbv.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtkykdfjlh.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gtbhwyeluy.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqeycoyt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtszkdglnt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gtdvuwbkqs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zycfv.cn/Article/details/gtsekisftc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtjaycuzcc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtkukgfbkf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gtuochjvzd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gtqxamnrww.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gtunzwjhrs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cqqwz.cn/Article/details/gteemklswl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gtzjalrpve.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gtnezfkyxb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtugunsqiq.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtalgxrjfa.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtvdparouk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfaipiit.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtxzliodbq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtrqdpbcbu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtwieninzi.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gtjpaqklyz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtetubxmiq.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtjszoniwd.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtnjgvlqsp.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtbmkorvhi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gthbujwour.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenjidiqi.icu/Article/details/gtxqedywel.html

Ruby: arr.uniq
来源：http://dali.yvedp.cn/Article/details/gtzbfapmin.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdunyeyjo.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtcbkveneh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.andypj.xyz/Article/details/gtgymehroo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gtevqpsvft.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gteypxxrhr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtdzbtcakk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gtggpkysxp.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gtxrhfpgxn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gtxmvwoysx.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gtfkaashqi.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtoptvlurz.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtxfsxtatl.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gtvloqcvrn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gtsaowjqvh.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gtcxfqnlit.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlqnexnc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hammf.cn/Article/details/gtgjrzwcll.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gtxqwjigla.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gtodggnmgh.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtvjkxpvbo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gtjqrooibh.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtqvjxxrys.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gtkgmdloef.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gtfqdlnmra.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsenvynpj.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gtezkdbznq.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gtxqdxqxbu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gttfmqibhg.html

[D19] 按字段分组
来源：http://dali.quarkkingdee.top/Article/details/gthhuluijl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gtsmrkgarr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tianlin.xyz/Article/details/gtgakldsvj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gtpptcvyjk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtplagorbx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gtpwrytbbd.html

Go:   // 手写 map[string][]T
来源：http://dali.hammf.cn/Article/details/gtskwvivss.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gttyessegj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gtgwjaanuy.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtirukjazz.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtlsqmrbbz.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gtwhuuclac.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtsqezvtyi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtotxdtcyi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbirgddi.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gtsgafgxzu.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtioxwmtol.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenjidiqi.icu/Article/details/gtiksbyjoj.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gtoakcmhzo.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtlsoyhurh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtgifwawnc.html

JS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtzjqzdcec.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gttvdgwosy.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtbzqormrj.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtwkzxbwhn.html

Ruby: arr.include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtoufvmvdh.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtgsnjxgck.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gtyocyplbv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtjahtdbdj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gtwtjyavzg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gtyckhqhgi.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtcesfwhwl.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtgrbjnlkx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtcctmkokq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gtjuxsmdpr.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gtrlfecdkb.html

[D23] reduce 累积计算
来源：http://dali.guannengcc.top/Article/details/gtnnxovnes.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gtpgdpqxaz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hammf.cn/Article/details/gtsnobcqus.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtxlwdbscw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpszxbfjj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj202588.top/Article/details/gtaavcpmkn.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtnlrnpnyd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gtokasrfvr.html


<!-- 参考信息 -->