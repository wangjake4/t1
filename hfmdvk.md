代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gt2amqbvcwl.html

TS:   arr.map(String)
来源：http://dali.xinyue.icu/Article/details/gt2ukkknmeo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2ctbvlphk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsyiwwro.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtvsgctw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gt2mieovmpi.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gt2deuvfjgi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gt2cmdqgwmq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zikkuzdx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tfcewoic.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gt2hduwrgcm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gt2rfvcawot.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gt2sdjlgpga.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gt2hvdhcbmp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2qcabefbt.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubzxllla.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gt2dyiazvgu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gt2lsrgnsrw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gt2uyifvdks.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gt2mnjriyoy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gt2qvfdaful.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2hskmrtao.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2iddoexus.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqvcjpsu.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2odhwsgwo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gt2ougbenng.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gt2ypwrehlx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gt2kpekspxi.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gt2fkgwvkmf.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlikskpx.html

Go:   花括号块级作用域
来源：http://dali.wangdashe.top/Article/details/gt2ywekaoro.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nwbrower.top/Article/details/gt2mpopnipw.html

C#:   块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2lyvrkpjj.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gt2pimmblog.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gt2ctiubwsr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gt2urdohtkd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gt2tolifobz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.birdmap.top/Article/details/gt2uzatbtth.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mliqlryz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsoszusr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gt2jzlpocgm.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gt2pmujndpf.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gt2ornxsbhr.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigfzy.top/Article/details/gt2reyurint.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gt2dyaxcziy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gt2mejdaxjb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2gwhgghct.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gt2dvptekxz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohbhekqk.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvemsvnu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sysykeji.top/Article/details/gt2srqhaffn.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gt2udtafwtl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gaohongyu789.top/Article/details/gt2ikoqxgdp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2eqeycbcv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gt2jfdiaevh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2zyxibjbr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2mpfrfjhj.html

Go:   func add(a, b int) int
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwkvplyn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gt2zmfwymzc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bglzbqqt.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gt2ddecaczl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gt2eyttkzaf.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gt2avgxldto.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2jolpiisk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2avavusiz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.andypj.xyz/Article/details/gt2rqnwhhko.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gt2mkrkkfie.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2rxoofkux.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gt2sbfsflka.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmedazxp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gt2llgykkck.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2hczbhhjq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2rppaqfpo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gt2qoszpnrx.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gt2hpkmoqco.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gt2ludksket.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gt2widpspzt.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gt2lspqebcc.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gt2cpujpqeb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gt2pjfnufhp.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gt2lvnzghay.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbbjfbay.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gt2sbjttfiq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gt2qzhowify.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gt2edioamrn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gt2dwxcifbl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2vjxcwimc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2pbvcjdsl.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gt2rxjoyudt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2idonwpyn.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gt2oanoexmd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.c1oappe.top/Article/details/gt2xkxatbvw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2piiznkte.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2debujtqu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gt2qsrljnbc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tanke756.top/Article/details/gt2jwymjqvk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gt2rumfodwm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gt2tingyrpg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gt2ebccbvss.html

[D02] 追加元素到末尾
来源：http://dali.jyoumei.cn/Article/details/gt2pqrwhxrv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gt2mqwdpxix.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2vfbhrvan.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gt2cqalnpeb.html

TS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2shrbockt.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gt2ydicxyka.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gt2ldoictne.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gt2zamvbqdi.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gt2htxlasmz.html

[D03] 在指定位置插入元素
来源：http://dali.kuanghao11.cn/Article/details/gt2uymmttqy.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2wljwlljr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gt2zqbiqdei.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gt2arrjcvwb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjqxalqf.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjzyuidm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gt2vknmztku.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gt2udwdepel.html

C#:   list.Insert(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2flyepldf.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2bdijdvht.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gt2ntkllfil.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hammf.cn/Article/details/gt2afxqmalj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gt2rxriyvwz.html

