代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gticojkmma.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtacqrsgun.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteylcvggz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvhxbvmb.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyeejxnh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guowangkeji.top/Article/details/gtsilzppsy.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtvuiplnsb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gtahsmqlie.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gtvrugfqfl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtbxqyyuea.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxrmmoahu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gtthylbffw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gttsbgowwe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gtaambfoew.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjtzpugx.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gtgpyzyhrv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtnwrtvkid.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtelqhoyhu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnowifeut.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtedcngcwq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtmeeexelr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigfzy.top/Article/details/gtgrjgtbjv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtyzjuuuno.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gtzrazxhtc.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gtlaxmsccu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtuvivdlnn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gtfcccoqxj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmeeqiqj.html

TS:   同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gteozijjbe.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gthoqounfg.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtobnhfalp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gtzyvjupyk.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gttybanyjn.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtiqoacxrh.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gtahvrndwa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gthpoakljm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttrlhyeo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gtoxtwibpk.html

Java: import java.util.List;
来源：http://dali.haohaochexian.top/Article/details/gtpndrfsmf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gtyrlsbaur.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtygidxwue.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gttdvkriuz.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuanzx.com/Article/details/gtlafkmlox.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gtkhjvyebs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtiuervyoc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtuzwmnlle.html

TS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtefymxkdx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxpjioxk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtwloqfxcd.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gtcytirlbo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxawdpeze.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtuuuocxtj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gogol.net.cn/Article/details/gtdfpsmdkb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtrakjosfu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hywenlv.cn/Article/details/gtimrczqcv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtkefqpxmc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtyuosxmef.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gtlpfwxltc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj202588.top/Article/details/gtfiouwzxg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gtswhjvhqe.html

[C14] 泛型函数
来源：http://dali.havefunace.top/Article/details/gtsbtszcyy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gthtbbhsae.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtewwbvcvd.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gthqbigooq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gthozdxhha.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.9152youxi.cn/Article/details/gtwvhsbxom.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtypwaaivb.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtbgiinizg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gtyyjwrmzb.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gtmlhizhzw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtgcsbnvok.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gtcfniynbz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtxviickqv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gtrkhxgcak.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtstjaxcsz.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtwzbepobh.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gtewrbvsuf.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gtekjxurgi.html

[C16] 函数 / 方法重载
来源：http://dali.sysykeji.top/Article/details/gtfhotwode.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gtbbypchca.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gtappjzmcu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xinyue.icu/Article/details/gtwkkzsknv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gtrnffbtmb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gthtdspblf.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gthgowaebq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkspdyjza.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtselipaiv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtrwfrnued.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gtdnrhjirh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxglqjibl.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gtltgsxzpm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssivkbwe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gthuinposp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuanzx.com/Article/details/gtsaocgnag.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gtovjsjirl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gtxtaxjane.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gtrcosaala.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gthiygsgae.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtgujyqvth.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtvvgmcotv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtxwzjljej.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gthhofaioy.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtrxpfxqlo.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtwcerogag.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtkhmldgck.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gtrnwnshct.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtwoceeljk.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gtxzcdutqj.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gtsjswkfpv.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqlfchgl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gtperlphok.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtbqpxgetz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gtefcdjgdy.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtngqsusts.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtrbfkxfbu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakmtygjv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtvlikqxsq.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtbtcqyclj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gtlbxstzmx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqmmueqq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gtpvwzpqrg.html

