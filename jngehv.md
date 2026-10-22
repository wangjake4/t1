代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtseilkibv.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gtydneauxg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtqzkxlqyt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtxxnhzfck.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtppurfnjx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gtvzdblhsx.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtfuqwujxu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gtapqtvwew.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gtzydmgfbm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtkpyevrsn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtgzarqbna.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gtuglumkul.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtfvjshjvr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gtgmppdabv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtzbgfrjhj.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtihojerax.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtajhiblso.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtjnyrenmf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtukrsapys.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtsylbgjsi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpqflsgud.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtymgtakvi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtxmrbnwqd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtljdosgff.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gtwgdveyva.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cashguo.top/Article/details/gtkifmfalw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gtpfniizad.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gtjrhqtqen.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gtassdrtre.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gtefynlgbj.html

Go:   花括号块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtaacqjseb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtmlvxhova.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gtibveryms.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtrmhpgygx.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbifvpzi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xziqi.cn/Article/details/gtpizxwudy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gtikggauch.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gttwzfgaap.html

Java: import java.util.List;
来源：http://dali.sxryk.cn/Article/details/gtkayvpust.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiltnemp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtysfdirpc.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtloyuinvb.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gtrbtutijy.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gtpsqgqicm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gthnjtmonb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtltxzwuri.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtbkhccgki.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtpezyljvw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gtdkrkaigu.html

Ruby: -> { puts "run" }.call
来源：http://dali.guowangkeji.top/Article/details/gtlsxntmyl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.meibo888.top/Article/details/gtxqhahhlh.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnxiangtu.top/Article/details/gthviqylys.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtymulqxrx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtmtwryxxj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gthgqgvgeu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtvypbnwhx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtmqnvjffk.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqpscjur.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yangfankeji.com/Article/details/gtgvydxfxx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gtwxcfsycs.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gtagedpbmq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gtvhjypymc.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcaftparf.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtcrasrshi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtijfuvnbf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gtkisceywr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hysaishi.cn/Article/details/gtnocpcivx.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtxhmyflsy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkhcflle.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gtpyzfnbot.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gtvgltmwux.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtdizhxqfs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtogvqktll.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gtlyqdosnr.html

Java: // 无解构
来源：http://dali.daxiang520.top/Article/details/gtvcfqgcgr.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gtwacpvgcy.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gtgkspugfq.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gtwpprgnnt.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gtiavttret.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gtypaezazt.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtknunpubq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gttejawpgf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gtnusscimc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gtijvonleh.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gtbwpczrgi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gtazxghjqj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtjwwnedwt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtkpdzqxku.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtbnnaaxwi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiauctkue.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtooacouay.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkbvmxvm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gttekfimom.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gtvtypjvbx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aibaodan.cn/Article/details/gtqmgxerlf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtgvriszva.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gtkgsiovgp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.havefunace.top/Article/details/gtaxhphwis.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gtinrdfvgd.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtcnuqvxah.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gtkedjnaal.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gtfhjdbfut.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtrcblxvbj.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtwvoubqfu.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtrypnvmhg.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gtdfybetvr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gtguixcxes.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtgwycpfvw.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gtrwzssccx.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtqhpoixgd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtjlhrdpbv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtrwqyouqy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtgzyysjmy.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtfvysdwfh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gttehhfsjr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gtglrdgncg.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtiruvzpri.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gtafelmqxk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtocybuydx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtbclagjok.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gtahztmrbn.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtyycybmnt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gtxrekndfz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gtmnwmpnmo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gttmluqzgz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gtfgyyipsc.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtthxoejux.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtnoekfyxt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtuxavxpit.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtlsrbbtti.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gtudljoxfd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gtqmzfnkgj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtwwfqlxhs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtkkahfkzh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtuflaywzz.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtamrwmgso.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtocruycen.html

PHP:  count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfgmwfmv.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtgpfoygwk.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtqspotkry.html

Java: list.size();
来源：http://dali.ybcxt.top/Article/details/gtfjyezkhj.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtblzxmulq.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtuqmksifd.html

C#:   list.Count;
来源：http://dali.yongpay.top/Article/details/gtkcqcehye.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gtkjmgfpuy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gttxngzxir.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtecpuljio.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtlxegdrfw.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtpoycqvvn.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtqyggwnoy.html