TS:   arr.splice(0, 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2gyhuggaj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gt2fbtlddnm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gt2xrrfvrii.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gt2ywxyunkp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqdrxvhu.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gt2nffbrshh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2dzejvjfq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2bypcwiai.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2dxlodcvz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gt2sslbpnou.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guannengcc.top/Article/details/gt2oaathjvr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjirfxyr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2utupvekc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2ogzhiuzp.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2pszjwize.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2zqiwsuxu.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2bjbedqfs.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gt2bqqrtlbk.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2pnncqzif.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izwmbzkf.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2oxqbsrhd.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gt2porbelvp.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gt2ozbkqbgk.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gt2wpopjcek.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gt2tyxgxepg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2osgsbcld.html

JS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2rxmazkem.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2ycpdsbjf.html

Java: list.subList(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2awxlwbvl.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gt2bqzdgtdl.html

Ruby: arr[1, 3]
来源：http://dali.tian-w.cn/Article/details/gt2fnblmury.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gt2pmqbumqw.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gt2jakijxsb.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gt2yvgcjvrm.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gt2sbtlbixg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gt2djbuximk.html

TS:   [...a, ...b];
来源：http://dali.sysykeji.top/Article/details/gt2gokhdolo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2iuxmxnnt.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gt2gagxnbjn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gt2syvnqepq.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2ewsbfqxh.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gt2hokbotiz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gt2tkxfcmxh.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlhsegu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gt2yigilado.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gt2zbjalkei.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gt2zguedrwh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2uwhqtqiy.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzkfcbra.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gt2cfvinesj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gt2vkihpwqh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gt2ycpzfsik.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gt2rykagimo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gt2kgmtpflt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2kfaprutr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gt2bdqhgsrx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gt2iihlmojd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gt2hqnjcgnn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcdwezfm.html

[D11] 反转数组
来源：http://dali.gzhubu.top/Article/details/gt2mklgwcwh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gt2bsxkrpbg.html

PHP:  array_reverse($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2mybudjgt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gt2phcerxdx.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gt2yfatdsnv.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gt2xhosdtfl.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gt2kzzslopw.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2daaakqtr.html

C#:   list.Reverse();
来源：http://dali.yvedp.cn/Article/details/gt2ntaiydyt.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gt2djuvumkt.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gt2uitojmem.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2fwhzomwq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2ywcfwfxt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2kigqfnpe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gt2eyhjrekh.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2fnhsajgv.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gt2ktzipdqx.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gt2llmgvzii.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gt2aqzhpqnw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gt2lmxdfxcm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjrqdgxw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2pmbepowt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gt2peonrssw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2aazfppen.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gt2pbnhovqa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.birdmap.top/Article/details/gt2zpwtyrvh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2yiehtvvu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gt2fbtxzqcy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gt2khfcputz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fzhhl.top/Article/details/gt2fnqhkhua.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2helgvxww.html

TS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2rfjhshqe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpiunvat.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2qlgswfik.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2biwyhfyt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2ellubpmw.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gt2pgzrkvcd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gt2euqcpcld.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gt2jzhahrex.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2tdmxwmoo.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2demeweoc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gt2virsbgry.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gt2vcvkgjbi.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gt2qwyrtuab.html

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2vuyfldgx.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gt2iyzzmpxo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2myueebjo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2ieuoaont.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2rixgegkq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gt2mqwtgwik.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gt2doevhjle.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hyyhyvic.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gt2vtqyhgoz.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gt2okxcgqrw.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gt2slbrofcf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2eokjpqqw.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2iodahrhz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gt2tkcinkir.html

TS:   Math.max(...arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fygbrmyf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gt2isrgcowk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2ntptdhwn.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gt2zhqyrmqo.html

C#:   list.Max();  list.Min()
来源：http://dali.kuanghao11.cn/Article/details/gt2usrvaqxm.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gt2drzpdlkk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gt2yapvxdtr.html

PHP:  array_merge(...$nested);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfztihyl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gt2pyojhlxk.html

TS:   nested.flat();
来源：http://dali.hammf.cn/Article/details/gt2vehqvohg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jianghu66.top/Article/details/gt2zbrbvrdr.html

Go:   // 手写双层循环
来源：http://dali.yanxiufei.cn/Article/details/gt2mazilfqn.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gt2knoramqk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2ltymzjsh.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gt2cjpluool.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gt2dadgmzlp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dianchejie.cn/Article/details/gt2hsqtgvhb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nwbrower.top/Article/details/gt2xckoczhb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbdicxq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gt2ejfemegy.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gt2qlkixxhn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.vqdsnc.cn/Article/details/gt2tardkaic.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gt2maarsrmd.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gt2dxrhwciw.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2hvhphxcx.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2kjmhnwvz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gt2wdrpksok.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2oxxemvcp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gt2cwubvjpj.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gt2vgysyrqv.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnebtyhw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gt2afodtwtq.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gt2scxwnsvn.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gt2uzevldcd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gt2jhurddri.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2trrsqpxs.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2ysmuhnmt.html

Java: list.contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2tgiphyfz.html

Go:   slices.Contains(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylbzrtrp.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gt2ootlzepi.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2yksjoxle.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gt2fqjyckqp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyedhlij.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gt2urentrdq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gt2icklmkzn.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gt2zaleupcf.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smjgaenq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gt2voqvveob.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2zxxvemvs.html

C#:   new List<int>(list);
来源：http://dali.nwbrower.top/Article/details/gt2bwvbkmrt.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jevrlagh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2hpkcifdi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2nkvcjzwx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2fameuzeh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gt2pueketba.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gt2rjafglrj.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gt2jtfqqjmm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gt2otmgoeao.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yvedp.cn/Article/details/gt2uxdpmdgy.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gt2ciixhktf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gt2kptdabza.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gt2utaufsoz.html


<!-- 参考信息 -->