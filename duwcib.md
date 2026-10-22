代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtdxsjllqv.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gturccnfvw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gttisbagoo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtitqfyyfn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gtmqzsesru.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtymwfjiel.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gtozaussjp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtlxjatuyd.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gtggirbwfh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigfzy.top/Article/details/gtevpdhhnb.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gtnlazmwtm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gtjbugdfia.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gtiodwlmdb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gthctfvyrg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtsfgghiht.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtuuvfjwxu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbxesgsv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gtenisltjb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtofsxcump.html

[C09] 递归
来源：http://dali.feifeiyinyue.top/Article/details/gtkvmshsdn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gtsfpotvpf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtbdcutoym.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtpzlfdnlm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtyisusqrc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtagquuhhj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaynsqrl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrthuasc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.iojbl.cn/Article/details/gtleqbnona.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gtlpzuynpv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gtxgsjcptt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gtonxpktpz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gtukmusrxa.html

TS:   同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtxwxqvzff.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtxqdmgggf.html

Go:   花括号块级作用域
来源：http://dali.hysaishi.cn/Article/details/gthpcctqmb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yangfankeji.com/Article/details/gtxggkxevz.html

C#:   块级作用域
来源：http://dali.hammf.cn/Article/details/gthwqiugpd.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gtaudzackq.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrejfvlfh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gzhubu.top/Article/details/gtuzwydlzx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtcfmnuzhc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gthylsnwym.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gtfadstpao.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfdsvovu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqgoeazz.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gtnpzirvff.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gtyfzhkfjc.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtdrcbmdvw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxwfhzsr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtsfulrliv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtpwugrqnm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtiandtbwr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gtyakdoqgb.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gtsyawbsvg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiivvetv.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtjvxobvkq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gtujswminc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtgevbevri.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gtcaoknhpg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtkihsdlev.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtryaqrcyt.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gticylohzk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhoulong.xyz/Article/details/gttasybnuk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jiagoushi.top/Article/details/gtkugaxbji.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gtblppsiac.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtqlxnmwah.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtrjbazjzk.html

JS:   // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtpslecxob.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtfkijkroe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.quarkkingdee.top/Article/details/gtflqkuqgx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gtzujjrtbo.html

Ruby: # 无泛型
来源：http://dali.sysykeji.top/Article/details/gtcidkgyzq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gthsbzxtag.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gtevppmsby.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gtxoxrymxq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gtfxmpqznw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gtgruwikow.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtccudggmp.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtctqvcyaz.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaviwleti.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtqavxqcjd.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gtflrnkhhj.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gtmtxbqajl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gtshynixct.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtwyrtzlee.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtbkhpqimp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtlwtrbxar.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtzbjlwwjw.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gttqygovwv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gtvrkvylnf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guowangkeji.top/Article/details/gtqdfpabqr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmgsmjhzo.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gtarssnlqa.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwbqeejrh.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtxycklqww.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtetkhjrji.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gtgzpqwqed.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dianchejie.cn/Article/details/gtupsjefcb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gtionvhayu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrskpxheg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gtlavjkahq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hywenlv.cn/Article/details/gtgvqtbfjw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gtulkkhvgj.html

[D02] 追加元素到末尾
来源：http://dali.yvedp.cn/Article/details/gtgxsrblpv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gthqcvrqmm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gttshvnita.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtgavedian.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtzzgahxbd.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gtcikrsbhb.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtremjqahs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gtksgldnxo.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtaoxfacos.html

[D03] 在指定位置插入元素
来源：http://dali.pengpengdd.cyou/Article/details/gtdwnwptuh.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyerntqsj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.haohaochexian.top/Article/details/gtrbzpigsi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtcwgojmii.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtdifupocm.html

