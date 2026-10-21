代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gtkwscsguz.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gtvlhjhyxg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtixgpqjjg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gtlpymekdd.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gthwqeglbv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gtjmycfxty.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gtorjfrwnq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gtwozalrdw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hywenlv.cn/Article/details/gtzfzeinzf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtthbebfar.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtpudwujae.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.316326.xyz/Article/details/gtrvuqqswp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gtkewfyxht.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hywenlv.cn/Article/details/gthdfbsgyg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjepurpmk.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzginptpo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gteguijeoe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtrbgggstn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtruwfhgkt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gthaiffetu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtofsmdncb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gtrafpmjde.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gtzmubvywb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtjzhfyqcz.html

[C10] 变量作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtgidscqmw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcalrwun.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gogol.net.cn/Article/details/gtbipcpfht.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gtmyggmnvm.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtiglotmji.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtbwiyvivq.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gtixxuuphx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gthkwlaltu.html

C#:   块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gttzfppffw.html

[C11] 模块导入与导出
来源：http://dali.yonumen.top/Article/details/gtgwjrzbpw.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtuhjqbadp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gthlghdcsu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtcnnfgtuq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.haohaochexian.top/Article/details/gthszkkbqr.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gtyxhtmvyn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbmabfok.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gtsmcvrckj.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gtkridezad.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gtkvoalvkv.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtuhaanpyt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sxryk.cn/Article/details/gtqimmaxcg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtayruvuul.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gtotfowkvs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gtqgeklxwv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gtgwutfyoj.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gtcojcyupc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtoghwuixk.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gttrypbdxv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrwpjqpr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtrahsxuuz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gtfyhyguaz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtnhunrzen.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtvdzcnyqj.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gtximtrcjb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gotoacloud.top/Article/details/gtxkwfdjgd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gthqnsjcbc.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtdikjnngh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gtrfsdhphm.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtyptgaszc.html

JS:   // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtlgkgffpd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjlsqnoh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtfylsboij.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gtsccxvrqu.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfiukzll.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gttgfhhxvm.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gtydhjeaiq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtdldqlpfu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gtzelbkwpk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtbgrzijvq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtcodjuyca.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtzodjocst.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtbhidadyk.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gtgwauyspe.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gtynlhbhgm.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtuwuozmbf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtfwihmrlt.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gtwetgmtmb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtuvzodoji.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gtlarduekf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gtdauttbeb.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gtsnrmpijo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtrtawwmgl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ehwqpu.com/Article/details/gtgpkfbmrl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjldbcvxa.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gtmkpoqblq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpduonjsj.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtsqveewhi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtrrxvzxcq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gtpbhuqyew.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiajqcxv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtodzrcugd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtalpaibeb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gtylicvitr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtyqmxbije.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtxgmzstds.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtvyqquscj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gtdismlnty.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yueranfly.top/Article/details/gttlrjfrfe.html

JS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtoshoxuxj.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtlbqawamd.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gtpfnsxnco.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gtyyjhtucl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gtpnqlxyml.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtvfcgbxzh.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gtlsinrwxd.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtnnavisrz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gtaskpsjqk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gteqenlgco.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtafxtsqpp.html

