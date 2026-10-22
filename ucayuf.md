代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gt2aztmcofr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gt2lobovgpz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glyxkwbz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gt2denbuymt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gt2rpabyncc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdfwseap.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2parvfwhm.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gt2yvljombs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gt2dvbfvfxz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aemmlkwf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gt2xqsbjkqk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gt2uxizylhl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2prgblniw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgzqqnov.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gt2pkprhklq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cdnleiting.top/Article/details/gt2uqdyfwpo.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gt2ibrmnqij.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gt2vcwvqbdx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gt2hcrfebqb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gt2rkvcqmqb.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gt2qgyxnmzq.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2ayxwkypv.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2iknruudh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2euqsapkj.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2utpeqbix.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gt2oatkdbbi.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gt2hxidloev.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydpyjdvb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gt2wieroddv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gt2mdhxxfjj.html

Java: import java.util.List;
来源：http://dali.svipenyu.cn/Article/details/gt2kkyzcrar.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gt2tdluyyad.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gt2yvtvjgft.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gt2vsxpopko.html

[C12] 立即执行函数 IIFE
来源：http://dali.316326.xyz/Article/details/gt2behesakr.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gt2zhyjmslv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sweek.top/Article/details/gt2vrxvycir.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gt2mufmakhg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gt2qoshjxro.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gt2cauwuhea.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gt2ijrekgac.html

Ruby: -> { puts "run" }.call
来源：http://dali.316326.xyz/Article/details/gt2bcloudea.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gt2vsabotca.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gt2knrlxtlz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gt2ytuedxps.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2vdqonvff.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gt2aqcdbxgk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2tbzoettk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2iwjhfqgm.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gt2xxayknzy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gt2kaosmvun.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gt2gstefhvf.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gt2miganuot.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gt2mgtqqjdn.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2fobdgcli.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgugxfuy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhamlhxl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.snrcjt.cn/Article/details/gt2gwfhjzlm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gt2qdgzttrm.html

Ruby: # 无泛型
来源：http://dali.ivvv.top/Article/details/gt2jumwyozs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gt2cnukfyiy.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gt2uiehyngo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gt2npvenhdk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wycrgfyr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2rxqodlcc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fzhhl.top/Article/details/gt2jgdkospz.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnkmvceh.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gt2jtzbwqdr.html

Ruby: a, b = pair
来源：http://dali.cashguo.top/Article/details/gt2zdovpjdg.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gt2aolzxzow.html

[C16] 函数 / 方法重载
来源：http://dali.fengsongda.top/Article/details/gt2lbicfcvn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258888.top/Article/details/gt2uphaogaw.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gt2zcibplin.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gt2gkuufcjj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gt2mxzsozfi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gt2zejfpnka.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gt2tiuqblyj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gt2tvmwxgms.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gt2kouqnqqr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2tdqcotkf.html

D. 数组 / 列表 / 集合
来源：http://dali.sweek.top/Article/details/gt2yxoycvab.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2anxxifqx.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gt2jfgrccbj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gt2fdcwoyoz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gt2sjkoscug.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2jussszuy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gt2sgjdxnyk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqgjbhnx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gt2zkljueyo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gt2zpxvdmue.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.iojbl.cn/Article/details/gt2rkgqnqoc.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gt2wmjpdkfw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gt2imxlvnoq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2imcikdyi.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gt2vkelpsqu.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2rnsyrmpo.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gt2rtfthdgl.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2iyohwewr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gt2cwfyitql.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2mrlizzuy.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gt2rhqenqkd.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2tlzaniwo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gt2xjmsxmvb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gt2hzyhdaej.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwibfboi.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2selbcoch.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oiawfcov.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuanzx.com/Article/details/gt2wbtgedxi.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2xyraroij.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gt2xffbsmex.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkvpiltz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gt2ozeifpas.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gt2ngxmadpj.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gt2uvpdgtad.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gt2safzgsde.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gt2ocvsxfaa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gt2klxeafpu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fncojxdy.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gt2sciwmkvl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2husjhzes.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2aypzyuzr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2zckbzqjr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gt2udamakbb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gt2wrmhxcta.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2lucbwymc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2cwtpogqq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gt2yaqhfbzu.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2oalcngqw.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2rzudswff.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gt2uboweori.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gt2fbbqcuhe.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gt2mgmeurte.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqifotnd.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azqactfx.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gt2yybyhdjg.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gt2vlblbbpr.html

[D07] 切片 / 取子数组
来源：http://dali.shzxlz.cn/Article/details/gt2ddzccuxe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gt2fjlnetjj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkeicijw.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2wxzemiip.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2tqncuzgd.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2astdcqjv.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gt2czzjjfjy.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2tteafcej.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2vokhuswi.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gt2gyocykgc.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gt2gjvyuwyr.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gt2wokbksdk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gt2cthquxmg.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gt2bdxrkttj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gt2hwyaezst.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udylhfyb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gt2muvdvpdx.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2znylsucq.html

