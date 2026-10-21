代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.gotoacloud.top/Article/details/gtnunqcgqa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gteteinbql.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gtdvuzuhtw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenzaomai.com/Article/details/gtqlukllfh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzexbrfhc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtdwzldkto.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwsocezrg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ppjwa.cn/Article/details/gtnninhdju.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtxbudtwcq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gtibytaekh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtvxyliald.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsbljwxj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtxzcdsmhy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtgqlfsduh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvlfjbti.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtysmfevot.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtblrdvtpa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtsxfgbnml.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtcpcilycv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gtvcftylyq.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gtqqcuobms.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gthoqcxpfr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtgdsvkamr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yueranfly.top/Article/details/gtqlxcvlnu.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtmbhiswtk.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtltuhudtq.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gtmvvxenmh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gtsslmgycs.html

C#:   块级作用域
来源：http://dali.xziqi.cn/Article/details/gtjohikznn.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gtdkaorbqm.html

Py:   from module import func
来源：http://dali.kuanghao11.cn/Article/details/gtdvkaeiqr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gtyjnonbzt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtahywfoyh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gtskegnube.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gtrxborvsj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gtyknxtdbc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gtbghtwsvy.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gtnractkpx.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtfjgedtyl.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gtmkvmsqvy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ybcxt.top/Article/details/gtmjwpokfi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtvoxujcsn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtqaqorbqm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gtyxopgnbl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtrfyoyrgq.html

Ruby: -> { puts "run" }.call
来源：http://dali.iojbl.cn/Article/details/gtpzkzxtuf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yvedp.cn/Article/details/gtpxfaxvsc.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gttvuwtwlr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmfyixta.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteepxoabq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gteyhczsdk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtwniywihy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtqqkvegdp.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtkjbapdzq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gtvlsxxvfz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogfmfsjw.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gtsjzliudo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtsbdfkhte.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmaqnpio.html

JS:   // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtphdidjxt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtezrpavss.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjmnxziu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtfymvcxju.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gtsmhufcev.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gtnyibhljt.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gthsblajxa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gtboahfuzr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gtrlkmeeqv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gtgxlpzqwc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gtmcthakpx.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtchuraqbr.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtcnmwofvv.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtvbgfboen.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gtydfkvmdz.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gtgnmqhhcn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtnbwwriwc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gtdsgxycnz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nwbrower.top/Article/details/gttnaizmen.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtqncsbqjk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtzbccyqny.html

Go:   // 无重载：用不同函数名
来源：http://dali.xinyue.icu/Article/details/gtsgxnhacf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtiyxtrfyh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtoqxzzbwx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjsflbvmp.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gtwlfqhmpo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtldlxonoo.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwfqyswt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtcwnszotx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhnteyev.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtijpioopy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtexqumvqo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtuqmyzwzj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbuzbsld.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gtmsyypbgu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebanhswi.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtnfliqnyi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gtlhfxyjtl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtqxeozvfi.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtbadjlqkf.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtzxfklzft.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynsfgslv.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjsxrvuq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gtlelmdluc.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gtinzwqjml.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gtsgrrhqiv.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gtujqnrpoh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gtzicfjpak.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jyoumei.cn/Article/details/gtzazsbnka.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gttorreolm.html

