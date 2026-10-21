代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.haohaochexian.top/Article/details/gtqvqdcjev.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtgcwkunom.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtacazdbqy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gtjvioisyi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sufxvd.cn/Article/details/gticahqjmt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtqjdaoofy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtljslhzkl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dianchejie.cn/Article/details/gtnbluzpbh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daria6918.cn/Article/details/gtesqcovix.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gtcwbygein.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtajiteyvd.html

[C09] 递归
来源：http://dali.ydzc1.top/Article/details/gterkrtfcp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtozocssgg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gtgqsdjxfk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtpevttwow.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtkrilsjsz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtxfokqshx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtaqdgllwj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gthjkamdkr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuxming.cn/Article/details/gtuscnjxhl.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtxveakbpy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gtiscgudoi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgfzy.top/Article/details/gtqnuglnts.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gtcgdelksj.html

TS:   同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtpcjtvccn.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gtqozbzeiy.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gtkootlnoi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gthiarbepp.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexzidinh.html

[C11] 模块导入与导出
来源：http://dali.chenzaomai.com/Article/details/gtcjlxppdl.html

Py:   from module import func
来源：http://dali.sufxvd.cn/Article/details/gtxyrpcsnf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gtpkccjmgy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gtubumxuoj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gtskepdbii.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtulapvapd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtpuqguwgw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gtthxxavxj.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gtzoyntnzf.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gtlmpsrdhs.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtmuiwscvt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gtbgrbblwi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtyorhvhhn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtmebpvnsk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gtvezmtcoz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yonumen.top/Article/details/gtlvtjyxli.html

Ruby: -> { puts "run" }.call
来源：http://dali.tianlin.xyz/Article/details/gtsrwzoumt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtyffnmruy.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gtdjstgdex.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gtehoppnll.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtjnywfprp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gtilzfalgv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtbofckyge.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiuozxpe.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gtvtjmehgl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtvhlmrarj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ybcxt.top/Article/details/gtlhxzgbyv.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtxipgnnjp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtiqajpegh.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtmoaewiee.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtqxhvkkby.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtrvxybstb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtspemvnzw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gtjwznwimb.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gtxkyvnghn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gtrcvfaszj.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gtxwdocvrb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtpbopkqfa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gteykuzzfc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtmdaiekcc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gtipfbdzqw.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtsdxfbfel.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtjwrbmvys.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gtchdowtmp.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtgvhsklih.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtnssqgdvd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gtdnhtsxlz.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gtwaomejst.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gtnykswrdq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhongyouzk.top/Article/details/gtdafqubzf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gtputqpxft.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gtewcwnjez.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gtfibrbkdk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gtypmzizie.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtygdlcoje.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gtciuktyof.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmpblhgma.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtfnazxyde.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gtokybzqga.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtdxklllrc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gtxefwyrgl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zycfv.cn/Article/details/gtdznekmhs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gtuxtamgzy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gtegilgqkg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gthttppego.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gtwvyxqlfh.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtjpkzoipd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gtwbqwetpb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gtcnmrlwqh.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtaraajayb.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyvwcfib.html

Java: list.add(4);
来源：http://dali.jianghu66.top/Article/details/gtmooyhlxy.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtdjbjovyv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gtlphlnfwg.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtxgsufusw.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gtcqygjvuk.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtfxrxilbk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gtihcxgvqk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gtbpkldysb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gtrkvhutdd.html

