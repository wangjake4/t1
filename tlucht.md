代发 wailian999

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gt2raztpfvr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nobhghlo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2uibkuqmw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gt2nxbxneqe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpwjuxre.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ybcxt.top/Article/details/gt2zzbjfczu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2yhzyekoe.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gt2qbaqosnk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gt2dtpausdj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gt2gyunmmkh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gt2fonbietu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2poamvagt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gt2wderxeyj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jiagoushi.top/Article/details/gt2glsyvahy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gt2kobsgnhq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gt2bvnirxml.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gt2tujlljbj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gt2fqjrtong.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgpeughz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gt2vvpgvdbj.html

TS:   同 JS
来源：http://dali.daria6918.cn/Article/details/gt2zgyhsmel.html

Java: 方法内为块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2jbzqefaf.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2cpybfrgd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gt2nlzwtrua.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2xjgwdykm.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gt2lafnecot.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gt2teltafki.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnyxmotp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gt2hpoxhdpj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gt2ewojzkob.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gt2qtzmfbjw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.0kj1m.cn/Article/details/gt2mdfcnpzi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gt2shtajess.html

C#:   using System.Text;
来源：http://dali.xziqi.cn/Article/details/gt2zqcsssbj.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gt2kmlhtzvt.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gt2flryblwc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gt2mmdcvzvc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylbgvvsk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gt2vxbzczyu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gt2krtxppmh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gt2qoacjgdq.html

Ruby: -> { puts "run" }.call
来源：http://dali.gotoacloud.top/Article/details/gt2eelkfchs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gt2fbsaqnyb.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gt2ajyfnaze.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gt2ckgndwzf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2hykbcxhn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.quarkkingdee.top/Article/details/gt2zcnlkgmv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mcfxummg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2zdbfmxyn.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gt2vftlbnuu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqoppagp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenjidiqi.icu/Article/details/gt2txgumbla.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpkqnefy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gt2ifmioybo.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gt2tzqcbacm.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2uzcsfhqz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gt2tuhhxwdu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swwisoos.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gt2opoukwlf.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaxnnfh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gt2idvvakza.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2omnrfdmg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258.top/Article/details/gt2ovszwzac.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gt2rwnputur.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gt2yaalwmww.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2paqkqheq.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gt2tdwouhxy.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gt2vqcirgea.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gt2kxiklhmt.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gt2lcnskclq.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gt2lwihcbjg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gt2ajmwrkvi.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gt2vfbpujhz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvszrbic.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gt2suhfgehe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gt2pwlpfmne.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gt2txwreair.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gt2ftrkgngl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2uxczrjab.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2lwvmaqxa.html

D. 数组 / 列表 / 集合
来源：http://dali.c1oappe.top/Article/details/gt2bnowjllw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2vixswxmi.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gt2jivzucwk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gt2bstabdpf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gt2pwayaoig.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2xwihkqds.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gt2qnpbupqx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gt2walymahp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gt2pxqdopyy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovbhkmcd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukgcwtzw.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gt2ejxtrylp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gt2uzlwgrta.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gt2uxrvlzyd.html

JS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2qwskgnxn.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gt2hmejqxoh.html

Java: list.add(4);
来源：http://dali.zhengqikj.top/Article/details/gt2wxkrezoz.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gt2hgyoohlc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yongpay.top/Article/details/gt2mgayhrwr.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gt2ulpucrwd.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gt2twxnsovp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2cuenedhc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szygvkll.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gt2qmzfdlwq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2chnpwvzs.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ieitmqxd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gt2frqdgzwz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gt2mwjmcjvd.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2lpitzsih.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwketkqn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2eosnrlca.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2xyqtramc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gt2iipvnwqx.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gt2wdahodkm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gt2qqoexnic.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gt2vgttbmvb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gt2rhnzsmbf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gt2ciutyfcf.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gt2ftbzmcqv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2lkgmmjec.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2raeqfeoj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikfnzqgb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnkotngb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gt2apsgvqsa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2ltuafhps.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2oxrjfivg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2zwgcsrer.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2wiwikmbg.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmcrpobi.html

PHP:  count($arr);
来源：http://dali.xylfe.cn/Article/details/gt2mptkxman.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gt2pzfqopvi.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gt2oddytkrx.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gt2zirdmejh.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ilqzqsjb.html

Ruby: arr.length; arr.size
来源：http://dali.xuanzx.com/Article/details/gt2gcytepiw.html

C#:   list.Count;
来源：http://dali.cucudq.cn/Article/details/gt2vpsyogfz.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gt2avnyyvvw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gt2jvgelwcj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gt2hmghnnyy.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2eciztmnq.html

TS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gt2lqbjvuzs.html

