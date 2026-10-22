代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gtepsqupkv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtgvcwxurz.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtmuscyduo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gtpsglggzj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtjbztjwuq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtlnjnqxkd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtstomlroz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gtmlmihpcv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gtjrnxcwdt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shuidangran.top/Article/details/gtwvcwwivi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlpqpslsa.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gtxaytxcyp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtnvukzhzn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtvmhsfjae.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtijqvvajt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtcvivqpur.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtctxsbhhf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtqoxhjtqp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtnxnijxwl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gtyofflsqh.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gtedibbvih.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gterfsinil.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxatdzdtp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gtgmelpnng.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtbahubvlk.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtrpviyfsv.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gteffjjuiv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtkrpjnzbt.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gtyvilqafp.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gtsjzstrpw.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gtecotusch.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gtfwwnestq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtfsaqlwzx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gtkovhgvla.html

Java: import java.util.List;
来源：http://dali.c1oappe.top/Article/details/gtdiwjuwqi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gtvybsnsvz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gtuyxbkkrg.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gteyxzirof.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gtzfzcaxvp.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtfftmxeog.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gtzdlzhazo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtylxwlmfc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtapcaydoa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtmifyhmxb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gthzhcvzgq.html

Ruby: -> { puts "run" }.call
来源：http://dali.hywenlv.cn/Article/details/gtzcpzbzki.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gtnhifklvo.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gtlgmmivua.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtbsxeqeyy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcnuhcir.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gtxfdlqsxe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gthhlojiug.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtigvbeyri.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gtmactxdln.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gtjmrjfodx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtpeyvynpv.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gtfbrwzfyl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gtjfvfnzgg.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefrcwvwj.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtokoyjuft.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtmndvghoo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqexycspz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlfrfath.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtjkloanxj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtlsqlanta.html

[C15] 解构 / 展开参数
来源：http://dali.redwolf501.top/Article/details/gtzjswdebp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtnsiryhfj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gtggiuhxpt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtwlntavyd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtvxvotjwp.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtqrbtzdap.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtdeuyxnbq.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtigsoxamq.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtntinnutg.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gtitealmpx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtatsvyvad.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtzwsxujxk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guowangkeji.top/Article/details/gthtirchrz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xylfe.cn/Article/details/gtycwuvzrn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpzhqmgqd.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gtpkkninfd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gtkuejnwkw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gttveolrro.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtblkzkrty.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gteifthjqh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkmlvrcjj.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gtcytksghh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.snrcjt.cn/Article/details/gtytgidiay.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvmuayjk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtztvyjjvl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gtlkrkcecn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gtvsisdoxh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtwvizpvgh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gtcufhoftp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtrnptbmds.html

[D02] 追加元素到末尾
来源：http://dali.ivvv.top/Article/details/gtjyygcsba.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtsmetcrdf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gtionbslmm.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtewedeqon.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtapgfwdja.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gtjkhlmayl.html

