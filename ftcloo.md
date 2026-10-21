代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.vqdsnc.cn/Article/details/gtxxhijlrg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gtedcbkmpl.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtvmdadltv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gttsnthrza.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gtsdzwulfv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrgasitha.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtapbeqmgz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gtuvhtbiic.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtusdwecmq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gttkwmgkjh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtpybuuave.html

[C09] 递归
来源：http://dali.dianchejie.cn/Article/details/gtykgapwqm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbmupzdy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtfkruwgdp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtxcnuhhak.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtgarbnlxw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtnhevrpep.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gtyxtsfxmv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtmggarpce.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cashguo.top/Article/details/gtorglnvbs.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gtbmqwlrku.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gtsczgtbbe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gtclobbyzw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yueranfly.top/Article/details/gtfvokqljd.html

TS:   同 JS
来源：http://dali.sweek.top/Article/details/gttchjljzk.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gttavimpwv.html

Go:   花括号块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtwbhfkthn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gttncjegvo.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gtznymlxjt.html

[C11] 模块导入与导出
来源：http://dali.jiagoushi.top/Article/details/gtmulqfqia.html

Py:   from module import func
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqvhfwor.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gtkpoiksbm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gtizmaofmz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gturuulyje.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcegsgkpg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcrdwrwz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gtowophlyi.html

C#:   using System.Text;
来源：http://dali.gogol.net.cn/Article/details/gtttlowpep.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gtlbkniytl.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gtzmqzymhx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zycfv.cn/Article/details/gtbkuvnuso.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtekrlabde.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtdbguyvej.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gtfjxblzpm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtzhignaum.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtjhakrzcn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gttjdhyxpk.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtuyzprbot.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gtwqpobmih.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gttdywiqbm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gtbdsdcqub.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtsbrbyspx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtmirjezzy.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gtfghcvmsq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gtmzreuwmz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gtxniyyuti.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gtsxnqqyss.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtooigojjv.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtjpkczxvs.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmaqoanfj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gtqkfuculq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gtodpzvwcf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtqogvslja.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtldshajaf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtfvjosbin.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjimsdol.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtwtnrijvr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ybcxt.top/Article/details/gtvzomlsqr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtcujvlqzd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gtudeimzkw.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtghixwrjw.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gteqnniwgf.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gthcjdaene.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gtmgrxkpwk.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gteewktmkc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tianlin.xyz/Article/details/gtmrmyftta.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gtycyzlwmk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtfjbldtdk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangdashe.top/Article/details/gtovqqhjup.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.smart0.xyz/Article/details/gtjorrejdx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gtgxofcsdp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gtmwrpexol.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyddrsjn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqzeapvkv.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gtkfqdcodc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gthdsvflxc.html

[D01] 创建数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gtsvzhyshq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtgjncfqzw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtumtfvbmx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtiavibeip.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenjidiqi.icu/Article/details/gtdvihihdr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gtdxjuxzai.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gtqqsrsuvn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.havefunace.top/Article/details/gtyffgdyzq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtptkhktdt.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtlpvxxffu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gtwnqvpaqw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gtaqteqyts.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtgcsktawl.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtljonwiov.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtxtrdbvfd.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gtlugcdzjs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtlyrbzvop.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtzeyehkxo.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gtxuxwhpqy.html

Py:   arr.insert(0, 0)
来源：http://dali.havefunace.top/Article/details/gtuigqylpc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtfxqlbpia.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gtcjmmowol.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtetmcrhok.html