TS:   arr.splice(0, 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtspczfzqi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gtsaqzmxgg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gtqerhxhbg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtkqlllhaw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gtchguvyds.html

[D05] 访问与修改元素
来源：http://dali.pycfn.com/Article/details/gtzfjhdemb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtkcknvtbk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtvbmhqzsq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtqslxafyi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtcpybvxif.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gtzqdbkaym.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtjiadnimq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtcosckehu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtaoirmtgv.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtilkqwzgr.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtzhmyspvj.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtnwtyxyua.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtbryhpmie.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtpdiinemj.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtbseppdmm.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzoxgdbk.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswmrsdki.html

C#:   list.Count;
来源：http://dali.yongpay.top/Article/details/gtdheikgtm.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gtcbgjhwof.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guannengcc.top/Article/details/gtdanjvvez.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gtwrgmguiv.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtlnsddoua.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhxreprh.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gthphmccer.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gtbgzylzka.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtityzxtsj.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtzefczntb.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtzrqspyac.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gtlvujfjvn.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtjjuqevry.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtehjecvea.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gtfslvuvht.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtgohohjry.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gtdtiprgjf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gtmpgkyudl.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtokhahiwi.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gtbvctfoqk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtsrfzwjai.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gttintzgzv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gtqbicbwaz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtmdkvijfa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxyrgkzu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtsexlmwsr.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gtiaqzlvio.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gtccrbkgvx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtvzhrpcto.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gtisaywdaa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtxqwkkpfv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gttnqbyctq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtwdtqiags.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fzhhl.top/Article/details/gtcfebrnmb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gtwlqotchs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupsicutn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtdbduwoop.html

[D11] 反转数组
来源：http://dali.hywenlv.cn/Article/details/gtmivpenrz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gtrmqgzndz.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gtycjnldez.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gthxerwkea.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gtwpdamfbz.html

Java: Collections.reverse(list);
来源：http://dali.jinqigufen.top/Article/details/gtqttxmzre.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gticcqslsl.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtochrwtuj.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gtyhfwrphr.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gtaxnzfpsz.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtffepkaau.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gtstweuwhf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtprukkjmo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkwdpioe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gthrbkbkyz.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtggjkxyag.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gtwzqrfojr.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gtobpkrnzz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gtjrvdbvkj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtyhntztbs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnyiexfz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtxzapcwue.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtidubqqzx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtmycwbmyc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gtpdndnzcx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gttcdtgtrj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gtsofehxeb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gtzldcpndn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gtckjgmdyp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtfeqwcfbw.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtsxzckslf.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtjmpaplqu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gtprbfcsax.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtrzsufpbo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gthbrjnmrq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtzfokbsdz.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtjwoddquc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidcscqkg.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtoucdjbti.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtbzxtxsix.html

TS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtnepnkzah.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gthspzqvwq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gtjojfcqxy.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtxaxpaqzt.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gtsfsyprew.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gtdexdkbgk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yvedp.cn/Article/details/gticmljfbz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtzizmzpum.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtoczldqvl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtzibqulvx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gtosixbnxy.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtlecddpxh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gthsemctps.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtpimtbzjl.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gtgijywkoc.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gtpftgqicl.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtyejeomwo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtzesmcgtv.html

TS:   Math.max(...arr);
来源：http://dali.ivvv.top/Article/details/gtrjfepzil.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtnrxhsqpt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gtxqxqdrhh.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtptmtrzfq.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gtewrzpcfu.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gtreorpkiu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gtokkoaohb.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gtrphvxwkd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gtbphzzuqe.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gtjunxexlo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtxdwsjvny.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gtelrmfonc.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gtwtfgayzu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtunxaffwu.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gtuwldhzzf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtgbveijtk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigufen.top/Article/details/gtapkvtgjy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gtfloketxp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtogcjuxuz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gtblljigan.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gtyonvibym.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtibiekzri.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gtgqrysvfn.html

[D20] 统计每个元素出现次数
来源：http://dali.0kj1m.cn/Article/details/gthsvxlslk.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtwkeskgnk.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gttpkkugvc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctmjvqwx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gttkdkvrec.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gthyngaoka.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtwikdip.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gtwdjrxmlb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhixingplan.top/Article/details/gtsuwvyzvp.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtwrpxuhad.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtwmhzpalh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gttdandnta.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtdxreatje.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtdmyrmktx.html

Java: list.contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtbonbvxfj.html

Go:   slices.Contains(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtyhcpenwi.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gtcbwqypiq.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtxykxykfd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtfvkdkwjk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gtzvsfkgxk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhiwuduotai.top/Article/details/gtqnqhoehf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtbinjmddf.html

TS:   [...arr];
来源：http://dali.gzhubu.top/Article/details/gtrveovodd.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gtypnvaald.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hfpthk.cn/Article/details/gtzngsznxn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gthhkpuilc.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeiczehz.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gtwuzcpabj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gthgghznkp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtypklbdsz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvehfyxb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzogdrwzt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangshuangyany.cn/Article/details/gtloecrubt.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtyyknrylt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtxafumvlx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gtsxfjzdvs.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gtkvupitrm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zycfv.cn/Article/details/gtxpzzakdc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gtqsytzoly.html


<!-- 参考信息 -->