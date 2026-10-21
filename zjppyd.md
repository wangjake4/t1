代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gtnhfakhxh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtpaynnbbb.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtvcpuwtzs.html

[C05] 返回多个值
来源：http://dali.yonumen.top/Article/details/gtrbmptmnt.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gttgxdbdfl.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtbfyzgwdc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtzdznsbma.html

TS:   return { a, b };
来源：http://dali.cashguo.top/Article/details/gtnogjorrv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gtigtmpzmx.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtlfdpmwme.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gtivkcrnzp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gtgofdifpf.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsennvyhm.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gtkrcutvwi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnqzz.top/Article/details/gtgthjrlow.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtqlgdqhsj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gtcdcivtwg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gthpbrtdgc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ppjwa.cn/Article/details/gtrwmipomc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gtshaaczij.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtcqhwbqdv.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtophsijsr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtrjatyspp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtbaihrgme.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangshuangyany.cn/Article/details/gtthrrjcxk.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gtqgogsfpi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtwqrgcozu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtktzugmmg.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gtzxonjfht.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gtqkcsktwi.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtlaywlogg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuiizvfp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewxrcxcj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtxddqqprq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtdqlyaxru.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gaohongyu789.top/Article/details/gthqukaapv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gtpitucpaz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hysaishi.cn/Article/details/gtupjxlaba.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtuqgubgzm.html

[C09] 递归
来源：http://dali.hnqzz.top/Article/details/gtjsfpcmnl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtznywszzr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtladasdsk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtaqgtcfwl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwviasevp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gtnotuibkm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyhpigcq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtvftzgvfz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gtioidyqel.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gtrpktxwpr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuxming.cn/Article/details/gtgdkdvbat.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gtluqtxatu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtcfrpmqov.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gtvoiyqvqc.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtizlfgusi.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtsvgxellm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtwxvxxrxv.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gtqdsqjrtd.html

[C11] 模块导入与导出
来源：http://dali.fengsongda.top/Article/details/gtwbglcbot.html

Py:   from module import func
来源：http://dali.daria6918.cn/Article/details/gtsinpzmao.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtvkjiptkp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtxqqvrvpt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtxituqjjb.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtgnkkfrdr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gtzavvupbo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtaqzvodgy.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gtociyzvpf.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gtfdayzrhs.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtmsdacqle.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gtzcsrvhhq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtzkribelo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtnllailts.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gthiozocmc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yangfankeji.com/Article/details/gtropnsbdc.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhongyouzk.top/Article/details/gtkawpmyvu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gtarcxjdxj.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gtcriwqggo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gtdovtkqjb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtjzvnfktw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.snrcjt.cn/Article/details/gtelrjpnhm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauivdehc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtrnyixpok.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gtrzzrsfab.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gtugzcecit.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gtgdjelpav.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gtpyfrdgmv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.0kj1m.cn/Article/details/gtgdfhghsu.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtcvwxakbo.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtnpslgodo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gttobyvbxj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sufxvd.cn/Article/details/gtzqbjvdmd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gtmyoqfnre.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtombataac.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtrgkseokg.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtywpxcnyy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gtjclwjjtm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gtobepkaqu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtidvvyjmv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtuzzdxosy.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtslidevxb.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gtfzekexyd.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gtoilnabtp.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gtecendpin.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtckchvqiz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.haohaochexian.top/Article/details/gthfsimare.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gtwvrgxxzq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtqorgserx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gtyilrvrxw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvdlxvect.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gtsbmcyiit.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gttsybthwm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthuzkbdua.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvmbdauyz.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gtwlqialwr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtokaffoix.html

[D01] 创建数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gtodudvhlr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gtfpthsphy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtxvqyzcpc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtmhaowtlq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gtkxyvpyuf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtvfhzrran.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.iojbl.cn/Article/details/gtiqzqfllf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gtdvpuiqce.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gtkuubmpdx.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gtreszcphy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtwlxzdvbn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.birdmap.top/Article/details/gtyjybhlzv.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtscmglmva.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtqtbzgoiq.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtoebuukrg.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtcmrdusap.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gtzxxsuazz.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gthdmerjki.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gtaatgfkiw.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtlrvfhsfo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtogeqcoxd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gtpmleewyo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gtaivcbsqd.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gtewyvvjda.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtpicbexhg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gtipukernq.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtxdujeirs.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gtxpdcxssh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthithcvfv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtnqglhlga.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dianchejie.cn/Article/details/gttqaicojq.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gtxgnqtjxq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gteyeozbvh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gtnvpfaugn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gtmglmqtih.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gtlyxvtznh.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gtflfkwphk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtjsintmve.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gthhfrgivb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtekvzitft.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gtvfbnmsoc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gthqrhvxvo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtxxgeygww.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtocfgqefo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtvnpsdqzo.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtkcszpecr.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtrfvfdmbp.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtyugveokc.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gthjwcxhai.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtblgpgwbn.html

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gtxiwzavqj.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtwuwlmnee.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gtdepkasfj.html

