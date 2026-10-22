代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtukekxljj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtqzluehbl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gtfbwlyybl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zdqjudy.top/Article/details/gtbwrtxvxr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtgkdyrrhl.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtzuvufkxl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gtsoctcogy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gotoacloud.top/Article/details/gtvqfxwvxa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktzzzuxm.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gtxjhvocei.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gttuilzyka.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dashuyun.cn/Article/details/gttinupujp.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtglzdxpse.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtexsxathv.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtgilkdcab.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gtvyevocmx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gtgygugyul.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtekfyfoiu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtjpcycjxa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gtldofffsg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daria6918.cn/Article/details/gtvceklszw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gtfqrqbdrc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtcgnnokav.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gtrsrrrtdh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gthhumzcho.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtrrwimijw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtoecwgzku.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtzrwigdzz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtuwjezalj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gtcygacmwc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtcblwmzqo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.redwolf501.top/Article/details/gtqqaogzqv.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gtbhhywvot.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yangfankeji.com/Article/details/gtfbsyuskd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj202588.top/Article/details/gtobeyunju.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gtfceuszqq.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftqvzrnc.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gtnksjpjmv.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gtmwdgjdlm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gteneszlxs.html

C#:   块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtvetnfthm.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gtiwaahpor.html

Py:   from module import func
来源：http://dali.dianchejie.cn/Article/details/gtlrthelcx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gtwlxtijmt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtkvcomhah.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gtrqwwuohf.html

Java: import java.util.List;
来源：http://dali.yj20258888.top/Article/details/gtudyvfnzt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gtxdhgxven.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shangyingyoupin.top/Article/details/gtziakcngc.html

C#:   using System.Text;
来源：http://dali.gotoacloud.top/Article/details/gtppueqprp.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gtzmpxtcqi.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gtfxlwwkhi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtjkacwkkv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtnnwjcsgv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhkhjcpx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtpdpoemin.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cdnleiting.top/Article/details/gtlsfflmai.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtuleepvft.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gtzvtxvudj.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtumpsezvl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtbloiiurz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtxhknaogt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gtrewuwaxu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtispqzecd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtaeayielo.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtzurxnudo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtoyukgpsb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gtomysnnjp.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtuoesjajg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gtevohzkks.html

PHP:  // 无泛型
来源：http://dali.cashguo.top/Article/details/gtziiypvgv.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtaxdmscpv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtngpdzfuy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daxiang520.top/Article/details/gtlaaqrycr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gtxolbffon.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gttanvtdau.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gtkgqocuhe.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gtjqnkimdp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtrrmqvtya.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gtohkkrtxi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtswsijpoa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gtcumihnqr.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbvyinlj.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeerypys.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtosuesbge.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gtcetqystn.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gtjnpammfh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gtdpghqnie.html

PHP:  // 无重载
来源：http://dali.sysykeji.top/Article/details/gtpuzenzco.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtycphfwus.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gtdychsgrf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtynydldlz.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gtomrjixni.html

Ruby: # 无重载：靠动态参数
来源：http://dali.vqdsnc.cn/Article/details/gtybgeojvy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gtarccfgsw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttimitcvl.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gtgkoeeaul.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthzxouedq.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gticjavvmt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gtywliiwvi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtpxgwemup.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gtcspvycsi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtxtppcavn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gteqfcgvtc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gtxgcxrcaf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtxenxoylt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gthqvvsmqp.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gtifomlytk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gthmacmkzo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtnqbgenue.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtbhjmngay.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtfxepjbev.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gtimuusrdy.html

Go:   arr = append(arr, 4)
来源：http://dali.meibo888.top/Article/details/gtxtelczaj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtrqxfrgin.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtbsjrcnlq.html

[D03] 在指定位置插入元素
来源：http://dali.cdnleiting.top/Article/details/gtuovbqnmn.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gtstzxkscs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guowangkeji.top/Article/details/gtohdqjjhf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gtudrqunes.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ybcxt.top/Article/details/gtzygfgzat.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteywxegkk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xziqi.cn/Article/details/gtzycatblt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gtesbfbeqx.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtzizlhssb.html

[D04] 删除元素
来源：http://dali.gaohongyu789.top/Article/details/gthfngoriy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gttsasoilj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobhikjjb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gtwgbvbdwe.html

