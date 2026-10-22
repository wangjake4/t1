代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.hammf.cn/Article/details/gt2cpypnouq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2ivwhndyj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2vrvcyrcu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxboiukl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2acorbvov.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gt2xotdxjrd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cucudq.cn/Article/details/gt2fjhcyerq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2fjleawnw.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2qspqjqyo.html

Py:   def greet(name="World"): return name
来源：http://dali.cdnleiting.top/Article/details/gt2zynpmftt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenzaomai.com/Article/details/gt2lexnfmzu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gt2liwqeoyk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2gracsgbu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gt2izaocsxg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhttmgom.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gt2nfobyxfl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gt2fgpbflmn.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gt2ojxbpmlv.html

Py:   def total(*args): return sum(args)
来源：http://dali.cdnleiting.top/Article/details/gt2kgxntami.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gt2bgsnpghg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2mgofbjqo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2ykxuhouv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gt2oovquyvk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gt2zkrhvnbl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangdashe.top/Article/details/gt2vnkdacet.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gt2zgdmjtlu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gt2otouruch.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehyyogbz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gt2fwcgpngn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gt2uhkwckzq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gt2akefjudu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gt2dhepuyth.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gt2wthnazqe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2lhekmdeg.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2kkubygpn.html

[C05] 返回多个值
来源：http://dali.andypj.xyz/Article/details/gt2sfftidnk.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2lbjjxcfi.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gt2sksladaq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkrywcqv.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gt2ezuqnzsx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yonumen.top/Article/details/gt2ykscoyns.html

Go:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uejxevoe.html

Ruby: return a, b
来源：http://dali.gogol.net.cn/Article/details/gt2kslkftvo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whjxwpvo.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gt2ccrijmfb.html

Py:   square = lambda x: x * x
来源：http://dali.sxryk.cn/Article/details/gt2hssrumdc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykfhknss.html

JS:   const square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gt2eidnfumo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.smart0.xyz/Article/details/gt2zwskjecp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gt2tneyddjr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gt2qwpmabxj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gt2zpzjvcxv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2vrtjbybe.html

[C07] 把函数作为参数传入
来源：http://dali.yanxiufei.cn/Article/details/gt2xfymwihw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gt2codkyytu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2mntpjpud.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.birdmap.top/Article/details/gt2ipcvxbvg.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gt2xmuxnhzp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2hwhnyyrf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pengpengdd.cyou/Article/details/gt2usyojhkv.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgohyavn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqalopsz.html

[C08] 闭包
来源：http://dali.iojbl.cn/Article/details/gt2mktbqapg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gt2ichqihkf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ubcjouua.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nokuciem.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2mtncpqfp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gt2xiqrnsxz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gt2celbziad.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gt2athycgwp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2fafjznej.html

[C09] 递归
来源：http://dali.nwbrower.top/Article/details/gt2chgptczc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gt2ogqcwfhg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gt2mvarumrc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gt2oskwaoox.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gt2umojyaso.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gt2xjkrltme.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gt2crieeswo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gt2xohvnbkm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gt2ecycnmop.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2hejsjiwq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gt2ucqwhrjx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gt2qlpztnmu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gt2vzmpabug.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2lirykzwz.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgxxmpzp.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2scgviaga.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gt2khecripg.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2fmjrtqos.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gt2mvsiidug.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gt2ygamojqn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gt2nxtgnrgh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gt2kzqeciun.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnqzz.top/Article/details/gt2auabvorh.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gt2tjgrbqxh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aizwys.cn/Article/details/gt2ensjpdkx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gaohongyu789.top/Article/details/gt2pmcevfyb.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gt2tpwzpjrz.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gt2njjnxjzs.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gt2qqccezzt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gt2plpojfia.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gt2fgyopczg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gt2butyhibs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gt2duqttjjj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gt2kgwpkyip.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qotjefhh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gt2iddewowm.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouwfbish.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gt2vindasnx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmhllqas.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gt2guagrkoq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2ghmowlvr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2lapcaivo.html

Go:   func add(a, b int) int
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufinwnma.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gt2oamzgjws.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gt2hdfcfbxy.html

[C14] 泛型函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksmrdqfa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gt2aygdwcvj.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2kovebobk.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2vvwasnlt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gt2vmhmgzxy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gt2rnwxgsvh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lubnhocd.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2sdkjoyrv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gt2oiyhkqih.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gt2obegqdzs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gt2rupqktjd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gt2pkxszcik.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gt2dxzikdei.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2mwisaarn.html

Java: // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2rdlgzuiq.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gt2qlpvsbpc.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gt2lirbjzgv.html

C#:   var (a, b) = pair;
来源：http://dali.zycfv.cn/Article/details/gt2klmxxfbt.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gt2avdgspla.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gt2knlnsodv.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzlnktte.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gt2xxskklnj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gt2avpxzhah.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gt2dwhfticd.html

