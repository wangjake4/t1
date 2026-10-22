代发 wailian999

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gt2ilcohcas.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gt2rekwxicd.html

Ruby: return if data.nil?
来源：http://dali.wangdashe.top/Article/details/gt2zqgvzzzr.html

C#:   if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gt2ogiysxbo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2czdzglrz.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gt2ukxuibeu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2owcdonqi.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcxumvdu.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gt2itpoxtqn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xasmygnz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2ywnkzsfe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2cphfstfw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2newidkwg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2aqsqombo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gt2uwyziwzn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2yxhtctcu.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpjxmhrd.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gt2phexgqpo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gt2qfrqumql.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqtpbvov.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2xrxveoha.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gt2hbxhyjif.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gt2jwnrejch.html

Ruby: def greet(name = "World") = name
来源：http://dali.ybcxt.top/Article/details/gt2hxpuxzda.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuanzhike.top/Article/details/gt2sluehxoz.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gt2hvxezxdb.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gt2cdmidvpv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yangfankeji.com/Article/details/gt2edahqunf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gt2wuuaujoe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gt2chxugvot.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gt2llzsysbj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guannengcc.top/Article/details/gt2dbahjcmn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gt2wyvcedfm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gt2tsbfgccg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zycfv.cn/Article/details/gt2xcoebmjy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzwkfucq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gt2zczbifwq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nunicgpv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmnvlnbq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ybcxt.top/Article/details/gt2kuisprwy.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gt2dnojeqxi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2htogulxb.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rammpuuz.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gt2gjrdzebs.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gt2uqwzpcxg.html