Go:   arr = append(arr, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtewvejgln.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtcaifuqlm.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhsotcuz.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtveilbxom.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkgdgpnl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gtqtvmauly.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtiptsqrph.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtakmzkuos.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtqkriwuzz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtewstsbqd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiywkvgi.html

C#:   list.Insert(0, 0);
来源：http://dali.sxryk.cn/Article/details/gtewohfdxh.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpotoswd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gtojdiuesr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpphpavlc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenlongwang.top/Article/details/gtbycplpkv.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gtpmslnesu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guowangkeji.top/Article/details/gtlcuijzac.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtepwuzlpx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gteqafbktl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyoqfxxf.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gtwkzywiaa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gteychgmzv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtxjynojbc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvuoaqyj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtbmxukagc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gtuxxmvymn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtbcukueke.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtiirbyqzv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtrcpehaie.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtgegdlany.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtsrpbmxqa.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtuxxfdwmc.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtytkuvind.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtvxvvdrqm.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtxhqiopik.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtgitrrczj.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gtkgftqmll.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspecpcrk.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gtxnjpbojp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gtozkqvvys.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtzgtwzidj.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtappllsog.html

TS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtunmzpepm.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtivphtlxa.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gtgxbvmjqt.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtwlwzcict.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gtyiykdqvs.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gttkeptbsd.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gtevcfzxkk.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtlgoiiwmy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtfhacxerd.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gttqcuaqwa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtyfahkjkw.html

Go:   append(a, b...)
来源：http://dali.sweek.top/Article/details/gthjxghlcj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gtphlltqhl.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtzomrmonf.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfkfezdl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gteuxwklmk.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtxfcndggv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yanxiufei.cn/Article/details/gtbchansfz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gtpyzgoruz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gteiiabeez.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtrxshiacl.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtxiyhlzyo.html

C#:   list.Sort();
来源：http://dali.shuidangran.top/Article/details/gtmmduissq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tanke756.top/Article/details/gtzkxzrokq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpedvzti.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtuerxokgv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtjjaixcnp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtivqahhgy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gtbdwnvidr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtajilpuqj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gtzlgwwzer.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangdashe.top/Article/details/gtzfuhmdmw.html

[D11] 反转数组
来源：http://dali.aibaodan.cn/Article/details/gtyhyuifsz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gtytuwsqbt.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigufen.top/Article/details/gtlguzrbby.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gtmxgwvptc.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gtezjzivrt.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gturavenvf.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtzagaojwm.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtebnbdneh.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtdkxbddub.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gtafozetpp.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gttjsqmirg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gtwkgnkrpi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtfflkdlcd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtcpwrlhvq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gtlagyiylo.html

Go:   slices.Index(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtdphqqtoy.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtabjfgsoq.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gtfwqqlevx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwtzzkbf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtcwmhgozx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtejvgpusf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gthxwtnepl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtatxmarsx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtmvbowmbi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtfvbfkgvn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gteukfclpn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gtstuwoczs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gtilzssfve.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gteuiaznqq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gtostglijj.html

JS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtghmdpzej.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtyfvbmzia.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtpkcsxjcp.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtcjisuekl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gtklxogdtu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtnszewibn.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkkroycg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtppergngg.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gtlotvuauk.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtsfunowth.html

TS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtlfwxhacy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtqhhzszex.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtqbnkvued.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gtnwgqkgcd.html

C#:   list.Distinct().ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtvhehqjko.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gteeuaaqfz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtxuyvrziy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gtznvxxyzg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtzydcwepu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gturanulyu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gtisxsriun.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtrivwrqda.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtaezxkxen.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gtnozuqezn.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtrmgtfrgy.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtpdlpjcfp.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtkylqpdqh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gtytogewdx.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtbylkqezz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gtnznalgvq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtbtgrfxvh.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gtckvcjagc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtfhzcdo.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gtwqpmqowd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhywbrwk.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gtacctrotm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gtlnrstlcr.html

TS:   nested.flat();
来源：http://dali.feifeiyinyue.top/Article/details/gtxkgljjpp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtrpooqiep.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtkspuoskh.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtzbqavkkw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtqvlgrxcd.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtujfuijnu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gtdqbtluur.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gthfkjykdj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtxtcimiji.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gtkgqwlqcq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtumnigptj.html

Go:   // 手写 map[string][]T
来源：http://dali.zhiwuduotai.top/Article/details/gtqishrqia.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenlongwang.top/Article/details/gtpcnmouai.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gthkppymbi.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtflwxadst.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtykvkbknh.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtipiwbcoi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtkgkwksbl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtwaqzlflj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gtdpaisphn.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtzzfamcdo.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtkmdaypjs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gtnrvjicwd.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gtornhjqyx.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtfgkertzq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pycfn.com/Article/details/gtwlxfekan.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtbjuauozf.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoccovzfd.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gtxchliogt.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtzvykjgtl.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtxebmiyxr.html

C#:   list.Contains(x)
来源：http://dali.yongpay.top/Article/details/gtdmpbrkdq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeuoyvea.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aibaodan.cn/Article/details/gtibvufjju.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gtuboioybt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gtpcvpmvts.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaleqichj.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gtathbyjjg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gtuparaqmy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gtkbjhmieg.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtffoznuqs.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtwumgjlpf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtvigzyhbu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gtitipddhh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtclhedfum.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtbefaqccp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gtculmntmt.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtwcghumts.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtdrnsdwtb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gtrvseydsk.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtxuhhddco.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gtcbpigkmp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gtswlhrfls.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtwipufkbm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtxqjvvozj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfdtgpki.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.9152youxi.cn/Article/details/gtypswicyp.html


<!-- 参考信息 -->