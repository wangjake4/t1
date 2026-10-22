代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gt2nxizpoih.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jyoumei.cn/Article/details/gt2whexagjv.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gt2nmtbbzdm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztjibmav.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xjnjtxxz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gt2hwelxgml.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gt2zabyrizk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hammf.cn/Article/details/gt2ursdfbde.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gt2ebfmixyf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zdqjudy.top/Article/details/gt2ghqrhvou.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2degdwraj.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gt2owydsggy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2jzonkatc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gt2jhrrutqx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gt2uecankun.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2cunkvxdz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gt2tdpoxdan.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gt2cfomwjjk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2apzopffl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gt2rqdjvrah.html

[C10] 变量作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llweglmg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gt2gwlvcabq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xylfe.cn/Article/details/gt2wuqqdtwt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gt2ywodgatp.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2phbjdgjm.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2wraiwyzm.html

Go:   花括号块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2pyenilmb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gt2aqxssiro.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2ykiezgvi.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gt2ztmxwfnz.html

Py:   from module import func
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjxwhtan.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gt2fygymgss.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gt2xuzkfotz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.svipenyu.cn/Article/details/gt2erwgfioj.html

Java: import java.util.List;
来源：http://dali.hnxiangtu.top/Article/details/gt2qpfkzcoz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gt2xsjzutwr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gt2xetmznep.html

C#:   using System.Text;
来源：http://dali.gogol.net.cn/Article/details/gt2ehstcbux.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gt2vlkounhz.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gt2oevuctrj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gt2gkzcyxgr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbtfojli.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gt2siluyton.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cdnleiting.top/Article/details/gt2hiyuxjih.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gt2ghobhplu.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gt2etsepwgp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2oqlwppku.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gt2wwdekzky.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2hhrlhppb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2jbnyfirf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gt2joxkqlnc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2urikwfjc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywajcctl.html

Go:   func add(a, b int) int
来源：http://dali.c1oappe.top/Article/details/gt2ofoghlii.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gt2qkekvwfb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gt2cpxytgdl.html

[C14] 泛型函数
来源：http://dali.vqdsnc.cn/Article/details/gt2tjdqhyho.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gt2vfqeoaam.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2jcapkzbr.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckfnvbua.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gt2iwfrwpsi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gt2xrtphpvb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gt2sgmrehnh.html

Ruby: # 无泛型
来源：http://dali.birdmap.top/Article/details/gt2emvrgosr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahleqflb.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gt2vxwmwzjb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gt2pizhkopr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gt2gtzkpgto.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gt2gprfcurc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gt2xaiqqluw.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2gldwbmsh.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gt2zcrnyibi.html

Ruby: a, b = pair
来源：http://dali.gaohongyu789.top/Article/details/gt2yfsdqqsj.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gt2cwznmtsr.html

[C16] 函数 / 方法重载
来源：http://dali.smart0.xyz/Article/details/gt2bbchwoos.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gt2meofwfwc.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwlblilc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gt2tnyknwmr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfgdsjdw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lzznqccv.html

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gt2oyfeygpp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gt2pfuhkjog.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gt2hilmxqpl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2arlmynlk.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gt2mkjamesr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2atwfmunk.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odjgcfrj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hiodqgzc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2fdsvxujs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gt2kptliarq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yongpay.top/Article/details/gt2wtqnwxuv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gt2klxlmlgi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gt2zsgnvrhz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gt2fbrlehum.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gt2srhdlpvf.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gt2ybfxldex.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gt2yhvwbkoa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gt2xjtzmyyq.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gt2ogozsuls.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gt2qgafbgwk.html

Java: list.add(4);
来源：http://dali.sysykeji.top/Article/details/gt2tznmhzts.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gt2fhzxovuc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gt2jlqdzcpy.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gt2bislvuzq.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gt2ofgfnlgc.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gt2joiukfpi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuanzhike.top/Article/details/gt2fpymgdfp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ppjwa.cn/Article/details/gt2agcudgxm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2uhlrnmpk.html