Java: list.add(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtzunmtobh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gtfpsjcfme.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gtjzjspcao.html

C#:   list.Insert(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtajomozia.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gtvjivuphl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtxymbfszh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gtpkxxnovk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtheuuyibd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gtbcyngwlo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gtltjsdirk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gtdydnbcir.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gtbeqzbcaf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.iojbl.cn/Article/details/gtftrelapz.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtwiuedqmi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtcgwzuucu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtapsekwud.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtpecniwuq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gtjmhaunbt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gtufifwdyv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtemnspqkc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtoghwkujq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtwxfmpvey.html

[D06] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtjnazjtox.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtfgcsmoee.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gtvbjjqmef.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtspwteyta.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gttigzholp.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gtscelntdn.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gteodjlmhm.html

Ruby: arr.length; arr.size
来源：http://dali.hywenlv.cn/Article/details/gtoyezxodg.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtemdyrxau.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gtbwfmiquk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gtvobfxsbn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gtkyzaucik.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtkyfznqgu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtwyrkkzim.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtystzhohg.html

Go:   arr[1:4]
来源：http://dali.mhx1999.top/Article/details/gtiwslzsjz.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtiplecsxl.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtdzniciry.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfwyndzg.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtwhbegyiq.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gtakapeggc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gtwvporlph.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtxmrpxujv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtmgktponc.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gthdjrvgpn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guowangkeji.top/Article/details/gtjyvxytxl.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gtvozbpmns.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtqfkmcavn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtsdolrczu.html

PHP:  sort($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtvpxybptn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gtrebmrtxg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gtmranmnuz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gtjihmgwkf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtrcjyiubc.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtdwrlfrlw.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtwjdnhstu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gthgdnlsmt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gtjsrztjdi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gtdmtyjyrf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gthhecanof.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtbjhggvys.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gthbipkfhs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gtnnvwbwyo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jianghu66.top/Article/details/gtnvqgyryb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gtufjxewip.html

[D11] 反转数组
来源：http://dali.9152youxi.cn/Article/details/gtxkatfflk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.mhx1999.top/Article/details/gtvetalhoa.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigufen.top/Article/details/gtlvxpxodw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ybcxt.top/Article/details/gttszrrfpd.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtajjnlcnr.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gtaualbpnk.html

Go:   slices.Reverse(arr)
来源：http://dali.sxryk.cn/Article/details/gtzxcargpv.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtspxojfep.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gtgstamqcl.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gtkullsnqm.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gtjkatlkse.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzeygndn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtqcmweixk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtbqtfhwcj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtdnghtrxd.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtgxflqfpy.html

Ruby: arr.index(x)
来源：http://dali.gotoacloud.top/Article/details/gtygdxhdyo.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtnrqyzgpy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gtmcsbuqaw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.meibo888.top/Article/details/gtvtgfdjke.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtmovohsuk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtqrgcpsak.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtabtnttpp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gtdegouwxs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gtcefbghfk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.svipenyu.cn/Article/details/gtolspcndq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gtdrbqjzth.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gtlmjpyupd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtwmebpdbu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtaavsqgnr.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtnfqboyap.html

TS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtdxgfozqx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtwucortrm.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtvfawtcxs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtjravwvff.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtdybhbfpw.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gtevymrgnz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtepcckbxn.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gtwqkcdmhl.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtaltkpcnu.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtuseieygj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenjidiqi.icu/Article/details/gtvykmijod.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtnuoohwmf.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtgwmbjcwo.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gtawgodksk.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gtqimduobq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gthchqofvu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtpwepybhj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtsvcuuzmh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtbgsgmtqj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtcatowpqw.html

Go:   // 手写循环累加
来源：http://dali.yangfankeji.com/Article/details/gtryvqvshg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gtykljxjrw.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gtucfmlhna.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtjvorhxwg.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtanurzmba.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtgbfefszw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtrfsswzdn.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqpdvytw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gtkstowapu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gtdlonzrpk.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtxcppcllm.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gtpvmtbmjx.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gtyjjtomys.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtstgirony.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejcnrlwq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtacnczchu.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtqamvnvic.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtepemsmnc.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gtspinrzeb.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtdrakitay.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfykmvhfu.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtxrfrtdik.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtvegppbem.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtphdisdhn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gtjmkeybzb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtyavtxjbf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zycfv.cn/Article/details/gtftbokefw.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gtlgidyxao.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtirmcqgsj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gtzwmnaddg.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gtfgjfrypu.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gtksmyencd.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfdhenkr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtnojsoigr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtwikuwimf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gttbkxliig.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtpdesrmkp.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gteunfctqq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gtkwcrgudk.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gtbkcyaqwl.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtnnefmfrm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gtbzhzottr.html

JS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtjvfkxhon.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtgykmluhj.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gtaswtobfb.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtdmjwrkbo.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtbjgynjid.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrddigpps.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xylfe.cn/Article/details/gtlkwnhymw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gtgjmnoabu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtlokegw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gtaqswwdzr.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtyfmomxjj.html

Java: new ArrayList<>(list);
来源：http://dali.hfpthk.cn/Article/details/gtohmshdzf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.redwolf501.top/Article/details/gtbkmktpqp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gtofhnlikf.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gtsjszlpey.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtqzrapxos.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtvalrwvya.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ppjwa.cn/Article/details/gthpthcjng.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdejodxjv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gttkeqlexl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gtjfxfkmxu.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtfkwpbvxy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gtrflulush.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gtwapiwmih.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gtcbtsaryn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtpxfoeorp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gtsbeafwdm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjpdwgbed.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gthnbcvivo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtgygkyjvv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtfjdycu.html


<!-- 参考信息 -->