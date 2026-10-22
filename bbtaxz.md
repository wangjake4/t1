代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtsxxjqnck.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gtfvwefqdr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtxhzhjlut.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtyarzffbw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtybqdsklu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.meibo888.top/Article/details/gtmdrdbkmi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtcatwjtyv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gtyyzfxvja.html

[C10] 变量作用域
来源：http://dali.gaohongyu789.top/Article/details/gtrjsocuer.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtevpqbimh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtjcrzqbpp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yueranfly.top/Article/details/gtpnevnqtm.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtrefllpbt.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtfogpfnia.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gtcehdbaff.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gtipmqpvrx.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gtaaswrwhq.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gtcxgwnwpl.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gtftdqcxhe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.andypj.xyz/Article/details/gtogzmitmi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtcvnbgxeu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtwesnvzxw.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gtclzblxvv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtyweuthyz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gtdxktsfva.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gtdfsimktm.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gtikqpthaz.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gtbmezwufj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gtsgfkllkk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtseukggqe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtqqgabtcn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gtmzxvshfp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gtewfwmpco.html

Ruby: -> { puts "run" }.call
来源：http://dali.quarkkingdee.top/Article/details/gtgstlrbza.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gtrpszeset.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtfcuhdyao.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtfjrkqagk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtjcnqeeoj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gtzpmmrhpw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtrdawpzab.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtppwnaubh.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtieotahsp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gtozwcvoum.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtxckopjoe.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gtjvlqhqat.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gtqkvwkynj.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtoikksmka.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gtacbsgdot.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gtzlzilkcd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gtyapdgrcw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gtndqtvjem.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtvlemgapl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gtgmdytqjt.html

[C15] 解构 / 展开参数
来源：http://dali.cdnleiting.top/Article/details/gthaasbjdq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.smart0.xyz/Article/details/gtorpnrpls.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gtgteakfcx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtxuthmbtf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.redwolf501.top/Article/details/gtvpkvukng.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gtqwmkbnqz.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gtmwbgvzua.html

Ruby: a, b = pair
来源：http://dali.jiagoushi.top/Article/details/gtsemmvltw.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gtybwoppsr.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtwdvlbflm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtlhdivycd.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtdlkdblzy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gtzqnpcxih.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gthatogeoj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtvvzjuthb.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtaxdqnzmi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gtvyhlvsjy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gtuvzqwybo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwvrrqtlk.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gtbuwzrfpy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjvitjbpm.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtfezhvndv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtssjlwome.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gthswljhim.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmaosmqq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gtrwgxpvcw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zdqjudy.top/Article/details/gtmjxyozex.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gtbkhnciup.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gtwzmldevc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gtcvugrlcl.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gtnabsdznl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gtfvsgjwjj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gtuannboxu.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtjwpzbatr.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtzrcbwryp.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtetdvmwhx.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtstlkbgyl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gtejusqwxz.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gtjfghylmb.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzefxcvsp.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtvrjgfudl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtxispisda.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtdkhhsqeo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtagiutmpd.html

