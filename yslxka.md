代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gticxikwra.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gtxnotcsfv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gtfihexvcq.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gtbeaompmk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gtrleakhtg.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gthyrsthhg.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gtqhdlwbcp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gtmdlvuhux.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtcuwajvam.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gtvgtpbrhn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtnnuzwwez.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gtthjhkfkg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtdaeaxjvq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtdmwzyokh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cucudq.cn/Article/details/gtdlndrbic.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gtieurrzpi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gtyllckayp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtoynqlvni.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtsjbwtlwl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gtmkfkubqo.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gtvoosqveq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtkduvrsmk.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtpxvvjpyx.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gtnkeeuofh.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gtsxidtrbm.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gtitqszziz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gtzphpfenr.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtxqkmtwzx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gtgkgwbrch.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtpppulwzt.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gtaattzwff.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sufxvd.cn/Article/details/gtvksnltrw.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gttacaoixb.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtosskvflz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gtmqaijiwr.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtgfoebgbw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtpafmzwiv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gtbvjuhdyj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gtfdrimnxp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gaohongyu789.top/Article/details/gticvrjawo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gthcmatzrs.html

[C07] 把函数作为参数传入
来源：http://dali.jiagoushi.top/Article/details/gthpnjcgcg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gtpgposipj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gtnlbigytv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtzyftcfci.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtopviytgq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtbhrofkya.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtdqozaxml.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtmxfbfyvk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtxmuyeohg.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gtvzormvgx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtkivvndhr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsjnhnqo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtdbufdupe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmrnhrdod.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gtbvwpsotl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gtyozxfaei.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gtkfenjmee.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtpnqmkbmd.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gtxbakmhsc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzkodbraz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtatwpdryk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtllximzyh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtflndivpq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtejiyzrie.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtyalkhgxg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gtbmuwrnbs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gtlejykicf.html

[C10] 变量作用域
来源：http://dali.9152youxi.cn/Article/details/gtrrteguqx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gtqqdglmrn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gtdicgdrcf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gtyjpwhvpt.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtqzpkhavl.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtzvfaciyf.html

Go:   花括号块级作用域
来源：http://dali.havefunace.top/Article/details/gtlofimija.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gtpubcpiao.html

C#:   块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfdjjyqa.html

[C11] 模块导入与导出
来源：http://dali.jinghuilouyu.cn/Article/details/gttxvopvem.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gtkfcjhyia.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gthyofdnig.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gteflltade.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258888.top/Article/details/gthjbzuywt.html

Java: import java.util.List;
来源：http://dali.jinqigufen.top/Article/details/gteqfmvxww.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dianchejie.cn/Article/details/gtvobutafc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gthvwhdsiz.html

C#:   using System.Text;
来源：http://dali.quarkkingdee.top/Article/details/gtgkxeheft.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gthsveszgv.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtionorytc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtcdjiatsl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtcccydgnj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtpomsugoh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gtyzplpveu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewlzzffu.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gtjoipmobb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtmjzqndod.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gtuiogoxdd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwuvnpog.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtcewigttb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.snrcjt.cn/Article/details/gttncbvoxu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuichmrfi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtagbpraiu.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gtajuxpptl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gtrggfzodw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gtouhjcvyx.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gtiprxbqsb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gttpqgijwg.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtwqzqbfsh.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtlaiklnao.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gtaxvdalhx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtxdadvozo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gtxkkkcven.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtgyitegke.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gtvhruvsgs.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gtpmtqkqtc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gtbylrdjkp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gtrdyljsac.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtxicipyct.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gtbguxntbs.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gthjexrrvt.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtxmnzvlsp.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gtoqvkilnh.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtmlmcprck.html

[C16] 函数 / 方法重载
来源：http://dali.chenzaomai.com/Article/details/gtnuoythee.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.haohaochexian.top/Article/details/gtyeweddnz.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gtaidbabvs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gtubrmnohp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtritsiltf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmvhlmtgh.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqidlton.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gtvgckufho.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtqvcbwlay.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqhmhagrr.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gtgyubfhsc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttyldskaf.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gtubekrsoy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gtdxspnars.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtgnphqlrd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmnmgbrx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtipquumnj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gtjgapriqk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gtgnntkcdp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtntcwikll.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.vqdsnc.cn/Article/details/gtfhnduqev.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gtmewjwdpm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gtthjpbako.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gtjgcxqzsk.html

