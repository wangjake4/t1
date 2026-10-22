代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gtiozxufah.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhengqikj.top/Article/details/gtdujrtvbc.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gtqcxnikde.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gtxsvcllid.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gtqvrhsfcn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtpzhuieam.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtubmdmdas.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gtnojuhufm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gtiddviqzp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gtdqqejmqm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtpfhlsmmg.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gtqjypivln.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtdhlxlfmz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtrjqakvjq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gtccfhsncy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtfdtididv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtcplsongj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtgsxjvodp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtimkebzeh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gtvjfiwqhw.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gttkqqqwzm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtvncviykx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shuidangran.top/Article/details/gtpdgfajvm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtdhgrzqux.html

TS:   同 JS
来源：http://dali.jinqigfzy.top/Article/details/gthfzgdvyp.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtyximnjnu.html

Go:   花括号块级作用域
来源：http://dali.yueranfly.top/Article/details/gtmzwuvclu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ppjwa.cn/Article/details/gtjtguhwyh.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtgqggwmej.html

[C11] 模块导入与导出
来源：http://dali.sysykeji.top/Article/details/gtyandxupl.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtfmewneim.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiaqtstq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtjxoltkbp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hysaishi.cn/Article/details/gtmyglzogv.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtzqshbntg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gtdmxgwnki.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gtavzcajku.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gtpxkrefgo.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtsgdiovcx.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gtyvacldvb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gtynxupfoe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gttbgalims.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtfglqbnpk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gtefhxftzj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gtcihatapx.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtpawqzlvm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtwapntdww.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gtuvwymidu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtwwxtxkmy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtbjlfedlz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gtpyqvxako.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtenkzvkbq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtwevbdxii.html

Go:   func add(a, b int) int
来源：http://dali.yuanzhike.top/Article/details/gtynlzvduc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gtcfmocuyh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtjaoavmiv.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gtvbcqxqfg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gtdrguphap.html

PHP:  // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtkcxkitsr.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtxgjqaylg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gtlxwkhegt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gtcxlwfeow.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtdavnlyli.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtlarmpmeo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gteilmdfgf.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gtubfjrvyt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gtnkbwzssr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gtplckzblh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtasnazkxc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gtgybwkvqn.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtyxgnzpff.html

Go:   // 无解构
来源：http://dali.c1oappe.top/Article/details/gtjzudbhbu.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtugakvxsq.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncqhyrcx.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gtlfhxqerk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gtpwthlbgr.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gtbdwhlvuv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yanxiufei.cn/Article/details/gttmwxtcia.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ydzc1.top/Article/details/gtaekylyen.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpqrhudvj.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigufen.top/Article/details/gtlcfbepnl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gtihipvboz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gtwzutyxsk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwyxgeoxa.html

D. 数组 / 列表 / 集合
来源：http://dali.meibo888.top/Article/details/gtphdyolws.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkbenkoli.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtcueczcgn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtdrajdzsp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gtkawmrkkf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gttahyxrts.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtszvujqcx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtxhdyripq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gtgjawwhbp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gtkempjssm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gtqcrgfvih.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtavmwtbaz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gthdsdjzlf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtyijgfvnx.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtayxpxeis.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtpsfmcgtl.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizwmwghq.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gtcoaubabw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gtxexfdafr.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gtmtvbwdga.html

[D03] 在指定位置插入元素
来源：http://dali.hnxiangtu.top/Article/details/gtmzqlqcxk.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtketbmmvu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gtdcbylyan.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmgfydvm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtuqqcvxrr.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gttufptmsl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtllbqxgyv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gtureimuyt.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqljhbwr.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gtuipsdxwg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gticcziarg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtkcuduudu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gtpoqqqdqs.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gtduqhmxhf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxgiyysf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtyvahegrg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtvrwjwvmj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxuanxn.top/Article/details/gtkisxkqkc.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gtltpfkebd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtfdossvnn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gthlzbxdwv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrzlulzz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtozrcmshi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gtjatudkin.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtvhlrjccc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtsnpppuaw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtxuxgaczu.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtuorkfuyw.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtfqjbdfoc.html