Java: list.add(0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2xohoihem.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gt2rvkekfpk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gt2ixkdqszg.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2jpnszlut.html

[D04] 删除元素
来源：http://dali.zycfv.cn/Article/details/gt2nduzdqfc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gt2kfktslyd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gt2knliyhma.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gt2apufqpil.html

TS:   arr.splice(0, 1);
来源：http://dali.jianghu66.top/Article/details/gt2lrdrhhqg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrkjbrbc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gt2capkuzrs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gt2imyhjsvz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkpygmvq.html

[D05] 访问与修改元素
来源：http://dali.yonumen.top/Article/details/gt2ofwfyjok.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2domwmqsl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxcjnogb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2fevkfuiz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gt2xfucakxp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gt2bxkwzdvm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gt2qxchndhb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2dklozdmc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2gsxsdhqm.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gt2gywknwhk.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2gvuwgreo.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gt2sitxlzqk.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2rjaztzec.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gt2yszmttdv.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gt2tdbnostk.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2mkaeoqrg.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gt2mlaipiup.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gt2cjyluepp.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gt2bpwswyjo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gt2dpuekbxh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2adjhmjtw.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2jeghkhcq.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2izfglqdq.html

Java: list.subList(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2vgjcgqpa.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gt2vqpvbhmi.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gt2rolhjrvp.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gt2khfclegk.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gt2zelzvxth.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xopvbqad.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gt2klbydsli.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gt2evattiey.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqrlyzrp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gt2lpwactmz.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gt2xdwerjps.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gt2jjfyxqnc.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2xcvaklfs.html

[D09] 排序（升序）
来源：http://dali.zdqjudy.top/Article/details/gt2vxzoivlu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gt2xmadgnnd.html

PHP:  sort($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2dfqtdfnc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulaxsnhk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhoulong.xyz/Article/details/gt2mbzzrets.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbxuutaa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydgxbple.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2ttrkknvz.html

C#:   list.Sort();
来源：http://dali.nanxinkj.top/Article/details/gt2zljehnkw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gt2lwwvgyim.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gt2mmwntvjl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2ouzkmqyp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyszbxko.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2uuzsuxms.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258888.top/Article/details/gt2iykmpega.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gt2boragtgz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gt2sygkffeo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gt2lrjpmjru.html

[D11] 反转数组
来源：http://dali.hywenlv.cn/Article/details/gt2ddzffrod.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cashguo.top/Article/details/gt2algirbao.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gt2ywgdjkva.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bukjnjxu.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gt2nutehnjc.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gt2hrywjjwx.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gt2qbucwvyl.html

Ruby: arr.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywmfmgee.html

C#:   list.Reverse();
来源：http://dali.zhongyouzk.top/Article/details/gt2jnzertlg.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gt2exclapxw.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2bvhucves.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2fkdbwmip.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfbumsri.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmqbdfma.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcchxdjd.html

Go:   slices.Index(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2mzpqsbuj.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gt2hzsfktkt.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gt2hljyjqmr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gt2aaiyruqg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gt2xamzvyly.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gt2zijtnnxt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2avtbjloe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2lskokpua.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yonumen.top/Article/details/gt2syjdwvko.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gt2jouvbhzt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gt2vbfxtusj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhkpuwqf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gt2mjmsyjom.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gt2qvcqgiod.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2xrlqroqb.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fiwrihvq.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2xparzhmh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.birdmap.top/Article/details/gt2dcwvlnhl.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gt2yzmgnoao.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gt2wrnhwkrj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2klvhqzsu.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzokyyhe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gt2czozsabb.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2alrhbpik.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2iehoqnwl.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2haeozkpw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gt2puuwlxqw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gt2hhxakgrz.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gt2roupxqtc.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtnrqfhv.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gt2bzluiqnu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2ackvnqkd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qcunjtkg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2yindldge.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2cavenhyg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2wokhvtch.html

Go:   // 手写循环累加
来源：http://dali.mhx1999.top/Article/details/gt2mpsnxtbi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2excxkqmx.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gt2jpzfyyew.html

[D17] 最大值与最小值
来源：http://dali.ehwqpu.com/Article/details/gt2pljuhwav.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gt2ekvpdzak.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehrhtrsp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhgzkppb.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gt2mleshgvv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gt2xsiuizhu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2crdalxdq.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gt2dnfxvbfp.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gt2ndxwkvsg.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2suximuqm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gt2imifrann.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gt2kslvkmim.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gt2pbgludhg.html

TS:   nested.flat();
来源：http://dali.guowangkeji.top/Article/details/gt2xnkpdybh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2plhwqgct.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gt2ycsgeisc.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gt2ybbqzxyc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2lxfjopun.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gt2dlbncrlq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2mwxyjfgr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gt2cfwstjpb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gt2bpidugyo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gt2xtnrtgpt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.snrcjt.cn/Article/details/gt2gmpzwqnp.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gt2dbvjeohf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gt2fewaduan.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gt2htkkkagd.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gt2emgqnqig.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlljjvwv.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2qqctcicf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2fatkoogd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gt2wmbppkkc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gt2edmbsnmf.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gt2xaxnptnt.html

Ruby: arr.tally
来源：http://dali.ydzc1.top/Article/details/gt2ttpgejpc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gt2gkbvivgn.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gt2tjozbzjk.html

Py:   x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2heckrcrd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2zghekroy.html

JS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2tzmwezhm.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2nebsqsvu.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrzxfxcp.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gt2myucjazb.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2rkatpodb.html

C#:   list.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdciksjv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gt2paaibnna.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2jaxosatu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gt2ttxgabrt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yiphswcf.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gt2orshoobt.html

Java: new ArrayList<>(list);
来源：http://dali.jqgfzy.top/Article/details/gt2fcqqlpfx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gt2ouyzhdpt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gt2npmrhnex.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gt2obydbyvu.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvgxwzhf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gt2zhzoptzy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gt2ncxsihax.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gt2izmaffvb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2gdsasmhc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gt2gwvnofxt.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gt2flvnzxmb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gt2tffqfger.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gt2owvyqjgs.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gt2clwdhgxl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gt2gbwathka.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gt2ajrmtozd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sxryk.cn/Article/details/gt2wgxgtqha.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gt2dkkxwgfn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnuykvtg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gt2gutcdkoc.html


<!-- 参考信息 -->