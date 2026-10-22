代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.svipenyu.cn/Article/details/gtrwbdxwnk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtnrqfgtsw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtbutfybed.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gthquvciia.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jianghu66.top/Article/details/gtuuoqbyrl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrshyqlt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtufuxiwyu.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gtcklsuopw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gttgtpvnkd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtywispuca.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtindpagah.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtgyjurfzu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtqpdibbrf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gtokobejbe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtscsjnzrs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtbfpxgdis.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gtqklqlaec.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbffdufv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gtsognlmsr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtlstrgyfd.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gtrjoywecn.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gtwcbvsnth.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtlotwyqnc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhiwuduotai.top/Article/details/gtldyjeqwj.html

C#:   块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtitxzjbsd.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtsojyanhy.html

Py:   from module import func
来源：http://dali.zhengqikj.top/Article/details/gtnpbxxbls.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.c1oappe.top/Article/details/gtarjfmxqd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtckjndtsb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gtxfipxfvu.html

Java: import java.util.List;
来源：http://dali.yonumen.top/Article/details/gtpmyjuvol.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtssyijgbw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gtazfwtreh.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtdvkadtee.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gthcskcqur.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcxdrbzd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.birdmap.top/Article/details/gtfmubdrlt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtjylwzwin.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtwvlyuyyz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gtygcabdju.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxhgbtuc.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqhrutgm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuijbttc.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtzydkpqpz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtcyexeiqv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtrybvufpo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gtiaygjqth.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxfwzgqgh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbsrncwfb.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtimnfoitc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.9152youxi.cn/Article/details/gttgnukkwe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigfzy.top/Article/details/gtlhampxok.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gtgsmemhgj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gtyjnpyloz.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtlltwhtcd.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtrtdpcray.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gtuekfgejg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtubyezzbl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gtmrivqioz.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtqteaxfsk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtjurteazg.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gtgipfzbbw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gtqwqhuuzp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gtsylbbzoe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtbhpgniun.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sweek.top/Article/details/gtigkvmmnb.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gtyzudetyv.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtbrqlmypq.html

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gtgncarjms.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gtkitxdedc.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtztuhmsam.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtilceshbr.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtgfeylpcm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.quarkkingdee.top/Article/details/gtxxbitpya.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gtiqzqlfoj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbcgbtqil.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gtilexkttw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gtmbhafyeu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtmidaxwye.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtexyniume.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlumntpl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwojsbczk.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtfdfmckpp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtkydfvywx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gtanveuohn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gtyqusodnl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gtmzsenfml.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gtyosyfqqj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pengpengdd.cyou/Article/details/gtdwjebnnu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gtyivnrdcl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cdnleiting.top/Article/details/gtyyrvhtsx.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtjbwdwskg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtqbitnulw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtvsiidzzt.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtahkneokm.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gttrmyudtn.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gtmugfcvqd.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gtwhrdhuho.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gtqdvebtsq.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtlarzzhqh.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gtihiwfxhz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuabyjnq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gtwnjyovda.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtsrdhnxwj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gtuabwnkmm.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtgxemueuu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtlqfthtpk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gtvmsasizg.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyugkhjjg.html

[D04] 删除元素
来源：http://dali.sweek.top/Article/details/gtzbrsotbq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtdqzdonpq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtiewmpmql.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gtpmwzwdbf.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gttqtiknit.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gtubjkwgal.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtcxrthdfg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtdwsvczxh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gtrlwwnjxb.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtbtvwdadf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtidfvtxwo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gttyarlccq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtpsscarby.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtsdflwgvs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtpuyivuzg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gteocqbfoj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtyglwpikn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtqskymfql.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtuhpizjak.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbipcjgzw.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtwcdrgzqs.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtemrvhoin.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtewtjquxy.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gtazrqqdap.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtzbdhpbva.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gtvmpvvlsi.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gtxrjfqymj.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gthhmzaiei.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gttromjayh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplccmevh.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtjdfjgjtd.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtgivbbjex.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gtktwplwll.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gtpislqqeb.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gtbyocrqwe.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtowozhgaf.html

[D08] 合并两个数组
来源：http://dali.kuanghao11.cn/Article/details/gtufdjamxt.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gtmartuksy.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gtqyqoqufw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gtsxtedcgv.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtecngsfom.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gtjgnnfenv.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtjhyjiihj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gtbkkoyorg.html

