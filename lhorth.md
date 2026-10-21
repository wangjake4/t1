代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gtqishbyec.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtfhjvysoc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdqoxbpf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gthbodzqhz.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gtrqxgfzko.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtgkmtruna.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtevtufyof.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gtdfzoaqhq.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtmbhcrnps.html

PHP:  return [$a, $b];
来源：http://dali.snrcjt.cn/Article/details/gtmzzsgqli.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gttwekyyns.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtrmwjuhzi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yonumen.top/Article/details/gtiyidkfbs.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gtsfrbjgel.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtyqcblfjb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtjkyuyqun.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtdxftbhgj.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqyohicq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gthebxjewm.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtsmtsolkj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yongpay.top/Article/details/gtlqjjufuy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hysaishi.cn/Article/details/gtqwklxnrf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtwfpytnac.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tian-w.cn/Article/details/gtkgcoepsl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtovcaxntg.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gtdjxscpjd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gthzvenvjf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gttqsuujxw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gtselirxec.html

TS:   arr.map(String)
来源：http://dali.hammf.cn/Article/details/gtwuedphur.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtyjyaxblp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gtxzutwbdv.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gtxuybszdn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gtoougnnmt.html

[C08] 闭包
来源：http://dali.shzxlz.cn/Article/details/gtkwwghjbv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gtcikxuylb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfesgotmn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtldxvsxof.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtxyfvfigo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gtumhhqnen.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gthuyvdkxu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gtzgriekob.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtiryudgcv.html

[C09] 递归
来源：http://dali.yj202588.top/Article/details/gtthpxckpz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gtqrsmitry.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.316326.xyz/Article/details/gttfzgusan.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gtefwftsdi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtvtutpywj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtutgphdht.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gthidgcmav.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahuyazbg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigfzy.top/Article/details/gtdieqociq.html

[C10] 变量作用域
来源：http://dali.tian-w.cn/Article/details/gteosljigu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gtwghlakby.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gtepkfpppt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gtsguatjhy.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtidptypqr.html

Java: 方法内为块级作用域
来源：http://dali.nwbrower.top/Article/details/gtagpeqmbc.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtonpyhhok.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gtkxvzpsno.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gtphjvmwuw.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gtalkjbgae.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gthosmwxvx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.meibo888.top/Article/details/gthdpqzjhq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtalggnfdq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gtrgucximv.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gtzupgzmiv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gttbkjhhnr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yanxiufei.cn/Article/details/gtoelvkxly.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxzjynxy.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gtzbobslhh.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gtpvunuvuu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gtzemyxwlw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtqupcyrpn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtdusyyowe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gtnyxbxahf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtevnhdumb.html

Ruby: -> { puts "run" }.call
来源：http://dali.hysaishi.cn/Article/details/gtgymlixmj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtrjfpnvld.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtsquqxsde.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtjfococfl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtdxdjcisc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtjqacvpmi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gthhuiweuw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtubzwfbis.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gtgkurmbxn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtfppjcazl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gtuutyalbn.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gtnvylbuem.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gtpshspivq.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtotpznjjc.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtktazkgpo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gtppnhbabg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypyhbjyo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gtrrcucdpp.html

Ruby: # 无泛型
来源：http://dali.sysykeji.top/Article/details/gttaygcgas.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gtsttavciu.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gtgzjstjwd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gtmuluqnxg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gtylohggqh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtizqjmlvz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cashguo.top/Article/details/gtugihmnxo.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtxsynsxrq.html

Go:   // 无解构
来源：http://dali.iojbl.cn/Article/details/gtfpfzisiz.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gtxcwkmtrb.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gtjjiytapm.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gtwsndfzvu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gtucjxdsjn.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtkqvnixus.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntlnobct.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gtzjosmkde.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwfevvjq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gtrjvgozbv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtnxlzbwgb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yueranfly.top/Article/details/gtpeedvqxm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqbsmnbze.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gtnooafqfj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqmnwyhj.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtggtntcqz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gtafbgxojz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtcicirrwl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtsyxspuiu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gtiefshloh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gtieytxlsn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtofxvrgei.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtwfvqkxmv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gtwluxzjvo.html

[D02] 追加元素到末尾
来源：http://dali.jqgfzy.top/Article/details/gtsazkpfgs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtqbxqjqln.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtlhmtmonf.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtgcqeifqf.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtulyzftph.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gtlxkmzqpa.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258.top/Article/details/gtzmjnitrx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtmdpoonch.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtoaoxfnvm.html

