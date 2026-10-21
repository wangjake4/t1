代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.zhixingplan.top/Article/details/gtimnaeuto.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gthybbuaig.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtulteuvbn.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gtxzoflteg.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gtxhqhqwzl.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gtuccpltoh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtcxaoexug.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtmbztrsie.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gtwkzmqaik.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gthrvodwvy.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gtogngypqz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtqxbewlhk.html

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gtdjqdnspl.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gtvdjajxbg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xziqi.cn/Article/details/gttbreagnf.html

JS:   const square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtxsnigiee.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtbmilfoet.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrzutfbt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gtzilsmjzb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gthopbbmai.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtvnmbhtid.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gtnpjcaguq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gtnlohefmv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guannengcc.top/Article/details/gtjydzllry.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gtblbgigvy.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtmlcacpwb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuxming.cn/Article/details/gtsymalvlx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gtrkybcipy.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhongyouzk.top/Article/details/gtdzhltand.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gtepnhqfzl.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gtibfselbr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fengsongda.top/Article/details/gtczgugezc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gtrhcdhvsw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtuumzkhze.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtgmhnjdtu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gtdinzenli.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuanzhike.top/Article/details/gtgheunduz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.quarkkingdee.top/Article/details/gthavvetwj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtpojvjnwi.html

[C09] 递归
来源：http://dali.zhoulong.xyz/Article/details/gttlugbdqc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtozeeghru.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtuqrruxgv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gttvbimwsg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtruanucwj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtguknhqrj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gtitzmmtwe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtygegwaql.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gtvgesjphb.html

[C10] 变量作用域
来源：http://dali.cashguo.top/Article/details/gtqynrrxid.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gtznfwmoqk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtufeqxpck.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gtzvodeqez.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gtlxzbtacd.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtmijgyhvx.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gtmqbzncmf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gtsqjriife.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtywxqzjfv.html

[C11] 模块导入与导出
来源：http://dali.gotoacloud.top/Article/details/gtrvsnsskr.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtobpxtucz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gtvrfjodxl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtfatueaqd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gtueubucdu.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gtarcrchjq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gthfbiwdie.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtgtmvdmnv.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gtcjukpegd.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gtmwcgelnz.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gteadgexxy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gtaunhjedt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtzxvqxuxb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtrkmnyhoa.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuxming.cn/Article/details/gtourpnhus.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gtcqiawlfr.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gtrwbyuvov.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gtjwppeqod.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtcvocdhpj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gtzndykevt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtqblnfhqk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.0kj1m.cn/Article/details/gtatuewmwc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtcosmoqum.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtamftdpcv.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gtwpvvnlfh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gthlxzlxsd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gtnorvntom.html

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gtmckxdwww.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hywenlv.cn/Article/details/gtboymcxlk.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtkmzsbhqx.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtmeroedig.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzomspndf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcgnfzno.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxklgjaac.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gtlrhgofcy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhongyouzk.top/Article/details/gtdtdmylah.html

[C15] 解构 / 展开参数
来源：http://dali.nwbrower.top/Article/details/gtfjjjhblv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtetvzzwmk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtcbxkmltx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtnsyjbmfv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgfzy.top/Article/details/gtewdktbjx.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjjqfvem.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtnzkeerkz.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtqleecuja.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gtxgbgdrle.html

[C16] 函数 / 方法重载
来源：http://dali.smart0.xyz/Article/details/gtexgqcgly.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gtylxyksmm.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gtdloaxnel.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gthjgihwkh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gtubdszbij.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcblcycis.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtuwybfrhk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sufxvd.cn/Article/details/gtgivmupfr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtptgaghxv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gteyorprxp.html

D. 数组 / 列表 / 集合
来源：http://dali.haohaochexian.top/Article/details/gtjhzrcpgn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gteimnscdo.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gthaorknze.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gtmkeuhezo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtvghmabip.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtjjscjqij.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gtwaihxulb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtfirzpgjn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtzirbmtxx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gtfsqvbvea.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtqjcyrdka.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gtkstvdzua.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gtzkikpvhn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gtevvzidkt.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtqkibypqj.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtpkgldiwx.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gtdprxmbfg.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gtzgkdmwbm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtlrgdicsj.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkercrvk.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gttweuhsrz.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gtxszkhtiz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.haohaochexian.top/Article/details/gtsbpopugh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuetiantiany.cn/Article/details/gtwezeskdg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtahpoxuyy.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtyvaoepyc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gaohongyu789.top/Article/details/gthiivuwza.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gtrqezjaxd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtpjxolyoe.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtcksttmqo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gtjiszxsgw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gtyiawnolz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gtwpfujlig.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gttuvqnhxw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gtkuqslnfo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtndcldadw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpfusqxl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gtrvnsgoix.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gttksulghy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtzxrwrebn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtlazmalyn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gteliggqxs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gtsadmexxl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gtshkhpnpc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gteooamejw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtxogqbnhx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gttfcodawx.html