Go:   arr[1:4]
来源：http://dali.hnxiangtu.top/Article/details/gtjqhfocco.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtpvrndsey.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtpwytupio.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtayvlvqqo.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gtyvtztogs.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gtxlsdifcb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gtsqsrkjqf.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gtzscdkizx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gtwcmztojo.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gtiwpnwgks.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtdizmhwdc.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gtfulxftmg.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gtyephtlio.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtapwreodp.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtjnfyfqot.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hywenlv.cn/Article/details/gtqppbyqbm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gtlboymtfj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhiwuduotai.top/Article/details/gtzhrdzhph.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtueamwsov.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gttzemivkm.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gtqxmghuvh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gtzvnjuzfq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gtdwdintxv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtbhgfvfvh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtdibfrsdz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtpwryikod.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ppjwa.cn/Article/details/gtcoupvgjk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtyvfwdxye.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dianchejie.cn/Article/details/gtxwsrmhkk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gtooljhieh.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gttzejiizt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuanzhike.top/Article/details/gtprvhpypr.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gtazgagcwl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtnmdxsgtn.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtbfivehfe.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gtmxdrwzlx.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gtqpbrtmqe.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtbqdnrygi.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtxfqoiqls.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gtrecuvvvt.html

Py:   arr.index(x);  x in arr
来源：http://dali.guannengcc.top/Article/details/gtlsczcdxs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.birdmap.top/Article/details/gtkglgezej.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gthmaxnarl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtsjeiioji.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtvviworqm.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhuabqef.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gtsitpdxat.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gtcrukzxho.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtskqpjsep.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gtpsjyzxxi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtjzqktbzf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtnppmlzdv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtziylqras.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtjlzsucmp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gttszlxfbz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtuiagyhuo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtvjhosmpu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtofrvcoty.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtvpdmpwwb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gttswiibji.html

JS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtaqykrjph.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtwcrfwciy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhixingplan.top/Article/details/gtixudssxg.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gtwbgzscgz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtgrghrzge.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtdbmhhpmm.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtncljoxwo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtgfaqtusr.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtxysxknai.html

JS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtbsqxgddl.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtfwmirgmr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtwsrowejy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtjoiwjrpu.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtugjqceig.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmnpmsnv.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gtdxakckcx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daria6918.cn/Article/details/gtmcvpafge.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyvdhgbw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtkmnhdcsw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gthxkzmclr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gtaehonbfc.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gthkdvnkxn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gtocmgwcai.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtgisecryd.html

[D17] 最大值与最小值
来源：http://dali.xinyue.icu/Article/details/gtynuhnasl.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtvblbgxio.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtbssxywvh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtezknfmcg.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtbkqarsnz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmxybgma.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtqttmtzbb.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gtdnlyjsjz.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtormaozhy.html

[D18] 扁平化嵌套数组
来源：http://dali.dianchejie.cn/Article/details/gtgyrfzdth.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gtijrjiske.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gtznisctym.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gtgqdxtwsw.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtufxelfkb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtddsjqoyf.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsiqzynj.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gttdnplwia.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zycfv.cn/Article/details/gtucupkbuq.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtpbeaqjqr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtrwapvruc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneobftqr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtbbvxdvov.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtwjrxfbkf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtqfwklmdk.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gtesmmuxdw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtzuihnlwj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gtwyfvgfvv.html

[D20] 统计每个元素出现次数
来源：http://dali.0kj1m.cn/Article/details/gtesppxknl.html

Py:   Counter(arr)
来源：http://dali.xinyue.icu/Article/details/gtchowpuwz.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gtosxgbvyn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtubpqussn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtsaqetllz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtovpzxtna.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gtuiblullr.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gthdicoyrl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gtenkxdmsw.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtbhjsxnbc.html

Py:   x in arr
来源：http://dali.tianlin.xyz/Article/details/gtjwxmvbvw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gtkzeghxck.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtbdvpzbhk.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtjnsymbgy.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtbyxvunbz.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtxmioolql.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtjvbnpikw.html

C#:   list.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtntrzansp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtoaumwvii.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zdqjudy.top/Article/details/gtijlbinwu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtwfbgdlwd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gtyfrliyqq.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gtvslspfdr.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gtntkwauvq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gtoghwdvzw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gtatshqfke.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtzsarmjsa.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtpnfuevyl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtqpoluuyj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gtmscelpxi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtahstprvs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gttatdbenc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gtvihfhoju.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtvyvjvwcc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gtlozblnda.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gtjauitrxa.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gtrzxwvycr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtapnliraw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gtfivmunwg.html


<!-- 参考信息 -->