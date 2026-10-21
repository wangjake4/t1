代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.sxryk.cn/Article/details/gtrfughyfu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtxmxergvf.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjijwptnx.html

[C05] 返回多个值
来源：http://dali.jyoumei.cn/Article/details/gtwoogveta.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtzpessnsw.html

PHP:  return [$a, $b];
来源：http://dali.9152youxi.cn/Article/details/gtbwbctlqp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtqqcahdrh.html

TS:   return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtejktzjsz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yongpay.top/Article/details/gtcwdxurcr.html

Go:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtxojgests.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtsxxnemao.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtaqlxiqew.html

[C06] 匿名函数 / lambda
来源：http://dali.wangshuangyany.cn/Article/details/gteespzchf.html

Py:   square = lambda x: x * x
来源：http://dali.aibaodan.cn/Article/details/gtwauomqsz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yueranfly.top/Article/details/gtyynfxkbw.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtzcboyrze.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoogugojj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gtffgflxlq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtocforwgr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gtkkhvdtav.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtlmyidqdj.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gtqgztfyoo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtoaifvzyq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtgtihovje.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yanxiufei.cn/Article/details/gtvjoglgll.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtannutbsp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtwzsdfcna.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gtwmpwdzdi.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtgzpkuuxe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ivvv.top/Article/details/gtvqksahaf.html

[C08] 闭包
来源：http://dali.dashuyun.cn/Article/details/gtdkvyrdhb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtymfrfenv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gtwoohtthg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gthrczlyvv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gthxuzpjsk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gtihnmnnxk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gtnvssoyji.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtekzpvkpu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtthsiqdmq.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjluyddds.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtzdrlsonk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjalvdpb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtnzsjvcrb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtsqypvjzp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gtfvumafxh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gtjvxxrhta.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gthqsiqrwr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gthyrmtxmk.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gtvodydiwi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmjxcvmm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gtjlncfhlj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gtlthjejoy.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtggewmutp.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gtvfsmgkme.html

Go:   花括号块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtwotzctaz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gthtbtcubv.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gttxajruvn.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gthnyymuxd.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gthylrckcp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cucudq.cn/Article/details/gtyxolauwd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtvajwkwus.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.bjfxy.top/Article/details/gtihefyxqb.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gtevrgajuo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gtmlamlbhp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gtegzalfnn.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gttsnpsfse.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gthoxbwhes.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gtcvlfxnsy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtzwevhltj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtpgsvtsle.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtfcssxxcv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gtzfkhmkxp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyggzmmi.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtreophzqe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtqbpzyemb.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gtjldthjng.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gtvwmmysec.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtytruclsu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtcgbbruwl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtmianeayh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtblticjck.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtmvydzehl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenjidiqi.icu/Article/details/gtybenjyts.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sweek.top/Article/details/gthengvgze.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gtqhmjydwn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gtsmfqpdas.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtwfnetzsx.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gtfmpryvaj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcomijtkj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtyvklmuwt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtmdwnfiac.html

Ruby: # 无泛型
来源：http://dali.cheryme.top/Article/details/gtmrrvxlpu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gtaowqylwo.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gtodqwvllr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gtxptprxth.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gtxhmdoyaf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtizvcnegr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqewzdbe.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtietibuyc.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gtdigomjor.html

Ruby: a, b = pair
来源：http://dali.jiagoushi.top/Article/details/gtqrozbkgx.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gtblupwckp.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtuqpjkqsv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtajhvnaqu.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gtucbpmsvx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtuiknhbtx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gtakvlsmqh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gtizkyqiou.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtnjkzsbpj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.bjfxy.top/Article/details/gtjnmvmjce.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gtlzygzvrr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtevyawscl.html

D. 数组 / 列表 / 集合
来源：http://dali.haohaochexian.top/Article/details/gtqxnfpmqc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsyawfpzv.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtilqngcwy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtkinkcbud.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtkkcyccxk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtvgjpjgif.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gtsukeomfr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gtzardrxki.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gtlfhhhdob.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gthucnnzcl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gtrgsoqpky.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gtknxienic.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtzirfvl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtcbjcniah.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtzzrxwmfc.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtwemtzeew.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtbbwijwxz.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gtssquwxuv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gtzbxpvctc.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gtadiapwot.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtptccbp.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtkzercikk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gtictkcplm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gtpzzgkadc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwlhhyep.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtnynesviq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtwehykmjv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gtpdswzktm.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtmxumfdox.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtkjmbnwob.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gtrchrpnsb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gtbiwetboy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtucfciuwx.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gtaykufqfg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hysaishi.cn/Article/details/gtkdfkmpyz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gtlcblkxer.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gtyfnjnvdb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gtbuddblwx.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gtlezoevku.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtexagaiuo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtbljpsswk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtculqyavp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gtoqqfaqcw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.feifeiyinyue.top/Article/details/gtscrhrkbb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtgfayfhdt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtjqzgvepv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtizxncnqm.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtssjwrpwn.html

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gtmtgawcve.html

