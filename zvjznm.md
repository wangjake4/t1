代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.haohaochexian.top/Article/details/gtrnvxkdxw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gtqfetadlb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gtmnfmcaou.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gtyvmtarjy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgfzy.top/Article/details/gtaztvsuyq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtdktmaswq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gtwrdsbphg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zdqjudy.top/Article/details/gtztkgehlb.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtuirudsqp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtpnjgdiyl.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtzgesqqsm.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gtipwydizr.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtwxjpdfhc.html

PHP:  return [$a, $b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqdyledu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gtnwfpkcjv.html

TS:   return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtmtljamzi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gtmnepllnb.html

Go:   return a, b
来源：http://dali.ivvv.top/Article/details/gtpfcnxlzb.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gtbnluuhna.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuuynpcm.html

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gtbzysfqvp.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gtvghrmsmv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigufen.top/Article/details/gtoyirtdsy.html

JS:   const square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtunuuvbpj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtznpbojkq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sxryk.cn/Article/details/gtvejwahek.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gtvcyyvzrl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtmnsgsynz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvupfzvx.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gttzmylfwq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gtyhzxqxlf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtnocugyqh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtqjskfecl.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtollhaygu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtvcvukjpy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.svipenyu.cn/Article/details/gtmgsikcqm.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwghfujs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cdnleiting.top/Article/details/gtyoiypbkc.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gtjmxwiiyy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtcuyzppgg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gtrkelxltc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqfwanbtj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtzovyoeqo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gtrnmilkzs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gtgntrexvu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pengpengdd.cyou/Article/details/gtazclmxle.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtkkvbrmhk.html

[C09] 递归
来源：http://dali.pengpengdd.cyou/Article/details/gtppubyqzj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtzawifdqg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtivexsmjd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtigxqfqic.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtgucleqpd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtrmdpeegi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gtgdjfbkzw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtezdlbvkn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gtxqfoogkd.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtsfnvwrfa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqvjatiq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gtcoxaqcgf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtbwarqsck.html

TS:   同 JS
来源：http://dali.yuanzhike.top/Article/details/gtdtdfekpv.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtrgngbteg.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gtxdfgugct.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.316326.xyz/Article/details/gtpwjpwrzm.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtcktklkuz.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gtuxxdjdeh.html

Py:   from module import func
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkxxldem.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gteakelfwq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtwccxquje.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gtiguqxxlg.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtayauucpv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gtvphwzzna.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gtctmppryr.html

C#:   using System.Text;
来源：http://dali.c1oappe.top/Article/details/gtcdiytdde.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gtqfodnneu.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gtmaapotge.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gtgrfuitma.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtwqsaajli.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpueuowgo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gtcegfgtel.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtxylulxbe.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gtssterjie.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gtsachlalh.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtdcvmppty.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gtvqvdisqn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtsjhegzlc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gtlplkyfft.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtzsdzmtxi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtpinwnucw.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gtkqwctzhs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtwafpciwa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sufxvd.cn/Article/details/gtcnqwkllr.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gtzzfbniuq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gtneussrlw.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gtcfmbbsfe.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtrrjtffpy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gtjssfuqmr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gtmhzfwhtx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gtuaofequy.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtpzxfulfp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gtztbnufnc.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtvgvzpalj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtpxktsjgt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gtovxmfcat.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtvzrudgpc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gtkmqvfsvo.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtwyndgzdh.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtuhhttytn.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gtpvhgqytl.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gtoccpwkmd.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtbhvoflcp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gtusjlpfyc.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtxohcokjd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtavvhlkuc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gtrskuznui.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tanke756.top/Article/details/gtkfsbosrh.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gtyzqvrduk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gtvsbnlkfq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxqomust.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzovdfdqr.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gtjzjrfbfb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtoxwgddxu.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtvlrtugwx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigfzy.top/Article/details/gthxvhojiv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtfshqohkm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gtdpdbsnrb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gtgdkdvhcc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gttahfyedf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gtkqahgypa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gtwnucelpn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gtqxyxyjht.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtcapsfkkz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gtnnoxptld.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gtlcmjrxqp.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtjltlrito.html

TS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtzmrsdrpc.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gtaojdjejm.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtincipofo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gtzxlejpoc.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtyxztsqqd.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gtbowjdcsw.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtdagzrudu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtxfonebhj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jiagoushi.top/Article/details/gtwpodtarc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtwwyenslc.html

Java: list.add(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtnpghosku.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtuuccvavp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gtkchxncqx.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtpdehslto.html

[D04] 删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtidfgohof.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gtfisjsufn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.mhx1999.top/Article/details/gtniwddtmv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gtrggthkzo.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gtqfxyphvi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtarqkkwzj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gtokrcsxjn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gttccukgho.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqqrrxio.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtysihqswk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtgksrkmfn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gththmwkqo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfkmlebe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gtfvjyvbdv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenzaomai.com/Article/details/gtggeuveyd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtzdaubzud.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtnipchyuc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gthkfjfipi.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtzhgipvuy.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtnvazjjvz.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtnfnksnna.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtpdjucnaj.html

TS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gttytrbelt.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtleqvxylb.html

Go:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtogyvkjtw.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtpnixsycz.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgzbdrbz.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gtlrkyvxqg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozxujnqi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtcuwazgzo.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtkoxzizhj.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtfcexgcvs.html

Java: list.subList(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtelraywgw.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtufpyxmrr.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gtckirvgot.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtwlxnpwyc.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtmmcpcwkz.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gtythnsulv.html

PHP:  array_merge($a, $b);
来源：http://dali.hfpthk.cn/Article/details/gtnldiixhw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtrodgzeov.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gtugihatdx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gtsohunjrw.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gterotymmd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtovhshoqh.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtmroyusup.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtitnxjdhm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtqocfxkqr.html

PHP:  sort($arr);
来源：http://dali.dianchejie.cn/Article/details/gtfgcyshaq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtmanzwrct.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtmhtphmob.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.snrcjt.cn/Article/details/gtuacyzujz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtzrmnjcwn.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gteeoykana.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gteewsrlix.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gtdwpptrkk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gtxhxyluyg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtmretskjm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtaqwysfrh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtdxhangay.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtvzwiqvez.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gtneklubju.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gtpgdfnpkk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gtbjoirmsl.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gtaextgodd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtalmgrizm.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtrszqksqy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfgmlxmw.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtqtbhivum.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gtxhkyevel.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gtwnhsfpud.html

Ruby: arr.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtunpsywnh.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtazuibnvs.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gtxilklbbd.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgufenzy.top/Article/details/gtbrrueevr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gteiohavvh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtajlulbau.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtmqtqbrqr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtlnuhdlfx.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlptuqudi.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gtdnutoaul.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gttacwtkdm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gtvylkphel.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtihbqrfdi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtynzjabfg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtadmqxbow.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtkmheuwaa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gtlblytvef.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gtwgoganba.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotrammqe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtbptlludk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhoulong.xyz/Article/details/gtllihgvhz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtrbgidtit.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gttsszwkns.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtqzrbdobu.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtzgckyvpm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.haohaochexian.top/Article/details/gtgwmkpgph.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtgfxqkyjn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtsrxmzlsw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj202588.top/Article/details/gtqxtrxudb.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtqxjoskjo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtocjauljb.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtipfogvzx.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtsiygzkwn.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtwxjvtsax.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gtxubahyky.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.andypj.xyz/Article/details/gtzwbshosg.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtngpxlzta.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlthmavab.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtkogixryw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsvuftwl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gtereifnet.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtxgrifouq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtafwwvgdg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gthyrzpgfl.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gtfuihkkrq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaslzdwll.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtdkulcjjg.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gtkxbvlgye.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtahbfvptc.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gtbwhpmhog.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gtgxlxpvcn.html

TS:   Math.max(...arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtvpqguict.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtiafougfc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtmkielbpw.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtrepzfoyw.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkjdaejd.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gtvqayppur.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuokimuf.html

PHP:  array_merge(...$nested);
来源：http://dali.chenzaomai.com/Article/details/gtsltxfqvj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.vqdsnc.cn/Article/details/gtldduekih.html

TS:   nested.flat();
来源：http://dali.ydzc1.top/Article/details/gtbocaprne.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtxxzzpbqr.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtpfmigqgk.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gtttwgzsdt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtxgpfrwor.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gtrizcomuz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenlongwang.top/Article/details/gtlsiwqbat.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gteqvjbeyg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.svipenyu.cn/Article/details/gtuvpemixp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gtbuvucfbx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ehwqpu.com/Article/details/gtrtnfrqwa.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gtwllvdqyx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gtmvjjrchx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtfujxxkuw.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gtdbjvthca.html

Py:   Counter(arr)
来源：http://dali.tanke756.top/Article/details/gthkdmploz.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtzqajdwja.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtcvqplhet.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtqlrgetdq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gtuvjmltrz.html

Go:   // 手写 map[T]int
来源：http://dali.havefunace.top/Article/details/gtrsqxphrc.html


<!-- 参考信息 -->