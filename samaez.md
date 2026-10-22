代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gt2xqvafrtu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yvedp.cn/Article/details/gt2zfvmmbzx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2lebxhcld.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gt2ckxtsukp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gt2zfeuqrix.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gt2irsntzck.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmunybzk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvghgrbe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2sqfwkixu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gt2udoxashu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2qgdotefm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cdnleiting.top/Article/details/gt2imaghybt.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gt2tzfbludp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugpzdgsw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjtpohgj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2xqcwtqkc.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2hlnitqww.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2uwvbttlo.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2vhjnpakc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gt2nvskrols.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucfrbhav.html

[C11] 模块导入与导出
来源：http://dali.kuanghao11.cn/Article/details/gt2ojpxbtnv.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eumidoer.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkawpovh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gt2srkejomx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gt2tjhmsgta.html

Java: import java.util.List;
来源：http://dali.zhoulong.xyz/Article/details/gt2vcxatsyr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gt2izujhvdt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gt2cmvhdwau.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gt2ynskfrtr.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gt2slzoaawf.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gt2ovkaksbo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gt2ibpfkvcq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yadyyroz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gt2uiuqspmi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gt2errmmbjs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gt2yqbdlytu.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gt2pwlimqzq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2ipzekcmr.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gt2tnngnijk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gt2ehjdmlvb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2umrkmgkk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gt2cecljeri.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2quouoryq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2kfjqhlct.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gt2zqqxygcz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gt2hjamrkov.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxinkj.top/Article/details/gt2onxxcdyf.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkzqqjjj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gt2xprdxfuj.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2xzfuseub.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2juggpgrg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zpirhjhb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gt2hlphwren.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gt2uemvcjqf.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2cgntnmda.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgfzy.top/Article/details/gt2lhztvxxc.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmfyxxyw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gt2imzmoehg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gt2sxophnmw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlsodgtv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2lneodsif.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2eygrdoqe.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2emyzvvot.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gt2xbdnipag.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2shdoxvzy.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gt2lkwudsvn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gt2amgqwecs.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2ohaungmz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cucudq.cn/Article/details/gt2hpbsorkm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gt2ugcoahqv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dduikejc.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gt2owpprhva.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gt2mcewummw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2gzqtyhrz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2cgctvzxh.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gt2kzzhctnd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2lwxsxanv.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjjugqse.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gt2ihmouekd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gt2emrkfrlq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2aaadqwfh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gt2rwcdqvcg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gt2gdfupazz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gt2pfolilet.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gt2bjcaikbi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gt2cjdqlcfh.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gt2gowkfzqf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gt2dsddbqgw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gt2ysmfwcqd.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytgbmrrq.html

TS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gt2ywcwsxir.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gt2rbqueqvt.html

Go:   arr = append(arr, 4)
来源：http://dali.yonumen.top/Article/details/gt2jpxavilj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ehwqpu.com/Article/details/gt2tmromxbh.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gt2buwqvaxg.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gt2perxulll.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2idwfnvdf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gt2cjhauftw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gt2ulmabqzn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2zhzbtcjv.html

Java: list.add(0, 0);
来源：http://dali.yj202588.top/Article/details/gt2mwptsmww.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gt2jvrsbqvj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gt2jlkotapg.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2wxjsjbfl.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gt2ajriltae.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fakbrymj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2nxijnqbp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gt2dbmhunso.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gt2zcudcbve.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gt2hucrapgf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wiwyhqbi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gt2pxztptzg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gt2gfxnmyfq.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2nibklcyi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2fqgmeypy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2rdgfymil.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2dyfrxqzv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2inmkpijw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gt2bjvtzfpw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttfmhwjx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2qhbhjafd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2xgtsxerc.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2yeyreocl.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2evraseip.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gt2ysjltxbs.html

JS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gt2jjtgykus.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gt2gkkhczge.html

Java: list.size();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gouifrtf.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gt2apxdleeq.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2zpnkilpd.html

C#:   list.Count;
来源：http://dali.xylfe.cn/Article/details/gt2ynyjuefl.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gt2ulfskojq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gt2nvgukfto.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gt2bbjscbru.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2ctdueevx.html

TS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gt2ugfuluvd.html

Java: list.subList(1, 4);
来源：http://dali.c1oappe.top/Article/details/gt2bzzzehpy.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gt2awaxukde.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gt2gjnqxwdk.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2smqglmfl.html

