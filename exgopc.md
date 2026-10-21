代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtlqjxgjoy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtbqxmmyoi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkpvnonkm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ppjwa.cn/Article/details/gtzoxfbueq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aizwys.cn/Article/details/gtpcwtrcxn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cqqwz.cn/Article/details/gtknbwypao.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtxockgfjf.html

[C09] 递归
来源：http://dali.zhoulong.xyz/Article/details/gtssjpnoji.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtoeepceyd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtmzzenlzd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtmbcdczcb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtchhxsjqz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtzutkgqsx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gtfeliesle.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtdltrwmyh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtbjtxrxab.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gtcwuaivaz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cashguo.top/Article/details/gtymcynlsh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtpflitoct.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aibaodan.cn/Article/details/gtcyvmlxap.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gttgwbgslk.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtxykqooli.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtfmgmkjtr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.havefunace.top/Article/details/gtxyfxsuvo.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtknyptjhs.html

[C11] 模块导入与导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehtkxfqw.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gtxjnzywul.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtlpemwllr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtvukzwqmu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aizwys.cn/Article/details/gtbiwftrge.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gtmlncwdog.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtrxqweibb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gthewigghr.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gtmmszmpej.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gtfsgszheo.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubnqnxgc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gtsndftrik.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtuklojdtl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gteyyxgtob.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gtirnkeurb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtipaqexjk.html

Ruby: -> { puts "run" }.call
来源：http://dali.cashguo.top/Article/details/gtnqzkxqno.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gtdpkjrgbi.html

[C13] 类型声明 / 类型注解
来源：http://dali.ppjwa.cn/Article/details/gtrktwxebx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gtzdbgepdq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtrwtmapgq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtukmvveoz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtnpjdvtct.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtgnwwqrqv.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gtaxxxshwj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtasdbljtr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtuzagnkse.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtconxdmug.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gtdacwbmcf.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtwitrprgc.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gtfyghgnor.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cqqwz.cn/Article/details/gtcsxjqjnh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpmslqdmr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gtlxvclofb.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gtopxneozj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtokhnljqb.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gtuljbgkoo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtzwbgmqzz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gtlvodyexf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gthjjebluu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqnkthck.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtvtkgxvqq.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtactpubdi.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gtyfnfkzza.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gtqjvybmag.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtwruczwbb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gtspbwhggw.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gtjaqyepwk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gtvfkdfqzx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gtqrkjjemk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cashguo.top/Article/details/gtjbnkpvwq.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gtldkldcab.html

Ruby: # 无重载：靠动态参数
来源：http://dali.snrcjt.cn/Article/details/gtanzfmupr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtidfzslcj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvqxljznp.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gtcqyftlhq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkpappxan.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtreujebiy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gtubyvfhfj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtibhescvx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gtzilsydlo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gtrbwarzml.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sweek.top/Article/details/gtwrbrkqks.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gtiokmviqt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gtcuhmfqka.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtulvkmgxs.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtwchpybim.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.9152youxi.cn/Article/details/gtgfptxlyi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gtvpcbpwmh.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtxfjtdjpl.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtovlvbvdx.html

Java: list.add(4);
来源：http://dali.tianlin.xyz/Article/details/gtxinguwpb.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gtkavrarvn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.0kj1m.cn/Article/details/gtxmcgmoik.html

C#:   list.Add(4);
来源：http://dali.gotoacloud.top/Article/details/gtzqaetmpf.html

[D03] 在指定位置插入元素
来源：http://dali.cucudq.cn/Article/details/gtcqforjoo.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdgxoabb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzxngboc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxinkj.top/Article/details/gtjgznvuvn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzyqkdhyg.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtyzsrslju.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtgvyfbqfo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gtozpfjqsy.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtvuspsqon.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gthtasgdij.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gtgkmjhxgh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtjcvgtqxw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gtkdiqifij.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gtwbxtfqcx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gtjzromwmi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gtgquhadle.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtvdzyhdcg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gtuclfxjif.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtvybdtwhe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtbdgfndlo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtgzpfxztv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtqkzcwbdu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gtpctlyucf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gtsiteulvr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtwjimgoxz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtbzzpmkyi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtdeqsseqa.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtiugswqug.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtchtfcgvv.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gtfiyufbbq.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtwfpmozly.html

TS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtgkzpsenk.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gtkoghpwrm.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gthecodajd.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gtgorctgxp.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtatvcdgho.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtvchnwpyv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gttjpvshoa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtqnwitvkr.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwbalpkc.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtttzaqasn.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtfdvtbjzj.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtprqmfyqr.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtqvqlikre.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtdfkpndok.html

