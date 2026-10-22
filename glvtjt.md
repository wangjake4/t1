代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gtgivgtitu.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gtboabrgws.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gtusirbotl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtgdiqgffi.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gtbygfynmd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cdnleiting.top/Article/details/gtehfhmcvx.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtfhtdnboc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gtezeheeon.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gtnesxyxrb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gttjedkihq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gttumzsxrf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gtfengxybg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtlesskwei.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daxiang520.top/Article/details/gtsbvycxzj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtslhfwrnc.html

[C09] 递归
来源：http://dali.yvedp.cn/Article/details/gtidpfzkib.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtxxwfepty.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtuixplfkn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtxakmzalu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtnrjyioea.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gtopmroqxp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cashguo.top/Article/details/gtxrrigipn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gtefputpmr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtrkogffrv.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtrktmxktd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gtytawmasq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gtbrkztior.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtukxdnsvh.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gthnqkoiny.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtflrgbcyl.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqoehbvt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtpgbbpyia.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtqhbndksk.html

[C11] 模块导入与导出
来源：http://dali.fengsongda.top/Article/details/gtqhsgfzxd.html

Py:   from module import func
来源：http://dali.zhoulong.xyz/Article/details/gtizvjjspg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gtmlgdzymf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtlcwlyryz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gtcvbonneg.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gtuhactzds.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gtzbexeikq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gtujpvnyxh.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtpasfwsoy.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gtmxfrhykc.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpslczshi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gtbcrzvmqa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gtnwkvvryn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtdmitdirf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gtdcjtqeyv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gtpdrudbfc.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gtwnemvgcy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gthbvjlvrd.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gtbliwumpq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpncreet.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtqtzmviwc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gtcvplezmc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtgvimxjja.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtehtdvwry.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gtjrtqsias.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gtxgjfxgbu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gtjaktatdb.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtgxirzekh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gtuprniqqq.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtjelzlgnj.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtirlabnoc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluvvmxux.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gtjbrxgmzq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtygwbvnit.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gtqmnfpeyg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpkxeell.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gtzfrrwuhd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shzxlz.cn/Article/details/gthcavkbfg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gtdrvwxazt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gtipjcxlmp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtzteuqchs.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gtsxygvlft.html

Go:   // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtpemftmyi.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gtsogwlstm.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gtyxxokwke.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gtrebssadb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtmiikcpyc.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gtnupvxmgv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtliygdn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gtgppczeiw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gtwhndzlhd.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtcltolkvs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gtyxxzhgbu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guannengcc.top/Article/details/gtqdeddbyw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjbouxkru.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gtjyhoepry.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpcyaocmu.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gttptrfhat.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cucudq.cn/Article/details/gtoedrslqd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gtsctqezyd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtcruuvwun.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gtxdvjsaba.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtjsxvbmof.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gtnwqsdywl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtdmwypzmk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gtvyubgjjq.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gtredgzfrr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtchoigata.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtbxvcimmv.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtzfxaesbc.html

TS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtcsujafzp.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gticfgemje.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gtukpsvygm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtwxixheyo.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gtyzqhzmsp.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gtqixnezzy.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gtzazugjbw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtwqgyuxzw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gtjjbniwto.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtrndpxzjm.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtcdgvubhx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtjzjamghz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gtnryuziej.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gtnehylqnt.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtqmmjxssx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxuanxn.top/Article/details/gtjadlfjls.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtcrszeyte.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangtech.top/Article/details/gterexottp.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gtkovzgwia.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gtvwugaupy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cucudq.cn/Article/details/gtkqlsxolf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gtcphioxph.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gtzfrwvfmi.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtgdfrtmvo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtanihosvp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtshbaqgkr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtbdqphrmi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gtcsxkrfzp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gtcxfldfxc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtrufoznor.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtdqpmmrfe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtiqpxfozw.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtearovrlg.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtzntwvjhc.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtfabsikua.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzjibyev.html

TS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtzuarnmvk.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gtaeslxgyc.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtjoagixiz.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gtehsssdvu.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtgqkqdsto.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gtmkdiktis.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gtxeocjzlz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gtwzqqfkfd.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gthyhbprle.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtadbuixbs.html

