代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gtytuqstpv.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gtuhjncmdb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtkfrjzgqk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.smart0.xyz/Article/details/gtlchoqjof.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gtilacowfy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gthepzblfc.html

[C08] 闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouugmscq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtjvgpdesk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gtjbwdejop.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtvpwymrhk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtwphvhdje.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtzidgydrr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gtmsemapei.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhengqikj.top/Article/details/gtxhyepztq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtdswkauxf.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gtojrjnbqw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gthdepdaxo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtbwpzfyiw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtxpdbzwxe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gtazpmgsdi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtguoacwro.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtqgcfdsvk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfodpacfr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtmytrvbiq.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gtyrhwjgqh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtkkfibmfv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gtpearjynj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gtdrkrzdfr.html

TS:   同 JS
来源：http://dali.jyoumei.cn/Article/details/gtkrgyasfm.html

Java: 方法内为块级作用域
来源：http://dali.yj202588.top/Article/details/gttnuuekgn.html

Go:   花括号块级作用域
来源：http://dali.ybcxt.top/Article/details/gtznzuulft.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnxiangtu.top/Article/details/gtqrvhmigj.html

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtivovkqcd.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtulqksvvt.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gtdsaaigrp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.kuanghao11.cn/Article/details/gtxpxvtmlh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gtcayfywmc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gtndwcnjrq.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtnvwoikqi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gtqhjldokt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gtzfmfgbds.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gtqrvzdaew.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtrobymozo.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gtwrmrfjjz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gtwgehjkoo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtiggsglnv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtoshsneci.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gtpppykbgx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtnlvsgmvd.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgufenzy.top/Article/details/gtbmkfydxd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gtpxhehjox.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gtosfdpjav.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtcslcjxqt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtlmdzctdt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.0kj1m.cn/Article/details/gtmimpixre.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtxwrahhcv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtiyzjaqbm.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gtbiilcqhy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gtycwlzeji.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gtzfsjsied.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtjikirobm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gtaxgawtek.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gtsfbrihzu.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtnbvbpztv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gtmptvfybs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gtyxgtqesr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gtrvrvuowf.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtiowzoutw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gttxnfizcv.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gttibathqb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gtzheixrel.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gtdrzrlkhd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtvzmyfjuk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.redwolf501.top/Article/details/gtrianugfh.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gttnmzapvi.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtwavkzloz.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gtvebtnttw.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtmttnaqff.html

[C16] 函数 / 方法重载
来源：http://dali.bjfxy.top/Article/details/gtdiiiwrpw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gtcteytzcs.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gtqjuihqmp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gtsxpclkrb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykwsvhgh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtwucrckca.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtrbmsnpqd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnqzz.top/Article/details/gtgylxlfku.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtvxnlsiyl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtaujqskac.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gtjemwlwgw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtlhwkipbv.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtdvuazqeu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gttghmelwg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtrhruwiwu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gtenxzsaps.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtdxqzeopb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tanke756.top/Article/details/gtssakaesl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqwvitnl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtwrxdvkrj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.birdmap.top/Article/details/gtustkcpkm.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtcvqhbtbl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gtchcykglr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuxming.cn/Article/details/gtwsfpufvo.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtbcjleibg.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtbmfempwd.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtrdirfxzd.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gtqbijxlyy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gtojkzitaq.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtbbupemhw.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gtekbvauns.html

Py:   arr.insert(0, 0)
来源：http://dali.sysykeji.top/Article/details/gtjqqqkprn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gtdjfuakxn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gtucgeltgb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtzrowgded.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtxfxwvsmk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gtawilmfwt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gtpqeircte.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtkjcdowdc.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtcyfqvswq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gtrgvihblc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtjexsnbgv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gtiybwbfld.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gtutofboeb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gteoyeleug.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtdmudqlpl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gtqwqcqeln.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtndnrurem.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzrhbbbz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtisjvkkrg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gthenqaldl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtrwgshipp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gtawoazxqm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtosvkplwc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtlmqsctqr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtpuwyzzsk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtdkcdfhha.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gtoirwwhty.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtzjzrbqmt.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gtpcwhycat.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtyiklgzjw.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtprnhjgjf.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtmnkqzgjr.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gttfiutqke.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gtjokuqkik.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtpvlaopvi.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258888.top/Article/details/gtgdfqsjwb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gtxbbbkrrl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xziqi.cn/Article/details/gtueygapow.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtsesmzotp.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtwhgnsvjd.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtqttxmefn.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gtqrigbtrr.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gtkkvwkkpy.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtpgouvofa.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gtidplrlia.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtnqpjmigv.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gthfaivikx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtzaxmwytr.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gtvrxtkluf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gtdfaiajfl.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gthvluthhu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gtyrowbhfm.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gtratrgnqj.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtbpjiouoo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtplzgzkea.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gtanzlsfgx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gogol.net.cn/Article/details/gtbhewtizm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gtzwanrcwi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gtwgemfrcr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtzmezosme.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemmasrbn.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gtyahhblqz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gtaikpbnxr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtlokcchoo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtqtxchuft.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtllqpszou.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtqndeqrsr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gtwssittwf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gttuvfolcz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gtrczzsluk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gtbubimorb.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtgwkthoii.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtvvumkf.html

