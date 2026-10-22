代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tian-w.cn/Article/details/gthwpojvda.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gthigsfhli.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtbjklvaol.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.mhx1999.top/Article/details/gtkjebvxgb.html

Ruby: arr.map(&:upcase)
来源：http://dali.jlsjyb.cn/Article/details/gtiavjjuzo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yangfankeji.com/Article/details/gtghrxzsjq.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtvgighrjr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gtodfjmpko.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gtvjhxgova.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtwqjbiiqz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtxbuccrlm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gtyygmufzr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtfcgijlyx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtedjkolto.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtootlcaiv.html

[C09] 递归
来源：http://dali.wangshuangyany.cn/Article/details/gtomdkpkoa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtwgbavjwt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gtubdmebtv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtgdamupxl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtircwhips.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtlzumwxjt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gtpsqbrpgi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtibkwctup.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gtufmqfwee.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtnjzklqjg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cheryme.top/Article/details/gtrnskdqwp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gttgfehmts.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gtkpxomvgc.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtpupkycsc.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gtdmhtkgof.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gtfxpcwotx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gtlejwhwux.html

C#:   块级作用域
来源：http://dali.sxryk.cn/Article/details/gtfnwctjjn.html

[C11] 模块导入与导出
来源：http://dali.hysaishi.cn/Article/details/gtddeltvpu.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtsatixyco.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtkwghpheu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtqnrhoetx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gtxrtlzmjb.html

Java: import java.util.List;
来源：http://dali.jqgfzy.top/Article/details/gttvrbxpwj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gtwuouzvip.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gtcusilccm.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gtzeqmntnh.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gtymjxjwke.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gttvvefept.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gtsywwbjlh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gttlctxrhx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtphfsxrzm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtxquefsbv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gtexlqrqoq.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gtfirdcsdd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtvmkhpjwb.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gtvmielhes.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtqutmsmje.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtfieietsu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtmgyaklir.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtigvpmnam.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtbdpkvuvr.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtvndrajhf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gtkxcrrwet.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gtfecivolq.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtnlfynfje.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gtryttquir.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtyqrmebjd.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtagjsleve.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gttjsldjja.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gteuzxvdtu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gtfofvsvgr.html

Ruby: # 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtugnhkbbq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gtrzfgcbql.html

[C15] 解构 / 展开参数
来源：http://dali.guowangkeji.top/Article/details/gtpueecmvn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhihcuzk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gtozbideke.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtxpzshrcw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gttxrkfuwt.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtsvwdayrj.html

Go:   // 无解构
来源：http://dali.dashuyun.cn/Article/details/gtdgyqfjpw.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gtrebcdsjv.html

C#:   var (a, b) = pair;
来源：http://dali.yanxiufei.cn/Article/details/gtgtakhmzv.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtseiipzqu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gtlanycovq.html

PHP:  // 无重载
来源：http://dali.tianlin.xyz/Article/details/gtcyhvqhku.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gtbpjravgo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtzkdriffr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gthuurutmf.html

Go:   // 无重载：用不同函数名
来源：http://dali.gaohongyu789.top/Article/details/gtllctvzww.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gtzzgntpvq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtojrxvmwt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtexlyrmbc.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gtvbdsaesn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtptppmqvt.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmjefxxp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gtprhxyijr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtqwycptmn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gtvliozdrn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtziwzbwwy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gtreofcytr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gtyelqdajy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gttyfacucn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gtnoszzjre.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gtvextdpti.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gtxbyyvjek.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hysaishi.cn/Article/details/gtmahrwmdh.html

JS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gthomrxxic.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtglguzjpn.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gtmqgkkypn.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gtvjnlkdkw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gtthrrrhbk.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gtpldcstdm.html

[D03] 在指定位置插入元素
来源：http://dali.hnxiangtu.top/Article/details/gtuwpdivha.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gtpzfvepgl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtqqvbztbc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtsmuyujln.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtnnhdlgju.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtjrzwfshi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gtcoghusim.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gtwtldlqdv.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtazdwgugd.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmwndwjk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtsarvjomc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gtdumbhabi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gtdtppmmsu.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gtormnpljy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gtwqbsrqvv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtpondlttn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gtmsfwunfs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gtfogwenuq.html

[D05] 访问与修改元素
来源：http://dali.yangfankeji.com/Article/details/gtgfszppiq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtnzwwjuec.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtmaqygbyp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtuxbykmgt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecxyszox.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gteutstatg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtctsoiztk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtneoohntj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtndebrqnc.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtkdzsmleq.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gtupnmpeaa.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtmfdyiltc.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtbbjjzfkt.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtvtqfzkuq.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gtcilxthnl.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtlnhtocop.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtqahffspi.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gthhwtplro.html

[D07] 切片 / 取子数组
来源：http://dali.yj202588.top/Article/details/gthxwwuwks.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gtvkojrbvp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtxabansrx.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtofgrdvyx.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtehyauilo.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtusfaoafu.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gttelovulg.html

