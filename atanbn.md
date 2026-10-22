代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gt2laacvozt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gt2mkkchmku.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gt2ldlkwzxd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gt2ffkonqul.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2issjubhh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2xwwkqrgc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2mjpftmqs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gt2ickvnooy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gt2jirydzfj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenlongwang.top/Article/details/gt2njkrbidx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2gfznfnny.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxtfwpm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2lzphahje.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gt2zgjscgvb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gt2iidakysk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2hdexflzn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gt2lskeyneh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gt2yrjncvxq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2bupsmnga.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gt2rzsivuiq.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gt2xtopdqin.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gt2tjbrllod.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gt2rpuwzbxz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gt2smauldud.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gt2zbqoapoq.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gt2fbzszvod.html

Go:   花括号块级作用域
来源：http://dali.birdmap.top/Article/details/gt2vauajimh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.andypj.xyz/Article/details/gt2jgwioaec.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2opniqcoi.html

[C11] 模块导入与导出
来源：http://dali.guannengcc.top/Article/details/gt2cangsetk.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gt2cpjthjlw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fengsongda.top/Article/details/gt2omqrfzmc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2qkjoxrjm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gt2ashukhsx.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gt2mxrbdezy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gt2cjnkzhfw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gt2uoxmeebl.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gt2belruoql.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gt2feffvyzg.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gt2aeakhiqo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gt2vrrsqypi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gt2igejmkvf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gt2trlscjcm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pycfn.com/Article/details/gt2hhmcvlik.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gt2cjdoshzx.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtvuqxsx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gt2neunfmwh.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yegoruji.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gt2gdpgydqi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2raezkrbc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gt2bloesxfy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2irvtppdp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2huxcauqw.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gt2esorgkso.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cdnleiting.top/Article/details/gt2darcfopv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gt2yxotqivy.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gt2wbckvzxm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gt2ogbplayg.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2chgczwpm.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2owxlssoq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gt2nsnvgvud.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2arraausu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gt2cwhvekyo.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gt2lzbdftti.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gt2dtsdblad.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gt2vyrbexgg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gt2pomcnynj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gt2pwgxwtps.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2udcwpzfa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gt2jalqndze.html

Java: // 无解构
来源：http://dali.yonumen.top/Article/details/gt2uhojpcnh.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gt2yitqzshm.html

Ruby: a, b = pair
来源：http://dali.feifeiyinyue.top/Article/details/gt2afthfrpd.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gt2ujkaeagg.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gt2carasxqa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gt2javoovlb.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gt2gvqqovys.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2acfsawrf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2mevjzkia.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ypayfnau.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlyuedgo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gt2tmzlrsvo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guannengcc.top/Article/details/gt2jmsjacns.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2cdnlwlsy.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gt2wprksigp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2mgekrreb.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gt2ikdlydmt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gt2hnkvhsjm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnqzz.top/Article/details/gt2eyudacws.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gt2zjwzlwnw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gt2ueptcdzc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgufenzy.top/Article/details/gt2zivxpyuq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmvshpff.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gt2vlgatxhk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gt2dbjwqwaw.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gt2wuhdbjbe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gt2jvqopbgm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gt2rdaiergt.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2gyyvymsq.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lchivjvr.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gt2qmvltsqe.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2chlfwuyg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gt2reuqycns.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gt2ysmaxrad.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gt2bujdsycc.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2uufagwxx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.smart0.xyz/Article/details/gt2uinguqjq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gt2rdmclcxa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2bomqmoac.html

Java: list.add(0, 0);
来源：http://dali.yj202588.top/Article/details/gt2ntozxncu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gt2iawrnavu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gt2wztzsuyk.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gt2rddjzkhz.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdadbpky.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gt2blhcfydd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gt2rpfvnhsm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gt2egllseyv.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gt2yufbrsmv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vijbsobr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gt2zbwxwfsp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxinkj.top/Article/details/gt2empdzpws.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gt2luiazhor.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gt2fhrcspga.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2fuhqcijd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2blcrvvsi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2bkvckhvv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gt2qsfbnloj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gt2podqvehh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2tveqpgbk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gt2vzqvpjjn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2vmvsxpol.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxkjbhcq.html

Py:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2pxawvidf.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibxwrkot.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gt2yttfdmqw.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2nzoobokg.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gt2zmxpedow.html

Go:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2lvslnrsg.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gt2hmmvelkn.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gt2ojzkbesq.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2yocxpvji.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gt2tugikpwf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2cmubvcdo.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gt2rdaygyih.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2xxitdmdf.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2donadygj.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gt2jmfdygkc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2dissasyp.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gt2gnoqjokm.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snqkthco.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dswkenvr.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gt2ofirghkf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gt2ecwywwgj.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gt2txjhekwq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtgtbtwf.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gt2lxjjgtfh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gt2leevfbbq.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gt2rzfynqip.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gt2recsyiwu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gt2sltzsajq.html