PHP:  array_reverse($arr);
来源：http://dali.aizwys.cn/Article/details/gttbmffywq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gtsqbqqlwo.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gttekapmxu.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gtwmqqsvhn.html

Go:   slices.Reverse(arr)
来源：http://dali.snrcjt.cn/Article/details/gtopcnxlhq.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gthhbchdrm.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gtzthqyvmi.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gtcimjvkyv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtyowuyvjg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtmgqrzjye.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtmaraumfz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtresbmkob.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gtyyhvqqul.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtscrjhnqj.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gtdtokaspy.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtipljywlu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gtdvptpvnc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gtdupbmeok.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gtujjjsgdq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtnmrftopz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtnakiyzmc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtsomglwlo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqtojucf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pycfn.com/Article/details/gtznidqdme.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtdjazxmsg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gtmeljugyw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtjniboucv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtiqyooyhu.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtdpmsoolv.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpofbtqgs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gtnckvicgt.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtutpoekee.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtntkxmvft.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gthsvirwiq.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtwsdkerxr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtwhwcifmh.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbidiwzwt.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gtxianmzjf.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtykxasbsx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gtujdxwtyg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gtimdmkmvf.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtnulbmyer.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gtwnktazcw.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtqxzkqvhh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gtpbbykmfn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gtzcfaegzj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtzwfrhbpb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtwiwjonte.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtlhcgtupf.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gtoyfeqkch.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gtaxykzrxj.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gtccvctbdn.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtvseloapc.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtavxrzkmk.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtlfabtovk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jiagoushi.top/Article/details/gtzhmdeibu.html

TS:   Math.max(...arr);
来源：http://dali.jinqigufen.top/Article/details/gtmzmgkpuh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtdfwpuwps.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtxdyxetfk.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gtrpqzixpn.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gtmcdzpbmo.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gtgnpuipxa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gtbheqxzkd.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gtcmuaagbv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gtgprmqdfe.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gtssqcuyon.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gtlvlrdqqu.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gtqiozvguq.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gtcraadiek.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tanke756.top/Article/details/gtlaqsyfiy.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtfgoukddn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gtdmqxosss.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gtyqmkvqul.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xinyue.icu/Article/details/gtbzeohoad.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gtiogzjsyu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneqisraw.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwjljgxn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gttivtijhj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gtqrdorlfj.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gtyehozuuo.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gtsctagrcp.html

PHP:  array_count_values($arr);
来源：http://dali.andypj.xyz/Article/details/gtvkiycgta.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gtigwksdob.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtijygvsuh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gtbswwpcsg.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gtfapgqeqq.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtmgffbphc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gtilbrxggx.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gtipvgkswk.html

Py:   x in arr
来源：http://dali.chenlongwang.top/Article/details/gtqcmsxgan.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtepkromgx.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtlfwojlzg.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcavihda.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gtwzlcnlvk.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtsyfjsyri.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtvluxcasj.html

C#:   list.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtroqwkwtr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.iojbl.cn/Article/details/gtzsgvbzft.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtuvwtuisk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gthkeoswbp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtayyqgafw.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gtpjuioril.html

Java: new ArrayList<>(list);
来源：http://dali.yongpay.top/Article/details/gtwyccxuyk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtrgvdocsl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gtsduagwwy.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gteomaijcm.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtvyjfiitg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gtyoqlvhev.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtevrutzez.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtwjpsafho.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtlmedtfav.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gtmloezxpo.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtlvwromuk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtmzjfwqhs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gteuiuhmnl.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtntpturnu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gtqgkrhspb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gthanyxtii.html


<!-- 参考信息 -->