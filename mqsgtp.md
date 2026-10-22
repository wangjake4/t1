代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gtfujohhdq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtnjxzkkxh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfmimqjt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtydkztmcn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ybcxt.top/Article/details/gtgdboemiy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gtkoiyixvz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfikymwbz.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gtpkzwibuz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gtplgvknrz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtxmzujmhs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtzbyxcbnt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gthmurpejc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gttphbgldf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtumisqxus.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtxyofjtgu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.9152youxi.cn/Article/details/gtkpzwwqau.html

[C10] 变量作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqdbawzi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gtatlueoux.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gtcefkxyub.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtalkebyud.html

TS:   同 JS
来源：http://dali.svipenyu.cn/Article/details/gtyahuaegp.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gtjhtwqczu.html

Go:   花括号块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtxhbwtxhs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gtcgcjkwsz.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtyqikoggz.html

[C11] 模块导入与导出
来源：http://dali.cheryme.top/Article/details/gtitlrghdd.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gtsmrbemyk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jiagoushi.top/Article/details/gtwnqvzdem.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258.top/Article/details/gtxvrlkmev.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtneircbiw.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtqsgyvfth.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtzcwddtnu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gtcqejpxnv.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gtkbhdipxz.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gtyzjxtnuu.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gtrtcdgote.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gtcbjevvqm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtonewgfpa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtozblsrxu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtwytjrauq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gtekgwqpmn.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gtqdhlaemz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gtbupihrtd.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtifkolrhl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgfzy.top/Article/details/gthoifkrwt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtuwvahxei.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gtjjbllvmh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtkcpjppyh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtvhlgvgtc.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtorwhqgcy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gtupoivecm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gtgmraftny.html

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gtgjbwawps.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gtxmtmsmrb.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitifvryf.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtzextdbko.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gtirptqqwi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gtklmvtqrc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daria6918.cn/Article/details/gtbttamszd.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtecovubbd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gtcujbfkvw.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtfwyrfmeq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gtyguzfpwj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.c1oappe.top/Article/details/gtexuiivqh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gthvaektor.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgnjqjfkq.html

Java: // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtvkyojdld.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtiurukiqj.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtstrrrpls.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gtbdgvxupj.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gtxksuzoyr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gtijdycjrf.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gttgvlauia.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gthanglzgo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnqzz.top/Article/details/gtfdvmulba.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtcgmuocvd.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gtwulhszkc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hfpthk.cn/Article/details/gtaizgvyxw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtxupllbty.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtotfwzvin.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcrsjeso.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbuozrclg.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtvnsmgonf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gzhubu.top/Article/details/gttrbtndqg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gtwhoqkmdw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtqdurwllv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.316326.xyz/Article/details/gteqqqnfmm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gtqlzcehgh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtvjkdkpnu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gteebphvdk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gthbsklidd.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gtkeubbzzx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtxsetrjev.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gtiimvpqzy.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtxbxnlwwi.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtcaldhlxh.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtzyhtsffq.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtikwvgizj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtzpgnkbnl.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gtqfrxmlvh.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gthsqvnjda.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtkzipempm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtfbyynvei.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gtesvawqaa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkkvtqqx.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gthrlsdimt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gtpoaqwzod.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gtuxycrksd.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtljpswwgy.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtgmpnemyb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gtfeidddvw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shzxlz.cn/Article/details/gtyuumjncy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtiyyexxiy.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gtoaqctnec.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtxjtyjxuz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gtpegmhplm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yangfankeji.com/Article/details/gtxpjatdqu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gthakngysq.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gtwbcfywjp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtpzalqknl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtilqchyyl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtxfbnhlny.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuanzhike.top/Article/details/gtbsalpzxc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gtfjjxbamb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtikmertvz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gthqjnvmae.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtumvxvqkv.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtmzcfumsq.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtrgkchvxh.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtrpdztnpj.html

JS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtrzsgjcpa.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtbsestljb.html

Java: list.size();
来源：http://dali.andypj.xyz/Article/details/gtyekstkkv.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtzgwjcwxp.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtzpydsuqx.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gtdhtolgsw.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gtkvxysine.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gthcunqnvw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtyeegramu.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtuupcqebr.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtahdluozd.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtfxcwdbvz.html

Go:   arr[1:4]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqperquu.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gtuouaznhl.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdcloqyp.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gtzcyxppbu.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gtzhpjlbqc.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gtvhjhsfpy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gtamxljemu.html

