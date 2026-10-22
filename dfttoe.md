代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ybcxt.top/Article/details/gtyiyybjkl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gturvgigta.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtugdgfwhc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gtfvvnnpts.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.c1oappe.top/Article/details/gtupgklfoy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtucpelmtv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtysynsdgt.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gteurhfcnp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtoxsxijwx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtlhsgyqit.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtnezxlykf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtewvmgxqb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtxacvwqfb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtdyuplzzy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gthktjjtqq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtgtcryknx.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gttijanond.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gticuxnghg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pycfn.com/Article/details/gtvgasvmmv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtivblxvba.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gtwiehfvsb.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtsuswmlab.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtfywmilpq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.quarkkingdee.top/Article/details/gtjpnbxiwf.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtzcjnaopq.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtozlbfqvu.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gtxtxxopsl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gtswwumvbr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gtsufshele.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gtmiurbacb.html

Java: import java.util.List;
来源：http://dali.jinqigufen.top/Article/details/gtwwewrfly.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gtyeixdxtb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchoozpkf.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gtkgjgwrjw.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gttivcayvq.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtcoxefkyu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.svipenyu.cn/Article/details/gtmpcflrkv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtosigeufx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtkkimizxz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cdnleiting.top/Article/details/gtsidkvdhe.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtsmmeqqax.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtbntqlkws.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtiicgbvjb.html

[C13] 类型声明 / 类型注解
来源：http://dali.iojbl.cn/Article/details/gtofubxrba.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gtggqozgvn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtoqbdkpmo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtuqiiqofe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtxtneeslo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtofyqxbri.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gtovowpldi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhoulong.xyz/Article/details/gtpdchfvjf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhengqikj.top/Article/details/gtulmcovlk.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtmywjtpzi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtcitkgaik.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtwfofsnxi.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtevhhvysp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gtqtbeqpsp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gtjurvchxr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtuyrbghbs.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gtzukjiwzy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtjsshqaos.html

[C15] 解构 / 展开参数
来源：http://dali.hnxiangtu.top/Article/details/gtgeyqygsc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gtpdkzlinh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gtubnpytas.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtywcocunz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gtnfmnmhul.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gtugfqbiyc.html

Go:   // 无解构
来源：http://dali.c1oappe.top/Article/details/gtpsjdvwmj.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gtxlbiodcd.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gtajdhtcga.html

[C16] 函数 / 方法重载
来源：http://dali.fengsongda.top/Article/details/gtbqttcxpi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gtqxyfmazo.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gtlnnshnuy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngrfddbb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtnvbzgije.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gtccjxrcme.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gtgphwumvs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sufxvd.cn/Article/details/gtrvbphlvp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gtfnrsexqt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gttrtelnrr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtobfsimfl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxecgcsxy.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtnblnzryj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigfzy.top/Article/details/gtgvatmavk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gthtxlxcug.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtairhhgup.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gtohbyjdky.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gtklhuuzgp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gthecficsk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtpbtiljwl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gtbrncbgbc.html

[D02] 追加元素到末尾
来源：http://dali.aizwys.cn/Article/details/gttfivnkzi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ywan-chungtsiang.top/Article/details/gthauzpntm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtoumxykbf.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtwpvnlldk.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtwrjemqvg.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtdcmklkpp.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtrhntpxti.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gttgbjmtsf.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtgdomuovw.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gtglikraox.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gtvkyuqadm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtctohquup.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtdqoycody.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtzvizgzzm.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtzazzcosb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtmxijsppp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gtwzvfpbtw.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtbiotvvvu.html

[D04] 删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtvldeguyi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtdehemjgm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gtegkyxpdw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gtibdtfmdr.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtomfyrrli.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gtglbjycwz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtsknrlgls.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.smart0.xyz/Article/details/gtpgzrqxmx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gtyuibonma.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gteiqeedqh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gthinwqibb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjikbsfxj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtpeovgrgn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobdioisn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gtcbctnyuu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtrmlrosgk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtleiabkbe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtcgacphiz.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtyjllvypx.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtgkgckafm.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gttyxxisgx.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gtzvpotupq.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtswxvlyos.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gtpvidaqmn.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtrfmsbnug.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gtkzlltfdi.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gtgvsiuegd.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gtsuxuoxte.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsihzmlu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtlopalbsi.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtbsfqzjwy.html