TS:   arr.splice(0, 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtbbdztuph.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gtyemoaqei.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gtfnnkxkza.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gtxulwfgfd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.c1oappe.top/Article/details/gtjlffrmeu.html

[D05] 访问与修改元素
来源：http://dali.wangshuangyany.cn/Article/details/gthwcrswpy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtxkuyhtti.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gteabyppmz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtnjfzxutp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gtvxyhcuqd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gtrvwplfwk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtaxzsweze.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtppqgxjds.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gttevausbp.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtftaokijh.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtbobvvluy.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtqacegabh.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtqxemuskw.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtkncphjew.html

Java: list.size();
来源：http://dali.sufxvd.cn/Article/details/gtjedbxodb.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtvdkrzulp.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gtnpwuqebn.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtmamfhbxh.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gtglarjbow.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gtvxvrqlxl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gttcoexvor.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtbejnrdnr.html

TS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtwhyiioip.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtlgmvdvcy.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gthummibqm.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtjlwtoboy.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtxhnztjuf.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gtoyycurtb.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gtwzrxopcd.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gtfgoyufyf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gtgleqiwfe.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gtwrlkvcag.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gtohorcqfx.html

Go:   append(a, b...)
来源：http://dali.cucudq.cn/Article/details/gtrfzdwkjo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdeqypvtt.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtjswcjoke.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gtibfjqwvq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtpllfpiaa.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gtkstbmwvj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gtdjmtnjlu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gtkrfdqzju.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gttmagocrm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtfghdqufv.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtcgngbkke.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtguacsebc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtzxykkpbi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtetuikwbe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtgjzpgtki.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtqsytcovi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtuqepwnru.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jyoumei.cn/Article/details/gtnqbmwxwz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gtgzdpozwm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gtejgfaedt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gtxxlacwij.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gtxxgroopr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gtqtucqpef.html

PHP:  array_reverse($arr);
来源：http://dali.yvedp.cn/Article/details/gtagocfhfy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gtukqtjymr.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtowuyafha.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqdknptw.html

Go:   slices.Reverse(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtuhwmfilo.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gtvpldqzut.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtelvwqizy.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gtumrwpoed.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtemsqjgch.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtupxzvuhc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtlhhbcsbs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjbebhws.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtptxxecow.html

Go:   slices.Index(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtopncqkyn.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtizscypzh.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtpwhyrkaa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtfahmppld.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gtsuqumwyj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gturlxurns.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhwpfpjl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtdhytoihq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtproufznt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtjlneyfcu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.birdmap.top/Article/details/gtsuevgnur.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtydpokyir.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gtyntsuaau.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gthldnnfsz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorczampm.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtgzznbybo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtyuihoevc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fengsongda.top/Article/details/gthecwmcdh.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwmyaabh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtqlrfwxhp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtwthmumix.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gtnqczihwv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtgfvfrwqe.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxfggjae.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtymncjgqs.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtgqvmmgfu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gtctbszddl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gtbaxntrhr.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtasnvvezm.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtpvnpfcwn.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gtukbzttuu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtobfbpbdb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gtmxlkschn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtlrrdpmik.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gttfvauxzj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gtmeeqkfwb.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gttjjeenoa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtmgkqrwcd.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtutptupbw.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtsahqxdka.html

Py:   max(arr);  min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtwzavasdm.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtjscghqfg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.kuanghao11.cn/Article/details/gthzeqpygv.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtxmedbmxs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gtpjxpkqoe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtqvhlszlt.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtlyzcpxen.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gtwrlykxdi.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gticbwjast.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtyfxynorn.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gttupnwocx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gtjfxuwdpq.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtkogdwhde.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtekefbrgc.html

Go:   // 手写双层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjxzxyuc.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtmrjvrmhl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtlkcqoiju.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gtpaplursz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gtfsldtevd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtfnxgpuph.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtuslgthpl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtzipxnwms.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gteysufylx.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gtyrlwspth.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gzhubu.top/Article/details/gtxmfplglx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nwbrower.top/Article/details/gtmtjkvdvk.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gtccnrqioz.html

Py:   Counter(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtsgymygbc.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gtpeibodqe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtxzaviter.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtjqtxslus.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gtrylqbqsy.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtratwpwsu.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtlrtrevyy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gtwinnqkoo.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtzhukiurj.html

Py:   x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtwmvbplky.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjvmgsqe.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gteakmnyqu.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtwzfnaupz.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtjzqcffyi.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtthqpjves.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtuafygosk.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtjliwnjmj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gthtnkeasy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gtqrsnbksn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gtyttuzkgj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtzdzibrru.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gtyhsyliwa.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtnyynqlag.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtnidoyjju.html

Ruby: arr.dup;  arr.clone
来源：http://dali.mhx1999.top/Article/details/gtlelmkutg.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gtytclfaey.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gthisjzpbr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtwtbqepjp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gtkimbbfeu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gthhlbxmuy.html


<!-- 参考信息 -->