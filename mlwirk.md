代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gtsizjlasm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtkefltwjm.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtrjqdwjsh.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gtaewlmuws.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gtqmhfxtgl.html

PHP:  return [$a, $b];
来源：http://dali.ehwqpu.com/Article/details/gtvmwbhllr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtyqrkdvna.html

TS:   return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtzviauvdr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gtiitnzwoc.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gtsmyjtsud.html

Ruby: return a, b
来源：http://dali.fzhhl.top/Article/details/gttjxfrqvu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtuagvdetw.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gtnjstqvsz.html

Py:   square = lambda x: x * x
来源：http://dali.jqgfzy.top/Article/details/gtpawqovvy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtqlpxzbdg.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtvbkjjxda.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzzoroan.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gtrdsesneq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtbitdcvjs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtedsjjpwa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdgswspc.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtiwtheobw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gtczyiesyg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtchnzmhvv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtlywipjcm.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gtlkxbfjnx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtdyhoxhcb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gtklfzrrhr.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtbmhfvcaw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhiwuduotai.top/Article/details/gtzihgbjnc.html

[C08] 闭包
来源：http://dali.tianlin.xyz/Article/details/gtaduujyhg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gtbpitemhb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gteqvmvnke.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtsvmtjped.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvkkpzppr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gaohongyu789.top/Article/details/gtwcpdpeon.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtdyanoknq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gtlejwlpsb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtrqoywean.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtmbvbppkg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtizbgqvro.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtbxbmbyfu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtxvkyxvmq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtfdsgjror.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtqpqgtdas.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gtevulycuk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtmupacqoh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtrfemiiih.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtgupxapdk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gttrjpwbux.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gtogpjcqgq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gtfycakyqr.html

TS:   同 JS
来源：http://dali.yj20258888.top/Article/details/gtytaisabt.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gtdcgpxdsk.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gtnjzjmecn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gtrrammlpd.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtpcbwkvqg.html

[C11] 模块导入与导出
来源：http://dali.0kj1m.cn/Article/details/gtvelkkuaj.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gtwahthpnp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gtsbdesfcd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtauamzflt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtwwblzfti.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gtlneplljt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgfzy.top/Article/details/gtclqzxdlu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtqpzwapxl.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gtfawtsmwn.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gtvqybrwaa.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gthzbmwzel.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtvwjzrygj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtetbifsbs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtyelxcizz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gtxsmabqmb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqgfthsy.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gtwrowswoj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtbbmnpbgp.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gthdngfuok.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtdaovwomx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gthxvuzbuo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gtbjguwvev.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtyoexhxcm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajqnhhll.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtjdqpenuc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gtwagitxtf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pengpengdd.cyou/Article/details/gtzqudgcgv.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gtmyseteiu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gtlptdqzuh.html

PHP:  // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtkerudlsb.html

JS:   // 无泛型
来源：http://dali.yj20258.top/Article/details/gtjmhspbqo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbtmztukd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.9152youxi.cn/Article/details/gtztbmewjd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gtxuqbognw.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtsuhszocs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtvwmeduxk.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gtgjxsxsad.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gtiivbieum.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gtvgvgmtab.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtbbqygvfq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sweek.top/Article/details/gtrfxvzwvc.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtzvecinec.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtdvkggngq.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gtlmxtkvew.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gtdwxnjkkv.html

[C16] 函数 / 方法重载
来源：http://dali.sysykeji.top/Article/details/gtsfuzadmg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtjelmtvjl.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtsrfynjbu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtfpjdxbqs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gthpvqpnuw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gtdqjlmpia.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtqzhylpcw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gtoyjipaxl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbohsnxar.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtubztospk.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjszraia.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtotxufgfw.html

[D01] 创建数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gtyywiprva.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gtetgsnalo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnqzz.top/Article/details/gtyghwtjog.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtfcvfhs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxsklmym.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtcessjeyb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtijqoldwd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthomdpmmc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtffiizrxs.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtybveaabw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtspuctewt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtapzuatjq.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtokiwycot.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gttqvizcdn.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gtlxaisfwu.html

