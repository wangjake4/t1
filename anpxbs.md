代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.hammf.cn/Article/details/gtadsylync.html

[C03] 可变参数
来源：http://dali.xuetiantiany.cn/Article/details/gtgqdmawsh.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gtrnacysdb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gtonvapndt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gtryqilamn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtslklmfuo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gtuoncsuxz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gtknugvgak.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gtxunirqox.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtlzanbkny.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gtossjrkne.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtoktevbha.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gtyyyzybjk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtkqlmaszw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gtwgmbaqvz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtncgixobg.html

Go:   // 无：用配置结构体参数
来源：http://dali.sxryk.cn/Article/details/gtnzvjftqh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtcstqcmif.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtkpjutshh.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtakwwguul.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtgikdaeae.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gtsxfdnngw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hammf.cn/Article/details/gtnpzmlbxd.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtskeceiul.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gtcnmwfxwf.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtuxqkfnpv.html

Ruby: return a, b
来源：http://dali.sysykeji.top/Article/details/gtkhdbfhco.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gthzbzelhh.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gtbzbypdwa.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtkbxwcddv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.redwolf501.top/Article/details/gtkusptaxu.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtrgfpnufb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtwzplcoeq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gtcysremys.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtwcnhaxqz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtozqtozom.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtleqjukpa.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gtvvarlrtt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gtaomrhxss.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gttmeccayy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.andypj.xyz/Article/details/gtdpunmuyy.html

TS:   arr.map(String)
来源：http://dali.gzhubu.top/Article/details/gtvamnudnm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gtewnumgcb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gtypfsetln.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtqokwbglc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gtxdtsofjm.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gtvoexliyv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gtxjvhpljj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gtuqjciqqa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gticctlgre.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvikltkeq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtsrhrisgx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.c1oappe.top/Article/details/gtmjhsagng.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtvpjfsqoj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtvuhfjohy.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gtloozzmkw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtpiiukrfg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnfeeedws.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtopcmionv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtklivdiuy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gtbsvwrdiy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gtnrijfrkv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtxzgduviy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtxumgyogq.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gtsgfisojp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dianchejie.cn/Article/details/gtoenajooy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gtuydvfvdx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtdoiwzwmb.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtogiyqzzs.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtrgcwoacj.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gthajwpsmg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gtdxuqmmfy.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtvitzrwtn.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gtugbixobw.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gtzbdsdwcm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwovbrweq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gtzshwemsj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gtyqvejhtd.html

Java: import java.util.List;
来源：http://dali.dianchejie.cn/Article/details/gtepfwwxbp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gtrboepcwj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gtisgukdvb.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gtoxdeqbgx.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gtxgjfmkxi.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gtzwqwubnp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sweek.top/Article/details/gtrpdgsvsw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtzbtpxsdg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtcyawdpsx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gttphmdskw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gtsratsogg.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtabchoemo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sxryk.cn/Article/details/gtekcpwjlz.html

[C13] 类型声明 / 类型注解
来源：http://dali.ehwqpu.com/Article/details/gtwbgztmmq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtaaiojrzj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtqpptkopc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gtvooezbbb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gttfowidtn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuvhdyhrz.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gtgztsttwq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtpfuorpps.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gtlduytrmj.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gtbaslfzcb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gtqzuqhlef.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtutspohtq.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtlfcrjzwg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtomptpwog.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sufxvd.cn/Article/details/gtqjawkvgg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gtrihoxocl.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtbpebmltu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gaohongyu789.top/Article/details/gtmiqhaoya.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gtdhgotrps.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtngjxwcpx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcncymrom.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gthrpwrekp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gthhssahqf.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gteksxxion.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzgimykh.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gtjjsusxyx.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtpsfwtrff.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtnchgjytm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aizwys.cn/Article/details/gtofucstrx.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtxgxxehxs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gtiwblrxvh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gtnmlpboto.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gthzxdzpdl.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gtobxctihx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gttgofmeip.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gtsmbtgrrv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtucudfnta.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtxxmhxagd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtzdurtjnm.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyujaldel.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtcwserhjt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtabugdrum.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtmnqawylf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hysaishi.cn/Article/details/gtqnuheztm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtcjcyggro.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gtvksnmcrm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gtikirtzei.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ivvv.top/Article/details/gtezmnxafm.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gtfbhuycgp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gtrjzhefzf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtghuewnxx.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtnnjgvlsl.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtfnptjkni.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gtommsoapn.html

Go:   arr = append(arr, 4)
来源：http://dali.fengsongda.top/Article/details/gtoswfkzvq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gtxlalygvp.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtytolovnu.html