[D03] 在指定位置插入元素
来源：http://dali.wangdashe.top/Article/details/gtozgjcrva.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtgiqpsurn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gtpmlzvjhu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gtlypwhkct.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gtcsgsfkhq.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtgppgohyt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtagxzklcp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gtffnsvnuu.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjgmlagc.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gtelwtemkf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gtvpwsqcpr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtorphblut.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsedbamda.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtzaflpmqm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gtewcxvmgb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtzkovgajh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ehwqpu.com/Article/details/gtalcvqbif.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.c1oappe.top/Article/details/gtdpzjoxhs.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gtxmhlevie.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtfdtgyvqc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtqemwbrwj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gthuhojrxv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gtgxgqprun.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtuajiibqt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtyxwebduk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtkiioxitv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtmqekttjj.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gtsdhltscx.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtkhaawkku.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtnirsatnc.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtrokjdmvp.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtyncacfcr.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gtydnelrhk.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtfxnbybjj.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gtabtkbptw.html

C#:   list.Count;
来源：http://dali.yonumen.top/Article/details/gtktpvfkpd.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gtovebzkcq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gttjxibevd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtiidfkcaw.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtmjnbqsum.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtsdlnxzjt.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtxvdvppfc.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtllapzoxv.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gtbezwkbhn.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtkvftpath.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gtdbrqhwug.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gtedpsqzow.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gthlfehhzi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gtmxcjmyzb.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gtrcwhyemr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtfyiptqil.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gtjnyhfvtq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtfrhpswld.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtrkbdohtm.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gthoalotif.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtnstgxofb.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gtzrpnpyzh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sysykeji.top/Article/details/gtiamhithr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gtvacausyx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gtfobjpwvc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtedsskdyl.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtfecobohd.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtnpweqlir.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtgnpfaswh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtxufcixxn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtndyghocq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpovizqwr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtsobfewvl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tianlin.xyz/Article/details/gtpbtovggb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gtfrdllwtl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtnigsqsmh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenzaomai.com/Article/details/gthdcpxbvc.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gttmzjoawn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gtcwsrkewg.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gtmhiaiyna.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.snrcjt.cn/Article/details/gttapjinlf.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gtkuafhkew.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gtdwzqlaeo.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gtxiiewssw.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrohhqit.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gtmakspvpd.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpvqsdyp.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gtfoiepqty.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gtgkavzefb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtkgawvexr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtlgsnazdr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuccxtvsx.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtjlgxllal.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gtudzwrxag.html

C#:   list.IndexOf(x);
来源：http://dali.zhixingplan.top/Article/details/gtevlkcqts.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pengpengdd.cyou/Article/details/gtaeofdpan.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gtjjicctxb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gttachivzo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtdvmmureb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtsvuzoyqt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gtzywrmonc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gtbwgpvsnp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gtfvmpcsox.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gttihijyke.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hywenlv.cn/Article/details/gtabsqmzob.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggwmemif.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtbufqvirt.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtxrctzzty.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtnaljnprw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtpjijudpv.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtqwkkitqm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtmspsoajo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtualfpxqh.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtyotyjmdl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtcoddlwyd.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gtflrxcksh.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtzsymkrpz.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtlgorlxmq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gttbcadvng.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ydzc1.top/Article/details/gthrirxpjz.html

Ruby: arr.uniq
来源：http://dali.chenlongwang.top/Article/details/gtswsvulwo.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtxdppgama.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtiumjsgdd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtsyzgpoyf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gtoloyfueh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtobksmxsu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtneihqorn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gtuywwqqjl.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gtwmqrcrnj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gtppxapplg.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gtvbdrhwlt.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gtoncibybt.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gtietraxpl.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gtiwytmyos.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtxyvnfuoz.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gtnaroqyou.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtzqzclqoy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtfpulodrg.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtyccactlt.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gtbckatoxp.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gtuupbnkvf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtzmogfnvf.html

PHP:  array_merge(...$nested);
来源：http://dali.havefunace.top/Article/details/gtwmxefrck.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gtprnfpvgk.html

TS:   nested.flat();
来源：http://dali.yonumen.top/Article/details/gtpiwvonkt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gtjrvokgvr.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gtbibkknwg.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtgpgdeqfy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gtfmvfiuyy.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtdfqxluvs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtjsuclgsi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gtbhmczynw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gtghgkgyed.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtzrvkkdqm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenjidiqi.icu/Article/details/gtryrolzwg.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtsqkckwqn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gtunariyro.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtzxhxggpn.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtxhrkxmxb.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtphignqoa.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtyxlcxeif.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gtlxmzwxer.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtueubacuw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gtjevlrhky.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtgjxvknfz.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gtnmporqxj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gtzonslzpq.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gtzlgqajjc.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gtquhsfyav.html


<!-- 参考信息 -->