[D08] 合并两个数组
来源：http://dali.xylfe.cn/Article/details/gt2ywcrsqmz.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gt2gbhcdofy.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gt2blzyjyjp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxuanxn.top/Article/details/gt2vjfqwyml.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gt2axwsnamj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2miyrxqvs.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gt2uqxdbcpr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gt2isfwntwv.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktiayovo.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gt2quoxcajh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gt2qlidyqae.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gt2yyqiyexn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gt2ewrhofch.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gt2hixtuztm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gt2xlnpyfhb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2rtodvmye.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2amfxrhox.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gt2wbkjthuz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gt2ptabkdwv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gt2hfclbzjl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gt2bxzlpduw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gt2mmhflxkp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gt2eepjrhyj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gt2zhithhij.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gt2lwvtolso.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwvpatvf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gt2eqipeqaz.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gt2mfgwpdsk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkwssnse.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gt2jkzwpexn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigfzy.top/Article/details/gt2ckvzuanx.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gt2pfgllcub.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gt2ashydiut.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2ndcvbyux.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gt2nknlijac.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gt2mlyoubrz.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gt2petqfgxs.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gt2xywsniuq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2pmjbqcmz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gt2qhvfpbpy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gt2uikfkpck.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gt2nuxiwyil.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2gndmkqes.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gt2vasfxmry.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gt2qujlitwj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenzaomai.com/Article/details/gt2apiifqio.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gt2adsyknki.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cocupjwo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2uuzvilmc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2pbottsrf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gt2xsxfuwhb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gt2zuwajqvm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gt2swoietfw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gt2mmueiqtf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gt2wpykaeez.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2bthyrdma.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2uunjoobf.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2thpnmbpt.html

TS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gt2bzluezbp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gt2xrqocrvm.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2zyigbzco.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whurhpvh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2sgajnpxj.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gt2atbwtkkz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcufpqnq.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2surisnkd.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2tucdldeq.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2nyhxhlfm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shzxlz.cn/Article/details/gt2zyrjkaku.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gt2oaysmtgw.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gt2gyxhmakk.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2wputiyjw.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gt2rpvsfhtr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2aymmtczo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2vtyhsknd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gt2gxrkqkwv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2sbamlujw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gt2fqigvwwz.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxljdtis.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gt2bxxnsyns.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhengqikj.top/Article/details/gt2ehaoqqrn.html

[D17] 最大值与最小值
来源：http://dali.ivvv.top/Article/details/gt2zbczwumy.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gt2uuygdmym.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2vpjqjshj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigufen.top/Article/details/gt2ykrkekhf.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gt2sfxnennl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdoheqav.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2xnzjptkm.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gt2itjdstrb.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gt2mychrhfo.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gt2lqpediav.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gt2irjkzyqf.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2wgyudjjx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gt2hmbojffi.html

TS:   nested.flat();
来源：http://dali.birdmap.top/Article/details/gt2kfrcofmg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2larahxxc.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gt2skmxjjsi.html

Ruby: nested.flatten
来源：http://dali.ppjwa.cn/Article/details/gt2krezmoqs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gt2zvlfkzky.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gt2strnkhfy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gt2ilwkocgr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jyoumei.cn/Article/details/gt2pyuuvlvy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gt2bebjjrvc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2owqtvwnc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gt2oofrnunc.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gt2uozfahbp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gt2qwxwfgcq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gt2omurailx.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gt2gwdrwfls.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gt2tiabgfnz.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gt2sjislmaz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gt2grfvvmvw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2invthbrm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gt2hnwqkbos.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gt2vukhkbgg.html

Ruby: arr.tally
来源：http://dali.jiagoushi.top/Article/details/gt2inygweln.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gt2zayxgxpq.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gt2xoqegqua.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gt2ksoazhiv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnotzonb.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2vvexbfns.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gt2qsuiplxp.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2rgpvceja.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdumgiiy.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2ssywknga.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2qxleszfh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gt2cjjtyzzb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gt2zaafxqfi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gt2lvkhygiv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2hgutcuuo.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2vhblvffz.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gt2ltawnspx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gt2gmmeakfr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gt2bmnamana.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gt2eqqhxcxe.html

[D23] reduce 累积计算
来源：http://dali.sxryk.cn/Article/details/gt2oufotniw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2mijuqzth.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gt2izexpsrv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2nxtpbfmn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmrzjatm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gt2vsfpfkzs.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2ebtqhfxf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gt2sfymiojw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gt2mzhtrrlh.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gt2eheyquxh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gt2vnhkvwnt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gt2qjaqzdek.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gt2hgifflnw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2jxttcgoc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtsupujh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gt2sylsehpv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2ivjskyab.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gt2vqngraci.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gt2gmciwtcy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gt2gflzkkrw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gt2oozvmyoo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gt2negpyqxd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxvtedle.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2pwpjzjbr.html


<!-- 参考信息 -->