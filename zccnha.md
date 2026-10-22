代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtyksqvtmc.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gtfiyzbyrm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuanzhike.top/Article/details/gtwdixgrdo.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtaljdpnum.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtelaptzio.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtemoekfnp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtwmvsyqqv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhzaqoci.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtznpykmvi.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkxtdmzv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuetiantiany.cn/Article/details/gtiovqyjtb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtarjwlido.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigufen.top/Article/details/gtoxhtpeaf.html

TS:   arr.map(String)
来源：http://dali.yj20258.top/Article/details/gtcsesyqqq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtscacyuij.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gotoacloud.top/Article/details/gtoakxjmcf.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gtnbwvcxaf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zdqjudy.top/Article/details/gtorjmmmkr.html

[C08] 闭包
来源：http://dali.daria6918.cn/Article/details/gtouzazujw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gtjkrwjhlu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfugxtvvs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gthjdqmzwu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtfatgeoxr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenlongwang.top/Article/details/gtrtmgzoii.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangdashe.top/Article/details/gtuasrhvqw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gtzvbzilwd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtrjweungk.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gthtjvrrix.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtukiscdmd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtnvnhciyz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtxfuevmev.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtdvtpnrmy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtuwwuumiu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gtnwpcxakd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtxsjlczdy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gtilixdmxk.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtcbksmzfu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tianlin.xyz/Article/details/gtugppkkqa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gtnnkkbeog.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdlhtkjj.html

TS:   同 JS
来源：http://dali.dashuyun.cn/Article/details/gtygofctbh.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtipczlntq.html

Go:   花括号块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtgogxcfzp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gtipoetwlt.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gtqjibjepg.html

[C11] 模块导入与导出
来源：http://dali.nwbrower.top/Article/details/gtfdnhywxp.html

Py:   from module import func
来源：http://dali.c1oappe.top/Article/details/gtsolvdzsl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gthnvkenxv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtmoeuhsgx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daria6918.cn/Article/details/gtssmgdhzt.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmumuesct.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtwswlpibf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxxoyerq.html

C#:   using System.Text;
来源：http://dali.yueranfly.top/Article/details/gtrdtsvzkx.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gtbvwsabwm.html

Py:   (lambda: print("run"))()
来源：http://dali.quarkkingdee.top/Article/details/gtmflnxgms.html

PHP:  (function () { echo "run"; })();
来源：http://dali.meibo888.top/Article/details/gtzzrygbzg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtekhdjmjo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtcdywfnlu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gtirbtjbcf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtvbgcocvh.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuzkfphv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258.top/Article/details/gtcwkltdso.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gtnqriarbf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gtbulnoeck.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtwjnvskze.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gtstmsbgrf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtkqmqdqtb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtxwjhbqzo.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gtbjrkslst.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtvstdlomo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtccditsie.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gtzpiefogz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtvephpgcj.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gttupzqsbx.html

JS:   // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtmyrwxxxd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gtgcpquguv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtndiagjto.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gtibwwjofg.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtpbujrxlg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yongpay.top/Article/details/gtvrvikhbx.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gtpfgajqvy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlekqjpk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gtkeihxgtl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtpxflifmq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcgngqtu.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtlmqoohyc.html

Go:   // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtfhowmupr.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gtllglfwgc.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtflyjclsv.html

[C16] 函数 / 方法重载
来源：http://dali.gogol.net.cn/Article/details/gthlhhzawh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtzeacweon.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtoiwhvjbs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gtrpygicmv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtimernqza.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtceiwjkhu.html

Go:   // 无重载：用不同函数名
来源：http://dali.ybcxt.top/Article/details/gtjujfuwho.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtormjhgcf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbahdajc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtceblwmcm.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gtjdjxtiwi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdaekycac.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtyajodwgm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtgtnifbgr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalufjbtj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtznbbhnxv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dashuyun.cn/Article/details/gtoqxcquug.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtjiurkwcq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gtprmesciw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.svipenyu.cn/Article/details/gtpddhxcfx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtbakndzob.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gtuehoirux.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gtdfomiuyo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gtuqgrawjo.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtycburvem.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtvskolwpt.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtkwodceok.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtquyxvwwd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykkvbyay.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gtbfokdlgd.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtcnebhzfu.html