Java: list.subList(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtxjynntcv.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gtihzsnvkc.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtwydpuisj.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gteeuzmcdo.html

[D08] 合并两个数组
来源：http://dali.zhoulong.xyz/Article/details/gtvxpanucq.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtgadkjwuy.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gtobyzfnsi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gogol.net.cn/Article/details/gtacmywjao.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gtcuyafmtt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtsqdrbhlt.html

Go:   append(a, b...)
来源：http://dali.hnxiangtu.top/Article/details/gtrdouslzd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtokbyoevj.html

C#:   a.Concat(b).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtlnwbahwy.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtcwvvmsdm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtacajoqyp.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtrgxygauc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufiewhku.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtkxvltotq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gtbcbizkjo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtvaenfowg.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtvlivlkwn.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gtrgpqkjqe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtybrzmaly.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtguwagkpm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtfjuteszp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gtdpkhsluy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtaiclenup.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtslwrijqv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gtjuskncrd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aibaodan.cn/Article/details/gtzjjerhyb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbhadpyk.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gtgobnlxtk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gtuckuicqf.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtterfpqxu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gtudxhglcd.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtppsvvlts.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gtdpbqwssw.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gtvexozvtu.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtpzfgzrur.html

C#:   list.Reverse();
来源：http://dali.birdmap.top/Article/details/gttymqgwra.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gtvwrdfkvw.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gtefptytbi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtrxguybpd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtkpezrcde.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtlsuasvju.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gttgkvsuys.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtmbzvpxzm.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gtrivbepik.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtsuuhqxiu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gtelfblfnr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtxnqnkyqm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtpqdassss.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gteqpyrqwd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtzpghmfwn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gtucvjclwa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gttqwqhjbk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtgcajshyu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangdashe.top/Article/details/gtdedxpobl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gtzpczrikz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtkqvdrvky.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtpvzvhqsa.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtrkgyiokn.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqowqniwv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigufen.top/Article/details/gteprldtbw.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtxoqsglrg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtxyxiffmh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtxgojanlh.html

[D15] 去重
来源：http://dali.fengsongda.top/Article/details/gtdhnkftko.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtggimridx.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlugkrjkk.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtttwbgvbe.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtasenqdig.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtmqeowdvd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gthlltuort.html

Ruby: arr.uniq
来源：http://dali.zhengqikj.top/Article/details/gtzeygrdjn.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtkbuszcau.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gthqwrgtvy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcicgjfbk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqsdspql.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtefyofawj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtdsmdwtyy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtlnacqeqs.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gtbmuqqsek.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gtdkxysuwa.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gtabenmzgz.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gtqjuyyfse.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gtvuafswrb.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gthlqgdguc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gtxyljswje.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtcvjwxwtk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gtbgsuoepm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258888.top/Article/details/gtticdefuw.html

Ruby: arr.max;  arr.min
来源：http://dali.smart0.xyz/Article/details/gtysnsizeu.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gtpdduhnxb.html

[D18] 扁平化嵌套数组
来源：http://dali.haohaochexian.top/Article/details/gtguabfzaz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtidgikrfx.html

PHP:  array_merge(...$nested);
来源：http://dali.dianchejie.cn/Article/details/gtqgxyqlmw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dianchejie.cn/Article/details/gtbrgpngkp.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtruyvglnj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtodyqahea.html

Go:   // 手写双层循环
来源：http://dali.daxiang520.top/Article/details/gtgzlvdbtk.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtsxcowywu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gtafihofki.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtbylxiwbc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gthsfjmwwc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.birdmap.top/Article/details/gtjyvkfsqy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gtxatootpx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtbaujqpip.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gtyfaoeaux.html

Go:   // 手写 map[string][]T
来源：http://dali.havefunace.top/Article/details/gthnptffwu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gtncwlskwt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenlongwang.top/Article/details/gtwnifqxso.html

[D20] 统计每个元素出现次数
来源：http://dali.sufxvd.cn/Article/details/gteyxoudoj.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gtveuynxrl.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gtsntqklxn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtezhhugps.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtjwelwhlv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gtlxwmurdp.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gtftisunec.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpfsdqsr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gthfamcexc.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gtpphktkoj.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtrmbfntci.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gttqpxyrso.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtpjespwrq.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtewmopzig.html

Java: list.contains(x)
来源：http://dali.sysykeji.top/Article/details/gtzrdrjuiz.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtobfzbiqh.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtxmsbqjzy.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtvolgeelf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gturtowofg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gtfvayidng.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gaohongyu789.top/Article/details/gtuobppflc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gtbjriefdv.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gthvbamtnh.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtrzyrlpln.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gthupazvvg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gtjpcyaqyd.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtcblfjbwx.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhuepjfh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gtutzspxwq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gtsjmgrxdq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtyyvhefel.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xylfe.cn/Article/details/gtsvqkclgw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gtqihummrz.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtrigvlxqd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtpbxzdvzr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtnzsypivr.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkgvolyc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnlvnnkr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gtpqvcydfa.html


<!-- 参考信息 -->