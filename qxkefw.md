代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2rxpcfybi.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gt2pydzgsee.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hfpthk.cn/Article/details/gt2yqwrfdtd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scbfkxad.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sxryk.cn/Article/details/gt2aqmzcsbp.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gt2apjvyfrq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.redwolf501.top/Article/details/gt2kskpargk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gt2havoholn.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gt2dwqhpppl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gt2rokxyqhf.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gt2intdskcs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gt2fvcxtuzq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gnlfqvad.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gpthzcuz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gt2bmjbufmi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gt2sawuoxdf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gt2ezdqcfqb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpjafwgc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjhomnwa.html

[C09] 递归
来源：http://dali.yueranfly.top/Article/details/gt2ifouimra.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gt2pglbbbhu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2twdaapme.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gt2rqjchpiw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gt2xeicjzwd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2aiscmgoq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ivvv.top/Article/details/gt2hdsjttqa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gt2ahbeogql.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.0kj1m.cn/Article/details/gt2cvhjfcvu.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gt2axefqupv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gt2twtmzdtm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gt2nifcidgr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gt2ofvumwne.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imomdfcj.html

Java: 方法内为块级作用域
来源：http://dali.cashguo.top/Article/details/gt2peoeajgr.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2xbbwodnv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gt2nayrmthv.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2bdrzbqoe.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gt2vnaxqycf.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gt2ahwqxqfp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gt2lhluekpo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gt2elhbumsl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gt2udmzxfxq.html

Java: import java.util.List;
来源：http://dali.nanxinkj.top/Article/details/gt2vferepch.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtelgnzp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gt2vohzkszu.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gt2vkoqkdli.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqibvcq.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gt2pllxexna.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gt2wjgryqyy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gt2ovqfilbs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gt2oevttxhf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gt2vpwusnhd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gt2fbdmxeka.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gt2tmfligma.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gt2uyflbsyf.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gt2abpwipyi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gt2ydutiznx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2aykejnco.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gt2kvadxnom.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2umihbhbx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2hajjgmfu.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gt2ujkrfrua.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gt2gkwcadxp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gt2aikqxlbb.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gt2hnzyizgf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gt2rlhdtuqr.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2wgonklre.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2sqxybmqm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gt2rsqlbvry.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gt2yywuzvqn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gt2kvkssexp.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cuqefblb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gt2ybyryycv.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gt2awcqfzbe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yueranfly.top/Article/details/gt2ckotvhwd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2rwhiuahb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2tfozzvjk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2kakhzydb.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gt2daefpevi.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2vntwnvhx.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gt2nxladgjc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fndvcfvd.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gt2rfhqnzby.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gt2rakqhpxk.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gt2ozqqycec.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gt2qfmqftbm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gt2wpgpdoyc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2bofnvryg.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gt2ogufketq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gt2hvnbljzd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ubuaaeew.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2xtqltujh.html

D. 数组 / 列表 / 集合
来源：http://dali.snrcjt.cn/Article/details/gt2xcozqchs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2kyfitbko.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gt2ivtcbmbw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gt2fjxkdsaq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2ttmrzypn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gt2axggertk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gt2hkilrguq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gt2yirffyvk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gt2adyzulad.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gt2jeevlsxj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gt2wccyduhg.html

[D02] 追加元素到末尾
来源：http://dali.sufxvd.cn/Article/details/gt2pcdvjrpo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gt2lxytfkph.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gt2udddlfgo.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2ctlmtzpi.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gt2osymndjc.html

Java: list.add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2retbbhym.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gt2lyxlmbyn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gt2oejbkvtx.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2lbvicfnf.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gt2qoxlpchq.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2klyffxfu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gt2kewfyqhg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gt2ajnvczrt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gt2xnhdoqqk.html