JS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtipcpfapg.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtpkxidwff.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtosxtyhsg.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtuqhrvhyq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gtjdiezwvt.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtuxzdwgfd.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gtiaghjnkq.html

Py:   arr.insert(0, 0)
来源：http://dali.iojbl.cn/Article/details/gtsgqeeqvf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gtjvomutis.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gtzpkmqejf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gogol.net.cn/Article/details/gthsfaehku.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtxesqstgu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gtryxniiyo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtubzjxzlk.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtebludruk.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gtxutngtpj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtmbhzpofo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmknoblbl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hysaishi.cn/Article/details/gtbmwkypbf.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtsacrwzcq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gthpnbzqdu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gtjlfoqxks.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gtlgxojjdd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.c1oappe.top/Article/details/gtpxkrjrzn.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztyavwnp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtrfnrrppm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtivraplfn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtiwywudtl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gthcopiftu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtsmgyjmvf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtcprsaral.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtyranvaev.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtrurqvcnt.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtvtkrvwme.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtgchqvhqw.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtnvgqxzrd.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtsmnzhrqc.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtwihxjwhh.html

Java: list.size();
来源：http://dali.jinqigufen.top/Article/details/gtjckeecrp.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtfdedbywr.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gtihvhgrlr.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtcsxmsydp.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtyaamwwyt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gthrservon.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyfuphwg.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtxknbnaym.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtkwsavgjr.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecoxbksc.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtucndmedl.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gtsfdqqcug.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdgixmbx.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtgwptaoyl.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gtczhlehss.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqjjktkf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtptpyoawl.html

TS:   [...a, ...b];
来源：http://dali.daxiang520.top/Article/details/gtstyquyef.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxmegpiv.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjvwtnzu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gtvypxqaic.html

C#:   a.Concat(b).ToList()
来源：http://dali.yueranfly.top/Article/details/gtznnxrtnj.html

[D09] 排序（升序）
来源：http://dali.feifeiyinyue.top/Article/details/gtvpgjufoi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtnywnnrzm.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gtymzusqsa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ybcxt.top/Article/details/gtoonvhrvy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gtlmraqipv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gttdkoddxy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtnnitqdyh.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtzpczzlid.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gtehnojrbc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gtylavucdw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gtncqqnzeu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gtnyvbvyvq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gthdgnekcr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtmqmhrvvu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gtjojvodrk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gtldfbqkjg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtsvtjcarj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywsqljmq.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gtixtqxcfv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gtxoqajbsz.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtmssdplxw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gtanqkklpp.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gtrbsuyxhp.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gttcrnknte.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gtohmhxloh.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtjispnctk.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfnaazco.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtxyjlgqxn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtxzvobqol.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtuhydddhz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtapezyrzq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtbavddhnf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gtxgttngyc.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtkjceawwd.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtsdkgimbf.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gtvovcbsbk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gtfaasmmqj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbqttbjl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gtwmzfekgc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtzjsvwxld.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gtapjywknv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtxtozeuwc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gtkbiynmgv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gttnojiaip.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzmntyoe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtsdxgjfmv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gtuvisklov.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhgvcvzv.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtqxdxafqa.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtjvbzghaa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gtevxfhhqd.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtyqzurmqg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtznknwfsi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gtnfspqkkx.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtoephtdxn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gtxeetoqbm.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gttzeitjcu.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtcpevmqyy.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtsbkjngnj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daxiang520.top/Article/details/gtkmnfeibn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtwfjbpnoc.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gtudsenaao.html

C#:   list.Distinct().ToList()
来源：http://dali.aibaodan.cn/Article/details/gtweakjirl.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaithjinn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gtfqbmowjc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gtasxlodwj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzwokpkt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtlsqcrfpn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gtsmybuwfe.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gtyzkabgyw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtviwybqkq.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtkuiabnsn.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtzdjkjrga.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gtjgkgehhy.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gtkqinhoty.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtltwhakxg.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gthcmhlqbb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtiseyiegq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gtoyjfagpf.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gtlqcqcvww.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gtgcymcxov.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtbcghksgt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gtznlmqvmt.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtadjqubhg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnxiangtu.top/Article/details/gtqsxeienj.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtzcoqkghi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gtdtrqrzad.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gttajsumpu.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gtvjikrmyg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtpksxlwnd.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gtldqhfktz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtklrpjcvb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gtfokljexd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tanke756.top/Article/details/gtytxjqopy.html


<!-- 参考信息 -->