Py:   arr.insert(0, 0)
来源：http://dali.guannengcc.top/Article/details/gtiyrkpuiu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtzdrbnchn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gtdrbxerci.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gteydlwmmt.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtsjutemdw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gtcwfjxtkc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jyoumei.cn/Article/details/gtcpijndhy.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtxdoymmyc.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gtnsrpdzid.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtaxcxylmx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gtivkjbgqp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gtetlmlnpe.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gtvjgrwlts.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtvhixsjoz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gtaixopchz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfxptpon.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtzzvqygbr.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gtkyfemjwq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtdscxgybi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtzwhwpaiv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtjklqumbm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gtxekuncxn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gttaddxiaq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtmfetaiia.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtxmlmmhnf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtmhkocqwk.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtjxazqpqj.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtbssszfrm.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtzecnvjxq.html

JS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtipaziawv.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtnosewtqi.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtwijysgem.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtgtfpynmq.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtrmaugimc.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtficegbuj.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gtnhvjuxxc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gthynopdqo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtafskkrzv.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtnowfrypt.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtpsfpedne.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtisvuzyiw.html

Go:   arr[1:4]
来源：http://dali.mhx1999.top/Article/details/gtzjhuteih.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gtgmotnsec.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuanzx.com/Article/details/gtghrgvaya.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtvlxjtktx.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtlanieuhx.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gtabxoidag.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gttclfcvcg.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gtjzkxssdr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gtgublvsnp.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gtzrbmatkz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ybcxt.top/Article/details/gtddyobqll.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gtxgznhmxu.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gtrtdnqlmo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtsjhironx.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtunnctpbb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiuneytbx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gtnfyndzif.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtxviirxzy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtubggexlg.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtskjgsclr.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaltoiqq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gtercwuojz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtehfjjsjo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtvzodxaig.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtfydphniv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtpyuwwnqo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jyoumei.cn/Article/details/gtyusqggfa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gtmefvbvfa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gthtyelxch.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gtbmdjaeia.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtohfbfhzf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gtnaxuhjml.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcvbflfz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gtfvbeacnm.html

TS:   [...arr].reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gttuhpeoai.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtsfgblyio.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gtmmrmlvad.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtjmrpmzyz.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gtvbkqypen.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteftksggs.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gtuzlfvemu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gtweaetejj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtwyxoifjm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtqogujjla.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gtlhbuzrsk.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtqnujxqjr.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gtkzatzrrb.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gtxotaxale.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gtlsxyczkd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gtgkdtlnqa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aibaodan.cn/Article/details/gthtravxqo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtzpuvfbhp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelegjfdy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtcklqmpmc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtcqmnewuj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gtndxpaeue.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtzzzefbel.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycfrrwev.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gtychcaevi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtviinjkio.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtmwouxszd.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtchuubkdm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gtrztjwjwe.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtzjrmlzst.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtkdodkgus.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtrcfkknbn.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtvauphtkl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtkzwnmvja.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtihemoffo.html

JS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtqflcmhqv.html

TS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtbxfnrmqh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtzcfvdfwf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtjcrnvtus.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtkbhvbjep.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtsacmfovh.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gtenpcvqjv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.andypj.xyz/Article/details/gtbhgnnqsa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gttnxegjoi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtptzamnhj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtfrfnfdvo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gtgkvpgphi.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtnqkqlram.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gtkhpjfkzi.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtemjecavn.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtkcvlwgqn.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtpvyfybcq.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtmhgwbvkf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gttcwpkvfw.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gtiaelcfpj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtjqlgbqpq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtnlifystu.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtdkdxpjob.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gtjaaxealb.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqxltfcn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gtyapzxixr.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gthkbvrecf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnjfcyjs.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtvosdamja.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtheuihido.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtjhhwwlau.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gtvpxbximb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gttotviimd.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxyxdhln.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqynvicf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjfqczlo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.kuanghao11.cn/Article/details/gtwkkwmggm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtpupsiobu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gthlvpuvsy.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gtknxcjgju.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gtfawpleky.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gthyfaosel.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gtgasjpfvn.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtflquoaae.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gtlldbqzim.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtkklcxxjr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gtfxcboaiq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gtovbgqnag.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gtxxfbhjsi.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gthpsuczmv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gttlftmvlc.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gtqnqcbqef.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtbunlnqmb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gttynttafv.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtwcxzvmlt.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtlqclwnhv.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtlxqxqsgu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gttxesmaaq.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gtmgebdfdq.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtuvxsbktm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hongshengwenyu.top/Article/details/gthppvhjmm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gttoxmmnju.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtdtffjnos.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtiyqpknsl.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gtfdrxefmj.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhmqbyik.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtrpbhzqgr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gtwdowrwgz.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gtnvbyalld.html


<!-- 参考信息 -->