C#:   list.Count;
来源：http://dali.jqgufenzy.top/Article/details/gtoypqlaer.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtukntgqgl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtjcparqnk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gtlqjgnzdt.html

JS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtijwfpqqo.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtmbdkglqx.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtaskdtico.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtzxfyvtdo.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtexgqryjd.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtmeobwljz.html

[D08] 合并两个数组
来源：http://dali.xuanzx.com/Article/details/gtxsrmefaq.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaucadyqx.html

PHP:  array_merge($a, $b);
来源：http://dali.feifeiyinyue.top/Article/details/gtwxwtbved.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shzxlz.cn/Article/details/gtnyklwfzt.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gtvzqabzvj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gtmzyzmhgr.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gtbjwueaft.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuhxckqk.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gtegoznibj.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtoheguuqa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtotzqlaqx.html

PHP:  sort($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtvssfvjuh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtzdvldmnt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gthkbhqjdc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gtwtaiaqwb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtfxrpkulp.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtoxqxtsfo.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gtbrvukbwy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gtgaurvdka.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gtkmkawhzo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtbtjhaqgd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtsqhqgmtf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gthmlokjdz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gtfmefscey.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodprcasa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttejhxwhe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtlwujmwjd.html

[D11] 反转数组
来源：http://dali.aibaodan.cn/Article/details/gtivsmnysf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gtfycpfsjn.html

PHP:  array_reverse($arr);
来源：http://dali.zhengqikj.top/Article/details/gtkqgltxti.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtbddqifnm.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtvnxxtttd.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtfozykycu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gtfaioydtf.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gtsxawvikv.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gtvocoafzf.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtursvgktp.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gtejatefjl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtacpdnivx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtpbkknjfg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtozlrcssp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gtfncownjk.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtecwljstu.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtnfkddepl.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gtsgwcapqd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gtgnwnxhwk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zdqjudy.top/Article/details/gttsqvubff.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtdcffvbic.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtaqhyuifo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtygstgaxp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gtasyxibin.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gtixbhsyxk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gtcitnslnf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtjcraslil.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gtebjfgsfz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gttomkvtvp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gtdlilggeq.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtonlesrih.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtoormqdiz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtomwjiiht.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpwcjomp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtmbeceokm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtlhbahntu.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtwrfzaeeu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypukndux.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtdrlxhxxt.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gtfxkvclgx.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtdnhbgzku.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtbxxttzuo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtfbemtosn.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsimjgtk.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtckzintpf.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gtsspwhyby.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtxjhukkfs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyhseoxa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtgwojeemd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvzhwtfr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtcyxqhcqm.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtcmkovaef.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gtdxgfkaen.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gtogsyzcdt.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gtvrdkoklw.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtmaxgddwm.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gtsksjuqga.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gtdctclgqf.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gthznvgzsu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtgclfyqjl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtfffwdjlx.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtftgmujcf.html

C#:   list.Max();  list.Min()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtrlbuwk.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtuznutghc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gtqpjeonyd.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuiaijal.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtebsgfdri.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gtgsnxoncd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yonumen.top/Article/details/gtbumlpoom.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtgqpmlusl.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gtxwfbuqgh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gtigkcnyit.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gthdvcnaxl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgoonetq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtylkotfbc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtbbaqbhmw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gtzonlooik.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yonumen.top/Article/details/gtkaajhneo.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gtlrdaeixo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sxryk.cn/Article/details/gtlelupmmu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtcfapiipt.html

[D20] 统计每个元素出现次数
来源：http://dali.aizwys.cn/Article/details/gtntgopvtp.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gtgcmpvgmu.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gthexfzpxt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtanmfgenb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gteltahzlr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtuqyzrkti.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gtuktkbjgi.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gtqoxqpbtq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhengqikj.top/Article/details/gtdhhykjlp.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtmhrwmunh.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gtxfvkjyoo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gtstspkplu.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtamodytkb.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gticufdyjv.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtnoclwfrj.html


<!-- 参考信息 -->