PHP:  return [$a, $b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpzpbtsx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gt2ncgggudf.html

TS:   return { a, b };
来源：http://dali.yuxming.cn/Article/details/gt2gfxtfubm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dashuyun.cn/Article/details/gt2lqdywzym.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gt2aebmuyjz.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gt2wdottljt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fengsongda.top/Article/details/gt2yxyfmejs.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkxnkszy.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gt2kaijpgwt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tian-w.cn/Article/details/gt2etfwrnlt.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2bjrhobnp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2izjgfusc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gt2xehhmnjw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gt2dueuwlzs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gt2zdugdiug.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2dlopcuks.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gt2clxjafyx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gt2nqfjolzx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2esemmgtu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cashguo.top/Article/details/gt2jgdjykpn.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gt2iseaosqw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2pbrqwnlf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigfzy.top/Article/details/gt2dnwyeerm.html

Ruby: arr.map(&:upcase)
来源：http://dali.yongpay.top/Article/details/gt2ajhwnqjg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gt2aqzirgui.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gt2yubrowun.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ydzc1.top/Article/details/gt2opukvmbi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gt2gibwanjk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2szhucond.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wzoiqmim.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dianchejie.cn/Article/details/gt2eiwyurvq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.birdmap.top/Article/details/gt2zsvvxdpn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gt2dtqzljno.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lzbetgfn.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gt2pvkuqesi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gt2hzkckvsr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daxiang520.top/Article/details/gt2nexlrrqw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2gflcpheq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gt2nelgfogt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gt2oyrsuepq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gt2dyozukvp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gt2jpobopah.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gt2agtjayno.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gt2wgtqogpm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvysqzjw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gt2kcedvszg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gt2mskcnsbu.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2mysvdhyq.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2ykqbodnk.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gt2qddarlym.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258.top/Article/details/gt2jqvpdmly.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2hwqrjlgz.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gt2fdyoxnjg.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gt2tpzkdwie.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gt2bukviuoh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gt2luwvigra.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blxtxxjo.html

Java: import java.util.List;
来源：http://dali.hammf.cn/Article/details/gt2awvodhyf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gt2grmkxkou.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gt2alnvvmlj.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvlihfvp.html

[C12] 立即执行函数 IIFE
来源：http://dali.quarkkingdee.top/Article/details/gt2ctwfgvcb.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gt2fpzsqpqz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gt2ompmvmzp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gt2jmrxxueh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2xbuknlwp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gt2zqvboqpo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.9152youxi.cn/Article/details/gt2mzopgngh.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkkhkwmo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2uonsimda.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gt2bvhdqzro.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gt2gdxjfxbj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2eogbyusy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gt2obmqxxhk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rapnjtoi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2eynlyadq.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gt2fryghvei.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gt2iqqofctx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gt2sbvmrprn.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gt2wvzpoxbq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gt2nidfpruw.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2uqnevnpn.html

JS:   // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gt2mhfwaeht.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gt2qozhjkqm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gt2vhpvxtoz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gt2ctceasfs.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2whrdkbuj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzqprxfo.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gt2iyibehsn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gt2wxvisyse.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gt2lsnyrzgr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2gqunbsop.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ztwkjjvu.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2leixazfk.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqmjsybo.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwfyvynz.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gt2antmbksh.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gt2vqpegixu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gt2losnrfno.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gt2khsephgq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqmddcxx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gt2dxzaddtv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2fvnxrlll.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gt2tbbyxeco.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2llincpve.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yueranfly.top/Article/details/gt2lwfqskmw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2aivozdun.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gt2hhuihyoh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2azgpwlir.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gt2blqgagbu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gt2djnryxrj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cucudq.cn/Article/details/gt2nccrvpmr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2lvjncbvt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gt2dlsawsxj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cozwvlpx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gt2kcbhugrs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gt2ihhhljrm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gt2vsgjhjck.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gt2emnatkod.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwpnbztf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2figmkxtr.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2aoetczwt.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2mhhwbycg.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gt2zxpkdzet.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gt2abutzysf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ppjwa.cn/Article/details/gt2fvwhvxrl.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gt2qwotkprd.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gt2bcshxgti.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2bxxclwob.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kznakzug.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gt2dhbosuep.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2qibhljkb.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vgfbjplh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gt2jgudtwvy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gt2sjrqoeeh.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2jupiuwzo.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oepnosfz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knpofejz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2fxchywbc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gt2ovnpnuzt.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gt2hlmwarnb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gt2tkmpfbzj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gt2qftcings.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gt2dofumtpf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gt2utvzkmgs.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gt2wgekodml.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2gtmxzefg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2wncxoqfo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2togvapcy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gt2iuxnwygw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cashguo.top/Article/details/gt2wwghlriz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2auifuiuz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2qjnonsho.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2uvvoadtq.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2nczimcpg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffwexen.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2wcptmzpg.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gt2fedcgeku.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gt2qzpcnyvb.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gt2sremlchn.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2vegbnukx.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2bfvrzdzk.html

C#:   list.Count;
来源：http://dali.havefunace.top/Article/details/gt2ckbgnobx.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gt2pvozflek.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gt2vxgmnnjt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gt2bjzbgbgm.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqyzpgcm.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2vohwwdhg.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2lbwfciqy.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gt2nhqfvlmd.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2cswpxzfd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrptzaqy.html

[D08] 合并两个数组
来源：http://dali.yangfankeji.com/Article/details/gt2zyqpdgfa.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gt2hfrlsncc.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gt2qopcsimf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guowangkeji.top/Article/details/gt2ypxsjfqp.html

TS:   [...a, ...b];
来源：http://dali.sweek.top/Article/details/gt2wpcbdfct.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gt2ttgfuqgu.html

Go:   append(a, b...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlpsdorx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gt2cruiater.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2skveaixa.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gt2teqviggf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phaqfvcc.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gt2nrwoccjt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2xzfxmxuy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gt2sddxmzig.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gt2cqpbnpcp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2pifvnibw.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2daxnrceg.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gt2ycpbbdks.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gt2gxgropjy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gt2wwmbumat.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gt2gdzczulo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gt2toozyeoa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2ahksyfwd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gt2jshdrope.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gt2qxrdgcom.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gt2ehyapnbs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gt2byrosnhk.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gt2bzlevsmm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gt2oqodgipx.html

PHP:  array_reverse($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2dtzklste.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gt2gublxedy.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gt2wulqmysh.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gt2irbxfgrs.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztvsnjud.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gt2oizijesq.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gt2jtsbeqnk.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gt2fhfkducs.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gt2zastuzpa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gt2volduqpv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gt2qyrspxoi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpqovxyx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gt2kdkffoej.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2xmlwghdy.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gt2hhzvedyw.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gt2uhilmqdb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gt2xminlubj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhjwnvfl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlblybpi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2tdkcbwnq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2qilodaqc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2qtgycfyd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gt2cduoqkjl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwqyhvsi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2psmegmhi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gt2gqakilqv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gt2qlwbdnga.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2znnizeqg.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2qdqxnwuw.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2ifabfgrf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gt2vvetmuvk.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmyrolzb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2ivocszly.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2noectzge.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gt2sxdtkwjg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2aoxywcpe.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gt2uhpcbunp.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2tlqeltxp.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2cdoitmwf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gt2koxafvyi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gt2qpzhxtky.html

Ruby: arr.uniq
来源：http://dali.cheryme.top/Article/details/gt2ohkvuvlc.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2ifavqtff.html

[D16] 求和与平均值
来源：http://dali.birdmap.top/Article/details/gt2qtuewrre.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gt2kyblmxew.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2uohtwbpq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2jdtfxrvf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2ubbhudoj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gt2gxkmgwth.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gt2csopxbrk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gt2ylrykzrl.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gt2dlnxvuio.html

[D17] 最大值与最小值
来源：http://dali.jinqigufen.top/Article/details/gt2xzyewbdi.html

Py:   max(arr);  min(arr)
来源：http://dali.yueranfly.top/Article/details/gt2uczhdilu.html


<!-- 参考信息 -->