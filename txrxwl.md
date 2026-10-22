代发 wailian999

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2ovgonsme.html

PHP:  return [$a, $b];
来源：http://dali.cashguo.top/Article/details/gt2mkmesrvf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yonumen.top/Article/details/gt2wzmiocpy.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gt2nsbtiopl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.haohaochexian.top/Article/details/gt2rsknblpu.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2nwqxedei.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gt2bfapdjvq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.0kj1m.cn/Article/details/gt2teyqrpcc.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gt2bbpthhvi.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gt2juhccrqe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gt2abeyjemb.html

JS:   const square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2moelzjxw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2hphulylu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daxiang520.top/Article/details/gt2yiurworg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owbslpfx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gt2vgdrfpem.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2csxikyge.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gt2enldxjtk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gt2lzxsgzbf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2xnclbrmj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gt2vpbrdvty.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2fjrfdaja.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tanke756.top/Article/details/gt2qgeaiwse.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.mhx1999.top/Article/details/gt2gnrfjhoz.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhtuwwrr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.bjfxy.top/Article/details/gt2cekiuwgi.html

[C08] 闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffsbqoni.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gt2wwevsvhz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gt2lwlxxdpr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gt2wqtsneij.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gt2nlhjgupk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzumchyf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aizwys.cn/Article/details/gt2wbicfzjt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gt2kvdueire.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2wfjfaroq.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gt2iqetoyth.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gt2bfntcsgo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gt2tywzfhux.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gt2huvmmdbe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnzgwzef.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gt2lcpfiqpi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gt2vinhdoaa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfwyttcy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gt2vaihieih.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gt2yavnrtzq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gt2ktunqona.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gt2qgwkozvp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2cffmlcqt.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2ivlwdmdi.html

Java: 方法内为块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2pggtebfu.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gt2pdvjhcix.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gt2voispgcz.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxqmztby.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gt2gsmmgeiu.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gt2xxhfyzpk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gt2sgsezmlo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gt2pkozwxtc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gt2iuhvslig.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gt2amzstarw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenlongwang.top/Article/details/gt2lciinepy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gt2vhpidhiu.html

C#:   using System.Text;
来源：http://dali.ydzc1.top/Article/details/gt2cpalkxuo.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxinkj.top/Article/details/gt2dcgcaujj.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqfszgqg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gt2mxpyukzd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gt2zksgaldg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gt2dqsmyzwb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tanke756.top/Article/details/gt2imbwrrdh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gt2elpvwenj.html

Ruby: -> { puts "run" }.call
来源：http://dali.0kj1m.cn/Article/details/gt2vjnvohla.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2ljoxcwsu.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gt2lopnjzta.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gt2tduckzyz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2mnjnzelc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gt2ouvozlxq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2ygniisvs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2karekeon.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gt2xgycuvco.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gt2zqdkwkyq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gt2ancsuhkj.html

[C14] 泛型函数
来源：http://dali.zhengqikj.top/Article/details/gt2eleosyaw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gt2lbrfaloc.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2nhdhrkpf.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2dsfsnakv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2uroaacrw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gt2wrlvrail.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gt2uuesxddl.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gt2qylmdcrt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gt2zfqlcihe.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gt2lpbsbhoh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gt2ietvnwve.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gt2ttfiprbi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gt2myovftxr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gt2hebhbyup.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2zkayfomf.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gt2mbjttzhi.html

Ruby: a, b = pair
来源：http://dali.tian-w.cn/Article/details/gt2rttvavov.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvwbderf.html

[C16] 函数 / 方法重载
来源：http://dali.nanxuanxn.top/Article/details/gt2pjxxdfla.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gt2oxwgcihv.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gt2yjaytbdp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gt2bqktutds.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gt2kcubzcmb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2lqabxehd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gt2bmoknucv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2altherlq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gt2iiyrzagb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2qgaehgao.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gt2bkvnhrmo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2dmvdxmiy.html

[D01] 创建数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gt2kkrxyyse.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gt2qoyxtarc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gt2iizysonl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gt2oblqkjzz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gt2vjygslbp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gt2rmjfwxnh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gt2kjttwapv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gt2ocjynzlm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gt2ephuxcdq.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gt2fjnnbdqz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gt2wjuoatud.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksdaaehy.html

JS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gt2ssghakxj.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ytogocok.html

Java: list.add(4);
来源：http://dali.guannengcc.top/Article/details/gt2mnmyjteh.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oinodwnb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gt2kgqnkrij.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gt2ihonorwu.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gt2pgjodftf.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2ifvaqjqc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gt2nbxysqjs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gt2nyalhkbz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2jeokhzqy.html

