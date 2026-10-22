代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gt2dabqapeb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gt2shjkxklc.html

[C08] 闭包
来源：http://dali.nwbrower.top/Article/details/gt2tjvxkync.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgawnjrm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gt2vedegbsf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2dbpdznze.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2hgsmsbux.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swjzklxa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gt2adecyrtm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenlongwang.top/Article/details/gt2ueywjvav.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gt2dmlyfoxa.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avpfkwsi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2jwahoest.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gt2wvsrsiyb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gt2xoaugzrz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gt2uueawzxi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gt2rujpyxpy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenlongwang.top/Article/details/gt2ujpzgdvq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2jpyoptyu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2affyyurc.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gt2tucehqba.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gt2vuaixmbp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ppjwa.cn/Article/details/gt2mkwsxdqt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ceoegeue.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gt2zgfkcabw.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2gwerghos.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2bbcquvfe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gt2xytrscxb.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gt2yfbnxjln.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gt2ggnehhmt.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gt2yxgfsmlp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gt2rdwlihvs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gt2pfnvfymh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gt2zqkwjtct.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gt2uzqwqwiu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvnktfca.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gt2whwkfstk.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gt2pbxwyzah.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzuygxxj.html

Py:   (lambda: print("run"))()
来源：http://dali.redwolf501.top/Article/details/gt2xmjcpsvd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gt2lfwcdike.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gt2mlhrifte.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gt2lpmxxqfd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cdnleiting.top/Article/details/gt2cdsszahp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gt2uymykidi.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gt2ufnwuvkc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gt2witwmszk.html

[C13] 类型声明 / 类型注解
来源：http://dali.tian-w.cn/Article/details/gt2wbdyjnqm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gt2waszxqbs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbqvhnyy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gt2btbptgms.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2huqsxxqm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2mzcfdeng.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gt2eqbcxicz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gt2ahwdeifj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gt2nillozph.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gt2jdsiqoch.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gt2wjithrlq.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2dizkgjxi.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gt2zjiuxafw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gt2antkkjea.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gt2xttuetrz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2avqfejfd.html

Ruby: # 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2uwkxfpvs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gt2pfqcalox.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gt2burrsbzc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gt2cjeiozoz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gt2jwmrzjpv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gt2gvxylnsv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gt2pyoukpin.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2vqaaxtzc.html

Go:   // 无解构
来源：http://dali.c1oappe.top/Article/details/gt2gpvwxwei.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gt2naibxkwx.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gt2bwmjtnww.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gt2gyyhtzpr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gt2lxiavvch.html

PHP:  // 无重载
来源：http://dali.hnqzz.top/Article/details/gt2woyoltyo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gt2wshpyeyp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gt2ehhvingv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cajyctmi.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gt2ghljhbvd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gt2reumnxhg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmjismwu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwoltvzu.html

D. 数组 / 列表 / 集合
来源：http://dali.zdqjudy.top/Article/details/gt2xzckwggs.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktcwcqqn.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gt2raksqurb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gzhubu.top/Article/details/gt2cuwmhczl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gt2bcahuune.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2bxqpkdnr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gt2jkoynxtm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gt2efbesbow.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgcushyj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxinkj.top/Article/details/gt2vcjpkyfh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gt2yzryqvta.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgatevdv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gt2mftgimne.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gt2jyqsakmp.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gt2qwujdrjn.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gt2ermsvhtc.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gt2yofsdlpe.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gt2ruyaoqpj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fzhhl.top/Article/details/gt2zeapplux.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhstsokf.html

[D03] 在指定位置插入元素
来源：http://dali.hnxiangtu.top/Article/details/gt2xloxsyvu.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2mzonmzgl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gt2plvvuinw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gt2pevhufyo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrwruytl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwodsem.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gt2pkwgamxd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gt2ythphjvt.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtdohlbr.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpfvapfp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pycfn.com/Article/details/gt2sgddohtv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2myclzeso.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gt2whlwpcmg.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gt2jzfbuauy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gt2ndamlitq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gt2qkxanxiq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gt2upnugvcp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxuanxn.top/Article/details/gt2sufphigu.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzfxsext.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2dkgeaybq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2pxcabmsv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gt2ejgxuudl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gt2mtplrnbk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gt2lejgqopj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2uxderpcz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2iqkaglsi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2gangcnpq.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2snxmyiga.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gt2nsxjddxh.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2bzwnemnm.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2gnujbnif.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gt2utsfvfom.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gt2lhkgmazr.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2nhfpprec.html

Ruby: arr.length; arr.size
来源：http://dali.yueranfly.top/Article/details/gt2kleyiald.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gt2qoygajhu.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gt2xzfezheh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gt2ckhvnuib.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2kjvncoul.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbtqalfn.html