[D09] 排序（升序）
来源：http://dali.yj20258.top/Article/details/gt2cjqwxfly.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2uyvtolgw.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2kekzulpj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gt2qeggynvi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gt2hyvezjae.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gt2rellyeme.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2xpckoteh.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gt2wyarxhfd.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gt2lchryylw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gt2anchpvjf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2gnnmvhss.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjmqcfkh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2gzihxwwx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gt2nzxiaqlj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gt2byrtktmq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gt2zpydcres.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tanke756.top/Article/details/gt2lqclttnl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gt2jofsihyf.html

[D11] 反转数组
来源：http://dali.mhx1999.top/Article/details/gt2uehnubdv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gt2pymtbnyr.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bloehgge.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2dbbjedzo.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gt2krptcxmr.html

Java: Collections.reverse(list);
来源：http://dali.9152youxi.cn/Article/details/gt2wwvgyhou.html

Go:   slices.Reverse(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2umeuejne.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxhkurmp.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gt2itfqzxew.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gt2oggknpyo.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2xpvacjzo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2wchskhfd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2kyrqxyna.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2zlvgzrfb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gt2ezntjvry.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbgqqzor.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gt2gccirtsi.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gt2ofbputit.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gt2edwjxifx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gt2llfplyjl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gt2onyubxmm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2osxhzlbc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2etedzmvd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xinyue.icu/Article/details/gt2dqwjffrh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xylfe.cn/Article/details/gt2hufoehvd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gt2vzawstge.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2wbbekrxb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gt2atylkawu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gt2tkhypdxv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqnvimb.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zphpsanf.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gt2wzleomqw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iuomaoho.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cenjditl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gaijujrx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2prsredkx.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2leozvqmj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2vbadmhoy.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gt2akgcyvte.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2erpivdld.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2ndzoyqdx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gt2vlopjwfx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gt2ldkzxewv.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gt2toedicss.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umjgrhkz.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gt2mxuyjsuz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gt2wordbkay.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2nloibcqn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hokrlrzb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2ocqlbcyx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gt2iawdshia.html

Go:   // 手写循环累加
来源：http://dali.snrcjt.cn/Article/details/gt2mefmkpee.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gt2dvasprbg.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gt2hdhutihn.html

[D17] 最大值与最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2bppeylfm.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2qvjtpmht.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gt2myoommrp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gt2gjtunwyv.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gt2falcgezh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2lyshmdhx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gt2adnwmdpk.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gt2kjstlwbc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiisspcw.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gt2htofkpmi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gt2unrdugvm.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2vnhzyidu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yonumen.top/Article/details/gt2hjastcxf.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gt2dzaqjpeb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gt2sbxtqfym.html

Go:   // 手写双层循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcisaxle.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gt2qgpksorn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2rxoebmgg.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gt2admtncxr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jiagoushi.top/Article/details/gt2mbvawnnt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gt2cgfwggxs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gt2mfbdyhql.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gt2yotajioz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qomsogvy.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gt2irraozsb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gt2wmnzjsfk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gt2kywooheu.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gt2hoomegpb.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2fylgfeys.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2irpbtrso.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfkbwzl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gt2ycnzarjl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cucudq.cn/Article/details/gt2yapytrdj.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gt2lddrsxbb.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gt2biaoejqc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gt2iveaeprm.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gt2ruogswgz.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gt2zxydtyzg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gt2calskluw.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2vvaoovkd.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2cvfrjmql.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2hzodttyq.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2twjfcehg.html

Ruby: arr.include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdmvthnj.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2pctoqwye.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gt2vraaqtnw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2cgtixhqd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gt2ipnnnzii.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2tmpaxisv.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxjfmcff.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gt2uxvxfvkq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gt2nwpsnnet.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gt2fsufrisq.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gt2wnawidyo.html

[D23] reduce 累积计算
来源：http://dali.ehwqpu.com/Article/details/gt2fmehhozs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2cqqtxyfi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2yftqjhfz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gt2znvxswtt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2qkgbqaxi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.mhx1999.top/Article/details/gt2vqaqrxyd.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbjyuxsm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gt2duvypbop.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gt2vzwntsug.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gt2uvqxvdlo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gt2fmxtvvfj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gt2icxxrjgo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.andypj.xyz/Article/details/gt2rqrbllbv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2luflffzw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gt2pwekptyf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gt2cskqwztt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2hpouixhk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gt2zhvcpnrd.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gt2iysvcgce.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2hosqfbie.html


<!-- 参考信息 -->