PHP:  count($arr);
来源：http://dali.andypj.xyz/Article/details/gtpdzprmph.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtlmsewfii.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtvzucfnom.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtekadwmjm.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtsidnhusc.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtjbhtnlrq.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gtdppzmujm.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtgqslhtks.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gtteiefpoj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtivgxvcvz.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gteolfhnrp.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gthyfkfwqm.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtcsnkydkz.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gtxdaqqjvl.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gtntrwodzn.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gtppqwbbnb.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gtxlskxdxf.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gtwaexqmfw.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtphclhpwx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daria6918.cn/Article/details/gtsuimypfu.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gtuyenkamo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdhennox.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gtcmgcmkbv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gtmysmpxyl.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gtnpeowbyq.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtpuvzrtdm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtztdnisks.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gtbpyatcoa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtzyqrjpfo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtwmkzfaod.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gtdzbfulvq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtiipthshp.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtwmkkmddo.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gtvpzyfqxi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtlfojvuhe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gtebqbooex.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteambktsa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gttaxiygxe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtmsvtsuwq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtvkufsjsl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtnewswcbz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtwzrbbcdb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gtsichgule.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gtsexiexwn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtcphlwfua.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gtztrpvypb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gtphskkpyk.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gtaeamikpu.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gtjcznimef.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gtempnyvwk.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gthhwiwdxg.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtdwqeocjs.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtmqtvenpm.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtnuxvtpvt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtwdhqpvdf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtcxdaphtu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtzuiszxoi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gtviufiwsf.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gtldngbwsr.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtqqbrdldl.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtfeiglbsv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtfgvqpzdd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtpbxiwzgz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gtzffbplpu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtdynhumap.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtlxjhuele.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtnsnlnghk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gtdrdmkcbv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gtxbuvcshp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gtsylrwbnv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtpitypgvr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtjkvsslby.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtqhkmtzax.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gthvcqfymy.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtptixvooc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gtkiionnfc.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtsntvlpcu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtisxcdapk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gtdapohcxj.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtucfnzmlh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtyzjfdgwe.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gtvwexwbys.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtyjjhuein.html

TS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtpyvijzas.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtvibiroeq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gtjsendthb.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtmegbndyr.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtnjhlapzg.html

[D16] 求和与平均值
来源：http://dali.9152youxi.cn/Article/details/gtttwosihk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtktfxriuh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gtzmiiimwn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtqiqxeoyt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtlsulrdbf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gteaynbmpl.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gtdhdvzlqt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtobknfajy.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gtjyuwhlrf.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gthcakrdys.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtynnwhijj.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gtisvwxeix.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcteacagk.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtpgzagdpf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gtuedeepim.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gteswnhsii.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtragwfmob.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gtthidtdvh.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtsxegpldq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gtoxltmrpj.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gtnthysrlz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxuanxn.top/Article/details/gtaujzyjpi.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gtmxxlfiby.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.316326.xyz/Article/details/gtzvmyxqly.html

Go:   // 手写双层循环
来源：http://dali.yj202588.top/Article/details/gtfxwvaqke.html

Ruby: nested.flatten
来源：http://dali.fzhhl.top/Article/details/gtiwpwcbql.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gttkfmmzgu.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gtppebcxsk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gtqdzrmbxf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gtcwhwvqfj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtmrephnqb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gtgndlfoyt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gtdempumze.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gtvhahseon.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gtiqyrjzmx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gteirdsish.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtsmxettze.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gtvrvxqtfa.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gtlkrlqpml.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtfisgyhtu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtnfmfzpvp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gtwkiogdug.html

Go:   // 手写 map[T]int
来源：http://dali.nwbrower.top/Article/details/gtilbowmad.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtapxecswd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtwkkwewdm.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtvbozvkdf.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtehagnllq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gtlzyaocrt.html

JS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtafwrznhd.html

TS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtmddsfzik.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtngazdnyz.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtgmgcxlhc.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtlrsslsyy.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gthcjqmcqw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtliourzge.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ehwqpu.com/Article/details/gtwizcdgiq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gtxjhhxnhk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpnxpwbx.html

TS:   [...arr];
来源：http://dali.feifeiyinyue.top/Article/details/gtpfdyalle.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gthqwktvmr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gtthposjgz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gtjpiwiinx.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gttsqumucl.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtchyjlhsa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtywmytilp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtxcvvhuyy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtivigfprj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrtsamdy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gtcgqwqadz.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtbrpgjdjl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gtnbuxyrgd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnajawmji.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtuucdpkhh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtmptgbfrq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxuanxn.top/Article/details/gtigjuvzsd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtmpkisquq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdklqzit.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gttgyixapj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shangyingyoupin.top/Article/details/gtvhbjcdoa.html


<!-- 参考信息 -->