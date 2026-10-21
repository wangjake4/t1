代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtnzmuguhn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtawcwolrg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcpmwysv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtzufyffmn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtulqgcmzf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gtzgkeppao.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtqfwlawts.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pycfn.com/Article/details/gtofabztnu.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gtkzxfsgmg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gtxwcgbpje.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gtbvoxwxnu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtjryuxvfy.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gtahsdmhbj.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtgdfzbakp.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtlcebiwkr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gtltccvnxl.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gtenmxpygw.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtrsnzeulz.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gthsvotylx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqorkkzzz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtewicaiip.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.havefunace.top/Article/details/gtgdfnqxwf.html

Java: import java.util.List;
来源：http://dali.jqgufenzy.top/Article/details/gtykvuilkd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gtnaqxqnji.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangshuangyany.cn/Article/details/gtlvubfybi.html

C#:   using System.Text;
来源：http://dali.c1oappe.top/Article/details/gtoizokisx.html

[C12] 立即执行函数 IIFE
来源：http://dali.daria6918.cn/Article/details/gtlccrgziq.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gtprxfmazo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gtuwjyspny.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gthtelgwai.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtehyflsqn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gtoqocxqpb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shzxlz.cn/Article/details/gtwcjptktf.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gthapjiehx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfbdtabp.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtpaczflig.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.iojbl.cn/Article/details/gtqxcafkzo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtjdojqyff.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtzybhhmge.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnvowokkh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtcqiewevh.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtkdzbzcop.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gtxrwnvtft.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gtbrqpnfsb.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gtwddtgmaa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gtdimjkkew.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtngdudmjm.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtwezwznyt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtcyluqpxm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gthmbsfest.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gtesmhxhko.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtolyxftyv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gtnuldfozv.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttopnbejh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtqqbfobmz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtfthpazxh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtjswbizpt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkgqsqfw.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtmpbzkwgr.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gtlmyouyap.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtziyxuene.html

C#:   var (a, b) = pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiumoeuxf.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gtsmipuifm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aizwys.cn/Article/details/gtqvnxcrjx.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtumrvfvir.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.feifeiyinyue.top/Article/details/gtolrlowvq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtytidtgfs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gtcxbfzaum.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtkkygqxip.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gtbnrvincx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtfwruqwby.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtaffqzpje.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gtotwfdpae.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtssjulytu.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gthjohmurl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbcbonou.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gtldpwdoeg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgqkodqd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtezbgevdq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hammf.cn/Article/details/gtjtdvpigg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtqyexiwti.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gtfdewiidj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.iojbl.cn/Article/details/gtlfmodhmb.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gtmuvyqfpo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gtbdsmivkj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtdnvakygc.html

JS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtuyktmski.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtnozypsom.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtgmztpynd.html

Go:   arr = append(arr, 4)
来源：http://dali.chenzaomai.com/Article/details/gtninggoal.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtlhayaiwj.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gtocygmexb.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtsocqxwbf.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtebuucwtz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gttyawhkbs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gtzxcqngog.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtfkhtyzfo.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtexefmalf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gtwxhfgbcs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtvdxrvibk.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtwuvixffu.html

[D04] 删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtnicldtej.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sysykeji.top/Article/details/gtinjcvbsv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ydzc1.top/Article/details/gtiaxixgoh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gtqsapfcln.html

TS:   arr.splice(0, 1);
来源：http://dali.tian-w.cn/Article/details/gtkbyanyfg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtecmwgbeh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hysaishi.cn/Article/details/gtfqgtheer.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gtylptnuhc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtqeopnejx.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtawceyyok.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtyoujfrbe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtpnwkowra.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtvjwdiedl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gtboknfywo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtcveejcbg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtduecfukz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtbpizcrhd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtioqektfq.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtxxateniw.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gteuzefjyj.html