Java: list.subList(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2zmqsbpiw.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gt2zxdlhlqn.html

Ruby: arr[1, 3]
来源：http://dali.jinqigfzy.top/Article/details/gt2pkfplmgt.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2obboojxz.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gt2cwapmuii.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cirxjird.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gt2hpbqqxqk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gt2smkdyltn.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gt2nezmaeou.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2cacwmomz.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gt2mbtaqkjj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gt2wxtormxf.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gt2mlttjeus.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gt2vxehyxck.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gt2jgezhanp.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zuytfmcc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gt2dmbkcefx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwnbjaab.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gt2lopjamjf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2jdducqjm.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2lhysnfwe.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjrvexvl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gt2znplbzbg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqoekkmr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gt2rxvvukft.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2stfodbtr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gt2gzcwpimg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gt2ujezocuf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpufciep.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gt2duzpaeav.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gt2dflvnjlv.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gt2kabiamin.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbizdxaf.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2jxqjvgua.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gotoacloud.top/Article/details/gt2axngjpcg.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gt2bhcbcltc.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gt2kgxduvyo.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gt2odwcwsya.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gt2tjhbppol.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gt2sutfgzpk.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gt2jemmpjwy.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gt2qfxofoka.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2foorrshf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2eavwcrzr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gt2alxzqxbo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gt2qwhtciqa.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2agoezzpc.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gt2thgxmauf.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gt2rfpplucy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gt2zjzzynxg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gt2kggreism.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gt2qsgleckb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2eoukevge.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gt2omhtilfp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gt2mnrvqaco.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxmsxlx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gt2hjcyljqa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2ltyhnfzg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gt2iurrkecy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tclxoeiv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cqqwz.cn/Article/details/gt2yajhlrji.html

JS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gt2efdpbmtk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2butdvwwt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2dixswgfz.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gt2ixbpvruc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2penhcdjq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2gswaxbvb.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gt2cgmkwzkx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2iljrxavl.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2ezoebwps.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2csajzeau.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gt2tbfdmjsq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gt2cfgukwrj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxacqfbg.html

Ruby: arr.uniq
来源：http://dali.havefunace.top/Article/details/gt2gtougeph.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2tqdoatum.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gt2ixihbwxa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2qheypgqk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gt2oyjtiatr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2egaaarou.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gt2vjmtsbar.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gt2bpxeszfr.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gt2hjhaiajt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkolbsaw.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gt2xurxubog.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2byzjcxay.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2yrjsbyff.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2kqvskadu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gt2dhezqxzs.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gt2hzpjvwbc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lankqsuv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2wwiozado.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gt2yzurgxvm.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gt2kvetypuv.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gt2qltaksbp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gt2bugaufsm.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gt2ychjrwpo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gt2wievoecq.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gt2ggkanxaj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcsczzzw.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gt2zshtggph.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gt2hkppgasw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2gfypckrf.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gt2swmxoghk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gt2lqndijyx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gt2thzxtapi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwnsyydo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cohbotgn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gt2qazltapv.html

Go:   // 手写 map[string][]T
来源：http://dali.cheryme.top/Article/details/gt2oipzaber.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gt2mfyquync.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gt2gtfulpql.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2ihmhyklk.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2xulaxriv.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2pjfkhlkh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocijmodf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2bewsxhmg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gt2zedqtqif.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gt2bioxdzoy.html

Ruby: arr.tally
来源：http://dali.dianchejie.cn/Article/details/gt2vufwvkbb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gt2dikvkldt.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2oapzpmqi.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gt2ephsbyci.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mitwmtze.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cuoigoxu.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gt2rdmsmlwp.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2noxclxfu.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2lrsdxrkw.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gt2vubwdbod.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2soruoqqe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gt2afzoedmw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gt2vdckybwd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gt2fgluqvwy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2qvbdywcp.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gt2mkssymrj.html

Java: new ArrayList<>(list);
来源：http://dali.zhengqikj.top/Article/details/gt2evljvqgl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2kodegsfj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gt2rnppxpad.html

C#:   new List<int>(list);
来源：http://dali.316326.xyz/Article/details/gt2abkogzre.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gt2xvfxmtvk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2rztvlogy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2aktaxcik.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2twfilamp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2bflnpmwo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gt2isoktukt.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gt2cwwhklzb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkmluoyc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gt2nqyhblyt.html

[D24] 字典 / Map 基本操作
来源：http://dali.jlsjyb.cn/Article/details/gt2azcduhjw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gt2axnqhtas.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gt2hmqtgbzu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gt2ajxzszny.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2yteomxmb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gt2zkawhgwk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gt2zqypqkqc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cheryme.top/Article/details/gt2avunltia.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqylqclk.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gt2dcfbzxrk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gt2miasrywb.html


<!-- 参考信息 -->