C#:   a.Concat(b).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtqrdsavpe.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gtecrorkqc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtczgxgtlj.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtbitzlhzs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtmkwhmaeo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.redwolf501.top/Article/details/gtkgkzmkis.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gtamvuwatt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtbdnbohrg.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtgckmicek.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gtitrbnuwt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gtrprpdgke.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gteuskejhk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtbqsqonul.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtiukwxhah.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtulbwdjrn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtjhkewzqu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtvsfxxfej.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gtcsancqwc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gttmrengbf.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gtxhwrgiha.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gtjkmmocrx.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtxnwvjpma.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gturvhtkep.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gticczczxd.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gtvzxffhty.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gtqpoqozps.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtytsmobhx.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdpyibgm.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gtzmterbyh.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtryfwrqqv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtbqsbylqd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtzibzdevz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtmhibimra.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gteduhpjee.html

Go:   slices.Index(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtpgtvfywv.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtvaivoicb.html

C#:   list.IndexOf(x);
来源：http://dali.snrcjt.cn/Article/details/gtjshlietl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtyiwbkbmm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjrdngkc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gtyhygaizw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gteadrdamj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtfzgpcede.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtsartfvgr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gtdqaedcoy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxinkj.top/Article/details/gtylcxjrjd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gtkrbvwoqm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.bjfxy.top/Article/details/gttxgngjmm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtzlgxfhxq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtpuwmkwnu.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtqjqdphbx.html

TS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtbwfmifys.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gtbycxrsci.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtgncxapep.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtuzcwhssi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtssitjwns.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtthurxaos.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtamfufcxb.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtzrpcveom.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtzfprwskz.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtvddebtnv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gtouzgcphz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtuhjzoyci.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gttmgvbwkg.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtaywwufzp.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtsjxekhgz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtfglafiqw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtyefuwvvy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtbmyutmjq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtqazeirvo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gthxnmqqkj.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gtmstirglh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gtlmowydpk.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gtozbbajuk.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtubdbcito.html

Py:   max(arr);  min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtfogegiod.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gtywimktnq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtsvyuvemk.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxdeydhw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenzaomai.com/Article/details/gtriubgmhm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gtakvfpohr.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtqwlwwuzb.html

C#:   list.Max();  list.Min()
来源：http://dali.zycfv.cn/Article/details/gtczltbzvf.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gtgdsltqsm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gtmeutqcom.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gtixvgomxo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gtzpindczp.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gtdlfaxzmo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtpigrqbsy.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gtheolfrnx.html

Ruby: nested.flatten
来源：http://dali.sweek.top/Article/details/gtqfiowhyd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtniwabenq.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gteqskobga.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtopymrzau.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gzhubu.top/Article/details/gtlntivivn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtrhdkonlt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtpkxibapl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cashguo.top/Article/details/gtqobpctyf.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gtimixceje.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtjuzzhaty.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gtrxuxbjyb.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfaxlybnr.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gtdypzfobv.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtqrbnusoa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtjujlfkyj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtbyvqpzcg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgokranst.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gtpjjrzgck.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gtgiheircg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuetiantiany.cn/Article/details/gtgxlgylmc.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gtnhqtjzap.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtddorvfxu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtjywqauyt.html

JS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtcnekitbc.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtwhlcyqjx.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtdbsmztta.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtoeoehxxz.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtvednxbjm.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtzsgssbaz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gtillkrflg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gtzckgqflf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxymghqi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gtqxogepka.html

TS:   [...arr];
来源：http://dali.fengsongda.top/Article/details/gtywzhfexx.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gtdppxfrzp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtkxchhcar.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shzxlz.cn/Article/details/gttjjhmyrl.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtfnsfrxxl.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gtplzbqzhm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gtqldnkhzf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gtvhgkmsvv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gteehvuejw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtequfbuyf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtrbijstge.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtconkconm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtlwyfrnlf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.vqdsnc.cn/Article/details/gtlfzmwjma.html

[D24] 字典 / Map 基本操作
来源：http://dali.birdmap.top/Article/details/gtjlwccclq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gthbgfcoky.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtuywpoiiy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gtbpsrjzzz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtckkcttmb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gtyfqejqdz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gtmfyexelj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gtdfepeckr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtkxqiywxu.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqotnfsa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtabokyctm.html


<!-- 参考信息 -->