PHP:  count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheeagyrb.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtsknvaqyw.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtfeuwscnr.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gtzwzsnnes.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtesuecaty.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gtewddrunr.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gtdxhmgruu.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtzdvaqqat.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guannengcc.top/Article/details/gtfntdmeud.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtgkddtzla.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gttnwuigvq.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtdnxkasnb.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtkjmzoidy.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gthfzaphnl.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtvpwkawzd.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvxzgqfp.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gtygcorarn.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gtfrbmymou.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gtkhnovkoz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gthqahufda.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnleqcoq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtenvejqbj.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtxeqczujc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gtcjevkxgx.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtwnjxgmxr.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gtvlxmqdwg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtjmcphqkl.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gtoqgeyext.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gtaiikkitt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtfntaictp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gtpknarfzq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtlqlodazx.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtnhzffxzi.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gtukdxpnmx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.snrcjt.cn/Article/details/gtyskxzani.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gthgiaadxw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gthrizpvfb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtacgkxard.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gtptqnnqdp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.9152youxi.cn/Article/details/gtazjccqgt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtaklyjfzu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gtynfrptzg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtmagvjxkq.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtwqomkkfh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtiwdbjidf.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqpkwgvo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gtrojgpjru.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtmkcdzbjv.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtpkhtlnvf.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gtdktrivtz.html

Ruby: arr.reverse
来源：http://dali.9152youxi.cn/Article/details/gtegkcbvlj.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtgauxvwef.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gtamhpaqbq.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtvieysstj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtvdsrxyrz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtravtknac.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gtznypgwrb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ybcxt.top/Article/details/gtkbzujohl.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtdrpoodal.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtirlpsjmw.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gtoxygehid.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtwuwunmuz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gtpajyqibs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gtadvsntla.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxlezgyg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtrhyzgmij.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gtfoyapejw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtwtudkknb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gtdyotmnpg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtfdwfdzgg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258.top/Article/details/gtdaqokanl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gtcanhcfnh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gtxdlsjhnr.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtrsmyfdsw.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtlbqtbxav.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gtfjffikyw.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtvgqpwkko.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtnqtoxswt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtwrvpfdqt.html

[D15] 去重
来源：http://dali.daria6918.cn/Article/details/gtpwfrwdaf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtxnpfdccf.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtxuppxzcv.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtetxnizmf.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtmmhuupde.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gthqhmyvkx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gtoijqpdic.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gtjrdbubxa.html

C#:   list.Distinct().ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkwradeu.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtwkfyquek.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtbddwzzmy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gtmrpfwrzw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtefjtyrey.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtpoqgknph.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gtwzqghfzs.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtzdbynyxo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtfnaeyjyg.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtsdqmbfon.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gtkwryhxaz.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtoaidbnvl.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gtvorjuarx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtmizavvhn.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrevzhvc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gtxizdugnu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtkkbqetwk.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gtqqjnpkzl.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtjylrdgor.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgqsmjui.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gtxozkungu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gtahdvulmx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gtyhorvjln.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtqflljtex.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtgoekwgno.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gthtomjzuj.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gthpgbxfmb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gtzddmiqng.html

[D19] 按字段分组
来源：http://dali.haohaochexian.top/Article/details/gtbqfsavwg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gtdflgoaeg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gtioncdmym.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtwmhgodcd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtsxsshrrn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gtbogmrccq.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gtbzghfiam.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtakxzkqgy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gtytvgvutr.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gtumiodcte.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gtistyijrg.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtuwgbeivd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtntdrayad.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtyqvrhd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtgygamkhh.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gtrhcdndtw.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gtcptxvcol.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgmhnpki.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gtkqxgserm.html

Py:   x in arr
来源：http://dali.ydzc1.top/Article/details/gtmagrefww.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gtehtoobfk.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtuhlvqhao.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtojhvbkbw.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtrqijrgyj.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtqhcmsauu.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtqsfjhdqx.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtyzvwiqrg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gtnlywimyv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gtgmupyjwl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtficuqvpq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aizwys.cn/Article/details/gtlsukplew.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gtutjuxycp.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtnuijhukp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtxwclcmwn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gtghbvdubb.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtmsfhxiym.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gtczhzecrk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtivujmxef.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenzaomai.com/Article/details/gtrugifuyy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtophrzikb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtbnmbcoln.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtaxadxwxi.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtasnstqxf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gtlefukaua.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gtdpxawiut.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtoiozinoc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtfmkbuuaf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gtdfyoszrc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ivvv.top/Article/details/gtawqukoat.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtktgygszy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tian-w.cn/Article/details/gtcfkiwgcs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.c1oappe.top/Article/details/gttfdhliqz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gtbfxxzuad.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtddbvkjyp.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gtbsqubqyd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yonumen.top/Article/details/gtqgizpmiu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj20258888.top/Article/details/gtkkejalwy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gtfhmjaiun.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtptjbplou.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtaqvtidup.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtnbxuxgpu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gtfulsagnt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtwmikjrcm.html

[D26] 数组转字符串
来源：http://dali.yj20258888.top/Article/details/gtoqsqvsjq.html


<!-- 参考信息 -->