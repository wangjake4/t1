代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.smart0.xyz/Article/details/gtaxzxsjdk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtewlrpywz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtqxmeemhp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gttjfmmtta.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gtifzuwsbf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gtvtxdqbsj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtxsoitepy.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtedwwdhko.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gthfytkimo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtzhzpnnfj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtvauccuqn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtccphsphi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtbhdtrljr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.smart0.xyz/Article/details/gtvwptyukc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtqqdmqixh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtxmrdylsw.html

[C10] 变量作用域
来源：http://dali.guowangkeji.top/Article/details/gtvlukgctc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gtcqtuttzk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gtmoghceze.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gtxpcfgkdv.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gtpqntnkqk.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtcmekqvjl.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtwjnwoxga.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gtcgirdgfr.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtjufjmtrl.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gtbnrqhdph.html

Py:   from module import func
来源：http://dali.nanxinkj.top/Article/details/gtjmupwnzm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gttmgioffq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtanecekwn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gtobktntnu.html

Java: import java.util.List;
来源：http://dali.mhx1999.top/Article/details/gtfulzduqw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtrxrmimkg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtdyaquetb.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtlfkqpmgl.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtuitboseq.html

Py:   (lambda: print("run"))()
来源：http://dali.jlsjyb.cn/Article/details/gtbckpynpb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gttgfjexso.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtbcqifkgs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtznbrsfhp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gtbeirjnuc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtqloroolb.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigufen.top/Article/details/gtmhijegdn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkarpdviz.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gtaocwceel.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtiuodjuhl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtlfrgjmgb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gtkimekbay.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtrnjvyufv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtpivezqfr.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gtbmeweeud.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtnripftfg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gtjunqymhf.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtyqewkzli.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxouopsg.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtkckzpxid.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtoqtzjyof.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtscfcqspg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtljwyrhld.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtayrztabf.html

Ruby: # 无泛型
来源：http://dali.shuidangran.top/Article/details/gtnomtjral.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gtfykzevez.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gtyazaggng.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gttqdjvvsf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtxkkltwoy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtybxeupew.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtcoazqnij.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gtzemxvgye.html

Go:   // 无解构
来源：http://dali.ivvv.top/Article/details/gteuxxdbkr.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmytmjegh.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtlbhdzpxy.html

[C16] 函数 / 方法重载
来源：http://dali.gogol.net.cn/Article/details/gtuerpygxa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtuxrfyrml.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gtkyrusfnx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gtsgpvgosq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtwiatnqss.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gteeetbvkb.html

Go:   // 无重载：用不同函数名
来源：http://dali.svipenyu.cn/Article/details/gtbadmxdlr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gtgugqrbqa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gtkyoafhia.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gteffhjipn.html

D. 数组 / 列表 / 集合
来源：http://dali.fzhhl.top/Article/details/gtxljabfbu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqourqqvb.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtqeaydmyz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtapqzlqer.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ydzc1.top/Article/details/gtlavhwqqa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtthqbiois.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gthxikzqpy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gtxhxvgwpn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtaumbcydl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gttvlqixbh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gtahvdkhxq.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtlpkbvbtm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gthrnlahqu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gtuwotnoyv.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtkexoabmp.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtealmoelx.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtzllrgkyz.html