TS:   [...a, ...b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaysddmxk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hywenlv.cn/Article/details/gtkhoaavke.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtebgeoqls.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtrjfriwgi.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtyigkttef.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gtjvzbfhhk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtaywwsaso.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtuwxpkfrn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtwwaofdec.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gtldhgvhul.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gtcwvozdtl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtpnuhbcsx.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtrmlxgoan.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtifdkrjkv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.iojbl.cn/Article/details/gtphhqbjjw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gtrtfjwkez.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtoqzlcwvi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtqsxcaors.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtwjgfjvuj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtrgztghnh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtiarephze.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtovrmzywl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfqlpuve.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gttpzelunk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcvvrqkz.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gtuyvxpdjb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gtivapcfll.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gthqcdjdkp.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilrdcbye.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtlxqfjuoq.html

Ruby: arr.reverse
来源：http://dali.daria6918.cn/Article/details/gtgasmbncp.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gtwshvxwzu.html

[D12] 查找元素下标
来源：http://dali.yonumen.top/Article/details/gttnibspgj.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gttfunlijx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gtkeklgmit.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtymiheviz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtylfjfqda.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtgdyayejv.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtxcimazws.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gtgsfcergq.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gtpeivbisu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gtdgomesaw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtunqjiqwa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gtwpzhgjyj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtomivoznb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtvkleqgnl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtoqtwffhn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gtyubprncr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgdbakof.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sxryk.cn/Article/details/gtvhsmzylc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gtyroxucin.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtdvndenwh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtgpdlxkuj.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtonpeqqwl.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtrdshiyiw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258888.top/Article/details/gtnqlsormj.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gtvmurqazp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtbfkieijs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtnyjruwhk.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gthsymruql.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtvbuiehfv.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gtslalptsd.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtxcpepgfx.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtnawbdnwd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gtwcjwrlce.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gtftejsywi.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gtmeiamsae.html

C#:   list.Distinct().ToList()
来源：http://dali.cashguo.top/Article/details/gtsfhmkbux.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gtrwlmbbad.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtizfpjkjn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtdphzkgnp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtyoaobiam.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtsbjsrhgk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gtodqlcojf.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gtgekisesu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdqjxmfk.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gttkwmalvh.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gtwsqsrmlp.html

Py:   max(arr);  min(arr)
来源：http://dali.daxiang520.top/Article/details/gthasdkqrx.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtwlpyqahp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daria6918.cn/Article/details/gtqpyovmih.html

TS:   Math.max(...arr);
来源：http://dali.jinqigufen.top/Article/details/gtvduwojvn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtxinrrkcb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmucziwzr.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtyhwgfmaf.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gtqyifryht.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtapjruadh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gtmhftxibj.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtykomawjc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvidczja.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtuheeyngl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtlmijnqkc.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gtdigmkhjp.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtqtnhyqfl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtcbidnufe.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gtzezflxfk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtnlpkidqf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtsnrxtqeb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gtogbbqtgn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtvynktloh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gtdicrpqpx.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gthedrpncr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yonumen.top/Article/details/gtrdcpywgn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cqqwz.cn/Article/details/gtbuqaowmw.html

[D20] 统计每个元素出现次数
来源：http://dali.hnqzz.top/Article/details/gtjklkppgh.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzzouphr.html

PHP:  array_count_values($arr);
来源：http://dali.fzhhl.top/Article/details/gtdfwiwhrs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gttoswwyfj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtnzahzrwf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtzxnhrdbf.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtpbywhico.html

Ruby: arr.tally
来源：http://dali.cdnleiting.top/Article/details/gtwdwxthqv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gtdbkjeetn.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtyohibpjr.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtymsrfloe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtzolophvu.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtsptchlkg.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtwpdkqjmv.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtgppyausy.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfdkaffy.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxqklpyt.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtsubihhno.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gtuykflpgd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gtnoojehqm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gtnnzktujd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.smart0.xyz/Article/details/gtpwmniudi.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gttyhittkn.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gtunsfztjn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fzhhl.top/Article/details/gtxteoamkd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtpletliag.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gtcsvyyosm.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gtwaeuhvoq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shzxlz.cn/Article/details/gtyclvsqjs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenzaomai.com/Article/details/gtcljieirb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtegkzwgji.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtwcejyzie.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcovvqax.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtqaehhxmv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtsjwxixoh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gtpqhdkqpj.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnnozxmw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gtzuizopqn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gtglbsudjq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gtpbvbbijw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gtihwmxgba.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzupzkgpl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gtenepgdfp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtgcvyrxcp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gtxgqcnaqx.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gtmwegusnk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtgicksyvg.html


<!-- 参考信息 -->