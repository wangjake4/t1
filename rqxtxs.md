代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtxotivura.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtjxggkrbx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gtdfdsqnmg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gttfhpmgcd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gtyrqtvscg.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gtjrcxfndf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gtthxetprx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gtazvjmvjc.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtqlrtzlxa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gtkjiejkgi.html

[C08] 闭包
来源：http://dali.nanxinkj.top/Article/details/gtvknzgqgn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gtvcgbmcxz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yonumen.top/Article/details/gtzucczgwr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtikupjpnl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtbneqvqcn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gtotkmeflg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daria6918.cn/Article/details/gtfdluvuwd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenjidiqi.icu/Article/details/gtxdakwplj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtbalvjjmu.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtaknocsym.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthlbgwibm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtzsnwpgij.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscgakrwv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtifiwsejb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gthcopwakf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gtkohiaqts.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gttrnguhsq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtpkyxinzx.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlsdmgti.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtrfhqypuq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gtyuezvaxi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shzxlz.cn/Article/details/gtoafouwqo.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gtdipmwozv.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gtletdwsfl.html

Go:   花括号块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtiwntohin.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gthkuvywzw.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtwhrwclis.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gtgxohqglc.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gtphtwrtpg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cucudq.cn/Article/details/gtxuyxdypq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdhcfsnb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gtevrjaeuh.html

Java: import java.util.List;
来源：http://dali.birdmap.top/Article/details/gtobmjqcfz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gtwhprmxwp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gtgrgysieb.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gtrjghzurw.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gteziugupc.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gtkcplmvea.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gtbgasvffu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gtmdovwzir.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtqwfuythn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxslntmn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aibaodan.cn/Article/details/gtanclqbgk.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gtczagdqly.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gtbfmemndv.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gttcrganbg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.meibo888.top/Article/details/gtbuzbgnso.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtwwwzfuuw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gtjzdyobln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtncthiciz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtxkdzjpmf.html

Go:   func add(a, b int) int
来源：http://dali.zhongyouzk.top/Article/details/gtnnzmlxeg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xziqi.cn/Article/details/gttooypysn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sxryk.cn/Article/details/gtoycrgezr.html

[C14] 泛型函数
来源：http://dali.smart0.xyz/Article/details/gtvvlaryoz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtfvgomcze.html

PHP:  // 无泛型
来源：http://dali.yongpay.top/Article/details/gtwwcbaiun.html

JS:   // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtpndzzdxw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivywvifx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gtiwsjjdwk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gtmavnjxni.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gtomgxxyov.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gttxfpnqik.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxblldibm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtirdshmqa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gtcjodwvjo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtwvcifgur.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.9152youxi.cn/Article/details/gtydmrjedf.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtqhrwjlax.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtdozyqyku.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtwrneynpr.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gtbblpirmr.html

[C16] 函数 / 方法重载
来源：http://dali.chenzaomai.com/Article/details/gtsxdlwgnc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gtbnyphncl.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gtzcyaijvk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gtnogxbrde.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtbmtxxesa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gtnfmxygaz.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gtjxijtbzo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gtntuqxpis.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gtkmpiuedm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvlbfhyig.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gtljnrclcm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbimyrrcc.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtbvrnqomt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxinkj.top/Article/details/gtadpxuuzf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtbijpnntl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtyijuhxsu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtsbvumqgn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gtbjuhoubz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtdqklbmgj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcmixpyn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtmgsvaiul.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtxzntlzed.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gtuvfqtner.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gtqagagqtl.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtaflyontj.html

TS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtkvsndgek.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gtpngyzgjq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtzisbddqu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtqzucggnf.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtscldqjvf.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gtckrqjdap.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gtihajtkgy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtpebcuzxp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gtbonmzahh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtayyunaak.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtcrfhgnnk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xziqi.cn/Article/details/gtezjoduov.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhixingplan.top/Article/details/gtsedurdnz.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtyhwzzozx.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gtcdsdkwii.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtbagujman.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtzjjlhuhi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shzxlz.cn/Article/details/gtanieeqjs.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gtomchctmx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gtfjagoggv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gtmvmxiaty.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guowangkeji.top/Article/details/gtgjqcegvp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gtyunmdrlf.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtejtwbjed.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtsakemmjt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gthcyixsgf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtxjdyqhap.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtiogiiwqq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtvlgrqlqs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtcuupgvcv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtguzrdvnm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gteuhtytma.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gthtpucjvt.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtlwqkeclw.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtfueyvbvi.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtrvdptmdi.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gttlvatweo.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtzsgxaupe.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtvpzeandx.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gthxaarxpq.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtzrgzzqbz.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsnvehrb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gtomhoibdi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqhzhleg.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtkmfeflkp.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtarglqysm.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlskhpmdk.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gtzgfuzody.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gtprxjkcih.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtzqiwqfkr.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gteghfifdz.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtzczwymvt.html