Go:   arr = append(arr, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtxsohgace.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gtohafsxdz.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gtzcwzyend.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gtjoavgdzm.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gtvwcznsgg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtbxazotpb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gzhubu.top/Article/details/gtiwbybryy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aizwys.cn/Article/details/gtcpijkyei.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtheygdoin.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gtinzwkbyj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tanke756.top/Article/details/gttamkjkno.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gtdakjzycz.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gtydlunwxw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtwdjwilfn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shzxlz.cn/Article/details/gtioldflac.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gtfwypflfd.html

TS:   arr.splice(0, 1);
来源：http://dali.havefunace.top/Article/details/gtwedxjfks.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtqtgkaewu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yanxiufei.cn/Article/details/gtysnzbrku.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shuidangran.top/Article/details/gtuccnmrpb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gtfmllpgeo.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtosvsroby.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtyutcdenm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtidmfqrxg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtfyrduqxk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gtidnkkdwb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnoymugd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtgpkcjgau.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtkdeozljn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtfbapglpr.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtwohaxdcv.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtiqeeizqq.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtqeavsels.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtwesxfzua.html

TS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtztvferoc.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gtxpnqpsjc.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtsagpgnlf.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gtxjbolxgp.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gtfseettpx.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gthgroylnl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gtfapewnvn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtjujxevyg.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtecamwkoc.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtybunmspx.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtbtszseub.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gtwppaborp.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gtaspwitxc.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtmumusxxv.html

[D08] 合并两个数组
来源：http://dali.nanxinkj.top/Article/details/gteedncmpq.html

Py:   a + b;  a.extend(b)
来源：http://dali.jyoumei.cn/Article/details/gtwyzufcyo.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtfzzwersw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofgkeshu.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtgmeskhzq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtjeoayikk.html

Go:   append(a, b...)
来源：http://dali.0kj1m.cn/Article/details/gtzghnrfbw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtnoewpbqe.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gttrgqmnxi.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gtixswdbrg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtfjepqkng.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtqknjftbe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gtdnvafldk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gtszpvehqw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gtgujqptnb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtbgyfdgxy.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtxtqlvxuy.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtkhvcbqsj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtibtffsed.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtndzdvkmj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtuozreaos.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtdvcsgbrk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtnkayndir.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gtojowxbbm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtxihorxxd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwemfzlp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gtjyqjfrcu.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtafdlondc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtlpsytjjv.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gtrzkufceb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gtnkjgcrjy.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gtmochfjlc.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gtvvuxzitq.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtmirsbhej.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtvhzepmxn.html

C#:   list.Reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtcwuxcvaa.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gtmpmkpcfm.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtugotkvcd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gtvxtqamdd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtrcsvscmg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtjyepnrxq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gtumlrfrut.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gttmqkuyla.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gtqlpcblfr.html

C#:   list.IndexOf(x);
来源：http://dali.tanke756.top/Article/details/gtetwyoetk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtraivybbw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gttezejtvm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtdzrmakkt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtigldzzyb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtftoiutoy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqokasxgf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtyfjodzxa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhuxtait.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cheryme.top/Article/details/gtljrnozsm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtkrjtysam.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtmjwfyidz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gtvrmgtyqo.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtizojyqjq.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlryprujp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gttlvduuay.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtllgpjflx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtvymuogfg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gtkoewtlqz.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gtxeepqayc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtjwzsfmlp.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtkcxnecjf.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtkdolcuvs.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtuzbhwzgy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gtmlswjcna.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtjllqbfnx.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gtvlxxqlpc.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gtuwdrdflr.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gtgadsicap.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtcxvzdsst.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtgjzjavpz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtfuidsxft.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtxkiaqjhp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gtmnnieend.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtrjitszif.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gthrnxffak.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtrbjvqojk.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gtxgfsyegu.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gttodptjhc.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtencgbolp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.vqdsnc.cn/Article/details/gtawizsosi.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gtyzsbapbb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtzezrrenp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtpvhjgxua.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gtwdxnagnp.html

C#:   list.Max();  list.Min()
来源：http://dali.dashuyun.cn/Article/details/gtshyoxftb.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtlzrmwenk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtqoauuqrd.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtckundvtu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daxiang520.top/Article/details/gtkxzngdfd.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gtrnmwpnzi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gtahtwgjes.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtartbczyj.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gtjhrbjzvu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtlxkpebur.html

[D19] 按字段分组
来源：http://dali.yj202588.top/Article/details/gtpcftakkc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yangfankeji.com/Article/details/gtfyufbqmc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtbgnuvqff.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gtussuucsb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtqppymjcg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gtvcvrpgpe.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtfccnicfc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtdrdsadtv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gtlhdawnva.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gtkdujpcxi.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtwdjnwoum.html

PHP:  array_count_values($arr);
来源：http://dali.shuidangran.top/Article/details/gtjovcfmib.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtmcyxqzdc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtdtftkkpr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gtawwjuzdw.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtrcongnil.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gthmrqtewi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shangyingyoupin.top/Article/details/gtodhwjlql.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsisbnlrz.html

Py:   x in arr
来源：http://dali.quarkkingdee.top/Article/details/gtawycggbs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtivefyhbg.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtlpakoosn.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gthegeoznj.html

Java: list.contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtgmdldjkn.html


<!-- 参考信息 -->