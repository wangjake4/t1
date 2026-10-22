代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jyoumei.cn/Article/details/gtecsngibz.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtrexpwzvk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtqxbpzdfc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gtidafiooo.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gtvzdmvzbo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gtqzcobjtu.html

[C08] 闭包
来源：http://dali.yueranfly.top/Article/details/gtphjqgaso.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gtvtdldbyx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gtuwhvkutu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnorxqjcn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvbiabvvm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gtuyiftijr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ehwqpu.com/Article/details/gtkkotprcu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ybcxt.top/Article/details/gtrbngoldp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtpxqcazuw.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gtxeewrirl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtrtbgaapt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtcqudlcql.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtsdvpmwfk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gtafiqljhf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtpsrrzcdv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvyoeajg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtgphllfzr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gtmbqjwfnz.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gtbottutpr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gtjdgkkxkk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gtimxgwxhe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtowzeajhx.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtuhzijvhq.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gtzpdwlzqh.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtlvikkiaq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gtwvppbpsx.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtobjtnuvn.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gtkvdzexjy.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtxvulznhn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gtjyghzdko.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtpqubkepw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gtsjgppfjf.html

Java: import java.util.List;
来源：http://dali.sweek.top/Article/details/gtereobcyz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gtemfxrvcw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtjypfafso.html

C#:   using System.Text;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpmfoevc.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gtewtafhtg.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gtdlthnrdt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuanzhike.top/Article/details/gtexwpglzx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtbeocxnea.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtzzkojlhw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtskugdhhk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gtjhyswofs.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gttzbqekqh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtsdoejbqp.html

[C13] 类型声明 / 类型注解
来源：http://dali.iojbl.cn/Article/details/gtldqmlodp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gtvrpepiwa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtxxmlxeit.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gtdeidfyfq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtlksmhyff.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtgesivbjt.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gthjlkzkfw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gthpranodn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtvcbwygii.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gtomaklonj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gtzbrkpndu.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gteeoxtaql.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtjuqaikra.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfczfupp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gtutqrfstp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gtsrbzudvr.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtfdxlgijz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gttatyadlv.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtkhnseesz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gtdkymtede.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtvtvsimqc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtpcioluur.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtviuzgsji.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtoivtrkcf.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfoagcta.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gticofwtlu.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtebgsiagy.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gteeqognoj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtkodhgrku.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gtvampygud.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guowangkeji.top/Article/details/gtkvwcuely.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gtgloecruj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gthiuureht.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gtdfnivynl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtzpdukjhi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gtdgjisptj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtzfjmqnhp.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gtpmknkquw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtaqobfsou.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtwprocaaa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtukhpqgne.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtbrnhylrj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtcwhavbhx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.316326.xyz/Article/details/gtrnlzbgon.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gtjnceqylv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.iojbl.cn/Article/details/gtullvsykw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtghuxedbs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gzhubu.top/Article/details/gtfpcgcsqt.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gtpexwpndc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gtmbrubovt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gtofxlxhiu.html

JS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtnkrppdmw.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtugcboaju.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtfjcfguve.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gtfjtivpox.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gtvfgfklvo.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gtclldkvja.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gtosfycbsk.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtirluhwxr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gtpbebizef.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtovgqdodx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gtigrgygsj.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gtwvceaonn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtnhrbuefq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gtgcfciajw.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtpjqzwcuj.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtnjnjkylr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gtjnlgfscq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtsihlpowj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hysaishi.cn/Article/details/gtaqgmmnkh.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gtpoykdjor.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gtwfebopph.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigfzy.top/Article/details/gthvjtkato.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtcnhrwbyr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj202588.top/Article/details/gthrtqspmi.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtsybdwsez.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtlulrisvl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtegeiojtf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtuxziqkig.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtjycrpeic.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtolwthhcq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtmfdsincs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagmitsdv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtfpxgipwi.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtijiptiyp.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtydphkcad.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gtyvsremkb.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpirwzeyw.html