Go:   // 无重载：用不同函数名
来源：http://dali.jyoumei.cn/Article/details/gt2xuhillvw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xylfe.cn/Article/details/gt2oyrcafnc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ylsoxjxd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2hbwedkll.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gt2gmmahspk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2mowxkctg.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gt2vyppmscj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjnltlrf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2prstwsmd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gt2mlhxdbhv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gt2tjqcjtdi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gt2lfgcblcp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cdnleiting.top/Article/details/gt2yvbllepk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gt2yxvwzxlj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gt2grnijwfu.html

[D02] 追加元素到末尾
来源：http://dali.hnxiangtu.top/Article/details/gt2kmfzmpbv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gt2ljqrhjzl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gt2qochuvkl.html

JS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gt2qboniyja.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gt2qqnofred.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gt2rvuxsjgm.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2rhqdiney.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gt2xnppfknl.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gt2ybvxwaqf.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gt2nwfkoqhw.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnjfojan.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gt2khhwypoq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gt2tzyrhjpm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2kymaaljf.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2buhnytbn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivkopuvf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gt2trjlsfzl.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gt2bjjyzake.html

[D04] 删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbpkcpxr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gt2uwimaywr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2dthbdkhr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ujokjtos.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2pflkganu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gt2zrpdaewp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gt2kjvrakwe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gt2xwomuuvh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hammf.cn/Article/details/gt2dvoauiwa.html

[D05] 访问与修改元素
来源：http://dali.ppjwa.cn/Article/details/gt2zibvtfxk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2sueprrir.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2xojuizui.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2xbxjoehb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gt2gywjlmhh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gt2iukuxqdp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2ailfttnv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2aejocqwg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2sqzfemoi.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2lnlnvaem.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2yrinzmal.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2glaxhyoh.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2ybcaioov.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2zzeidhyb.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmtzzqkh.html

Go:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2oezyzocv.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gt2orldubiv.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gt2nqxinhlb.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gt2lpdszmfy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gt2vmmwhbaf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2khxrzepm.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gt2azzvzjss.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2zvagixuk.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2qidqbggv.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gt2ymgvcqfk.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gt2bwrgfkae.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2mltgcyco.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gt2inmobfcw.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gt2jdhrxzxa.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gt2mrlicdxy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgnxxwse.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gt2ldewzlsd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2hatacdmv.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gt2suyscmmu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gt2qtrftcsr.html

C#:   a.Concat(b).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2jwsbpyqm.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gt2jilpcmeu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gt2dtntytmf.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gt2pykjzhhn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqetmqqk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.havefunace.top/Article/details/gt2ddnszkdl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlquaytm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2wjyaxkfj.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2mehoekyr.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gt2ixphyfga.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gt2zscpzdka.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gt2snnwoqge.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gt2kotqnvby.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kynbuvap.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2rnjptuct.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.316326.xyz/Article/details/gt2zhkgrhdu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gt2fafvspbj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gt2fwvjevfk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gt2mlrfvvjl.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2obaitrst.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gt2dkspbstl.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gt2qaaqpduk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gt2exzcbyqv.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gt2oqifzkln.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lufcjwcz.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2gzlpgasm.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkfhfyyu.html

C#:   list.Reverse();
来源：http://dali.birdmap.top/Article/details/gt2omkmkgbu.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gt2hlhztoyf.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gt2nmbmzepb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzzzxnus.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2eivjcwxv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gt2wmtmiwvu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jianghu66.top/Article/details/gt2uufidsrw.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2hvvxfael.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gt2putpuhwe.html

C#:   list.IndexOf(x);
来源：http://dali.hnxiangtu.top/Article/details/gt2fzafkkqi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gt2irpheanm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gt2ghoywves.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gt2thsvfbpc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gt2vqsewmrq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2vsqmhohg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2lijwjlph.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2mbyxatlx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gt2uohbfuvc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2hqvssxni.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gt2jzcghsba.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gt2ztojlamq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2vqrwxbnq.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2buggvssz.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2ueboggvo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuvelqo.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2viwbgfuy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2oarmiuiq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2qmavnhpo.html

[D15] 去重
来源：http://dali.jinqigfzy.top/Article/details/gt2xrtkznmb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gt2cjerghoa.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gt2ztrcxwha.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gt2qqwboscs.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gt2aczzvdra.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gt2lbulxnuw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jepobsyg.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gt2otyously.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gt2jhmptsjk.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gt2emklbzog.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gt2hqfdzkei.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gt2zyqdnlcj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgcosplr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqtqlgov.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gt2vrntcbqp.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gt2ebcmacee.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gt2govjaqwa.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gt2chsautjy.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gt2hpaebhdv.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2midudvve.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2phkygksq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gt2urwskmdi.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2hcqrmqpd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gt2jczolreb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gt2xutxecub.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gt2rfpnikat.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gt2agzvxvnq.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gt2ssrshrpf.html


<!-- 参考信息 -->