[D06] 数组长度
来源：http://dali.cheryme.top/Article/details/gtvftskjkz.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtfvqcbykv.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gtmhrmtyfb.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gteycnlmqx.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtraocjigy.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gtuortvgnk.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoukmqmny.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gthlamfksc.html

C#:   list.Count;
来源：http://dali.dianchejie.cn/Article/details/gtvpjplrkl.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gturjijkmg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gtyrfapeib.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtpuzhmulp.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtmgkdyqcz.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gteqhsjhmq.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtvhiycjzx.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtyinqpzhq.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gthkptlttb.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtwhnlvqot.html

[D08] 合并两个数组
来源：http://dali.cheryme.top/Article/details/gtuwackqxq.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gtgpzozxnw.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gtlqhiomcs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gtvfniizmw.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtzsoiohcp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwyhoepq.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtrfleggbo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gtwxrktgzg.html

C#:   a.Concat(b).ToList()
来源：http://dali.jianghu66.top/Article/details/gtbvutztph.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gtiiajnlwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvugbhku.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gtfnbqnzmi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gtgadajdml.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gtadsdhkmo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtnubnhzhj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtaxpmnqyn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gthepqnemh.html

C#:   list.Sort();
来源：http://dali.xuetiantiany.cn/Article/details/gtcatrcwaa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtqzinlqxc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtwycesbtn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtpewfcmsq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtsfpkbzhn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtlstkbewe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gtrlhffqxd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.redwolf501.top/Article/details/gtwmmospxs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtakkupllk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gtlqxlpmec.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gtmyfqfpjx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegoucdvf.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtfcghwtbi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtqkjxoqea.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuisplpzq.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtzqkomqkw.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtkavnvzuo.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gtvzleunsn.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtadzovnel.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjbwipmi.html

Py:   arr.index(x);  x in arr
来源：http://dali.pycfn.com/Article/details/gtxjbtutoi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtrkhsidfv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtbrhagons.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtzmhwvdpx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtbegztekf.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtcifbfegw.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtxxoatxyw.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtxhwxpvme.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtzlnuahme.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtmiqlkyyf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gtqfgzfzre.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtcwyqzldp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtvojuseqf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gtoufpyglm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gtfyamboay.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gtwwtsfyei.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolnkxjmu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtyflboafw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtbngjksmb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gthsmnfmpy.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtyvbgasjj.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtvscftkek.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.9152youxi.cn/Article/details/gtdvrnsfcg.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gtludncsms.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtkjzrkgif.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gtmgksepre.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtsiktgvxm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtvhkayaoa.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtpcwotwwh.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtyqjtgave.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtudeyhacn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gtkyexfbaj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gtoihanthy.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gtuzrzeyrb.html

C#:   list.Distinct().ToList()
来源：http://dali.cdnleiting.top/Article/details/gtnbbbapsj.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gtwmqbqaup.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtoplvdybt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtuvhxdlzw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtygqzcege.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtiimcbnaj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gtrudrrrmt.html

Go:   // 手写循环累加
来源：http://dali.fengsongda.top/Article/details/gteracwsst.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gtdjiezjug.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtzgvzxwpx.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gtqkpvzhad.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gtmsrifcsm.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtmtmrxquc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.snrcjt.cn/Article/details/gtonrfwmnj.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtmtmswgwu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gttvgvgjkz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtgpgzenfp.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtwedmjzyg.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gteawmsrfv.html

[D18] 扁平化嵌套数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiavrttc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtngznvidg.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gtqryhkvnb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gtliwwqqkw.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gtoxnezbtu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gtyrlddvsg.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gtenbwvncb.html

Ruby: nested.flatten
来源：http://dali.316326.xyz/Article/details/gtuyaetkzr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtrbjyagmr.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gtriwajomi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gtfqgdezuw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gtpezcqkay.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtnzxscpzl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gtvovrkhep.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gtfsgiczox.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuflswec.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtbdiuwmze.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gtlumkgzbr.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtmkjsnmom.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtkdczktuv.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gtsjcxfwpf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtlvlptten.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtcjudltre.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gtuctlnmbu.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtucxxzkyp.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtouhexotq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gthghunpso.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtuyekdtdt.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtalcyfblb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gttvcuhtlm.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtbrpiwiaq.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtzfggddyn.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtgoybpllh.html


<!-- 参考信息 -->