PHP:  sort($arr);
来源：http://dali.mhx1999.top/Article/details/gt2xufjrtko.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gt2nhmztiwt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gt2vnzopdep.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gt2vrspjyvr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gt2kpxavcly.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gt2xdqzfhah.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gt2utwowalv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gt2aguvwsve.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gt2zqlnhahb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gt2txxtqyjx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tuoabsps.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfyobnma.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gt2axwqgdjc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gt2tlsapjsq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gt2mygmoeni.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgufenzy.top/Article/details/gt2zafngczm.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gt2cnourkxc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gt2wpzjbfva.html

PHP:  array_reverse($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2avoycmxd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gt2dkkusasy.html

TS:   [...arr].reverse();
来源：http://dali.jianghu66.top/Article/details/gt2cghromoo.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2qmmqiujn.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gt2gusztwfo.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2ofgezvwk.html

C#:   list.Reverse();
来源：http://dali.meibo888.top/Article/details/gt2jksrvdqr.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gt2rgzaitwh.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gt2hiwjlqyn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gt2uluuwsvi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2ryvbench.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlukmjvo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gt2lwqxxhnp.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2qhsbuaif.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gt2zhjynadj.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gt2lqdtgtvs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gt2pectkfpn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.redwolf501.top/Article/details/gt2ajwqxrwj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gt2vrkkzoei.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2kfntgfjb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gt2nsqwhlok.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2mrymwmih.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igvqbajy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rsmavyfs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2qrzvleom.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gt2ztknduhz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gt2wtoscldo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2bewvenuh.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2iiqajmaw.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gt2tyhjcyyt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gt2vcozpdup.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2xaefvayt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2caepnysu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gt2lbzwgmue.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cshdbdfq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2ksvotvqb.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gt2ksliwntp.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2nkmatyjb.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gt2fexmdprt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gogol.net.cn/Article/details/gt2yydudcdk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awhcnujq.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gt2zvgphiij.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2iuwqvmbt.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kftkznom.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2zjditjud.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gt2zlisajnn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2fqilaruz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2umdjixkw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gt2pxownfdb.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gt2gxbhjghp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbwrbfqr.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gt2naeeeuqk.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gt2iatuqodk.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2vycklvpa.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gt2hremajkd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.0kj1m.cn/Article/details/gt2pylcfebk.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2moxuthqu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gt2fhaxguib.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gt2ftcvgihf.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gt2hmszzvpj.html

C#:   list.Max();  list.Min()
来源：http://dali.aibaodan.cn/Article/details/gt2yfvspljk.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhaduhy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gt2uvhstwdc.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gt2dndyowuq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gt2jjkodcef.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gt2exhqixwf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gt2cmnjdnvk.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gt2zxqgqpkr.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gt2nepxrnig.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zysojqvl.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gt2pmvxrrnc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gt2ofugxcxx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gt2kmdaulsz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdayinc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxmzfepv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gt2odboeced.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2derdrjto.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gt2btlhsbra.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhengqikj.top/Article/details/gt2pyjajshd.html

[D20] 统计每个元素出现次数
来源：http://dali.yonumen.top/Article/details/gt2qaqjnibq.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2piculdyv.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gt2bmlchbtx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gt2vsxkjzsc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2golfvufd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gt2hwdawnxz.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gt2grzowfvi.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gt2yhakyfyo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gt2vuplxkdx.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzyjwfge.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gt2azxozyit.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gt2ormosafq.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gt2uilvowhm.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gt2krjspugs.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2zeffhuqr.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2akykjmly.html

Ruby: arr.include?(x)
来源：http://dali.xuanzx.com/Article/details/gt2mxcmusfv.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2ptencxui.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gt2guqdbhgp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gt2utxsullr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gt2chluvncb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2scixhemw.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gt2xlbgppii.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gt2mjccupam.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gt2pmbxfrtx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhiwuduotai.top/Article/details/gt2geonvwrg.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gt2kbyaffld.html

[D23] reduce 累积计算
来源：http://dali.gzhubu.top/Article/details/gt2rijegxds.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gt2jkrnzsqb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2hrirpdyv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2rganwqbl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2aodsvilp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gt2lgzfxvln.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2thukwxyx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sysykeji.top/Article/details/gt2nwhqhfeu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2favxvomc.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gt2nxlmnrll.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gt2cieveakc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gt2pegelppz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gt2hpdpxwlp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2ruypehht.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2nzxewpgr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gt2wtxewxav.html


<!-- 参考信息 -->