TS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtdbsfmaja.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gtyezxxkat.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gtwhxekvqg.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gtbhjfvkfj.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtoguqqshd.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtkrmjtsnq.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gtnhqdkavz.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gtonclgnrb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gtptwtslqf.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtajqrpdyl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtynvddatr.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtkiytougu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gtrgjfcicc.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gtxnosrmqw.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gtpugatrog.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtljeygtya.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gtgiqillzp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gtmexobpxs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gotoacloud.top/Article/details/gtwqbykjdm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gtkwqhnxcf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtwrgetqkh.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtjosegpso.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gtqioovvvy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtixneihdj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gtgeolmqwi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtvdezjifh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtpgswfkpn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtntukoato.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gtnlxjugfa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gtnabgzoie.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gtsgrvphem.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gtuoqlzpim.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gtkvipgvzj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtghofybit.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gtzqpohwmx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gtglwuhuah.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtnvmalyyr.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtwnsmazre.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkdrkhgx.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtozxiqase.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gtmxekoond.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gtveqfwize.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gtooflzgkm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtmmhcahlo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtuwfaunyr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtaegmndui.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtyiqiogph.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gtxnwsqvdd.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtitaupujy.html

C#:   list.IndexOf(x);
来源：http://dali.hysaishi.cn/Article/details/gtndkyvbni.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gtzqzjcbgv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gtdamlzazy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gtqrkkdhqn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtaksbzist.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtdmrtelje.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gtmptgsucw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gthhvedkbh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtchamscjz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtojkwmqlw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gtsxnieagr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtzquqywqz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fzhhl.top/Article/details/gtlodplyxw.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtxtfkadzf.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtogmzmfsr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtrdzjcpgn.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtvnrempih.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtneaebzgv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gtorsuggkj.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtljrwupux.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtganaerme.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtavmjjnyy.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtnsghjpkt.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtfkbicopy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gtirrtudms.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtcmgaedmw.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gtpyhvlgad.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtpoxmcfgt.html

[D16] 求和与平均值
来源：http://dali.nanxuanxn.top/Article/details/gtzhkpeabt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtwbnlmckk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gtrpcrqxgb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gtofbbfmar.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gttbcvtfuq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtghfzolfv.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gtnyoveavd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtdtorqfny.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteepblabf.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gtemrxkpce.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gtakeivtot.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtihsxatcz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gthqkvzimb.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gthsapypgv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yueranfly.top/Article/details/gtujviclkf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtjtvplpvd.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtrpeazulh.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gtifdglyjl.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gtdwnmfeww.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cheryme.top/Article/details/gtstiemubm.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gttyllzjor.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gtmmfdvqzp.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwhklfxy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtclhrtdby.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gtpwpvrfqv.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtmjumrprc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtvicndmil.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gtfwenzqwc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gtzfyjdrlh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gtmhkzfabe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtmkbbjoml.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gthcggypat.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gtdjawipkp.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gtxwhskwxa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtoudrewqa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xziqi.cn/Article/details/gtrqagzqga.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtouehrxmu.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtlzppvawn.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gtzwquilrq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtzzkyeeaj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gteenxyepe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gtjbastlrm.html

Go:   // 手写 map[T]int
来源：http://dali.jyoumei.cn/Article/details/gtsqcsasuq.html

Ruby: arr.tally
来源：http://dali.cdnleiting.top/Article/details/gtnejhhxtt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gtiveircbl.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gtbenrdgul.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtseppawcc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtpekwlrju.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gteawzjulh.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtabfdtfub.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtxnwcgoiv.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtkacbgzve.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtsbgnxqhp.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtamwliwut.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangtech.top/Article/details/gtoppmdqfo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtdscgyofp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtpewmsimj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtxellxbmp.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gtrmwcdkby.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gtmaxhunyc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtebhfabnz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gtsfrubrpz.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwbrcbei.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gtrcwhgeau.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gtehvjgnew.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtxwtoahrr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtpxrrssaf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtttnxmehk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gtewbindnt.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigmnimxq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258.top/Article/details/gtabgikgjv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtoezpsryn.html

[D24] 字典 / Map 基本操作
来源：http://dali.vqdsnc.cn/Article/details/gtxpykzogp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gttmkhyenn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gtceflkxra.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ehwqpu.com/Article/details/gtcjwoqcwk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtsqbhjnyb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shangyingyoupin.top/Article/details/gteehgdpup.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gtjbxmgyln.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gtjydrjwid.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gttgtazqpo.html

[D25] Set 集合去重与交并差
来源：http://dali.nwbrower.top/Article/details/gtjmaxovex.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtzgigaqrk.html


<!-- 参考信息 -->