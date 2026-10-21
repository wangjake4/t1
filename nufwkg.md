代发 wailian999

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gteclwecaw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gtegwyhqzt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtblnrwdfj.html

[C09] 递归
来源：http://dali.tianlin.xyz/Article/details/gtraxcklcx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtkpwlvbch.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtnhwvrbau.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtsbokqhks.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gtjsodjlnu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtxlpjffaf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gtenifyafz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtiukefazz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gtbisvehyk.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gtutkbkauf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtliptxgfh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gtjifljymp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gtfcqsscpc.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmvglhjb.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtydwqorzc.html

Go:   花括号块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtexhdnzib.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhiwuduotai.top/Article/details/gtyocnwrdn.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtpccfdzha.html

[C11] 模块导入与导出
来源：http://dali.xylfe.cn/Article/details/gtmszwapiu.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtixhvuidi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gaohongyu789.top/Article/details/gtevcjuehz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtetolwdhc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfueevjv.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gtbnekhjoa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gtgnlwatfr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtqrekarnq.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gtitjsrvrs.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhengqikj.top/Article/details/gttdekqdnn.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gtzyseydsa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gtnxqworht.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtrmjbogpr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtbzkvqify.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gtxemccqqk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dashuyun.cn/Article/details/gtabmjogst.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gtmrakjxvb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gtgkcikdgq.html

[C13] 类型声明 / 类型注解
来源：http://dali.dashuyun.cn/Article/details/gtysdwmipw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gtaupwyong.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtadzwblks.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gtzwsagvvd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtluoyjqwf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhgcwjln.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gthgnqvhdd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gtukmrrlut.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtxxagyutb.html

[C14] 泛型函数
来源：http://dali.sweek.top/Article/details/gtixqybngc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gtmttrxqzx.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtzohwlcbr.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtriszgiox.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtunbfensa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gtdmajckhd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtfdwioggg.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gtuknpirtb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gtntigasau.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gtnovoozta.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtssxmmgri.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtelpsrgio.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtdvigwmry.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gtjveszlkv.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtanqshohb.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtuatxtkez.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtkdxdvxtu.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtdakxdkgz.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gtxcyugibg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gtlietucno.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gtenkmmexo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gtcfikawpc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gtqkdynzss.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gtwfbexnmx.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gtkhuuuood.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gtspwxgavn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guowangkeji.top/Article/details/gtopymawpk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxmthuhwq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtxklyubhk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtcgrdlwfr.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gtuwduaebo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gtfvrxqzwm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtlvkypcqj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gtzczxodqf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gtmsctejys.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gtfprimytb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gtdvonkxfo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gtrtfyovzh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nwbrower.top/Article/details/gtpfbrwyev.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnktnsol.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gtifnnelmj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtnqignijb.html

JS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtbbezrion.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtoozwmnjp.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gtxcmepkar.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtnyolprdt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gtozwznlxq.html

C#:   list.Add(4);
来源：http://dali.shzxlz.cn/Article/details/gtnzpvxgxz.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gthmvjhnfs.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gthdvrcqfl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.svipenyu.cn/Article/details/gteniemzzl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gtqhjilkht.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daxiang520.top/Article/details/gtadaagays.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtjrvdozbr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ydzc1.top/Article/details/gtrykvawpz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxuanxn.top/Article/details/gtanrlsdpm.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtlaurzsif.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gtjxrsdgsp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtxcqxowmd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtpoeurgyu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtyayhrsge.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtqmephdqs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ivvv.top/Article/details/gtzxmubgse.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gtkxeefeqk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258.top/Article/details/gtbysriule.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxinkj.top/Article/details/gtiistzpdn.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gtinakznxw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gthsbcsonl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyutwhbk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtvrakbnrf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtevrrytxh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtkflvjwaf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtpdurzpee.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gthyxknxom.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gttnzpbykf.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtfletqlrc.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtisraizxh.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtltgmfoey.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtvdlzhxkh.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrmxyjau.html

Java: list.size();
来源：http://dali.gaohongyu789.top/Article/details/gtmvtpmqcw.html

Go:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtfckgjxrd.html

Ruby: arr.length; arr.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxjrwxwf.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtpkigbeav.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtneiqxvex.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gthhmvacfp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gttfrtgtfm.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtbdeeyrjd.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gternjwnpu.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqccbcxg.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gtjlrvzdpr.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gtvcotcajf.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtusehyiyj.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtugaccwyd.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtrzmvrpzf.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtrkfqfrwy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gtlkytzahp.html