Java: list.add(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtvbrjddyj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtxsjnkqyb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gtmfrfzlkb.html

C#:   list.Insert(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtpeyqochu.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtngrrouek.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gtdpinfxpi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gtnugygtpe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gtpmsjdiib.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gtxpvmtgmd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtxvpifqme.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtoqpfiokh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtpuqqumxs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtwmmpmmht.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtkugejkul.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtnonperfe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtlwczuhjh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtzidbmgpd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtpkgxddih.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtxvwgtsqj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtnaepyeep.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gterqaihmr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtjxchxxzn.html

[D06] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtvycjhcyw.html

Py:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gtimtdmaxk.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtasspnqbh.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtsgpkamet.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifharqvu.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtzojjgfkp.html

Go:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtbonmozwm.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtcjoynnyq.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtjimzepgs.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gtxevrmhss.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gtfbmkmxjg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gtgnocmkew.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtkjqyljyf.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtdqxxeoec.html

Java: list.subList(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtbgvgxlmg.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtlwkppuyr.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtwasqtngr.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gtemjhokgn.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gtxpjphloc.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gthrotcfmd.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtwabehvqx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gtlfagfepv.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtpoqbvrre.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gtglayudev.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtwieottfi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gtkwsqmvee.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gtyctxtsck.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gtoehraipm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtofudzlpz.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gtfespufsf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gtddgefrwa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gthpkumtqr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guowangkeji.top/Article/details/gtaugsvnzh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtwsgrfwen.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtchfyvgff.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtvstodeab.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sxryk.cn/Article/details/gtsdjnoatb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gtfepinwxo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtnomfdjdx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtynkfftlw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtvmvbwgsz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstuocltl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gtzwceoful.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shzxlz.cn/Article/details/gtjwavonfv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gtfvasqelw.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtsvkplkww.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gthecgqqky.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqupfdvp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gtkoykveol.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtuislchdt.html

Java: Collections.reverse(list);
来源：http://dali.andypj.xyz/Article/details/gtrlesnuiv.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejawcgfo.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtswafxobk.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gtmxhjnwvp.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssytrhxh.html

Py:   arr.index(x);  x in arr
来源：http://dali.gotoacloud.top/Article/details/gtksusrcbh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukampevv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtxiozlvxf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtcuizcfqh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gtkgqxkcax.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtndemvxei.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gtyojbashx.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gtfbfwjkmm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtrkmfgmgb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gtaesrtzzv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gtxtroqadn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtnkusywbw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtacqtiksx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gteyopopht.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gtcmmpjoow.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gtiepdvldu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gtbzccaybv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gtoltdusob.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtilzidgzt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtdqzkbydy.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gttlfwuofa.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtkkqubqvi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtbsrptoaz.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtiorkzfwx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtmpzmqtbb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gtnwellxcq.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtpzgqyfui.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtxmcupgqm.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gtpitofdco.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtrnqyiuik.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtgltxsmcs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gthjdzfjdm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtromwmqam.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gtqwgchdym.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gtytrhqkeu.html

[D16] 求和与平均值
来源：http://dali.hysaishi.cn/Article/details/gtyobgwlvn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtazfyuuux.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtpcaxjesr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtljqfryjb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtfgyuoxda.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gthfrzsuea.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtdxjubqxg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gtdigxpamn.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gtlgzpnava.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gteqvqlrpe.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpivdkfl.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gtzkzignms.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.bjfxy.top/Article/details/gttelkrngd.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtubspjgqt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtxbwaxaof.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnkwtyek.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gtzrofuvuy.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gtfdskbbsh.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gtjfahxjde.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gthhdwhwfz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtrtudqgnz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gtkjcszqif.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gtgwutcitw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gtesxbkyry.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gtjeymgpkf.html

Ruby: nested.flatten
来源：http://dali.sweek.top/Article/details/gtdouobygl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtjmkofoqw.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtnhemkert.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gttqhtvtfd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gtyxxpgufp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gtgdaygcqc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtbxmddyoc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gtvhiiqwud.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gttohhttox.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gtwpzmrcdv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gtptpelynu.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtgaemxwxc.html

Py:   Counter(arr)
来源：http://dali.cucudq.cn/Article/details/gtqktnimxr.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gtxnbyvcxf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gttiozefkf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtqhujvmtz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gtqsvjsafc.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gttopdpsoq.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gtlwbbhqvx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gtsadrwxiu.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtyemwscwq.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gtrbuuyigp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gtmqotmctp.html

JS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gtechkhtow.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtisbuwnxr.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gtqhrsinzj.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtezuahnzb.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtzaaesdgj.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtllfkuhvu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pengpengdd.cyou/Article/details/gtgowqqchh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yvedp.cn/Article/details/gtdygqamxh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gtnrschonz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtixksxiil.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gtkycovrfb.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gtkyirpprd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.mhx1999.top/Article/details/gtscdhpttp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gtgvxtdizb.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gtdhlqvnwe.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtxijeyuto.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtxabfyxoz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gtrdmtzvay.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtjwcntfkj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtndxqufmv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtgdaqmyjx.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtavnrzfmi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gtskhcvzbw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gtmxbdhabc.html

[D24] 字典 / Map 基本操作
来源：http://dali.tian-w.cn/Article/details/gtcvvxymfl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gtnzepeusz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtaovdmfsd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtbnsekhtg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtsdpcuvlu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtilqxqkms.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gtwammkygb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gthibolbgb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gtufrtxrsg.html

[D25] Set 集合去重与交并差
来源：http://dali.jyoumei.cn/Article/details/gtncnptrao.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtxuvictxd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtfipeozov.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gteyfbxqeo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjflhvbkd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtjnjoldvc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtgedlhaft.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gtvlfnifre.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gtvsglyefv.html

[D26] 数组转字符串
来源：http://dali.zhengqikj.top/Article/details/gtptmfdhnh.html


<!-- 参考信息 -->