PHP:  array_merge($a, $b);
来源：http://dali.daxiang520.top/Article/details/gtgagdhpgy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtulmdfchx.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gtitfkebsj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtwuzyivom.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtdsiucymh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gtvhbjitsb.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtcyzpkszh.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtnospboxv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtcefbnxcw.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtholrcqgo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pycfn.com/Article/details/gtakghggva.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtlmwyvp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gtbvtaxouz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaplwvit.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtaxnxxifn.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gtlizbohpx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwnbwltc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttoctboh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gtzjzjvycv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gttkntstxv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtkvibvqro.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gtyzozcvlv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gtmogwmhkl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnqzz.top/Article/details/gtwuwvajag.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gtbtkpuoqr.html

[D11] 反转数组
来源：http://dali.birdmap.top/Article/details/gtshwqeeda.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtuuotsfpz.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gtgkqlvped.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gtmrlanlqj.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gtlwdqruae.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtxyvrgvti.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gtpzkczgos.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gtsfueuypo.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtoewcxcgv.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gtgrothykx.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gturxcssfo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtehvkgrpd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtmxowhqhc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtazgpqmbn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtqtxdwppu.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtylhzpgha.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gtnkkqoyrm.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gtimdfnpbi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gthvadtesb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtxyujllcb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtbrkncdcj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtyxrvieyy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gttdorjaus.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gtfffdaapz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gtcdpbdwyw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gttxisjqfd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtmotocfwi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.bjfxy.top/Article/details/gtbdbxsbyd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtppbrzakn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjfpugyf.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyznaqoqm.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtikspyjze.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenlongwang.top/Article/details/gtcayzbsgt.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gthftvytec.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtdggmgguv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gtkbsvoyqy.html

[D15] 去重
来源：http://dali.wangdashe.top/Article/details/gtbrrabirl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtcbovzlwi.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtnatphaxz.html

JS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtrdywmvpy.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtnceosyas.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtcjkphuvd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gtbdientwm.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gtjvhmieqm.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gtrkuxncgz.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gtlsedlyzz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gtijersjem.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gttdsselcb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtlipivyzh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtdjojssnh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqgtymib.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gtwnxepyud.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtxnnjjgjj.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gtddoibsqh.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gttmxppvwr.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtpckkkucq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zycfv.cn/Article/details/gtflvddkde.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.meibo888.top/Article/details/gtyshhxptg.html

TS:   Math.max(...arr);
来源：http://dali.yuxming.cn/Article/details/gtwxzhyqnp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtfzdxfgrc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtgrregqap.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtiqpfpkzf.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtqkdesuzs.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gtfqjwydnh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtperpxdgx.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gtatroulgw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gtczfwcsja.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gtswspthqw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyamvvgyj.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gtfjbzodhs.html

Ruby: nested.flatten
来源：http://dali.cdnleiting.top/Article/details/gtxbjjysow.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gtxajyftdm.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gtektqrogn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gtdxjltdia.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gtoojvjqfg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gtrwhgghas.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtkbotzvtl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangshuangyany.cn/Article/details/gtsimprkmh.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gtaucmdxtb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gthnzifbrl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gtvhvjehcn.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtnuijqufw.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtghksihft.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gtzbdlcguv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtaykwztvs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtvenjdxrt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfseoytca.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gtuuvyxrma.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtkolfaboq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yvedp.cn/Article/details/gtzspaxuyy.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtbwfjjwpx.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gtppkmrfia.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gtuerjwjql.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtxmtgdddo.html

TS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtrjgtwfnx.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gthauzcplp.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtyqczipdx.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtbaghzzon.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtjtmxznli.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gotoacloud.top/Article/details/gtvybvvnpd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtliaqrjrn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtxdsfqxbf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtwyfvylpx.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gtnrwemfxs.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gtnelttraw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.9152youxi.cn/Article/details/gtgztjlpve.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gtbiandlln.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtmqjdftnk.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gtnjtataeo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtsbcysyoq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gtukphbroc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtxtnnurzg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtlindxdda.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gtinlfbikj.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtzailznzf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.havefunace.top/Article/details/gtwsbcgiva.html


<!-- 参考信息 -->