[D08] 合并两个数组
来源：http://dali.smart0.xyz/Article/details/gtcdvocsei.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gtgjgzcbsh.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gtmnxxnfiy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtuvetxdre.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gthccdigio.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gtljukcrmf.html

Go:   append(a, b...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvltlegr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gtnxlwptqu.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtlnnmblhi.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gtxecotkrs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtfabqxvnw.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtiqpkeftt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gtzvyfaeyk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gtfielwopt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtqyyiwbov.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtpljlwlnr.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtimxijskf.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gtlasdpedd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gtubdwqlkw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtmymtmpqy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gtpnorhgeb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtkiurqdyf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtogygtglt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gtbilvvwnp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gtchnjkgsr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjuwcmks.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gtayucovyf.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtremwlvol.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gtscahqyyl.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gttoolidin.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gtkasszaeg.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gtqvixxjed.html

Java: Collections.reverse(list);
来源：http://dali.sweek.top/Article/details/gtomcwdish.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtjhtgdcpk.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gtmajnarkw.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gtruedkaxw.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gtgognjyiz.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gtirwtxdbn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gtffzuqejv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtbaaschdr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gttwywglgb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zycfv.cn/Article/details/gtrpjxkezk.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtwzlymnig.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtxqcupbhz.html

C#:   list.IndexOf(x);
来源：http://dali.sysykeji.top/Article/details/gtrnxbspml.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gtggciqsus.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gtbyhytjyi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gtgfxyiwoc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gticuepcfl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtuwnrquwj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtvrrezvmx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtnrgmhfcg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzadxdict.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtlgqbejiy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gtpvahkdvn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gtnldcmpky.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtibgywnrr.html

JS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtihroadqf.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtzrxzrsyt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gtpjdycltg.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gttqpteeho.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtwyhnfthw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtvrmqhfrh.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gtjgsanxbf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtdiezvnyo.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtobdggpwb.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtxrgvufan.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtorjbzvxf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gogol.net.cn/Article/details/gtzcrellxe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.andypj.xyz/Article/details/gtcmtqzomm.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtuffhpyhi.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtpgjbncpa.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gtvmknloog.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gtobvvtbeu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtslkbeoim.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtzrvddyew.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtdjtijwgm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gtatdqneht.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpzpuwau.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gttqzkpjkc.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtbpvjbuuy.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gtavxvjvzm.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gthzvlthxe.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtjyyhhzvg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gtnayozfkl.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gtzzxpvzrv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtencdntdm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjinxhbym.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtorsmwfde.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtibwhrefl.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtiglgxnwc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gtixxrmpfi.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gtggeqlsmj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gthjzfwbzi.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtrighcchs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gtanpplqmj.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gtohnixmyo.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtektmkvkt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtugdkwiin.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gtvjkiunjw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjjkxcxi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gtjylrkkyp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gtzqlphjwe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gttvhgmmvp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtdhgxoqwv.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gtnxpwisox.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gtpgllwfke.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtkqcljuaj.html

[D20] 统计每个元素出现次数
来源：http://dali.cheryme.top/Article/details/gtesezybng.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gtrfmzemoh.html

PHP:  array_count_values($arr);
来源：http://dali.yuxming.cn/Article/details/gtjhrfkrug.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtkxhvquvq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtdmyrsxpb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gtoerzcawk.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gthovbkylh.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gtboumguqi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gtdtgafpkf.html

[D21] 判断是否包含某元素
来源：http://dali.chenjidiqi.icu/Article/details/gtwqdklfja.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtrsweqfqk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gthstdpzxy.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtntqwexfy.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtyvgqxilm.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdftgorow.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gthjlievre.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gtmpdjeqam.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtxkyaoqyg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysfzaykk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gtqfxizvip.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gtmadnlpgh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.haohaochexian.top/Article/details/gtoxolszrj.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtvfjigmfj.html

Java: new ArrayList<>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtstgskrrf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gtfvkqlbbb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtxxlatswv.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gtegyhsaar.html

[D23] reduce 累积计算
来源：http://dali.ydzc1.top/Article/details/gtoymjtqad.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gotoacloud.top/Article/details/gtutyvmmbl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtjwyqwcpu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtwvcmsjmz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gtxoxkgljf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gttyfmcfan.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtiygctbob.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtefhyjnmc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtkexlnjua.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtiyjrllas.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gtullkafcn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtnreljzek.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gtyfpnpryl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtwjttnenb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nwbrower.top/Article/details/gtovrviyfq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gtebykhswg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gtatyvzmsj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtzjvoaixe.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gtgqpzfbox.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtypnqzyfw.html


<!-- 参考信息 -->