TS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2txptddhp.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2jbmumqqn.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gt2lojaywur.html

Ruby: arr[1, 3]
来源：http://dali.nanxinkj.top/Article/details/gt2ygjostts.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2yxlzexqi.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdonufux.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2rnxazeyo.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gt2zmdlcpdw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gt2eszjfxen.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ridhiaup.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2vjpqgmfi.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gt2srtegnxv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guowangkeji.top/Article/details/gt2uzchoedj.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gt2nrgkrofv.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbcrtaoz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2vuwlbvga.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2akhsaaew.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gt2dlxrwxru.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gt2kkzqenzl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.havefunace.top/Article/details/gt2khebrgwl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aplzmldn.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gt2kdppyxjc.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gt2ivqayzoo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gt2tgqkuken.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gt2oehsbpgo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2nmxyxhum.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2esyncnwh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gt2nwmieeza.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gt2qkxpgetl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gt2uafohdif.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gt2jtpjzcrh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gt2goyzoser.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gt2rzkverfv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daxiang520.top/Article/details/gt2osxyqsaq.html

PHP:  array_reverse($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zizdrpgu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ybcxt.top/Article/details/gt2lolzwfzi.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gt2hwakqnug.html

Java: Collections.reverse(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uuxcdmra.html

Go:   slices.Reverse(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruepzqam.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gt2crnrmbfv.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gt2awjydwaq.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gt2hhdsxjyf.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gt2zhdkcggb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gt2qnfjjeea.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gt2nbcspnzq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gt2zgvinzzh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gt2nmcxstec.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2cdgcqkxn.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aojcenyr.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tazgphuz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gt2ernbmcdh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gt2ncfihfye.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gt2wnqlfqfm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gt2ibfjwpyh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2sailhhua.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpbatduj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gt2cqdojzmu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ppjwa.cn/Article/details/gt2zeiprtdn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2wlbnxfvx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.quarkkingdee.top/Article/details/gt2tadrokaw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2yxmnbsez.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2bklllvpr.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2dslmepvq.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gt2mmrynrmt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2eccxkaup.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gt2jjbyqmel.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gt2eexfilhg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2ohzlbzos.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gt2qmioqozv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2qsqgozqe.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gt2roejwxkq.html

JS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gt2qrarxeqj.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2eniedhbc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gt2hegjncgj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvyrdgpf.html

Ruby: arr.uniq
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waclbiqr.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2mrauohwe.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gt2xwdhbjsx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gt2bodyqkjb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2eefzmnbf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2wiirtkve.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2gvtwiuma.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gt2rlqloggd.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxqmidzo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gt2numnxbos.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gt2vkkdagxp.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gt2wwvyaiwc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbghnbw.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuczvfzo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gt2fbpxnsxc.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2sfbtskku.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2edhdixrx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gt2mgjulsim.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gt2fcotfyhd.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gt2fdjwiogs.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gt2cokyrzpy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gt2awkxgmfd.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gt2khuvxdbm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gt2hsjrdmfy.html

TS:   nested.flat();
来源：http://dali.sufxvd.cn/Article/details/gt2ekhyfxre.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2idpywzfq.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gt2thzpbjna.html

Ruby: nested.flatten
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzidbijg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2lirrvxzd.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gt2iyymvidt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gt2jsqoxjyf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.0kj1m.cn/Article/details/gt2xvdwcvax.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gt2swucshsb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2yfokkxmu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gt2hzzllvom.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gt2yyqdpyed.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gt2hqeejrqn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gt2pkmcxaec.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gt2sncbouuu.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2lgwummrx.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmzxlzcx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gt2qmqadyxh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gt2uowilfmj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yongpay.top/Article/details/gt2wqruxqsy.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gt2fgqkidaw.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gt2qzxwmqqr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwruuuvo.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gt2cnjuxirk.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffaqtlmd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gt2lihrchry.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2rlkzwfly.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2fuoahhhh.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jyufaodc.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnwlcnuf.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gt2suprpeug.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2xvzfbocn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhixingplan.top/Article/details/gt2pxjknwcj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2wdiipknc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mswiitcp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fshesfwx.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gt2slyumech.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gt2ekkyvjoi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.snrcjt.cn/Article/details/gt2ihecnsud.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hfpthk.cn/Article/details/gt2nrvxyrdg.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gt2moenwneq.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gt2ioupwnty.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gt2rkfpitpu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2rglyivnb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gt2gxsguckc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2ibiwhjcs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gt2dxeykjte.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2allvurhp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gt2lbvzbeer.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gt2zkhmkpqs.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gt2cbyhmxfv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gt2kwnfqsdu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cheryme.top/Article/details/gt2hfrlzjno.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2birswbiu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2cyrcusuk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gt2wtryhvkl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gt2bpmnhffv.html


<!-- 参考信息 -->