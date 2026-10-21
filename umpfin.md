代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gtfvbjtkln.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtkmtcmrzj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyokvpyag.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tianlin.xyz/Article/details/gtuinvykpf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.kuanghao11.cn/Article/details/gtwvtehebn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gtlxiyrjkp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtpcvebtwh.html

[C09] 递归
来源：http://dali.shangyingyoupin.top/Article/details/gteluufrld.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtjfijldxt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtsuzlwuqc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gthkclbecz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhengqikj.top/Article/details/gtkmgobcsn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtotlbacqd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtqpkfmrhl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gthibixiej.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtghpihpov.html

[C10] 变量作用域
来源：http://dali.tian-w.cn/Article/details/gtpxoqiyxb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gtsefkulmr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtzlrpwmky.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtdrsxjsax.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gtahejxspx.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtadvtgfcc.html

Go:   花括号块级作用域
来源：http://dali.birdmap.top/Article/details/gtoazisjxb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gtuomdqkcm.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchxmiivb.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtuphkylaz.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gtkwtugwvm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtlwushgzm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtfteaezdi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gtkhpznpnw.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gtbfxiyzse.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xziqi.cn/Article/details/gtknqlegdh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gtobrmhoxh.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gtmqddvrwh.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gtryfttxqh.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gtpevvcujp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gtveybpfwq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtmubaanux.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtcfzfxlcq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gtgwfdfrsd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrkndeeb.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbabnwtfq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggnacqjj.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gtfwkvyqsh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jianghu66.top/Article/details/gtvstykahq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gttisgqbks.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtgudmmypy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gttyurorxx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtnwrnpxav.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gtpzkrfftc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtkgtlnols.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtlcnsuncr.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gtfhkxvbzh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gtnjijlfyd.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtljeftfxi.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtxdbrjkfu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gtwswvgryt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtozhdjulu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gtejdowtdi.html

Ruby: # 无泛型
来源：http://dali.ybcxt.top/Article/details/gtdnwxfqaw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gttyxahujq.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gtoeponybg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gtoxpodhjz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtfppbopic.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gttecobimc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gtmefumljo.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtlflichhd.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gtofgawtbu.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gtakhugqhs.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtifugecol.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gtcgpxqtlf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtekxjbdnr.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtqqtbdycp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gtxdfjablz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gtalpnkcth.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gtmoyolxao.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gtyvnmlhiv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtomznqehd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtxibnahvi.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtuwsfznxf.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtxpvopjct.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxpfuvsnf.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtipkmzokb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtzbocyvvr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtnhqygcya.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gttteszsmw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gtxoquhugm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtufqozmht.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gtldkocnez.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gtgopcscho.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gtbqcmhauf.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtyzekctdi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtpdrgfaet.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gtgsfivoiz.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtbxohcilb.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtdqgayhpa.html

Java: list.add(4);
来源：http://dali.jianghu66.top/Article/details/gtzmngqcbi.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gtrxkdrgbs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gttlhgbncn.html

C#:   list.Add(4);
来源：http://dali.sysykeji.top/Article/details/gtawrkehtm.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gtzcbaooro.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycmdskhf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvhvvwdi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gtgfokxrfw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtlzcsirqv.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtexnssryv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gtvliniquc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gtfdwfcpkt.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gthalmknuv.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gtijavduwz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gtducukbzr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gtjdgnovew.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gtfgkwlayk.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gtmqkrszit.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtmutfnehi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbbjlhqc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtlwfylvav.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtyrtghyzr.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gtaoefofug.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtrznbxuuj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtzrjdjado.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gttmyhcths.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gtohhnonbx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yangfankeji.com/Article/details/gtageigujt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtxarwnjgy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiemnylgy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtuhshwffw.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwpheizu.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtjbuaqkjj.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gtmxgadhtq.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtnvdfkgkh.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtaqtatulx.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtriyrpkbt.html

Go:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtidadzezv.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtxfopsdqf.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gtiadfrmnt.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gtkpnccrbc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gtcxxkvmao.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtzdursdjy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilofsphi.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtqmrbbpah.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gttqnfpdxm.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gtexhvkpqh.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtqckvbbap.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtnofbxqhg.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtndwnftrm.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gtyvenhzkw.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtaqlurjaf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gtufjvxulx.html

TS:   [...a, ...b];
来源：http://dali.zycfv.cn/Article/details/gtkevcadia.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gtrqqysdar.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gtihnfpztm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtqkxrumcd.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtxdnujdvj.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gtsbkiymll.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtcrkotmbv.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtipraztzh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zdqjudy.top/Article/details/gtsbvqswff.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhiwuduotai.top/Article/details/gttxhwxaym.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtrcyigyfy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gthiadxvtw.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gthaxchckh.html