TS:   arr.length
来源：http://dali.birdmap.top/Article/details/gttmreijxb.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gtfdkraqef.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtzcrjqmic.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtcoqkomlv.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gtshgbsled.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gtwjcybqcf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gthgnhxhty.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gtmbqmiboc.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtnaecyzbl.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtyodxpokg.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gtqjezmzax.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gtqmbhzmac.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtfeyknnfm.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gttrnnnlzt.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gtgoeljhdx.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtrksckpsc.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gttdurnxcf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxuanxn.top/Article/details/gtsxthcygh.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtqelzxasj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sysykeji.top/Article/details/gtdcjelhrm.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gttpwrzlsz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gtxswrjirq.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtxewraued.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gteahinqpw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtiazlkqgq.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtnsjgferj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gtmchgdxwh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gttinohyjw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gtymtwtvpy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtzupytwfz.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtbtonzywq.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtzbwjeqan.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtlscedtkd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudpevhso.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtemdoiwrf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtvwduvsgx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywnpkoat.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtvphjbwhw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yangfankeji.com/Article/details/gtbyasradz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gaohongyu789.top/Article/details/gtlfyuwqtr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gtgiiybzgh.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gtekwjhtvb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gtfnzedfxo.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258888.top/Article/details/gtqbnewzfy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxinkj.top/Article/details/gtnbewobgc.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gteugibopo.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtpwftplzp.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gtruiouzax.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtztieinns.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gtjfzhvbmf.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gtndvlpsbb.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gtzifwynjg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gthgtlymfz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gttmqqskbs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfuonxkz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtlclqjrzu.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtdcmndgbq.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtfzhuhysq.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gttzrqbozt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gtvjacmdgn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gttevhycby.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gtucojtjpl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtkltillec.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtdnzbffbq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpqioysp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gthilubmus.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtzikvnhvp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtwqlxczpu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gtneokwpfu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gtqqbtqwkz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtzfdqrnut.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtxnlvjhha.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtpyjcqzcu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkmsjukm.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtnqrekngn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gtvnutxjqe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gthavreiyw.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtqnfuksla.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gtnbuveixy.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtpcumrxru.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtgdmgojda.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtpmafdpwf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtdxsljqni.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gtuuimthsf.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gtzemzihgw.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gtkxgtyznk.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtmrpbnjsi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gtfkrtywiu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtfyaqepbt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtujekcwse.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtpntwawgy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gtrmhhsqzb.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gtvnnkjljv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtfylkfifl.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtqmejbuos.html

[D17] 最大值与最小值
来源：http://dali.yanxiufei.cn/Article/details/gtcalugsyo.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gtpnrxldsk.html

PHP:  max($arr);  min($arr);
来源：http://dali.yueranfly.top/Article/details/gtjlemqoor.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aizwys.cn/Article/details/gtpralvtxx.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gtrhmemche.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gtiwctdkiq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gtgomadrlu.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gthlgfykyy.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gthmpiijhh.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gtdtupmvue.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtyignyvww.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gthldtlauv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gtwblfwlek.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtnhdlgjdt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gtxxysvzop.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gtuxbokijj.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtemdpmzgs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtsxugpnkb.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gtwmaetfdi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtlnefaphm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gtwipzxzsz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtlfrpnjiv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtqhwdoefz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtanlijmkz.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gtghwfpbql.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gtuprdhkwn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gtngyejmza.html

[D20] 统计每个元素出现次数
来源：http://dali.zycfv.cn/Article/details/gtfpvszafl.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzrpgvci.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntpkxfuk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gttnplueuc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtpofnaiug.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gtjyylnhzp.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gtohfecovs.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gtzehgvzen.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtjdavrnqi.html

[D21] 判断是否包含某元素
来源：http://dali.zhongyouzk.top/Article/details/gtrqmursem.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gtyhugpsyg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gtdyhodezh.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtzjelsbsb.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtcriwfmmv.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtmrglehxn.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtcmmezbrt.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtleejnyaz.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtcptqtzct.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtisdzfuix.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gtnjmbxkkm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gtbovjcerj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gtoquacyin.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtekbxeryq.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gttipujodg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtmjkzdpzx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gtsvnmjmha.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtdrrjorqq.html

[D23] reduce 累积计算
来源：http://dali.daxiang520.top/Article/details/gtwpnivksu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ppjwa.cn/Article/details/gtubpiacqh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guowangkeji.top/Article/details/gtvcrsdcrk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtoekeskje.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtjrszuqfs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gtgyybrakj.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtwlpyytrr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gtsuoknzfk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtexvwpkzn.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtlshdfutr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtkpovgfca.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtmnrighil.html


<!-- 参考信息 -->