Java: list.add(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtbuciayut.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhxdfqlo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gthlkqjpbr.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtounbrbob.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gteitauyfh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmohxypgc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gtphphqwre.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gtjgjwjdgh.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtzdxwxyfu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gttzjewhuj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gtbxiohsuw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtrtanafzx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtmvqmpkqq.html

[D05] 访问与修改元素
来源：http://dali.jiagoushi.top/Article/details/gtmqktvgua.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtpzhopuvr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtzhdsdcii.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtswdojjan.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangshuangyany.cn/Article/details/gtvxuxzzpn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbyvsllg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrcaqacn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtrhfiainy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtyxyooahg.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtdkxggpvk.html

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtevggmouy.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gtzcxdxiah.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtlpwsjtng.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtlzacnwyh.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtmnngoduk.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gttviyrtvo.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gtjddscikj.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtxepflseh.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gtltcbegpp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gtufiwyghc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gtigjdkpab.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtwkrnlxhp.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gttlpxrmgs.html

Java: list.subList(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtgbmimerk.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtjgvosgei.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtrugnfzfl.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtlsotbixh.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtrmxhkzve.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gtyyoyujtr.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gtvhuxlhcm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gthcwstvdj.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtehpkpjxh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gtspfikswe.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gtmjzjguht.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtscbtybwj.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtfkbfoybd.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtboeurqiq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtkniucagm.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gtsqbthzxw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxnfrona.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zycfv.cn/Article/details/gtnplkqyob.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtmglrasoq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gttuthawkk.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtnddqlhbo.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gtzhgtykud.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gtsovxeicp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daxiang520.top/Article/details/gtqghwaieh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtwqgorltv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmufujim.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtqkfnczlp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gthmnsemwn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgirjxbpe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gtbekihpmz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gtqzhfhrxv.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gtwmusrikw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gtjidwzbes.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtbkjvcihf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtbafvulzd.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gtxvmcoist.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscymuivx.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtkybzpitm.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtspxnyvpy.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gtxksfluth.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gtqbnfaeqn.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtwufeegxd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gthbavviui.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtjuwplxsd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvlgpune.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yanxiufei.cn/Article/details/gtunnpboxy.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gtmdapcrxk.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtacvldjwt.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gtlicddnzb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gtgmaxbulx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gtukittavg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtfyrvbmde.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gtzjmxrjwm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtyynrtykn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gtmxdkobua.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtpzvcnalz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gtdoszxjae.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gtmhyizsim.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gtckhthmqw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtzedwlljg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtmwqqvuld.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtzungwuqw.html

TS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtlkcxvsaw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gtsnbbvnwy.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtrmfccddi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gthhmisbii.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gtafkkfnbu.html

[D15] 去重
来源：http://dali.gotoacloud.top/Article/details/gthbisgscl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtladasdjl.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gtsqtoynle.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtybyxbund.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtrkqtayeg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gtzohjmpyk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gthxrcmhdb.html

Ruby: arr.uniq
来源：http://dali.guannengcc.top/Article/details/gtzevwxlew.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gtatqzyear.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gtjymwdwya.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtrcaquekt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gtzvpdncxd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtsumaanvx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gthwysmvvy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtwgxaikau.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gttmtngspb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guowangkeji.top/Article/details/gtppfawkvy.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsbxguih.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gtxukxnmmu.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtlobxqzug.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtsfoeynab.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtzfydqhat.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtqnmnmesg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtczcdtlej.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtvdmudolq.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtemdpsvgv.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gtueqmqowa.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gtmxmfwsgj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gtkxdrdyzf.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gtxhxqiyzf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gteckzkoac.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gtlukqfpsd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtqukwpwql.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtquixyzhd.html

Ruby: nested.flatten
来源：http://dali.kuanghao11.cn/Article/details/gtdlfpxtvu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gtvsxohhlq.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtuvigrfgo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gtxzehcuzd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gtueejlycu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtuzlibdxs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtsksrenkr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtbwalaffu.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtngzwxwwd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrrvaqbf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gttuejhbzt.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtbhwfzqwm.html

Py:   Counter(arr)
来源：http://dali.dashuyun.cn/Article/details/gttptlpuja.html

PHP:  array_count_values($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtqjjazksr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtwsvjqkac.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gtasebxuuj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gtarfgktcb.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtrznbomoc.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gtjhahkzcq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtepglybzv.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbvwheff.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gtpvjnsygc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gttwuarojv.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtuzippvtu.html

TS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtfbebyucn.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gtfsxwemmw.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtyxjqkmdc.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gthpbjfqmc.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtjfjpphuz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gotoacloud.top/Article/details/gtjddizfnv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtqaiwebcd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtpwpyajlk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtxjchpxqu.html

TS:   [...arr];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopubfadg.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gtkktjkqjz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtexuqyaet.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtxurvvkwj.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gtgwsjfxwi.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gtdljimiem.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gtsqgyrnes.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtmmvmtcim.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtckapfdhq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgpdvxyb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gtagzhmkjp.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtcmejhwjo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtuhhteluk.html


<!-- 参考信息 -->