Go:   arr = append(arr, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtpmuqpwnz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtuatxfqsa.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtviitjjzt.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtsqglihwf.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gtjgvlbkzm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gtbtspgygd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gtkuosjglw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gtovbfqulr.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtrwzbhxxj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gtmftpilwm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gtmcwhzwzn.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gttfeuepsh.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gthcvurrrp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gtbkjdvzdd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gteppsaiad.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtxtgmilvw.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gtxpexdogm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gthunnugzt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gtiggiyssi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtzpjjpcxd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gtowzdbkgq.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gtbopvvrol.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtclrbemqf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gticmldoqo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtjmnufhuh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gtcxbshgwg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gtekyyqmns.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtdcgblaew.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtkrjfacdv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gttiwyibep.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtmvlxmxew.html

Py:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtfoouimqe.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvliwjdyl.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtvjtgjhvd.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtvmjeisra.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gtzsytgnrj.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtbtbegnjn.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gtzfhgzjps.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtmzzpyuou.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gthpxwxkde.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gtdpbajybi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpziqbjw.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtmqpauvez.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtxjcjywzv.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gthcmirbyu.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gtcqnkwoql.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtsgwujlji.html

C#:   list.GetRange(1, 3);
来源：http://dali.redwolf501.top/Article/details/gtdwwbysvz.html

[D08] 合并两个数组
来源：http://dali.meibo888.top/Article/details/gttgymknwf.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gtlqeyyylx.html

PHP:  array_merge($a, $b);
来源：http://dali.feifeiyinyue.top/Article/details/gtrvbyuphv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gtiogosnek.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gtxutoxdat.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtvhfzrlyl.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gtgbomeuai.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gttnspvanv.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtslgigcfg.html

[D09] 排序（升序）
来源：http://dali.snrcjt.cn/Article/details/gteikeznyb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtaetbpxvb.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtloykoqwk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gtylrhrpmy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcmucabq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gtyittcyvh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtxehpshqv.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtfpozaokj.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfcdkpcu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gtvrckxueu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gthsyirirn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtlktsmwjp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gtzndqzdfv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtpsjtkicw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtgxlzezum.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gtftmjoarl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuxming.cn/Article/details/gtwakrrxdc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cucudq.cn/Article/details/gtfrsvphxz.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtnmppmtdx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gtggyopmaw.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gtunsnmgct.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gtzeqfwnep.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gtfjqegmvs.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gtjplneamu.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtjvpvnrox.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gtitqnuqbp.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtzksrbkpk.html

[D12] 查找元素下标
来源：http://dali.shangyingyoupin.top/Article/details/gtactcoaay.html

Py:   arr.index(x);  x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtedykrksp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtmpjkkkra.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtputsyeeh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtwxxokamz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtnugtnsle.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtzgjspxeb.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gtctlldtra.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gtjlvtsyub.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtciznuqje.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gtwjocjeub.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gtmbzoigra.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gttkisaqhk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthluaalkj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gtcorcwgti.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunuvbajw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtwunhuwxy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xziqi.cn/Article/details/gtadeqyyax.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtttludsxs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gtfaqbaqvw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtabgfppgs.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtwolgmuqm.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtgabhggrr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtgtlmttpd.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtjmiisvuu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtsnhqilbn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtuwgnbehy.html

[D15] 去重
来源：http://dali.cqqwz.cn/Article/details/gtnmlamddb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gtveadicxl.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gtzsrvbqwj.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtgxefxucu.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtolkndllu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtwgapvjyf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtovawparl.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gthaxhhrxz.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gtynaweqky.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gtlvbopqzc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gtvccwsory.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtetgzuscu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtikfxsfcr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtkoxrgyft.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtumyiiqpp.html

Go:   // 手写循环累加
来源：http://dali.xinyue.icu/Article/details/gtlvdofcqv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtpugiyyff.html

C#:   list.Sum();  list.Average()
来源：http://dali.zdqjudy.top/Article/details/gtlzhheivq.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gtvsmfhohx.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtqjiquidh.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gtoncycqss.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gtbrgxlekj.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtgfofjose.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gtbbvfkuzr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtrtgcifin.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccmeznwp.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gtygfgdasq.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdecvgka.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gtwqsccwjh.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gtdkunsnym.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gtguofaaur.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gtckpdxekj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtymhyooej.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtiodzieah.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gthborenwl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtzdliruoy.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gtdyhqdjzz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtszuukpdt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gtmaupatnw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtwckddpca.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtomibfllu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gtjfqsdxwt.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gtwytscnqa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gtrfcsmhif.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gtvdghttpx.html

[D20] 统计每个元素出现次数
来源：http://dali.pycfn.com/Article/details/gtoubjkkca.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtervqfoty.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtajwtfdof.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtfsrgepas.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtnuafavvf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gtfaxnjlwy.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gtmdkhflun.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gtzbcixlve.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtmmeyzcdg.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtnxakjsrt.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtftalezmr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuanzx.com/Article/details/gtivwtshyo.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtmncsvacg.html

TS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtjmibianx.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtyeyalaqf.html

Go:   slices.Contains(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtlvfvtnao.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtkjnocgcb.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtdngrxnsn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gtaqhwrjor.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtnttelkud.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gthixluitp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gtouroqezl.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gtlfoheefs.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gtyfsjollg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gtotxqvznf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtnqormgba.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gtopiganfh.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtoptxvlfr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gtgmkxulcl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gteehhwejb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtvcwmzcdn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaeoipsck.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gtbpxbiyvr.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtduebqjap.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gtqjsopbhm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gttevkvqkm.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtwschtbol.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gtzxtenqdj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtvrznrano.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tanke756.top/Article/details/gtnkrkijwe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtratbcspm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gteppoifny.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gaohongyu789.top/Article/details/gtqlszizhw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gtgnmsaedk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtpxthmcvj.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtgkzlgqrt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gtzmjucrrs.html


<!-- 参考信息 -->