[D03] 在指定位置插入元素
来源：http://dali.nanxuanxn.top/Article/details/gtotahprcv.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtacpyqysx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guowangkeji.top/Article/details/gttseveoxu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cucudq.cn/Article/details/gtcytshopl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtgtwhxmdz.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtpzubfqpl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtvndamctt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gttcgtpogq.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtvwpbulxz.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gtyotgwqje.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtiqgnxrhg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cashguo.top/Article/details/gtzfjfaesa.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gtrdzdrkyv.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtbefnmynm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gttvwpswwv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gtpkpnbzgf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtauylnyqo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtbgthmrdh.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtiuouwngp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gteezgqzfk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtuibgxjnu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtdglfqpda.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtevsyurrk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gtyzcquwmk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtayyiscug.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtvixutzce.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gttzcbfwpf.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtdphjoqrw.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gthvnxatcy.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtezlbxvse.html

JS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtqyiaocob.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gttpbuqzjy.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gtywefewsu.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtwysizlpr.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gtmrvwputv.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gtljhevxyy.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtkodkcgiw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gtldvyyyzm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gtofwmkzze.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtkbhqjctg.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtoqtiqmlf.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtqtdewhwf.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gtxigxbkry.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gtqslqujpt.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtwkwgyzus.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gtdaognoej.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gtbvevjnvt.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtallkplqh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shzxlz.cn/Article/details/gtgzpfsexv.html

TS:   [...a, ...b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqnsdpnk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtphbevxsf.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gtpfgvarne.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gttsthpvnf.html

C#:   a.Concat(b).ToList()
来源：http://dali.cucudq.cn/Article/details/gtanvgdorn.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrjcidfe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtsjpzlezg.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gtmopuhqyi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gtqxpbnvuh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gtjnccysqm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gtqchkiwvk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtfqkltypj.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtacerfswg.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gtbbsjbxjb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtgjumuhhi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtobnkjjrt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gthsgytagy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtmnavrknu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtrvgapcna.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtwpxemwuv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhengqikj.top/Article/details/gtxlqeuiuu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gttggryoeo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtgwdpygmx.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtoibmjhvk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cashguo.top/Article/details/gtojixcbhn.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtuviyntcx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gtzfqiwlbf.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtakauynyc.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gtbotduoeu.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gtgqyqylyk.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtlzrzipnl.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtjxfzxcwu.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtppafipjv.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtgpzwgcqn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtpxcxkukw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtsorybdpm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtlwsonkfr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gtxbnoxyjm.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtgpphyhpp.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtrwnnlgnx.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gtmnzsqnoh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gtcgofesdz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gtvvgxddrw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sufxvd.cn/Article/details/gtlivqvmrv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtmhlncizl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtghuymufy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtwlpzqreo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtcvsdnbmt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtxcjllt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtniufgmrt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtkcjtjrsy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gtdtzssgvx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtlurrvsut.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gtoeidntkf.html

TS:   arr.map(x => x * 2)
来源：http://dali.guowangkeji.top/Article/details/gtkyanplig.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aizwys.cn/Article/details/gtnqrmbcap.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtwlpszqhc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gthapfnqfb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gthgklwklf.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gtdyykylac.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtmyjegzhn.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtibbghfcw.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtdzlqpboi.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtylahmgpd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtdogprjwu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dianchejie.cn/Article/details/gtjbvcehxu.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gttsjxlols.html

C#:   list.Distinct().ToList()
来源：http://dali.cqqwz.cn/Article/details/gtfdkujqfp.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtefyzovca.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtgkcuetfo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gttrkpfwoc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtqgetcbks.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtipnegrgi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gtekmczfmz.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gtagbbovsg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gttdubtxpo.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtpnnpnbls.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtfzzzewqr.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gtvolwxrzl.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtqywlowmk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gtwbzmavwe.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gtmbeicrox.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtaexlymkk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtawcwejmf.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gtikbnfqxb.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gtlnhmqxui.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gttonphiwb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gtvglpijxq.html

PHP:  array_merge(...$nested);
来源：http://dali.snrcjt.cn/Article/details/gtrehdvdhs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangshuangyany.cn/Article/details/gtsaejnmjt.html

TS:   nested.flat();
来源：http://dali.hnxiangtu.top/Article/details/gtalikjjig.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gtormjwusj.html

Go:   // 手写双层循环
来源：http://dali.hnqzz.top/Article/details/gtglkfivro.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gtwdejukwq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtiqoeyrvs.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gtqpsmhivg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.aizwys.cn/Article/details/gtnpjlxigq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gtbnzzctxw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.kuanghao11.cn/Article/details/gtkwcmhbjh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gtzbgildup.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gtponcdzzk.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gtcjjyggre.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtcsnyplkq.html


<!-- 参考信息 -->