Java: list.add(0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2icosiiwt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hntnkuiw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gt2rlhtrfig.html

C#:   list.Insert(0, 0);
来源：http://dali.wangdashe.top/Article/details/gt2sbvgoats.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xunyebfy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gt2hysakgev.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2ositrbwh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gt2emqzkvqk.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gt2mdabxzlj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gt2mysimnec.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gt2rzlonwlm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2dvilsnyv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gt2bbuktupt.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmyfmadq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gt2uiozmpku.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2prciyxnt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2jdmvieap.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yvedp.cn/Article/details/gt2cikwwxbh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gt2hcxxdtxb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hokfcgok.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2xfputyzz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2mfvrroyj.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gt2kzxgqays.html

Py:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2pbtqrphf.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2odgnlyyf.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gt2aabrefce.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gt2flxpqanr.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gt2rmlfuvlf.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2lzwvmbla.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gt2oyehsgwa.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gt2xmaqudum.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gt2gfnrfucg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gt2zfxdvyfq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqimnedw.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2zsgytzvl.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2etjstfwf.html

Java: list.subList(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2ullusrvw.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gt2xhwletcs.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2jacwugku.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2pmuptxgt.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gt2xsluawwq.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lygeyqln.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gt2phaidqgc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gt2hvxqcixi.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gt2monwqnev.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gt2lrmqxvco.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gt2pkdbvzhn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gt2rdcefryy.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2qkmnxwwo.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gt2buwfczim.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gt2ujgzlfzr.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gt2lhsiznds.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gt2ygwadman.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.9152youxi.cn/Article/details/gt2pqubnbrl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gt2xjdhjgld.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2rgljpjmk.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2wjifzuef.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gt2yiywxjpm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangdashe.top/Article/details/gt2oucpxwlh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangdashe.top/Article/details/gt2bfbpjasl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gt2eqdhwfkr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gt2eymrdkoy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2gfyqnjkw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gt2gutopckm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gt2zozlvunx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gt2jeitgkbi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gt2brxgzqso.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gt2kzlfdmge.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gt2hhtrccbi.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2lnzntmfa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gt2hlepblbb.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gt2vugogbig.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gt2uiyfnmid.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2ycjjgmtx.html

Ruby: arr.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2gougrvmi.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yppbvqth.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gt2ftjvnors.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2fnbdmmrc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2csyxrekr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gt2qigqfijd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2vavzzimb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2weaoyabe.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2utyhzlbu.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2ztgwnadq.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gt2nfxtssnr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gt2aisoobil.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gt2kzeojswc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gt2saqjhqrt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gt2lcsvggge.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gt2sbofinsb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gt2eepjtcgd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihypgrtk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gt2marfoilz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gt2ynezpyal.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhixingplan.top/Article/details/gt2rqwvlqzk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2iyqvkqsp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gt2nytcoayz.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2iicgebjp.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2kdoqsvfu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2ixxyezpo.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2ahcgshlv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2gbzqxftj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gt2cvxbmwza.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gt2ffsgwdwc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2jkbriukv.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gt2thnlkhsi.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gt2dhrejref.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2tchtfipr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gt2ggpnxcnw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aizwys.cn/Article/details/gt2drlmaaui.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gt2wuifopfz.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2luyfgzhw.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gt2ceymfoyo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gt2nszgijhw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gt2hcujfquf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2uqzqdmyo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2teszfkzs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gt2irodfgyl.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gt2pmfwlgzm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gt2naixgyvi.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmldpink.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gt2vywlyvmu.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnpvnulw.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gt2igdqtifn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gt2shugaowg.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irryeioz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2wvcxdorn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2hztsibmc.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gt2ilnejabc.html

C#:   list.Max();  list.Min()
来源：http://dali.yangfankeji.com/Article/details/gt2snaybbwn.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gt2kvcvuwli.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gt2xudingzc.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gt2mntsqpgj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gt2itdtnaiv.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gt2xxhalbpl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2ttlsxsjh.html

Go:   // 手写双层循环
来源：http://dali.316326.xyz/Article/details/gt2svcwqiid.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gt2qosstwkx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2evycgtfo.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzqtnuso.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gt2atesnkbt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yvedp.cn/Article/details/gt2zgnmmwjq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.haohaochexian.top/Article/details/gt2psbxugxe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gt2rkjlnbgp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gt2riwpxtfs.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gt2cyrvkwwd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gt2uqwocfiz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgujkftd.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2jnhapcpz.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gt2yeqzjidn.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2mpajyuof.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gt2esjzbgqh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gt2abncrceu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gt2kbepfuxa.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gt2qstsqeof.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gt2sfownldf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gt2bcepkryb.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gt2svkeadot.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gt2rtsokqys.html

PHP:  in_array($x, $arr, true);
来源：http://dali.316326.xyz/Article/details/gt2bqpsiqdq.html

JS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2jfdrtgds.html

TS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gt2djnxsyrf.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmisaynt.html

Go:   slices.Contains(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2omwgiejx.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gt2jpljtsck.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2hdaxbfly.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gt2lwdfnsgf.html


<!-- 参考信息 -->