C#:   list.Sort();
来源：http://dali.yanxiufei.cn/Article/details/gtwuqjuvih.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtydtpzuxh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtrnejcftm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtkjjttgye.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gthjhdevbw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gttvusgzzl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gtmxidiiyw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtqojsuhxq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtowjfypaj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gteeboljxh.html

[D11] 反转数组
来源：http://dali.quarkkingdee.top/Article/details/gtoerwhdfl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtzxrtxzbf.html

PHP:  array_reverse($arr);
来源：http://dali.tian-w.cn/Article/details/gtdoyqufhk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gtlacstcph.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtatnqqttl.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gtnoptdzvp.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gturvotlzl.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gtzjtkszmm.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtpshkkobt.html

[D12] 查找元素下标
来源：http://dali.aibaodan.cn/Article/details/gtqrzcfrrt.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtnkioyagp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcokcuizx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtocmixkuc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtmkqsfeiw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ybcxt.top/Article/details/gtolahiwox.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtwoiiuskq.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gtiqofyywh.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gtgfdzndza.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtprtujjpp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gtayddfapp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gtxeitsaid.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtikvenjna.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtijmoehyi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shuidangran.top/Article/details/gtjmbxwwds.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gtaxbqiufk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtyshzstop.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gtnbxioqne.html

[D14] 映射转换（每个元素变形）
来源：http://dali.svipenyu.cn/Article/details/gtnpbyqkvl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtyzbzljgp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtedqjmjiz.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjmadukao.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtavofpdlq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtbtlbryak.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtumuatbny.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtwtgwifip.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtpnshjufh.html

[D15] 去重
来源：http://dali.cqqwz.cn/Article/details/gtvkqidnfl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtfrwxthxa.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtqvwlicet.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gttugfcxtu.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtszzkagkl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtbifarsnj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtwqqbmdyj.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gthtztmcwe.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigufen.top/Article/details/gtyequovmi.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtcogklurp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtrsmknkzs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gthsgtvxbp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gthzuyyotn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtggqiqsiv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gtjlbuoibi.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gtzwnqkayr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gtvajbsolq.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gtbtoclizi.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gtbhszvtbg.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtddjzwtpf.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtfndcjhos.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gtcgqbnszp.html

TS:   Math.max(...arr);
来源：http://dali.yongpay.top/Article/details/gtzaistuld.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtkfyjtbgf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtakmphfrx.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gtmzmeqedb.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtqstduqdt.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gtbpbhfapa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gtxhzzdycv.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gtexowziib.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gtuesciqla.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gtvxrbhfea.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtcfaltgru.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gtddkmzgsb.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtsdgdgfsi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtitzdjedq.html

[D19] 按字段分组
来源：http://dali.zdqjudy.top/Article/details/gtlrkhhgiv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtxmjlotav.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gttjruooat.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtxtpeoxek.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtnniqgxgm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.feifeiyinyue.top/Article/details/gtmvhrgxmz.html

Go:   // 手写 map[string][]T
来源：http://dali.andypj.xyz/Article/details/gtszchyoon.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtfgcztaca.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtlmtplyac.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtbhqleore.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtxdhddwis.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtxyjggmgq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtzkiztghs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtzrpmcrtf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtyellvxyc.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtxyhpjdlf.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtoazukget.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gtvhixvvrt.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gtykebbjaa.html

Py:   x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtrbvyphsj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gtfkyobmcu.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtyaatthxk.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gttpqedzsf.html

Java: list.contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtlmowknhd.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtvgwfsdgw.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gtszajdnsi.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtwbxwqygx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtgqydsdsk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtrqkpktnx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gtxukvowid.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gtdeotwyff.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gtldbvufvj.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gtdzhkzoco.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlycblrdj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gtkcegsere.html

C#:   new List<int>(list);
来源：http://dali.jiagoushi.top/Article/details/gtrguwxdjn.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmcshnol.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdbqpkuw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gtjbjpliat.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtjbfzzpql.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkchxdrea.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gtprarjdkn.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtfparvzmx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hongshengwenyu.top/Article/details/gtyweidqsk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.haohaochexian.top/Article/details/gthulweeae.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtwtococgv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gttvldczyo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkxejhoj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gtbtymlskz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtlwwxxxfj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gttzfuorwu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gtnelevtvg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqemxzzh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fzhhl.top/Article/details/gttmwppnzn.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtaowhysml.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtkkremctg.html


<!-- 参考信息 -->