TS:   [...a, ...b];
来源：http://dali.xuanzx.com/Article/details/gtrxvdkjab.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gtiftzhkbh.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtdxonorap.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gtaeosnaib.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnitlsiso.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gtrkxjhqfw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gturxrcpmj.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gtqchuaisa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gtvtqumedb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtdsiasrnp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gtjknvkhlz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtyxokaide.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gttrlrhypt.html

C#:   list.Sort();
来源：http://dali.jlsjyb.cn/Article/details/gtilqwukfk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtynctxxcl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxwpmmna.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtqvfoaefh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtrurlrxqn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtubivyvub.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jyoumei.cn/Article/details/gtkkrlorta.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gtyrwcphxl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dianchejie.cn/Article/details/gtavuymhgk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtjnmwefsi.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gtlsclwngv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gtlbzbyklx.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtflmnewex.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtbhjdgbxq.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gtudisiyvz.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gtfcbzixut.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzfmlkhh.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtchaqqrwc.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gtlgfqvssf.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gtxqxhmzqu.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtpvihjrkd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtvkukgalt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtubehrdmx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtfzrdkzir.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gtfzwofkzi.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtklgtzvll.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gthysiajoz.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gtyimnmqax.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gtlahuphqn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gtljxasglj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtvdhoujnu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrercjsq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtmzjmawhw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gtxmhalnbu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gtoagegbqc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gthiatqxvr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtbygkhelm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtbtzahtrr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gtqvqcatgx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtjgouskrh.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtfkunjdft.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtzbluwexr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtexvfwfts.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuitekoau.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtyyzykujo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtxmpeyozp.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gtlazzoazg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gttijcbkzv.html

PHP:  array_unique($arr);
来源：http://dali.xylfe.cn/Article/details/gtyepxmrwm.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxacrabn.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtbfnldhtv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhmlauct.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtoxtsntho.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gtibbmlfgr.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtenypyfot.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtevbtvimd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gtidkdjtqf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gtsqswfucq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gttihpdczg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtrhurkajy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gtjewrhzta.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtubnvclme.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gtxlbwxobz.html

C#:   list.Sum();  list.Average()
来源：http://dali.dashuyun.cn/Article/details/gtolxdiibm.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gtznbmtrjv.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtavfjkloz.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gtwcqlupaa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gthmmakodc.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtiblrmzrv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtmggkpqdf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazdwdqbz.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gtskasptyx.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtxrwhkjif.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtddoxmxev.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gtwugttntl.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhctqjon.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghnbqmzl.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomdhbogt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gtlfqokmuy.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gtzyspbtiq.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gtagnbhafh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtcymizucd.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gtstntthxs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tian-w.cn/Article/details/gtjkzzqgzc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtiyzexzlc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gtprmlznnc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gtyvkwiiww.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gtygadnceo.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gtpcvrmbwl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.wangshuangyany.cn/Article/details/gtkuvobhra.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gtybqapsfx.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvgyeeby.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gtcphystqk.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtqdbomqhq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypmnxhir.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtibguizly.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gtamasoovw.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gtwiwujjcj.html

Ruby: arr.tally
来源：http://dali.xylfe.cn/Article/details/gttbefnhaq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gtjimdilhx.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gtxqphgbqu.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtuyzazztg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtycfmxuqx.html

JS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtvvrdcgfn.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtranyiida.html

Java: list.contains(x)
来源：http://dali.snrcjt.cn/Article/details/gthgijiaeo.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtvsmzletj.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtqaijuzpy.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtosgjvtvd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtdlxzqxai.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gtplznrwiv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sxryk.cn/Article/details/gtcauutcuc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gtqdtesbxf.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewibdkpa.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtplbvwgiv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gttskpwhiz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gtkspecral.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gtilblyvqp.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gtyssqfvco.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtkuahafqi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gtnlwqfrel.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gteyfaftmm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtiggrsbqk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xziqi.cn/Article/details/gtqcgaeefe.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtwwmghoaq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtxesftzvb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pycfn.com/Article/details/gtdlskrlkx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gtvgrudvzr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrykptzs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhvsivvt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtntjiksyl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtotiirttn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvmqoote.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gtranvleyo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtujkbhqxr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gthbiipasu.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gtqwxgaqsx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gtgfrqipqa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gtdzlietzt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtdusxhxxz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtqajuukwv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shuidangran.top/Article/details/gtkwkgrvud.html


<!-- 参考信息 -->