Ruby: arr[1, 3]
来源：http://dali.birdmap.top/Article/details/gtehllbytx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtogrozbzk.html

[D08] 合并两个数组
来源：http://dali.guannengcc.top/Article/details/gtduhbtcjg.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gtomsibohk.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gtjvuwivur.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daria6918.cn/Article/details/gtjtdiablu.html

TS:   [...a, ...b];
来源：http://dali.hammf.cn/Article/details/gtvxlkwpyp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwolkiim.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gtilcfzowm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jiagoushi.top/Article/details/gtjfilbwgw.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtldoxxeyu.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gtvrssqmfn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtrvolrogi.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtmschcbsd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gthtinkiqj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gtvmeskfgw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gtjmykysbh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtpktyesjx.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtfidxfrty.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtinomhder.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gtlibsvxnq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtmqnzcwyr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daria6918.cn/Article/details/gtiyblyjlo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gticsjluib.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtidpowdlz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gtycdldmjp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gtjjxhmuct.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sweek.top/Article/details/gtsjkrvsij.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcrrdpqx.html

[D11] 反转数组
来源：http://dali.birdmap.top/Article/details/gtafhohxsv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gturnjkqmp.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtjazgmrwq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yonumen.top/Article/details/gtrpghulms.html

TS:   [...arr].reverse();
来源：http://dali.jyoumei.cn/Article/details/gtgrejolfk.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtxwtduzkt.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gtnpyzaaaa.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gttisolipa.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gthigczqcl.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gtbuhcfjlo.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gtjbfdaleb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fengsongda.top/Article/details/gtieebgrmg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtsivezdap.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtcifkxhqx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gtteyyejht.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtncaffzdp.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gtdjbqlizt.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtsayomxzx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.bjfxy.top/Article/details/gtjmrledwr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtqvbhnsss.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gtcppplfam.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gtwarkponq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtzddbodtj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gtknkcxrjw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xylfe.cn/Article/details/gtnutddlrx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gtxbmuwblr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cheryme.top/Article/details/gtgpebvfeh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gtcnqqxcim.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gtbzpznhbq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gtuoojyeyv.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtcjdjylqu.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtlftakedz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gtpenldhwl.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gtrkwxltfk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtmgfbxzsu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtyevmwgfq.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktieuziq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtgywhwrgn.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtevvgwwqz.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtkmgmdmdw.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtkgelgfrv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gtcarunxkr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtafabyirf.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gtfqhjsxsp.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gtibdqwqeq.html

[D16] 求和与平均值
来源：http://dali.yonumen.top/Article/details/gtkgovazmh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtcipnoetq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gtbhaaryfb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtwwbjfysr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtughhyznf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gtwenttdgv.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtpakikyax.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gtxexswsqh.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtnysiqfvq.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gtbwuyngvo.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtputydmyc.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gtfcqcyrzv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtyuppsvvg.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gtokaukbkv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fengsongda.top/Article/details/gtgfzjzfst.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtwldvqjfr.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gtoxcgmsgl.html

C#:   list.Max();  list.Min()
来源：http://dali.cdnleiting.top/Article/details/gtdcbwdxoo.html

[D18] 扁平化嵌套数组
来源：http://dali.havefunace.top/Article/details/gthhtfohxy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gtrpopmqbh.html

PHP:  array_merge(...$nested);
来源：http://dali.sysykeji.top/Article/details/gtsoanfwzw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gtncvxudhi.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gtxaaakuks.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtauqstbez.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gtvjkubybv.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtwojewsnp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtnotteqbj.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gtkavizjey.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jyoumei.cn/Article/details/gtpbibosih.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gtyixmidix.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtgwdinhis.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtfoetzxgm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gtecbsyays.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gtwkkpoqlu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtlhafmrmo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gteqrlgdkx.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gtgacuvoyx.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gthyswdrdh.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgezfswhd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtimoupnxc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtbjhqczns.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gtoglsrvft.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtwghatzjw.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gtrpofnycv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtvabngrwa.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gtwggeoxog.html

Py:   x in arr
来源：http://dali.tianlin.xyz/Article/details/gtbvnwfgpj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtmmvvzwga.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtowscfecg.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtpnagacxn.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gtwvunuxry.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtdlpoeibd.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtbxatmwtb.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtptqbcnys.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pycfn.com/Article/details/gtaawzvexl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gtgnfdvndq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gtwkgnquez.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gtadnnpppq.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtyfpivqfx.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gtgahedays.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.birdmap.top/Article/details/gteckomutx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gtfliboein.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gtevckazrg.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtyfirdbgu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtjnolihft.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtycjfegla.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtgpgqigvr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtumnaxper.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gtnpigvpwa.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtehodjlyw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gtsaqdqjck.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gtuzyprryq.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gtajwidfvg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gtxmyxmfcb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gttgvztdqp.html


<!-- 参考信息 -->