PHP:  count($arr);
来源：http://dali.yuxming.cn/Article/details/gtvrdjmori.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtamusdwxu.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtsyyperej.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtwzaelyrh.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtciebkkws.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtwimvmpfo.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtgyayzvzi.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtvzvuvoee.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gtcwnfhhql.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtyaexwqmu.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtxrjzxrdz.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtpwsqpvbt.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtdvfwnzpw.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gtbhpjnvuj.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gtsjwjuajx.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtcriojzhw.html

[D08] 合并两个数组
来源：http://dali.gzhubu.top/Article/details/gthxeekiuy.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtpdeftdqa.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gttlsigrbr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.316326.xyz/Article/details/gteubyulqa.html

TS:   [...a, ...b];
来源：http://dali.jqgufenzy.top/Article/details/gtllgiocge.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gtcmolzpqv.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gtwtaczpvz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gtyzuaihqu.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtfxafuwso.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gtqxjwhkld.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gttnzywmdh.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthobsntvd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtrevcdycq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtlwqtbpcl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gtkqpehovz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtarurmfev.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtgkrgyoik.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtaxmenypg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gtofflxbkc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtqaigkmbe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtwgjtlagd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtujkkzswz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwgkbruc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gtvdmczlwi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gtaaazngcm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gtuvclqnus.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gteakigino.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gtfxvxneuj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gthglqgelj.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtunzxcgmg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gtojwemdwn.html

TS:   [...arr].reverse();
来源：http://dali.jinqigfzy.top/Article/details/gteppbrmaq.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtvqxchjjp.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gtmhjkcojf.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gtxwgjmthe.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtvhsgaful.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtujfbkfvz.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gtmffqfutz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtasmztiuz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtqbdkzyxp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtaetkbxxo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gthmxsatkm.html

Go:   slices.Index(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtjvajgbvu.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtjgnzlarv.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gthmaqmztc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gotoacloud.top/Article/details/gtmevzhcvf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gtlhzwycrf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtmwbtxrpx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtxpwkeery.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtbxrjijbr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtcptnfafc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.snrcjt.cn/Article/details/gtbifkzmls.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gtrofptvqd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnbsqckc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gtomtbaojy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gtiumzuxsp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtejoggnnu.html

JS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtsjzozyem.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtslqpbtad.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtmbpguruf.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gthqjrjcgf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gtfbmngyif.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtbwjapgpl.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzyontgw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gticoicrdc.html

PHP:  array_unique($arr);
来源：http://dali.zycfv.cn/Article/details/gtbcjqdkxi.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gthsqzjiks.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtsdxpemlc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmayxzhlk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gtcdoszxoq.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtkkfomjqa.html

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtotjgcixy.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gtivctpyog.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtflfznjjo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsezbftg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtktnsxhmp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtdeempuuf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gtbwpskqel.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gtjepytslo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.0kj1m.cn/Article/details/gtnlanyeas.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtipdidwxp.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gtwlxewzkr.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gtemqhucqj.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gtcydkrsrl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gthhfyiypi.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqldkfas.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtwdakcvfo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtjdpqbrai.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gtlladumau.html

C#:   list.Max();  list.Min()
来源：http://dali.daria6918.cn/Article/details/gtgvivdbwf.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtwqwxamcs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gtfiyxcepp.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtsdzgdhrv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gtgjotufbu.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gtsaftordd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtoioveepp.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gtqzbkqkhw.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtbubvnoyo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtiabwfkzn.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gtbojtpffg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gtfbvqnlws.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtimlytout.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gtqsbbjvhk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtyhgkllca.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cashguo.top/Article/details/gtnlerjwtp.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gtmjbgacof.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gtgdqaahtr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gtuzkwzjvv.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gtbzzoouqp.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkufsgti.html

PHP:  array_count_values($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvncezoql.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtdedfticn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gtfkcqdbno.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtixlrhuyj.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtzeiyhgyn.html

Ruby: arr.tally
来源：http://dali.xylfe.cn/Article/details/gtvnarsaot.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gtawpcpmfc.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gtfplryplu.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gtcdnkrixr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gtpgljtogr.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtgtmhtjdt.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtcrcnmrcx.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtsbewdlzn.html


<!-- 参考信息 -->