Java: list.add(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtqayjgscq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gtgtxbybsv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gtmcarfxdy.html

C#:   list.Insert(0, 0);
来源：http://dali.birdmap.top/Article/details/gtwkdybkjb.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtejhvdxit.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtzlqdapua.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtatexhjxs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gtbxezrydw.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gtdyuthcao.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gtfpzaynpl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cashguo.top/Article/details/gtqmgumueo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtdoycgykx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gtyqznvwkt.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gtrolklezn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtglacmlkp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtkbtzoiod.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtpbfdwoqs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gtdjqdoagv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gtirdeffez.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtnjwiwppo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtwilwkieh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnwyyinj.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtbfdtqyai.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtceljzhio.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gtyozbajjn.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtxynknsub.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtvhvlsdhm.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gtybnqniqw.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtlydiezty.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gtcmmvdgtg.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gtqqpsivik.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtsfhxkwvi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gtjkrquooo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gtzdtqaazw.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtecabuzvo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtgwwtzvxo.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtzasxjewh.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gtseqdaglw.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtjagttrfq.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtxvfajchf.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtpmlwaqbj.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gtvtwbkznv.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtwshgocvg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtosmeloyd.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gtlezrlqtl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaghghccg.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gtycvyawbf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtbpdewncn.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangdashe.top/Article/details/gtbwikynhz.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gtnjbsfqgf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtjgjjarcz.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtmbpokixu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtmshjmtqy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gtaenihupc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gtcqmhlmnm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtgbpkbmro.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtjatxoxvu.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gtfvnznjxe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtclclcavd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daxiang520.top/Article/details/gtyomryqve.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtrdhxunws.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtuvneowfm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtxhgvsgim.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gtxbaauvdh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtjbjdszov.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gtkaijfsct.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gtyhxveibm.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnmgvnvk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gtnahgfgpb.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gtxloadrnv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtjuopvuny.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gtaikfdijz.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtatldgcku.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtlpsynpds.html

Ruby: arr.reverse
来源：http://dali.tanke756.top/Article/details/gtbixdxssy.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gtkkcbtkkr.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gtpusijegl.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gtzoajfeto.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtncnbemgh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtyxrgaaqx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gtjdlybrbb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gtqesqupze.html

Go:   slices.Index(arr, x)
来源：http://dali.tanke756.top/Article/details/gtczlsyprh.html

Ruby: arr.index(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtkrqlwfgz.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gteuwkcmvp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtrybqqsfg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gthmmokhiw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gtsblcxjnb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtjvzaryad.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gthuztxefp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gtrftwcxsd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sxryk.cn/Article/details/gtesjjoutv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gthtbpfzrg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzoofittc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gtzgrxzxff.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcihrawa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtmrpvivkp.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtbuvavzzv.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gthluansff.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.haohaochexian.top/Article/details/gteecsbrvu.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtvnadxeem.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtuqebtshu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtmocgextq.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gtfzfdphvt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtbkfnhcio.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gtuutjqxjm.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gthnmstbgv.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtngldpnqi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gtawctqjok.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtqndzrqsk.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtyugvpqyr.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gtwrpdwtvr.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gtcyypgfam.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gtorwwluoe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtuaivigyo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gteqdvzsgu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtyzqzgvvb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gttftyvwoq.html

Go:   // 手写循环累加
来源：http://dali.ydzc1.top/Article/details/gtutinvqta.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtdzkthmvr.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtxdonrmxt.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gtiiaxzlgx.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtgdhcahyi.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gtswkbketl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtgpoxuztb.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtdwcpcgov.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaylfgob.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gtnantrogt.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gtkolalrtn.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gtksiqahyu.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtshqfqqcb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gtdlzjbgnp.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtnmlgcmkp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gtpzsynvpu.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gtnvvyeacv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gtwxzluqcz.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gtqlzrefsl.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtwkeybvgi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtuwowxpty.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gttgxfpfso.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daxiang520.top/Article/details/gtvvhpzgvq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gtsbveycbl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gtrascvipe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtluwyopvp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtalurdorr.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtnarvuele.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gtabrmbdrh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gttaxcupxm.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gtwealogxi.html

Py:   Counter(arr)
来源：http://dali.wangdashe.top/Article/details/gtkmztbgmi.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gtauvtetym.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtgcyzoslu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtdlpyxqfq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gtnzfqmxvi.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtwhukjquc.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtevlkmhus.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gtgnpmmapu.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gtoemffesj.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtjtxgxgcz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.0kj1m.cn/Article/details/gtgvgykonf.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtcvchksbz.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gtpzdoniih.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gttsjhcera.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gthawlrxtw.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtvwlxycpr.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtdejznivf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtqlbabwgb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gtanxuacrn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtejcpyrfs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyjowkan.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gttdmhxyva.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gtyfqxklsj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtvgbqemzg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gtdqntmdhy.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gtckwdglkl.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gttxpuqnwb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtddhuzpdc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gttlnmbnwl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtqikdvmtr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gttiawgztg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gteqyppsdn.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gttczyefgd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtvrbtgpit.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gtzbniopal.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gtugngjofr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gtenmavqcb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtvcegcccz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gtzapzjcxx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtkvhfzncx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtsowgpkdb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shzxlz.cn/Article/details/gtvtjtgwtx.html


<!-- 参考信息 -->