Java: list.add(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtsdhzfsif.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gtiejcbsrb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gtxkrzvezi.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtkbfebqjg.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gtfewhlwug.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtzfbynlhx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gtzlvaqjyv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gtbkdpqrvi.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gtousupbkk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sweek.top/Article/details/gtwnjxoyxi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcfaiaeh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gthlylemes.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtymlzuvln.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtshompklt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtkiogtejs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtkhhcyuxf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtlcnihjbv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gtpvmhhzlk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yueranfly.top/Article/details/gtgotrwlag.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gttwokbbxq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtjfngezka.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtyktgzlnm.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gttrhsnsnr.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtffgbbqqi.html

PHP:  count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvhuomwe.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtxofsiamk.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtomonmeuf.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gtbbhmvldi.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtdjwhqqea.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gthdbuvsrj.html

C#:   list.Count;
来源：http://dali.jqgufenzy.top/Article/details/gtkostgfkr.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gtquqqqccc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtrrxttyzs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gttbwccuty.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaazxgqog.html

TS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtlrrpstkm.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gtyeklsvpf.html

Go:   arr[1:4]
来源：http://dali.ivvv.top/Article/details/gtizxsqryd.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtvxiyewiw.html

C#:   list.GetRange(1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtfvukkimu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtiezzowcc.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtxjktcdtd.html

PHP:  array_merge($a, $b);
来源：http://dali.cqqwz.cn/Article/details/gtnyzvhvpg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gtvkkvgbob.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gtbzccavnj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtfdgldwqq.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gtnhnqcqfu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.andypj.xyz/Article/details/gtqlywxpwc.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtobacgnrr.html

[D09] 排序（升序）
来源：http://dali.tianlin.xyz/Article/details/gtavjpnsbh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwvcokei.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gtqqazpssi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gtiwxdlwnb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtnphxtmxw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gttnlghjan.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtatnznxws.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtzxcnvvaq.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gtsggdvoms.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gtckqtmgor.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gtqayglhzz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtarnkwzjp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtlgigveen.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtsfzqloqu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gtobpcxeyd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtpqxozimp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gtjbaxgrzm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gthxpvaejk.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gtkrotcxjb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gtfpjzklit.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gtgljoagih.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jyoumei.cn/Article/details/gtddvdllvu.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtdoamrkoh.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gteodprswg.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gtqtvgunys.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gtmfofkale.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gtysgjugbu.html

[D12] 查找元素下标
来源：http://dali.jinqigfzy.top/Article/details/gtosqsgxni.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gtjqtlcmfe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtpucrojne.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gttbnlyqlr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtdrvdqzxq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ehwqpu.com/Article/details/gtivllxcob.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gtvzcbbvdv.html

Ruby: arr.index(x)
来源：http://dali.fzhhl.top/Article/details/gtmnkrpeyn.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtcaqroqum.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gtgsyeabyw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gtmspoywkn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gtiltrjruz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtpuhhbnef.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtroodujlj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtwfazqbzh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gtlzmbcyef.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtcwhiuzvm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtyxxpovjk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gtrsalylyl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gtvvmtfvnu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdlcuzol.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtqagolnop.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtlfmhdzdi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtetwvyzkf.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gttjqzjcjs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gteaztcfkt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtpexolcum.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtbrmlvadl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtplaalcyb.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gtxzovknek.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtjholkjrt.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpaopexax.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gtgjfbnrag.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gttltdvsrp.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtoyncctae.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gtvlncfqkz.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gttoyvznse.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gtwyrnwylv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuanzx.com/Article/details/gtoigqqhms.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gttbwemgym.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtcegusthu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gogol.net.cn/Article/details/gtsrtfrkvo.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxcdoymv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtzpxjpvkd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gthahravmg.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gtwxczdmjn.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtklfxxccu.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gtjqoyljjg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gtmshlepet.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtgcmllorn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gttgoasncd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtkohaxoth.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gtifklfukm.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtyyxhcnii.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gthuylyitd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xinyue.icu/Article/details/gtvkjksvre.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gthbfluupo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gtpwtsejlj.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gtermslhoq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtskcbsvbl.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtndhzirbg.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gtkswpkrrh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gtohwiejin.html

[D19] 按字段分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxceyqon.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gtqagczqoe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gtnqchamaj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gtbgspbnwh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqaxjvgt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gteorghkuz.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtdkgrigcb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shuidangran.top/Article/details/gtwgtdmzuw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtsjeiiroz.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtlxkzfblk.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtqkisyykb.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gttuxmjhrf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gttbebhmwi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.iojbl.cn/Article/details/gtkvwfebin.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtfsgrfatw.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtbtejykkn.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtboytmbtw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtrnkpqgtu.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gtmilqhfvd.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gtpdsveorv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gtaceauiml.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtvaxphsyj.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtjzoujzxi.html

Java: list.contains(x)
来源：http://dali.bjfxy.top/Article/details/gtulzxihov.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtmaxdnipd.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtglwxbgvt.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gttvvcbsoi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtevfxxdrj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtgjtfffzz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnqzz.top/Article/details/gtatsnlfil.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtrkmiirnq.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gtceyzqrrp.html

Java: new ArrayList<>(list);
来源：http://dali.sufxvd.cn/Article/details/gtwknzueuw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gtapilodlc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xinyue.icu/Article/details/gtonmvtitw.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtfihthoiz.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gtyqdirztm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtcddkgkoa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gtqtiurpgq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtkkcevdai.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtbjfamoiu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ybcxt.top/Article/details/gtuhbgzgwm.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtfrnjnihg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gtmddjicjr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiuhndeq.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gtucucvcnc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gtbewzieam.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gtwftpfodh.html


<!-- 参考信息 -->