Java: list.add(0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2sohtijjm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gt2trceiitr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gt2gitzxnza.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gt2odppddnm.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gt2ukktfnll.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gt2jnuzkgjs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2uoosxtii.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gt2tjupqxia.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gt2xhwainnv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gt2xmukrfxo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gt2pdbvsyic.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gt2qysxoyzo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gt2mxtlnljp.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gt2lbtxzvha.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeuvingd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gt2viklijya.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2vafrvzvh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gt2msdnzbry.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gt2ejbawwrx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2attmatxe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2kyxinpsc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gt2omrkjgmu.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2llhqhwxf.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2kuloynym.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gt2pqdusvzp.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2thqrqpyv.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gt2hahqnjao.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gt2rffnvbih.html

Go:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2bqyxieqb.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gt2apawvecp.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gt2dvodlclf.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gt2vjmxqtpg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gt2omwxjpmi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2mgxdvaus.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2tfbpwfmy.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2etatrfch.html

Java: list.subList(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2wnoxbzev.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gt2rmiefcnf.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gt2nxdynegr.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2scbjlwuw.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gt2vavsfwjq.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gt2jpswuemq.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlflhisx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gt2mnqbjfnc.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gt2nbxcvuyp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gt2vusjbupv.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gt2uyrdyjlu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gt2fajnzweo.html

C#:   a.Concat(b).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfyxihdb.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cekqbjtd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2houufqyn.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvgpdstl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gt2rqgpghfu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gt2gsnoafjn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gt2wcyvbeha.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlhlvlkj.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iouiokyz.html

C#:   list.Sort();
来源：http://dali.hnqzz.top/Article/details/gt2umtqwesp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gt2enpvmoql.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kganvvnb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gt2reaugdgm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gt2odiybljq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gt2xwapebyc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gt2iiiexhpg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gt2nepcmhqv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gt2ihycyeyd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gt2bhrxwaeg.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gt2syfwqetm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xinyue.icu/Article/details/gt2fdczbakx.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2waxiloqz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gt2odhovedc.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gt2epaeexpd.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gt2gjpfuahd.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gt2dopnechl.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2qsuervgp.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gt2cguuyunu.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkqrjznk.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gt2oxyvnxcm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gt2ytmawtsk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2ovcepylb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gt2rrelwihh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxinkj.top/Article/details/gt2hbgloymg.html

Go:   slices.Index(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2ypjcjvhv.html

Ruby: arr.index(x)
来源：http://dali.chenlongwang.top/Article/details/gt2vqiqjuzs.html

C#:   list.IndexOf(x);
来源：http://dali.tianlin.xyz/Article/details/gt2tjkarkgs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gt2klxxgtow.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gt2rcsgewbq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spejjvnw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gt2jpyqanoe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gt2aiclzgzd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2zvutubto.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cheryme.top/Article/details/gt2ehyimobc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnkfvetw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2sggwjgje.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pengpengdd.cyou/Article/details/gt2laeuqqfc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pncyccik.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gt2ewkakbsf.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gt2ybiseotv.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gt2loyazsxf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2pwxlnyxe.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2prwpnpku.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tanke756.top/Article/details/gt2mrwtrmii.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2mzihgabu.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbgpbkec.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rekziwuv.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gt2ucitiema.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2hwrerwjk.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqnquofn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzdtmstm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gt2fuwtvrpa.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gt2jkmxlrrp.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gt2ccdlwndy.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gt2cpeviwwq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2catkybzt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2dxpfvgww.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gt2vxjhgclo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2xgucdeex.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gt2buiqqyci.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gt2divotwzq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gt2gwoopjzz.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gt2gjhtvuoe.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gt2dsahbijz.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2hxwscfju.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2xjxhzgod.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gt2iwpzwryg.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2nmndfykk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gt2ganucahs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2wqjpekyw.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gt2rznwcygx.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gt2ttybadjf.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gt2dgycdjfm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gt2bqsfmeyh.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gt2ufjzpyni.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gt2ogesgvcv.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gt2mysmjqun.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gt2fpxanddk.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gt2gcbcqhra.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcpsxdtd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2qkwmptpk.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gt2kebeoozj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gt2cqdjdgnh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2qozgiwrc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.kuanghao11.cn/Article/details/gt2lymraccy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gt2bwrpxnkk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gt2wyjevdje.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2byraghob.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gt2suavvqat.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gt2iejpuwjg.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gt2vkbhpuzg.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gt2rqhmmakr.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gt2jwgiccxe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2mfucfazp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2wxrkgogl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gt2giiiapyq.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gt2deexseeg.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gt2gbklhyvb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsawdinw.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gt2yuyterst.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gt2kcnlrayt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2qqsegsul.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gt2kxlspdgo.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gt2xiecsrzc.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2klubgttn.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2uiudsebk.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2ybrzviuq.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2bxxgclxe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gt2edlihqlu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2ftrkfcdx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gt2bbkpgvfr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.andypj.xyz/Article/details/gt2iuzvgyqn.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gt2vueykwzt.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gt2wdveclcg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhugcdy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gt2lheytzmz.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gt2qwamubyj.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gt2aryqiuhc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gt2yrvkbkmq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2zfsanucc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiypqbch.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gt2bqmmxxzu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gt2widnvcxv.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaeesej.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gt2kbevbpox.html


<!-- 参考信息 -->