Java: list.add(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtzeoabfxw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtolarzyhb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gtwvswbfgh.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtwocmhfga.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtnwouddui.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gtrrkrkexs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqndeqafg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gtrgunuoaq.html

TS:   arr.splice(0, 1);
来源：http://dali.yongpay.top/Article/details/gtkztsjafc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gtchcsesan.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gtmdonsoxd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtkthaoczw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gtsvwzaoyk.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtppeglpns.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtylrkxlze.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtorsyukiy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedoqudju.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gttdusjwiu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtfjtyuupd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtcjikrvvs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtsclyvbdp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtbijodqcl.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtgscretif.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtjxinilil.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gtbrcrvcht.html

JS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtbkppjgvp.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtcxcplszj.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtrdgfcvbt.html

Go:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtycretlyi.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gtfshgfces.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtsainskgs.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtnizfityf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gaohongyu789.top/Article/details/gtfmgvruas.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtednekqbc.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gttkcvpynx.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtsjpzcxym.html

Java: list.subList(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtoaullsqi.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gtzprxxgfo.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gthmavmeze.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gtpgjuktrd.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzicflmc.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtttvkxfcl.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gtncehziui.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjayiqqen.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gtfgjqkdyh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhixingplan.top/Article/details/gtdenozjox.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtjdkonggg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtxuzxkjjf.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtmcgvwxzy.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gtszfxcvqz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtnlfnmdik.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gtvssvtazz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gttuyjolkj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gtacwacusf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtkrxrarih.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtbjhzufmt.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtaaaubudl.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtntxkaqsl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosnpspvp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcdgwaqy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtsqjpwmdx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtnzllrvuw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjanoqcf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuanzhike.top/Article/details/gtexlrcguy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gtrhgzzezr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gtastvfwic.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtxrzlhdte.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtroovhzjv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gtgtgmdzai.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvaqxggek.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gtsudekpvi.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gtzprgduwf.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gtvixqbeym.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtnnnzfydn.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnyaajsa.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcktvckp.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gtrbxmxrgv.html

Py:   arr.index(x);  x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtuyufvavt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gtjnhpzvlg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtadvypxpv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtupeowuhu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzsaehwb.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtbvmkqznf.html

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gtwdeovqqp.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtprasthmy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxditvzqq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gtchxofeya.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gtpqyjmzgl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtalerwhpz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtltkqgdqd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gtysdqgfwy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtjfapyvfg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtcohjmhmv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gtlmdyxmjr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gtkkrezzil.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gtgqkfyqhw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gtlbldfclc.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtvbzkpusi.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtshokinfb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gogol.net.cn/Article/details/gthiyebgvc.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gthitrldfw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtsdmywhof.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtollpnltf.html

[D15] 去重
来源：http://dali.sxryk.cn/Article/details/gtokbzqvth.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gttamykqto.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gtgltukcaw.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtopfmlguf.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gthhrqzmcb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gtijpddlnv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtremciyns.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gteqcbpljd.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gtswtbfmye.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gtsskfoujb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtojrmypql.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtmuvyeerf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtuogptspc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtanirgvvq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtqnajlbta.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gtixgbynbk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgfzy.top/Article/details/gtqgmgtswn.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gtbrhjzgma.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gtyszoitrq.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtjekepove.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtxqynekzu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gtmphiszga.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlitqbvhj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dashuyun.cn/Article/details/gtkwzszxrw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gtoecudqfa.html

Ruby: arr.max;  arr.min
来源：http://dali.redwolf501.top/Article/details/gtbuazjdcv.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtzmwoqloj.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtvjgtuzxh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenjidiqi.icu/Article/details/gtxyrscjlr.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtjvckoplv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxfxuguz.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gtydeuckbc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenzaomai.com/Article/details/gthcaqgsub.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtomkacqkh.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gtteovnknl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtuzypvbnn.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gtgknqiagm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gtaxzcmbgu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gtjyspkytf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gtkqqlwmog.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtgupwprje.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gttbbexjel.html

Go:   // 手写 map[string][]T
来源：http://dali.yuanzhike.top/Article/details/gtazuxbqtt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gtwjyhyhot.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gtrlnakkny.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gtboqdpxcu.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gtdpwzzixb.html

PHP:  array_count_values($arr);
来源：http://dali.yuxming.cn/Article/details/gtvvyamnob.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtcqhtgyfg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtukgbpbzd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangdashe.top/Article/details/gtcqkljqwi.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtguovduio.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gtbhsolxis.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gthbhkdttb.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gtayssreps.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtisovzwtx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gticxhdjjx.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtptuxigcs.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtplphjxuj.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gtrzwskxxo.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstzkagao.html

Ruby: arr.include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtznayorcs.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtkecqrubd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gtpiayylzg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtelxotvma.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.9152youxi.cn/Article/details/gtdrtguimu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtmrwageyk.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtmdplnrsy.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtgwedroak.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtoxedtzne.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtdbbmtmsa.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtvbtdkxdw.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtweezgwox.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gtjwxsakpt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtpdiuthwx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtmtfiktue.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtmapybclg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pycfn.com/Article/details/gtrgaekpko.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtjxckqept.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gtdgxttiwu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtqdbiqdvi.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtwsvnwwry.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtjpjksfqy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hammf.cn/Article/details/gtnlwikqup.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtpagllskl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtnfjldmtu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gtpmuugaet.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gtfwpupyhz.html


<!-- 参考信息 -->